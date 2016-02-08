#### Test 58380500055030c_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
W/libprocessgroup( 1021): failed to open /acct/uid_10120/pid_4690/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4055/cgroup.procs: No such file or directory
--------- beginning of main
E/SMD     (  303): DCD OFF
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5170): getAccountsCursor
D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5170): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5170): Observing account changes for notifications
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5170): Error finding the version of the Email provider.....
E/Gmail   ( 5170): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5170): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5170): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5170): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5170): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5170): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5170): We do not support migrating this version of the Email provider.
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5170): getAccountsCursor
D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4768): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1021): Killing 4262:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 5170): (283) recovered 84 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1021): failed to open /acct/uid_10125/pid_4262/cgroup.procs: No such file or directory
W/GCoreFlp( 1884): No location to return for getLastLocation()
W/FusedLocationProvider( 1884): location=null
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
E/File    ( 5170): fail readDirectory() errno=2
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
I/Gmail   ( 5170): notifyAccountChanged
I/Gmail   ( 5170): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5170): getAccountsCursor
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5170): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5170): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5170): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1884): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5219 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5219): MountEmulatedStorage()
E/Zygote  ( 5219): v2
I/libpersona( 5219): KNOX_SDCARD checking this for 10033
I/libpersona( 5219): KNOX_SDCARD not a persona
I/SELinux ( 5219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5219): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/Gmail   ( 5170): getAccountsCursor
D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5219): TimaSignature is unavailable
D/ActivityThread( 5219): Added TimaKeyStore provider
W/ResourcesManager( 5219): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5219): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5234): 
D/AndroidRuntime( 5234): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5234): CheckJNI is OFF
D/AndroidRuntime( 5234): readGMSProperty: start
D/AndroidRuntime( 5234): readGMSProperty: already setted!!
D/AndroidRuntime( 5234): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5234): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5234): readGMSProperty: end
D/AndroidRuntime( 5234): addProductProperty: start
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5257): MountEmulatedStorage()
E/Zygote  ( 5257): v2
I/libpersona( 5257): KNOX_SDCARD checking this for 10104
I/libpersona( 5257): KNOX_SDCARD not a persona
I/SELinux ( 5257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5257): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5257 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 4498:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
D/TimaKeyStoreProvider( 5257): TimaSignature is unavailable
D/ActivityThread( 5257): Added TimaKeyStore provider
E/AffinityControl( 5234): AffinityControl: registerfunction enter
W/ResourcesManager( 5257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AndroidRuntime( 5234): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5234): Shutting down VM
W/libprocessgroup( 1021): failed to open /acct/uid_10009/pid_4498/cgroup.procs: No such file or directory
I/Babel   ( 5257): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5257): MmsConfig.loadMmsSettings
I/Babel   ( 5257): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5257): MmsConfig.loadFromDatabase
E/Babel   ( 5257): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5257): MmsConfig.loadFromResources
E/Babel   ( 5257): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5257): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
D/ActivityManager( 1021): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 5257): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/art     ( 5234): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Babel_StickerModule( 5257): App launched.
,I/art     ( 1021): Background sticky concurrent mark sweep GC freed 195658(6MB) AllocSpace objects, 16(5MB) LOS objects, 12% free, 54MB/62MB, paused 3.782ms total 152.120ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 4117): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
W/QCamera2Factory(  291): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  291): getCameraInfo: X
,W/QCamera2Factory(  291): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  291): getCameraInfo: X
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5284): MountEmulatedStorage()
E/Zygote  ( 5284): v2
I/libpersona( 5284): KNOX_SDCARD checking this for 10035
I/libpersona( 5284): KNOX_SDCARD not a persona
,I/SELinux ( 5284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5284 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5284): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 5284): TimaSignature is unavailable
,D/ActivityThread( 5284): Added TimaKeyStore provider
,W/VideoCapabilities( 5257): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5257): Unsupported mime audio/evrc
,W/AudioCapabilities( 5257): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5257): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5257): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5257): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5257): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5257): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5257): Unsupported mime audio/evrc
,E/SPPClientService( 5284): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5284): [PushClientApplication] Push log off : This is Ship build version
,W/VideoCapabilities( 5257): Unsupported mime video/wvc1
,D/SPPClientService( 5284): PushLog.txt file is not deleted.
,D/SPPClientService( 5284): PushLog.txt file is not deleted.
W/VideoCapabilities( 5257): Unsupported mime video/x-ms-wmv
,D/SPPClientService( 5284): ============PushLog. stop!
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/VideoCapabilities( 5257): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5257): Unsupported mime video/wvc1
,W/VideoCapabilities( 5257): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5257): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5257): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5257): Unsupported mime video/mp43
,W/VideoCapabilities( 5257): Unsupported mime video/sorenson
,W/VideoCapabilities( 5257): Unsupported mime video/mp4v-esdp
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 5257): Unsupported profile 4 for video/mp4v-es
,E/Zygote  ( 5304): MountEmulatedStorage()
E/Zygote  ( 5304): v2
I/libpersona( 5304): KNOX_SDCARD checking this for 10035
I/libpersona( 5304): KNOX_SDCARD not a persona
I/SELinux ( 5304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5304 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1021): Killing 4222:com.android.providers.calendar/u0a42 (adj 15): empty #31
E/SELinux ( 5304): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5304): TimaSignature is unavailable
,D/ActivityThread( 5304): Added TimaKeyStore provider
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1021): Killing 4301:com.android.calendar/u0a135 (adj 15): empty #31
,E/SPPClientService( 5304): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5304): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 5304): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 5304): PushLog.txt file is not deleted.
,D/SPPClientService( 5304): PushLog.txt file is not deleted.
D/SPPClientService( 5304): ============PushLog. stop!
,E/Zygote  ( 5323): MountEmulatedStorage()
E/Zygote  ( 5323): v2
I/libpersona( 5323): KNOX_SDCARD checking this for 1000
I/libpersona( 5323): KNOX_SDCARD not a persona
I/SELinux ( 5323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1021): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5323 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 4156:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/SELinux ( 5323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5323): TimaSignature is unavailable
,D/ActivityThread( 5323): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5323): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1021): failed to open /acct/uid_10042/pid_4222/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10135/pid_4301/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10041/pid_4156/cgroup.procs: No such file or directory
,I/art     ( 1021): Background sticky concurrent mark sweep GC freed 68273(2MB) AllocSpace objects, 1(1808KB) LOS objects, 3% free, 60MB/62MB, paused 2.992ms total 107.585ms
,I/DIAGMON_AGENT( 5323): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5323): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5323): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1021): Killing 4429:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3055): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5338): MountEmulatedStorage(),
E/Zygote  ( 5338): v2
I/libpersona( 5338): KNOX_SDCARD checking this for 10142
I/libpersona( 5338): KNOX_SDCARD not a persona
,I/SELinux ( 5338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5338 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5338): TimaSignature is unavailable
D/ActivityThread( 5338): Added TimaKeyStore provider
,I/art     (  323): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 33.647ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.415ms
,V/TaskCloserActivity( 5338): TaskCloserActivity enter()
,V/TaskCloserActivity( 5338): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.752ms
,E/Zygote  ( 5353): MountEmulatedStorage(),
E/Zygote  ( 5353): v2
I/libpersona( 5353): KNOX_SDCARD checking this for 10135
I/libpersona( 5353): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5353 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 5353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Killing 4732:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31,
,I/SELinux ( 5353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5353): TimaSignature is unavailable
,D/ActivityThread( 5353): Added TimaKeyStore provider
,W/ResourcesManager( 5353): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5353): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1021): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4429/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_10062/pid_4732/cgroup.procs: No such file or directory
E/Zygote  ( 5374): MountEmulatedStorage()
E/Zygote  ( 5374): v2
I/libpersona( 5374): KNOX_SDCARD checking this for 10042
I/ActivityManager( 1021): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5374 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5374): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Killing 4751:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
I/SELinux ( 5374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5374): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5374): TimaSignature is unavailable
,D/ActivityThread( 5374): Added TimaKeyStore provider
,I/art     ( 1021): Background partial concurrent mark sweep GC freed 365750(21MB) AllocSpace objects, 3(3MB) LOS objects, 27% free, 43MB/59MB, paused 4.886ms total 273.845ms
,W/libprocessgroup( 1021): failed to open /acct/uid_10157/pid_4751/cgroup.procs: No such file or directory
,W/ResourcesManager( 5374): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5374): CalendarProvider2.onCreate() called
,W/PackageManager( 1021): verifying app can be installed or not
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1021): isApplicationInstallationEnabled :  enabled true,
,I/AASAInstall( 1021): ship mode,
,D/ActivityManager( 1021): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5392): MountEmulatedStorage()
E/Zygote  ( 5392): v2
I/libpersona( 5392): KNOX_SDCARD checking this for 1000
I/libpersona( 5392): KNOX_SDCARD not a persona
,I/SELinux ( 5392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1021): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/SQLiteLog( 5374): (284) automatic index on view_events(_id)
,D/TimaKeyStoreProvider( 5392): TimaSignature is unavailable
,D/ActivityThread( 5392): Added TimaKeyStore provider
,E/MTPRx   ( 5392): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/CalendarAlarmManager( 5374): sys current time:1454970732392
D/SecContentProvider2( 1021): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1021): mCursor = null
,D/CalendarAlarmManager( 5374): reminder amount:0
,D/SecContentProvider2( 1021): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1021): mCursor = null
,V/MTPRx   ( 5392): sealedState: false
V/MTPRx   ( 5392): sealedUsbMassStorageState: false
,E/MTPRx   ( 5392): check value of boot_completed is1
E/MTPRx   ( 5392): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5392): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5392): Status for mount/Unmount :removed
E/MTPRx   ( 5392): SDcard is not available
,W/MTPRx   ( 5392): value of connected istrue
W/MTPRx   ( 5392): value of configured istrue
W/MTPRx   ( 5392): value of mtpEnabled istrue
W/MTPRx   ( 5392): value of ptpEnabled isfalse
,E/MTPRx   ( 5392): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5392): mFirstTime: false
,D/        ( 5392): MTP: reading debug level property
,E/MTPJNIInterface( 5392): Getting CryptionKey from JAVA
,E/MTPRx   ( 5392): currentUserId is 0
,E/MTPRx   ( 5392): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5392): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5392): is_Privatemode is NOT 1
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,D/SecContentProvider( 1021): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5392): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1021): name = mtp_running_status
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,E/MTPRx   ( 5392): else part ... so first time!!!
,E/MTPPlaObsrvr( 5392): inside setContext()
E/MTPPlaObsrvr( 5392):  inside createplafiles
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5392): playlist count is0
,E/MTPPlaObsrvr( 5392):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5392):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5392): Inside registerContentObserver
,E/MtpAdbObserver( 5392): inside setContext()
,E/MtpAdbObserver( 5392): Inside registerContentObserver
,W/Settings( 5392): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1021): name = mtp_running_status
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,E/MtpService( 5392): onCreate.
,D/ActivityManager( 1021): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1231): updating state; isCurrentUser=true, mMtpLocked=false
,V/MtpMediaDBManager( 5392): inside deleteAllDB
,E/MtpService( 5392): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5392): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,I/PolicyManagerBroadcastReceiver( 5121): This process will be killed soon.
,I/Process ( 5121): Sending signal. PID: 5121 SIG: 9
,D/MediaScannerReceiver( 1231): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/MtpService( 5392): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5392): onStartCommand.
,W/MTPRx   ( 5392): calling native method
E/MTPJNIInterface( 5392): < MTP > Registering BroadCast receiver :::::
,V/MtpMediaDBManager( 5392): inside Thread updateDB
,E/MTPJNIInterface( 5392): < MTP > Registering BroadCast receiver :::::::
,D/ActivityManager( 1021): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,E/MtpService( 5392): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MTPJNIInterface( 5392): noti = 10
E/MtpService( 5392): onStartCommand.
W/MTPRx   ( 5392): calling native method
E/MTPRx   ( 5392): Checking the driver time out
,E/MTPJNIInterface( 5392): noti = 2
D/        ( 5392): deleting sockets before message queue initialization
D/        ( 5392): event handler thread is created, so set the flag
,E/MtpService( 5392): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 5392): called native method
E/MTPJNIInterface( 5392): setting Media scanner status0
E/MTPJNIInterface( 5392): After setting Media scanner status0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,E/        ( 5392): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5392): Getting media scanner status0
,W/MTPRx   ( 5392): notification from stack 1
,E/MTPJNIInterface( 5392): DeviceName is A5-1
,E/MtpMediaDBManager( 5392): count : 27
,I/SettingSearch/SearchIntentReceiver( 1305): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1305): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1305): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1305): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1305): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/MtpMediaDBManager( 5392): sending db update complete noti to stack
,E/MTPJNIInterface( 5392): noti = 29
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1021): Process com.sec.android.app.wluc (pid 5121)(adj 15) has died(59,1176)
,E/MTPJNIInterface( 5392): Status for mount/Unmount :removed
E/MTPJNIInterface( 5392): SDcard is not available
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5392): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/        ( 5392): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/MTPJNIInterface( 5392): Status for mount/Unmount :removed
E/MTPJNIInterface( 5392): SDcard is not available
,E/SQLiteLog( 5392): (21) API call with NULL database connection pointer
E/SQLiteLog( 5392): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5392): (21) API call with NULL database connection pointer
E/SQLiteLog( 5392): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5392): (21) API call with NULL database connection pointer
E/SQLiteLog( 5392): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5392): (21) API call with NULL database connection pointer
E/SQLiteLog( 5392): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5392): notification from stack 2
,D/        ( 5392): [mtp_init_device] Library open with 32 bits.
D/        ( 5392): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5392): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
D/        ( 5392): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5392):  [sua_support_present:1287] returning false 
D/        ( 5392): *****Starting mtp_io()
,W/MTPRx   ( 5392): notification from stack 3
D/        ( 5392): [mtp_start_io] source_thread Creation 
D/        ( 5392): [mtp_start_io] sink_thread Creation 
D/        ( 5392): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/MediaScannerService( 1231): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1021): Background sticky concurrent mark sweep GC freed 55676(3MB) AllocSpace objects, 16(5MB) LOS objects, 8% free, 54MB/59MB, paused 3.461ms total 100.395ms
,I/SettingSearch/SettingsSearchManager( 1305): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1231): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1305):  Infomation -> getItem size : 306
,D/WearableService( 1884): callingUid 10012, callindPid: 1884
,V/MediaScanner( 1231): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1231): Skipping:
D/MediaScanner( 1231): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1231): Skipping:
D/MediaScanner( 1231): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1231): processDirectory :  /storage/extSdCard
W/MediaScanner( 1231): Error opening directory, reason : Permission denied.
W/MediaScanner( 1231): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1231):  prescan time: 31ms (DB items: 27)
V/MediaScanner( 1231):     scan time: 29ms (Caching mode: true), (makeEntry time: 15ms ~51%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1231): postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
,V/MediaScanner( 1231):    total time: 64ms
V/MediaScanner( 1231): checked files: 10  directories : 17  (I: 0, U: 0)
,I/art     ( 2038): Explicit concurrent mark sweep GC freed 21359(1498KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 12MB/20MB, paused 1.365ms total 62.321ms
,E/DataBuffer( 2038): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a36299f)
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 5392): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ResourcesManager( 1305): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1305): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1305): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1305): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MediaScannerService( 1231): !@done scanning volume external
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/iu.UploadsManager( 2038): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 4489): Conditions not met for autocaching.
I/MusicLeanback( 4489): Stop autocaching.
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{39f2afa8 u0 com.sec.bcservice/.BroadcastService}
,I/iu.UploadsManager( 2038): End new media; added: 0, uploading: 0, time: 80 ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  303): DCD OFF
,E/GmsUtils( 4489): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4489): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1459): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1459): Media DB Scanner finished.
D/CscFactoryReceiver( 1459): start service to Set Ringtone
,D/ActivityManager( 1021): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1459): start service to Set Notification
,D/ActivityManager( 1021): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1459): start service to Set Alarmtone
,D/ActivityManager( 1021): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1459): onStart
E/CscUpdateService( 1459): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1459): only ringtone update
,D/CscUpdateService( 1459): onStart
E/CscUpdateService( 1459): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1459): only notification update
,D/CscUpdateService( 1459): onStart
E/CscUpdateService( 1459): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1459): only alarmtone update
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1459): update(): xml file exist,
E/CscParser( 1459): update(): xml file exist
I/ActivityManager( 1021): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5434 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
E/CscParser( 1459): update(): xml file exist
W/CSCSettings( 1459): Setting Ringtones (type) : 1
D/CscParser( 1459): RingTone: null
W/CSCSettings( 1459): 1. Tag_Str: null,
W/CSCSettings( 1459): Setting Ringtones (type) : 2
D/CscParser( 1459): MessageTone: null
W/CSCSettings( 1459): 1. Tag_Str: null
E/Zygote  ( 5434): MountEmulatedStorage()
E/Zygote  ( 5434): v2
I/libpersona( 5434): KNOX_SDCARD checking this for 10006
I/libpersona( 5434): KNOX_SDCARD not a persona
W/CSCSettings( 1459): Setting Ringtones (type) : 4
D/CscParser( 1459): AlarmTone: null
W/CSCSettings( 1459): 1. Tag_Str: null
,I/SELinux ( 5434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5434): TimaSignature is unavailable
,D/ActivityThread( 5434): Added TimaKeyStore provider
,D/PackageManager( 1021): Existing package
,D/PackageManager( 1021): Renaming /data/app/vmdl627578654.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1021): installNewPackageLI: Package{12915cb4 com.test.thalitest}
,I/PackageManager( 1021): scanFileNewer : com.test.thalitest
,I/ThumbnailProvider( 5434): ThumbnailProvider onCreate()
,I/art     ( 1021): Background partial concurrent mark sweep GC freed 275436(15MB) AllocSpace objects, 3(5MB) LOS objects, 27% free, 42MB/58MB, paused 6.808ms total 258.350ms
,I/DocumentBroadcastReceiver( 5434): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5434): [START] processBroadcastIntent ...
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,D/BluetoothMediaBrowser( 2598):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5038): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/BluetoothMediaBrowser( 2598): no now playing list
D/BluetoothMediaBrowser( 2598):  getNowPlayingId now playing id : -1
,D/GalleryCacheReady( 5038): handleMeidaScanFinish()
,D/FaceInterface( 5038): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5038): query fail: 
,W/LocalSuggestAlbumData( 5038): query fail: 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,I/BroadcastProcessorService( 5434): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/FaceInterface( 5038): startFaceScan() : waiting 5 sec
,I/SystemInfo( 5434): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5434): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5434): [START] DocumentService startDocumentService
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DocumentService( 5434): DocumentService onCreate ... service
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/SettingSearch/SearchIntentReceiver( 1305): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1305): LOCALE_CHANGED call search setting db finish!!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5434): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5434): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/MediaStoreImporter( 4489): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/SystemInfo( 5434): [SIOP LEVEL] : 0
,I/DocumentService( 5434): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5434): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files,
,I/SettingSearch/SearchIntentReceiver( 1305): InitTitleDBThread start --> mDoingInitTitleDB : true
,E/File    ( 5434): fail readDirectory() errno=13
E/File    ( 5434): fail readDirectory() errno=13
,I/SystemInfo( 5434): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5434): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5434): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :28
E/DocumentService( 5434): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5434): [INDEX] Total time taken for each file :0
,I/art     ( 1021): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1021): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1021): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/DocumentService( 5434): DocumentService onDestroy start,
I/DocumentService( 5434): DocumentService onDestroy end
,I/DocumentService( 5434): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5434): InterruptedException: null
,I/SystemInfo( 5434): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5434): DocumentService cleanupEverything end
,I/Process ( 5434): Sending signal. PID: 5434 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1305): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1305): LOCALE_CHANGED call search setting db finish!!
,I/dex2oat ( 5458): ----------------------------------------------------
I/dex2oat ( 5458): <SS>: S T A R T I N G . . .
I/dex2oat ( 5458): <SS>: going to process manifest for 32-bit...
,I/        ( 5458): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5458): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5458): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5458): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5458): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5458): SS_ART_lib [I]: Parsing completed
I/        ( 5458): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5458): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5458): SS_ART_lib [I]: access to SS denied
I/        ( 5458): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5458): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5458): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5458): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5458): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5458): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5458): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/CalendarProvider2( 5374): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1021): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1021): Process com.samsung.indexservice (pid 5434)(adj 11) has died(61,1177)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1021): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/dex2oat ( 5458): dex2oat took 391.310ms (threads: 4)
,I/PackageManager( 1021): do mInstaller.dexopt : 0
,D/PackageManager( 1021): Time to dexopt: 0.46 seconds
,W/System.err( 1021): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1021): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1021): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1021): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1021): 	,at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
W/System.err( 1021): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1021): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1021): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:446),
W/System.err( 1021): 	... 5 more
,I/HarmonyEASService( 1021): Updating for all 1
D/PackageManager( 1021): New package installed
,D/PackageManager( 1021): doPostInstall for uid{10155}
,D/PackageManager( 1021): token 1 to BM for possible restore
,V/BackupManagerService( 1021): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1021): Finishing install immediately
D/PackageManager( 1021): BM finishing package install for 1
,D/PackageManager( 1021): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1021): [MSG] MCS_UNBIND
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4208): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5469): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5469 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/FaceInterface( 5038): startFaceScan() : going on
E/Zygote  ( 5469): v2
,I/libpersona( 5469): KNOX_SDCARD checking this for 1000
I/libpersona( 5469): KNOX_SDCARD not a persona
D/FaceInterface( 5038): startFaceScan() is called.
,I/SELinux ( 5469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1021): [MSG] POST_INSTALL: observer{100459879}
D/PackageManager( 1021):           Handling post-install for 1
,I/ActivityManager( 1021): Killing 4791:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/ContentApp( 1231): startScan() is called.
,D/FaceValue( 1231): mSleepTime: 800
D/FaceValue( 1231): mMaxThreadNum: 2
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5469): TimaSignature is unavailable
,D/ActivityThread( 5469): Added TimaKeyStore provider
,W/FaceValue( 1231): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,W/Settings( 1021): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
D/ContentApp( 1231): startScan() is end.
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ContentApp( 1231): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1231): isNeedToRestore : start
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 5469): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1769): mOCRHelper is null
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1021): Killing 4816:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/splitIntent( 1021): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1021): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1021): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/RegisteredServicesCache( 1444): empty dynamic service
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5488): MountEmulatedStorage(),
E/Zygote  ( 5488): v2
I/libpersona( 5488): KNOX_SDCARD checking this for 10057
I/libpersona( 5488): KNOX_SDCARD not a persona
,I/SELinux ( 5488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5488 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,I/SELinux ( 5488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5488): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,I/FaceInterface( 5038): startFaceScan() : going on
,D/FaceInterface( 5038): startFaceScan() is called.
,D/ContentApp( 1231): startScan() is called.
,D/ContentApp( 1231): startScan() is end.
,D/TimaKeyStoreProvider( 5488): TimaSignature is unavailable
,D/ContentApp( 1231): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1231): isNeedToRestore : start
,D/ActivityThread( 5488): Added TimaKeyStore provider
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,I/art     ( 1231): Explicit concurrent mark sweep GC freed 6859(460KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 725us total 64.274ms
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1444): empty dynamic service
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1021): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 41530(3MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 3.414ms total 289.558ms
D/PackageManager( 1021): result of install: 1{100459879}
,I/PackageManager( 1021): Observer no longer exists.
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1021): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1021): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1021): PackageReceiver onReceive()
D/RCPManagerService( 1021): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1021):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1021):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
W/BackupManagerService( 1021): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1021): uID is 10155
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter,
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0,
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null,
D/PersonaPolicyManagerService( 1021): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService( 1021): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1884): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/BackupManagerService( 1021): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ce11445
,V/AlarmManagerEXT( 1021): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1021): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1021): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5509): MountEmulatedStorage()
E/Zygote  ( 5509): v2
I/libpersona( 5509): KNOX_SDCARD checking this for 10015
I/libpersona( 5509): KNOX_SDCARD not a persona
I/SELinux ( 5509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1021): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5509 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 5509): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
,I/CrashAnrDetector( 1021): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4791/cgroup.procs: No such file or directory
,D/LocationManagerService( 1021): getProviders()=[passive]
,D/TimaKeyStoreProvider( 5509): TimaSignature is unavailable
,D/ActivityThread( 5509): Added TimaKeyStore provider
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GCoreNlp( 1884): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/libprocessgroup( 1021): failed to open /acct/uid_10085/pid_4816/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1021): applying state to connected service
D/LocationProviderProxy( 1021): applying state to connected service
,D/LocationProviderProxy( 1021): applying state to connected service
,I/ActivityManager( 1021): Killing 4837:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5257): Creating RTCS
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5534): MountEmulatedStorage(),
,E/Zygote  ( 5534): v2
I/libpersona( 5534): KNOX_SDCARD checking this for 10032
I/SELinux ( 5534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 5534): KNOX_SDCARD not a persona
I/SELinux ( 5534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1021): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5534 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5534): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5534): TimaSignature is unavailable
,D/ActivityThread( 5534): Added TimaKeyStore provider
,W/libprocessgroup( 1021): failed to open /acct/uid_10094/pid_4837/cgroup.procs: No such file or directory
,I/Babel   ( 5257): Destroying RTCS
,I/ActivityManager( 1021): Killing 4893:com.wsomacp/u0a25 (adj 15): empty #31
,I/FeatureConfig( 5534): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/ActivityManager( 1021): Killing 4916:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 5038): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5534): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,I/UpdateIcingCorporaServi( 5488): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5552): MountEmulatedStorage()
E/Zygote  ( 5552): v2
I/libpersona( 5552): KNOX_SDCARD checking this for 10069
I/libpersona( 5552): KNOX_SDCARD not a persona
,I/SELinux ( 5552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5552 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1021): failed to open /acct/uid_10025/pid_4893/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10003/pid_4916/cgroup.procs: No such file or directory
,W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5552): TimaSignature is unavailable
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityThread( 5552): Added TimaKeyStore provider
,W/ResourcesManager( 5534): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FileShare-Server( 5552): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,W/ResourcesManager( 5534): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5567): MountEmulatedStorage()
W/ResourcesManager( 5534): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
E/Zygote  ( 5567): v2
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/libpersona( 5567): KNOX_SDCARD checking this for 1000
I/libpersona( 5567): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5567 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/UpdateIcingCorporaServi( 5488): UpdateCorporaTask done [took 121 ms] updated apps [took 120 ms] 
E/SELinux ( 5567): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 4933:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5567): TimaSignature is unavailable
,W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/ActivityThread( 5567): Added TimaKeyStore provider
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5534): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5567): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5534): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5583): MountEmulatedStorage()
,E/Zygote  ( 5583): v2
I/libpersona( 5583): KNOX_SDCARD checking this for 1000
I/libpersona( 5583): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5583 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 4967:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
I/SELinux ( 5583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  323): Explicit concurrent mark sweep GC freed 8746(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 22.589ms
,D/TimaKeyStoreProvider( 5583): TimaSignature is unavailable
,D/ActivityThread( 5583): Added TimaKeyStore provider
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 749us total 18.762ms
,D/KnoxSetupWizardDbHelper( 5583): dbMigrationFlag : false
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 730us total 20.057ms
,D/ShortcutReceiver( 5583):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_10107/pid_4933/cgroup.procs: No such file or directory
,E/Zygote  ( 5600): MountEmulatedStorage(),
E/Zygote  ( 5600): v2
I/libpersona( 5600): KNOX_SDCARD checking this for 10120
I/libpersona( 5600): KNOX_SDCARD not a persona
I/SELinux ( 5600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5600): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5600 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 4775:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms,
,I/GAV2    ( 5170): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 5600): TimaSignature is unavailable
,D/ActivityThread( 5600): Added TimaKeyStore provider
,W/ResourcesManager( 5600): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1021): No listener is left
,W/libprocessgroup( 1021): failed to open /acct/uid_10153/pid_4967/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10046/pid_4775/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5622): MountEmulatedStorage(),
E/Zygote  ( 5622): v2
I/libpersona( 5622): KNOX_SDCARD checking this for 10028
I/libpersona( 5622): KNOX_SDCARD not a persona,
I/SELinux ( 5622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5622 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5622): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 5087:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5622): TimaSignature is unavailable
,D/ActivityThread( 5622): Added TimaKeyStore provider
,D/Finsky  ( 5622): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{2e393880 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5087/cgroup.procs: No such file or directory
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/Finsky  ( 5622): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5622): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5622): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5622): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5622): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5622): Skipping gmscore version check
,D/Finsky  ( 5622): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1021): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2038): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5622): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/HomeSyncInstallReceiver( 1444): This pkg do not need BT addr. Do nothing
,I/PackageBroadcastService( 2038): Null package name or gms related package.  Ignoreing.
,I/splitIntent( 1021): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1021): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5469): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5469): parseToken()
,W/System.err( 5469): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 5469): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5469): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5469): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5469): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5469): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5469): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5469): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5469): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5469): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5469): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5469): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5469): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5469): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5469): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5469): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5469): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5469): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5469): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5469): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5469): 	... 14 more
E/AASAservice-TokenRule( 5469): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 5469): AASARuleUpdateResult() : Rule file is not exist.
I/PackagesMonitor( 5038): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5665): MountEmulatedStorage()
E/Zygote  ( 5665): v2
I/ActivityManager( 1021): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5665 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/libpersona( 5665): KNOX_SDCARD checking this for 10152
I/libpersona( 5665): KNOX_SDCARD not a persona
I/SELinux ( 5665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5665): TimaSignature is unavailable
D/ActivityThread( 5665): Added TimaKeyStore provider
E/Zygote  ( 5681): MountEmulatedStorage()
E/Zygote  ( 5681): v2
I/libpersona( 5681): KNOX_SDCARD checking this for 10046
I/libpersona( 5681): KNOX_SDCARD not a persona
I/SELinux ( 5681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5681 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 5681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5681): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1021): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5681): TimaSignature is unavailable
,D/ActivityThread( 5681): Added TimaKeyStore provider
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 5139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5665): (284) automatic index on shooting_modes(title_id)
,E/Zygote  ( 5704): MountEmulatedStorage()
E/Zygote  ( 5704): v2
I/libpersona( 5704): KNOX_SDCARD checking this for 1000
I/libpersona( 5704): KNOX_SDCARD not a persona
,I/SELinux ( 5704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/TimaKeyStoreProvider( 5704): TimaSignature is unavailable
,D/ActivityThread( 5704): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2038): Storage manager: low false usage 1.73MB avail 10.16GB capacity 11.68GB
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/SMD     (  303): DCD OFF
,W/ResourcesManager( 5681): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5681): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5681): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5681): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5681): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5681): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5723): MountEmulatedStorage()
,E/Zygote  ( 5723): v2
I/libpersona( 5723): KNOX_SDCARD checking this for 1000
I/libpersona( 5723): KNOX_SDCARD not a persona
I/SELinux ( 5723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5723): TimaSignature is unavailable
,D/ActivityThread( 5723): Added TimaKeyStore provider
,E/Zygote  ( 5738): MountEmulatedStorage()
,E/Zygote  ( 5738): v2
I/libpersona( 5738): KNOX_SDCARD checking this for 10156
I/libpersona( 5738): KNOX_SDCARD not a persona
,I/SELinux ( 5738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5738 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/PCWCLIENTTRACE_LOG( 5704): DEFAULT_LOGON : true,
I/PCWCLIENTTRACE_LOG( 5704): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5704): new DMDBOpenHelper instance
,I/SELinux ( 5738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 5681): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1021): Killing 5103:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31,
,I/PCWCLIENTTRACE_PushUtil( 5704): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5704): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5704): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5704): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/TimaKeyStoreProvider( 5738): TimaSignature is unavailable
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 5738): Added TimaKeyStore provider
,W/ResourcesManager( 5723): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,E/Zygote  ( 5755): MountEmulatedStorage(),
I/libpersona( 5755): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5755): v2
I/libpersona( 5755): KNOX_SDCARD not a persona
I/SELinux ( 5755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,W/libprocessgroup( 1021): failed to open /acct/uid_10122/pid_5103/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5755): TimaSignature is unavailable
,D/ActivityThread( 5755): Added TimaKeyStore provider
,E/Zygote  ( 5770): MountEmulatedStorage()
E/Zygote  ( 5770): v2
I/libpersona( 5770): KNOX_SDCARD checking this for 10091
I/libpersona( 5770): KNOX_SDCARD not a persona
,I/SELinux ( 5770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5738): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5738): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
I/SELinux ( 5770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5770): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5770 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 5219:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 5770): TimaSignature is unavailable
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5770): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 4117:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/TapandpayWidget:Utils( 5738): Clear T&P info.
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5738): Widget is not attached.
,W/art     ( 5681): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 148.530ms
,W/libprocessgroup( 1021): failed to open /acct/uid_10033/pid_5219/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10035/pid_4117/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 5622): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/Zygote  ( 5789): MountEmulatedStorage()
,E/Zygote  ( 5789): v2
I/libpersona( 5789): KNOX_SDCARD checking this for 10010
I/libpersona( 5789): KNOX_SDCARD not a persona
,I/SELinux ( 5789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1021): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5789 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 5789): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 5284:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5789): TimaSignature is unavailable
,D/ActivityThread( 5789): Added TimaKeyStore provider
,D/Mms/ArtClassLoader( 5681): init before art
,D/Mms/TelephonyPermission( 5681): start operation mode monitor
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ResourcesManager( 5681): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,D/Mms/TelephonyPermission( 5681): DefaultSmsApp is com.android.mms
I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
D/Mms/TelephonyPermission( 5681): isDefault true
,D/Mms/MmsApp( 5681): onCreate() com.android.mms
,W/libprocessgroup( 1021): failed to open /acct/uid_10035/pid_5284/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5755): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5755): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 2038): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraModuleLdr( 2038): Loading module APK com.google.android.play.games
I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/Mms/MmsApp( 5681): [start]    initCountryIso consume time = 405.439323
,D/CountryDetector( 1021): The first listener is added
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
D/Mms/MmsApp( 5681): [end]    initCountryIso consume time = 10.956198
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/Mms/MmsConfig( 5681): [start]    MmsConfig.init() consume time = 0.616146
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig( 5681): before partial update
,E/Zygote  ( 5820): MountEmulatedStorage()
E/Zygote  ( 5820): v2
I/libpersona( 5820): KNOX_SDCARD checking this for 10035
I/libpersona( 5820): KNOX_SDCARD not a persona
,I/SELinux ( 5820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1021): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5820 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5820): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 5304:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/Mms/MmsConfig( 5681): Load Resize quality : 80
,D/TimaKeyStoreProvider( 5820): TimaSignature is unavailable
,D/ActivityThread( 5820): Added TimaKeyStore provider
,D/EasySignUpManager_1.0.1( 5681): serviceId : 1, features : -1
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
D/EasySignUpManager_1.0.1( 5681): isAuth is false
D/Mms/MmsConfig( 5681): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5755): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/art     (  323): Explicit concurrent mark sweep GC freed 8735(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 55.728ms
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5755): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,D/TP/MmsSmsProvider( 1459): query,matched:2117, calling pid = 5681
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/TP/MmsSmsProvider( 1459): match 2117:Elapsed time : 9.063 ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 684us total 22.046ms
,D/EasySignUpManager_1.0.1( 5681): isAuth is false
D/EasySignUpManager_1.0.1( 5681): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5681): mps_code.dat does not exist
,E/CscParser( 5681): customer_path =/system/csc/customer.xml
E/CscParser( 5681): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 700us total 18.359ms
,W/libprocessgroup( 1021): failed to open /acct/uid_10035/pid_5304/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/CscParser( 5681): mps_code.dat does not exist
E/CscParser( 5681): customer_path =/system/csc/customer.xml
E/CscParser( 5681): fileName + /system/csc/customer.xml
,D/CscParser( 5681): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5681):  enable multiwindow = true
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5755): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,I/DBG_POLICYDM( 5755): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/08/23:32:16
,E/SPPClientService( 5820): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5820): [PushClientApplication] Push log off : This is Ship build version
,E/PhotosPlugin( 5770): Loading PhotosPlugin
,I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,D/SPPClientService( 5820): PushLog.txt file is not deleted.
,D/SPPClientService( 5820): PushLog.txt file is not deleted.
D/SPPClientService( 5820): ============PushLog. stop!
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5755): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5755): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,E/Zygote  ( 5840): MountEmulatedStorage()
E/Zygote  ( 5840): v2
I/libpersona( 5840): KNOX_SDCARD checking this for 10038,
I/DBG_POLICYDM( 5755): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/libpersona( 5840): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5840 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
I/SELinux ( 5840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5840): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
E/Mms/MessageUtils( 5681): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5681): updateCountryIso : update country iso info 
,I/DBG_POLICYDM( 5755): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,D/Mms/MmsConfig( 5681): [end]    init() consume time = 201.395677
,D/Mms/Contact( 5681): [start]    init() consume time = 0.848593
,D/TimaKeyStoreProvider( 5840): TimaSignature is unavailable
D/ActivityThread( 5840): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5755): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5755): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,D/TP/MmsSmsProvider( 1459): query,matched:13, calling pid = 5681
D/TP/MmsSmsProvider( 1459): match 13:Elapsed time : 1.547 ms
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/Mms/Contact( 5681): [end]    init consume time = 24.678959
,D/Mms/DraftCache( 5681): [start]    rebuildCache consume time = 23.321458
,D/TP/MmsSmsProvider( 1459): query,matched:12, calling pid = 5681
D/TP/MmsSmsProvider( 1459): match 12:Elapsed time : 1.020 ms
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/Mms/DraftCache( 5681): [end]    rebuildCache consume time = 14.471615
,D/Mms/MethodReflector( 5681): getSubId is called
D/Mms/TelephonyUtils( 5681): getLongSubId from simSlot 0, return Value = -1
,W/ResourcesManager( 5840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5840): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Mms/MethodReflector( 5681): getTelephonyProperty is called
,D/Mms/DownloadManager( 5681): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5681): auto download without roaming -> true
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5681): getSubId is called
D/Mms/MethodReflector( 5681): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5681): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5681): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5681): getTelephonyProperty is called
D/Mms/DownloadManager( 5681): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5681): auto download without roaming -> true
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5681): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5681): mAutoDownload ------> true
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/ComposerPerformance( 5681): 1454970736808 ms / [DONE] Composer constructor
,I/Icing   ( 2038): updateResources: need to parse f{com.google.android.gms}
,E/CII     ( 5681): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5681): ReservationManager()
I/Mms/ReservationManager( 5681): resetAfterConnected()
,D/TP/MmsSmsProvider( 1459): query,matched:7, calling pid = 5681
,D/TP/MmsSmsProvider( 1459): match 7:Elapsed time : 3.007 ms
,D/Mms/Conversation( 5681): [start]    init() consume time = 157.37427
,D/TP/MmsSmsProvider( 1459): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1459): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1459): updateThread(), thread_id = 9223372036854775807
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 206729(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.852ms total 237.240ms
V/TP/MmsSmsDatabaseHelper( 1459): sUpgradeVersion = 0, db.getVersion() = 81
,I/Mms/ReservationManager( 5681): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1459): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
,D/Mms/MmsApp( 5681): [end]    onCreate() consume time = 15.770313
,D/Mms/Conversation( 5681): [end]    init consume time = 1.610729
,D/Mms/DownloadManager( 5681): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5681): roaming ------> false, mSimSlot = 0
,D/Mms/MessagingNotification( 5681): [start]    init() consume time = 7.895885
,D/Mms/MessagingNotification( 5681): [end]    init consume time = 6.452292
,D/Mms/MethodReflector( 5681): getSubId is called
D/Mms/TelephonyUtils( 5681): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5681): getTelephonyProperty is called
D/Mms/DownloadManager( 5681): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5681): auto download without roaming -> true
D/Mms/DownloadManager( 5681): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5681): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1459): query,matched:0, calling pid = 5681
,V/TP/MmsSmsProvider( 1459): getSimpleConversations entered.
,D/Mms/Synchronizer( 5681): [start]    doSync consume time = 10.747136
,D/TP/MmsSmsProvider( 1459): match 0:Elapsed time : 3.824 ms
,I/DBG_POLICYDM( 5755): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/TP/MmsSmsProvider( 1459): update, matched:300, calling pid = 5681
,V/TP/MmsSmsProvider( 1459): syncDBData start
,V/TP/MmsSmsProvider( 1459): syncDBData sms end
,V/TP/MmsSmsProvider( 1459): syncDBData mms end
D/Mms/FreeMessageStatusReceiver( 5681): onReceive, action : android.intent.action.PACKAGE_ADDED
,V/TP/MmsSmsProvider( 1459): syncDBData end
D/Mms/Synchronizer( 5681): [end]    doSync consume time = 10.920833
,D/ActivityManager( 1021): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/Mms/SpamFilter( 5681): [start]    SpamFilter fill() begin consume time = 9.747812
,E/Zygote  ( 5862): MountEmulatedStorage(),
I/libpersona( 5862): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5862): v2
,I/libpersona( 5862): KNOX_SDCARD not a persona
I/SELinux ( 5862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1021): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5862 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 5862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1021): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/SELinux ( 5862): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5862): TimaSignature is unavailable,
D/ActivityThread( 5862): Added TimaKeyStore provider
,E/Zygote  ( 5871): MountEmulatedStorage()
E/Zygote  ( 5871): v2
I/libpersona( 5871): KNOX_SDCARD checking this for 10072
I/libpersona( 5871): KNOX_SDCARD not a persona
I/SELinux ( 5871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5871 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5871): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1459): query,matched:400, calling pid = 5681
,D/Mms/SpamFilter( 5681): [end]    SpamFilter fill() finished consume time = 64.241146
,W/ResourcesManager( 5862): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5862): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5862): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5871): TimaSignature is unavailable
,D/ActivityThread( 5871): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 5681): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5681): onHandleIntent: ACTION_PACKAGE_ADDED
,D/Mms/ArtClassLoader( 5681): init [DONE] art
,I/ActivityManager( 1021): Killing 5338:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 5323:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,D/BadgeProvider( 5871): onCreate
,D/BadgeProvider( 5871): DatabaseHelper
,D/Mms/MessagingNotification( 5681): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1459): query,matched:26, calling pid = 5681
,D/TP/SmsProvider( 1459): match 26:Elapsed time : 1.601 ms
,D/TP/MmsSmsProvider( 1459): query,matched:6, calling pid = 5681
,D/TP/MmsSmsProvider( 1459): match 6:Elapsed time : 1.290 ms
,V/AlarmManager( 1021): waitForAlarm result :4,
,W/libprocessgroup( 1021): failed to open /acct/uid_10142/pid_5338/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5323/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2038): Module APK com.google.android.play.games already loaded
,E/Zygote  ( 5896): MountEmulatedStorage(),
E/Zygote  ( 5896): v2
I/libpersona( 5896): KNOX_SDCARD checking this for 10025
I/libpersona( 5896): KNOX_SDCARD not a persona
,I/SELinux ( 5896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5896 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 5896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5896): TimaSignature is unavailable
,D/ActivityThread( 5896): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 5374:com.android.providers.calendar/u0a42 (adj 15): empty #31
,W/ResourcesManager( 5896): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/MyFiles ( 5862): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/ActivityManager( 1021): Killing 5154:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/AsyncTaskServiceImpl( 2038): Submit a task: k
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/TactileAssist( 1021): enable value -1
I/TactileAssist( 1021): internal enable value -1
I/TactileAssist( 1021): intensity value -1
,I/TactileAssist( 1021): saveAppList value true
,I/TactileAssist( 1021): List of disabled apps :
,I/ActivityManager( 1021): Killing 5020:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 5374
,E/installd(  294): system dir 0 : /system/app/
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/installd(  294): system dir 1 : /system/priv-app/
E/installd(  294): system dir 2 : /vendor/app/
E/installd(  294): system dir 3 : /oem/app/
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1021): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  ( 5918): MountEmulatedStorage()
I/libpersona( 5918): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5918): v2
I/libpersona( 5918): KNOX_SDCARD not a persona
,I/SELinux ( 5918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5918 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 5918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5918): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_10042/pid_5374/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10150/pid_5154/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10040/pid_5020/cgroup.procs: No such file or directory
,I/OMACP   ( 5896): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 5681): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/k       ( 2038): Processing package: com.test.thalitest
,D/TimaKeyStoreProvider( 5918): TimaSignature is unavailable
,D/ActivityThread( 5918): Added TimaKeyStore provider
,W/ResourcesManager( 5918): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,D/GassUtils( 2038): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2038): Found info for package com.test.thalitest in db.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/Compatibility( 5918): onReceive() it will make start service
,D/ActivityManager( 1021): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,D/Compatibility( 5918): onHandleIntent()
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,D/Compatibility( 5918): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/Compatibility( 5918): found: 2
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/UpdateIcingCorporaServi( 5488): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5896): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/Compatibility( 5918): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5918): skipping ResolveInfo{3c5a935d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5918): considering ResolveInfo{226544d2 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5918): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5918): enabling receiver ResolveInfo{c8279a3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/DBG_POLICYDM( 5755): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/Compatibility( 5918): enabling receiver ResolveInfo{bafa4a0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 5918): enabling receiver ResolveInfo{31b20859 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/Compatibility( 5918): enabling receiver ResolveInfo{352edc1e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Compatibility( 5918): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 2038): Done disabling old GoogleServicesFramework version
,I/SL_DEBUG( 5840): isLoggable:: isProductShip = 1
W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5840): isLoggable:: SL_DEBUG_EXIST = false
,I/PeopleDatabaseHelper( 2038): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5840): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5951): MountEmulatedStorage(),
E/Zygote  ( 5951): v2
I/libpersona( 5951): KNOX_SDCARD checking this for 10041
I/libpersona( 5951): KNOX_SDCARD not a persona
,I/SELinux ( 5951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5951): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5951 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5951): TimaSignature is unavailable
,D/ActivityThread( 5951): Added TimaKeyStore provider
,I/Icing   ( 2038): Internal init done: storage state 0
,I/SA      ( 5951): [SSP] onCreated
,I/SA      ( 5951): [TPM] There is no property file
,I/SA      ( 5951): [SCU] isHaveSA() - false
,I/SA      ( 5951): [TPM] getModelProperty : null
I/SA      ( 5951): [TPM] getCSCProperty : null
,I/SA      ( 5951): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5951): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5951): [DM] TFT FEATURE: false
,I/SA      ( 5951): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/art     ( 1661): Explicit concurrent mark sweep GC freed 3592(142KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 815us total 34.680ms
,I/SA      ( 5951): [DM] init START
,W/GAV2    ( 5770): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SA      ( 5951): [DM] This device is not a Vodafone
,W/ResourceType( 5951): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
I/Icing   ( 2038): Post-init done
W/ResourceType( 5951): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/Icing   ( 2038): updateResources: need to parse f{com.google.android.gms}
,W/ResourceType( 5951): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5951): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5951): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 5951): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 5951): [SCU] isHaveSA() - false
I/SA      ( 5951): support phone number id : false
I/SA      ( 5951): [DM] Supports Ref Jpn : true
,I/SA      ( 5951): [DM] init END
I/SA      ( 5951): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5951): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1021): Killing 4489:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_10111/pid_4489/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5983): MountEmulatedStorage()
,E/Zygote  ( 5983): v2
I/libpersona( 5983): KNOX_SDCARD checking this for 10100
I/libpersona( 5983): KNOX_SDCARD not a persona
,I/SELinux ( 5983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5983 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 5170:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GAV2    ( 5770): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5983): TimaSignature is unavailable
,D/ActivityThread( 5983): Added TimaKeyStore provider
,D/PackageIntentReceiver( 5983): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5983): Not GearManger package! 
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6005): MountEmulatedStorage()
E/Zygote  ( 6005): v2
I/libpersona( 6005): KNOX_SDCARD checking this for 1000
I/libpersona( 6005): KNOX_SDCARD not a persona
,I/SELinux ( 6005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1021): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6005 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SELinux ( 6005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5770): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1021): Killing 4857:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,I/FaceInterface( 5038): startFaceScan() : going on
,D/FaceInterface( 5038): startFaceScan() is called.
,D/TimaKeyStoreProvider( 6005): TimaSignature is unavailable
,D/ActivityThread( 6005): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5770): Write apps_features disabled false
,D/ContentApp( 1231): startScan() is called.
D/ContentApp( 1231): startScan() is end.
,I/art     ( 1884): Explicit concurrent mark sweep GC freed 35382(2MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 12MB/21MB, paused 1.329ms total 82.994ms
,E/DataBuffer( 1884): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29caa7c9)
,D/ContentApp( 1231): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1231): isNeedToRestore : start
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5488): UpdateCorporaTask done [took 845 ms] updated apps [took 845 ms] 
,I/ActivityManager( 1021): Killing 5353:com.android.calendar/u0a135 (adj 15): empty #31
,W/libprocessgroup( 1021): failed to open /acct/uid_10101/pid_5170/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6023): MountEmulatedStorage(),
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 1000
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6023): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 5257:com.google.android.talk/u0a104 (adj 15): empty #31
,I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_10134/pid_4857/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
,D/ActivityThread( 6023): Added TimaKeyStore provider
,D/AcmsPackageEventListener( 6023): Received: android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ContextImpl( 6023): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsService( 6023): Enter Oncreate
,D/AcmsServiceMonitor( 6023): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6023): creating AcmsCore
,D/AcmsCore( 6023): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6023): AcmsCore
,D/AcmsCore( 6023): init
D/AcmsCore( 6023): Looper handler is not null
D/AcmsCore( 6023): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6023): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6023): Incrementing - Counter value: 1
D/AcmsCore( 6023): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6023): onStartCommand
D/AcmsService( 6023): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6023): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6023): Incrementing - Counter value: 2
D/AcmsService( 6023): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6023): AcmsCertificateMngr
,D/ActivityManager( 1021): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6023): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6023): AcmsRevocationMngr
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2038): Module APK com.google.android.play.games already loaded
,W/libprocessgroup( 1021): failed to open /acct/uid_10135/pid_5353/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10104/pid_5257/cgroup.procs: No such file or directory
,D/AcmsService( 6023): Inside handle Intent
D/AcmsService( 6023): App added - package name: com.test.thalitest
D/AcmsCore( 6023): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6023): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6023): Incrementing - Counter value: 3
D/AcmsCore( 6023): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6023): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6023): Decrementing - Counter value: 2
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/SSRM:n  ( 1021): SIOP:: AP = 390
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 1021): [SO] 0.019 0.096 10.132
,I/Mms/MmsApp( 5681):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5681): [start]    fillCache consume time = 1890.61651
,D/Mms/ComposeMessageFragment( 5681): fillCache, easy = false
,D/AbsListView( 5681): Get MotionRecognitionManager
,D/MotionRecognitionService( 1021):  ssp status : false
,D/Mms/ComposeMessageFragment( 5681): [end]    fillCache consume time = 71.97401
,E/SMD     (  303): DCD OFF
,D/Mms/BubbleViewCache( 5681): fillCache bubble = 1
,I/Icing   ( 2038): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Icing   ( 2038): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2038): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 2038): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,I/Icing   ( 2038): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,I/Icing   ( 2038): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Icing   ( 2038): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 5552:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1021): failed to open /acct/uid_10069/pid_5552/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/SMD     (  303): DCD OFF
,D/AcmsKeyStoreHelper( 6023):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6023): Key Store exist
,I/AcmsKeyStoreHelper( 6023): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6023):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6023): getKeyStoreForApplication success 
D/AcmsCore( 6023): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6023): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6023): Decrementing - Counter value: 1
D/AcmsCore( 6023): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6023): This is NOT a valid MirrorLink app
,D/AcmsCore( 6023): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6023): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6023): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6023): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6023): getSvcCounter - Counter value: 0
,D/AcmsService( 6023): Enter onDestroy
I/AcmsService( 6023): cleanUp(): inside service clean up
D/AcmsCore( 6023): AcmsCore: inside DeInit
D/AcmsCore( 6023): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6023): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6023): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6023): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6023): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6023): getSvcCounter - Counter value: 0
D/AcmsService( 6023): killing acms process
I/Process ( 6023): Sending signal. PID: 6023 SIG: 9
,I/ActivityManager( 1021): Process ACMS.Process (pid 6023)(adj 0) has died(78,1183)
,V/AlarmManager( 1021): waitForAlarm result :4
,D/ActivityManager( 1021): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6049): MountEmulatedStorage()
,I/libpersona( 6049): KNOX_SDCARD checking this for 10104
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD not a persona
,I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6049 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
,D/ActivityThread( 6049): Added TimaKeyStore provider
,W/ResourcesManager( 6049): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 2038): End new media; added: 0, uploading: 0, time: 66 ms
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Babel   ( 6049): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6049): MmsConfig.loadMmsSettings
I/Babel   ( 6049): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6049): MmsConfig.loadFromDatabase
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,E/Babel   ( 6049): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6049): MmsConfig.loadFromResources
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6049): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6049): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6049): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6049): App launched.
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/QCamera2Factory(  291): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  291): getCameraInfo: X
,W/QCamera2Factory(  291): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  291): getCameraInfo: X
,W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6049): Unsupported mime audio/evrc
,W/AudioCapabilities( 6049): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6049): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6049): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6049): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6049): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6049): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6049): Unsupported mime audio/evrc
,W/VideoCapabilities( 6049): Unsupported mime video/wvc1
,W/VideoCapabilities( 6049): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6049): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6049): Unsupported mime video/wvc1
,W/VideoCapabilities( 6049): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6049): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6049): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6049): Unsupported mime video/mp43
,W/VideoCapabilities( 6049): Unsupported mime video/sorenson
,W/VideoCapabilities( 6049): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6049): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6049): Creating RTCS
,I/Babel   ( 6049): Destroying RTCS
,I/ActivityManager( 1021): Killing 5583:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5583/cgroup.procs: No such file or directory
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  303): DCD OFF
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1021): waitForAlarm result :4
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5622): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 30431(1703KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.440ms total 154.189ms
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5622): Thread-957(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5622): Thread-957(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5622): Thread-957(ApacheHTTPLog):isShipBuild true
I/System.out( 5622): Thread-957(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5622): Thread-957(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  282): uids 10028
D/EnterpriseController(  282): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5622): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5622, getuid(): 10028,
,I/qtaguid ( 5622): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5622, getuid(): 10028
,I/qtaguid ( 5622): Untagging socket 44
,I/System.out( 5622): Thread-957 calls detatch()
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5622): Thread-958(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5622): Thread-958(ApacheHTTPLog):isShipBuild true
,I/System.out( 5622): Thread-958(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5622): Thread-958(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5622): Untagging socket 44
,I/qtaguid ( 5622): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5622): Untagging socket 44 failed errno=-22,
W/NetworkManagementSocketTagger( 5622): untagSocket(44) failed with errno -22
I/System.out( 5622): Thread-958 calls detatch()
,D/Finsky  ( 5622): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1],
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6086 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,E/Zygote  ( 6086): MountEmulatedStorage()
I/libpersona( 6086): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6086): v2
I/libpersona( 6086): KNOX_SDCARD not a persona
,I/SELinux ( 6086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6086): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6086): TimaSignature is unavailable
,D/ActivityThread( 6086): Added TimaKeyStore provider
,I/System.out( 5622): Thread-957(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5622): Thread-957(ApacheHTTPLog):isShipBuild true
I/System.out( 5622): Thread-957(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5622): Thread-957(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/art     (  323): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 716us total 42.712ms
,W/ResourcesManager( 6086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 760us total 18.109ms,
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.029ms,
,I/MultiDex( 6086): VM with version 2.1.0 has multidex support
I/MultiDex( 6086): install
,I/MultiDex( 6086): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5622): Untagging socket 44
,I/qtaguid ( 5622): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5622): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5622): untagSocket(44) failed with errno -22
I/System.out( 5622): Thread-957 calls detatch()
,W/ActivityThread( 6086): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6086): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d017feb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6086): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1021): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1,
I/splitIntent( 1021): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1021): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6086): Reading stored module config
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1884): callingUid 10012, callindPid: 1884
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1884): [254] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 6086): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2038): Restart initialization of location
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1884): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6086): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1884): No location to return for getLastLocation()
,W/FusedLocationProvider( 1884): location=null
,D/CAR.SERVICE( 6086): Connecting to CarCallService...
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6086): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6086): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6086): Creating a new PhoneAdapter instance
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6086): setListener: com.google.android.gms.car.dn@c36e3b6
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6086): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6086): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6086): Package validated; name: com.android.vending
,V/Finsky  ( 5622): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5622): Thread-958(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 5622): Thread-958(ApacheHTTPLog):isShipBuild true
I/System.out( 5622): Thread-958(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5622): Thread-958(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PackageManager( 1021): [MSG] MCS_UNBIND
,I/qtaguid ( 5622): Untagging socket 44
,I/qtaguid ( 5622): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5622): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5622): untagSocket(44) failed with errno -22
I/System.out( 5622): Thread-958 calls detatch()
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{1a26ad45 u0 com.samsung.android.MtpApplication/.MtpService}
,W/ResourcesManager( 5622): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5622): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5622): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1021): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5622): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,V/AlarmManager( 1021): waitForAlarm result :4
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1884): client connected with version: 8296000
,D/Finsky  ( 5622): [980] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5622): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5622): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 5622): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5622): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5622): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5622): (HTTPLog)-Thread-968-186114465: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5622): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  282): uids 10028
D/EnterpriseController(  282): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5622): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  303): DCD OFF
,I/ActivityManager( 1021): Killing 5038:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 5469:com.samsung.aasaservice/1000 (adj 15): empty #32
,W/libprocessgroup( 1021): failed to open /acct/uid_10044/pid_5038/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5469/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1021): SIOP:: AP = 350
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SensorService( 1021): [SO] 0.019 0.077 10.056,
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  303): DCD OFF,
,D/PowerManagerService( 1021): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1021): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1021): lcd : 1 +
D/DisplayPowerController( 1021): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
,D/lights  ( 1021): lcd : 1 -
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1021): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{217d2b4e u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/CAR.SERVICE( 6086): mConnectedToCar = false, abort
,E/ActivityThread( 6086): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1aacd6de that was originally bound here
E/ActivityThread( 6086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1aacd6de that was originally bound here
E/ActivityThread( 6086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6086): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6086): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6086): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6086): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6086): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6086): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6086): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6086): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6086): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6086): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33ad8f51 that was originally bound here
E/ActivityThread( 6086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33ad8f51 that was originally bound here
E/ActivityThread( 6086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6086): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6086): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6086): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6086): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6086): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6086): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6086): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6086): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6086): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6086): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1021): Unbind failed: could not find connection for android.os.BinderProxy@241d0f3a
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/Watchdog( 1021): !@Sync 2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,D/PowerManagerService( 1021): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1021): Nap time (uid 1000)...
D/PowerManagerService( 1021): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1021): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1021): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1021): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1021): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1021): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1021): WindowOrientationListener disabled
,D/PowerManagerService( 1021): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1021): handleSandman : startDream(true)
,E/PowerManagerService( 1021): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1021): Sleeping (uid 1000)...
D/PowerManagerService( 1021): [s] UserActivityState : 4 -> 0
D/SensorService( 1021): [SO] activate (ident=0xb8723398, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1021): unregisterListener ::   
,D/KeyguardViewMediator( 1174): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1174): *** KeyguardEffectView getInstanceIfExists ***
,D/PowerManagerService( 1021): Excessive delay in ColorFade : createSurface: 15ms
,I/Adreno-EGL( 1021): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1021): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1021): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1021): Local Branch: 
I/Adreno-EGL( 1021): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1021): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1021):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardEffectViewController( 1174): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1174): notifyScreenOffLocked
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1174): timeout : 5000
,D/PowerManagerService( 1021): Excessive delay in ColorFade : createEglContext: 36ms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (787 us)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ActivityThread( 3055): updateVisibility : ActivityRecord{303dc2c2 token=android.os.BinderProxy@269feec1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PowerManagerService( 1021): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 22ms
,D/KeyguardViewMediator( 1174): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1174): handleNotifyScreenOff
D/VolumePanel( 1174): onScreenTurnedOff()
D/VolumePanel( 1174): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1174): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1174): onScreenTurnedOff
,E/SmartFaceService( 1021): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1021): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1021): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1021): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1021): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1021): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1021): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SmartFaceService( 1021): fail to set sysfs 1
W/System.err( 1021): 	... 10 more
,D/InputMethodManagerService( 1021): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 1021):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1021):  handler : SCREEN_ON end
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/NotificationService( 1021): ACTION_SCREEN_ON
,D/PowerManagerService( 1021): Excessive delay in ColorFade : initGLShaders: 41ms
D/LightsService( 1021): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1021) 
D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PowerManagerService( 1021): Excessive delay in ColorFade prepare: 128ms
,D/DisplayPowerController( 1021): ColorFade: onAnimationStart
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
,V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  291): adev_set_parameters: exit
,W/IcingInternalCorpora( 2038): getNumBytesRead when not calculated.
,E/WifiNative-wlan0( 1021): do suspend false
,I/wpa_supplicant( 2076): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2076): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2076): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2076): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1021): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1021): Bridge Server is not available
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1021): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1021): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1444): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1444): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1021): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1769): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1021): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1021) 
,D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1021): turn on LED for fully charged
D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1021): write_int failed to open -1
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1021): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1021): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1021): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1021): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1021): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1021): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SmartFaceService( 1021): fail to set sysfs 0
W/System.err( 1021): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1021): 	... 10 more
,D/SSRM:n  ( 1021): SIOP:: AP = 330
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,D/MotionRecognitionService( 1021):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1769): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1021):  handler : SCREEN_OFF end 
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/NotificationService( 1021): ACTION_SCREEN_OFF
,D/LightsService( 1021): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1021) 
,D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/DisplayPowerState( 1021): !@ ColorFade entry
,D/DisplayPowerController( 1021): ColorFade: onAnimationEnd
,D/lights  ( 1021): lcd : 0 +
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
,I/BackgroundCompactionService( 1021): Schedule Type1 BGCompaction
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/lights  ( 1021): lcd : 0 -
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454992260000
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454970757543
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1021): Got set_interactive hint
,D/IpRemoteDisplayController( 1021): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1021): Bridge Server is not available
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DisplayManagerService( 1021): !@display_state: ON -> OFF
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb71d7690
I/DisplayManagerService( 1021): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager( 1021): Display changed displayId=0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
D/daemonapp( 1323): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/BatteryStatsDumper( 1021): In refreshStats isReason Screen ON/OFF: true
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,V/EmergencyMode( 1419): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1021): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1021): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1444): call the applyRouting
,D/StatusBar.NetworkController( 1174): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,I/BatteryStatsDumper( 1021): Screen bin #0: time=30305 power=0.17677916666666665,
I/BatteryStatsDumper( 1021): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1021): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1021): Screen bin #3: time=0 power=0.0
,I/BatteryStatsDumper( 1021): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1021): Previous Battery Level: 0 Current Level: 100 Delta: -100
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1940): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1021): SIOP:: AP = 330
,D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!,
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1021): Excessive delay in setPowerMode(): 241ms
D/PowerManagerService( 1021): Excessive delay in !@display_state: OFF: 242ms
,I/libsuspend( 1021): !@autosuspend_wakeup_count_enable
I/libsuspend( 1021): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1021): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 255ms
,I/PowerManagerService( 1021): [PWL] Off : 0s ago
I/PowerManagerService( 1021): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1021): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1021, ws=null) (elapsedTime=233)
,I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Message' (uid=1000, pid=1021, ws=null) (elapsedTime=88)
,I/BatteryStatsDumper( 1021): Writing to database completed
,E/WifiNative-wlan0( 1021): do suspend true
,D/SSRM:a  ( 1021): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1021): SettingsAirViewInfo:: 000000000
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2076): nl80211: Received scan results (4 BSSes)
,D/WifiP2pService( 1021): InactiveState{ what=147461 },
D/WifiP2pService( 1021): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1021): DefaultState{ what=147461 }
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1021): waitForAlarm result :4
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardViewMediator( 1174): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1174): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1174): *** Keyguard wallpaper service already unbounded
,D/Finsky  ( 5622): [970] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5622): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService( 1021): [PWL] Off : 5s ago
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,D/SSRM:n  ( 1021): SIOP:: AP = 300
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 15s ago,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2598): Disconnected process message: 10
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1021): !@Sync 3
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,V/AlarmManager( 1021): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1021): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1021): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1021): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,I/BackgroundCompactionService( 1021): onStart. jobID=801
,I/BackgroundCompactionService( 1021): onStart done. jobID=801
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,I/BackgroundCompactionService( 1021): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1021): compact_memory command done
,I/PowerManagerService( 1021): [PWL] Off : 30s ago
,I/PowerManagerService( 1021): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1021): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1021, ws=WorkSource{1000}) (elapsedTime=95)
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4,
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1884): Vacuum at: now=1454970791128 tag=VacuumService
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1884): Scheduling Phenotype for one-off execution 13077 seconds from now (1454970791573)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1884): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1884): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1884): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1021): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1884): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  282): uids 10012
D/EnterpriseController(  282): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1884): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1884): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1884, getuid(): 10012
,I/qtaguid ( 1884): Tagging socket 90 with tag 1000120100000000{268440065,0} for uid -1, pid: 1884, getuid(): 10012
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1884): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1884): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1884, getuid(): 10012
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1884): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1884): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1884, getuid(): 10012
,D/LocationManagerService( 1021): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1884): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1884): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1884, getuid(): 10012
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 5392): Not factory mode
D/FactoryTest( 5392): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5392): DRIVER_TIME_OUT 60s lapsed,
,D/MTPRx   ( 5392): still no open session command from host, so toast
W/ContextImpl( 5392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
I/Timeline( 5392): Timeline: Activity_launch_request id:com.android.settings time:115730
,W/ContextImpl( 5392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/ServiceManager(  349): Waiting for service AtCmdFwd...
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): mDVFSHelper.acquire(),
,V/ActivityManager( 1021): Display changed displayId=0
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 3055
,E/MTPRx   ( 5392): started activity for popup
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5392): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5392): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5392): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5392): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5392): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5392): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus entered window: 3055
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1021): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1d26f64a attribute=android.view.inputmethod.EditorInfo@fdd99bb, token = android.os.BinderProxy@30360f09
,D/SamsungIME( 1769): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5392): dev.kiessupport is : TRUE
,D/PhoneWindow( 5392): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5392): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 30
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3055): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3055): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3055): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3055): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3055): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityThread( 3055): updateVisibility : ActivityRecord{303dc2c2 token=android.os.BinderProxy@269feec1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 3055): Timeline: Activity_idle id: android.os.BinderProxy@269feec1 time:115996
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ActivityManager( 1021): mDVFSHelper.release(),
,E/SMD     (  303): DCD OFF,
,D/TaskPersister( 1021): removeObsoleteFile: deleting file=7_task.xml,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1021): [PWL] Off : 50s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 270,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 4
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 75s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1021): waitForAlarm result :8,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 5
,E/SMD     (  303): DCD OFF,
,I/ClearcutLoggerApiImpl( 1884): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 140s ago,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/Watchdog( 1021): !@Sync 7
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  303): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 9
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 225s ago,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1021): initializing...
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1021): !@Sync 10,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 11,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1021): [PWL] Off : 275s ago
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 12,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :8
V/AlarmManager( 1021): No more alarm at this time.nowELAPSED=403109 batch.start=798109
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1,
D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 13
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1021): [PWL] Off : 330s ago,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 14,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1021): waitForAlarm result :8,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 15,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1021): [PWL] Off : 390s ago,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/bootchecker(  346): bootchecker wake up!!,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 16,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 17,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,E/SMD     (  303): DCD OFF
,I/ServiceManager(  349): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1021): [PWL] Off : 455s ago,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1021): !@Sync 18,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,I/Atfwd_Daemon(  349): Stop the daemon....
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 19,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 525s ago,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 20,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 21,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 22,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 23,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 24,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1021): [PWL] Off : 680s ago,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 25,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/ActivityManager( 1021): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2038): Aggregate from 1454969623054 (log), 1454969623054 (data)
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 1021): !@Sync 26
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 27
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 765s ago,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 28
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 29,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 30
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 855s ago
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1021): waitForAlarm result :8
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 31,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 32,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 33,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 950s ago,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 34,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1021): !@Sync 35
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 36,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 37,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1050s ago,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1021): !@Sync 38,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 39,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1021): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1021): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 1021): Updating Usage Statistics in DB @ 1454971892943
I/ApplicationPolicy( 1021): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1021): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1021): ::isTableExists: Table exists 
,I/ApplicationUsage( 1021): Done Updating Usage Statistics in DB @ 1454971893316
,E/SMD     (  303): DCD OFF,
,E/Watchdog( 1021): !@Sync 40,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1155s ago,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/Watchdog( 1021): !@Sync 41,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  303): DCD OFF
,E/SMD     (  303): DCD OFF,
,E/SMD     (  303): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/AndroidRuntime( 6643): 
D/AndroidRuntime( 6643): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6643): CheckJNI is OFF
V/HeadsetService( 2598): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2598): Disconnected process message: 10
D/AndroidRuntime( 6643): readGMSProperty: start
D/AndroidRuntime( 6643): readGMSProperty: already setted!!
D/AndroidRuntime( 6643): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6643): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6643): readGMSProperty: end
D/AndroidRuntime( 6643): addProductProperty: start
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/AffinityControl( 6643): AffinityControl: registerfunction enter
D/AndroidRuntime( 6643): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{90310598}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1021): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
I/art     ( 5488): Explicit concurrent mark sweep GC freed 671(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 770us total 27.529ms
W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4768): Explicit concurrent mark sweep GC freed 15063(807KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 687us total 30.873ms
I/art     ( 5003): Explicit concurrent mark sweep GC freed 2304(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 716us total 23.839ms
I/art     ( 2038): Explicit concurrent mark sweep GC freed 5203(333KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 1.459ms total 66.973ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1769): mOCRHelper is null
W/GeofencerStateMachine( 1884): Ignoring removeGeofence because network location is disabled.
W/SQLiteConnectionPool( 2038): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.183: ( 3594): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 23:52:22 GMT+01:00 2016
D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
D/PersonaManager( 1444): isKioskContainerExistOnDevice
D/ActivityManager( 1021): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3594): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1021): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1021): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): onCreate()
E/Zygote  ( 6656): MountEmulatedStorage()
E/Zygote  ( 6656): v2
I/libpersona( 6656): KNOX_SDCARD checking this for 10094
I/libpersona( 6656): KNOX_SDCARD not a persona
I/SELinux ( 6656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3594): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6656 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3594): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SSRM:n  ( 1021): SIOP:: AP = 260
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1021): PackageReceiver onReceive()
I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1021): PackageRemovalReceiver::onReceive Enter
E/Zygote  ( 6670): MountEmulatedStorage()
E/Zygote  ( 6670): v2
I/libpersona( 6670): KNOX_SDCARD checking this for 10044
D/OTPFW   ( 1021): OtpDbHelper::getInstance New instance created
I/libpersona( 6670): KNOX_SDCARD not a persona
I/SELinux ( 6670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/OTPFW   ( 1021): DBIntegrity::getInstance - New instance created
I/SELinux ( 6670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1021): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6670 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/OTPFW   ( 1021): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1021): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1021): ProvisionData::getAllEntries Table is empty
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1021): uID is 10155
D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 6656): TimaSignature is unavailable
D/ActivityThread( 6656): Added TimaKeyStore provider
I/ActivityManager( 1021): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6680 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6680): MountEmulatedStorage()
E/Zygote  ( 6680): v2
I/libpersona( 6680): KNOX_SDCARD checking this for 10149
I/libpersona( 6680): KNOX_SDCARD not a persona
I/SELinux ( 6680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1444): isKioskContainerExistOnDevice
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10155
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
D/TimaKeyStoreProvider( 6670): TimaSignature is unavailable
D/TimaKeyStoreProvider( 6680): TimaSignature is unavailable
D/ActivityThread( 6670): Added TimaKeyStore provider
D/ActivityThread( 6680): Added TimaKeyStore provider
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
D/RegisteredServicesCache( 1444): empty dynamic service
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/AlarmManagerEXT( 1021): com.test.thalitest(10155) is removed.
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3594): KLMSIntentService(): onDestroy()
I/art     ( 1021): Explicit concurrent mark sweep GC freed 58141(6MB) AllocSpace objects, 242(3MB) LOS objects, 33% free, 28MB/42MB, paused 3.703ms total 272.348ms
W/ResourcesManager( 6670): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6670): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/elm:15183( 6656): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6656): ELMEngine.ELMEngine( context ).
D/elm:15183( 6656): MDMBridge.setEnterpriseBridge()
E/SQLiteLog( 4768): (284) automatic index on crash_info_summary(package_name_touched)
D/ActivityManager( 1021): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6656): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/art     ( 4768): Explicit concurrent mark sweep GC freed 995(48KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.038ms total 54.069ms
D/elm:15183( 6656): ElmAgentService : onCreate()
D/elm:15183( 6656): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6656): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6656): MDMBridge.getInstance()
D/elm:15183( 6656): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6656): MDMBridge.getAllLicenseInfoFromSDK()
D/PackageManager( 1021): delete codoeFile: 
E/Zygote  ( 6703): MountEmulatedStorage()
E/Zygote  ( 6703): v2
I/libpersona( 6703): KNOX_SDCARD checking this for 1000
I/libpersona( 6703): KNOX_SDCARD not a persona
I/SELinux ( 6703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/AASA_removePackage( 1021): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/ActivityManager( 1021): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6703 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/PackageManager( 1021): result of delete: 1{90310598}
I/SELinux ( 6703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ThemeInfoUtil( 6680): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6680): isCurrentFestival = false
E/SELinux ( 6703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/TimaKeyStoreProvider( 6703): TimaSignature is unavailable
D/ActivityThread( 6703): Added TimaKeyStore provider
I/TapandpayWidget:TapandpayAppWidgetProvider( 5738): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5738): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5738): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5738): Widget is not attached.
D/AndroidRuntime( 6643): Shutting down VM
D/BadgeProvider( 5871): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5871): sendNotify, [notify] : null
D/BadgeProvider( 5871): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5871): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5871): update, [UpdateCount] : 1
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/AASAservice-UpdateReceiver( 6703): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/ContextImpl( 5139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
E/Zygote  ( 6721): MountEmulatedStorage()
E/Zygote  ( 6721): v2
I/libpersona( 6721): KNOX_SDCARD checking this for 10160
I/libpersona( 6721): KNOX_SDCARD not a persona
W/System.err( 6703): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6703): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
I/ActivityManager( 1021): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6721 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
W/System.err( 6703): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6703): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6703): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6703): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6703): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6703): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6703): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6703): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6703): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6703): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6703): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SELinux ( 6721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/elm:15183( 6656): ElmAgentService : onDestroy().
I/SELinux ( 6721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6721): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 5509:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/TimaKeyStoreProvider( 6721): TimaSignature is unavailable
D/ActivityThread( 6721): Added TimaKeyStore provider
I/PCWCLIENTTRACE_PushUtil( 5704): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5704): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5704): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5704): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/RCPManager( 5567):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021): queryAllProviders():  providerCallBack is not register for 0
W/ResourcesManager( 6721): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5534): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/[0]UMC:UMCContentProvider( 6721): @onCreate
E/Zygote  ( 6739): MountEmulatedStorage()
I/libpersona( 6739): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6739): v2
I/libpersona( 6739): KNOX_SDCARD not a persona
I/SELinux ( 6739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1021): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6739 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6739): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 5723:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 6750): MountEmulatedStorage()
E/Zygote  ( 6750): v2
I/libpersona( 6750): KNOX_SDCARD checking this for 1000
I/libpersona( 6750): KNOX_SDCARD not a persona
I/SELinux ( 6750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1021): Killing 5755:com.policydm/1000 (adj 15): empty #31
E/SELinux ( 6750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:Core( 6721): onCreate(): 
D/[0]UMC:Core( 6721): @isManagedProfileUser
D/[0]UMC:Core( 6721): userId: 0
D/TimaKeyStoreProvider( 6739): TimaSignature is unavailable
D/ActivityThread( 6739): Added TimaKeyStore provider
D/[0]UMC:Core( 6721): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6721): userInfo.isManagedProfile() : false
W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6750): TimaSignature is unavailable
D/ActivityThread( 6750): Added TimaKeyStore provider
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/NearbySource( 6670): Nearby Source Create!
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/NearbyContext( 6670): Nearby Context Create!
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/[0]UMC:DeviceInfo( 6721): USA==US==
E/SMD     (  303): DCD OFF
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/art     ( 6643): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 5534): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ResourcesManager( 5534): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1021): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/ActivityManager( 1021): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/SPPClientService( 6739): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6739): [PushClientApplication] Push log off : This is Ship build version
E/Zygote  ( 6772): MountEmulatedStorage()
I/libpersona( 6772): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6772): v2
I/libpersona( 6772): KNOX_SDCARD not a persona
I/SELinux ( 6772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6772 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/SPPClientService( 6739): PushLog.txt file is not deleted.
D/SPPClientService( 6739): PushLog.txt file is not deleted.
D/SPPClientService( 6739): ============PushLog. stop!
W/ContextImpl( 6670): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6670): Samsung link source created
D/TimaKeyStoreProvider( 6772): TimaSignature is unavailable
W/ResourcesManager( 5534): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityThread( 6772): Added TimaKeyStore provider
W/ResourcesManager( 5534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 5951): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5951): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1021): Killing 5789:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/ActivityManager( 1021): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/ActivityManager( 1021): Killing 5681:com.android.mms/u0a46 (adj 15): empty #31
W/ResourcesManager( 5534): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/USER_AGENT( 6721): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/[0]UMC:AdminManager( 6721): init - start
W/ResourcesManager( 5534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityManager( 1021): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsPackageEventListener( 6772): Received: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 5534): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 6772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1021): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 6772): Enter Oncreate
D/AcmsServiceMonitor( 6772): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6772): creating AcmsCore
D/AcmsCore( 6772): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6772): AcmsCore
D/AcmsCore( 6772): init

```
