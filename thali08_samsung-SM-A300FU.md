#### Test 58135655812b57f_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/GAV2    ( 4487): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of system
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/SMD     (  294): DCD OFF
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4931): getAccountsCursor
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4931): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 4931): Observing account changes for notifications
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 4931): getAccountsCursor
E/Gmail   ( 4931): Error finding the version of the Email provider.....
E/Gmail   ( 4931): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4931): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4931): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 4931): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 4931): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4931): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4931): We do not support migrating this version of the Email provider.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 4365:com.android.chrome/u0a77 (adj 15): empty #31
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4973): MountEmulatedStorage()
I/libpersona( 4973): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4973): v2
I/libpersona( 4973): KNOX_SDCARD not a persona
E/SQLiteLog( 4931): (283) recovered 30 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/SELinux ( 4973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=4973 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/SELinux ( 4973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4389:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
D/TimaKeyStoreProvider( 4973): TimaSignature is unavailable
D/ActivityThread( 4973): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/File    ( 4931): fail readDirectory() errno=2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PopupuiReceiver( 4973): onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 1018): uri = -1 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
I/PopupuiReceiver_KNOX( 4973): getSealedState : true
D/SecContentProvider2( 1018): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 1018): mCursor = null
I/PopupuiReceiver_KNOX( 4973): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 1018): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 1018): mCursor = null
I/PopupuiReceiver_KNOX( 4973): getCheckCoverPopupState : true
D/PopupuiReceiver( 4973): Action cable connected ! on - 
I/Gmail   ( 4931): notifyAccountChanged
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_4365/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 4931): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 4931): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4931): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4931): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/Zygote  ( 4990): MountEmulatedStorage()
E/Zygote  ( 4990): v2
I/libpersona( 4990): KNOX_SDCARD checking this for 1000
I/libpersona( 4990): KNOX_SDCARD not a persona
I/SELinux ( 4990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=4990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4405:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #31
I/Gmail   ( 4931): getAccountsCursor
I/SELinux ( 4990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4990): TimaSignature is unavailable
D/ActivityThread( 4990): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_4389/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_4405/cgroup.procs: No such file or directory
D/AssistantMenuSettingSearch( 4990): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 4990): Make Setting DB
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 4931): getAccountsCursor
E/Zygote  ( 5006): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5006 uid=10146 gids={50146, 9997} abi=armeabi-v7a
E/Zygote  ( 5006): v2
I/libpersona( 5006): KNOX_SDCARD checking this for 10146
I/SELinux ( 5006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5006): KNOX_SDCARD not a persona
I/SELinux ( 5006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SELinux ( 5006): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5006): TimaSignature is unavailable
D/ActivityThread( 5006): Added TimaKeyStore provider
W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1018): Killing 4506:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 4471:com.sec.android.cloudagent/u0a1 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1465): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1465): addSearchInfoDB
I/SettingSearchManagerReceiver( 1465): endInsert
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5022): MountEmulatedStorage()
E/Zygote  ( 5022): v2
I/libpersona( 5022): KNOX_SDCARD checking this for 10102
I/libpersona( 5022): KNOX_SDCARD not a persona
I/SELinux ( 5022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/AlarmManager( 1018): waitForAlarm result :8
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5022 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 5022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5022): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
D/SecKeyguardClockView( 1185): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1185): HomeTimezone(): 1
W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_4471/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4506/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5022): TimaSignature is unavailable
D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
D/ActivityThread( 5022): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ResourcesManager( 5022): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/SViewCoverWidget( 1185): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1718): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1718): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
E/accuweather( 1718): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 24
I/Babel   ( 5022): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5022): MmsConfig.loadMmsSettings
I/Babel   ( 5022): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 5022): MmsConfig.loadFromDatabase
E/Babel   ( 5022): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5022): MmsConfig.loadFromResources
W/Settings( 5022): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 5022): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5022): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/VideoCapabilities( 5022): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5022): Unsupported mime audio/evrc
W/AudioCapabilities( 5022): Unsupported mime audio/qcelp
W/AudioCapabilities( 5022): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 5022): Unsupported mime audio/mpeg-L2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/AudioCapabilities( 5022): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5022): Unsupported mime audio/x-ima
W/AudioCapabilities( 5022): Unsupported mime audio/qcelp
W/AudioCapabilities( 5022): Unsupported mime audio/evrc
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5054): MountEmulatedStorage()
E/Zygote  ( 5054): v2
I/libpersona( 5054): KNOX_SDCARD checking this for 10030
I/libpersona( 5054): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5054 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5054): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 5022): Unsupported mime video/wvc1
W/VideoCapabilities( 5022): Unsupported mime video/x-ms-wmv
D/TimaKeyStoreProvider( 5054): TimaSignature is unavailable
D/ActivityThread( 5054): Added TimaKeyStore provider
D/AndroidRuntime( 5038): 
D/AndroidRuntime( 5038): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5038): CheckJNI is OFF
D/AndroidRuntime( 5038): readGMSProperty: start
D/AndroidRuntime( 5038): readGMSProperty: already setted!!
D/AndroidRuntime( 5038): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5038): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5038): readGMSProperty: end
D/AndroidRuntime( 5038): addProductProperty: start
W/VideoCapabilities( 5022): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 5022): Unsupported mime video/wvc1
W/VideoCapabilities( 5022): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 5022): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 5022): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 5022): Unsupported mime video/mp43
W/VideoCapabilities( 5022): Unsupported mime video/sorenson
W/VideoCapabilities( 5022): Unsupported mime video/mp4v-esdp
W/art     ( 5022): Suspending all threads took: 6.400ms
E/SQLiteLog( 5022): (284) automatic index on conversation_participants_view(conversation_id)
I/VideoCapabilities( 5022): Unsupported profile 4 for video/mp4v-es
W/ResourcesManager( 5054): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5054): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5054): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SQLiteLog( 5022): (284) automatic index on conversation_participants_view(conversation_id)
W/ResourcesManager( 5054): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5054): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5054): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     ( 1639): Explicit concurrent mark sweep GC freed 3440(139KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 927us total 29.461ms
E/AffinityControl( 5038): AffinityControl: registerfunction enter
W/ResourcesManager( 5054): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5054): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/AndroidRuntime( 5038): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5038): Shutting down VM
E/SQLiteLog( 5022): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 5022): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 5022): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager( 1018): Killing 3101:com.policydm/1000 (adj 15): empty #31
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3101/cgroup.procs: No such file or directory
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 3976:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
W/art     ( 5038): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/GCM     ( 1800): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10121/pid_3976/cgroup.procs: No such file or directory
,W/GCoreFlp( 1800): No location to return for getLastLocation()
W/FusedLocationProvider( 1800): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 3926): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1018): Background sticky concurrent mark sweep GC freed 142896(4MB) AllocSpace objects, 1(16KB) LOS objects, 9% free, 44MB/49MB, paused 5.393ms total 110.925ms
,E/Zygote  ( 5107): MountEmulatedStorage()
I/libpersona( 5107): KNOX_SDCARD checking this for 10032
E/Zygote  ( 5107): v2
I/libpersona( 5107): KNOX_SDCARD not a persona
,I/SELinux ( 5107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5107 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5107): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 22.985ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 20.392ms
,D/TimaKeyStoreProvider( 5107): TimaSignature is unavailable
,D/ActivityThread( 5107): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.318ms
,E/SPPClientService( 5107): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5107): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5107): PushLog.txt file is not deleted.
,D/SPPClientService( 5107): PushLog.txt file is not deleted.
D/SPPClientService( 5107): ============PushLog. stop!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5127): MountEmulatedStorage()
,E/Zygote  ( 5127): v2
,I/libpersona( 5127): KNOX_SDCARD checking this for 10032
I/libpersona( 5127): KNOX_SDCARD not a persona
,I/SELinux ( 5127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5127 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4526:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
I/SELinux ( 5127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5127): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5127): TimaSignature is unavailable
,D/ActivityThread( 5127): Added TimaKeyStore provider
,E/SPPClientService( 5127): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5127): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 5127): [PhoneStatusChangeReceiver] This device doesn't register yet.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4562:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/SPPClientService( 5127): PushLog.txt file is not deleted.
D/SPPClientService( 5127): PushLog.txt file is not deleted.
D/SPPClientService( 5127): ============PushLog. stop!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_4526/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10058/pid_4562/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4063): (284) automatic index on view_events(_id),
,E/Zygote  ( 5150): MountEmulatedStorage()
,E/Zygote  ( 5150): v2
I/libpersona( 5150): KNOX_SDCARD checking this for 1000
I/libpersona( 5150): KNOX_SDCARD not a persona
,I/SELinux ( 5150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CalendarAlarmManager( 4063): sys current time:1454948641675
,D/CalendarAlarmManager( 4063): reminder amount:0
,D/TimaKeyStoreProvider( 5150): TimaSignature is unavailable
,D/ActivityThread( 5150): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5150): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{371ee82 u0 com.sec.bcservice/.BroadcastService}
,I/DIAGMON_AGENT( 5150): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5150): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5150): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1018): Killing 4235:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3058): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5165): MountEmulatedStorage(),
E/Zygote  ( 5165): v2
I/libpersona( 5165): KNOX_SDCARD checking this for 10139
I/libpersona( 5165): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5165 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SensorService( 1018): [SO] -0.441 -0.057 9.883
,D/TimaKeyStoreProvider( 5165): TimaSignature is unavailable
,D/ActivityThread( 5165): Added TimaKeyStore provider
,V/TaskCloserActivity( 5165): TaskCloserActivity enter()
,V/TaskCloserActivity( 5165): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 4000:com.osp.app.signin/u0a36 (adj 15): empty #31
,E/Zygote  ( 5180): MountEmulatedStorage()
E/Zygote  ( 5180): v2
I/libpersona( 5180): KNOX_SDCARD checking this for 1000
,I/libpersona( 5180): KNOX_SDCARD not a persona
I/SELinux ( 5180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5180): TimaSignature is unavailable
,D/ActivityThread( 5180): Added TimaKeyStore provider
,I/PolicyManagerBroadcastReceiver( 4912): This process will be killed soon.
,I/Process ( 4912): Sending signal. PID: 4912 SIG: 9
,E/MTPRx   ( 5180): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 5180): sealedState: false
V/MTPRx   ( 5180): sealedUsbMassStorageState: false
,E/MTPRx   ( 5180): check value of boot_completed is1
E/MTPRx   ( 5180): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5180): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5180): Status for mount/Unmount :removed
,E/MTPRx   ( 5180): SDcard is not available
,W/MTPRx   ( 5180): value of connected istrue
W/MTPRx   ( 5180): value of configured istrue
W/MTPRx   ( 5180): value of mtpEnabled istrue
W/MTPRx   ( 5180): value of ptpEnabled isfalse
,E/MTPRx   ( 5180): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 5180): mFirstTime: false
,D/        ( 5180): MTP: reading debug level property
,E/MTPJNIInterface( 5180): Getting CryptionKey from JAVA
,E/MTPRx   ( 5180): currentUserId is 0
,E/MTPRx   ( 5180): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5180): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5180): is_Privatemode is NOT 1
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/SecContentProvider( 1018): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 5180): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MTPRx   ( 5180): else part ... so first time!!!
,E/MTPPlaObsrvr( 5180): inside setContext()
E/MTPPlaObsrvr( 5180):  inside createplafiles
,I/SecKeyguardClockSingleView( 1185): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5180): playlist count is0
,E/MTPPlaObsrvr( 5180):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5180):  inside deleteing plas createplafiles
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4235/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10036/pid_4000/cgroup.procs: No such file or directory
,E/MTPPlaObsrvr( 5180): Inside registerContentObserver
,E/MtpAdbObserver( 5180): inside setContext(),
E/MtpAdbObserver( 5180): Inside registerContentObserver
W/Settings( 5180): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,I/ActivityManager( 1018): Process com.sec.android.app.wluc (pid 4912)(adj 15) has died(53,619)
,V/MtpMediaDBManager( 5180): inside deleteAllDB
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,W/MTPRx   ( 5180): calling native method
E/MTPJNIInterface( 5180): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 5180): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5180): noti = 10
,E/MtpService( 5180): onCreate.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5180): < MTP > Registering BroadCast receiver :::::
,V/MtpMediaDBManager( 5180): inside Thread updateDB
,D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpMediaDBManager( 5180): count : 26
,E/MtpService( 5180): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5180): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/TMNetworkReceiver( 4758): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 4758): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 4758): MirrorLink feauture level: using UEvent
,E/MtpService( 5180): onStartCommand.
,E/MtpService( 5180): onStartCommand.
W/MTPRx   ( 5180): calling native method
E/MTPRx   ( 5180): Checking the driver time out
E/MTPJNIInterface( 5180): noti = 2
D/        ( 5180): deleting sockets before message queue initialization
,D/        ( 5180): event handler thread is created, so set the flag
,E/MtpService( 5180): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 5180): called native method
W/ActivityManager( 1018): userId = 0, bbcId = -10000
E/MTPJNIInterface( 5180): setting Media scanner status0
E/MTPJNIInterface( 5180): After setting Media scanner status0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/MTPRx   ( 5180): notification from stack 1
,E/        ( 5180): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5180): Getting media scanner status0
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_CHANGED, mSplitNum[0]=5, mSplitNum[1]=8, mSplitNum[2]=11, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=14
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_CHANGED !! Enqueue -> schedule it!!
,E/MTPJNIInterface( 5180): DeviceName is Thali Test (Galaxy A3)
,E/MtpService( 5180): handleMessage. msg= { when=-11ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5202): MountEmulatedStorage(),
I/libpersona( 5202): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5202): v2
I/libpersona( 5202): KNOX_SDCARD not a persona
I/SELinux ( 5202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5202 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5202): TimaSignature is unavailable
,D/ActivityThread( 5202): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5217): MountEmulatedStorage(),
E/Zygote  ( 5217): v2
I/libpersona( 5217): KNOX_SDCARD checking this for 10029,
I/libpersona( 5217): KNOX_SDCARD not a persona
,I/SELinux ( 5217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5217 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SELinux ( 5217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/MtpMediaDBManager( 5180): sending db update complete noti to stack
E/MTPJNIInterface( 5180): noti = 29
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2031): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5202): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 1018): Background sticky concurrent mark sweep GC freed 128129(4MB) AllocSpace objects, 0(0B) LOS objects, 7% free, 45MB/49MB, paused 5.084ms total 160.450ms
,D/TimaKeyStoreProvider( 5217): TimaSignature is unavailable
,D/ActivityThread( 5217): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 3221): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/Zygote  ( 5234): MountEmulatedStorage()
,E/Zygote  ( 5234): v2
I/libpersona( 5234): KNOX_SDCARD checking this for 10026
I/libpersona( 5234): KNOX_SDCARD not a persona
,I/SELinux ( 5234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5234 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5234): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SMD     (  294): DCD OFF
,D/TimaKeyStoreProvider( 5234): TimaSignature is unavailable
I/libpersona( 5249): KNOX_SDCARD checking this for 10065
E/Zygote  ( 5249): MountEmulatedStorage()
I/libpersona( 5249): KNOX_SDCARD not a persona
E/Zygote  ( 5249): v2
D/ActivityThread( 5234): Added TimaKeyStore provider
I/SELinux ( 5249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5249 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5261): MountEmulatedStorage()
E/Zygote  ( 5261): v2
I/libpersona( 5261): KNOX_SDCARD checking this for 1000
I/libpersona( 5261): KNOX_SDCARD not a persona
,I/SELinux ( 5261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 5249): TimaSignature is unavailable
,D/ActivityThread( 5249): Added TimaKeyStore provider
I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=5261 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 2031): Null package name or gms related package.  Ignoreing.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 5180): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5180): SDcard is not available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5261): TimaSignature is unavailable
,D/ActivityThread( 5261): Added TimaKeyStore provider
,E/        ( 5180): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 5180): Status for mount/Unmount :removed
E/MTPJNIInterface( 5180): SDcard is not available
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5180): (21) API call with NULL database connection pointer
E/SQLiteLog( 5180): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5180): notification from stack 2
,D/        ( 5180): [mtp_init_device] Library open with 32 bits.
D/        ( 5180): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5180): [mtp_init_device 702]  After open the MTP fd = 31 and line = 702...
D/        ( 5180): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5180):  [sua_support_present:1287] returning false 
D/        ( 5180): *****Starting mtp_io()
,W/MTPRx   ( 5180): notification from stack 3
D/        ( 5180): [mtp_start_io] source_thread Creation 
D/        ( 5180): [mtp_start_io] sink_thread Creation 
D/        ( 5180): [mtp_start_io:376] sink thread created so set th_sink
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/FeatureConfig( 5217): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1018): Killing 4600:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2031): updateResources: need to parse f{com.google.android.gms}
,I/PackagesMonitor( 4843): PackagesMonitor onReceive :com.google.android.gms
,D/ShortcutReceiver( 5261):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_4600/cgroup.procs: No such file or directory
,D/FileShare-Server( 5249): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ResourcesManager( 5217): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{3d8f35c u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/ActivityManager( 1018): Killing 4634:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5217): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_4634/cgroup.procs: No such file or directory
,W/ResourcesManager( 5217): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5234): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 5217): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5217): system/finder_cp/cpdata.xml file not found
,D/Finsky  ( 5234): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5234): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5234): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/UpdateIcingCorporaServi( 3221): UpdateCorporaTask done [took 556 ms] updated apps [took 556 ms] 
,D/Finsky  ( 5234): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5234): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager( 1018): Killing 4651:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/Ads     ( 5234): Skipping gmscore version check
,D/Finsky  ( 5234): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_CHANGED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
D/MediaScannerReceiver( 1224): action: com.samsung.intent.action.MTP_FILE_SCAN
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/Finsky  ( 5234): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1800): callingUid 10011, callindPid: 1800
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4651/cgroup.procs: No such file or directory,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/MusicLeanback( 4348): Conditions not met for autocaching.
I/MusicLeanback( 4348): Stop autocaching.
,D/MediaScannerService( 1224): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/SettingSearch/SearchIntentReceiver( 1302): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1302): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1302): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1302): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
,W/ResourcesManager( 4348): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
,W/ResourcesManager( 4348): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaScanner( 1224): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,V/MediaScanner( 1224): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1224): Skipping:
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(75ebcf7
,I/GHttpClientFactory( 4348): Using the GMSCore's GoogleHttpClient
,D/MediaScanner( 1224): Skipping:
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1224): processDirectory :  /storage/extSdCard
W/MediaScanner( 1224): Error opening directory, reason : Permission denied.
W/MediaScanner( 1224): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1224):  prescan time: 44ms (DB items: 26)
V/MediaScanner( 1224):     scan time: 23ms (Caching mode: true), (makeEntry time: 8ms ~34%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1224): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1224):    total time: 70ms
V/MediaScanner( 1224): checked files: 10  directories : 16  (I: 0, U: 0)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5180): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/MediaScannerService( 1224): !@done scanning volume external
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2031): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/art     ( 1224): Explicit concurrent mark sweep GC freed 6560(411KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 666us total 28.182ms
,I/SettingSearch/SettingsSearchManager( 1302): Infomation -> numtitleinfo : 0 numSearchinfo : 305
,D/WearableClient( 4348): WearableClientImpl.onPostInitHandler: done
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableClient( 4348): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 4348): WearableClientImpl.onPostInitHandler: done
,I/iu.UploadsManager( 2031): End new media; added: 0, uploading: 0, time: 86 ms
,D/WearableClient( 4348): WearableClientImpl.onPostInitHandler: done
,I/SettingSearch/SettingsSearchManager( 1302):  Infomation -> getItem size : 305
,E/GmsUtils( 4348): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/GmsUtils( 4348): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,E/ActivityThread( 4348): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2cf2cf29 that was originally bound here
E/ActivityThread( 4348): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2cf2cf29 that was originally bound here
E/ActivityThread( 4348): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4348): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4348): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4348): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4348): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4348): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 4348): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 4348): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 4348): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 4348): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 4348): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 4348): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 4348): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 4348): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 4348): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 4348): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 4348): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 4348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 4348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4348): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4348): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 4348): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4348): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 4348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ResourcesManager( 1302): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1465): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1465): Media DB Scanner finished.
D/CscFactoryReceiver( 1465): start service to Set Ringtone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1465): start service to Set Notification
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1465): start service to Set Alarmtone
,I/ActivityManager( 1018): Killing 4670:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1465): onStart
E/CscUpdateService( 1465): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1465): only ringtone update
,D/CscUpdateService( 1465): onStart
E/CscUpdateService( 1465): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1465): only notification update
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1465): onStart
E/CscUpdateService( 1465): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1465): only alarmtone update
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/CscParser( 1465): update(): xml file exist
,E/CscParser( 1465): update(): xml file exist
,W/CSCSettings( 1465): Setting Ringtones (type) : 1
,D/CscParser( 1465): RingTone: null,
W/CSCSettings( 1465): 1. Tag_Str: null
,E/CscParser( 1465): update(): xml file exist
I/ActivityManager( 1018): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5335 uid=10005 gids={50005, 9997, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5335): MountEmulatedStorage()
I/libpersona( 5335): KNOX_SDCARD checking this for 10005
E/Zygote  ( 5335): v2
I/libpersona( 5335): KNOX_SDCARD not a persona
I/SELinux ( 5335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/CSCSettings( 1465): Setting Ringtones (type) : 2
D/CscParser( 1465): MessageTone: null
W/CSCSettings( 1465): 1. Tag_Str: null
E/SELinux ( 5335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1465): Setting Ringtones (type) : 4
,D/CscParser( 1465): AlarmTone: null
W/CSCSettings( 1465): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5335): TimaSignature is unavailable
,D/ActivityThread( 5335): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10090/pid_4670/cgroup.procs: No such file or directory
,I/ThumbnailProvider( 5335): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5335): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5335): [START] processBroadcastIntent ...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4843): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5335): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5335): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5335): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5335): [START] DocumentService startDocumentService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/GalleryCacheReady( 4843): handleMeidaScanFinish()
,D/FaceInterface( 4843): requestFaceScan() is called.
,I/DocumentService( 5335): DocumentService onCreate ... service
,W/LocalSuggestAlbumData( 4843): query fail: 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5335): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,W/LocalSuggestAlbumData( 4843): query fail: 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
D/BluetoothMediaBrowser( 2583):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/FaceInterface( 4843): startFaceScan() : waiting 5 sec
,D/BluetoothMediaBrowser( 2583): no now playing list
,W/ContextImpl( 5335): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2583):  getNowPlayingId now playing id : -1
,E/SystemInfo( 5335): [SIOP LEVEL] : 0
,I/DocumentService( 5335): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5335): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 5335): fail readDirectory() errno=13
,E/File    ( 5335): fail readDirectory() errno=13
,I/SystemInfo( 5335): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5335): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5335): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :38
E/DocumentService( 5335): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5335): [INDEX] Total time taken for each file :0
,I/DocumentService( 5335): DocumentService onDestroy start
,I/DocumentService( 5335): DocumentService onDestroy end
,I/DocumentService( 5335): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5335): InterruptedException: null
,I/SystemInfo( 5335): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5335): DocumentService cleanupEverything end
I/Process ( 5335): Sending signal. PID: 5335 SIG: 9
,I/MediaStoreImporter( 4348): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/Icing   ( 2031): Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,I/FaceInterface( 4843): startFaceScan() : going on
I/ActivityManager( 1018): Process com.samsung.indexservice (pid 5335)(adj 9) has died(31,622)
,D/FaceInterface( 4843): startFaceScan() is called.
,D/ContentApp( 1224): startScan() is called.
,D/FaceValue( 1224): mSleepTime: 800
D/FaceValue( 1224): mMaxThreadNum: 2
,W/FaceValue( 1224): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1224): startScan() is end.
,D/ContentApp( 1224): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1224): isNeedToRestore : start
,W/art     ( 2031): Suspending all threads took: 8.356ms
,D/Icing   ( 2031): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2031): Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,I/art     ( 2031): Background sticky concurrent mark sweep GC freed 21412(1510KB) AllocSpace objects, 13(208KB) LOS objects, 13% free, 10MB/11MB, paused 12.192ms total 57.353ms
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1302): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1302): LOCALE_CHANGED call search setting db finish!!
,I/FaceInterface( 4843): startFaceScan() : going on,
D/FaceInterface( 4843): startFaceScan() is called.
,D/ContentApp( 1224): startScan() is called.
,D/ContentApp( 1224): startScan() is end.
,D/ContentApp( 1224): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1224): isNeedToRestore : start
,I/art     ( 1018): Background partial concurrent mark sweep GC freed 154501(5MB) AllocSpace objects, 2(1818KB) LOS objects, 27% free, 42MB/58MB, paused 3.901ms total 223.951ms
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 4931): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4315, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2583): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,I/art     ( 1018): Background sticky concurrent mark sweep GC freed 78330(2MB) AllocSpace objects, 2(1818KB) LOS objects, 4% free, 55MB/58MB, paused 2.925ms total 106.503ms
,W/PackageManager( 1018): verifying app can be installed or not
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1018): ship mode
,I/art     ( 1018): Background partial concurrent mark sweep GC freed 339964(20MB) AllocSpace objects, 1(1802KB) LOS objects, 27% free, 42MB/58MB, paused 3.427ms total 251.529ms
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/CheckinService( 2031): Done disabling old GoogleServicesFramework version
,D/PackageManager( 1018): Existing package
,D/PackageManager( 1018): Renaming /data/app/vmdl770913713.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1018): installNewPackageLI: Package{2b78cadc com.test.thalitest}
,I/PackageManager( 1018): scanFileNewer : com.test.thalitest
,I/SELinux (  285): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory,
D/PackageManager( 1018): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5368): ----------------------------------------------------
,I/dex2oat ( 5368): <SS>: S T A R T I N G . . .
I/dex2oat ( 5368): <SS>: going to process manifest for 32-bit...
,I/        ( 5368): SS_ART_lib [I]: Memory allocation: ctx
,I/        ( 5368): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5368): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5368): SS_ART_lib [I]: Memory allocation: ctx->libs
,I/        ( 5368): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5368): SS_ART_lib [I]: Parsing completed
I/        ( 5368): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5368): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5368): SS_ART_lib [I]: access to SS denied
I/        ( 5368): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5368): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5368): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5368): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5368): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5368): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5368): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/dex2oat ( 5368): dex2oat took 461.841ms (threads: 4)
,I/PackageManager( 1018): do mInstaller.dexopt : 0
,D/PackageManager( 1018): Time to dexopt: 0.542 seconds
,W/System.err( 1018): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1018): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1018): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5127)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19341)
,W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.access$5500(PackageManagerService.java:339)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService$21.run(PackageManagerService.java:19326)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:446)
,W/System.err( 1018): 	... 5 more
,I/HarmonyEASService( 1018): Updating for all 1
D/PackageManager( 1018): New package installed
,D/PackageManager( 1018): doPostInstall for uid{10167}
,D/PackageManager( 1018): token 1 to BM for possible restore
,V/BackupManagerService( 1018): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1018): Finishing install immediately
,D/PackageManager( 1018): BM finishing package install for 1
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,D/PackageManager( 1018): [MSG] POST_INSTALL: observer{32702368}
D/PackageManager( 1018):           Handling post-install for 1
,W/Settings( 1018): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,I/ActivityManager( 1018): Killing 4722:com.wsomacp/u0a23 (adj 15): empty #31
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1831): mOCRHelper is null
,D/RCPManagerService( 1018): PackageReceiver onReceive()
D/RCPManagerService( 1018): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1018):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1018):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/RegisteredServicesCache( 1456): empty dynamic service
,I/HomeSyncInstallReceiver( 1456): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
,I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5378 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 5378): MountEmulatedStorage(),
E/Zygote  ( 5378): v2
I/libpersona( 5378): KNOX_SDCARD checking this for 10014
I/libpersona( 5378): KNOX_SDCARD not a persona
,I/SELinux ( 5378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 5378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/PackagesMonitor( 4843): PackagesMonitor onReceive :com.test.thalitest
,E/SELinux ( 5378): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  316): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 36.713ms
,D/TimaKeyStoreProvider( 5378): TimaSignature is unavailable
,D/ActivityThread( 5378): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 17.184ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 637us total 16.530ms
,E/Zygote  ( 5393): MountEmulatedStorage()
E/Zygote  ( 5393): v2
I/libpersona( 5393): KNOX_SDCARD checking this for 10087
I/libpersona( 5393): KNOX_SDCARD not a persona
,I/SELinux ( 5393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
E/SELinux ( 5393): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5393 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/BackupManagerService( 1018): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1018): uID is 10167
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1018): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KnoxMUMContainerPolicy( 1018): packageInstalledForExternalStorage com.test.thalitest
,D/TimaKeyStoreProvider( 5393): TimaSignature is unavailable
,D/ActivityThread( 5393): Added TimaKeyStore provider
,D/Mms/FreeMessageStatusReceiver( 4619): onReceive, action : android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PackageBroadcastService( 2031): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2031): Loading module APK com.google.android.play.games
,E/Zygote  ( 5410): MountEmulatedStorage()
,E/Zygote  ( 5410): v2
I/libpersona( 5410): KNOX_SDCARD checking this for 10042
I/libpersona( 5410): KNOX_SDCARD not a persona
,I/SELinux ( 5410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Mms/FreeMessageReceiverService( 4619): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 4619): onHandleIntent: ACTION_PACKAGE_ADDED
I/SELinux ( 5410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5410): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5410 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 294332(17MB) AllocSpace objects, 11(3MB) LOS objects, 29% free, 37MB/53MB, paused 3.564ms total 346.444ms
,D/PackageManager( 1018): result of install: 1{32702368}
,I/PackageManager( 1018): Observer no longer exists.
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 5410): TimaSignature is unavailable
D/ActivityThread( 5410): Added TimaKeyStore provider
,W/ResourcesManager( 5410): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5410): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5410): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5429): MountEmulatedStorage()
,E/Zygote  ( 5429): v2
I/libpersona( 5429): KNOX_SDCARD checking this for 1000
I/libpersona( 5429): KNOX_SDCARD not a persona
,I/SELinux ( 5429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4778:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5429): TimaSignature is unavailable
,D/ActivityThread( 5429): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 5429): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5429): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5429): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5429): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5429): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5429): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5429): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5444): MountEmulatedStorage()
I/libpersona( 5444): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5444): v2
I/libpersona( 5444): KNOX_SDCARD not a persona
,I/SELinux ( 5444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ResourcesManager( 5217): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
I/SELinux ( 5444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/SMD     (  294): DCD OFF
,I/ActivityManager( 1018): Killing 4869:com.sec.smartcard.manager/u0a149 (adj 15): empty #31
,W/ResourcesManager( 5217): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5444): TimaSignature is unavailable
,D/ActivityThread( 5444): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4
,D/MyFiles ( 5410): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/DocsApplication( 5393): Installing DEX configuration.
,W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/installd(  285): system dir 0 : /system/app/
E/installd(  285): system dir 1 : /system/priv-app/
E/installd(  285): system dir 2 : /vendor/app/
E/installd(  285): system dir 3 : /oem/app/
,W/ResourcesManager( 5217): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5217): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/DexInstaller( 5393): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,W/ResourcesManager( 5217): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/PackageInfoHelper( 5393): Provided clientMode=RELEASE, packageInfo=PackageInfo{20dbb118 com.google.android.apps.docs}
,W/ResourcesManager( 5217): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,V/AlarmManager( 1018): waitForAlarm result :4
,I/TactileAssist( 1018): enable value -1
,I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,I/TactileAssist( 1018): List of disabled apps :
,W/TextServicesManagerService( 1018): no available spell checker services found
,D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 5217): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5461): MountEmulatedStorage()
,E/Zygote  ( 5461): v2
I/libpersona( 5461): KNOX_SDCARD checking this for 10048
,I/libpersona( 5461): KNOX_SDCARD not a persona
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 5217): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5461 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 5461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5461): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/TAG     ( 5393): onCreate()
,D/TimaKeyStoreProvider( 5461): TimaSignature is unavailable,
D/ActivityThread( 5461): Added TimaKeyStore provider
,D/CrossAppStateProvider( 5393): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/DBG_POLICYDM( 5444): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,I/FaceInterface( 4843): startFaceScan() : going on
D/FaceInterface( 4843): startFaceScan() is called.
,D/ContentApp( 1224): startScan() is called.
D/ContentApp( 1224): startScan() is end.
,D/ContentApp( 1224): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1224): isNeedToRestore : start
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Compatibility( 5461): onReceive() it will make start service
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Compatibility( 5461): onHandleIntent()
D/Compatibility( 5461): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10167, android.intent.extra.user_handle=0}]
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/CrashAnrDetector( 1018): onPackageAdded : com.test.thalitest
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_4722/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_4778/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10149/pid_4869/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Compatibility( 5461): found: 2
,I/UpdateIcingCorporaServi( 3221): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/art     ( 2031): Verification of void com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0(android.content.Context, com.google.android.gms.common.app.BaseApplicationContext) took 176.663ms
,W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/Compatibility( 5461): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5461): skipping ResolveInfo{3e0fe771 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5461): considering ResolveInfo{37b02956 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5461): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5461): enabling receiver ResolveInfo{311dfdd7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5461): enabling receiver ResolveInfo{3866c6c4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5461): enabling receiver ResolveInfo{13ea89ad com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5461): enabling receiver ResolveInfo{199d84e2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5461): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.games from APK com.google.android.play.games
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraModuleLdr( 2031): Module APK com.google.android.play.games already loaded
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2031): Submit a task: k
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2031): Processing package: com.test.thalitest
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GassUtils( 2031): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2031): Found info for package com.test.thalitest in db.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 3221): UpdateCorporaTask done [took 350 ms] updated apps [took 350 ms] 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5444): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5444): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/Zygote  ( 5501): MountEmulatedStorage()
,E/Zygote  ( 5501): v2
I/libpersona( 5501): KNOX_SDCARD checking this for 10009
I/libpersona( 5501): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/SELinux ( 5501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/SELinux ( 5501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5501): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5444): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!,
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5501 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5444): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/TimaKeyStoreProvider( 5501): TimaSignature is unavailable
D/SSRM:n  ( 1018): SIOP:: AP = 420
,D/ActivityThread( 5501): Added TimaKeyStore provider
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Zygote  ( 5516): MountEmulatedStorage(),
E/Zygote  ( 5516): v2
I/libpersona( 5516): KNOX_SDCARD checking this for 10036,
I/libpersona( 5516): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5516 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 4973:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,I/SELinux ( 5516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5516): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5516): TimaSignature is unavailable
D/ActivityThread( 5516): Added TimaKeyStore provider
,I/PeopleDatabaseHelper( 2031): cleanUpNonGplusAccounts done.
,I/DBG_POLICYDM( 5444): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5444): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5444): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0,
I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5444): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5444): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/02/12/15:25:42
,I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/02/08/17:24:09
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5444): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5444): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5444): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5444): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5444): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5444): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4973/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5444): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/Finsky  ( 5234): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,I/SA      ( 5516): [SSP] onCreated
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,I/ActivityManager( 1018): Killing 5054:com.sec.android.app.sns3/u0a30 (adj 15): empty #31
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,W/art     ( 5393): Suspending all threads took: 8.087ms
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,I/SA      ( 5516): [TPM] There is no property file
,I/SA      ( 5516): [SCU] isHaveSA() - false
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/SA      ( 5516): [TPM] getModelProperty : null
,I/SA      ( 5516): [TPM] getCSCProperty : null
,I/SA      ( 5516): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 5516): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5516): [DM] TFT FEATURE: false
,I/SA      ( 5516): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/DBG_POLICYDM( 5444): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,W/BaseAppContext( 2031): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 5444): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/SA      ( 5516): [DM] init START
,I/SA      ( 5516): [DM] This device is not a Vodafone
,W/ResourceType( 5516): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5516): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5516): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5516): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 5516): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5516): [SCU] isHaveSA() - false
I/SA      ( 5516): support phone number id : false
I/SA      ( 5516): [DM] Supports Ref Jpn : true
,I/SA      ( 5516): [DM] init END
I/SA      ( 5516): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5516): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10167 extra.user_handle.:0 ]
,I/ActivityManager( 1018): Killing 5107:com.sec.spp.push:RemoteDlcProcess/u0a32 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10030/pid_5054/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5107/cgroup.procs: No such file or directory
,W/art     ( 2031): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 103.344ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5541): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5541 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 5541): v2
I/libpersona( 5541): KNOX_SDCARD checking this for 1000
I/SELinux ( 5541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5541): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5127:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
I/SELinux ( 5541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5393): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5541): TimaSignature is unavailable
,D/ActivityThread( 5541): Added TimaKeyStore provider
,D/FilterInstaller( 5541): onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,W/ContextImpl( 5541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/FilterInstaller( 5541): FilterPackageService : ACTION_CHANGED
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5127/cgroup.procs: No such file or directory
,E/Zygote  ( 5563): MountEmulatedStorage()
E/Zygote  ( 5563): v2
,I/libpersona( 5563): KNOX_SDCARD checking this for 10098
I/libpersona( 5563): KNOX_SDCARD not a persona
,I/SELinux ( 5563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5563 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5563): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller( 5541): installFilters
,E/FilterInstaller( 5541): There is no requred permission
,D/TimaKeyStoreProvider( 5563): TimaSignature is unavailable
,D/ActivityThread( 5563): Added TimaKeyStore provider
,I/Icing   ( 2031): Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2031): Module APK com.google.android.play.games already loaded
,D/PackageIntentReceiver( 5563): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5563): Not GearManger package! 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5581): MountEmulatedStorage()
E/Zygote  ( 5581): v2
I/libpersona( 5581): KNOX_SDCARD checking this for 1000
I/libpersona( 5581): KNOX_SDCARD not a persona
,I/SELinux ( 5581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5581 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4689:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #31
E/SELinux ( 5581): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5581): TimaSignature is unavailable
,D/ActivityThread( 5581): Added TimaKeyStore provider
,I/Icing   ( 2031): Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,I/Icing   ( 2031): Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2031): Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,E/Zygote  ( 5598): MountEmulatedStorage(),
E/Zygote  ( 5598): v2
I/libpersona( 5598): KNOX_SDCARD checking this for 1000,
I/libpersona( 5598): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5598 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5598): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4045:com.android.calendar/u0a131 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10130/pid_4689/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5598): TimaSignature is unavailable
,I/art     (  316): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 24.527ms
,D/ActivityThread( 5598): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.564ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.680ms,
,D/AcmsPackageEventListener( 5598): Received: android.intent.action.PACKAGE_ADDED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ContextImpl( 5598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 5598): Enter Oncreate
D/AcmsServiceMonitor( 5598): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5598): creating AcmsCore
,D/AcmsCore( 5598): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5598): AcmsCore
,D/AcmsCore( 5598): init
D/AcmsCore( 5598): Looper handler is not null
D/AcmsCore( 5598): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5598): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5598): Incrementing - Counter value: 1
D/AcmsCore( 5598): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5598): onStartCommand
D/AcmsService( 5598): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5598): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5598): Incrementing - Counter value: 2
D/AcmsService( 5598): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 5598): AcmsCertificateMngr
D/AcmsRevocationMngr( 5598): AcmsRevocationMngr
,D/ActivityThread( 5598): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/GAV2    ( 5393): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_4045/cgroup.procs: No such file or directory
,D/AcmsService( 5598): Inside handle Intent
D/AcmsService( 5598): App added - package name: com.test.thalitest
D/AcmsCore( 5598): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5598): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5598): Incrementing - Counter value: 3
D/AcmsCore( 5598): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5598): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5598): Decrementing - Counter value: 2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5617 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 5617): MountEmulatedStorage()
I/libpersona( 5617): KNOX_SDCARD checking this for 10148
E/Zygote  ( 5617): v2
I/libpersona( 5617): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 4063:com.android.providers.calendar/u0a37 (adj 15): empty #31
I/SELinux ( 5617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5617): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5617): TimaSignature is unavailable
,D/ActivityThread( 5617): Added TimaKeyStore provider
,E/SQLiteLog( 5617): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5632): MountEmulatedStorage(),
,E/Zygote  ( 5632): v2
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5632 uid=10152 gids={50152, 9997} abi=armeabi-v7a
I/SELinux ( 5632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5632): KNOX_SDCARD checking this for 10152
I/libpersona( 5632): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5150:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/SELinux ( 5632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5632): TimaSignature is unavailable
,D/ActivityThread( 5632): Added TimaKeyStore provider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5632): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5632): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 5632): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5632): Widget is not attached.
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5165:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10037/pid_4063/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5150/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5165/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 5598):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5598): Key Store exist
,I/AcmsKeyStoreHelper( 5598): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5598):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5598): getKeyStoreForApplication success 
D/AcmsCore( 5598): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 5598): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter,
D/AcmsServiceMonitor( 5598): Decrementing - Counter value: 1,
D/AcmsCore( 5598): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5598): This is NOT a valid MirrorLink app
,D/AcmsCore( 5598): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5598): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5598): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5598): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor( 5598): getSvcCounter - Counter value: 0
D/AcmsService( 5598): Enter onDestroy
I/AcmsService( 5598): cleanUp(): inside service clean up
D/AcmsCore( 5598): AcmsCore: inside DeInit
,D/AcmsCore( 5598): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5598): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5598): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5598): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5598): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5598): getSvcCounter - Counter value: 0
D/AcmsService( 5598): killing acms process
I/Process ( 5598): Sending signal. PID: 5598 SIG: 9
,I/ActivityManager( 1018): Process ACMS.Process (pid 5598)(adj 0) has died(60,601)
,E/SMD     (  294): DCD OFF
,I/DBG_POLICYDM( 5444): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5444): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/SensorService( 1018): [SO] -0.441 -0.057 9.902
,I/DBG_POLICYDM( 5444): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 195497(12MB) AllocSpace objects, 6(3MB) LOS objects, 33% free, 23MB/34MB, paused 2.449ms total 178.961ms
,I/iu.UploadsManager( 2031): End new media; added: 0, uploading: 0, time: 240 ms
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5393): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1185
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : -1
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1185): Icon Only
I/StatusBar( 1185): Icon Only
D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1185): Icon Only
I/StatusBar( 1185): Icon Only
D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): kidsfalse mQsExpansionEnabled:true
,D/BatteryMeterView( 1185): onDraw batteryColor : -1
,D/PanelView( 1185): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{eceaaf9 u0 com.samsung.android.MtpApplication/.MtpService}
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  294): DCD OFF,
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PackageManager( 1018): [MSG] MCS_UNBIND,
,I/ActivityManager( 1018): Killing 4758:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4758/cgroup.procs: No such file or directory
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
,D/lights  ( 1018): lcd : 15 +
,D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 15 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 1018): SIOP:: AP = 370
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/Finsky  ( 5234): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/SMD     (  294): DCD OFF
,I/System.out( 5234): Thread-872(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5234): Thread-872(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5234): Thread-872(ApacheHTTPLog):isShipBuild true
I/System.out( 5234): Thread-872(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5234): Thread-872(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10026
,I/qtaguid ( 5234): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5234, getuid(): 10026
,I/qtaguid ( 5234): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5234, getuid(): 10026
,I/qtaguid ( 5234): Untagging socket 44,
I/System.out( 5234): Thread-872 calls detatch()
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5234): Thread-873(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 5234): Thread-873(ApacheHTTPLog):isShipBuild true
I/System.out( 5234): Thread-873(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5234): Thread-873(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5234): Untagging socket 44
,I/qtaguid ( 5234): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5234): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5234): untagSocket(44) failed with errno -22
I/System.out( 5234): Thread-873 calls detatch()
,D/Finsky  ( 5234): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5666 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/Zygote  ( 5666): MountEmulatedStorage()
,E/Zygote  ( 5666): v2,
,I/libpersona( 5666): KNOX_SDCARD checking this for 10011
I/libpersona( 5666): KNOX_SDCARD not a persona,
,I/SELinux ( 5666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SELinux ( 5666): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5666): TimaSignature is unavailable
,D/ActivityThread( 5666): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5234): Thread-872(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5234): Thread-872(ApacheHTTPLog):isShipBuild true
I/System.out( 5234): Thread-872(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5234): Thread-872(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 5666): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5666): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5666): VM with version 2.1.0 has multidex support
I/MultiDex( 5666): install
I/MultiDex( 5666): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5666): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5234): Untagging socket 44
,W/ActivityThread( 5666): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5666): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fe96ec: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5666): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 5234): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5234): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5234): untagSocket(44) failed with errno -22
I/System.out( 5234): Thread-872 calls detatch()
,D/ChimeraCfgMgr( 5666): Reading stored module config
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ChimeraCfgMgr( 5666): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2031): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1800): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1800): Explicit concurrent mark sweep GC freed 35228(2MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 9MB/16MB, paused 1.362ms total 115.960ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 5666): Suspending all threads took: 18.580ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1800): callingUid 10011, callindPid: 1800
,E/MDM     ( 1800): [254] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/NativeLibraryUtils( 5666): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1800): No location to return for getLastLocation()
,W/FusedLocationProvider( 1800): location=null
,D/CAR.SERVICE( 5666): Connecting to CarCallService...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 5666): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5666): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5666): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5666): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5666): Creating a new PhoneAdapter instance
,W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5666): setListener: com.google.android.gms.car.dn@1a27baab
,W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5666): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5666): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5666): Package validated; name: com.android.vending
,V/Finsky  ( 5234): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5234): Thread-873(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5234): Thread-873(ApacheHTTPLog):isShipBuild true
I/System.out( 5234): Thread-873(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5234): Thread-873(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5234): Untagging socket 44,
I/qtaguid ( 5234): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5234): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5234): untagSocket(44) failed with errno -22
I/System.out( 5234): Thread-873 calls detatch()
,W/ResourcesManager( 5234): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5234): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5234): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/DeviceConnectionService( 1800): client connected with version: 8296000
,D/Finsky  ( 5234): [895] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5234): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5234): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5234): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5234): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5234): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5234): (HTTPLog)-Thread-883-648318075: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5234): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5234): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,I/ActivityManager( 1018): Killing 5202:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5202/cgroup.procs: No such file or directory
,D/SensorService( 1018): [SO] -0.441 -0.057 9.883
,E/SMD     (  294): DCD OFF
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{1bf48294 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): [PWL] On : 0 (74737 ms ago)
,I/PowerManagerService( 1018): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService( 1018): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10049, pid=1185, ws=null) (elapsedTime=8778)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/PersonaManager( 1185): isKioskContainerExistOnDevice,
D/PersonaManager( 1185): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1185): Icon Only
I/StatusBar( 1185): Icon Only
D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1185): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2031): getNumBytesRead when not calculated.
,E/SMD     (  294): DCD OFF
,D/CAR.SERVICE( 5666): mConnectedToCar = false, abort
,E/ActivityThread( 5666): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@165f7833 that was originally bound here
E/ActivityThread( 5666): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@165f7833 that was originally bound here
E/ActivityThread( 5666): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5666): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5666): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5666): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5666): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5666): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5666): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5666): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5666): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5666): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5666): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5666): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5666): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5666): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5666): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5666): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5666): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5666): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5666): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5666): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5666): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5666): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5666): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5666): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@261244fa that was originally bound here
E/ActivityThread( 5666): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@261244fa that was originally bound here
E/ActivityThread( 5666): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5666): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5666): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5666): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5666): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5666): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5666): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5666): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5666): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5666): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5666): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5666): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5666): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5666): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5666): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5666): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5666): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5666): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5666): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5666): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5666): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5666): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@361eef57
,V/AlarmManager( 1018): waitForAlarm result :8
,E/Watchdog( 1018): !@Sync 2
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1018): SIOP:: AP = 340
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1018): [PWL] On : 0 (79741 ms ago),
I/PowerManagerService( 1018): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService( 1018): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10049, pid=1185, ws=null) (elapsedTime=13781)
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SensorService( 1018): [SO] -0.421 -0.057 9.864
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,V/WindowOrientationListener( 1018): WindowOrientationListener disabled
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1185 (0x0)
D/SensorService( 1018): [SO] activate (ident=0xb84e19b8, enabled=0)
I/PowerManagerService( 1018): Nap time (uid 1000)...
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0,
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),-1 flag=20004, DolorFade,
,D/SensorManager( 1018): unregisterListener ::   
,D/KeyguardViewMediator( 1185): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1185): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1185): changeWallpaperByScreenOff()
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createSurface: 12ms
,I/Adreno-EGL( 1018): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1018): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1018): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1018): Local Branch: 
I/Adreno-EGL( 1018): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1018): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1018):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1185): notifyScreenOffLocked
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1185): timeout : 5000
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1185): setting alarm to turn off keyguard, seq = 1,
D/KeyguardViewMediator( 1185): handleNotifyScreenOff
D/VolumePanel( 1185): onScreenTurnedOff()
,V/ActivityThread( 3058): updateVisibility : ActivityRecord{79ceb34 token=android.os.BinderProxy@1e05e0aa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/VolumePanel( 1185): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1185): mCoverBroadcastReceiver: Screen OFF end
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,D/SecKeyguardClockSingleView( 1185): onScreenTurnedOff
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglContext: 77ms
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (447 us)
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 20ms
,I/StatusBar( 1185): Icon Only
,D/PanelView( 1185): There is/are notification(s) 
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NotificationService( 1018): ACTION_SCREEN_ON
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PanelView( 1185): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
,V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,E/WifiNative-wlan0( 1018): do suspend false
,I/wpa_supplicant( 1389): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1389): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1389): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1389): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1456): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1456): call the applyRouting
D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 70ms
,D/PowerManagerService( 1018): Excessive delay in ColorFade prepare: 197ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 31 -> 31
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,D/accuweather( 1718): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance,
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance,
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1831): getNextShiftState() cursorCapsMode : 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/StatusBar( 1185): Icon Only
,D/PanelView( 1185): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/SamsungIME( 1831): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true,
,D/comsamsunglog( 1778): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1778): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1778): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1778): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/NotificationService( 1018): ACTION_SCREEN_OFF,
D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454970180000
D/daemonapp( 1778): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454948676358
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,D/daemonapp( 1778): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1778): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
E/daemonapp( 1778): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1430): [EmergencyStateReceiver] binteractive [false] why[3]
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,D/NfcService( 1456): call the applyRouting
,D/accuweather( 1718): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1718): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1718): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/accuweather( 1718): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1718): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/lights  ( 1018): lcd : 0 +
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1847): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/daemonapp( 1778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(false) while turning screen off: 52ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(false): 55ms
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb79bf690
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager( 1018): Display changed displayId=0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,I/wpa_supplicant( 1389): nl80211: Received scan results (2 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1018): DefaultState{ what=147461 }
,E/WifiNative-wlan0( 1018): do suspend true
,D/StatusBar.NetworkController( 1185): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :4
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 237ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 238ms
,I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 295ms
,I/PowerManagerService( 1018): [PWL] Off : 0s ago
,D/Finsky  ( 5234): [885] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5234): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000,
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardViewMediator( 1185): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1185): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1185): *** Keyguard wallpaper service already unbounded
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 5s ago,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 310,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 15s ago,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/SecKeyguardClockView( 1185): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1185): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1185): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1800): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1800): Vacuum at: now=1454948701588 tag=VacuumService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 51142(2MB) AllocSpace objects, 26(416KB) LOS objects, 33% free, 23MB/34MB, paused 2.450ms total 146.512ms
,I/PhenotypeConfigurator( 1800): Scheduling Phenotype for one-off execution 5342 seconds from now (1454948702147)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1800): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/FactoryTest( 5180): Not factory mode
,D/FactoryTest( 5180): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5180): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5180): still no open session command from host, so toast
,W/ContextImpl( 5180): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,I/Timeline( 5180): Timeline: Activity_launch_request id:com.android.settings time:112158
W/ContextImpl( 5180): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/ActivityManager( 1018): Display changed displayId=0
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 3058
,E/MTPRx   ( 5180): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5180): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5180): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5180): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5180): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5180): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5180): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PhenotypeFlagCommitter( 1800): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,E/SMD     (  294): DCD OFF
,E/SettingsReceiverActivity( 5180): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus entered window: 3058
,I/GoogleURLConnFactory( 1800): Using platform SSLCertificateSocketFactory
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2b4953c5 attribute=android.view.inputmethod.EditorInfo@151ce11a, token = android.os.BinderProxy@3dd0ec83
,D/SamsungIME( 1831): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5180): dev.kiessupport is : TRUE
,D/PhoneWindow( 5180): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5180): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 19
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1185): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1185): Icon Only
I/StatusBar( 1185): Icon Only
,D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 19
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1185): Icon Only
I/StatusBar( 1185): Icon Only
,D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3058): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3058): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] ,
,I/Timeline( 3058): Timeline: Activity_idle id: android.os.BinderProxy@1e05e0aa time:112449
,V/ActivityThread( 3058): updateVisibility : ActivityRecord{79ceb34 token=android.os.BinderProxy@1e05e0aa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/PanelView( 1185): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1800): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1800): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1800): (HTTPLog)-Static: isShipBuild true
I/System.out( 1800): (HTTPLog)-Thread-261-738819674: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1800): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1800): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1800): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1800, getuid(): 10011
,I/qtaguid ( 1800): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1800, getuid(): 10011
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1800): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1800): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1800, getuid(): 10011
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1800): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1800): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1800, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): mDVFSHelper.release(),
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=7_task.xml,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,I/PowerManagerService( 1018): [PWL] Off : 30s ago,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,I/PowerManagerService( 1018): [PWL] Off : 50s ago,
,E/Watchdog( 1018): !@Sync 4,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 75s ago,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,I/ClearcutLoggerApiImpl( 1800): disconnect managed GoogleApiClient
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/SecKeyguardClockView( 1185): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1185): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1185): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 6,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/Watchdog( 1018): !@Sync 7,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  294): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...,
I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  294): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 275s ago,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 12
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=409935 batch.start=797551,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 14
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 15
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/bootchecker(  331): bootchecker wake up!!,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 16
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 17
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 18
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,I/Atfwd_Daemon(  334): Stop the daemon....,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 19
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 20,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ActivityManager( 1018): Killing 5249:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10065/pid_5249/cgroup.procs: No such file or directory
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 21
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 22
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate,
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2583): Disconnected process message: 10
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 23
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 681s ago
,E/Watchdog( 1018): !@Sync 25
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/SecKeyguardClockView( 1185): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1185): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1185): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2031): Aggregate from 1454947395963 (log), 1454947395963 (data)
,E/Watchdog( 1018): !@Sync 26
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 27
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 766s ago
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 28
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 29
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  294): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/SecKeyguardClockView( 1185): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1185): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1185): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 856s ago
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 31,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 32,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 33,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 951s ago
,E/Watchdog( 1018): !@Sync 34,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2583): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2583): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1185): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1185): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 35,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/Watchdog( 1018): !@Sync 36,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 37,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 1051s ago,
,E/SMD     (  294): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 38,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 39,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1454949805467
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1454949805848
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 40,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1156s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/Watchdog( 1018): !@Sync 41,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  294): DCD OFF
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/AndroidRuntime( 6220): 
D/AndroidRuntime( 6220): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6220): CheckJNI is OFF
D/AndroidRuntime( 6220): readGMSProperty: start
D/AndroidRuntime( 6220): readGMSProperty: already setted!!
D/AndroidRuntime( 6220): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6220): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6220): readGMSProperty: end
D/AndroidRuntime( 6220): addProductProperty: start
E/AffinityControl( 6220): AffinityControl: registerfunction enter
D/AndroidRuntime( 6220): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{188572566}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10167, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3692): Explicit concurrent mark sweep GC freed 2557(153KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 698us total 26.337ms
E/SamsungIME( 1831): mOCRHelper is null
W/GeofencerStateMachine( 1800): Ignoring removeGeofence because network location is disabled.
I/art     ( 3221): Explicit concurrent mark sweep GC freed 26393(1556KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 4.672ms total 51.371ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/art     ( 2031): Explicit concurrent mark sweep GC freed 7504(457KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 11MB/14MB, paused 2.153ms total 78.530ms
W/SQLiteConnectionPool( 2031): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.123: ( 3487): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:44:14 GMT+01:00 2016
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3487): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6234): MountEmulatedStorage()
E/Zygote  ( 6234): v2
I/libpersona( 6234): KNOX_SDCARD checking this for 10090
I/libpersona( 6234): KNOX_SDCARD not a persona
I/SELinux ( 6234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3487): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3487): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6234 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10167
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/Mms/FreeMessageStatusReceiver( 4619): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): PACKAGE_REMOVED
D/TimaKeyStoreProvider( 6234): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): listeningToPackageRemoved().START
E/Zygote  ( 6249): MountEmulatedStorage()
I/libpersona( 6249): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6249): v2
I/libpersona( 6249): KNOX_SDCARD not a persona
I/SELinux ( 6249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ActivityThread( 6234): Added TimaKeyStore provider
I/SELinux ( 6249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6249 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RegisteredServicesCache( 1456): empty dynamic service
D/FilterInstaller( 5541): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/FreeMessageReceiverService( 4619): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4619): onHandleIntent: ACTION_PACKAGE_REMOVED
D/TimaKeyStoreProvider( 6249): TimaSignature is unavailable
D/ActivityThread( 6249): Added TimaKeyStore provider
I/FilterInstaller( 5541): FilterPackageService : ACTION_PACKAGE_REMOVED
I/TactileAssist( 1018): enable value -1
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
V/EnterpriseBillingPolicy( 1018): uID is 10167
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
I/TactileAssist( 1018): List of disabled apps :
I/FilterInstaller( 5541): FilterPackageService : ACTION_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/FilterUnInstaller( 5541): before removeFromFS
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6266): MountEmulatedStorage()
E/Zygote  ( 6266): v2
I/libpersona( 6266): KNOX_SDCARD checking this for 1000
I/libpersona( 6266): KNOX_SDCARD not a persona
I/SELinux ( 6266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/elm:15121( 6234): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6234): ELMEngine.ELMEngine( context ).
D/elm:15121( 6234): MDMBridge.setEnterpriseBridge()
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): listeningToPackageRemoved().END
I/SELinux ( 6266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6266 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/art     ( 1018): Explicit concurrent mark sweep GC freed 36761(3MB) AllocSpace objects, 145(2MB) LOS objects, 33% free, 23MB/35MB, paused 4.915ms total 236.063ms
E/Zygote  ( 6281): MountEmulatedStorage()
I/libpersona( 6281): KNOX_SDCARD checking this for 10095
E/Zygote  ( 6281): v2
I/libpersona( 6281): KNOX_SDCARD not a persona
I/SELinux ( 6281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6281 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6281): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6266): TimaSignature is unavailable
D/ActivityThread( 6266): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3487): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider( 6281): TimaSignature is unavailable
D/ActivityThread( 6281): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6234): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ThemeInfoUtil( 6249): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6249): isCurrentFestival = false
D/PackageManager( 1018): delete codoeFile: 
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10167, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10167 Target=com.test.thalitest
D/PackageManager( 1018): result of delete: 1{188572566}
D/elm:15121( 6234): ElmAgentService : onCreate()
D/elm:15121( 6234): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6234): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6234): MDMBridge.getInstance()
D/elm:15121( 6234): MDMBridge.getAllLicenseInfoFromSDK()
D/Compatibility( 5461): onReceive() it will make start service
D/elm:15121( 6234): MDMBridge.getAllLicenseInfoFromSDK()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/PCWCLIENTTRACE_PushUtil( 5429): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5429): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5429): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5429): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/Compatibility( 5461): onHandleIntent()
D/Compatibility( 5461): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AndroidRuntime( 6220): Shutting down VM
D/Compatibility( 5461): found: 2
D/Compatibility( 5461): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5461): skipping ResolveInfo{135313a9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
W/ContextImpl( 6266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
I/TapandpayWidget:TapandpayAppWidgetProvider( 5632): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5632): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5632): Clear T&P info.
D/Compatibility( 5461): considering ResolveInfo{28130d2e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5461): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/TapandpayWidget:TapandpayAppWidgetProvider( 5632): Widget is not attached.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5461): enabling receiver ResolveInfo{3db4d0cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/Compatibility( 5461): enabling receiver ResolveInfo{2cb62a5c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/UpdateIcingCorporaServi( 3221): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/PreloadFilterInstaller( 6281): uses FILTER_DB_VER_1
D/Compatibility( 5461): enabling receiver ResolveInfo{29a04165 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15121( 6234): ElmAgentService : onDestroy().
D/Compatibility( 5461): enabling receiver ResolveInfo{646ce3a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 6281): (284) automatic index on titles(filter_id)
D/Compatibility( 5461): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PackageBroadcastService( 2031): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2031): Clearing selected account for com.test.thalitest
E/Zygote  ( 6304): MountEmulatedStorage()
I/libpersona( 6304): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6304): v2
I/libpersona( 6304): KNOX_SDCARD not a persona
I/SELinux ( 6304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 6281): (284) automatic index on titles(filter_id)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6304): TimaSignature is unavailable
D/ActivityThread( 6304): Added TimaKeyStore provider
E/Zygote  ( 6320): MountEmulatedStorage()
E/Zygote  ( 6320): v2
I/libpersona( 6320): KNOX_SDCARD checking this for 10032
I/libpersona( 6320): KNOX_SDCARD not a persona
I/SELinux ( 6320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6320 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6320): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/LocationSettingsChecker( 2031): Removing dialog suppression flag for package com.test.thalitest
E/Zygote  ( 6335): MountEmulatedStorage()
E/Zygote  ( 6335): v2
I/libpersona( 6335): KNOX_SDCARD checking this for 10055
I/SELinux ( 6335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6335): KNOX_SDCARD not a persona
I/SELinux ( 6335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6335 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6320): TimaSignature is unavailable
D/ActivityThread( 6320): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/gH_CompatibleDatabase( 2031): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2031): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 2031): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 2031): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/TimaKeyStoreProvider( 6335): TimaSignature is unavailable
D/ActivityThread( 6335): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 6220): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/gH_CompatibleDatabase( 2031): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 2031): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 2031): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager( 1018): Killing 5261:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
D/gH_CompatibleDatabase( 2031): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 2031): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 2031): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 2031): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 2031): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 2031): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2031): Module APK com.google.android.play.games already loaded
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/AcmsPackageEventListener( 6304): Received: android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 6304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 6304): Enter Oncreate
D/AcmsServiceMonitor( 6304): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6304): creating AcmsCore
D/AcmsCore( 6304): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6304): AcmsCore
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AcmsCore( 6304): init
D/AcmsCore( 6304): Looper handler is not null
D/AcmsCore( 6304): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6304): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6304): Incrementing - Counter value: 1
D/AcmsCore( 6304): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6304): onStartCommand
D/AcmsService( 6304): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6304): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6304): Incrementing - Counter value: 2
D/AcmsService( 6304): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 6304): AcmsCertificateMngr
D/AcmsRevocationMngr( 6304): AcmsRevocationMngr
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
E/SPPClientService( 6320): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6320): [PushClientApplication] Push log off : This is Ship build version
D/UserAnalysis.PlaceProvider( 6335): PlaceProvider onCreate()
D/ActivityThread( 6304): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/ChimeraCfgMgr( 2031): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2031): Module APK com.google.android.play.games already loaded
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SPPClientService( 6320): PushLog.txt file is not deleted.
D/SPPClientService( 6320): PushLog.txt file is not deleted.
D/SPPClientService( 6320): ============PushLog. stop!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecureDbManager( 6335): Key for secure DB is newly created
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecurePlaceDbHelper( 6335): SecurePlaceDbHelper() 
D/UserAnalysis( 6335): Create SecureDbHelper
E/SMD     (  294): DCD OFF
W/FileUtils( 6320): Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Zygote  ( 6363): MountEmulatedStorage()
I/libpersona( 6363): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD not a persona
I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6363 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AcmsService( 6304): Inside handle Intent
D/AcmsService( 6304): App removed - package name: com.test.thalitest
D/AcmsCore( 6304): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6304): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6304): Incrementing - Counter value: 3
D/AcmsCore( 6304): Incremented Counter Value: postToAcmsCoreHandler =>5
D/AcmsService( 6304): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6304): Decrementing - Counter value: 2
E/NetworkScheduler.SchedulerReceiver( 1800): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1800): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/IntelligenceServiceApplication( 6335): onCreate()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6335): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
I/art     (  316): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 23.114ms
I/FilterUnInstaller( 5541): FilterUninstaller.java : removeFromDB()
E/SQLiteLog( 2031): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 2031): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SA      ( 5516): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5516): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
E/SQLiteLog( 6335): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 6363): TimaSignature is unavailable
D/ActivityThread( 6363): Added TimaKeyStore provider
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.973ms
E/AndroidRuntime( 2031): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2031): Process: com.google.android.gms, PID: 2031
E/AndroidRuntime( 2031): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 2031): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 2031): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2031): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2031): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2031): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
E/AndroidRuntime( 2031): 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
E/AndroidRuntime( 2031): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2031): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2031): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2031): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2031): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2031): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2031): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6335): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6335): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6335): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6335): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6335): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6335): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6335): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6335): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6335): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6335): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6335): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6335): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6335): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6335): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6335): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6335): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6335): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6335): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6335): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6335): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6335): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6335): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6335): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6335): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6335): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6335): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6335): Opened privacy in read-only mode
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/FilterProvider( 6281): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 6281): packageName : com.test.thalitest
D/IntelligenceServiceApplication( 6335): no applications having user consent for prediction
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.119ms
V/PlaceDetection v1.0.19 ( 6335): [PlaceDetection::stopService] Service stopped.

```
