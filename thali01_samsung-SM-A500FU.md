#### Test 58751238ee11130_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/SettingSearchManagerReceiver( 1453): endInsert
--------- beginning of system
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5167): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5167 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5167): v2
I/libpersona( 5167): KNOX_SDCARD checking this for 10101
I/libpersona( 5167): KNOX_SDCARD not a persona
I/SELinux ( 5167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5167): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5167): TimaSignature is unavailable
D/ActivityThread( 5167): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_4658/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10125/pid_4234/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5167): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5167): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5167): Observing account changes for notifications
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5167): Error finding the version of the Email provider.....
E/Gmail   ( 5167): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5167): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5167): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5167): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5167): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5167): We do not support migrating this version of the Email provider.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5167): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 4507:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5201): MountEmulatedStorage()
E/Zygote  ( 5201): v2
I/libpersona( 5201): KNOX_SDCARD checking this for 10033
I/libpersona( 5201): KNOX_SDCARD not a persona
I/SELinux ( 5201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5201 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5201): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5201): TimaSignature is unavailable
D/ActivityThread( 5201): Added TimaKeyStore provider
E/SQLiteLog( 5167): (283) recovered 40 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_4507/cgroup.procs: No such file or directory
E/File    ( 5167): fail readDirectory() errno=2
W/ResourcesManager( 5201): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Gmail   ( 5167): notifyAccountChanged
I/Gmail   ( 5167): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5167): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5201): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Gmail   ( 5167): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5167): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5167): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 5201): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5201): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Gmail   ( 5167): getAccountsCursor
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ServiceManager(  334): Waiting for service AtCmdFwd...
I/ActivityManager( 1017): Killing 4271:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GCoreFlp( 1872): No location to return for getLastLocation()
W/FusedLocationProvider( 1872): location=null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1872): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_4271/cgroup.procs: No such file or directory
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{20ec0b8 u0 com.sec.bcservice/.BroadcastService}
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5234): 
D/AndroidRuntime( 5234): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5234): CheckJNI is OFF
D/AndroidRuntime( 5234): readGMSProperty: start
D/AndroidRuntime( 5234): readGMSProperty: already setted!!
D/AndroidRuntime( 5234): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5234): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5234): readGMSProperty: end
D/AndroidRuntime( 5234): addProductProperty: start
I/art     ( 1017): Background sticky concurrent mark sweep GC freed 120985(4MB) AllocSpace objects, 16(5MB) LOS objects, 13% free, 54MB/62MB, paused 4.063ms total 156.883ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SPPClientService( 4051): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5243): MountEmulatedStorage()
E/Zygote  ( 5243): v2
I/libpersona( 5243): KNOX_SDCARD checking this for 10035
I/libpersona( 5243): KNOX_SDCARD not a persona
I/SELinux ( 5243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5243 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5243): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5243): TimaSignature is unavailable
D/ActivityThread( 5243): Added TimaKeyStore provider
E/SPPClientService( 5243): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5243): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 5243): PushLog.txt file is not deleted.
D/SPPClientService( 5243): PushLog.txt file is not deleted.
D/SPPClientService( 5243): ============PushLog. stop!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/AffinityControl( 5234): AffinityControl: registerfunction enter
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5270): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5270 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5270): v2
I/ActivityManager( 1017): Killing 4162:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/libpersona( 5270): KNOX_SDCARD checking this for 10035
I/libpersona( 5270): KNOX_SDCARD not a persona
I/SELinux ( 5270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5270): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5234): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5234): Shutting down VM
D/TimaKeyStoreProvider( 5270): TimaSignature is unavailable
D/ActivityThread( 5270): Added TimaKeyStore provider
E/SPPClientService( 5270): ============PushLog. commonIsShipBuild. stop!
E/LNoti   ( 5270): [PhoneStatusChangeReceiver] This device doesn't register yet.
E/SPPClientService( 5270): [PushClientApplication] Push log off : This is Ship build version
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 5270): PushLog.txt file is not deleted.
D/SPPClientService( 5270): PushLog.txt file is not deleted.
D/SPPClientService( 5270): ============PushLog. stop!
E/Zygote  ( 5290): MountEmulatedStorage()
E/Zygote  ( 5290): v2
I/libpersona( 5290): KNOX_SDCARD checking this for 10104
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5290 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4408:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/libpersona( 5290): KNOX_SDCARD not a persona
I/SELinux ( 5290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5290): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5290): TimaSignature is unavailable
D/ActivityThread( 5290): Added TimaKeyStore provider
I/art     (  318): Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 27.684ms
W/ResourcesManager( 5290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.893ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.667ms
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4408/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_4162/cgroup.procs: No such file or directory
W/art     ( 5234): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/art     ( 1017): Background sticky concurrent mark sweep GC freed 72771(2MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 62MB/62MB, paused 3.070ms total 110.144ms
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Babel   ( 5290): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5290): MmsConfig.loadMmsSettings
,I/Babel   ( 5290): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 5290): MmsConfig.loadFromDatabase
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 5290): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5290): MmsConfig.loadFromResources
,E/Babel   ( 5290): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5290): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_StickerModule( 5290): App launched.
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  281): getCameraInfo: X
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,E/Zygote  ( 5315): MountEmulatedStorage(),
I/libpersona( 5315): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 5315): v2
I/libpersona( 5315): KNOX_SDCARD not a persona
,I/SELinux ( 5315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/art     ( 5290): Suspending all threads took: 8.881ms
E/SELinux ( 5315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5315): TimaSignature is unavailable
,D/ActivityThread( 5315): Added TimaKeyStore provider
,W/VideoCapabilities( 5290): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5290): Unsupported mime audio/evrc
,W/AudioCapabilities( 5290): Unsupported mime audio/qcelp
,I/art     ( 1017): Background partial concurrent mark sweep GC freed 334435(19MB) AllocSpace objects, 4(5MB) LOS objects, 27% free, 41MB/57MB, paused 6.065ms total 285.995ms
,W/AudioCapabilities( 5290): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5290): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5290): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5290): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5290): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5290): Unsupported mime audio/evrc
,I/DIAGMON_AGENT( 5315): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/VideoCapabilities( 5290): Unsupported mime video/wvc1
,W/VideoCapabilities( 5290): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5290): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5290): Unsupported mime video/wvc1
,W/VideoCapabilities( 5290): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5290): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5290): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5290): Unsupported mime video/mp43
,W/VideoCapabilities( 5290): Unsupported mime video/sorenson
,W/VideoCapabilities( 5290): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5290): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/PackageManager( 1017): verifying app can be installed or not
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  Checking SIG BL - true
I/ActivityManager( 1017): Killing 4710:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/ApplicationPolicy( 1017): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1017): ship mode
,I/DIAGMON_AGENT( 5315): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5315): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5315): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1017): Killing 4111:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/DBG_DM  ( 3058): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5331): MountEmulatedStorage()
I/libpersona( 5331): KNOX_SDCARD checking this for 10142
E/Zygote  ( 5331): v2
I/libpersona( 5331): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5331 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5331): TimaSignature is unavailable
,D/ActivityThread( 5331): Added TimaKeyStore provider
,V/TaskCloserActivity( 5331): TaskCloserActivity enter()
,V/TaskCloserActivity( 5331): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5346): MountEmulatedStorage(),
E/Zygote  ( 5346): v2
I/libpersona( 5346): KNOX_SDCARD checking this for 10135,
I/libpersona( 5346): KNOX_SDCARD not a persona
,I/SELinux ( 5346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5346 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 5346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 4729:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 5346): TimaSignature is unavailable
,D/ActivityThread( 5346): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_4710/cgroup.procs: No such file or directory
,W/ResourcesManager( 5346): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5346): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5346): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_4111/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10157/pid_4729/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5368): MountEmulatedStorage()
,E/Zygote  ( 5368): v2
,I/libpersona( 5368): KNOX_SDCARD checking this for 10042
I/libpersona( 5368): KNOX_SDCARD not a persona
,I/SELinux ( 5368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5368 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 4768:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/SELinux ( 5368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5368): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5368): TimaSignature is unavailable
,D/ActivityThread( 5368): Added TimaKeyStore provider
,W/ResourcesManager( 5368): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5368): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4768/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5386): MountEmulatedStorage()
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
E/Zygote  ( 5386): v2
I/libpersona( 5386): KNOX_SDCARD checking this for 1000
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/libpersona( 5386): KNOX_SDCARD not a persona
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar,
I/SELinux ( 5386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,E/SQLiteLog( 5368): (284) automatic index on view_events(_id)
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/TimaKeyStoreProvider( 5386): TimaSignature is unavailable
,D/ActivityThread( 5386): Added TimaKeyStore provider
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CalendarAlarmManager( 5368): sys current time:1455027653534
,D/CalendarAlarmManager( 5368): reminder amount:0
,E/MTPRx   ( 5386): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
V/MTPRx   ( 5386): sealedState: false
V/MTPRx   ( 5386): sealedUsbMassStorageState: false
E/MTPRx   ( 5386): check value of boot_completed is1
E/MTPRx   ( 5386): check booting is completed_sys.boot_completed
E/MTPRx   ( 5386): Sd-Card path/storage/extSdCard
E/MTPRx   ( 5386): Status for mount/Unmount :removed
E/MTPRx   ( 5386): SDcard is not available
W/MTPRx   ( 5386): value of connected istrue
W/MTPRx   ( 5386): value of configured istrue
W/MTPRx   ( 5386): value of mtpEnabled istrue
W/MTPRx   ( 5386): value of ptpEnabled isfalse
E/MTPRx   ( 5386): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 5386): mFirstTime: false
D/        ( 5386): MTP: reading debug level property
E/MTPJNIInterface( 5386): Getting CryptionKey from JAVA
E/MTPRx   ( 5386): currentUserId is 0
E/MTPRx   ( 5386): Start observing USB_STATE_MATCH 
E/MTPRx   ( 5386): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5386): is_Privatemode is NOT 1
D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5386): sending MTP_ICON_ENABLED to stack
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MTPRx   ( 5386): else part ... so first time!!!
,E/MTPPlaObsrvr( 5386): inside setContext()
E/MTPPlaObsrvr( 5386):  inside createplafiles
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5386): playlist count is0
,E/MTPPlaObsrvr( 5386):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5386):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5386): Inside registerContentObserver
,E/MtpAdbObserver( 5386): inside setContext()
E/MtpAdbObserver( 5386): Inside registerContentObserver
W/Settings( 5386): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,V/MtpMediaDBManager( 5386): inside deleteAllDB
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MtpService( 5386): onCreate.
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5386): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5386): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MtpService( 1225): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 5386): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5386): onStartCommand.
,W/MTPRx   ( 5386): calling native method
,E/MTPJNIInterface( 5386): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 5386): < MTP > Registering BroadCast receiver :::::::
,E/MtpService( 5386): handleMessage. msg= { when=-5ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5386): noti = 10
,V/MtpMediaDBManager( 5386): inside Thread updateDB
,E/MtpService( 5386): onStartCommand.
W/MTPRx   ( 5386): calling native method
,E/MTPRx   ( 5386): Checking the driver time out
E/MTPJNIInterface( 5386): noti = 2
D/        ( 5386): deleting sockets before message queue initialization
D/        ( 5386): event handler thread is created, so set the flag
,E/MtpService( 5386): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 5386): called native method
E/MTPJNIInterface( 5386): setting Media scanner status0
E/MTPJNIInterface( 5386): After setting Media scanner status0
,D/MediaScannerReceiver( 1225): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/SMD     (  289): DCD OFF,
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/MTPRx   ( 5386): notification from stack 1
,E/        ( 5386): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5386): Getting media scanner status0
,E/MTPJNIInterface( 5386): DeviceName is A5-1
,E/MtpMediaDBManager( 5386): count : 27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/PolicyManagerBroadcastReceiver( 5116): This process will be killed soon.
,I/Process ( 5116): Sending signal. PID: 5116 SIG: 9
,I/art     ( 1017): Background partial concurrent mark sweep GC freed 259009(14MB) AllocSpace objects, 4(6MB) LOS objects, 28% free, 40MB/56MB, paused 4.668ms total 245.617ms
,W/MtpMediaDBManager( 5386): sending db update complete noti to stack
E/MTPJNIInterface( 5386): noti = 29
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 5386): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5386): SDcard is not available
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5386): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5386): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 5386): Status for mount/Unmount :removed
E/MTPJNIInterface( 5386): SDcard is not available
E/SQLiteLog( 5386): (21) API call with NULL database connection pointer
E/SQLiteLog( 5386): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5386): (21) API call with NULL database connection pointer
E/SQLiteLog( 5386): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5386): (21) API call with NULL database connection pointer
E/SQLiteLog( 5386): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5386): (21) API call with NULL database connection pointer
E/SQLiteLog( 5386): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5386): notification from stack 2
,D/        ( 5386): [mtp_init_device] Library open with 32 bits.
D/        ( 5386): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5386): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5386): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5386):  [sua_support_present:1287] returning false 
D/        ( 5386): *****Starting mtp_io()
,W/MTPRx   ( 5386): notification from stack 3
D/        ( 5386): [mtp_start_io] source_thread Creation 
D/        ( 5386): [mtp_start_io] sink_thread Creation 
D/        ( 5386): [mtp_start_io:376] sink thread created so set th_sink
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PackageManager( 1017): Existing package
,D/PackageManager( 1017): Renaming /data/app/vmdl270435361.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1017): installNewPackageLI: Package{1effe154 com.test.thalitest}
,I/PackageManager( 1017): scanFileNewer : com.test.thalitest
,I/ActivityManager( 1017): Process com.sec.android.app.wluc (pid 5116)(adj 15) has died(86,1159)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/MediaScannerService( 1225): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/WearableService( 1872): callingUid 10012, callindPid: 1872
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,D/MediaScanner( 1225): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
,V/MediaScanner( 1225): processDirectory :  /storage/emulated/0
,I/MusicLeanback( 4495): Conditions not met for autocaching.
I/MusicLeanback( 4495): Stop autocaching.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(75ebcf7
,I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
V/MediaScanner( 1225): processDirectory :  /storage/extSdCard
W/MediaScanner( 1225): Error opening directory, reason : Permission denied.
W/MediaScanner( 1225): 7klwibgf7fxlKdCbid7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1225):  prescan time: 29ms (DB items: 27)
V/MediaScanner( 1225):     scan time: 33ms (Caching mode: true), (makeEntry time: 20ms ~60%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 7ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 69ms
V/MediaScanner( 1225): checked files: 10  directories : 17  (I: 0, U: 0)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/iu.UploadsManager( 2036): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/MediaScannerService( 1225): !@done scanning volume external
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MTPJNIInterface( 5386): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1300): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,E/GmsUtils( 4495): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4495): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2036): End new media; added: 0, uploading: 0, time: 76 ms
,I/SettingSearch/SettingsSearchManager( 1300):  Infomation -> getItem size : 306
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1017): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1017): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,W/ResourcesManager( 1300): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1453): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1453): Media DB Scanner finished.
D/CscFactoryReceiver( 1453): start service to Set Ringtone
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1453): start service to Set Notification
,I/dex2oat ( 5426): ----------------------------------------------------
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
I/dex2oat ( 5426): <SS>: S T A R T I N G . . .
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
I/dex2oat ( 5426): <SS>: going to process manifest for 32-bit...
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1453): start service to Set Alarmtone
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscUpdateService( 1453): onStart
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
E/CscUpdateService( 1453): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1453): only ringtone update
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,D/CscUpdateService( 1453): onStart
E/CscUpdateService( 1453): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1453): only notification update
,D/CscUpdateService( 1453): onStart
E/CscUpdateService( 1453): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1453): only alarmtone update
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/        ( 5426): SS_ART_lib [I]: Memory allocation: ctx
,I/        ( 5426): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5426): SS_ART_lib [I]: Parsing Manifest for SS stuff
,I/        ( 5426): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5426): SS_ART_lib [I]: Memory allocation: ctx->package_name
,E/CscParser( 1453): update(): xml file exist
,I/        ( 5426): SS_ART_lib [I]: Parsing completed
I/        ( 5426): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5426): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5426): SS_ART_lib [I]: access to SS denied
I/        ( 5426): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5426): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5426): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5426): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5426): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5426): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5426): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/Zygote  ( 5432): MountEmulatedStorage()
E/Zygote  ( 5432): v2
I/libpersona( 5432): KNOX_SDCARD checking this for 10006
I/libpersona( 5432): KNOX_SDCARD not a persona
,I/SELinux ( 5432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
W/CSCSettings( 1453): Setting Ringtones (type) : 4
I/ActivityManager( 1017): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5432 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
D/CscParser( 1453): AlarmTone: null
W/CSCSettings( 1453): 1. Tag_Str: null
E/CscParser( 1453): update(): xml file exist
W/CSCSettings( 1453): Setting Ringtones (type) : 2
D/CscParser( 1453): MessageTone: null
,W/CSCSettings( 1453): 1. Tag_Str: null
I/SELinux ( 5432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/CscParser( 1453): update(): xml file exist
,W/CSCSettings( 1453): Setting Ringtones (type) : 1
,D/CscParser( 1453): RingTone: null
W/CSCSettings( 1453): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5432): TimaSignature is unavailable
,D/ActivityThread( 5432): Added TimaKeyStore provider,
,I/ThumbnailProvider( 5432): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5432): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5432): [START] processBroadcastIntent ...
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5013): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5013): handleMeidaScanFinish()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 5013): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5013): query fail: 
I/BroadcastProcessorService( 5432): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/LocalSuggestAlbumData( 5013): query fail: 
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SystemInfo( 5432): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5432): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5432): [START] DocumentService startDocumentService
,I/FaceInterface( 5013): startFaceScan() : waiting 5 sec
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5432): DocumentService onCreate ... service
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5432): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5432): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2593):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 2593): no now playing list
,D/BluetoothMediaBrowser( 2593):  getNowPlayingId now playing id : -1
,E/SystemInfo( 5432): [SIOP LEVEL] : 0
,I/DocumentService( 5432): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5432): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 5432): fail readDirectory() errno=13
E/File    ( 5432): fail readDirectory() errno=13
,I/SystemInfo( 5432): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5432): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5432): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :44
E/DocumentService( 5432): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5432): [INDEX] Total time taken for each file :0
,I/DocumentService( 5432): DocumentService onDestroy start
,I/DocumentService( 5432): DocumentService onDestroy end
,I/DocumentService( 5432): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5432): InterruptedException: null
,I/SystemInfo( 5432): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5432): DocumentService cleanupEverything end
,I/Process ( 5432): Sending signal. PID: 5432 SIG: 9
,I/MediaStoreImporter( 4495): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 1017): Process com.samsung.indexservice (pid 5432)(adj 9) has died(75,1160)
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,I/CalendarProvider2( 5368): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/dex2oat ( 5426): dex2oat took 538.800ms (threads: 4)
,I/PackageManager( 1017): do mInstaller.dexopt : 0
,D/PackageManager( 1017): Time to dexopt: 0.621 seconds
,W/System.err( 1017): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	,at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1017): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1017): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1017): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1017): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1017): 	... 5 more
,I/HarmonyEASService( 1017): Updating for all 1
D/PackageManager( 1017): New package installed
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 1017): doPostInstall for uid{10155}
,D/PackageManager( 1017): token 1 to BM for possible restore
,V/BackupManagerService( 1017): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1017): Finishing install immediately
,D/PackageManager( 1017): BM finishing package install for 1
,D/PackageManager( 1017): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4218): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5464): MountEmulatedStorage()
,E/Zygote  ( 5464): v2
,I/libpersona( 5464): KNOX_SDCARD checking this for 1000
,I/libpersona( 5464): KNOX_SDCARD not a persona
,I/SELinux ( 5464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/PackageManager( 1017): [MSG] POST_INSTALL: observer{684295757}
D/PackageManager( 1017):           Handling post-install for 1
I/SELinux ( 5464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 4792:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FaceInterface( 5013): startFaceScan() : going on
,D/FaceInterface( 5013): startFaceScan() is called.
,D/TimaKeyStoreProvider( 5464): TimaSignature is unavailable
,D/ActivityThread( 5464): Added TimaKeyStore provider
,D/ContentApp( 1225): startScan() is called.
,D/FaceValue( 1225): mSleepTime: 800
D/FaceValue( 1225): mMaxThreadNum: 2
,W/FaceValue( 1225): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1225): startScan() is end.
,W/Settings( 1017): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1225): isNeedToRestore : start
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAservice-UpdateReceiver( 5464): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SamsungIME( 1782): mOCRHelper is null
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1017): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/FaceInterface( 5013): startFaceScan() : going on
,D/FaceInterface( 5013): startFaceScan() is called.
,E/Zygote  ( 5482): MountEmulatedStorage()
E/Zygote  ( 5482): v2
I/libpersona( 5482): KNOX_SDCARD checking this for 10057
I/libpersona( 5482): KNOX_SDCARD not a persona
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 6847(462KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 717us total 33.789ms
,I/SELinux ( 5482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5482 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 5482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5482): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 4815:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/ContentApp( 1225): startScan() is called.
,D/ContentApp( 1225): startScan() is end.
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1225): isNeedToRestore : start
,D/TimaKeyStoreProvider( 5482): TimaSignature is unavailable
,D/ActivityThread( 5482): Added TimaKeyStore provider
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1017): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1017): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1017): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
I/art     ( 1017): Explicit concurrent mark sweep GC freed 61235(3MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 2.981ms total 334.404ms
,D/PackageManager( 1017): result of install: 1{684295757}
,I/PackageManager( 1017): Observer no longer exists.
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5502): MountEmulatedStorage()
E/Zygote  ( 5502): v2
I/libpersona( 5502): KNOX_SDCARD checking this for 10015
I/libpersona( 5502): KNOX_SDCARD not a persona
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,I/SELinux ( 5502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5502 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 5502): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1017): PackageReceiver onReceive()
D/RCPManagerService( 1017): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1017):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1017):  PackageReceiver onReceive() bundle null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 1017): Removing schedule queue dupe of com.test.thalitest
,D/LocationManagerService( 1017): getProviders()=[passive]
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1017): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,I/GCoreNlp( 1872): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TimaKeyStoreProvider( 5502): TimaSignature is unavailable
,V/BackupManagerService( 1017): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityThread( 5502): Added TimaKeyStore provider
V/BackupManagerService( 1017): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@9efaf1d
,V/AlarmManagerEXT( 1017): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1017): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/ActivityManager( 1017): Killing 4850:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
I/Babel   ( 5290): Creating RTCS
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5527): MountEmulatedStorage()
E/Zygote  ( 5527): v2
I/libpersona( 5527): KNOX_SDCARD checking this for 10032
I/libpersona( 5527): KNOX_SDCARD not a persona
,I/SELinux ( 5527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5527 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1017): no available spell checker services found
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5527): TimaSignature is unavailable
,D/ActivityThread( 5527): Added TimaKeyStore provider
,I/Babel   ( 5290): Destroying RTCS
,I/ActivityManager( 1017): Killing 4881:com.wsomacp/u0a25 (adj 15): empty #31
,I/FeatureConfig( 5527): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1017): Killing 4907:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 5013): PackagesMonitor onReceive :com.google.android.gms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/CrashAnrDetector( 1017): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_4792/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_4815/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1017): applying state to connected service
D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/LocationProviderProxy( 1017): applying state to connected service
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 5527): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_4850/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_4881/cgroup.procs: No such file or directory
,W/ResourcesManager( 5527): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_4907/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 5482): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 5548): MountEmulatedStorage()
I/libpersona( 5548): KNOX_SDCARD checking this for 10069
E/Zygote  ( 5548): v2
I/libpersona( 5548): KNOX_SDCARD not a persona
I/SELinux ( 5548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 5527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/SELinux ( 5548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux ( 5548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5548 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/LocationProviderProxy( 1017): applying state to connected service,
,I/GCoreNlp( 1872): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TimaKeyStoreProvider( 5548): TimaSignature is unavailable
,D/ActivityThread( 5548): Added TimaKeyStore provider
,I/art     (  318): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 31.848ms
,W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 16.916ms
,W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.805ms
,D/FileShare-Server( 5548): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5527): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5564): MountEmulatedStorage()
E/Zygote  ( 5564): v2
I/libpersona( 5564): KNOX_SDCARD checking this for 1000
I/libpersona( 5564): KNOX_SDCARD not a persona
,I/SELinux ( 5564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/SELinux ( 5564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5564 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 5564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5527): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5482): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,W/ResourcesManager( 5527): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 4925:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5564): TimaSignature is unavailable
,D/ActivityThread( 5564): Added TimaKeyStore provider
,W/ResourcesManager( 5527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5564): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5527): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5527): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5580): MountEmulatedStorage()
,E/Zygote  ( 5580): v2
I/libpersona( 5580): KNOX_SDCARD checking this for 1000,
,I/libpersona( 5580): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5580 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 5580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Killing 4744:com.android.mms/u0a46 (adj 15): empty #31
,I/SELinux ( 5580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5580): TimaSignature is unavailable
,D/ActivityThread( 5580): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5580): dbMigrationFlag : false
,D/ShortcutReceiver( 5580):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5596): MountEmulatedStorage()
,E/Zygote  ( 5596): v2
,I/libpersona( 5596): KNOX_SDCARD checking this for 10120
I/libpersona( 5596): KNOX_SDCARD not a persona
,I/SELinux ( 5596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5596 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 5063:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,E/SELinux ( 5596): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/CountryDetector( 1017): No listener is left
,W/libprocessgroup( 1017): failed to open /acct/uid_10107/pid_4925/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5596): TimaSignature is unavailable
,D/ActivityThread( 5596): Added TimaKeyStore provider
,W/ResourcesManager( 5596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_4744/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10153/pid_5063/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 5617): MountEmulatedStorage()
,E/Zygote  ( 5617): v2
I/libpersona( 5617): KNOX_SDCARD checking this for 10028
I/libpersona( 5617): KNOX_SDCARD not a persona
,I/SELinux ( 5617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5617 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5617): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5167): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 5617): TimaSignature is unavailable
,D/ActivityThread( 5617): Added TimaKeyStore provider
,D/Finsky  ( 5617): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5617): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5617): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5617): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5617): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5617): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager( 1017): Killing 5084:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/Ads     ( 5617): Skipping gmscore version check
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5617): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2036): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5617): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 2036): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1439): This pkg do not need BT addr. Do nothing
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/splitIntent( 1017): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1017): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5464): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5464): parseToken()
,W/System.err( 5464): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 5464): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 5464): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5464): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5464): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
,W/System.err( 5464): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
,W/System.err( 5464): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
,W/System.err( 5464): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5464): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5464): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5464): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5464): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5464): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5464): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5464): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5464): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5464): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5464): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5464): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5464): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5464): 	... 14 more
E/AASAservice-TokenRule( 5464): parseToken() : TokenFile is null
,I/PackagesMonitor( 5013): PackagesMonitor onReceive :com.test.thalitest
E/AASAservice-UpdateReceiver( 5464): AASARuleUpdateResult() : Rule file is not exist.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5663): MountEmulatedStorage()
,I/libpersona( 5663): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5663): v2
I/libpersona( 5663): KNOX_SDCARD not a persona
I/SELinux ( 5663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5663 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  289): DCD OFF
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5084/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5663): TimaSignature is unavailable
,D/ActivityThread( 5663): Added TimaKeyStore provider
,E/Zygote  ( 5678): MountEmulatedStorage()
,E/Zygote  ( 5678): v2
I/libpersona( 5678): KNOX_SDCARD checking this for 10046
I/libpersona( 5678): KNOX_SDCARD not a persona
,I/SELinux ( 5678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5678 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 5678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5678): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5678): TimaSignature is unavailable
,D/ActivityThread( 5678): Added TimaKeyStore provider
,W/ContextImpl( 5131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5663): (284) automatic index on shooting_modes(title_id)
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ResourcesManager( 5678): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5678): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5678): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5678): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5678): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5702): MountEmulatedStorage()
,E/Zygote  ( 5702): v2
I/libpersona( 5702): KNOX_SDCARD checking this for 1000
I/libpersona( 5702): KNOX_SDCARD not a persona
,I/SELinux ( 5702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5702 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Icing   ( 2036): Storage manager: low false usage 1.75MB avail 10.16GB capacity 11.68GB
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5719): MountEmulatedStorage()
I/libpersona( 5719): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5719): v2
I/libpersona( 5719): KNOX_SDCARD not a persona
I/SELinux ( 5719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{f74b60a u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5702): TimaSignature is unavailable
,D/ActivityThread( 5702): Added TimaKeyStore provider
,D/Mms/MmsApp( 5678): [start]    onCreate() consume time = 0.0
,E/Zygote  ( 5735): MountEmulatedStorage()
E/Zygote  ( 5735): v2
I/libpersona( 5735): KNOX_SDCARD checking this for 10156
I/libpersona( 5735): KNOX_SDCARD not a persona
,I/SELinux ( 5735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5735 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5719): TimaSignature is unavailable
,D/ActivityThread( 5719): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5735): TimaSignature is unavailable
,D/ActivityThread( 5735): Added TimaKeyStore provider
,W/ResourcesManager( 5702): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 5099:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5735): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5735): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/PCWCLIENTTRACE_LOG( 5719): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5719): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5719): new DMDBOpenHelper instance
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:Utils( 5735): Clear T&P info.
,E/Zygote  ( 5755): MountEmulatedStorage()
,E/Zygote  ( 5755): v2
I/libpersona( 5755): KNOX_SDCARD checking this for 10091
I/libpersona( 5755): KNOX_SDCARD not a persona
,I/SELinux ( 5755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5755): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5755 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5201:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5735): Widget is not attached.
,D/TimaKeyStoreProvider( 5755): TimaSignature is unavailable
,D/ActivityThread( 5755): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_PushUtil( 5719): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5719): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5719): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5719): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 5617): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/Zygote  ( 5770): MountEmulatedStorage()
E/Zygote  ( 5770): v2
I/libpersona( 5770): KNOX_SDCARD checking this for 1000
I/libpersona( 5770): KNOX_SDCARD not a persona
,I/SELinux ( 5770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 4051:com.sec.spp.push/u0a35 (adj 15): empty #31
,E/SELinux ( 5770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  318): Explicit concurrent mark sweep GC freed 8765(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.374ms total 22.793ms
W/libprocessgroup( 1017): failed to open /acct/uid_10122/pid_5099/cgroup.procs: No such file or directory
,W/art     ( 5678): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 141.045ms,
,D/TimaKeyStoreProvider( 5770): TimaSignature is unavailable
D/ActivityThread( 5770): Added TimaKeyStore provider
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.148ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.007ms
,E/Zygote  ( 5787): MountEmulatedStorage()
,E/Zygote  ( 5787): v2
I/libpersona( 5787): KNOX_SDCARD checking this for 10010
I/libpersona( 5787): KNOX_SDCARD not a persona,
I/SELinux ( 5787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5787 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 5787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5787): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Killing 5243:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31,
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Mms/TelephonyPermission( 5678): start operation mode monitor
,D/TimaKeyStoreProvider( 5787): TimaSignature is unavailable
D/ActivityThread( 5787): Added TimaKeyStore provider
,D/Mms/ArtClassLoader( 5678): init before art
,W/ResourcesManager( 5678): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 5678): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5678): isDefault true
,D/Mms/MmsApp( 5678): onCreate() com.android.mms
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4051/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10033/pid_5201/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5243/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/PackageBroadcastService( 2036): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2036): Loading module APK com.google.android.play.games
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 5678): [start]    initCountryIso consume time = 431.559479
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5770): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/DBG_POLICYDM( 5770): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/CountryDetector( 1017): The first listener is added
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5770): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/Mms/MmsApp( 5678): [end]    initCountryIso consume time = 8.654792
D/Mms/MmsConfig( 5678): [start]    MmsConfig.init() consume time = 0.12401
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5770): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsConfig( 5678): before partial update
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsConfig( 5678): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 5678): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5678): isAuth is false
,D/Mms/MmsConfig( 5678): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1453): query,matched:2117, calling pid = 5678
,D/TP/MmsSmsProvider( 1453): match 2117:Elapsed time : 1.331 ms
,D/EasySignUpManager_1.0.1( 5678): isAuth is false
D/EasySignUpManager_1.0.1( 5678): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5678): mps_code.dat does not exist
E/CscParser( 5678): customer_path =/system/csc/customer.xml
E/CscParser( 5678): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/CscParser( 5678): mps_code.dat does not exist
E/CscParser( 5678): customer_path =/system/csc/customer.xml
E/CscParser( 5678): fileName + /system/csc/customer.xml
,E/PhotosPlugin( 5755): Loading PhotosPlugin
,D/CscParser( 5678): getInstance fileName =/system/csc/customer.xml
,I/DBG_POLICYDM( 5770): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5770): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/Mms/MmsConfig( 5678):  enable multiwindow = true
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5770): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/Mms/MessageUtils( 5678): setCountryDetector : update country detector info 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Mms/MessageUtils( 5678): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5678): [end]    init() consume time = 122.690782
,D/Mms/Contact( 5678): [start]    init() consume time = 0.780572
,E/Zygote  ( 5819): MountEmulatedStorage()
E/Zygote  ( 5819): v2
,I/libpersona( 5819): KNOX_SDCARD checking this for 10035
,I/libpersona( 5819): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5819 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5819): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1453): query,matched:13, calling pid = 5678
,D/TP/MmsSmsProvider( 1453): match 13:Elapsed time : 2.038 ms
,D/Mms/Contact( 5678): [end]    init consume time = 26.929428
,I/DBG_POLICYDM( 5770): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/TimaKeyStoreProvider( 5819): TimaSignature is unavailable
,D/ActivityThread( 5819): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5770): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5770): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/Mms/DraftCache( 5678): [start]    rebuildCache consume time = 31.713333
,D/TP/MmsSmsProvider( 1453): query,matched:12, calling pid = 5678
,D/TP/MmsSmsProvider( 1453): match 12:Elapsed time : 1.282 ms
,D/Mms/MethodReflector( 5678): getSubId is called
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5678): getTelephonyProperty is called
,D/Mms/DownloadManager( 5678): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 5678): getSubId is called
,D/Mms/MethodReflector( 5678): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5678): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/DraftCache( 5678): [end]    rebuildCache consume time = 32.181927
D/Mms/MethodReflector( 5678): getTelephonyProperty is called
D/Mms/DownloadManager( 5678): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5678): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5678): mAutoDownload ------> true
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0,
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0,
,I/DBG_POLICYDM( 5770): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true,
I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5770): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/16/12:12:08
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/09/15:20:57
,I/DBG_POLICYDM( 5770): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5770): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5770): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5770): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5770): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5770): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,E/SPPClientService( 5819): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5819): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/Icing   ( 2036): updateResources: need to parse f{com.google.android.gms}
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5842): MountEmulatedStorage(),
D/SPPClientService( 5819): PushLog.txt file is not deleted.
D/SPPClientService( 5819): PushLog.txt file is not deleted.
D/SPPClientService( 5819): ============PushLog. stop!
E/Zygote  ( 5842): v2
,I/libpersona( 5842): KNOX_SDCARD checking this for 10038
I/libpersona( 5842): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5842 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a,
I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/ActivityManager( 1017): Killing 5270:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,I/SELinux ( 5842): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5842): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5842): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5842): TimaSignature is unavailable
D/ActivityThread( 5842): Added TimaKeyStore provider
I/DBG_POLICYDM( 5770): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5270/cgroup.procs: No such file or directory
,W/ResourcesManager( 5842): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5842): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ComposerPerformance( 5678): 1455027657722 ms / [DONE] Composer constructor
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/CII     ( 5678): CommonIMSInterface: VoLTE CSC feature disabled.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/ReservationManager( 5678): ReservationManager()
,I/Mms/ReservationManager( 5678): resetAfterConnected()
,D/TP/MmsSmsProvider( 1453): query,matched:7, calling pid = 5678
,D/TP/MmsSmsProvider( 1453): match 7:Elapsed time : 2.099 ms
,I/Mms/ReservationManager( 5678): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 5678): [start]    init() consume time = 214.412448
,D/Mms/MmsApp( 5678): [end]    onCreate() consume time = 1.164375
,D/TP/MmsSmsProvider( 1453): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1453): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1453): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1453): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1453): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
,D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2036): Module APK com.google.android.play.games already loaded
,D/Mms/Conversation( 5678): [end]    init consume time = 19.042239
,D/Mms/DownloadManager( 5678): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/MessagingNotification( 5678): [start]    init() consume time = 3.197396
D/Mms/DownloadManager( 5678): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 5678): getSubId is called
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5678): getTelephonyProperty is called
D/Mms/DownloadManager( 5678): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5678): mAutoDownload ------> true
,D/Mms/MessagingNotification( 5678): [end]    init consume time = 6.173646
D/Mms/SpamFilter( 5678): [start]    SpamFilter fill() begin consume time = 4.612656
,D/TP/MmsSmsProvider( 1453): query,matched:0, calling pid = 5678
,V/TP/MmsSmsProvider( 1453): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1453): match 0:Elapsed time : 2.197 ms
,D/Mms/Synchronizer( 5678): [start]    doSync consume time = 14.650834
,D/TP/MmsSmsProvider( 1453): query,matched:400, calling pid = 5678
,D/Mms/SpamFilter( 5678): [end]    SpamFilter fill() finished consume time = 6.012968
,D/TP/MmsSmsProvider( 1453): update, matched:300, calling pid = 5678
,V/TP/MmsSmsProvider( 1453): syncDBData start
V/TP/MmsSmsProvider( 1453): syncDBData sms end
V/TP/MmsSmsProvider( 1453): syncDBData mms end
V/TP/MmsSmsProvider( 1453): syncDBData end
,D/Mms/Synchronizer( 5678): [end]    doSync consume time = 6.243334,
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5863): MountEmulatedStorage()
,I/libpersona( 5863): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5863): v2
I/libpersona( 5863): KNOX_SDCARD not a persona
I/SELinux ( 5863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5863 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/ArtClassLoader( 5678): init [DONE] art
,I/SELinux ( 5863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5863): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/FreeMessageStatusReceiver( 5678): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 206091(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.916ms total 196.815ms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5878): MountEmulatedStorage()
,E/Zygote  ( 5878): v2
I/libpersona( 5878): KNOX_SDCARD checking this for 10047
I/libpersona( 5878): KNOX_SDCARD not a persona
,I/SELinux ( 5878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5878 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 5878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5878): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5863): TimaSignature is unavailable
D/ActivityThread( 5863): Added TimaKeyStore provider
D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/DBG_POLICYDM( 5770): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/TimaKeyStoreProvider( 5878): TimaSignature is unavailable
,D/ActivityThread( 5878): Added TimaKeyStore provider
,W/ResourcesManager( 5878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/FreeMessageReceiverService( 5678): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5678): onHandleIntent: ACTION_PACKAGE_ADDED
,D/BadgeProvider( 5863): onCreate
,D/BadgeProvider( 5863): DatabaseHelper
I/ActivityManager( 1017): Killing 5331:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5315:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,D/Mms/MessagingNotification( 5678): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1453): query,matched:26, calling pid = 5678
,D/TP/SmsProvider( 1453): match 26:Elapsed time : 1.194 ms
,D/TP/MmsSmsProvider( 1453): query,matched:6, calling pid = 5678
,D/TP/MmsSmsProvider( 1453): match 6:Elapsed time : 1.088 ms
,D/AsyncTaskServiceImpl( 2036): Submit a task: k
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5368:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2036): Processing package: com.test.thalitest
,E/Zygote  ( 5899): MountEmulatedStorage()
,E/Zygote  ( 5899): v2
I/libpersona( 5899): KNOX_SDCARD checking this for 10025
I/libpersona( 5899): KNOX_SDCARD not a persona
I/SELinux ( 5899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5899 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5899): TimaSignature is unavailable
,D/ActivityThread( 5899): Added TimaKeyStore provider
,W/ResourcesManager( 5899): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 5146:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5331/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5315/cgroup.procs: No such file or directory
,D/MyFiles ( 5878): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/GassUtils( 2036): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2036): Found info for package com.test.thalitest in db.
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5368/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_5146/cgroup.procs: No such file or directory
,I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
,I/TactileAssist( 1017): List of disabled apps :
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,I/OMACP   ( 5899): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.,
W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,D/Mms/Omacp( 5678): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/Zygote  ( 5923): MountEmulatedStorage()
E/Zygote  ( 5923): v2
I/libpersona( 5923): KNOX_SDCARD checking this for 10053
I/libpersona( 5923): KNOX_SDCARD not a persona
,I/SELinux ( 5923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5923): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5923 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5923): TimaSignature is unavailable
,D/ActivityThread( 5923): Added TimaKeyStore provider
,W/ResourcesManager( 5923): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,D/Compatibility( 5923): onReceive() it will make start service
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,V/AlarmManager( 1017): waitForAlarm result :4
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/UpdateIcingCorporaServi( 5482): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,D/Compatibility( 5923): onHandleIntent()
,D/Compatibility( 5923): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,D/Compatibility( 5923): found: 2
,I/OMACP   ( 5899): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/DBG_POLICYDM( 5770): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/Compatibility( 5923): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5923): skipping ResolveInfo{395b45f6 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5923): considering ResolveInfo{d71edf7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5923): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5923): enabling receiver ResolveInfo{340dc464 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/BaseAppContext( 2036): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2036): cleanUpNonGplusAccounts done.
,I/SL_DEBUG( 5842): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5842): isLoggable:: SL_DEBUG_EXIST = false
,D/Compatibility( 5923): enabling receiver ResolveInfo{250b46cd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/DBG_POLICYDM( 5770): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/Compatibility( 5923): enabling receiver ResolveInfo{4edcb82 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5923): enabling receiver ResolveInfo{35cd7293 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/Compatibility( 5923): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5842): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,I/Icing   ( 2036): Internal init done: storage state 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5842): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 3604(143KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 6.353ms total 52.617ms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5951): MountEmulatedStorage(),
I/libpersona( 5951): KNOX_SDCARD checking this for 10041
E/Zygote  ( 5951): v2
I/libpersona( 5951): KNOX_SDCARD not a persona
I/SELinux ( 5951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5951 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5951): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/Icing   ( 2036): Post-init done
,D/TimaKeyStoreProvider( 5951): TimaSignature is unavailable
,D/ActivityThread( 5951): Added TimaKeyStore provider
,I/Icing   ( 2036): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 5951): [SSP] onCreated
,I/ActivityManager( 1017): Killing 4995:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SA      ( 5951): [TPM] There is no property file
,I/SA      ( 5951): [SCU] isHaveSA() - false
,I/SA      ( 5951): [TPM] getModelProperty : null
I/SA      ( 5951): [TPM] getCSCProperty : null
,I/SA      ( 5951): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5951): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5951): [DM] TFT FEATURE: false
,I/SA      ( 5951): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5951): [DM] init START
,I/SA      ( 5951): [DM] This device is not a Vodafone
,W/ResourceType( 5951): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5951): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5951): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5951): [SCU] isHaveSA() - false
I/SA      ( 5951): support phone number id : false
I/SA      ( 5951): [DM] Supports Ref Jpn : true
,I/SA      ( 5951): [DM] init END
,I/SA      ( 5951): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5951): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1017): Killing 4495:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/CheckinService( 2036): Done disabling old GoogleServicesFramework version
,W/GAV2    ( 5755): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5482): UpdateCorporaTask done [took 617 ms] updated apps [took 617 ms] 
,I/ActivityManager( 1017): Killing 5167:com.google.android.gm/u0a101 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_4995/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10111/pid_4495/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_5167/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5983): MountEmulatedStorage(),
I/libpersona( 5983): KNOX_SDCARD checking this for 10100
E/Zygote  ( 5983): v2
I/libpersona( 5983): KNOX_SDCARD not a persona
I/SELinux ( 5983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5983 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Killing 4832:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
E/SELinux ( 5983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5755): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5983): TimaSignature is unavailable
,D/ActivityThread( 5983): Added TimaKeyStore provider
,D/PackageIntentReceiver( 5983): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5983): Not GearManger package! 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6005): MountEmulatedStorage()
E/Zygote  ( 6005): v2
I/libpersona( 6005): KNOX_SDCARD checking this for 1000
I/libpersona( 6005): KNOX_SDCARD not a persona
,I/SELinux ( 6005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6005 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 2036): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2036): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 6005): TimaSignature is unavailable
,D/ActivityThread( 6005): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5755): Write apps_features disabled false
,W/libprocessgroup( 1017): failed to open /acct/uid_10134/pid_4832/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6024): MountEmulatedStorage(),
E/Zygote  ( 6024): v2
I/libpersona( 6024): KNOX_SDCARD checking this for 1000,
I/libpersona( 6024): KNOX_SDCARD not a persona
,I/SELinux ( 6024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5346:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 6024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6024): TimaSignature is unavailable
,D/ActivityThread( 6024): Added TimaKeyStore provider
,I/art     (  318): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 25.659ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 16.852ms
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_5346/cgroup.procs: No such file or directory
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 771us total 17.809ms
,D/AcmsPackageEventListener( 6024): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6024): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/FaceInterface( 5013): startFaceScan() : going on
D/FaceInterface( 5013): startFaceScan() is called.
D/AcmsService( 6024): Enter Oncreate
,D/AcmsServiceMonitor( 6024): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6024): creating AcmsCore
,D/AcmsCore( 6024): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6024): AcmsCore
,D/AcmsCore( 6024): init
D/AcmsCore( 6024): Looper handler is not null
D/AcmsCore( 6024): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6024): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6024): Incrementing - Counter value: 1
D/AcmsCore( 6024): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6024): onStartCommand
D/AcmsService( 6024): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6024): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6024): Incrementing - Counter value: 2
D/AcmsService( 6024): Incremented Counter Value : onStartCommand
,D/ContentApp( 1225): startScan() is called.
,D/ContentApp( 1225): startScan() is end.
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/AcmsCertificateMngr( 6024): AcmsCertificateMngr
,D/ActivityThread( 6024): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1225): isNeedToRestore : start
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsRevocationMngr( 6024): AcmsRevocationMngr
,D/AcmsService( 6024): Inside handle Intent
,D/AcmsService( 6024): App added - package name: com.test.thalitest
,D/AcmsCore( 6024): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6024): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6024): Incrementing - Counter value: 3
D/AcmsCore( 6024): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 6024): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6024): Decrementing - Counter value: 2
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/GAV2    ( 5755): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1017): Killing 5290:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_5290/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1017): SIOP:: AP = 390,
,E/SMD     (  289): DCD OFF,
,I/Mms/MmsApp( 5678):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5678): [start]    fillCache consume time = 1941.901614
,D/Mms/ComposeMessageFragment( 5678): fillCache, easy = false
,D/AbsListView( 5678): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5678): [end]    fillCache consume time = 72.32776
,D/SensorService( 1017): [SO] 0.019 0.096 10.132
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 2036): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Mms/BubbleViewCache( 5678): fillCache bubble = 1
,V/AlarmManager( 1017): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/accuweather( 1723): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/Icing   ( 2036): Loaded CLD2 Version V2.0 - 20141016
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1723): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 21
,I/Icing   ( 2036): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 2036): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Icing   ( 2036): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5548:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_5548/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 6024):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6024): Key Store exist
,I/AcmsKeyStoreHelper( 6024): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6024):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6024): getKeyStoreForApplication success 
D/AcmsCore( 6024): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 6024): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6024): Decrementing - Counter value: 1
D/AcmsCore( 6024): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6024): This is NOT a valid MirrorLink app
,D/AcmsCore( 6024): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6024): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6024): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6024): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6024): getSvcCounter - Counter value: 0
,D/AcmsService( 6024): Enter onDestroy
I/AcmsService( 6024): cleanUp(): inside service clean up
,D/AcmsCore( 6024): AcmsCore: inside DeInit
D/AcmsCore( 6024): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 6024): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6024): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6024): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 6024): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6024): getSvcCounter - Counter value: 0
,D/AcmsService( 6024): killing acms process
,I/Process ( 6024): Sending signal. PID: 6024 SIG: 9
,I/ActivityManager( 1017): Process ACMS.Process (pid 6024)(adj 0) has died(67,1188)
,I/DBG_POLICYDM( 5770): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5770): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/SQLiteConnectionPool( 2036): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 4760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6052 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 6052): MountEmulatedStorage()
E/Zygote  ( 6052): v2
I/libpersona( 6052): KNOX_SDCARD checking this for 10104
I/libpersona( 6052): KNOX_SDCARD not a persona
,I/SELinux ( 6052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6052): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/iu.UploadsManager( 2036): End new media; added: 0, uploading: 0, time: 84 ms
,D/TimaKeyStoreProvider( 6052): TimaSignature is unavailable
,D/ActivityThread( 6052): Added TimaKeyStore provider
,W/ResourcesManager( 6052): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 6052): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6052): MmsConfig.loadMmsSettings
,I/Babel   ( 6052): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6052): MmsConfig.loadFromDatabase
,E/Babel   ( 6052): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6052): MmsConfig.loadFromResources
,E/Babel   ( 6052): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6052): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6052): App launched.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,W/VideoCapabilities( 6052): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6052): Unsupported mime audio/evrc
,W/AudioCapabilities( 6052): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6052): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6052): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6052): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6052): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6052): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6052): Unsupported mime audio/evrc
,W/VideoCapabilities( 6052): Unsupported mime video/wvc1
,W/VideoCapabilities( 6052): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6052): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6052): Unsupported mime video/wvc1
,W/VideoCapabilities( 6052): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6052): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6052): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6052): Unsupported mime video/mp43
,W/VideoCapabilities( 6052): Unsupported mime video/sorenson
,W/VideoCapabilities( 6052): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6052): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6052): Creating RTCS
,I/Babel   ( 6052): Destroying RTCS
,I/ActivityManager( 1017): Killing 5580:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5580/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5617): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1872): Explicit concurrent mark sweep GC freed 33829(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 12MB/20MB, paused 1.347ms total 79.532ms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 31761(1766KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.416ms total 140.267ms
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5617): Thread-967(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5617): Thread-967(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5617): Thread-967(ApacheHTTPLog):isShipBuild true
,I/System.out( 5617): Thread-967(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5617): Thread-967(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5617): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5617, getuid(): 10028
,I/qtaguid ( 5617): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5617, getuid(): 10028
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5617): Untagging socket 44
,I/System.out( 5617): Thread-967 calls detatch()
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5617): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5617): Thread-968(ApacheHTTPLog):isShipBuild true
,I/System.out( 5617): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5617): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5617): Untagging socket 44
,I/qtaguid ( 5617): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5617): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5617): untagSocket(44) failed with errno -22
I/System.out( 5617): Thread-968 calls detatch()
,D/Finsky  ( 5617): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6087 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/Zygote  ( 6087): MountEmulatedStorage()
,E/Zygote  ( 6087): v2
I/libpersona( 6087): KNOX_SDCARD checking this for 10012
I/libpersona( 6087): KNOX_SDCARD not a persona
,I/SELinux ( 6087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6087): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6087): TimaSignature is unavailable
,D/ActivityThread( 6087): Added TimaKeyStore provider
,I/System.out( 5617): Thread-967(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5617): Thread-967(ApacheHTTPLog):isShipBuild true
I/System.out( 5617): Thread-967(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5617): Thread-967(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6087): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6087): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6087): VM with version 2.1.0 has multidex support
I/MultiDex( 6087): install
I/MultiDex( 6087): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6087): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5617): Untagging socket 44
,I/qtaguid ( 5617): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5617): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5617): untagSocket(44) failed with errno -22
I/System.out( 5617): Thread-967 calls detatch()
,W/ActivityThread( 6087): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6087): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fe8a08c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6087): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6087): Reading stored module config
,D/WearableService( 1872): callingUid 10012, callindPid: 1872
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1872): [251] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2036): Restart initialization of location
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1872): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 6087): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1872): No location to return for getLastLocation()
,W/FusedLocationProvider( 1872): location=null
,D/NativeLibraryUtils( 6087): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6087): Connecting to CarCallService...
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6087): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6087): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6087): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6087): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6087): Creating a new PhoneAdapter instance
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6087): setListener: com.google.android.gms.car.dn@2491d0cb
D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
D/CAR.TEL.PhoneAdapter( 6087): Returning an existing PhoneAdapter instance.
W/ActivityManager( 1017): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.Service( 6087): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6087): Package validated; name: com.android.vending
,V/Finsky  ( 5617): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2482e919 u0 com.samsung.android.MtpApplication/.MtpService}
,E/SMD     (  289): DCD OFF
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5617): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5617): Thread-968(ApacheHTTPLog):isShipBuild true
,I/System.out( 5617): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5617): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5617): Untagging socket 44
,I/qtaguid ( 5617): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5617): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5617): untagSocket(44) failed with errno -22
I/System.out( 5617): Thread-968 calls detatch()
,W/ResourcesManager( 5617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5617): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5617): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms,
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1872): client connected with version: 8296000
,D/Finsky  ( 5617): [989] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5617): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5617): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5617): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5617): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5617): (HTTPLog)-Static: isShipBuild true
I/System.out( 5617): (HTTPLog)-Thread-978-320267934: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5617): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5617): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1017): Killing 5013:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5464:com.samsung.aasaservice/1000 (adj 15): empty #32
,D/SSRM:n  ( 1017): SIOP:: AP = 350,
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_5013/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5464/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 1017): [SO] 0.019 0.077 10.056
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{72fb1c6 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/PowerManagerService( 1017): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1017): lcd : 1 +
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1017): lcd : 1 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAR.SERVICE( 6087): mConnectedToCar = false, abort
,E/ActivityThread( 6087): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15016a53 that was originally bound here,
,E/ActivityThread( 6087): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15016a53 that was originally bound here,
E/ActivityThread( 6087): 	,at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6087): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6087): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6087): 	,at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6087): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6087): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6087): 	,at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6087): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6087): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6087): 	,at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6087): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6087): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6087): 	,at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6087): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280),
,E/ActivityThread( 6087): ,	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6087): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6087): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6087): 	a,t android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6087): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6087): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6087): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6087): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6087): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@215c5f9a that was originally bound here
E/ActivityThread( 6087): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@215c5f9a that was originally bound here
E/ActivityThread( 6087): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6087): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6087): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6087): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6087): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6087): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6087): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6087): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6087): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6087): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6087): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6087): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6087): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6087): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6087): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6087): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6087): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6087): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6087): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6087): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6087): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@15e1d48a
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/Watchdog( 1017): !@Sync 2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2036): getNumBytesRead when not calculated.
,D/PowerManagerService( 1017): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1017): Nap time (uid 1000)...
D/PowerManagerService( 1017): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1017): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1017): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1017): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1017): WindowOrientationListener disabled
D/PowerManagerService( 1017): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1017): handleSandman : startDream(true)
E/PowerManagerService( 1017): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1017): Sleeping (uid 1000)...
D/PowerManagerService( 1017): [s] UserActivityState : 4 -> 0
,D/SensorService( 1017): [SO] activate (ident=0xb86d3b28, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1017): unregisterListener ::   
,D/KeyguardViewMediator( 1179): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1179): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1179): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1179): notifyScreenOffLocked
,D/PowerManagerService( 1017): Excessive delay in ColorFade : createSurface: 18ms
I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Adreno-EGL( 1017): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1017): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1017): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1017): Local Branch: 
I/Adreno-EGL( 1017): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1017): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1017):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1179): timeout : 5000
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1017): fail to set sysfs 1
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,V/ActivityThread( 3058): updateVisibility : ActivityRecord{d0cc627 token=android.os.BinderProxy@3ddbe34a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1179): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1179): handleNotifyScreenOff
,D/VolumePanel( 1179): onScreenTurnedOff()
,D/VolumePanel( 1179): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1179): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1179): onScreenTurnedOff
,D/PowerManagerService( 1017): Excessive delay in ColorFade : createEglContext: 78ms
,D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (195 us)
,D/InputMethodManagerService( 1017): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1017):  handler : SCREEN_ON end
,D/NotificationService( 1017): ACTION_SCREEN_ON
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 1017): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 31ms
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
,V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
,E/WifiNative-wlan0( 1017): do suspend false
,I/wpa_supplicant( 2069): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2069): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2069): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2069): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1017): Bridge Server is not available
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1017): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1723): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/PowerManagerService( 1017): Excessive delay in ColorFade : initGLShaders: 40ms
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
D/PowerManagerService( 1017): Excessive delay in ColorFade prepare: 184ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/DisplayPowerController( 1017): ColorFade: onAnimationStart
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,I/SamsungIME( 1782): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1017): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,E/lights  ( 1017): write_int failed to open -1,
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1017): turn on LED for fully charged
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1017): fail to set sysfs 0
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,D/SamsungIME( 1782): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1017):  handler : SCREEN_OFF end 
,D/NotificationService( 1017): ACTION_SCREEN_OFF
,D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1314): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,I/BackgroundCompactionService( 1017): Schedule Type1 BGCompaction
D/comsamsunglog( 1314): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455049200000
D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455027678498
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1314): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1017): Bridge Server is not available
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1017): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_OFF called
E/daemonapp( 1314): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1416): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1439): call the applyRouting
,I/BatteryStatsDumper( 1017): In refreshStats isReason Screen ON/OFF: true
,D/accuweather( 1723): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1723): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DisplayPowerState( 1017): !@ ColorFade entry
,D/DisplayPowerController( 1017): ColorFade: onAnimationEnd
,I/BatteryStatsDumper( 1017): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1017): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1017): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1017): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1017): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1017): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1017): lcd : 0 +
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1723): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1723): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1723): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1723): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/lights  ( 1017): lcd : 0 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1017): Got set_interactive hint
,D/DisplayManagerService( 1017): !@display_state: ON -> OFF
,I/DisplayManagerService( 1017): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb8adf690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager( 1017): Display changed displayId=0
,E/LibSecureUISvc( 1922): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1723): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1723): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1723): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1017): Excessive delay in setPowerMode(): 259ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
D/PowerManagerService( 1017): Excessive delay in !@display_state: OFF: 261ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/libsuspend( 1017): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1017): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1017): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 269ms
I/PowerManagerService( 1017): [PWL] Off : 0s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1017, ws=null) (elapsedTime=367)
,I/BatteryStatsDumper( 1017): Writing to database completed
,E/WifiNative-wlan0( 1017): do suspend true
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 2069): nl80211: Received scan results (2 BSSes),
,D/WifiP2pService( 1017): InactiveState{ what=147461 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1017): DefaultState{ what=147461 }
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1,
,D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off,
V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
E/SMD     (  289): DCD OFF
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 5617): [980] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5617): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService( 1017): [PWL] Off : 5s ago
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,D/SSRM:n  ( 1017): SIOP:: AP = 300,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1017): [PWL] Off : 15s ago
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 3,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1017): onStart. jobID=801
,I/BackgroundCompactionService( 1017): onStart done. jobID=801
,I/BackgroundCompactionService( 1017): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1017): compact_memory command done
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/PowerManagerService( 1017): [PWL] Off : 30s ago,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1872): Vacuum at: now=1455027712254 tag=VacuumService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1872): Scheduling Phenotype for one-off execution 11242 seconds from now (1455027712685)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1872): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1872): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1872): Using platform SSLCertificateSocketFactory
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1872): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1872): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1872): (HTTPLog)-Static: isShipBuild true
I/System.out( 1872): (HTTPLog)-Thread-257-269975574: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1872): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1872): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1872): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1872, getuid(): 10012
,I/qtaguid ( 1872): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1872, getuid(): 10012
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1872): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1872): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1872, getuid(): 10012
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1872): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1872): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1872, getuid(): 10012
,D/LocationManagerService( 1017): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1872): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1872): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1872, getuid(): 10012
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,D/FactoryTest( 5386): Not factory mode
,D/FactoryTest( 5386): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5386): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5386): still no open session command from host, so toast
,W/ContextImpl( 5386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
I/Timeline( 5386): Timeline: Activity_launch_request id:com.android.settings time:116117
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire(),
,V/ActivityManager( 1017): Display changed displayId=0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 3058
,E/MTPRx   ( 5386): started activity for popup
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5386): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5386): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5386): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 3058
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@23c6979a attribute=android.view.inputmethod.EditorInfo@18dba8cb, token = android.os.BinderProxy@1b94ca36
,D/SamsungIME( 1782): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,D/SettingsReceiverActivity( 5386): dev.kiessupport is : TRUE
,D/PhoneWindow( 5386): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5386): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 31
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 31
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0,
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3058): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3058): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3058): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3058): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3058): Timeline: Activity_idle id: android.os.BinderProxy@3ddbe34a time:116370
,V/ActivityThread( 3058): updateVisibility : ActivityRecord{d0cc627 token=android.os.BinderProxy@3ddbe34a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/ActivityManager( 1017): mDVFSHelper.release(),
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=7_task.xml,
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 290,
,I/PowerManagerService( 1017): [PWL] Off : 50s ago,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1017): !@Sync 4,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 75s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 5,
,E/SMD     (  289): DCD OFF,
,I/ClearcutLoggerApiImpl( 1872): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 105s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1017): !@Sync 6,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4,
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/Watchdog( 1017): !@Sync 7,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1017): !@Sync 8,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1017): !@Sync 9,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 225s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
I/TLC_TIMA_PKM_initialize( 1017): initializing...
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1017): !@Sync 10
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 11
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 275s ago,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1017): !@Sync 12
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 13
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1017): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=422327 batch.start=798223
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 14,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 15,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 390s ago,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,V/AlarmManager( 1017): waitForAlarm result :8,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/bootchecker(  329): bootchecker wake up!!
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 16,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,I/ServiceManager(  334): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 17,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  334): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  334): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 455s ago,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  334): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  334): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/Atfwd_Daemon(  334): Stop the daemon....,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 19
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 525s ago,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 20
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 21,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 22,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1017): [PWL] Off : 600s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 23,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 24,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1017): [PWL] Off : 680s ago
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 25,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/Watchdog( 1017): !@Sync 26,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 27,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 765s ago
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1017): stay LED for fully charged
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 28,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 29,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 30
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 855s ago,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 31
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 32
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 33
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 950s ago,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 34
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 35,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 36,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,E/SMD     (  289): DCD OFF
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 37,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 1050s ago,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 38,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 39,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/BatteryService( 1017): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1017): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1017): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1017): Updating Usage Statistics in DB @ 1455028813865
,I/ApplicationPolicy( 1017): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1017): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1017): ::isTableExists: Table exists 
,I/ApplicationUsage( 1017): Done Updating Usage Statistics in DB @ 1455028814177
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1017): !@Sync 40
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 1155s ago,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1017): !@Sync 41,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2593): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2593): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6640): 
D/AndroidRuntime( 6640): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6640): CheckJNI is OFF
D/AndroidRuntime( 6640): readGMSProperty: start
D/AndroidRuntime( 6640): readGMSProperty: already setted!!
D/AndroidRuntime( 6640): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6640): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6640): readGMSProperty: end
D/AndroidRuntime( 6640): addProductProperty: start
D/SSRM:n  ( 1017): SIOP:: AP = 260
E/AffinityControl( 6640): AffinityControl: registerfunction enter
D/AndroidRuntime( 6640): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{939969772}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1017): !@killApplicatoin: 10155, uninstall pkg
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4978): Explicit concurrent mark sweep GC freed 2304(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 691us total 20.937ms
I/art     ( 5482): Explicit concurrent mark sweep GC freed 670(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 781us total 34.026ms
I/art     ( 4760): Explicit concurrent mark sweep GC freed 15317(823KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 678us total 49.488ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1872): Ignoring removeGeofence because network location is disabled.
I/art     ( 2036): Explicit concurrent mark sweep GC freed 3220(193KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/18MB, paused 1.278ms total 68.147ms
E/SamsungIME( 1782): mOCRHelper is null
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3526): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:41:03 GMT+01:00 2016
D/ActivityManager( 1017): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3526): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1017): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1017): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6654): MountEmulatedStorage()
I/libpersona( 6654): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6654): v2
I/libpersona( 6654): KNOX_SDCARD not a persona
E/SMD     (  289): DCD OFF
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6654 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): onCreate()
I/SELinux ( 6654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
I/SELinux ( 6654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 6654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3526): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 6662): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6662 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/Zygote  ( 6662): v2
I/libpersona( 6662): KNOX_SDCARD checking this for 10044
I/libpersona( 6662): KNOX_SDCARD not a persona
I/SELinux ( 6662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
I/SELinux ( 6662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3526): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 6654): TimaSignature is unavailable
D/ActivityThread( 6654): Added TimaKeyStore provider
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/Zygote  ( 6679): MountEmulatedStorage()
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  ( 6679): v2
I/libpersona( 6679): KNOX_SDCARD checking this for 10149
I/libpersona( 6679): KNOX_SDCARD not a persona
I/SELinux ( 6679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6679 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6662): TimaSignature is unavailable
D/ActivityThread( 6662): Added TimaKeyStore provider
D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
D/PersonaManager( 1439): isKioskContainerExistOnDevice
E/SQLiteLog( 4760): (284) automatic index on crash_info_summary(package_name_touched)
D/RegisteredServicesCache( 1439): empty dynamic service
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
D/TimaKeyStoreProvider( 6679): TimaSignature is unavailable
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ActivityThread( 6679): Added TimaKeyStore provider
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1017): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
W/ResourcesManager( 6662): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 4760): Explicit concurrent mark sweep GC freed 1124(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 771us total 39.085ms
W/ResourcesManager( 6662): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/elm:15183( 6654): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6654): ELMEngine.ELMEngine( context ).
D/elm:15183( 6654): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1017): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
D/BadgeProvider( 5863): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5863): sendNotify, [notify] : null
D/BadgeProvider( 5863): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5863): update, [BadgeCount] : badgecount=0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/BadgeProvider( 5863): update, [UpdateCount] : 1
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6654): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6654): ElmAgentService : onCreate()
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15183( 6654): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6654): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6654): MDMBridge.getInstance()
D/elm:15183( 6654): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6654): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6701): MountEmulatedStorage()
E/Zygote  ( 6701): v2
I/libpersona( 6701): KNOX_SDCARD checking this for 1000
I/libpersona( 6701): KNOX_SDCARD not a persona
I/SELinux ( 6701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6701 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 6654): ElmAgentService : onDestroy().
D/ThemeInfoUtil( 6679): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6679): isCurrentFestival = false
W/ContextImpl( 5131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
I/KLMS-2.5.183: ( 3526): KLMSIntentService(): onDestroy()
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/TimaKeyStoreProvider( 6701): TimaSignature is unavailable
D/ActivityThread( 6701): Added TimaKeyStore provider
I/TapandpayWidget:TapandpayAppWidgetProvider( 5735): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5735): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5735): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5735): Widget is not attached.
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/RCPManager( 5564):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1017):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1017): queryAllProviders():  providerCallBack is not register for 0
E/Zygote  ( 6719): MountEmulatedStorage()
E/Zygote  ( 6719): v2
I/libpersona( 6719): KNOX_SDCARD checking this for 10160
I/libpersona( 6719): KNOX_SDCARD not a persona
I/SELinux ( 6719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6719 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
D/AASAservice-UpdateReceiver( 6701): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6701): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/SELinux ( 6719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/System.err( 6701): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6701): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6701): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6701): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6701): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6701): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6701): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6701): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6701): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6701): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6701): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1017): Killing 5502:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/PCWCLIENTTRACE_PushUtil( 5719): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5719): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5719): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5719): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6719): TimaSignature is unavailable
D/ActivityThread( 6719): Added TimaKeyStore provider
E/Zygote  ( 6736): MountEmulatedStorage()
I/libpersona( 6736): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6736): v2
I/libpersona( 6736): KNOX_SDCARD not a persona
I/SELinux ( 6736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5702:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
E/SELinux ( 6736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/TimaKeyStoreProvider( 6736): TimaSignature is unavailable
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 6736): Added TimaKeyStore provider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5527): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6719): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6751 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6751): MountEmulatedStorage()
E/Zygote  ( 6751): v2
I/libpersona( 6751): KNOX_SDCARD checking this for 10035
I/libpersona( 6751): KNOX_SDCARD not a persona
I/SELinux ( 6751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6751): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5770:com.policydm/1000 (adj 15): empty #31
W/ResourcesManager( 5527): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/[0]UMC:UMCContentProvider( 6719): @onCreate
D/TimaKeyStoreProvider( 6751): TimaSignature is unavailable
D/ActivityThread( 6751): Added TimaKeyStore provider
D/[0]UMC:Core( 6719): onCreate(): 
D/[0]UMC:Core( 6719): @isManagedProfileUser
D/[0]UMC:Core( 6719): userId: 0
D/[0]UMC:Core( 6719): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6719): userInfo.isManagedProfile() : false
W/ContextImpl( 6736): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
I/art     ( 1017): Explicit concurrent mark sweep GC freed 63430(6MB) AllocSpace objects, 258(4MB) LOS objects, 33% free, 28MB/42MB, paused 3.263ms total 537.649ms
D/ActivityManager( 1017): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/NearbySource( 6662): Nearby Source Create!
D/NearbyContext( 6662): Nearby Context Create!
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/[0]UMC:DeviceInfo( 6719): USA==US==
E/Zygote  ( 6767): MountEmulatedStorage()
E/Zygote  ( 6767): v2
I/libpersona( 6767): KNOX_SDCARD checking this for 1000
I/libpersona( 6767): KNOX_SDCARD not a persona
I/SELinux ( 6767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6767): TimaSignature is unavailable
D/ActivityThread( 6767): Added TimaKeyStore provider
D/PackageManager( 1017): delete codoeFile: 
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AASA_removePackage( 1017): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
D/PackageManager( 1017): result of delete: 1{939969772}
W/ContextImpl( 6662): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6662): Samsung link source created
I/ActivityManager( 1017): Killing 5787:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/AndroidRuntime( 6640): Shutting down VM
W/ResourcesManager( 5527): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/SPPClientService( 6751): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6751): [PushClientApplication] Push log off : This is Ship build version
W/ResourcesManager( 5527): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 5951): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
D/SPPClientService( 6751): PushLog.txt file is not deleted.
I/SA      ( 5951): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/SPPClientService( 6751): PushLog.txt file is not deleted.
D/SPPClientService( 6751): ============PushLog. stop!
W/ResourcesManager( 5527): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/ActivityManager( 1017): Killing 5678:com.android.mms/u0a46 (adj 15): empty #31
D/AcmsPackageEventListener( 6767): Received: android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ResourcesManager( 5527): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.

```
