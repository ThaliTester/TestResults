#### Test 6262501074dad8f_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/art     ( 1660): Explicit concurrent mark sweep GC freed 4136(181KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 777us total 48.095ms
W/art     ( 3982): Suspending all threads took: 7.301ms
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/Babel   ( 3982): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3982): MmsConfig.loadMmsSettings
I/Babel   ( 3982): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3982): MmsConfig.loadFromDatabase
I/GFX raster( 3818): took 0.681771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb88a4af0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891c8f0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
E/Babel   ( 3982): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3982): MmsConfig.loadFromResources
W/SQLiteConnectionPool( 1660): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
E/Babel   ( 3982): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3982): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
--------- beginning of system
W/libprocessgroup( 1015): failed to open /acct/uid_10092/pid_3287/cgroup.procs: No such file or directory
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/SMD     (  288): DCD OFF
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.549323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc9090 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
W/Settings( 3982): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 3818): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/AMMetaDataParserService( 3818): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034112
,I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.803698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc8cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891c8f0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/Volley  ( 3953): [593] DiskBasedCache.clear: Cache cleared.
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Finsky  ( 3953): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3953): [1] Libraries$2.run: Finished loading 1 libraries.
I/AMMetaDataParserService( 3818): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/Volley  ( 3953): [586] DiskBasedCache.clear: Cache cleared.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Ads     ( 3953): Skipping gmscore version check
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/DBG_POLICYDM( 4062): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.619948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc8cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf0e40 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4062): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4062): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3818): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/FileApkUtils( 2053): Optimizing (staging complete)
D/FileApkUtils( 2053): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
I/art     ( 2053): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
I/DBG_POLICYDM( 4062): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Babel_StickerModule( 3982): App launched.
D/DexOptUtils( 2053): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2053): Lollipop platform, using <isa> directory.
D/DexOptUtils( 2053): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2053): Primary ABI of odexing process is armeabi-v7a
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.680000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb883ad28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3403): unregister AuthInfo UpdateReceiver v2.0
I/DBG_POLICYDM( 4062): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 4062): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4062): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4098): MountEmulatedStorage()
E/Zygote  ( 4098): v2
I/libpersona( 4098): KNOX_SDCARD checking this for 10035
I/libpersona( 4098): KNOX_SDCARD not a persona
D/Finsky  ( 3953): [1] GmsCoreHelper.cleanupNlp: result=false type=4
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.636718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb88a4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891c8f0 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4098 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4098): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4098): TimaSignature is unavailable
D/ActivityThread( 4098): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1850): Reading stored module config
D/AndroidRuntime( 4091): 
D/AndroidRuntime( 4091): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/Babel   ( 3982): babel boot account: SMS
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
D/AndroidRuntime( 4091): CheckJNI is OFF
D/AndroidRuntime( 4091): readGMSProperty: start
D/AndroidRuntime( 4091): readGMSProperty: already setted!!
D/AndroidRuntime( 4091): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4091): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4091): readGMSProperty: end
D/AndroidRuntime( 4091): addProductProperty: start
D/WearableService( 1850): callingUid 10012, callindPid: 1850
I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
E/GmsWearableNodeHelper( 1850): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/Babel   ( 3982): EsDatabaseHelper.static should not be called on main thread [called on main thread]
W/Babel   ( 3982): java.lang.Exception
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3982): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3982): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3982): 	at ckh.a(SourceFile:67)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3982): 	at bhn.a(SourceFile:301)
W/Babel   ( 3982): 	at bhn.a(SourceFile:137)
W/Babel   ( 3982): 	at bhn.a(SourceFile:126)
W/Babel   ( 3982): 	at bhn.a(SourceFile:159)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3982): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3982): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3982): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/Babel   ( 3982): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3982): java.lang.Exception
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3982): 	at aes.a(SourceFile:145)
W/Babel   ( 3982): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3982): 	at ckh.a(SourceFile:67)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3982): 	at bhn.a(SourceFile:301)
W/Babel   ( 3982): 	at bhn.a(SourceFile:137)
W/Babel   ( 3982): 	at bhn.a(SourceFile:126)
W/Babel   ( 3982): 	at bhn.a(SourceFile:159)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3982): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3982): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3982): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/dex2oat ( 4097): ----------------------------------------------------
I/dex2oat ( 4097): <SS>: S T A R T I N G . . .
I/dex2oat ( 4097): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4097): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/Finsky  ( 3953): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/InstanceID/Rpc( 2053): Found 10012
E/AffinityControl( 4091): AffinityControl: registerfunction enter
I/DBG_POLICYDM( 4062): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 4062): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/AndroidRuntime( 4091): Calling main entry com.android.commands.am.Am
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
D/SSRM:n  ( 1015): SIOP:: AP = 390
I/DBG_POLICYDM( 4062): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
I/Gmail   ( 3761): getAccountsCursor
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
I/PersonaManagerService( 1015): PersonaId don't exist
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
E/SPPClientService( 4098): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SPPClientService( 4098): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4098): [PushClientApplication] Push log off : This is Ship build version
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034113
I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.858855ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd63f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bf0e40 counterpartCT=4 counterpartW=96 counterparth=96
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
I/AMMetaDataParserService( 3818): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : -2122120936
D/Launcher.HomeView( 1488): onPause
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
D/InputDispatcher( 1015): Focused application set to: xxxx
D/SPPClientService( 4098): PushLog.txt file is not deleted.
D/InputDispatcher( 1015): Focus left window: 1488
D/SPPClientService( 4098): PushLog.txt file is not deleted.
D/SPPClientService( 4098): ============PushLog. stop!
I/DBG_DM  ( 3134): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
I/ActivityManager( 1015): Killing 3353:com.fmm.dm/1000 (adj 15): empty #31
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/GFX raster( 3818): took 0.822604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd63f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c0efa0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 4091): Shutting down VM
I/DBG_POLICYDM( 4062): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, uhalitest
I/DBG_POLICYDM( 4062): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
I/AMMetaDataParserService( 3818): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/14/23:37:53
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 4062): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 4062): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 4062): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 4062): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 4062): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 4062): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
E/Zygote  ( 4136): MountEmulatedStorage()
I/libpersona( 4136): KNOX_SDCARD checking this for 10155
E/Zygote  ( 4136): v2
I/libpersona( 4136): KNOX_SDCARD not a persona
I/SELinux ( 4136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4136): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4136 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 4062): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
V/ActivityThread( 1488): updateVisibility : ActivityRecord{1f300a66 token=android.os.BinderProxy@3235c370 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/GFX raster( 3818): took 0.628177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 4136): TimaSignature is unavailable
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4136): Added TimaKeyStore provider
V/Babel   ( 3982): babel boot account: thalitester@gmail.com
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
W/Babel   ( 3982): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
I/AMMetaDataParserService( 3818): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
W/Babel   ( 3982): java.lang.Exception
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3982): 	at aes.a(SourceFile:145)
W/Babel   ( 3982): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3982): 	at ckh.a(SourceFile:67)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3982): 	at bhn.a(SourceFile:301)
W/Babel   ( 3982): 	at bhn.a(SourceFile:137)
W/Babel   ( 3982): 	at bhn.a(SourceFile:126)
W/Babel   ( 3982): 	at bhn.a(SourceFile:159)
W/Babel   ( 3982): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3982): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3982): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3982): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1488): onStop
V/ActivityThread( 1488): updateVisibility : ActivityRecord{1f300a66 token=android.os.BinderProxy@3235c370 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/SecDataIO(  257): Write to block
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/DBG_POLICYDM( 4062): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3353/cgroup.procs: No such file or directory
W/ContextImpl( 2572): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.645468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc8cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891c8f0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
I/DBG_DM  ( 3134): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3134): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
E/DBG_DM  ( 3134): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Launcher( 1488): onTrimMemory. Level: 20
W/art     ( 4091): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4153 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.846875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0fdf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf0e40 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4153): MountEmulatedStorage(),
I/ActivityManager( 1015): Killing 3234:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
,E/Zygote  ( 4153): v2
I/libpersona( 4153): KNOX_SDCARD checking this for 10041
I/SELinux ( 4153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 4153): KNOX_SDCARD not a persona
,I/SELinux ( 4153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4153): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3818): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1015): [SO] activate (ident=0xb9050db0, enabled=0),
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,D/SensorManager( 1015): unregisterListener ::   ,
I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 66000000(ns),
,D/SensorService( 1015): [SO] changed settle time [1],
D/SensorService( 1015): [SO] setDelay [66000000]
D/SensorService( 1015): [SO] activate (ident=0xb9338cf0, enabled=1),
D/SensorService( 1015): [SO] AR_init,
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity,
D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3818): took 0.628802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb88a4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c0efa0 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  304): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 49.815ms
I/DBG_POLICYDM( 4062): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.558ms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.705313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb88a4af0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4153): TimaSignature is unavailable
,D/ActivityThread( 4153): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 18.459ms
I/Process ( 2572): Sending signal. PID: 2572 SIG: 9
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4136): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/GCM     ( 2053): COMPAT: Multi user not supported
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.567709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc9090 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891c8f0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3818): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/LibraryLoader( 4136): Time to load native libraries: 2 ms (timestamps 4687-4689)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
I/LibraryLoader( 4136): Expected native library version number "",actual native library version number ""
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity,
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
D/SensorService( 1015): [SO] 0.134 0.402 10.151
D/SensorService( 1015): [SO] [100 -> 255]
,E/Zygote  ( 4175): MountEmulatedStorage(),
E/Zygote  ( 4175): v2
I/libpersona( 4175): KNOX_SDCARD checking this for 1000
I/libpersona( 4175): KNOX_SDCARD not a persona
I/SELinux ( 4175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,V/WebViewChromiumFactoryProvider( 4136): Binding Chromium to main looper Looper (main, tid 1) {1fe439}
,I/LibraryLoader( 4136): Expected native library version number "",actual native library version number ""
,I/chromium( 4136): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,E/SELinux ( 4175): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165203
,W/art     ( 3777): Suspending all threads took: 23.871ms
,I/ActivityManager( 1015): Process com.sec.android.app.sysscope (pid 2572)(adj 0) has died(58,1155)
,D/TimaKeyStoreProvider( 4175): TimaSignature is unavailable
,D/ActivityThread( 4175): Added TimaKeyStore provider
,W/ResourcesManager( 3818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/BrowserStartupController( 4136): Initializing chromium process, singleProcess=true
,W/art     ( 4136): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4136): ApplicationContext is null in ApplicationStatus
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,I/AMMetaDataParserService( 3818): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_3234/cgroup.procs: No such file or directory
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 3.347447ms for 0*0 texture 0
,W/chromium( 4136): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4136): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 4136): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/DBG_POLICYDM( 4062): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Adreno-EGL( 4136): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4136): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4136): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4136): Local Branch: 
I/Adreno-EGL( 4136): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4136): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4136):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/GFX generate_partition_tables( 3818): took 11.008438ms for 0*0 texture 0
,I/GFX raster( 3818): took 15.221613ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bf0e08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8dc1be0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/8)
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,I/SA      ( 4153): [SSP] onCreated
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.926407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0e4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb910c640 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/VideoCapabilities( 3982): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3982): Unsupported mime audio/evrc
,W/AudioCapabilities( 3982): Unsupported mime audio/qcelp
,I/AMMetaDataParserService( 3818): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/AudioCapabilities( 3982): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3982): Unsupported mime audio/mpeg-L2
,I/CheckinService( 2053): Disabling old GoogleServicesFramework version
,W/AudioCapabilities( 3982): Unsupported mime audio/x-ms-wma
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AudioCapabilities( 3982): Unsupported mime audio/x-ima
W/AudioCapabilities( 3982): Unsupported mime audio/qcelp
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/AudioCapabilities( 3982): Unsupported mime audio/evrc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 2053): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/SystemUpdateService( 2053): onCreate
I/SA      ( 4153): [TPM] There is no property file
I/SA      ( 4153): [SCU] isHaveSA() - false
,I/SA      ( 4153): [TPM] getModelProperty : null
I/SA      ( 4153): [TPM] getCSCProperty : null
,I/SA      ( 4153): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4153): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4153): [DM] TFT FEATURE: false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4153): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4153): [DM] init START
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/VideoCapabilities( 3982): Unsupported mime video/wvc1
,I/GFX raster( 3818): took 0.786250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0e4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bd63f0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3982): Unsupported mime video/x-ms-wmv
,I/AMMetaDataParserService( 3818): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 4153): [DM] This device is not a Vodafone
,W/ResourceType( 4153): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4153): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/VideoCapabilities( 3982): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourceType( 4153): No package identifier when getting value for resource number 0x00000000
,W/VideoCapabilities( 3982): Unsupported mime video/wvc1
,W/ResourceType( 4153): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4153): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/VideoCapabilities( 3982): Unsupported mime video/x-ms-wmv
,W/ResourceType( 4153): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,D/SystemUpdateService( 2053): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ResourceType( 4153): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/VideoCapabilities( 3982): Unsupported mime video/x-ms-wmv7
,W/ResourceType( 4153): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4153): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4153): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,W/VideoCapabilities( 3982): Unsupported mime video/x-ms-wmv8
,V/AuthZen ( 2053): Handling intent: android.intent.action.BOOT_COMPLETED
,W/chromium( 4136): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/VideoCapabilities( 3982): Unsupported mime video/mp43
,I/SA      ( 4153): [SCU] isHaveSA() - false
I/SA      ( 4153): support phone number id : false
I/SA      ( 4153): [DM] Supports Ref Jpn : true
I/SA      ( 4153): [DM] init END
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SA      ( 4153): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4153): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,I/GFX raster( 3818): took 0.779583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0e4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bd5430 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3982): Unsupported mime video/sorenson
,D/AuthZenEventHandler( 2053): Handling event: android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 4221): MountEmulatedStorage(),
I/libpersona( 4221): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4221): v2
,I/libpersona( 4221): KNOX_SDCARD not a persona
I/SELinux ( 4221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4221 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 3378:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
E/SELinux ( 4221): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/art     ( 4136): Attempt to remove local handle scope entry from IRT, ignoring
,I/SA      ( 4153): [OR] onReceive END
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,I/AMMetaDataParserService( 3818): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4221): TimaSignature is unavailable
,D/ActivityThread( 4221): Added TimaKeyStore provider
,W/AwContents( 4136): onDetachedFromWindow called when already detached. Ignoring
E/Zygote  ( 4237): MountEmulatedStorage()
E/Zygote  ( 4237): v2
I/libpersona( 4237): KNOX_SDCARD checking this for 10042
I/libpersona( 4237): KNOX_SDCARD not a persona
I/SELinux ( 4237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/VideoCapabilities( 3982): Unsupported mime video/mp4v-esdp
I/SELinux ( 4237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4237 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4237): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.610312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc9090 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bd0378 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4153): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4153): [ODM] queryOpenData(key= GEO_IP )
,D/PhoneWindow( 4136): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4136): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4136): CordovaWebView is running on device made by: samsung
,I/SA      ( 4153): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4153): [LBE] REF_JPN : true
,D/ChimeraCfgMgr( 2053): Reading stored module config
,D/TimaKeyStoreProvider( 4237): TimaSignature is unavailable
,D/ActivityThread( 4237): Added TimaKeyStore provider
,I/SA      ( 4153): [BDC] create
,W/art     ( 4136): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4136): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1015): failed to open /acct/uid_10092/pid_3378/cgroup.procs: No such file or directory
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.631458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bc9090 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bc8cf0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/DBG_DM  ( 3134): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/ResourcesManager( 4237): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3134): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3134): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/VideoCapabilities( 3982): Unsupported profile 4 for video/mp4v-es
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3134): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3134): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3134): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
I/DBG_DM  ( 3134): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/KnoxSetupWizardDbHelper( 4221): dbMigrationFlag : false
,I/DBG_DM  ( 3134): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3134): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3134): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/DBG_DM  ( 3134): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/DBG_DM  ( 3134): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 3134): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,D/OpenGLRenderer( 4136): Render dirty regions requested: true
,D/ShortcutReceiver( 4221):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/CheckinService( 2053): Checking schedule, now: 1457995074643 next: 1458246240395
I/CheckinService( 2053): active receiver: disabled
,I/SA      ( 4153): [DBMV2] getEmailID
,D/PhoneWindow( 4136): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4136): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/KnoxShortcutUtil( 4221): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4221):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4221):  shortcut migration not required 
,D/BootCompletedReceiver( 2053): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2053): Got an BootCompleted event.
,D/InputDispatcher( 1015): Focus entered window: 4136
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/SystemUpdateService( 2053): cancelUpdate (empty URL)
I/SystemUpdateService( 2053): active receiver: disabled
,I/SA      ( 4153): [DBMV2] getDataV02ForItems
,I/SA      ( 4153): [SSP] query invoked
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/SA      ( 4153): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4153): [SCU] get signed id from samsung account1.0 DB.,
W/ResourcesManager( 3818): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
W/ResourcesManager( 3818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/GFX raster( 3818): took 0.688073ms for 96*96 texture 0
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8be1548 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 3818): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 4136): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4136): Initialized EGL, version 1.4
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,E/Zygote  ( 4263): MountEmulatedStorage()
I/libpersona( 4263): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4263): v2
I/libpersona( 4263): KNOX_SDCARD not a persona
I/SELinux ( 4263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/OpenGLRenderer( 4136): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4136): Enabling debug mode 0
I/ActivityManager( 1015): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4263 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 3387:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/SELinux ( 4263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/SA      ( 4153): [BDC] destroy
,I/ActivityManager( 1015): Killing 3431:com.fmm.ds/1000 (adj 15): empty #31
,D/BootCompletedReceiver( 2053): Will NOT schedule AdAttestation signal task because it's disabled.
,I/DBG_DM  ( 3134): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4263): TimaSignature is unavailable
I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
D/ActivityThread( 4263): Added TimaKeyStore provider
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 2.749114ms for 0*0 texture 0
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/CalendarProvider2( 4237): CalendarProvider2.onCreate() called
,W/BaseAppContext( 2053): Using Auth Proxy for data requests.
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_3387/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
I/DBG_DM  ( 3134): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/GFX generate_partition_tables( 3818): took 9.041041ms for 0*0 texture 0
,E/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@397b0c0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1189): Icon Only
,D/PanelView( 1189): There is/are notification(s) 
I/GFX raster( 3818): took 12.863749ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bf7340 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8bf73e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1015): Displayed Component not be shown by security: +1s444ms
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{a2c151d u0 com.test.thalitest/.MainActivity t12} time:45791
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
E/KnoxSetupWizardClient( 4263): isShipMode : 1
I/KnoxSetupWizardClient( 4263): onReceive : android.intent.action.BOOT_COMPLETED
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/SamsungIME( 1795): getCurrentCandidateView
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3431/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3134): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 3134): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/BindingManager( 4136): Cannot call determinedVisibility() - never saw a connection for the pid: 4136
,W/ContextImpl( 3134): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,I/Timeline( 4136): Timeline: Activity_idle id: android.os.BinderProxy@2f6ea03a time:45896
,E/Zygote  ( 4289): MountEmulatedStorage(),
E/Zygote  ( 4289): v2
I/libpersona( 4289): KNOX_SDCARD checking this for 10107
I/SELinux ( 4289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4289): KNOX_SDCARD not a persona
,I/SELinux ( 4289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4289): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4289 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3452:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,D/SettingsProvider( 1015): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.647188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bf49a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8bf4a48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SecKeyguardClockSingleView( 1189): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 4289): TimaSignature is unavailable
,W/System.err( 4263): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4263): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4263): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4263): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4263): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4263): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4263): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityThread( 4289): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  258): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=10 Removed uhalitest (-2/8)
,I/DBG_DM  ( 3134): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/libprocessgroup( 1015): failed to open /acct/uid_10060/pid_3452/cgroup.procs: No such file or directory
,E/BaseAppContext( 2053): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/JsMessageQueue( 4136): Set native->JS mode to OnlineEventsBridgeMode
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.907552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc4f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bfc598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3818): took 0.625521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8be1548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf7270 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SQLiteLog( 3982): (284) automatic index on conversation_participants_view(conversation_id)
,W/dex2oat ( 4097): Verification of int com.google.android.gms.common.j.b(android.content.Context) took 101.683ms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.726511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bfc8f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,D/GCM     ( 1850): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 46773(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/40MB, paused 2.663ms total 179.391ms
,W/art     ( 3777): Suspending all threads took: 303.245ms
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/AuthZen ( 2053): Fetching signing key...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1850): DispatchingService.onCreate()
,I/AuthZen ( 2053): Signing key fetched successfully!
,E/SQLiteLog( 3982): (284) automatic index on conversation_participants_view(conversation_id)
,I/GCM     ( 1850): GCM config loaded
,E/SQLiteLog( 3982): (284) automatic index on conversation_participants_view(conversation_id)
,D/SystemUpdateService( 2053): onDestroy
,W/BaseAppContext( 2053): Using Auth Proxy for data requests.
,D/jxcore_app_log( 4136): JniHelper::setJavaVM(0xb8834450), pthread_self() = -1193714656
,I/ActivityManager( 1015): Killing 3474:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c3ec51 added. We now have 1 listener(s)
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1015): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1189): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4136): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4136): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4136): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4136): setHandshakeRequired: true -> false
I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a2b924 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4136): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4136): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4136): setScanMode: 1 -> 2
D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1015): mCursor = null
D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/KnoxNotification( 1189): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/dex2oat ( 4097): Verification of com.google.android.gms.maps.model.StreetViewPanoramaOrientation com.google.android.gms.maps.internal.ak$a$a.a(maps.bu.a) took 160.642ms
,W/dex2oat ( 4097): Verification of boolean com.google.android.gms.maps.internal.j$a.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 140.887ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_3474/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/chromium( 4136): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/KnoxNotification( 1189): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1189): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1189): Icon Only
,I/StatusBar( 1189): Icon Only
,D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1189): Icon Only
I/StatusBar( 1189): Icon Only
,D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1850): No location to return for getLastLocation()
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/SQLiteLog( 3982): (284) automatic index on conversation_participants_view(conversation_id)
,I/GFX raster( 3818): took 0.889063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bde558 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/FusedLocationProvider( 1850): location=null
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/GCoreFlp( 1850): No location to return for getLastLocation()
,W/FusedLocationProvider( 1850): location=null
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/art     ( 1660): Explicit concurrent mark sweep GC freed 4277(164KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 5.922ms total 45.878ms
,D/SamsungIME( 1795): Dismiss ExpandCandiate
,I/art     ( 4136): Background partial concurrent mark sweep GC freed 4850(456KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/18MB, paused 6.190ms total 36.802ms
W/dex2oat ( 4097): Verification of void com.google.android.libraries.appstreaming.framework.f.<init>(maps.cd.q, int, int) took 137.818ms
,W/dex2oat ( 4097): Verification of void com.google.android.libraries.appstreaming.framework.h.a(int) took 125.898ms
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.642604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8c0e5e0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3982): (284) automatic index on conversation_participants_view(conversation_id)
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1015): mCursor = null
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/a       ( 2053): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2053): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2053): Clearing transaction cache
,I/DBG_DM  ( 3134): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3134): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.620625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0efa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8887480 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 3134): Render dirty regions requested: true
,W/Auth    ( 1850): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1015): Killing 3510:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/SRIB_DCS( 3134): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3134): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3134): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3134): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3134): Local Branch: 
I/Adreno-EGL( 3134): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3134): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3134):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3134): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3134): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3134): Enabling debug mode 0
,I/art     ( 1850): Explicit concurrent mark sweep GC freed 36572(2MB) AllocSpace objects, 39(768KB) LOS objects, 39% free, 12MB/20MB, paused 17.517ms total 573.339ms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/dex2oat ( 4097): Verification of java.lang.Object com.google.maps.api.android.lib6.gmm6.streetview.f.a(com.google.maps.api.android.lib6.gmm6.streetview.f) took 250.746ms
,D/PersistentNotificationBroadcastReceiver( 1850): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GAV2    ( 3761): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
,I/GCoreUlr( 1850): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/dex2oat ( 4097): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.aa.b(javax.microedition.khronos.opengles.GL10, maps.ei.aq) took 354.365ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3510/cgroup.procs: No such file or directory
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.652552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8dc2030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
,W/dex2oat ( 4097): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.ag.a(long) took 366.930ms
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1795): KeybaordView init() : load resources
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.626302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb891c8f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8887480 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1850): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SamsungIME( 1795): getCurrentKeyboard
I/SamsungIME( 1795): getTextKeyboard
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.727396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb897bfa0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1795): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/GCoreUlr( 1850): Unbound from all location providers
I/GCoreUlr( 1850): Place inference reporting - stopped
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.963127ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bc9260 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.645521ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1850): DispatchingService.onDestroy()
,I/GCoreUlr( 1850): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1850): Unbound from all location providers
,I/GCoreUlr( 1850): Place inference reporting - stopped
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.630156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0efa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb883adf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.655989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8dc2030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bc9260 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_POLICYDM( 4062): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/GFX raster( 3818): took 0.656302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb891c8f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf1d00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.850884ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb883adf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/CalendarProvider2( 4237): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1015): Killing 3267:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3818): Resource data:2131099648
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.720468ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb897bfa0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_3267/cgroup.procs: No such file or directory
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.680364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8bc9260 counterpartCT=4 counterpartW=96 counterparth=96
,D/StrictMode( 4289): StrictMode policy violation; ~duration=1352 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4289): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4289): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4289): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4289): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4289): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4289): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=1119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4289): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4289): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4289): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4289): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4289): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=596 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4289): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4289): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4289): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4289): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4289): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4289): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=595 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4289): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4289): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4289): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4289): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instru,mentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=594 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4289): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4289): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4289): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4289): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=592 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4289): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4289): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4289): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4289): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4289): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4289): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4289): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4289): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4289): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4289): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4289): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4289): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=590 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4289): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4289): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4289): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4289): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4289): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4289): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4289): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4289): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4289): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4289): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4289): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4289): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4289): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=383 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4289): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4289): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4289): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4289): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4289): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4289): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4289): StrictMode policy violation; ~duration=383 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4289): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4289): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4289): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4289): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4289): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4289): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4289): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4289): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4289): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4289): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4289): 	at android.os.Handler.dis,patchMessage(Handler.java:102)
D/StrictMode( 4289): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4289): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4289): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4289): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4367): MountEmulatedStorage()
E/Zygote  ( 4367): v2
I/libpersona( 4367): KNOX_SDCARD checking this for 1000
I/libpersona( 4367): KNOX_SDCARD not a persona
I/SELinux ( 4367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.646093ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0efa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb883adf8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3527:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
D/TimaKeyStoreProvider( 4367): TimaSignature is unavailable
D/ActivityThread( 4367): Added TimaKeyStore provider
,D/StatusChecker( 4367): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4367): onReceive : net.mt.init : DONE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService( 1015): [s] UserActivityState : 1 -> 2
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.661928ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8dc2030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb897bfa0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4385): MountEmulatedStorage()
E/Zygote  ( 4385): v2
I/libpersona( 4385): KNOX_SDCARD checking this for 10116
I/libpersona( 4385): KNOX_SDCARD not a persona
,I/SELinux ( 4385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/SELinux ( 4385): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4385 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3543:com.wssnps/1000 (adj 15): empty #31
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.733697ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb891c8f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bc9260 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4385): TimaSignature is unavailable
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 4385): Added TimaKeyStore provider
,I/GFX raster( 3818): took 0.731615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8887480 counterpartCT=4 counterpartW=96 counterparth=96
,W/dex2oat ( 4097): Verification of void maps.dq.c.<init>(int) took 112.989ms
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.710000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb910c590 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_3527/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3543/cgroup.procs: No such file or directory
,I/PageBuddyNotiSvc( 4385): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/com.google.a.a.b.d.a( 4289): Application name is not set. Call Builder#setApplicationName.
,W/ContextImpl( 4385): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4385): onCreate mCpBitFlag=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4401 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3818): took 0.661981ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8bf24f8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4401): MountEmulatedStorage(),
,E/Zygote  ( 4401): v2
I/libpersona( 4401): KNOX_SDCARD checking this for 10125,
I/libpersona( 4401): KNOX_SDCARD not a persona
,I/SELinux ( 4401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4401): TimaSignature is unavailable
,D/ActivityThread( 4401): Added TimaKeyStore provider
,W/dex2oat ( 4097): Verification of void maps.dz.aq$h.g() took 116.095ms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.913802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0efa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8bde558 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4401): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4401): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/QuickConnect( 4401): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4401): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1015): name = scon_is_running
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10125
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4401): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1189): Ignore. Because it is same clock text
,W/jxcore-log( 4136): Initializing JXcore engine
,W/jxcore-log( 4136): JXcore engine is ready
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.639323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8dc2030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c0ec80 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4401): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
E/Zygote  ( 4417): MountEmulatedStorage()
E/Zygote  ( 4417): v2
I/libpersona( 4417): KNOX_SDCARD checking this for 10131
I/libpersona( 4417): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4417 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Killing 3305:com.google.android.partnersetup/u0a15 (adj 15): empty #31,
,I/SELinux ( 4417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.694479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb891c8f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bd4290 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.731718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb897bfa0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3818): Resource data:2131099648
,E/audit   ( 1923): type=1400 msg=audit(1457995077.620:205): avc:  denied  { ioctl } for  pid=4337 comm="Thread-627" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1923):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1923): type=1300 msg=audit(1457995077.620:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c38f8f8 items=0 ppid=304 ppcomm=main pid=4337 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-627" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,E/audit   ( 1923): type=1320 msg=audit(1457995077.620:205): 
,W/jxcore-log( 4136): Starting JXcore engine
,D/TimaKeyStoreProvider( 4417): TimaSignature is unavailable
,D/ActivityThread( 4417): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.688646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bd5430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb883c4d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityThread( 4289): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/System.out( 4289): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4289): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4289): (HTTPLog)-Static: isShipBuild true
I/System.out( 4289): (HTTPLog)-Thread-644-340532608: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4289): (HTTPLog)-Static: isSBSettingEnabled false
,W/ResourcesManager( 4417): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_3305/cgroup.procs: No such file or directory
D/EnterpriseController(  278): uids 10107
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10107
,I/GFX raster( 3818): took 0.679636ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c09a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8887480 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3818): took 0.742916ms for 96*96 texture 0
,V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8c0efa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c0ec80 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 4136): Platform android
W/jxcore-log( 4136): 
,W/jxcore-log( 4136): Process ARCH arm
W/jxcore-log( 4136): 
,I/System.out( 4289): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.843125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8dc2030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bd4290 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/SBrowserFeatureFlag( 4417): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.805208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb891c8f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb897bfa0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ManifestProvider( 4417): onCreate()
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.986458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb8bfc850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb883c4d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/NetworkSettingsReceiver( 4417): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3818): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165197
,W/ResourcesManager( 3818): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SBrowserFeatureFlag( 4417): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2118af5
,D/SBrowserFeatureFlag( 4417): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4417): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,W/ResourcesManager( 3818): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,I/AMMetaDataParserService( 3818): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/dex2oat ( 4097): Verification of void maps.k.b$m.a(byte[], byte[]) took 109.484ms,
I/libpersona( 4440): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4440): MountEmulatedStorage(),
I/libpersona( 4440): KNOX_SDCARD not a persona
E/Zygote  ( 4440): v2
I/SELinux ( 4440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3818): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625,
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4440 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 2731:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,D/SamsungIME( 1795): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/TimaKeyStoreProvider( 4440): TimaSignature is unavailable
,D/ActivityThread( 4440): Added TimaKeyStore provider
,W/dex2oat ( 4097): Verification of void maps.k.b$l.a(byte[], byte[]) took 143.021ms
,W/dex2oat ( 4097): Verification of void maps.k.b$k.a(byte[], byte[]) took 155.215ms
,I/AMMetaDataParserService( 3818): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourcesManager( 4440): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_2731/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4461): MountEmulatedStorage(),
I/libpersona( 4461): KNOX_SDCARD checking this for 10139
,E/Zygote  ( 4461): v2
I/libpersona( 4461): KNOX_SDCARD not a persona
I/SELinux ( 4461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4461 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 4461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  304): Explicit concurrent mark sweep GC freed 8736(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 27.390ms,
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.891ms,
,I/jxcore-log( 4136): JXcore Cordova bridge is ready!,
I/jxcore-log( 4136): 
W/jxcore-log( 4136): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4136): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity,
E/jxcore  ( 4136): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4136): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165197
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 20.394ms
,I/AMMetaDataParserService( 3818): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
I/chromium( 4136): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/AMMetaDataParserService( 3818): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/FocusedStackFrame( 1015): Set to : 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 4136
,D/TimaKeyStoreProvider( 4461): TimaSignature is unavailable
D/ActivityThread( 4461): Added TimaKeyStore provider
,W/dex2oat ( 4097): Compilation of android.os.IBinder com.google.android.gms.maps.internal.p$a$a.asBinder() took 120.124ms
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
,W/dex2oat ( 4097): Compilation of void maps.aj.b$1$2.a(maps.aj.c) took 117.025ms
,I/AMMetaDataParserService( 3818): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3818): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/PluginManager( 4136): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 56ms. Plugin should use CordovaInterface.getThreadPool().,
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
V/WindowManager( 1015): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/Launcher( 1488): onRestart, Launcher: 34704117
,D/Launcher( 1488): onStart, Launcher: 34704117
,D/Launcher.HomeView( 1488): onStart
,D/Launcher( 1488): onResume, Launcher: 34704117
,D/SettingsProvider( 1015): name = kids_home_mode
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10007
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/Launcher.HomeView( 1488): onResume
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1015): [SO] activate (ident=0xb9338cf0, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1015): unregisterListener ::   
,I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1015): [SO] changed settle time [0]
,D/SensorService( 1015): [SO] setDelay [200000000]
D/SensorService( 1015): [SO] activate (ident=0xb9338cf0, enabled=1)
D/SensorService( 1015): [SO] AR_init
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
,D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165197
,I/AMMetaDataParserService( 3818): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/MenuAppsGridFragment( 1488): onResume
,D/ActivityManager( 1015): handle home activity for 0
I/WallpaperManagerService( 1015): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1015): post home show event for user 0
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1015):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,I/SurfaceFlinger(  258): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1015): Focus entered window: 1488
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
W/ResourcesManager( 4461): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4461): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4461): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4461): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4461): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SRIB_DCS( 1488): log_dcs ThreadedRenderer::initialize entered! 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/StatusBar( 1189): Icon Only
,D/PanelView( 1189): There is/are notification(s) 
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 4136): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1795): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,V/Herrevad( 2053): NQAS connected
,I/Timeline( 1488): Timeline: Activity_idle id: android.os.BinderProxy@3235c370 time:49447
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Displayed Component not be shown by security: +195ms
,I/dex2oat ( 4097): dex2oat took 5.373s (threads: 4)
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3818): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3818): getResourcePackageName:android.wallpaper.preview
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,D/DexOptUtils( 2053): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
D/DexOptUtils( 2053): Set odex to world readable.
,D/DexOptUtils( 2053): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,E/Zygote  ( 4485): MountEmulatedStorage()
,E/Zygote  ( 4485): v2
,I/libpersona( 4485): KNOX_SDCARD checking this for 10145
I/SELinux ( 4485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4485): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4485 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/ActivityManager( 1015): Killing 3657:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
,W/ResourcesManager( 3818): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,I/AMMetaDataParserService( 3818): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/ActivityManager( 1015): Killing 3606:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4485): TimaSignature is unavailable
,I/AMMetaDataParserService( 3818): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
D/ActivityThread( 4485): Added TimaKeyStore provider
,W/ResourcesManager( 4485): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4485): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4485): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Watchdog( 1015): !@Sync 1
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1850): onCreate
,D/SettingsProvider( 1015): name = audio_safe_volume_state
,W/libprocessgroup( 1015): failed to open /acct/uid_10022/pid_3657/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10094/pid_3606/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/SMD     (  288): DCD OFF
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165220
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ResourcesManager( 3818): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.755261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb930d170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb930cea0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/SensorService( 1015): [SO] currT = 49720068156, prevT = 49260116958, diff = 459951198, [0.134 0.402 10.151]
,D/SensorService( 1015): [SO] 0.134 0.402 10.151
D/SensorService( 1015): [SO] [100 -> 255]
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.617448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb930cfc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb931f9e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.HomeSettings
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1015): mDVFSHelper.release()
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.UsbSettings
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.BandMode
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
D/ActivityManager( 1015): startService callerProcessName:com.android.email, calleePkgName: com.android.email
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.CryptKeeper
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ModePreview
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.andr,oid.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/libpersona( 4512): KNOX_SDCARD checking this for 10072
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/libpersona( 4512): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4512 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3818): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
E/Zygote  ( 4512): MountEmulatedStorage()
E/Zygote  ( 4512): v2
I/SELinux ( 4512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4512): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/art     ( 1015): Explicit concurrent mark sweep GC freed 35078(1813KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/45MB, paused 4.081ms total 214.270ms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4512): TimaSignature is unavailable
,D/ActivityThread( 4512): Added TimaKeyStore provider
E/Zygote  ( 4531): MountEmulatedStorage()
E/Zygote  ( 4531): v2
I/libpersona( 4531): KNOX_SDCARD checking this for 10146
I/libpersona( 4531): KNOX_SDCARD not a persona
I/SELinux ( 4531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4531 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 4531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 3683:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
E/SELinux ( 4531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 3702:com.sec.factory.camera/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3403:com.sec.pcw.device/1000 (adj 15): empty #31
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{1ed6e17 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:49900
I/SurfaceFlinger(  258): id=11 Removed NainActivit (7/9)
,I/ActivityManager( 1015): Killing 3723:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/9)
,D/TimaKeyStoreProvider( 4531): TimaSignature is unavailable
,D/ActivityThread( 4531): Added TimaKeyStore provider
,W/ResourcesManager( 4531): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 4512): onCreate
,D/BadgeProvider( 4512): DatabaseHelper
,D/BadgeProvider( 4512): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/BindingManager( 4136): Cannot call determinedVisibility() - never saw a connection for the pid: 4136
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/Launcher.Model( 1488): reloadBadges entered.
,D/BadgeProvider( 4512): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4512): sendNotify, [notify] : null
D/BadgeProvider( 4512): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4512): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4512): update, [UpdateCount] : 1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3702/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_3723/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3683/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3403/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/Process ( 4485): Sending signal. PID: 4485 SIG: 9
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4547): MountEmulatedStorage(),
I/libpersona( 4547): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4547): v2
I/libpersona( 4547): KNOX_SDCARD not a persona
I/SELinux ( 4547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3741:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,E/JavaBinder( 4531): !!! FAILED BINDER TRANSACTION !!!
,D/TimaKeyStoreProvider( 4547): TimaSignature is unavailable
,D/ActivityThread( 4547): Added TimaKeyStore provider
,W/ActivityManager( 1015): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/Process ( 4531): Sending signal. PID: 4531 SIG: 9
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Process com.android.email (pid 4485)(adj 11) has died(80,1111)
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4566 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Process com.android.exchange (pid 4531)(adj 9) has died(80,1112)
E/Zygote  ( 4566): MountEmulatedStorage()
I/libpersona( 4566): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4566): v2
I/libpersona( 4566): KNOX_SDCARD not a persona
,I/SELinux ( 4566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3741/cgroup.procs: No such file or directory
,I/SELinux ( 4566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4566): TimaSignature is unavailable
,D/ActivityThread( 4566): Added TimaKeyStore provider
,D/SecurityLogAgent( 4566): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4566): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4566): StateMachine : Current State = 1
D/SecurityLogAgent( 4566): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1850): callingUid 10012, callindPid: 1850
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2053): Restart initialization of location
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1464): query,matched:0, calling pid = 2053
,D/TP/SmsProvider( 1464): match 0:Elapsed time : 3.180 ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 50379
,D/PowerManagerService( 1015): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=3407)
,D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 2053
,D/TP/SmsProvider( 1464): query,matched:0, calling pid = 2053
,D/TP/SmsProvider( 1464): match 0:Elapsed time : 1.629 ms
,D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 2053
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1850): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1850): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/IcingInternalCorpora( 2053): getNumBytesRead when not calculated.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1850): [232] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,W/GCoreFlp( 1850): No location to return for getLastLocation()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/FusedLocationProvider( 1850): location=null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3571): Starting #2
,I/Hs20UtilService( 3571): Message received 5011
,D/SecurityLogAgent( 4566): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4566): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4566): StateMachine : Current State = 1
,D/SecurityLogAgent( 4566): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4603): MountEmulatedStorage()
E/Zygote  ( 4603): v2
I/libpersona( 4603): KNOX_SDCARD checking this for 10174
I/libpersona( 4603): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4603 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4603): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4603): TimaSignature is unavailable
,D/ActivityThread( 4603): Added TimaKeyStore provider
,D/jxcore_app_log( 4603): JniHelper::setJavaVM(0xb8834450), pthread_self() = -1225548088
,E/JX-Cordova( 4603): JXcore wasn't initialized yet
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 3792:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1850): [247] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2053): Restart initialization of location
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1850): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_3792/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1850): No location to return for getLastLocation()
,W/FusedLocationProvider( 1850): location=null
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3571): Starting #3
,I/Hs20UtilService( 3571): Message received 5011
,E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
,D/SecurityLogAgent( 4566): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4566): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4566): StateMachine : Current State = 1
,D/SecurityLogAgent( 4566): StateMachine : Changed Current State = 1
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1189): handleTimeUpdate
,I/ActivityManager( 1015): Killing 3587:com.samsung.android.sm/1000 (adj 15): empty #31
,D/SecKeyguardClockView( 1189): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{d81d7fd u0 com.samsung.android.providers.context/.ContextService}
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/SecKeyguardClockView( 1189): HomeTimezone(): 1,
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1189): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1189): *** don't update sliding image ***
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4624): MountEmulatedStorage(),
E/Zygote  ( 4624): v2
I/libpersona( 4624): KNOX_SDCARD checking this for 10068
I/libpersona( 4624): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4624 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/accuweather( 1720): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1720): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1720): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1720): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1720): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1720): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1720): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1720): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1720): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,I/SurfaceFlinger(  258): id=12 Removed Uoast (8/8)
,I/SurfaceFlinger(  258): id=12 Removed Uoast (-2/8)
,E/accuweather( 1720): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 38
,D/TimaKeyStoreProvider( 4624): TimaSignature is unavailable
,D/ActivityThread( 4624): Added TimaKeyStore provider
,W/ResourcesManager( 4624): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/OpenGLRenderer( 1488): SFEffectCache::get: create texture(0xa075e724): name, size, mSize = 39, 147852, 321864
,D/DateView( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/FileShare-Client( 4624): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3587/cgroup.procs: No such file or directory
,D/FileShare-Client( 4624): ClientBroadcastReceiver.onReceive - disconnected
,D/SecKeyguardStatusUtils( 1189): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/FileShare-Client( 4624): Outbound.stopDelayTimer - 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4641 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3818:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
E/Zygote  ( 4641): MountEmulatedStorage()
I/libpersona( 4641): KNOX_SDCARD checking this for 10069
E/Zygote  ( 4641): v2
I/libpersona( 4641): KNOX_SDCARD not a persona
,I/SELinux ( 4641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4641): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4641): TimaSignature is unavailable
,D/ActivityThread( 4641): Added TimaKeyStore provider
,D/FileShare-Server( 4641): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1015): Killing 3777:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3571): Starting #4
,I/Hs20UtilService( 3571): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3571): Starting #5
,I/Hs20UtilService( 3571): Message received 5007
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3571): Starting #6
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/Hs20UtilService( 3571): Message received 5007
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3571): Starting #7
,I/Hs20UtilService( 3571): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3818/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10031/pid_3777/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast,
,E/Zygote  ( 4656): MountEmulatedStorage()
I/libpersona( 4656): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4656): v2
I/libpersona( 4656): KNOX_SDCARD not a persona
I/SELinux ( 4656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/TimaKeyStoreProvider( 4656): TimaSignature is unavailable
,D/ActivityThread( 4656): Added TimaKeyStore provider
,D/SRIB_DCS( 1189): log_dcs ThreadedRenderer::initialize entered! 
,I/PCWCLIENTTRACE_LOG( 4656): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 4656): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 4656): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 4656): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4656): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4656): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4656): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4673): MountEmulatedStorage()
,E/Zygote  ( 4673): v2
I/libpersona( 4673): KNOX_SDCARD checking this for 10111
,I/libpersona( 4673): KNOX_SDCARD not a persona
,I/SELinux ( 4673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4673 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3854:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,I/SELinux ( 4673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4673): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3625): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 23:38:00 GMT+01:00 2016
,D/accuweather( 1720): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{14a89069 u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/SecurityLogAgent( 4566): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4566): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4566): StateMachine : Current State = 1
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/SecurityLogAgent( 4566): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3625): KLMSAbstractReciever(): onReceive().END.
,D/TimaKeyStoreProvider( 4673): TimaSignature is unavailable
,D/ActivityThread( 4673): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onCreate()
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/KLMS-2.5.183: ( 3625): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3625): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  ( 4689): MountEmulatedStorage()
E/Zygote  ( 4689): v2
I/libpersona( 4689): KNOX_SDCARD checking this for 10159
I/libpersona( 4689): KNOX_SDCARD not a persona
I/SELinux ( 4689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4689 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4689): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
I/KLMS-2.5.183: ( 3625): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/accuweather( 1720): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1720): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1720): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1720): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1015): Exception when sending broadcast to ComponentInfo{com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyReceiver}
W/BroadcastQueue( 1015): android.os.TransactionTooLargeException
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1015): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20562)
W/BroadcastQueue( 1015): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3405)
W/BroadcastQueue( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3625): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
I/KLMS-2.5.183: ( 3625): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3625): NetworkChangeOperations(): uploadRequestLog().START 
,I/art     (  304): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 24.906ms
,D/TimaKeyStoreProvider( 4689): TimaSignature is unavailable
,I/KLMS-2.5.183: ( 3625): NetworkChangeOperations(): uploadRequestLog().END 
D/ActivityThread( 4689): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3625): StateImplV2(): networkChangeListener().END
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 588us total 16.450ms,
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 588us total 16.370ms,
,E/Zygote  ( 4704): MountEmulatedStorage(),
,E/Zygote  ( 4704): v2,
I/libpersona( 4704): KNOX_SDCARD checking this for 10032
I/libpersona( 4704): KNOX_SDCARD not a persona,
I/SELinux ( 4704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4704 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 4704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onDestroy()
,D/accuweather( 1720): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1720): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4721): MountEmulatedStorage(),
,E/Zygote  ( 4721): v2
I/libpersona( 4721): KNOX_SDCARD checking this for 10081
I/libpersona( 4721): KNOX_SDCARD not a persona
,I/SELinux ( 4721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4721 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4721): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
V/AlarmManager( 1015): waitForAlarm result :4
,D/TimaKeyStoreProvider( 4704): TimaSignature is unavailable
D/ActivityThread( 4704): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4721): TimaSignature is unavailable
,D/ActivityThread( 4721): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_3854/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4062): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4062): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/DBG_POLICYDM( 4062): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts,
,I/DBG_POLICYDM( 4062): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/SPPClientService( 4098): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 4062): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 4153): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4153): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 4153): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 4062): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 4062): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/iu.SyncManager( 2053): SYNC; picasa accounts
,I/SA      ( 4153): [SLFUCHKMGR] constructor called
,D/NetworkLogImpl( 2053): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2053): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SA      ( 4153): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4153): [OR] == isSIMCardReady false ==
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4746): MountEmulatedStorage()
I/libpersona( 4746): KNOX_SDCARD checking this for 10010
E/Zygote  ( 4746): v2
I/libpersona( 4746): KNOX_SDCARD not a persona
,I/SELinux ( 4746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4746 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 4746): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/iu.UploadsManager( 2053): num queued entries: 0
,I/iu.UploadsManager( 2053): num updated entries: 0
,I/iu.SyncManager( 2053): NEXT; no task
,D/TimaKeyStoreProvider( 4746): TimaSignature is unavailable
,D/ActivityThread( 4746): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 3833:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/MusicStore( 4673): Database version: 108
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4764): MountEmulatedStorage()
,E/Zygote  ( 4764): v2
I/libpersona( 4764): KNOX_SDCARD checking this for 10113
I/libpersona( 4764): KNOX_SDCARD not a persona
,I/SELinux ( 4764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4764 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4764): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 1942:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4764): TimaSignature is unavailable
,D/ActivityThread( 4764): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3833/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10004/pid_1942/cgroup.procs: No such file or directory
,I/SA      ( 4153): [SCU] == networkStateCheck == true
,I/SA      ( 4153): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4153): isChinaCountryCode : false
,I/SA      ( 4153): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 4153): [OR] == networkStateCheck true ==
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WaitQueueForNetworkActivate( 4746): notifyNetworkActivated
,I/SA      ( 4153): [OR] GetMyCountryZoneTask
,I/SA      ( 4153): [OR] onReceive END
,I/ActivityManager( 1015): Killing 3330:com.google.android.youtube/u0a166 (adj 15): empty #31
,V/DownloadManager( 1239): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 4153): [SRS] prepareGetMyCountryZone
,I/SA      ( 4153): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4153): [SSP] query invoked
,W/ResourcesManager( 4673): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4673): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4673): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 4746): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/libprocessgroup( 1015): failed to open /acct/uid_10166/pid_3330/cgroup.procs: No such file or directory
,W/ActivityThread( 4673): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4673): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4022fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4673): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4673): GMSCore installation verified
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 26195(1613KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/44MB, paused 2.479ms total 150.946ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,I/SA      ( 4153): [TPMU] GetMccFromDB : null
,I/SA      ( 4153): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4153): [TPM] isNoProxy(default) : true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4673): Config Database version: 1
,E/File    ( 4153): fail readDirectory() errno=2
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4673): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4673): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4673): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/MediaRouter( 4673): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,V/MusicLeanback( 4673): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/hcjo    ( 4746): AutoUpdateManager:IDLE:execute
,I/NetworkMonitor( 4673): type=WIFI subType= reason=null isConnected=true
,D/InitializeManagerStateMachine( 4746): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4746): exit::IDLE
,D/InitializeManagerStateMachine( 4746): entry::NETWORK_CHECK
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 4704): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/InitializeManagerStateMachine( 4746): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4746): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4746): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4746): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4746): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4746): entry::SUCCESS
D/hcjo    ( 4746): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ContextImpl( 4764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/hcjo    ( 4746): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4746): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4746): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4746): exit::SUCCESS
D/InitializeManagerStateMachine( 4746): entry::IDLE
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 4704): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4704): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4704): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 4764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 4764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 4673): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4802): MountEmulatedStorage()
E/Zygote  ( 4802): v2
I/libpersona( 4802): KNOX_SDCARD checking this for 10002
I/libpersona( 4802): KNOX_SDCARD not a persona
I/SELinux ( 4802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4802 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms,
,D/TimaKeyStoreProvider( 4802): TimaSignature is unavailable
,D/ActivityThread( 4802): Added TimaKeyStore provider
,W/GoogleHttpClient( 4673): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient( 4673): Falling back to old SSLCertificateSocketFactory
,I/GHttpClientFactory( 4673): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 3761:com.google.android.gm/u0a101 (adj 15): empty #31
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WebViewFactory( 4764): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 4764): Time to load native libraries: 1 ms (timestamps 2886-2887)
I/LibraryLoader( 4764): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4764): Binding Chromium to main looper Looper (main, tid 1) {3c62d7d8}
,I/LibraryLoader( 4764): Expected native library version number "",actual native library version number ""
,I/chromium( 4764): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_3761/cgroup.procs: No such file or directory
,E/Zygote  ( 4835): MountEmulatedStorage(),
I/BrowserStartupController( 4764): Initializing chromium process, singleProcess=true
,E/Zygote  ( 4835): v2
I/libpersona( 4835): KNOX_SDCARD checking this for 1000,
W/art     ( 4764): Attempt to remove local handle scope entry from IRT, ignoring
I/libpersona( 4835): KNOX_SDCARD not a persona,
I/SELinux ( 4835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/SysUtils( 4764): ApplicationContext is null in ApplicationStatus,
,I/SELinux ( 4835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4835): TimaSignature is unavailable
,D/ActivityThread( 4835): Added TimaKeyStore provider
W/chromium( 4764): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4764): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 4764): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4764): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4764): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4764):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 4835): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioManagerAndroid( 4764): Requires BLUETOOTH permission
,I/NSApplication( 4764): Starting up...
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4866): MountEmulatedStorage()
E/Zygote  ( 4866): v2
I/libpersona( 4866): KNOX_SDCARD checking this for 10120
I/libpersona( 4866): KNOX_SDCARD not a persona
,I/SELinux ( 4866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4866): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4866 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 4175:com.samsung.helphub/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3953:com.android.vending/u0a28 (adj 15): empty #32
,D/TimaKeyStoreProvider( 4866): TimaSignature is unavailable
,D/ActivityThread( 4866): Added TimaKeyStore provider
,W/ResourcesManager( 4866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DIAGMON_AGENT( 4835): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4835): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4835): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4835): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4835): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4835): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4175/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_3953/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4885): MountEmulatedStorage(),
E/Zygote  ( 4885): v2,
I/libpersona( 4885): KNOX_SDCARD checking this for 10009
,I/libpersona( 4885): KNOX_SDCARD not a persona
I/SELinux ( 4885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4885 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4885): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4885): TimaSignature is unavailable
,D/ActivityThread( 4885): Added TimaKeyStore provider
,I/SA      ( 4153): [RC New] Execute method=[GET] start
,I/SA      ( 4153): [RC New] Security=[true]
,I/System.out( 4153): Thread-616(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4153): Thread-616(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4153): Thread-616(ApacheHTTPLog):isShipBuild true
I/System.out( 4153): Thread-616(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4153): Thread-616(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10041
,I/ActivityManager( 1015): Killing 4221:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/FOTA_Client( 4885): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4885): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4885): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4885): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1015): Killing 4263:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/QuickConnect( 4401): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4401): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4401): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4907): MountEmulatedStorage(),
E/Zygote  ( 4907): v2
I/libpersona( 4907): KNOX_SDCARD checking this for 10145
I/libpersona( 4907): KNOX_SDCARD not a persona
,I/SELinux ( 4907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4907 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4289:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/SELinux ( 4907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4907): TimaSignature is unavailable
,D/ActivityThread( 4907): Added TimaKeyStore provider
,W/ResourcesManager( 4907): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4907): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4907): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4907): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4221/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4263/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_4289/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 4512): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 4512): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 1488): reloadBadges entered.
D/BadgeProvider( 4512): sendNotify, [notify] : null
D/BadgeProvider( 4512): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4512): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4512): update, [UpdateCount] : 1
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 4417:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4367:com.sec.android.app.mt/1000 (adj 15): empty #32
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/splitIntent( 1015): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1015): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4930): MountEmulatedStorage(),
I/libpersona( 4930): KNOX_SDCARD checking this for 10062
,E/Zygote  ( 4930): v2
I/libpersona( 4930): KNOX_SDCARD not a persona
I/SELinux ( 4930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4930 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4930): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/FOTA_Client( 4885): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1327): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1327): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/TimaKeyStoreProvider( 4930): TimaSignature is unavailable
,D/ActivityThread( 4930): Added TimaKeyStore provider
,I/FOTA_Client( 4885): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1327): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1327): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1327): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1327): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1327): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1327): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1327): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1327): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1327): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1327): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/KLMS-2.5.183: ( 3625): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Mar 14 23:38:02 GMT+01:00 2016
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/daemonapp( 1327): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/SecurityLogAgent( 4566): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4566): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4566): StateMachine : Current State = 1
I/KLMS-2.5.183: ( 3625): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 4153): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/comdaemonstockapp( 1327): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1327): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4367/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10131/pid_4417/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onCreate()
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,I/KLMS-2.5.183: ( 3625): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3625): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,E/Zygote  ( 4949): MountEmulatedStorage()
E/Zygote  ( 4949): v2
I/libpersona( 4949): KNOX_SDCARD checking this for 10157
I/libpersona( 4949): KNOX_SDCARD not a persona
,I/SELinux ( 4949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/StatusBar.NetworkController( 1189): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1189): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/ExternalOEMControlProvider( 4930): onCreate
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/SELinux ( 4949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1189): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.183: ( 3625): StateImplV2(): dateTimeChanged().START : Mon Mar 14 23:38:02 GMT+01:00 2016
I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4949 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
I/KLMS-2.5.183: ( 3625): StateImplV2(): dateTimeChanged().END
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     (  304): Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.219ms total 20.624ms
,D/TimaKeyStoreProvider( 4949): TimaSignature is unavailable
,D/ActivityThread( 4949): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 17.039ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.803ms
,E/Zygote  ( 4966): MountEmulatedStorage(),
E/Zygote  ( 4966): v2
I/libpersona( 4966): KNOX_SDCARD checking this for 10046
I/libpersona( 4966): KNOX_SDCARD not a persona
,I/SELinux ( 4966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4966 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux ( 4966): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/KLMS-2.5.183: ( 3625): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 4930): Time Difference not stored. TIME_DIFFERENCE
,W/ResourcesManager( 4949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4981): MountEmulatedStorage()
I/libpersona( 4981): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4981): v2
I/libpersona( 4981): KNOX_SDCARD not a persona
,I/SELinux ( 4981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/TimaKeyStoreProvider( 4966): TimaSignature is unavailable
,D/ActivityThread( 4966): Added TimaKeyStore provider
,I/SELinux ( 4981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4981 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4981): TimaSignature is unavailable
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,D/ActivityThread( 4981): Added TimaKeyStore provider
,W/ResourcesManager( 4966): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4966): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4966): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4997): MountEmulatedStorage()
E/Zygote  ( 4997): v2
I/libpersona( 4997): KNOX_SDCARD checking this for 1000
I/libpersona( 4997): KNOX_SDCARD not a persona
,I/SELinux ( 4997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4461:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4997): TimaSignature is unavailable
,D/Mms/MmsApp( 4966): [start]    onCreate() consume time = 0.0
,D/ActivityThread( 4997): Added TimaKeyStore provider
,W/ResourcesManager( 4981): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimeService( 4997): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457995083195
D/        ( 4997): TimeServiceNative: User Time to be set is 1457995083195
D/QC-time-services( 4997): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4997): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4997): Lib:time_genoff_operation: pargs->ts_val = 1457995083195
,D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4997): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457995083195
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1457995083195, operation = 0
D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/13/70 20:43:19
,D/QC-time-services(  316): Daemon:Value read from RTC seconds = 22106599000
D/QC-time-services(  316): Daemon:new time 1457995083195 
,D/QC-time-services(  316): Daemon: delta 1435888484195 genoff 1435888484195 
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888484195 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/accuweather( 1720): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1720): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/QC-time-services(  316): Updating the TOD offset
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888484195 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5013): MountEmulatedStorage()
,E/Zygote  ( 5013): v2
I/libpersona( 5013): KNOX_SDCARD checking this for 10085
I/libpersona( 5013): KNOX_SDCARD not a persona
,I/SELinux ( 5013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5013 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 4997): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1119923684195
I/SELinux ( 5013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4136:com.test.thalitest/u0a155 (adj 15): empty #31
E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1015): Killing 4547:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/SA      ( 4153): [RC New] [v2liruge] api execute + 786
I/SA      ( 4153): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4153): AsyncTask #1 calls detatch()
,D/TimaKeyStoreProvider( 5013): TimaSignature is unavailable
,D/ActivityThread( 5013): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4624:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,I/SA      ( 4153): [ODM] saveOpenData( GEO_IP, PL )
,W/ResourcesManager( 5013): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5013): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5013): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,W/art     ( 4966): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 121.351ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10139/pid_4461/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4547/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10155/pid_4136/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10068/pid_4624/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1015): SIOP:: AP = 390
,D/Mms/ArtClassLoader( 4966): init before art
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 17896(1071KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 29MB/44MB, paused 2.565ms total 141.201ms
,D/Mms/TelephonyPermission( 4966): start operation mode monitor
,I/SA      ( 4153): [OCP] update openData : PL
,I/SA      ( 4153): [TPMU] getNetworkMcc : 
,I/SA      ( 4153): [SCU] saveMccToPreferece Start
I/SA      ( 4153): [SCU] RegionMCC : 260
I/SA      ( 4153): [SSP] query invoked
,I/SA      ( 4153): [TPMU] GetMccFromDB : null
I/SA      ( 4153): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4153): [SCU] saveMccToPreferece End
,I/SA      ( 4153): [RC New] executeRequest [v2liruge] end. 1004
I/SA      ( 4153): [RC New] Execute end
I/SA      ( 4153): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4153): [OR] GetMyCountryZoneTask Success
,W/ResourcesManager( 4966): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4966): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4966): isDefault true
,D/Mms/MmsApp( 4966): onCreate() com.android.mms
,D/SettingsProvider( 1015): name = next_alarm_formatted
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10085
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/Mms/MmsApp( 4966): [start]    initCountryIso consume time = 316.570729
,D/CountryDetector( 1015): The first listener is added
,D/Mms/MmsApp( 4966): [end]    initCountryIso consume time = 6.388646
D/Mms/MmsConfig( 4966): [start]    MmsConfig.init() consume time = 0.129427
,D/Mms/MmsConfig( 4966): before partial update
,D/Mms/MmsConfig( 4966): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4966): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4966): isAuth is false
,D/Mms/MmsConfig( 4966): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1464): query,matched:2117, calling pid = 4966
,D/TP/MmsSmsProvider( 1464): match 2117:Elapsed time : 1.296 ms
,D/EasySignUpManager_1.0.1( 4966): isAuth is false
,D/EasySignUpManager_1.0.1( 4966): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4966): mps_code.dat does not exist
,E/CscParser( 4966): customer_path =/system/csc/customer.xml
E/CscParser( 4966): fileName + /system/csc/customer.xml
,D/PackageManager( 1015): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/CscParser( 4966): mps_code.dat does not exist
E/CscParser( 4966): customer_path =/system/csc/customer.xml
,E/CscParser( 4966): fileName + /system/csc/customer.xml
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/CscParser( 4966): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4966):  enable multiwindow = true
,E/Mms/MessageUtils( 4966): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4966): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4966): [end]    init() consume time = 69.79802
,D/Mms/Contact( 4966): [start]    init() consume time = 1.299375
,D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 4966
,D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 1.359 ms
,D/Mms/Contact( 4966): [end]    init consume time = 13.434271
,D/Mms/DraftCache( 4966): [start]    rebuildCache consume time = 7.739896
,D/TP/MmsSmsProvider( 1464): query,matched:12, calling pid = 4966
,D/Mms/MethodReflector( 4966): getSubId is called
D/Mms/TelephonyUtils( 4966): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1464): match 12:Elapsed time : 2.790 ms
,D/Mms/MethodReflector( 4966): getTelephonyProperty is called
D/Mms/DownloadManager( 4966): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4966): auto download without roaming -> true
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 4966): getSubId is called
,D/Mms/MethodReflector( 4966): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4966): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4966): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4966): getTelephonyProperty is called
D/Mms/DownloadManager( 4966): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4966): auto download without roaming -> true
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4966): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4966): mAutoDownload ------> true
W/art     ( 5013): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 119.633ms
,D/Mms/DraftCache( 4966): [end]    rebuildCache consume time = 14.940261
,D/ComposerPerformance( 4966): 1457995083631 ms / [DONE] Composer constructor
,E/CII     ( 4966): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4966): ReservationManager()
,I/Mms/ReservationManager( 4966): resetAfterConnected()
,D/Mms/Conversation( 4966): [start]    init() consume time = 42.773958
,D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 4966
,D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 3.086 ms
,I/Mms/ReservationManager( 4966): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1464): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1464): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1464): updateThread(), thread_id = 9223372036854775807
,D/Mms/MmsApp( 4966): [end]    onCreate() consume time = 13.94651
V/TP/MmsSmsDatabaseHelper( 1464): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/DownloadManager( 4966): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 4966): roaming ------> false, mSimSlot = 0
,E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
,I/ActivityManager( 1015): Killing 4641:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1464): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): need read changed broadcast:false
,D/Mms/MethodReflector( 4966): getSubId is called
D/Mms/TelephonyUtils( 4966): getLongSubId from simSlot 0, return Value = -1
D/Mms/Conversation( 4966): [end]    init consume time = 15.326979
D/Mms/MessagingNotification( 4966): [start]    init() consume time = 0.120105
,D/Mms/MethodReflector( 4966): getTelephonyProperty is called
D/Mms/DownloadManager( 4966): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4966): auto download without roaming -> true
D/Mms/DownloadManager( 4966): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4966): mAutoDownload ------> true
,D/Mms/MessagingNotification( 4966): [end]    init consume time = 4.7475
,D/Mms/Synchronizer( 4966): [start]    doSync consume time = 3.178281
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 4966
,V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
,D/Mms/SpamFilter( 4966): [start]    SpamFilter fill() begin consume time = 2.899583
,D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 2.649 ms
,D/TP/MmsSmsProvider( 1464): update, matched:300, calling pid = 4966
V/TP/MmsSmsProvider( 1464): syncDBData start
,V/TP/MmsSmsProvider( 1464): syncDBData sms end
,V/TP/MmsSmsProvider( 1464): syncDBData mms end
,V/TP/MmsSmsProvider( 1464): syncDBData end
,D/Mms/Synchronizer( 4966): [end]    doSync consume time = 8.788229
,D/TP/MmsSmsProvider( 1464): query,matched:400, calling pid = 4966
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5039 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 5039): MountEmulatedStorage()
E/Zygote  ( 5039): v2
I/libpersona( 5039): KNOX_SDCARD checking this for 10094
I/libpersona( 5039): KNOX_SDCARD not a persona
,I/SELinux ( 5039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4656:com.sec.pcw.device/1000 (adj 15): empty #31
,E/SELinux ( 5039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/SpamFilter( 4966): [end]    SpamFilter fill() finished consume time = 31.806615
,D/TimaKeyStoreProvider( 5039): TimaSignature is unavailable
,D/ActivityThread( 5039): Added TimaKeyStore provider
,D/Mms/ArtClassLoader( 4966): init [DONE] art
,D/Mms/MessagingNotification( 4966): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1464): query,matched:26, calling pid = 4966
,D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.737 ms
,D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 4966
,D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 1.640 ms
,D/elm:15183( 5039): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 5039): ELMEngine.ELMEngine( context ).
D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/elm:15183( 5039): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5039): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 5039): ElmAgentService : onCreate()
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 5039): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_4641/cgroup.procs: No such file or directory
,D/elm:15183( 5039): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 5039): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15183( 5039): ModuleBase.ModifySetAlarm()
,D/elm:15183( 5039): MDMBridge.getInstance()
D/elm:15183( 5039): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5059): MountEmulatedStorage()
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5059 uid=10134 gids={50134, 9997} abi=armeabi-v7a
E/Zygote  ( 5059): v2
I/libpersona( 5059): KNOX_SDCARD checking this for 10134
I/SELinux ( 5059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5059): KNOX_SDCARD not a persona
,D/elm:15183( 5039): ElmAgentService : onDestroy().
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4656/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,I/SELinux ( 5059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5059): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
E/Zygote  ( 5071): MountEmulatedStorage()
E/Zygote  ( 5071): v2
I/libpersona( 5071): KNOX_SDCARD checking this for 10025
I/libpersona( 5071): KNOX_SDCARD not a persona
,I/SELinux ( 5071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5071 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4689:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 54694
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3478)
,D/TimaKeyStoreProvider( 5059): TimaSignature is unavailable
,D/ActivityThread( 5059): Added TimaKeyStore provider
,W/ResourcesManager( 5059): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5059): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5071): TimaSignature is unavailable
,D/ActivityThread( 5071): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4704:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,W/ResourcesManager( 5071): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/splitIntent( 1015): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 4721:com.android.chrome/u0a81 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1015): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 5071): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 4966): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10159/pid_4689/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_4704/cgroup.procs: No such file or directory
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false,
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false,
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5071): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/Zygote  ( 5091): MountEmulatedStorage()
,E/Zygote  ( 5091): v2
I/libpersona( 5091): KNOX_SDCARD checking this for 1000
I/libpersona( 5091): KNOX_SDCARD not a persona,
,I/SELinux ( 5091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5091 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/SELinux ( 5091): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_4721/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5091): TimaSignature is unavailable
,D/ActivityThread( 5091): Added TimaKeyStore provider
,E/MTPRx   ( 5091): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 5091): sealedState: false
V/MTPRx   ( 5091): sealedUsbMassStorageState: false
E/MTPRx   ( 5091): check value of boot_completed is1
E/MTPRx   ( 5091): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5091): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5091): Status for mount/Unmount :removed
E/MTPRx   ( 5091): SDcard is not available
,W/MTPRx   ( 5091): value of connected istrue
W/MTPRx   ( 5091): value of configured istrue
W/MTPRx   ( 5091): value of mtpEnabled istrue
W/MTPRx   ( 5091): value of ptpEnabled isfalse
,E/MTPRx   ( 5091): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5091): mFirstTime: false
,I/ValidateNoPeople( 1015): mEvictionCount: 0
D/Mms/Contact( 4966): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4966): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4966): [start]    invalidate() consume time = 359.504635
,D/Mms/ContactsCache( 4966): [end]    invalidate() consume time = 0.347813
,D/        ( 5091): MTP: reading debug level property
,E/MTPJNIInterface( 5091): Getting CryptionKey from JAVA
,E/MTPRx   ( 5091): currentUserId is 0
,E/MTPRx   ( 5091): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5091): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 5091): is_Privatemode is NOT 1
,D/SettingsProvider( 1015): name = boot_time_connected
,E/MTPRx   ( 5091): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 5091): noti = 17
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/SecContentProvider( 1015): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5091): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,I/ConfigService( 1850): onDestroy
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MTPRx   ( 5091): else part ... so first time!!!
,E/MTPPlaObsrvr( 5091): inside setContext()
E/MTPPlaObsrvr( 5091):  inside createplafiles
,I/SecKeyguardClockSingleView( 1189): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5091): playlist count is0
,E/MTPPlaObsrvr( 5091):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5091):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5091): Inside registerContentObserver
,E/MtpAdbObserver( 5091): inside setContext()
,E/MtpAdbObserver( 5091): Inside registerContentObserver
,W/Settings( 5091): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MtpService( 5091): onCreate.
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1239): updating state; isCurrentUser=true, mMtpLocked=false
,V/MtpMediaDBManager( 5091): inside deleteAllDB
,E/MtpService( 5091): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5091): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5091): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5091): onStartCommand.
,W/MTPRx   ( 5091): calling native method
E/MTPJNIInterface( 5091): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5091): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MTPJNIInterface( 5091): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5091): noti = 10
,E/MtpService( 5091): onStartCommand.
,W/MTPRx   ( 5091): calling native method
E/MtpService( 5091): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 5091): Checking the driver time out
E/MTPJNIInterface( 5091): noti = 2
D/        ( 5091): deleting sockets before message queue initialization
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/        ( 5091): event handler thread is created, so set the flag
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 5091): called native method
,E/MTPJNIInterface( 5091): setting Media scanner status0
,E/MTPJNIInterface( 5091): After setting Media scanner status0
,W/MTPRx   ( 5091): notification from stack 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/MtpMediaDBManager( 5091): inside Thread updateDB
,E/        ( 5091): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
V/UserPresentBroadcastReceiver( 1850): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/MTPJNIInterface( 5091): Getting media scanner status0
,E/MTPJNIInterface( 5091): DeviceName is A5-1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{149b201 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,E/MtpMediaDBManager( 5091): count : 27
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,V/BluetoothStatusReceiver( 1189): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1189): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5114): MountEmulatedStorage(),
I/libpersona( 5114): KNOX_SDCARD checking this for 10003
E/Zygote  ( 5114): v2,
I/libpersona( 5114): KNOX_SDCARD not a persona
I/SELinux ( 5114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5114 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 5114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5114): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/MtpMediaDBManager( 5091): sending db update complete noti to stack,
E/MTPJNIInterface( 5091): noti = 29,
,E/MTPJNIInterface( 5091): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5091): SDcard is not available
,E/        ( 5091): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
D/TimaKeyStoreProvider( 5114): TimaSignature is unavailable
D/ActivityThread( 5114): Added TimaKeyStore provider
,E/        ( 5091): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 5091): Status for mount/Unmount :removed
E/MTPJNIInterface( 5091): SDcard is not available
E/SQLiteLog( 5091): (21) API call with NULL database connection pointer
E/SQLiteLog( 5091): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5091): (21) API call with NULL database connection pointer
E/SQLiteLog( 5091): (21) misuse at line 100726 of [9491ba7d73]
,E/SQLiteLog( 5091): (21) API call with NULL database connection pointer
E/SQLiteLog( 5091): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5091): (21) API call with NULL database connection pointer
E/SQLiteLog( 5091): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5091): notification from stack 2
,D/        ( 5091): [mtp_init_device] Library open with 32 bits.
,D/        ( 5091): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5091): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 5091): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 5091):  [sua_support_present:1287] returning false 
,D/        ( 5091): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
