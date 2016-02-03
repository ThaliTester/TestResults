#### Test 58135655c662d33_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 5133): TimaSignature is unavailable
D/ActivityThread( 5133): Added TimaKeyStore provider
E/SystemInfo( 5111): [SIOP LEVEL] : 0
--------- beginning of system
D/MotionRecognitionService( 1015):  ssp status : false
D/Mms/ComposeMessageFragment( 4843): [end]    fillCache consume time = 166.841302
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/DocumentService( 5111): [BEGIN SYNC] DocumentService beginIndexing :16
W/ResourcesManager( 5133): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5111): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/File    ( 5111): fail readDirectory() errno=13
E/File    ( 5111): fail readDirectory() errno=13
E/SmartCardContentProvider( 5133): onCreate
I/SystemInfo( 5111): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5111): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5111): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :57
E/DocumentService( 5111): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5111): [INDEX] Total time taken for each file :0
I/DocumentService( 5111): DocumentService onDestroy start
I/DocumentService( 5111): DocumentService onDestroy end
I/DocumentService( 5111): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 5111): InterruptedException: null
I/SystemInfo( 5111): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5111): DocumentService cleanupEverything end
I/SmartCardBroadcastReceiver( 5133): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 5133): Broadcast received for locktype changed 
I/Process ( 5111): Sending signal. PID: 5111 SIG: 9
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Mms/BubbleViewCache( 4843): fillCache bubble = 1
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/MediaStoreImporter( 4561): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
E/Zygote  ( 5158): MountEmulatedStorage()
E/Zygote  ( 5158): v2
I/libpersona( 5158): KNOX_SDCARD checking this for 1000
I/libpersona( 5158): KNOX_SDCARD not a persona
I/SELinux ( 5158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5158 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/lowmemorykiller(  254): Error writing /proc/5111/oom_score_adj; errno=22
I/ActivityManager( 1015): Killing 4623:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
I/SELinux ( 5158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 4706:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5111)(adj 11) has died(137,1128)
D/TimaKeyStoreProvider( 5158): TimaSignature is unavailable
D/ActivityThread( 5158): Added TimaKeyStore provider
D/PopupuiReceiver( 5158): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1015): uri = -1 selection = getSealedState
D/SecContentProvider2( 1015): mCursor = null
I/PopupuiReceiver_KNOX( 5158): getSealedState : true
D/SecContentProvider2( 1015): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1015): mCursor = null
I/PopupuiReceiver_KNOX( 5158): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1015): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1015): mCursor = null
I/PopupuiReceiver_KNOX( 5158): getCheckCoverPopupState : true
D/PopupuiReceiver( 5158): Action cable connected ! on - 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.powersharing, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1015): failed to open /acct/uid_10010/pid_4623/cgroup.procs: No such file or directory
E/Zygote  ( 5173): MountEmulatedStorage()
E/Zygote  ( 5173): v2
I/libpersona( 5173): KNOX_SDCARD checking this for 10122
I/libpersona( 5173): KNOX_SDCARD not a persona
I/SELinux ( 5173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5173 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/SELinux ( 5173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_4706/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5173): TimaSignature is unavailable
D/ActivityThread( 5173): Added TimaKeyStore provider
W/ResourcesManager( 5046): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5046): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5046): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5046): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/PowerSharing.BatteryReceiver( 5173): onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.wluc, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5188): MountEmulatedStorage()
E/Zygote  ( 5188): v2
I/libpersona( 5188): KNOX_SDCARD checking this for 10165
I/libpersona( 5188): KNOX_SDCARD not a persona
I/SELinux ( 5188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5188 uid=10165 gids={50165, 9997} abi=armeabi-v7a
I/SELinux ( 5188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4752:com.sec.android.diagmonagent/1000 (adj 15): empty #31
E/SELinux ( 5188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5188): TimaSignature is unavailable
D/ActivityThread( 5188): Added TimaKeyStore provider
I/PolicyManagerBroadcastReceiver( 5188): onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
I/PolicyManagerBroadcastReceiver( 5188): onReceive: width = 720, height = 1280
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5203): MountEmulatedStorage()
E/Zygote  ( 5203): v2
I/libpersona( 5203): KNOX_SDCARD checking this for 1000
I/libpersona( 5203): KNOX_SDCARD not a persona
I/SELinux ( 5203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4735:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 5203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SensorService( 1015): [SO] 0.019 0.096 10.113
D/TimaKeyStoreProvider( 5203): TimaSignature is unavailable
D/ActivityThread( 5203): Added TimaKeyStore provider
D/AssistantMenuSettingSearch( 5203): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5203): Make Setting DB
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5218): MountEmulatedStorage()
E/Zygote  ( 5218): v2
I/libpersona( 5218): KNOX_SDCARD checking this for 10150
I/libpersona( 5218): KNOX_SDCARD not a persona
I/SELinux ( 5218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5218 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 5218): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4752/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_4735/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5218): TimaSignature is unavailable
D/ActivityThread( 5218): Added TimaKeyStore provider
W/ContextImpl( 5203): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1015): Killing 4300:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/ActivityManager( 1015): Killing 4080:com.policydm/1000 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1455): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1455): addSearchInfoDB
I/SettingSearchManagerReceiver( 1455): endInsert
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5234): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5234 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5234): v2
I/libpersona( 5234): KNOX_SDCARD checking this for 10101
I/SELinux ( 5234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5234): KNOX_SDCARD not a persona
I/SELinux ( 5234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5234): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5234): TimaSignature is unavailable
D/ActivityThread( 5234): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_10125/pid_4300/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4080/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5234): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5234): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5234): Observing account changes for notifications
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager( 1015): Waited long enough for: ServiceRecord{36da3241 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 5234): Error finding the version of the Email provider.....
E/Gmail   ( 5234): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5234): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5234): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5234): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5234): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5234): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5234): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5234): We do not support migrating this version of the Email provider.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5234): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1015): Killing 4577:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5270): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5270 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5270): v2
I/libpersona( 5270): KNOX_SDCARD checking this for 10033
I/SELinux ( 5270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5270): KNOX_SDCARD not a persona
I/SELinux ( 5270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5270): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_4577/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5270): TimaSignature is unavailable
D/ActivityThread( 5270): Added TimaKeyStore provider
E/SMD     (  293): DCD OFF
D/AndroidRuntime( 5252): 
D/AndroidRuntime( 5252): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5252): CheckJNI is OFF
D/AndroidRuntime( 5252): readGMSProperty: start
D/AndroidRuntime( 5252): readGMSProperty: already setted!!
D/AndroidRuntime( 5252): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5252): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5252): readGMSProperty: end
D/AndroidRuntime( 5252): addProductProperty: start
I/art     ( 1015): Explicit concurrent mark sweep GC freed 233954(8MB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 46MB/62MB, paused 3.818ms total 271.545ms
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 5234): (283) recovered 28 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 5270): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/AffinityControl( 5252): AffinityControl: registerfunction enter
W/ResourcesManager( 5270): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/File    ( 5234): fail readDirectory() errno=2
I/Gmail   ( 5234): notifyAccountChanged
W/ResourcesManager( 5270): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/AndroidRuntime( 5252): Calling main entry com.android.commands.am.Am
I/Gmail   ( 5234): getAccountsCursor
I/Gmail   ( 5234): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5234): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5234): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5234): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5252): Shutting down VM
I/Gmail   ( 5234): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1015): Killing 4777:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/art     ( 5252): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1833): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_4777/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1833): No location to return for getLastLocation()
,W/FusedLocationProvider( 1833): location=null
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1627): Explicit concurrent mark sweep GC freed 4448(187KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 773us total 34.025ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5319): MountEmulatedStorage()
E/Zygote  ( 5319): v2
I/libpersona( 5319): KNOX_SDCARD checking this for 10104
I/libpersona( 5319): KNOX_SDCARD not a persona
I/SELinux ( 5319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5319 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5319): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5319): TimaSignature is unavailable
,D/ActivityThread( 5319): Added TimaKeyStore provider
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/ResourcesManager( 5319): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 5319): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5319): MmsConfig.loadMmsSettings
I/Babel   ( 5319): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5319): MmsConfig.loadFromDatabase
,E/Babel   ( 5319): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5319): MmsConfig.loadFromResources
,E/Babel   ( 5319): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5319): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5319): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5319): App launched.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 4167): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5344): MountEmulatedStorage(),
E/Zygote  ( 5344): v2
I/libpersona( 5344): KNOX_SDCARD checking this for 10035,
I/libpersona( 5344): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5344 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,I/SELinux ( 5344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5344): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1,
W/QCamera2Factory(  282): getCameraInfo: X
,I/art     (  319): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.091ms total 31.300ms,
,D/TimaKeyStoreProvider( 5344): TimaSignature is unavailable
,D/ActivityThread( 5344): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 17.077ms
,W/VideoCapabilities( 5319): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5319): Unsupported mime audio/evrc
,W/AudioCapabilities( 5319): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5319): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5319): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5319): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5319): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5319): Unsupported mime audio/qcelp
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 734us total 19.196ms
,W/AudioCapabilities( 5319): Unsupported mime audio/evrc
,W/VideoCapabilities( 5319): Unsupported mime video/wvc1
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5319): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5319): Unsupported mime video/wvc1
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5319): Unsupported mime video/mp43
,E/SPPClientService( 5344): ============PushLog. commonIsShipBuild. stop!
,W/VideoCapabilities( 5319): Unsupported mime video/sorenson
E/SPPClientService( 5344): [PushClientApplication] Push log off : This is Ship build version
,W/VideoCapabilities( 5319): Unsupported mime video/mp4v-esdp
,D/SPPClientService( 5344): PushLog.txt file is not deleted.
,D/SPPClientService( 5344): PushLog.txt file is not deleted.
,D/SPPClientService( 5344): ============PushLog. stop!
,I/VideoCapabilities( 5319): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5364): MountEmulatedStorage()
I/libpersona( 5364): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5364): v2
I/libpersona( 5364): KNOX_SDCARD not a persona
I/SELinux ( 5364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5364 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4245:com.android.providers.calendar/u0a42 (adj 15): empty #31
E/SELinux ( 5364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1015): Killing 4343:com.android.calendar/u0a135 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5364): TimaSignature is unavailable
D/ActivityThread( 5364): Added TimaKeyStore provider
,E/SPPClientService( 5364): ============PushLog. commonIsShipBuild. stop!
E/LNoti   ( 5364): [PhoneStatusChangeReceiver] This device doesn't register yet.
,E/SPPClientService( 5364): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5364): PushLog.txt file is not deleted.
,D/SPPClientService( 5364): PushLog.txt file is not deleted.
,D/SPPClientService( 5364): ============PushLog. stop!
,W/ContextImpl( 4812): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5319): Creating RTCS
,E/Zygote  ( 5386): MountEmulatedStorage(),
E/Zygote  ( 5386): v2
I/libpersona( 5386): KNOX_SDCARD checking this for 1000
,I/libpersona( 5386): KNOX_SDCARD not a persona
I/SELinux ( 5386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5319): Destroying RTCS
,I/ActivityManager( 1015): Killing 4477:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5386): TimaSignature is unavailable
,D/ActivityThread( 5386): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5386): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_4343/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_4245/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4477/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 5386): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5386): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5386): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1015): Killing 4795:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,I/DBG_DM  ( 3130): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5401): MountEmulatedStorage()
,E/Zygote  ( 5401): v2
I/libpersona( 5401): KNOX_SDCARD checking this for 10135
I/libpersona( 5401): KNOX_SDCARD not a persona
,I/SELinux ( 5401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5401 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 5401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5401): TimaSignature is unavailable
,D/ActivityThread( 5401): Added TimaKeyStore provider
,W/ResourcesManager( 5401): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5401): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1015): failed to open /acct/uid_10157/pid_4795/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5422): MountEmulatedStorage(),
E/Zygote  ( 5422): v2
I/libpersona( 5422): KNOX_SDCARD checking this for 10142
,I/libpersona( 5422): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5422 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Killing 4219:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/SELinux ( 5422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5422): TimaSignature is unavailable
,D/ActivityThread( 5422): Added TimaKeyStore provider
,V/TaskCloserActivity( 5422): TaskCloserActivity enter()
,V/TaskCloserActivity( 5422): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5438): MountEmulatedStorage(),
E/Zygote  ( 5438): v2
I/libpersona( 5438): KNOX_SDCARD checking this for 10042
I/libpersona( 5438): KNOX_SDCARD not a persona
I/SELinux ( 5438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5438 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4821:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/SELinux ( 5438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5438): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5438): TimaSignature is unavailable
,D/ActivityThread( 5438): Added TimaKeyStore provider
,W/ResourcesManager( 5438): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_4219/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4821/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5438): CalendarProvider2.onCreate() called
,I/PolicyManagerBroadcastReceiver( 5188): This process will be killed soon.
,I/Process ( 5188): Sending signal. PID: 5188 SIG: 9
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5456): MountEmulatedStorage()
I/libpersona( 5456): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5456): v2
I/libpersona( 5456): KNOX_SDCARD not a persona
I/SELinux ( 5456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/SQLiteLog( 5438): (284) automatic index on view_events(_id)
,I/ActivityManager( 1015): Process com.sec.android.app.wluc (pid 5188)(adj 15) has died(117,1140)
,D/TimaKeyStoreProvider( 5456): TimaSignature is unavailable
,D/ActivityThread( 5456): Added TimaKeyStore provider
,D/CalendarAlarmManager( 5438): sys current time:1454523112148
,D/CalendarAlarmManager( 5438): reminder amount:0
,E/MTPRx   ( 5456): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 5456): sealedState: false
,V/MTPRx   ( 5456): sealedUsbMassStorageState: false
E/MTPRx   ( 5456): check value of boot_completed is1
,E/MTPRx   ( 5456): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5456): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5456): Status for mount/Unmount :removed
,E/MTPRx   ( 5456): SDcard is not available
,W/MTPRx   ( 5456): value of connected istrue
,W/MTPRx   ( 5456): value of configured istrue
W/MTPRx   ( 5456): value of mtpEnabled istrue
W/MTPRx   ( 5456): value of ptpEnabled isfalse
,E/MTPRx   ( 5456): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5456): mFirstTime: false
,D/        ( 5456): MTP: reading debug level property
,E/MTPJNIInterface( 5456): Getting CryptionKey from JAVA
,E/MTPRx   ( 5456): currentUserId is 0
,E/MTPRx   ( 5456): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5456): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5456): is_Privatemode is NOT 1
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/SecContentProvider( 1015): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5456): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MTPRx   ( 5456): else part ... so first time!!!
,E/MTPPlaObsrvr( 5456): inside setContext()
E/MTPPlaObsrvr( 5456):  inside createplafiles
,E/MTPPlaObsrvr( 5456): playlist count is0
E/MTPPlaObsrvr( 5456):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5456):  inside deleteing plas createplafiles
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5456): Inside registerContentObserver
,E/MtpAdbObserver( 5456): inside setContext(),
E/MtpAdbObserver( 5456): Inside registerContentObserver
W/Settings( 5456): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/SettingsProvider( 1015): name = mtp_running_status
D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,E/MtpService( 5456): onCreate.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,V/MtpMediaDBManager( 5456): inside deleteAllDB,
,D/MediaScannerReceiver( 1226): action: com.samsung.intent.action.MTP_FILE_SCAN
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5456): < MTP > Registering BroadCast receiver :::::
,V/MtpMediaDBManager( 5456): inside Thread updateDB
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
E/MtpService( 5456): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5456): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,I/SettingSearch/SearchIntentReceiver( 1301): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1301): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/MtpMediaDBManager( 5456): count : 27
,E/MtpService( 5456): onStartCommand.
,W/MTPRx   ( 5456): calling native method
E/MTPJNIInterface( 5456): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5456): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 5456): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5456): noti = 10
E/MtpService( 5456): onStartCommand.
W/MTPRx   ( 5456): calling native method
,E/MTPRx   ( 5456): Checking the driver time out
E/MTPJNIInterface( 5456): noti = 2
D/        ( 5456): deleting sockets before message queue initialization
,D/        ( 5456): event handler thread is created, so set the flag
I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread start --> mDoingInitTitleDB : true
,E/MTPRx   ( 5456): called native method
E/MTPJNIInterface( 5456): setting Media scanner status0
E/MTPJNIInterface( 5456): After setting Media scanner status0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1301): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1301): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/MTPRx   ( 5456): notification from stack 1
,E/        ( 5456): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5456): Getting media scanner status0
,E/MTPJNIInterface( 5456): DeviceName is A5-1
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,E/MtpService( 5456): handleMessage. msg= { when=-21ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/MtpMediaDBManager( 5456): sending db update complete noti to stack
E/MTPJNIInterface( 5456): noti = 29
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MTPJNIInterface( 5456): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5456): SDcard is not available
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,E/        ( 5456): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/        ( 5456): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,E/MTPJNIInterface( 5456): Status for mount/Unmount :removed
E/MTPJNIInterface( 5456): SDcard is not available
E/SQLiteLog( 5456): (21) API call with NULL database connection pointer
E/SQLiteLog( 5456): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5456): (21) API call with NULL database connection pointer
E/SQLiteLog( 5456): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5456): (21) API call with NULL database connection pointer
E/SQLiteLog( 5456): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5456): (21) API call with NULL database connection pointer
E/SQLiteLog( 5456): (21) misuse at line 106108 of [9491ba7d73]
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/MTPRx   ( 5456): notification from stack 2
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/        ( 5456): [mtp_init_device] Library open with 32 bits.
D/        ( 5456): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5456): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5456): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5456):  [sua_support_present:1287] returning false 
D/        ( 5456): *****Starting mtp_io()
,W/MTPRx   ( 5456): notification from stack 3
,D/        ( 5456): [mtp_start_io] source_thread Creation 
D/        ( 5456): [mtp_start_io] sink_thread Creation 
D/        ( 5456): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1301): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1301):  Infomation -> getItem size : 306
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1833): callingUid 10012, callindPid: 1833
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ResourcesManager( 1301): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 1301): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 4561): Conditions not met for autocaching.
I/MusicLeanback( 4561): Stop autocaching.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 4561): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/GmsUtils( 4561): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{dac292e u0 com.sec.bcservice/.BroadcastService}
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 206051(7MB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 46MB/62MB, paused 3.481ms total 282.962ms
,D/MediaScanner( 1226): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
,I/iu.UploadsManager( 2004): End new media; added: 0, uploading: 0, time: 321 ms
,D/MediaScanner( 1226): Skipping:
,D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1226): Skipping:
,D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1226):  prescan time: 322ms (DB items: 27)
,V/MediaScanner( 1226):     scan time: 23ms (Caching mode: true), (makeEntry time: 17ms ~73%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
,V/MediaScanner( 1226): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 348ms
,V/MediaScanner( 1226): checked files: 10  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1226): !@done scanning volume external
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/MTPJNIInterface( 5456): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,E/CscFactoryReceiver( 1455): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1455): Media DB Scanner finished.
D/CscFactoryReceiver( 1455): start service to Set Ringtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1455): start service to Set Notification
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1455): start service to Set Alarmtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1455): onStart
,E/CscUpdateService( 1455): costomer file is exists : it has been preconfiged.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,D/CscUpdateService( 1455): only ringtone update
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1455): onStart
E/CscUpdateService( 1455): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1455): only notification update
,D/CscUpdateService( 1455): onStart
,E/CscUpdateService( 1455): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1455): only alarmtone update
,E/CscParser( 1455): update(): xml file exist
,W/CSCSettings( 1455): Setting Ringtones (type) : 4
D/CscParser( 1455): AlarmTone: null
W/CSCSettings( 1455): 1. Tag_Str: null
E/CscParser( 1455): update(): xml file exist
,E/Zygote  ( 5498): MountEmulatedStorage(),
E/Zygote  ( 5498): v2
I/libpersona( 5498): KNOX_SDCARD checking this for 10006
,I/libpersona( 5498): KNOX_SDCARD not a persona
,I/SELinux ( 5498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/CSCSettings( 1455): Setting Ringtones (type) : 2,
D/CscParser( 1455): MessageTone: null
W/CSCSettings( 1455): 1. Tag_Str: null
,I/SELinux ( 5498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/CscParser( 1455): update(): xml file exist
,E/SELinux ( 5498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1455): Setting Ringtones (type) : 1
D/CscParser( 1455): RingTone: null
W/CSCSettings( 1455): 1. Tag_Str: null
,I/ActivityManager( 1015): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5498 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5498): TimaSignature is unavailable
,D/ActivityThread( 5498): Added TimaKeyStore provider
,E/SMD     (  293): DCD OFF
,I/ThumbnailProvider( 5498): ThumbnailProvider onCreate()
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/DocumentBroadcastReceiver( 5498): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5498): [START] processBroadcastIntent ...
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/BluetoothMediaBrowser( 2623):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/BluetoothMediaBrowser( 2623): no now playing list
,D/BluetoothMediaBrowser( 2623):  getNowPlayingId now playing id : -1
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,I/BroadcastProcessorService( 5498): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5081): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5498): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5498): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5498): [START] DocumentService startDocumentService
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/GalleryCacheReady( 5081): handleMeidaScanFinish()
,D/FaceInterface( 5081): requestFaceScan() is called.
,I/DocumentService( 5498): DocumentService onCreate ... service
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/LocalSuggestAlbumData( 5081): query fail: 
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/FaceInterface( 5081): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 5081): query fail: 
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1301): LOCALE_CHANGED call search setting db finish!!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5498): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5498): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/art     ( 1226): Explicit concurrent mark sweep GC freed 7088(485KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 714us total 35.718ms
,E/SystemInfo( 5498): [SIOP LEVEL] : 0
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1301): LOCALE_CHANGED call search setting db finish!!
,I/DocumentService( 5498): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5498): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/MediaStoreImporter( 4561): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/File    ( 5498): fail readDirectory() errno=13
E/File    ( 5498): fail readDirectory() errno=13
,I/SystemInfo( 5498): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5498): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5498): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :45
E/DocumentService( 5498): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5498): [INDEX] Total time taken for each file :0
,I/DocumentService( 5498): DocumentService onDestroy start
,I/DocumentService( 5498): DocumentService onDestroy end
,I/DocumentService( 5498): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5498): InterruptedException: null
,I/SystemInfo( 5498): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5498): DocumentService cleanupEverything end
,I/Process ( 5498): Sending signal. PID: 5498 SIG: 9
,I/CalendarProvider2( 5438): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,E/lowmemorykiller(  254): Error writing /proc/5498/oom_score_adj; errno=22
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5498)(adj 11) has died(109,1141)
,I/FaceInterface( 5081): startFaceScan() : going on
,D/FaceInterface( 5081): startFaceScan() is called.
D/ContentApp( 1226): startScan() is called.
,D/FaceValue( 1226): mSleepTime: 800
,D/FaceValue( 1226): mMaxThreadNum: 2
,W/FaceValue( 1226): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1226): isNeedToRestore : start
,I/FaceInterface( 5081): startFaceScan() : going on
,D/FaceInterface( 5081): startFaceScan() is called.
,D/ContentApp( 1226): startScan() is called.
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1226): isNeedToRestore : start
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/PackageManager( 1015): verifying app can be installed or not
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1015): ship mode
,I/art     ( 1015): Background partial concurrent mark sweep GC freed 327689(20MB) AllocSpace objects, 2(1839KB) LOS objects, 24% free, 48MB/64MB, paused 4.460ms total 249.029ms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5234): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/PackageManager( 1015): Existing package
,D/PackageManager( 1015): Renaming /data/app/vmdl783410789.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1015): installNewPackageLI: Package{2b0c2c8e com.test.thalitest}
,I/PackageManager( 1015): scanFileNewer : com.test.thalitest
,I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1015): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5531): ----------------------------------------------------
,I/dex2oat ( 5531): <SS>: S T A R T I N G . . .
I/dex2oat ( 5531): <SS>: going to process manifest for 32-bit...
,I/        ( 5531): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5531): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5531): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5531): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5531): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5531): SS_ART_lib [I]: Parsing completed
I/        ( 5531): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5531): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5531): SS_ART_lib [I]: access to SS denied
I/        ( 5531): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5531): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5531): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5531): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5531): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5531): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5531): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5531): dex2oat took 387.123ms (threads: 4)
,I/PackageManager( 1015): do mInstaller.dexopt : 0
,D/PackageManager( 1015): Time to dexopt: 0.449 seconds
,W/System.err( 1015): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1015): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1015): 	... 5 more
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{15545b77 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/PackageManager( 1015): New package installed
,I/HarmonyEASService( 1015): Updating for all 1
,D/PackageManager( 1015): doPostInstall for uid{10155}
,D/PackageManager( 1015): token 1 to BM for possible restore
,V/BackupManagerService( 1015): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1015): Finishing install immediately
D/PackageManager( 1015): BM finishing package install for 1
,D/PackageManager( 1015): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/PageBuddyNotiSvc( 4280): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1455): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/Zygote  ( 5538): MountEmulatedStorage()
E/Zygote  ( 5538): v2
I/libpersona( 5538): KNOX_SDCARD checking this for 1000
I/libpersona( 5538): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/PackageManager( 1015): [MSG] POST_INSTALL: observer{660546578}
D/PackageManager( 1015):           Handling post-install for 1
,E/SELinux ( 5538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,E/SMD     (  293): DCD OFF
,D/TimaKeyStoreProvider( 5538): TimaSignature is unavailable
,D/ActivityThread( 5538): Added TimaKeyStore provider
W/Settings( 1015): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,I/ActivityManager( 1015): Killing 4860:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1799): mOCRHelper is null
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 5538): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1015): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5556): MountEmulatedStorage()
E/Zygote  ( 5556): v2
I/libpersona( 5556): KNOX_SDCARD checking this for 10057
I/libpersona( 5556): KNOX_SDCARD not a persona
,I/SELinux ( 5556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5556): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5556 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4877:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/IntentResolver( 1015): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1015): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1015): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 5556): TimaSignature is unavailable
,D/ActivityThread( 5556): Added TimaKeyStore provider
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1015): PackageReceiver onReceive()
D/RCPManagerService( 1015): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1015):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1015):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 1015): Removing schedule queue dupe of com.test.thalitest
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaPolicyManagerService( 1015): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BackupManagerService( 1015): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1015): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@8ca6dc9
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 288065(17MB) AllocSpace objects, 11(3MB) LOS objects, 27% free, 42MB/58MB, paused 2.938ms total 441.400ms
,D/PackageManager( 1015): result of install: 1{660546578}
I/PackageManager( 1015): Observer no longer exists.
,V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is added to mUserAppList
,D/KnoxMUMContainerPolicy( 1015): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/GCoreNlp( 1833): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1015): getProviders()=[passive],
,E/Zygote  ( 5578): MountEmulatedStorage()
E/Zygote  ( 5578): v2
I/libpersona( 5578): KNOX_SDCARD checking this for 10015
I/libpersona( 5578): KNOX_SDCARD not a persona
I/SELinux ( 5578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5578 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5578): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/TimaKeyStoreProvider( 5578): TimaSignature is unavailable
,D/ActivityThread( 5578): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1015): no available spell checker services found
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1015): Killing 4935:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Babel   ( 5319): Creating RTCS
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5596): MountEmulatedStorage(),
E/Zygote  ( 5596): v2
I/libpersona( 5596): KNOX_SDCARD checking this for 10032
,I/libpersona( 5596): KNOX_SDCARD not a persona
I/SELinux ( 5596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5596 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  319): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 682us total 22.525ms
,I/Babel   ( 5319): Destroying RTCS
,I/CrashAnrDetector( 1015): onPackageAdded : com.test.thalitest
,I/ActivityManager( 1015): Killing 4952:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2,
,D/TimaKeyStoreProvider( 5596): TimaSignature is unavailable
,D/ActivityThread( 5596): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 18.730ms
W/libprocessgroup( 1015): failed to open /acct/uid_10085/pid_4860/cgroup.procs: No such file or directory
,D/LocationProviderProxy( 1015): applying state to connected service
W/libprocessgroup( 1015): failed to open /acct/uid_10094/pid_4877/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1015): applying state to connected service
,W/libprocessgroup( 1015): failed to open /acct/uid_10072/pid_4935/cgroup.procs: No such file or directory
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.514ms total 18.843ms,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GCoreNlp( 1833): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/FeatureConfig( 5596): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1015): Killing 4975:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 5081): PackagesMonitor onReceive :com.google.android.gms
,D/LocationProviderProxy( 1015): applying state to connected service
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_4952/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5596): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5556): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5617): MountEmulatedStorage()
I/libpersona( 5617): KNOX_SDCARD checking this for 10069
E/Zygote  ( 5617): v2
I/libpersona( 5617): KNOX_SDCARD not a persona
,I/SELinux ( 5617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
W/ResourcesManager( 5596): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5617 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5617): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5596): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_4975/cgroup.procs: No such file or directory
,W/ResourcesManager( 5596): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5617): TimaSignature is unavailable
,D/ActivityThread( 5617): Added TimaKeyStore provider
,W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/FileShare-Server( 5617): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5596): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5632): MountEmulatedStorage(),
I/libpersona( 5632): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5632): v2
I/libpersona( 5632): KNOX_SDCARD not a persona
I/SELinux ( 5632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5632 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5596): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5632): TimaSignature is unavailable
D/ActivityThread( 5632): Added TimaKeyStore provider
,W/ResourcesManager( 5596): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5556): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,I/ActivityManager( 1015): Killing 4990:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,W/ResourcesManager( 5632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5596): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/GalaxyFinderApplication( 5596): system/finder_cp/cpdata.xml file not found,
,E/Zygote  ( 5648): MountEmulatedStorage(),
E/Zygote  ( 5648): v2
I/libpersona( 5648): KNOX_SDCARD checking this for 1000
,I/libpersona( 5648): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 5133:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 5648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5648): TimaSignature is unavailable
,D/ActivityThread( 5648): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5648): dbMigrationFlag : false
,D/ShortcutReceiver( 5648):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5664): MountEmulatedStorage()
E/Zygote  ( 5664): v2
I/libpersona( 5664): KNOX_SDCARD checking this for 10120
I/libpersona( 5664): KNOX_SDCARD not a persona
,I/SELinux ( 5664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5664 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4843:com.android.mms/u0a46 (adj 15): empty #31
E/SELinux ( 5664): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5664): TimaSignature is unavailable
,D/ActivityThread( 5664): Added TimaKeyStore provider
,W/ResourcesManager( 5664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1015): No listener is left
,W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_5133/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_4990/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_4843/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5684 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5684): MountEmulatedStorage()
I/libpersona( 5684): KNOX_SDCARD checking this for 10028
,E/Zygote  ( 5684): v2
I/libpersona( 5684): KNOX_SDCARD not a persona
,I/SELinux ( 5684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5684): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5684): TimaSignature is unavailable
,D/ActivityThread( 5684): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5158:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5158/cgroup.procs: No such file or directory
,D/Finsky  ( 5684): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5684): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5684): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5684): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5684): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5684): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5684): Skipping gmscore version check
,D/Finsky  ( 5684): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2004): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1439): This pkg do not need BT addr. Do nothing
,I/PackageBroadcastService( 2004): Null package name or gms related package.  Ignoreing.
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/Finsky  ( 5684): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/AASAservice-UpdateReceiver( 5538): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/AASAservice-TokenRule( 5538): parseToken()
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/System.err( 5538): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 5538): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5538): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5538): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5538): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5538): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5538): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5538): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5538): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5538): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5538): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5538): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5538): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5538): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5538): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5538): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5538): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5538): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5538): 	... 14 more
E/AASAservice-TokenRule( 5538): parseToken() : TokenFile is null
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/AASAservice-UpdateReceiver( 5538): AASARuleUpdateResult() : Rule file is not exist.
V/AlarmManager( 1015): waitForAlarm result :4
I/PackagesMonitor( 5081): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5730): MountEmulatedStorage()
I/libpersona( 5730): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5730): v2
I/libpersona( 5730): KNOX_SDCARD not a persona
I/SELinux ( 5730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5730 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/TimaKeyStoreProvider( 5730): TimaSignature is unavailable
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5730): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5746): MountEmulatedStorage()
,I/libpersona( 5746): KNOX_SDCARD checking this for 10046
E/Zygote  ( 5746): v2
I/libpersona( 5746): KNOX_SDCARD not a persona
I/SELinux ( 5746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5746 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/SELinux ( 5746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 5746): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5746): TimaSignature is unavailable
D/ActivityThread( 5746): Added TimaKeyStore provider
E/Zygote  ( 5765): MountEmulatedStorage()
E/Zygote  ( 5765): v2
I/libpersona( 5765): KNOX_SDCARD checking this for 1000
,I/libpersona( 5765): KNOX_SDCARD not a persona
,I/SELinux ( 5765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 5730): (284) automatic index on shooting_modes(title_id)
,W/ContextImpl( 5203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ResourcesManager( 5746): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5746): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5765): TimaSignature is unavailable
,D/ActivityThread( 5765): Added TimaKeyStore provider
,E/Zygote  ( 5784): MountEmulatedStorage()
E/Zygote  ( 5784): v2
I/libpersona( 5784): KNOX_SDCARD checking this for 1000
I/libpersona( 5784): KNOX_SDCARD not a persona
,I/SELinux ( 5784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp( 5746): [start]    onCreate() consume time = 0.0
,D/TimaKeyStoreProvider( 5784): TimaSignature is unavailable
,D/ActivityThread( 5784): Added TimaKeyStore provider
,E/Zygote  ( 5801): MountEmulatedStorage()
I/Icing   ( 2004): Storage manager: low false usage 1.75MB avail 10.15GB capacity 11.68GB
I/libpersona( 5801): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5801): v2
I/libpersona( 5801): KNOX_SDCARD not a persona
,I/SELinux ( 5801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5801 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 5173:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
W/ResourcesManager( 5784): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5801): TimaSignature is unavailable
,D/ActivityThread( 5801): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 5765): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5765): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5765): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5765): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5765): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5765): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5801): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5801): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 5801): Clear T&P info.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5801): Widget is not attached.
,E/Zygote  ( 5823): MountEmulatedStorage()
,E/Zygote  ( 5823): v2
I/libpersona( 5823): KNOX_SDCARD checking this for 1000
I/libpersona( 5823): KNOX_SDCARD not a persona
,I/SELinux ( 5823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5270:com.sec.android.app.sns3/u0a33 (adj 15): empty #31,
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,I/SELinux ( 5823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 5823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  319): Explicit concurrent mark sweep GC freed 8773(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 22.670ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.357ms
,D/TimaKeyStoreProvider( 5823): TimaSignature is unavailable
,D/ActivityThread( 5823): Added TimaKeyStore provider
,I/CheckinService( 2004): Done disabling old GoogleServicesFramework version
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.094ms
,E/Zygote  ( 5839): MountEmulatedStorage()
E/Zygote  ( 5839): v2
I/libpersona( 5839): KNOX_SDCARD checking this for 10091
I/libpersona( 5839): KNOX_SDCARD not a persona
,I/SELinux ( 5839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5839): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5839 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4167:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/FaceInterface( 5081): startFaceScan() : going on
D/FaceInterface( 5081): startFaceScan() is called.
,W/art     ( 5746): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 159.836ms
,D/TimaKeyStoreProvider( 5839): TimaSignature is unavailable
,D/ActivityThread( 5839): Added TimaKeyStore provider
,D/ContentApp( 1226): startScan() is called.
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1226): isNeedToRestore : start
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1015): failed to open /acct/uid_10122/pid_5173/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10033/pid_5270/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4167/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,D/Finsky  ( 5684): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5855): MountEmulatedStorage()
,E/Zygote  ( 5855): v2
,I/libpersona( 5855): KNOX_SDCARD checking this for 10010
I/libpersona( 5855): KNOX_SDCARD not a persona
,I/SELinux ( 5855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5855 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/SELinux ( 5855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5855): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/art     ( 5746): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 100.229ms
,D/Mms/TelephonyPermission( 5746): start operation mode monitor
,D/Mms/ArtClassLoader( 5746): init before art
,W/ResourcesManager( 5746): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5855): TimaSignature is unavailable
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/ActivityThread( 5855): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 5746): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5746): isDefault true
,D/Mms/MmsApp( 5746): onCreate() com.android.mms
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 5823): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5823): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5823): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5823): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/Mms/MmsApp( 5746): [start]    initCountryIso consume time = 419.134583
,I/DBG_POLICYDM( 5823): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
D/CountryDetector( 1015): The first listener is added
,I/DBG_POLICYDM( 5823): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/ActivityManager( 1015): Killing 5344:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 5746): [end]    initCountryIso consume time = 27.301875
D/Mms/MmsConfig( 5746): [start]    MmsConfig.init() consume time = 0.163229
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/PackageBroadcastService( 2004): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/DBG_POLICYDM( 5823): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraModuleLdr( 2004): Loading module APK com.google.android.play.games
,D/Mms/MmsConfig( 5746): before partial update
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5886): MountEmulatedStorage()
I/libpersona( 5886): KNOX_SDCARD checking this for 10035
,E/Zygote  ( 5886): v2
I/libpersona( 5886): KNOX_SDCARD not a persona
,I/SELinux ( 5886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5886): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5886 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MmsConfig( 5746): Load Resize quality : 80
,I/ActivityManager( 1015): Killing 5364:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/EasySignUpManager_1.0.1( 5746): serviceId : 1, features : -1
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EasySignUpManager_1.0.1( 5746): isAuth is false
D/Mms/MmsConfig( 5746): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1455): query,matched:2117, calling pid = 5746
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5886): TimaSignature is unavailable
,D/ActivityThread( 5886): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1455): match 2117:Elapsed time : 4.282 ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5823): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5823): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EasySignUpManager_1.0.1( 5746): isAuth is false
,D/EasySignUpManager_1.0.1( 5746): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5746): mps_code.dat does not exist
E/CscParser( 5746): customer_path =/system/csc/customer.xml
,E/CscParser( 5746): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5823): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,E/CscParser( 5746): mps_code.dat does not exist
,E/CscParser( 5746): customer_path =/system/csc/customer.xml
,E/CscParser( 5746): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/CscParser( 5746): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5746):  enable multiwindow = true
,E/DataBuffer( 2004): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@335baf06)
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5344/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5364/cgroup.procs: No such file or directory
,E/Mms/MessageUtils( 5746): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5746): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5746): [end]    init() consume time = 171.160782
,D/Mms/Contact( 5746): [start]    init() consume time = 1.490937
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5823): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,E/SPPClientService( 5886): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5886): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1455): query,matched:13, calling pid = 5746
,I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
,I/DBG_POLICYDM( 5823): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/TP/MmsSmsProvider( 1455): match 13:Elapsed time : 2.251 ms
,I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/03/19:11:58
I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/SPPClientService( 5886): PushLog.txt file is not deleted.
D/SPPClientService( 5886): PushLog.txt file is not deleted.
D/SPPClientService( 5886): ============PushLog. stop!
D/Mms/Contact( 5746): [end]    init consume time = 33.586458
,E/Zygote  ( 5911): MountEmulatedStorage()
I/libpersona( 5911): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5911): v2
I/libpersona( 5911): KNOX_SDCARD not a persona
,I/SELinux ( 5911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5911): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5911 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/ActivityManager( 1015): Killing 5386:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 5823): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,D/TimaKeyStoreProvider( 5911): TimaSignature is unavailable
,D/ActivityThread( 5911): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5823): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5823): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5823): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5823): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5823): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/Mms/DraftCache( 5746): [start]    rebuildCache consume time = 34.011511
,D/TP/MmsSmsProvider( 1455): query,matched:12, calling pid = 5746
,D/TP/MmsSmsProvider( 1455): match 12:Elapsed time : 2.543 ms
,E/PhotosPlugin( 5839): Loading PhotosPlugin
,D/Mms/DraftCache( 5746): [end]    rebuildCache consume time = 24.468281
,W/ResourcesManager( 5911): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ResourcesManager( 5911): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Mms/MethodReflector( 5746): getSubId is called,
D/Mms/TelephonyUtils( 5746): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5746): getTelephonyProperty is called,
D/SSRM:n  ( 1015): SIOP:: AP = 380
D/Mms/DownloadManager( 5746): roaming -> false (slotId = 0),
D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5746): auto download without roaming -> true
,D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5746): getSubId is called
,D/Mms/MethodReflector( 5746): getDefaultSmsSubId is called,
E/Mms/TelephonyUtils( 5746): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5746): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 5746): getTelephonyProperty is called
D/Mms/DownloadManager( 5746): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5746): auto download without roaming -> true
,D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5746): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5746): mAutoDownload ------> true
,W/art     ( 2004): Verification of void com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver.onReceive(android.content.Context, android.content.Intent) took 142.959ms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5386/cgroup.procs: No such file or directory
,D/ComposerPerformance( 5746): 1454523118542 ms / [DONE] Composer constructor
,E/CII     ( 5746): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5746): ReservationManager()
,I/Mms/ReservationManager( 5746): resetAfterConnected()
,D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 5746
,D/Mms/ArtClassLoader( 5746): init [DONE] art
,D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 2.551 ms
,D/Mms/Conversation( 5746): [start]    init() consume time = 100.903906
,D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
,D/Mms/Conversation( 5746): [end]    init consume time = 13.98974
,I/Mms/ReservationManager( 5746): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MessagingNotification( 5746): [start]    init() consume time = 5.685989
,D/Mms/MmsApp( 5746): [end]    onCreate() consume time = 0.951667
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/Mms/MessagingNotification( 5746): [end]    init consume time = 3.734271
,D/TP/MmsSmsProvider( 1455): query,matched:0, calling pid = 5746
V/TP/MmsSmsProvider( 1455): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1455): match 0:Elapsed time : 1.408 ms
,D/Mms/Synchronizer( 5746): [start]    doSync consume time = 10.280937
,D/Mms/SpamFilter( 5746): [start]    SpamFilter fill() begin consume time = 1.165313
,D/TP/MmsSmsProvider( 1455): update, matched:300, calling pid = 5746
V/TP/MmsSmsProvider( 1455): syncDBData start
,V/TP/MmsSmsProvider( 1455): syncDBData sms end
,V/TP/MmsSmsProvider( 1455): syncDBData mms end
,V/TP/MmsSmsProvider( 1455): syncDBData end
,D/TP/MmsSmsProvider( 1455): query,matched:400, calling pid = 5746
,D/Mms/Synchronizer( 5746): [end]    doSync consume time = 4.734115
,D/Mms/DownloadManager( 5746): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5746): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5746): getSubId is called
,D/Mms/TelephonyUtils( 5746): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5746): getTelephonyProperty is called
,D/Mms/DownloadManager( 5746): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/SpamFilter( 5746): [end]    SpamFilter fill() finished consume time = 16.558385
,D/Mms/DownloadManager( 5746): auto download without roaming -> true
,D/Mms/DownloadManager( 5746): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5746): mAutoDownload ------> true
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 205705(13MB) AllocSpace objects, 7(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.761ms total 205.632ms
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageStatusReceiver( 5746): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5933): MountEmulatedStorage()
E/Zygote  ( 5933): v2
I/libpersona( 5933): KNOX_SDCARD checking this for 10072
I/libpersona( 5933): KNOX_SDCARD not a persona
,I/SELinux ( 5933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5933 uid=10072 gids={50072, 9997} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/SELinux ( 5933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/DBG_POLICYDM( 5823): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,E/SELinux ( 5933): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5947): MountEmulatedStorage()
E/Zygote  ( 5947): v2
I/libpersona( 5947): KNOX_SDCARD checking this for 10047
I/libpersona( 5947): KNOX_SDCARD not a persona
,I/SELinux ( 5947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5947): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5947 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5933): TimaSignature is unavailable
D/ActivityThread( 5933): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5947): TimaSignature is unavailable
,D/ActivityThread( 5947): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 5746): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5746): onHandleIntent: ACTION_PACKAGE_ADDED
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1015): Killing 5422:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,W/ResourcesManager( 5947): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5947): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5947): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/BadgeProvider( 5933): onCreate
,D/BadgeProvider( 5933): DatabaseHelper
,D/Mms/MessagingNotification( 5746): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1455): query,matched:26, calling pid = 5746
,D/TP/SmsProvider( 1455): match 26:Elapsed time : 1.202 ms
,D/TP/MmsSmsProvider( 1455): query,matched:6, calling pid = 5746
,D/TP/MmsSmsProvider( 1455): match 6:Elapsed time : 1.129 ms
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2004): updateResources: need to parse f{com.google.android.gms}
,E/Zygote  ( 5965): MountEmulatedStorage(),
E/Zygote  ( 5965): v2
I/libpersona( 5965): KNOX_SDCARD checking this for 10025
I/libpersona( 5965): KNOX_SDCARD not a persona
,I/SELinux ( 5965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5965 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5965): TimaSignature is unavailable
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5965): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5422/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5438:com.android.providers.calendar/u0a42 (adj 15): empty #31
,E/SMD     (  293): DCD OFF
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 5965): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/MyFiles ( 5947): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/OMACP   ( 5965): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5438/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Mms/Omacp( 5746): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
,I/TactileAssist( 1015): List of disabled apps :
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/DBG_POLICYDM( 5823): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,E/Zygote  ( 5991): MountEmulatedStorage()
,E/Zygote  ( 5991): v2
I/libpersona( 5991): KNOX_SDCARD checking this for 10053
,I/libpersona( 5991): KNOX_SDCARD not a persona
,I/SELinux ( 5991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false,
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5991 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/DBG_POLICYDM( 5823): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/SELinux ( 5991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5991): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/TimaKeyStoreProvider( 5991): TimaSignature is unavailable
,D/ActivityThread( 5991): Added TimaKeyStore provider
,W/ResourcesManager( 5991): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5991): onReceive() it will make start service
,D/AsyncTaskServiceImpl( 2004): Submit a task: k
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 5991): onHandleIntent()
,D/Compatibility( 5991): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5991): found: 2
,D/Compatibility( 5991): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5991): skipping ResolveInfo{3277798 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5991): considering ResolveInfo{35ce6bf1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5991): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5991): enabling receiver ResolveInfo{3b2d93d6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/UpdateIcingCorporaServi( 5556): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 5991): enabling receiver ResolveInfo{2f75657 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5991): enabling receiver ResolveInfo{3de87544 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5991): enabling receiver ResolveInfo{264cd62d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5965): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Compatibility( 5991): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/k       ( 2004): Processing package: com.test.thalitest
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,D/GassUtils( 2004): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2004): Found info for package com.test.thalitest in db.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5218:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5911): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5911): isLoggable:: SL_DEBUG_EXIST = false
,I/PeopleDatabaseHelper( 2004): cleanUpNonGplusAccounts done.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5218/cgroup.procs: No such file or directory
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5911): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,W/BaseAppContext( 2004): Using Auth Proxy for data requests.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5911): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6022): MountEmulatedStorage(),
E/Zygote  ( 6022): v2
I/libpersona( 6022): KNOX_SDCARD checking this for 10041
I/libpersona( 6022): KNOX_SDCARD not a persona
I/SELinux ( 6022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6022 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6022): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6022): TimaSignature is unavailable
,D/ActivityThread( 6022): Added TimaKeyStore provider
,W/art     ( 5839): Suspending all threads took: 5.005ms
,I/Icing   ( 2004): Internal init done: storage state 0
,I/Icing   ( 2004): Post-init done
,I/Icing   ( 2004): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 6022): [SSP] onCreated
,I/ActivityManager( 1015): Killing 5234:com.google.android.gm/u0a101 (adj 15): empty #31
,I/SA      ( 6022): [TPM] There is no property file
,I/SA      ( 6022): [SCU] isHaveSA() - false
,I/SA      ( 6022): [TPM] getModelProperty : null
I/SA      ( 6022): [TPM] getCSCProperty : null
,I/SA      ( 6022): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6022): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6022): [DM] TFT FEATURE: false
,I/SA      ( 6022): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6022): [DM] init START
,I/SA      ( 6022): [DM] This device is not a Vodafone
,W/ResourceType( 6022): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 6022): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6022): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 6022): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6022): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 6022): [SCU] isHaveSA() - false
I/SA      ( 6022): support phone number id : false
I/SA      ( 6022): [DM] Supports Ref Jpn : true
,I/SA      ( 6022): [DM] init END
I/SA      ( 6022): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6022): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 5063:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5234/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1015): [SO] 0.019 0.077 10.094
,W/GAV2    ( 5839): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5556): UpdateCorporaTask done [took 599 ms] updated apps [took 599 ms] 
,I/ActivityManager( 1015): Killing 4561:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5063/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4561/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6054): MountEmulatedStorage()
,E/Zygote  ( 6054): v2
I/libpersona( 6054): KNOX_SDCARD checking this for 10100
I/libpersona( 6054): KNOX_SDCARD not a persona
I/SELinux ( 6054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6054 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 4895:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/SELinux ( 6054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5839): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 6054): TimaSignature is unavailable
,D/ActivityThread( 6054): Added TimaKeyStore provider
,D/PackageIntentReceiver( 6054): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6054): Not GearManger package! 
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6076): MountEmulatedStorage()
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6076 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 6076): v2
I/libpersona( 6076): KNOX_SDCARD checking this for 1000
I/libpersona( 6076): KNOX_SDCARD not a persona
,I/SELinux ( 6076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4895/cgroup.procs: No such file or directory
I/SELinux ( 6076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6076): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  319): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 19.882ms
,D/TimaKeyStoreProvider( 6076): TimaSignature is unavailable
D/ActivityThread( 6076): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.215ms
W/AccountFeatureHelper( 5839): Write apps_features disabled false
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.221ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6092): MountEmulatedStorage()
,E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD checking this for 1000
I/libpersona( 6092): KNOX_SDCARD not a persona
,I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5401:com.android.calendar/u0a135 (adj 15): empty #31
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
,D/ActivityThread( 6092): Added TimaKeyStore provider
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/accuweather( 1725): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5401/cgroup.procs: No such file or directory
D/accuweather( 1725): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1725): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 19 12
,W/SQLiteConnectionPool( 2004): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 6092): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6092): Enter Oncreate
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
D/AcmsServiceMonitor( 6092): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6092): creating AcmsCore
D/AcmsCore( 6092): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6092): AcmsCore
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsCore( 6092): init
,D/AcmsCore( 6092): Looper handler is not null
D/AcmsCore( 6092): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6092): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6092): Incrementing - Counter value: 1
D/AcmsCore( 6092): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6092): onStartCommand
D/AcmsService( 6092): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6092): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6092): Incrementing - Counter value: 2
D/AcmsService( 6092): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityThread( 6092): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 6092): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6092): AcmsRevocationMngr
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
,W/GAV2    ( 5839): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/AcmsService( 6092): Inside handle Intent
D/AcmsService( 6092): App added - package name: com.test.thalitest
D/AcmsCore( 6092): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6092): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6092): Incrementing - Counter value: 3
D/AcmsCore( 6092): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6092): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6092): Decrementing - Counter value: 2
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5319:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5319/cgroup.procs: No such file or directory
,I/Mms/MmsApp( 5746):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5746): [start]    fillCache consume time = 1965.153437
D/Mms/ComposeMessageFragment( 5746): fillCache, easy = false
,D/AbsListView( 5746): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5746): [end]    fillCache consume time = 82.338437
,I/Icing   ( 2004): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Mms/BubbleViewCache( 5746): fillCache bubble = 1
,D/Icing   ( 2004): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2004): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,I/Icing   ( 2004): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 2004): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5617:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5617/cgroup.procs: No such file or directory
,E/SMD     (  293): DCD OFF
,D/AcmsKeyStoreHelper( 6092):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6092): Key Store exist
I/AcmsKeyStoreHelper( 6092): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6092):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6092): getKeyStoreForApplication success 
,D/AcmsCore( 6092): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6092): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6092): Decrementing - Counter value: 1
D/AcmsCore( 6092): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6092): This is NOT a valid MirrorLink app
,D/AcmsCore( 6092): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6092): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6092): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6092): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6092): getSvcCounter - Counter value: 0
,D/AcmsService( 6092): Enter onDestroy
I/AcmsService( 6092): cleanUp(): inside service clean up
,D/AcmsCore( 6092): AcmsCore: inside DeInit
D/AcmsCore( 6092): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 6092): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 6092): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6092): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6092): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6092): getSvcCounter - Counter value: 0
,D/AcmsService( 6092): killing acms process
,I/Process ( 6092): Sending signal. PID: 6092 SIG: 9
,I/DBG_POLICYDM( 5823): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/ActivityManager( 1015): Process ACMS.Process (pid 6092)(adj 0) has died(68,1185)
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5823): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 2004): End new media; added: 0, uploading: 0, time: 54 ms
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5684): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5684): Thread-974(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5684): Thread-974(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5684): Thread-974(ApacheHTTPLog):isShipBuild true
I/System.out( 5684): Thread-974(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5684): Thread-974(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5684): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5684, getuid(): 10028
,I/qtaguid ( 5684): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5684, getuid(): 10028
,I/qtaguid ( 5684): Untagging socket 44,
I/System.out( 5684): Thread-974 calls detatch()
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/System.out( 5684): Thread-975(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5684): Thread-975(ApacheHTTPLog):isShipBuild true
I/System.out( 5684): Thread-975(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5684): Thread-975(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5684): Untagging socket 44,
I/qtaguid ( 5684): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5684): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5684): untagSocket(44) failed with errno -22
I/System.out( 5684): Thread-975 calls detatch()
,D/Finsky  ( 5684): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6125 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,E/Zygote  ( 6125): MountEmulatedStorage()
I/libpersona( 6125): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6125): v2
I/libpersona( 6125): KNOX_SDCARD not a persona
,I/SELinux ( 6125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 6125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6125): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5684): Thread-974(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5684): Thread-974(ApacheHTTPLog):isShipBuild true
I/System.out( 5684): Thread-974(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5684): Thread-974(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 6125): TimaSignature is unavailable
,D/ActivityThread( 6125): Added TimaKeyStore provider
,W/ResourcesManager( 6125): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6125): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6125): VM with version 2.1.0 has multidex support
,I/MultiDex( 6125): install
I/MultiDex( 6125): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6125): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5684): Untagging socket 44
,I/qtaguid ( 5684): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5684): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5684): untagSocket(44) failed with errno -22
I/System.out( 5684): Thread-974 calls detatch()
,W/ActivityThread( 6125): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6125): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3699fdbe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6125): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1833): callingUid 10012, callindPid: 1833
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 6125): Reading stored module config
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1833): [258] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2004): Restart initialization of location
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1833): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6125): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6125): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6125): Connecting to CarCallService...
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 33212(1754KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.645ms total 145.585ms
,W/GCoreFlp( 1833): No location to return for getLastLocation()
,W/FusedLocationProvider( 1833): location=null
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6125): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6125): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6125): com.google.android.projection.gearhead isn't installed.
,W/art     ( 6125): Suspending all threads took: 20.970ms
,D/CAR.TEL.Service( 6125): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6125): Creating a new PhoneAdapter instance
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6125): setListener: com.google.android.gms.car.dn@226837a5
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6125): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6125): Starting CarCallService with initial phone null
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{365906d0 u0 com.samsung.android.MtpApplication/.MtpService}
,D/CAR.SERVICE( 6125): Package validated; name: com.android.vending
,V/Finsky  ( 5684): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5684): Thread-975(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5684): Thread-975(ApacheHTTPLog):isShipBuild true
,I/System.out( 5684): Thread-975(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5684): Thread-975(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5684): Untagging socket 44
,I/qtaguid ( 5684): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5684): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5684): untagSocket(44) failed with errno -22
I/System.out( 5684): Thread-975 calls detatch()
,E/SMD     (  293): DCD OFF
,W/ResourcesManager( 5684): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5684): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5684): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1833): client connected with version: 8296000
,D/Finsky  ( 5684): [996] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5684): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5684): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5684): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5684): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5684): (HTTPLog)-Static: isShipBuild true
I/System.out( 5684): (HTTPLog)-Thread-985-549224693: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5684): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5684): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  ( 1015): SIOP:: AP = 350,
,I/ActivityManager( 1015): Killing 5648:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5648/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5538:com.samsung.aasaservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5538/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1015): [SO] 0.019 0.057 10.036
,D/PowerManagerService( 1015): [s] UserActivityState : 1 -> 2,
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1015): lcd : 1 +
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1015): lcd : 1 -,
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  293): DCD OFF
,D/CAR.SERVICE( 6125): mConnectedToCar = false, abort
,E/ActivityThread( 6125): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15af7ed that was originally bound here
E/ActivityThread( 6125): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15af7ed that was originally bound here
E/ActivityThread( 6125): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6125): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6125): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6125): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6125): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6125): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6125): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6125): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6125): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6125): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6125): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6125): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6125): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6125): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6125): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6125): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6125): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6125): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6125): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6125): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16e7119c that was originally bound here
E/ActivityThread( 6125): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16e7119c that was originally bound here
E/ActivityThread( 6125): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6125): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6125): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6125): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6125): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6125): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6125): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6125): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6125): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6125): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6125): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6125): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6125): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6125): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6125): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6125): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6125): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6125): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@123c0a17
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{2696bbaf u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/Watchdog( 1015): !@Sync 2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1015): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1015): Nap time (uid 1000)...
,D/PowerManagerService( 1015): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1015): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1015): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1015): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1015): WindowOrientationListener disabled
,D/SensorService( 1015): [SO] activate (ident=0xb8ea2ac8, enabled=0)
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1015): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1015): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1015): handleSandman : startDream(true)
,E/PowerManagerService( 1015): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1015): Sleeping (uid 1000)...
D/PowerManagerService( 1015): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,I/Adreno-EGL( 1015): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1015): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1015): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1015): Local Branch: 
I/Adreno-EGL( 1015): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1015): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1015):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorManager( 1015): unregisterListener ::   
,D/KeyguardViewMediator( 1173): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1173): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1173): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1173): notifyScreenOffLocked
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1173): timeout : 5000
,D/PowerManagerService( 1015): Excessive delay in ColorFade : createEglContext: 28ms
,E/SMD     (  293): DCD OFF
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
,V/ActivityThread( 3130): updateVisibility : ActivityRecord{1bfdd4a1 token=android.os.BinderProxy@2b6019cc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1173): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1173): handleNotifyScreenOff,
D/VolumePanel( 1173): onScreenTurnedOff()
D/VolumePanel( 1173): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1173): onScreenTurnedOff
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_ON,
,D/PowerManagerService( 1015): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
,W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1015): fail to set sysfs 1
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
,D/InputMethodManagerService( 1015): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,W/IcingInternalCorpora( 2004): getNumBytesRead when not calculated.
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1015):  handler : SCREEN_ON end
,I/StatusBar( 1173): Icon Only
,D/NotificationService( 1015): ACTION_SCREEN_ON
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/PanelView( 1173): There is/are notification(s) 
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,E/WifiNative-wlan0( 1015): do suspend false
,I/wpa_supplicant( 2074): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2074): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
,D/PowerManagerService( 1015): Excessive delay in ColorFade : initGLShaders: 43ms
,D/PowerManagerService( 1015): Excessive delay in ColorFade prepare: 118ms
,D/DisplayPowerController( 1015): ColorFade: onAnimationStart
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1015): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1725): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1799): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1015): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1015): turn on LED for fully charged
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1015): write_int failed to open -1
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SmartFaceService( 1015): fail to set sysfs 0
W/System.err( 1015): 	... 10 more
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1799): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1015):  handler : SCREEN_OFF end 
,D/daemonapp( 1321): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1321): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/NotificationService( 1015): ACTION_SCREEN_OFF
,D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,E/WifiNative-wlan0( 1015): do suspend true
,D/comsamsunglog( 1321): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1321): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1321): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1321): [MSC_Daemon]>>> ====================================================================================================================
I/BackgroundCompactionService( 1015): Schedule Type1 BGCompaction
D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454544660000
D/daemonapp( 1321): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454523137084
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1321): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/daemonapp( 1321): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1321): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1321): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,E/daemonapp( 1321): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1015): ACTION_SCREEN_OFF onReceive
,I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: true
,D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_OFF called
,D/accuweather( 1725): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/DisplayPowerState( 1015): !@ ColorFade entry
D/DisplayPowerController( 1015): ColorFade: onAnimationEnd
D/lights  ( 1015): lcd : 0 +
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF,
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
,D/lights  ( 1015): lcd : 0 -
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1015): Got set_interactive hint
,D/DisplayManagerService( 1015): !@display_state: ON -> OFF
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb73fb690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1015): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1015): Display changed displayId=0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 0 Current Level: 100 Delta: -100
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/StatusBar.NetworkController( 1173): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LibSecureUISvc( 1933): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Broadcasts
D/accuweather( 1725): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1725): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/BatteryStatsDumper( 1015): Writing to database completed
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1015): Excessive delay in setPowerMode(): 260ms
D/PowerManagerService( 1015): Excessive delay in !@display_state: OFF: 261ms
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1015): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1015): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 273ms
I/PowerManagerService( 1015): [PWL] Off : 0s ago
,D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 2074): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1015): InactiveState{ what=147461 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 },
D/WifiP2pService( 1015): DefaultState{ what=147461 }
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1173): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1,
,D/KeyguardViewMediator( 1173): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1173): *** Keyguard wallpaper service already unbounded
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,D/Finsky  ( 5684): [987] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5684): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 15s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,I/art     ( 1833): Explicit concurrent mark sweep GC freed 38814(2MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 12MB/21MB, paused 1.386ms total 72.461ms
,E/DataBuffer( 1833): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f104a91),
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/VacuumService( 1833): Vacuum at: now=1454523170998 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1833): Scheduling Phenotype for one-off execution 4369 seconds from now (1454523171428)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1833): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1833): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1833): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1833): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1833): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1833): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1833, getuid(): 10012
,I/qtaguid ( 1833): Tagging socket 91 with tag 1000120100000000{268440065,0} for uid -1, pid: 1833, getuid(): 10012
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1833): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1833): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1833, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1833): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1833): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1833, getuid(): 10012
,D/FactoryTest( 5456): Not factory mode
,D/FactoryTest( 5456): Not factory mode. isFactoryMode() returend false,
,D/MTPRx   ( 5456): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5456): still no open session command from host, so toast
,W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5456): Timeline: Activity_launch_request id:com.android.settings time:115060
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!,
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,V/ActivityManager( 1015): Display changed displayId=0
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 3130
,E/MTPRx   ( 5456): started activity for popup
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5456): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5456): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5456): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5456): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5456): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus entered window: 3130
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@330292a6 attribute=android.view.inputmethod.EditorInfo@132b34e7, token = android.os.BinderProxy@11c6c0e
,D/SamsungIME( 1799): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5456): dev.kiessupport is : TRUE
,D/PhoneWindow( 5456): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5456): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 27
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 27
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3130): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 27
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3130): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3130): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3130): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3130): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityThread( 3130): updateVisibility : ActivityRecord{1bfdd4a1 token=android.os.BinderProxy@2b6019cc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 3130): Timeline: Activity_idle id: android.os.BinderProxy@2b6019cc time:115319
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1015): mDVFSHelper.release(),
,E/SMD     (  293): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD OFF,
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1015): !@Sync 5
,I/ClearcutLoggerApiImpl( 1833): disconnect managed GoogleApiClient,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/HeadsetStateMachine( 2623): Disconnected process message: 10
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 105s ago,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8,
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260

```
