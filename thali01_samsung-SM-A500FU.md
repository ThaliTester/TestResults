#### Test 586024278176cca_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/Zygote  ( 5216): MountEmulatedStorage()
E/Zygote  ( 5216): v2
I/SELinux ( 5216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
--------- beginning of system
I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5216 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5216): KNOX_SDCARD checking this for 10101
I/libpersona( 5216): KNOX_SDCARD not a persona
I/SELinux ( 5216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5216): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5216): TimaSignature is unavailable
D/ActivityThread( 5216): Added TimaKeyStore provider
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4142/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_4721/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5216): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5216): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5216): Observing account changes for notifications
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5216): Error finding the version of the Email provider.....
E/Gmail   ( 5216): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5216): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5216): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5216): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5216): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5216): We do not support migrating this version of the Email provider.
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 4255:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/Gmail   ( 5216): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5253 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5253): MountEmulatedStorage()
E/Zygote  ( 5253): v2
I/libpersona( 5253): KNOX_SDCARD checking this for 10033
I/libpersona( 5253): KNOX_SDCARD not a persona
I/SELinux ( 5253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 5253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5253): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5253): TimaSignature is unavailable
D/ActivityThread( 5253): Added TimaKeyStore provider
E/SQLiteLog( 5216): (283) recovered 72 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup( 1018): failed to open /acct/uid_10125/pid_4255/cgroup.procs: No such file or directory
W/ResourcesManager( 5253): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/File    ( 5216): fail readDirectory() errno=2
W/ResourcesManager( 5253): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Gmail   ( 5216): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5216): notifyAccountChanged
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5253): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5253): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5216): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5216): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5216): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5216): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5216): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 4537:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/GCM     ( 1869): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ServiceManager(  316): Waiting for service AtCmdFwd...
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5292): MountEmulatedStorage()
I/libpersona( 5292): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5292): v2
I/libpersona( 5292): KNOX_SDCARD not a persona
I/SELinux ( 5292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5292 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_4537/cgroup.procs: No such file or directory
E/SELinux ( 5292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GCoreFlp( 1869): No location to return for getLastLocation()
W/FusedLocationProvider( 1869): location=null
D/TimaKeyStoreProvider( 5292): TimaSignature is unavailable
D/ActivityThread( 5292): Added TimaKeyStore provider
I/DIAGMON_AGENT( 5292): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/AndroidRuntime( 5290): 
D/AndroidRuntime( 5290): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5290): CheckJNI is OFF
D/AndroidRuntime( 5290): readGMSProperty: start
D/AndroidRuntime( 5290): readGMSProperty: already setted!!
D/AndroidRuntime( 5290): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5290): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5290): readGMSProperty: end
D/AndroidRuntime( 5290): addProductProperty: start
I/DIAGMON_AGENT( 5292): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 5292): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 5292): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3121): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/AffinityControl( 5290): AffinityControl: registerfunction enter
D/AndroidRuntime( 5290): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5290): Shutting down VM
W/ContextImpl( 4808): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5319): MountEmulatedStorage()
E/Zygote  ( 5319): v2
I/libpersona( 5319): KNOX_SDCARD checking this for 10104
I/libpersona( 5319): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5319 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 5319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5319): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5319): TimaSignature is unavailable
D/ActivityThread( 5319): Added TimaKeyStore provider
W/ResourcesManager( 5319): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 1018): Explicit concurrent mark sweep GC freed 207005(7MB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 46MB/62MB, paused 4.615ms total 293.935ms
W/art     ( 5290): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Babel   ( 5319): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5319): MmsConfig.loadMmsSettings
I/Babel   ( 5319): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5319): MmsConfig.loadFromDatabase
,E/Babel   ( 5319): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5319): MmsConfig.loadFromResources
,E/Babel   ( 5319): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5319): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5319): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5319): App launched.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 4196): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  284): getCameraInfo: X
,E/Zygote  ( 5344): MountEmulatedStorage(),
E/Zygote  ( 5344): v2
I/libpersona( 5344): KNOX_SDCARD checking this for 10035
I/libpersona( 5344): KNOX_SDCARD not a persona
,I/SELinux ( 5344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5344 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5344): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4765:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5344): TimaSignature is unavailable
,D/ActivityThread( 5344): Added TimaKeyStore provider
,W/VideoCapabilities( 5319): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5319): Unsupported mime audio/evrc
,W/AudioCapabilities( 5319): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5319): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5319): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5319): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5319): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5319): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5319): Unsupported mime audio/evrc
,W/VideoCapabilities( 5319): Unsupported mime video/wvc1
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5319): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5319): Unsupported mime video/wvc1
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv
,E/SPPClientService( 5344): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5344): [PushClientApplication] Push log off : This is Ship build version
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5319): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5319): Unsupported mime video/mp43
,W/VideoCapabilities( 5319): Unsupported mime video/sorenson
,D/SPPClientService( 5344): PushLog.txt file is not deleted.
,D/SPPClientService( 5344): PushLog.txt file is not deleted.
D/SPPClientService( 5344): ============PushLog. stop!
,W/VideoCapabilities( 5319): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5319): Unsupported profile 4 for video/mp4v-es
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_4765/cgroup.procs: No such file or directory
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/art     ( 1018): Suspending all threads took: 10.470ms,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5364): MountEmulatedStorage()
,I/libpersona( 5364): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5364): v2
I/libpersona( 5364): KNOX_SDCARD not a persona
I/SELinux ( 5364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5364 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4354:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/SELinux ( 5364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1018): Background sticky concurrent mark sweep GC freed 48156(1885KB) AllocSpace objects, 16(7MB) LOS objects, 13% free, 54MB/62MB, paused 15.115ms total 127.193ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 23.790ms
,I/Babel   ( 5319): Creating RTCS
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.684ms
,D/TimaKeyStoreProvider( 5364): TimaSignature is unavailable
D/ActivityThread( 5364): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 16.883ms
,I/Babel   ( 5319): Destroying RTCS
,I/ActivityManager( 1018): Killing 4334:com.android.calendar/u0a135 (adj 15): empty #31
,E/SPPClientService( 5364): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5364): [PushClientApplication] Push log off : This is Ship build version
E/LNoti   ( 5364): [PhoneStatusChangeReceiver] This device doesn't register yet.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SPPClientService( 5364): PushLog.txt file is not deleted.
D/SPPClientService( 5364): PushLog.txt file is not deleted.
D/SPPClientService( 5364): ============PushLog. stop!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_4354/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_4334/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5386): MountEmulatedStorage()
E/Zygote  ( 5386): v2
I/libpersona( 5386): KNOX_SDCARD checking this for 10142
I/libpersona( 5386): KNOX_SDCARD not a persona
I/SELinux ( 5386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5386 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Killing 4487:com.samsung.android.securitylogagent/1000 (adj 15): empty #31,
E/SELinux ( 5386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5386): TimaSignature is unavailable
,D/ActivityThread( 5386): Added TimaKeyStore provider
,V/TaskCloserActivity( 5386): TaskCloserActivity enter()
,V/TaskCloserActivity( 5386): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5401): MountEmulatedStorage(),
E/Zygote  ( 5401): v2
I/libpersona( 5401): KNOX_SDCARD checking this for 10135
I/libpersona( 5401): KNOX_SDCARD not a persona
I/SELinux ( 5401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5401 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 5401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4281:com.osp.app.signin/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5401): TimaSignature is unavailable
,D/ActivityThread( 5401): Added TimaKeyStore provider
,W/ResourcesManager( 5401): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5401): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4487/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_4281/cgroup.procs: No such file or directory
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5424): MountEmulatedStorage(),
I/libpersona( 5424): KNOX_SDCARD checking this for 10042
E/Zygote  ( 5424): v2
I/libpersona( 5424): KNOX_SDCARD not a persona
I/SELinux ( 5424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5424 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5424): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4783:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5424): TimaSignature is unavailable
,D/ActivityThread( 5424): Added TimaKeyStore provider
,W/ResourcesManager( 5424): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5424): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1018): failed to open /acct/uid_10157/pid_4783/cgroup.procs: No such file or directory
I/art     ( 1018): Background partial concurrent mark sweep GC freed 382501(21MB) AllocSpace objects, 3(3MB) LOS objects, 27% free, 43MB/59MB, paused 3.944ms total 255.690ms
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/PackageManager( 1018): verifying app can be installed or not
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false,
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
,D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
,E/SQLiteLog( 5424): (284) automatic index on view_events(_id)
,E/Zygote  ( 5442): MountEmulatedStorage()
E/Zygote  ( 5442): v2
I/libpersona( 5442): KNOX_SDCARD checking this for 1000
I/libpersona( 5442): KNOX_SDCARD not a persona
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  enabled true
I/SELinux ( 5442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AASAInstall( 1018): ship mode
,I/SELinux ( 5442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
E/SELinux ( 5442): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CalendarAlarmManager( 5424): sys current time:1454934982415
,D/CalendarAlarmManager( 5424): reminder amount:0
,D/TimaKeyStoreProvider( 5442): TimaSignature is unavailable
,D/ActivityThread( 5442): Added TimaKeyStore provider
,E/MTPRx   ( 5442): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 5442): sealedState: false
V/MTPRx   ( 5442): sealedUsbMassStorageState: false
E/MTPRx   ( 5442): check value of boot_completed is1
E/MTPRx   ( 5442): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5442): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5442): Status for mount/Unmount :removed
,E/MTPRx   ( 5442): SDcard is not available
,W/MTPRx   ( 5442): value of connected istrue
,W/MTPRx   ( 5442): value of configured istrue
W/MTPRx   ( 5442): value of mtpEnabled istrue
,W/MTPRx   ( 5442): value of ptpEnabled isfalse
,E/MTPRx   ( 5442): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5442): mFirstTime: false
,D/        ( 5442): MTP: reading debug level property
,E/MTPJNIInterface( 5442): Getting CryptionKey from JAVA
,E/MTPRx   ( 5442): currentUserId is 0
,E/MTPRx   ( 5442): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5442): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5442): is_Privatemode is NOT 1
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/SecContentProvider( 1018): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5442): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MTPRx   ( 5442): else part ... so first time!!!
,E/MTPPlaObsrvr( 5442): inside setContext()
E/MTPPlaObsrvr( 5442):  inside createplafiles
,E/MTPPlaObsrvr( 5442): playlist count is0
E/MTPPlaObsrvr( 5442):  inside try branch createplafiles
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
E/MTPPlaObsrvr( 5442):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5442): Inside registerContentObserver
,E/MtpAdbObserver( 5442): inside setContext()
,E/MtpAdbObserver( 5442): Inside registerContentObserver
,W/Settings( 5442): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,V/MtpMediaDBManager( 5442): inside deleteAllDB
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5442): onCreate.
,V/MtpMediaDBManager( 5442): inside Thread updateDB
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpMediaDBManager( 5442): count : 27
,D/MediaScannerReceiver( 1227): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/MtpService( 5442): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5442): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5442): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5442): onStartCommand.
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
W/MTPRx   ( 5442): calling native method
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
E/MTPJNIInterface( 5442): < MTP > Registering BroadCast receiver :::::
E/MtpService( 5442): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1333): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1333): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/MTPJNIInterface( 5442): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5442): noti = 10
E/MtpService( 5442): onStartCommand.
,W/MTPRx   ( 5442): calling native method
E/MTPRx   ( 5442): Checking the driver time out
E/MTPJNIInterface( 5442): noti = 2
D/        ( 5442): deleting sockets before message queue initialization
E/MtpService( 5442): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/        ( 5442): event handler thread is created, so set the flag
,E/MTPRx   ( 5442): called native method
E/MTPJNIInterface( 5442): setting Media scanner status0
E/MTPJNIInterface( 5442): After setting Media scanner status0
,W/MtpMediaDBManager( 5442): sending db update complete noti to stack
I/SettingSearch/SearchIntentReceiver( 1333): InitTitleDBThread start --> mDoingInitTitleDB : true
E/MTPJNIInterface( 5442): noti = 29
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,E/        ( 5442): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,W/MTPRx   ( 5442): notification from stack 1
E/MTPJNIInterface( 5442): Getting media scanner status0
,E/MTPJNIInterface( 5442): DeviceName is A5-1
,I/SettingSearch/SearchIntentReceiver( 1333): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1333): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/MTPJNIInterface( 5442): Status for mount/Unmount :removed
E/MTPJNIInterface( 5442): SDcard is not available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/        ( 5442): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5442): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/PolicyManagerBroadcastReceiver( 5164): This process will be killed soon.
,I/Process ( 5164): Sending signal. PID: 5164 SIG: 9
,E/MTPJNIInterface( 5442): Status for mount/Unmount :removed
E/MTPJNIInterface( 5442): SDcard is not available
,E/SQLiteLog( 5442): (21) API call with NULL database connection pointer
E/SQLiteLog( 5442): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5442): (21) API call with NULL database connection pointer
E/SQLiteLog( 5442): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5442): (21) API call with NULL database connection pointer
E/SQLiteLog( 5442): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5442): (21) API call with NULL database connection pointer
E/SQLiteLog( 5442): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5442): notification from stack 2
,D/        ( 5442): [mtp_init_device] Library open with 32 bits.
,D/        ( 5442): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5442): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
D/        ( 5442): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5442):  [sua_support_present:1287] returning false 
D/        ( 5442): *****Starting mtp_io()
,D/        ( 5442): [mtp_start_io] source_thread Creation 
W/MTPRx   ( 5442): notification from stack 3
,D/        ( 5442): [mtp_start_io] sink_thread Creation 
D/        ( 5442): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4322, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,E/SMD     (  289): DCD OFF
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/HeadsetStateMachine( 2624): Disconnected process message: 10
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ActivityManager( 1018): Process com.sec.android.app.wluc (pid 5164)(adj 15) has died(58,1189)
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1333): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,D/WearableService( 1869): callingUid 10012, callindPid: 1869
V/MediaScanner( 1227):  prescan time: 41ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 19ms (Caching mode: true), (makeEntry time: 11ms ~57%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 62ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,I/SettingSearch/SettingsSearchManager( 1333):  Infomation -> getItem size : 306
,D/MediaScannerService( 1227): !@done scanning volume external
,E/MTPJNIInterface( 5442): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/iu.UploadsManager( 1975): End new media; added: 0, uploading: 0, time: 82 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1333): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 1333): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1333): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/GmsUtils( 4526): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4526): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 4526): Conditions not met for autocaching.
,I/MusicLeanback( 4526): Stop autocaching.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1454): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1454): Media DB Scanner finished.
D/CscFactoryReceiver( 1454): start service to Set Ringtone
,D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1454): start service to Set Notification
,D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1454): start service to Set Alarmtone
,D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1454): onStart,
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.,
D/CscUpdateService( 1454): only ringtone update
D/CscUpdateService( 1454): onStart,
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1454): only notification update
D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.,
D/CscUpdateService( 1454): only alarmtone update
I/ActivityManager( 1018): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5484 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
E/CscParser( 1454): update(): xml file exist
E/Zygote  ( 5484): MountEmulatedStorage(),
,E/Zygote  ( 5484): v2,
I/libpersona( 5484): KNOX_SDCARD checking this for 10006
,I/libpersona( 5484): KNOX_SDCARD not a persona
,I/SELinux ( 5484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/CSCSettings( 1454): Setting Ringtones (type) : 4
D/CscParser( 1454): AlarmTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
,E/CscParser( 1454): update(): xml file exist
,I/SELinux ( 5484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/CscParser( 1454): update(): xml file exist
,W/CSCSettings( 1454): Setting Ringtones (type) : 1
,D/CscParser( 1454): RingTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5484): TimaSignature is unavailable
W/CSCSettings( 1454): Setting Ringtones (type) : 2
,D/CscParser( 1454): MessageTone: null
W/CSCSettings( 1454): 1. Tag_Str: null
D/ActivityThread( 5484): Added TimaKeyStore provider
,I/ThumbnailProvider( 5484): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5484): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5484): [START] processBroadcastIntent ...
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5060): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/GalleryCacheReady( 5060): handleMeidaScanFinish()
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 5060): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5060): query fail: 
,W/LocalSuggestAlbumData( 5060): query fail: 
,I/BroadcastProcessorService( 5484): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5484): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/BroadcastProcessorService( 5484): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5484): [START] DocumentService startDocumentService
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5484): DocumentService onCreate ... service
,D/PackageManager( 1018): Existing package
,D/PackageManager( 1018): Renaming /data/app/vmdl1471253952.tmp to /data/app/com.test.thalitest-1
,I/art     ( 1018): Background partial concurrent mark sweep GC freed 276073(15MB) AllocSpace objects, 3(5MB) LOS objects, 27% free, 42MB/58MB, paused 7.086ms total 248.637ms
,I/FaceInterface( 5060): startFaceScan() : waiting 5 sec
,D/PackageManager( 1018): installNewPackageLI: Package{3d0fcab8 com.test.thalitest}
,I/PackageManager( 1018): scanFileNewer : com.test.thalitest
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,D/BluetoothMediaBrowser( 2624):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,W/ContextImpl( 5484): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5484): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2624): no now playing list
D/BluetoothMediaBrowser( 2624):  getNowPlayingId now playing id : -1
,I/SettingSearch/SearchIntentReceiver( 1333): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1333): LOCALE_CHANGED call search setting db finish!!
,I/MediaStoreImporter( 4526): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{fab9ded u0 com.sec.bcservice/.BroadcastService}
,E/SystemInfo( 5484): [SIOP LEVEL] : 0
,I/DocumentService( 5484): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5484): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SettingSearch/SearchIntentReceiver( 1333): InitTitleDBThread start --> mDoingInitTitleDB : true
,E/File    ( 5484): fail readDirectory() errno=13
E/File    ( 5484): fail readDirectory() errno=13
,I/SystemInfo( 5484): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5484): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5484): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :51
E/DocumentService( 5484): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5484): [INDEX] Total time taken for each file :0
,I/DocumentService( 5484): DocumentService onDestroy start
,I/DocumentService( 5484): DocumentService onDestroy end
,I/DocumentService( 5484): DocumentService cleanupEverything start
,I/SettingSearch/SearchIntentReceiver( 1333): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1333): LOCALE_CHANGED call search setting db finish!!
,I/IndexParserThreadsManager( 5484): InterruptedException: null
,I/SystemInfo( 5484): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5484): DocumentService cleanupEverything end
,I/Process ( 5484): Sending signal. PID: 5484 SIG: 9
,I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1018): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/CalendarProvider2( 5424): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
I/ActivityManager( 1018): Process com.samsung.indexservice (pid 5484)(adj 9) has died(61,1189)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/dex2oat ( 5508): ----------------------------------------------------
I/dex2oat ( 5508): <SS>: S T A R T I N G . . .
I/dex2oat ( 5508): <SS>: going to process manifest for 32-bit...
,I/        ( 5508): SS_ART_lib [I]: Memory allocation: ctx
,I/        ( 5508): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5508): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5508): SS_ART_lib [I]: Memory allocation: ctx->libs
,I/        ( 5508): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5508): SS_ART_lib [I]: Parsing completed
I/        ( 5508): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5508): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5508): SS_ART_lib [I]: access to SS denied
I/        ( 5508): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5508): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5508): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5508): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5508): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5508): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5508): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/dex2oat ( 5508): dex2oat took 378.357ms (threads: 4)
,I/PackageManager( 1018): do mInstaller.dexopt : 0
,D/PackageManager( 1018): Time to dexopt: 0.454 seconds
,W/System.err( 1018): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1018): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1018): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1018): 	... 5 more
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 1018): New package installed
I/HarmonyEASService( 1018): Updating for all 1
,I/FaceInterface( 5060): startFaceScan() : going on
,D/FaceInterface( 5060): startFaceScan() is called.
,I/art     ( 1227): Explicit concurrent mark sweep GC freed 7118(502KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 788us total 32.448ms
,D/ContentApp( 1227): startScan() is called.
,D/FaceValue( 1227): mSleepTime: 800
D/FaceValue( 1227): mMaxThreadNum: 2
,W/FaceValue( 1227): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1227): startScan() is end.
D/PackageManager( 1018): doPostInstall for uid{10155}
,D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1227): isNeedToRestore : start
D/PackageManager( 1018): token 1 to BM for possible restore
V/BackupManagerService( 1018): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1018): Finishing install immediately
D/PackageManager( 1018): BM finishing package install for 1
,D/PackageManager( 1018): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/PageBuddyNotiSvc( 4221): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5520): MountEmulatedStorage(),
,E/Zygote  ( 5520): v2
I/libpersona( 5520): KNOX_SDCARD checking this for 1000
I/SELinux ( 5520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/libpersona( 5520): KNOX_SDCARD not a persona
,I/SELinux ( 5520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5520): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5520 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PackageManager( 1018): [MSG] POST_INSTALL: observer{214291652}
D/PackageManager( 1018):           Handling post-install for 1
,I/ActivityManager( 1018): Killing 4840:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,W/Settings( 1018): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/TimaKeyStoreProvider( 5520): TimaSignature is unavailable
,D/ActivityThread( 5520): Added TimaKeyStore provider
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1444): empty dynamic service
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/AASAservice-UpdateReceiver( 5520): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,E/SamsungIME( 1811): mOCRHelper is null
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1018): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5537): MountEmulatedStorage()
E/Zygote  ( 5537): v2
I/libpersona( 5537): KNOX_SDCARD checking this for 10057
I/libpersona( 5537): KNOX_SDCARD not a persona
,I/SELinux ( 5537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5537 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 5537): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4856:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,I/FaceInterface( 5060): startFaceScan() : going on,
D/FaceInterface( 5060): startFaceScan() is called.
,D/ContentApp( 1227): startScan() is called.
,D/ContentApp( 1227): startScan() is end.
,D/TimaKeyStoreProvider( 5537): TimaSignature is unavailable
,D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1227): isNeedToRestore : start
D/ActivityThread( 5537): Added TimaKeyStore provider
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1444): empty dynamic service
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 41174(3MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 3.257ms total 266.377ms
D/PackageManager( 1018): result of install: 1{214291652}
,I/PackageManager( 1018): Observer no longer exists.
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1018): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BackupManagerService( 1018): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1018): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/RCPManagerService( 1018): PackageReceiver onReceive()
D/RCPManagerService( 1018): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1018):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1018):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 1018): Removing schedule queue dupe of com.test.thalitest
,I/GCoreNlp( 1869): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1018): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
D/LocationManagerService( 1018): getProviders()=[passive]
,V/BackupManagerService( 1018): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/BackupManagerService( 1018): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d4306d4
,V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1018): packageInstalledForExternalStorage com.test.thalitest
,E/Zygote  ( 5561): MountEmulatedStorage()
E/Zygote  ( 5561): v2
I/libpersona( 5561): KNOX_SDCARD checking this for 10015
I/libpersona( 5561): KNOX_SDCARD not a persona
,I/SELinux ( 5561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5561 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
I/SELinux ( 5561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5561): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/TimaKeyStoreProvider( 5561): TimaSignature is unavailable
,D/ActivityThread( 5561): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Killing 4935:com.wsomacp/u0a25 (adj 15): empty #31
I/ActivityManager( 1018): Killing 4876:com.sec.esdk.elm/u0a94 (adj 15): empty #32
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1018): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4840/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_4856/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5319): Creating RTCS
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/Babel   ( 5319): Destroying RTCS
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GCoreNlp( 1869): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Zygote  ( 5583): MountEmulatedStorage()
E/Zygote  ( 5583): v2
I/libpersona( 5583): KNOX_SDCARD checking this for 10032
I/libpersona( 5583): KNOX_SDCARD not a persona
,I/SELinux ( 5583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5583 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5583): TimaSignature is unavailable
,D/ActivityThread( 5583): Added TimaKeyStore provider
,D/LocationProviderProxy( 1018): applying state to connected service
D/LocationProviderProxy( 1018): applying state to connected service
,W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_4876/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1018): applying state to connected service
W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_4935/cgroup.procs: No such file or directory
,I/FeatureConfig( 5583): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1018): Killing 4958:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 5060): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5583): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,I/UpdateIcingCorporaServi( 5537): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5601): MountEmulatedStorage()
W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Zygote  ( 5601): v2
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SELinux ( 5601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5601): KNOX_SDCARD checking this for 10069
I/libpersona( 5601): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5601 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5583): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5601): TimaSignature is unavailable
,D/ActivityThread( 5601): Added TimaKeyStore provider
,W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_4958/cgroup.procs: No such file or directory
,D/FileShare-Server( 5601): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5616): MountEmulatedStorage()
,I/libpersona( 5616): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5616): v2
I/libpersona( 5616): KNOX_SDCARD not a persona
I/SELinux ( 5616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5616 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5616): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5583): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 24.208ms
,D/TimaKeyStoreProvider( 5616): TimaSignature is unavailable
D/ActivityThread( 5616): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 5537): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,I/ActivityManager( 1018): Killing 4975:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,W/ResourcesManager( 5583): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.077ms
,W/ResourcesManager( 5583): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5616): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.040ms
,W/ResourcesManager( 5583): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5583): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5583): system/finder_cp/cpdata.xml file not found,
,E/Zygote  ( 5632): MountEmulatedStorage(),
I/libpersona( 5632): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5632): v2
I/libpersona( 5632): KNOX_SDCARD not a persona
I/SELinux ( 5632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5632 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5089:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 5632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5632): TimaSignature is unavailable
,D/ActivityThread( 5632): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5632): dbMigrationFlag : false
,D/ShortcutReceiver( 5632):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5649): MountEmulatedStorage()
E/Zygote  ( 5649): v2
I/libpersona( 5649): KNOX_SDCARD checking this for 10120
I/libpersona( 5649): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5649 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Killing 4824:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5649): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 5216): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 5649): TimaSignature is unavailable
,D/ActivityThread( 5649): Added TimaKeyStore provider,
,W/ResourcesManager( 5649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_5089/cgroup.procs: No such file or directory
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_10107/pid_4975/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_4824/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 5670): MountEmulatedStorage(),
I/libpersona( 5670): KNOX_SDCARD checking this for 10028
E/Zygote  ( 5670): v2
I/libpersona( 5670): KNOX_SDCARD not a persona
I/SELinux ( 5670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5670 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Waited long enough for: ServiceRecord{8ad7930 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/SELinux ( 5670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5670): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5670): TimaSignature is unavailable
,D/ActivityThread( 5670): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5131:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/Finsky  ( 5670): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5131/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,D/Finsky  ( 5670): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Settings( 5670): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5670): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5670): Skipping gmscore version check
,D/Finsky  ( 5670): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5670): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5670): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5670): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1975): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 1975): Null package name or gms related package.  Ignoreing.
,I/HomeSyncInstallReceiver( 1444): This pkg do not need BT addr. Do nothing
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5520): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5520): parseToken()
,W/System.err( 5520): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5520): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5520): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5520): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5520): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5520): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5520): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5520): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5520): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5520): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5520): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5520): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5520): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5520): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5520): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5520): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5520): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 5520): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5520): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5520): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5520): 	... 14 more
E/AASAservice-TokenRule( 5520): parseToken() : TokenFile is null
I/PackagesMonitor( 5060): PackagesMonitor onReceive :com.test.thalitest
E/AASAservice-UpdateReceiver( 5520): AASARuleUpdateResult() : Rule file is not exist.
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5715): MountEmulatedStorage()
E/Zygote  ( 5715): v2
I/libpersona( 5715): KNOX_SDCARD checking this for 10152
I/libpersona( 5715): KNOX_SDCARD not a persona
I/SELinux ( 5715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5715 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 5715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5715): TimaSignature is unavailable
D/ActivityThread( 5715): Added TimaKeyStore provider
E/Zygote  ( 5729): MountEmulatedStorage()
E/Zygote  ( 5729): v2
I/libpersona( 5729): KNOX_SDCARD checking this for 10046
I/libpersona( 5729): KNOX_SDCARD not a persona
I/SELinux ( 5729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5729 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 5729): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5729): TimaSignature is unavailable
,D/ActivityThread( 5729): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,W/ContextImpl( 5182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5715): (284) automatic index on shooting_modes(title_id)
,W/ResourcesManager( 5729): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5729): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5729): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5729): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5729): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5729): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 5752): MountEmulatedStorage()
E/Zygote  ( 5752): v2
,I/libpersona( 5752): KNOX_SDCARD checking this for 1000
I/SELinux ( 5752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5752): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 5752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5752): TimaSignature is unavailable
,D/ActivityThread( 5752): Added TimaKeyStore provider
,I/Icing   ( 1975): Storage manager: low false usage 1.73MB avail 10.16GB capacity 11.68GB
,E/Zygote  ( 5770): MountEmulatedStorage()
E/Zygote  ( 5770): v2
,I/libpersona( 5770): KNOX_SDCARD checking this for 1000
I/libpersona( 5770): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 5729): [start]    onCreate() consume time = 0.0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5770): TimaSignature is unavailable
,D/ActivityThread( 5770): Added TimaKeyStore provider
,E/Zygote  ( 5787): MountEmulatedStorage()
E/Zygote  ( 5787): v2
I/libpersona( 5787): KNOX_SDCARD checking this for 10156
I/libpersona( 5787): KNOX_SDCARD not a persona
,I/SELinux ( 5787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5787 uid=10156 gids={50156, 9997} abi=armeabi-v7a
E/SELinux ( 5787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5147:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
I/PCWCLIENTTRACE_LOG( 5752): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5752): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5752): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5752): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5752): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5752): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5752): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/TimaKeyStoreProvider( 5787): TimaSignature is unavailable
D/ActivityThread( 5787): Added TimaKeyStore provider
,W/ResourcesManager( 5770): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5804): MountEmulatedStorage()
,E/Zygote  ( 5804): v2
I/libpersona( 5804): KNOX_SDCARD checking this for 1000
I/libpersona( 5804): KNOX_SDCARD not a persona
I/SELinux ( 5804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5804): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5253:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5787): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5787): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 5787): Clear T&P info.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,D/TimaKeyStoreProvider( 5804): TimaSignature is unavailable
,D/ActivityThread( 5804): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5787): Widget is not attached.,
,E/Zygote  ( 5821): MountEmulatedStorage(),
E/Zygote  ( 5821): v2
,I/libpersona( 5821): KNOX_SDCARD checking this for 10091
I/libpersona( 5821): KNOX_SDCARD not a persona
I/SELinux ( 5821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5821 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5821): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5292:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10122/pid_5147/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5821): TimaSignature is unavailable
,D/ActivityThread( 5821): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5670): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,W/libprocessgroup( 1018): failed to open /acct/uid_10033/pid_5253/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5292/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5837): MountEmulatedStorage()
E/Zygote  ( 5837): v2
I/libpersona( 5837): KNOX_SDCARD checking this for 10010
I/libpersona( 5837): KNOX_SDCARD not a persona
,I/SELinux ( 5837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5837): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5837 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/art     (  305): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 667us total 29.283ms
,W/art     ( 5729): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 198.873ms
,D/TimaKeyStoreProvider( 5837): TimaSignature is unavailable
,D/ActivityThread( 5837): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 18.224ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.491ms
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/ActivityManager( 1018): Killing 4196:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/DBG_POLICYDM( 5804): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5804): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5804): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/PackageBroadcastService( 1975): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/DBG_POLICYDM( 5804): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1975): Loading module APK com.google.android.play.games
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Mms/ArtClassLoader( 5729): init before art
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/TelephonyPermission( 5729): start operation mode monitor
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5804): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5804): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/ResourcesManager( 5729): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,D/Mms/TelephonyPermission( 5729): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5729): isDefault true
,D/Mms/MmsApp( 5729): onCreate() com.android.mms
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5804): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4196/cgroup.procs: No such file or directory
,E/Zygote  ( 5866): MountEmulatedStorage()
E/Zygote  ( 5866): v2
I/libpersona( 5866): KNOX_SDCARD checking this for 10035
I/libpersona( 5866): KNOX_SDCARD not a persona
,I/SELinux ( 5866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5866 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5866): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5344:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5866): TimaSignature is unavailable
,D/ActivityThread( 5866): Added TimaKeyStore provider
,D/Mms/MmsApp( 5729): [start]    initCountryIso consume time = 534.980625
,D/CountryDetector( 1018): The first listener is added
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5344/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5804): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/Mms/MmsApp( 5729): [end]    initCountryIso consume time = 22.014063
D/Mms/MmsConfig( 5729): [start]    MmsConfig.init() consume time = 0.130156
,W/art     ( 1975): Suspending all threads took: 5.894ms
,I/DBG_POLICYDM( 5804): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5804): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/Mms/MmsConfig( 5729): before partial update
,E/DataBuffer( 1975): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d02a75d)
,D/Mms/MmsConfig( 5729): Load Resize quality : 80
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/EasySignUpManager_1.0.1( 5729): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5729): isAuth is false
,D/Mms/MmsConfig( 5729): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/TP/MmsSmsProvider( 1454): query,matched:2117, calling pid = 5729
,D/TP/MmsSmsProvider( 1454): match 2117:Elapsed time : 1.400 ms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 1975): updateResources: need to parse f{com.google.android.gms}
,E/PhotosPlugin( 5821): Loading PhotosPlugin
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,E/SPPClientService( 5866): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5866): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] ,
E/Zygote  ( 5887): MountEmulatedStorage()
E/Zygote  ( 5887): v2
I/libpersona( 5887): KNOX_SDCARD checking this for 10038
,I/libpersona( 5887): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/SELinux ( 5887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5887): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5887 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5364:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
I/DBG_POLICYDM( 5804): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
,D/SPPClientService( 5866): PushLog.txt file is not deleted.
D/SPPClientService( 5866): PushLog.txt file is not deleted.
D/SPPClientService( 5866): ============PushLog. stop!
,D/EasySignUpManager_1.0.1( 5729): isAuth is false
,D/EasySignUpManager_1.0.1( 5729): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5729): mps_code.dat does not exist
E/CscParser( 5729): customer_path =/system/csc/customer.xml
E/CscParser( 5729): fileName + /system/csc/customer.xml
,D/TimaKeyStoreProvider( 5887): TimaSignature is unavailable
,D/ActivityThread( 5887): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/08/13:36:26
,I/DBG_POLICYDM( 5804): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,W/ResourcesManager( 5887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5804): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5804): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5804): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5804): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5804): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5804): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,E/CscParser( 5729): mps_code.dat does not exist
E/CscParser( 5729): customer_path =/system/csc/customer.xml
E/CscParser( 5729): fileName + /system/csc/customer.xml
,D/CscParser( 5729): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5729):  enable multiwindow = true
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/Mms/MessageUtils( 5729): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5729): updateCountryIso : update country iso info 
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5364/cgroup.procs: No such file or directory
,D/Mms/MmsConfig( 5729): [end]    init() consume time = 177.192448
,D/Mms/Contact( 5729): [start]    init() consume time = 5.171302
,D/TP/MmsSmsProvider( 1454): query,matched:13, calling pid = 5729
,D/TP/MmsSmsProvider( 1454): match 13:Elapsed time : 1.971 ms
,D/Mms/Contact( 5729): [end]    init consume time = 23.689375
,D/Mms/DraftCache( 5729): [start]    rebuildCache consume time = 5.892552
,D/TP/MmsSmsProvider( 1454): query,matched:12, calling pid = 5729
,D/Mms/MethodReflector( 5729): getSubId is called
D/Mms/TelephonyUtils( 5729): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1454): match 12:Elapsed time : 2.512 ms
,D/Mms/MethodReflector( 5729): getTelephonyProperty is called
D/Mms/DownloadManager( 5729): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5729): auto download without roaming -> true
D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 5729): getSubId is called
,D/Mms/MethodReflector( 5729): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5729): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5729): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 5729): getTelephonyProperty is called
D/Mms/DownloadManager( 5729): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5729): auto download without roaming -> true
D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5729): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5729): mAutoDownload ------> true
,D/Mms/DraftCache( 5729): [end]    rebuildCache consume time = 19.140677
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 205622(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.853ms total 198.546ms
,I/DBG_POLICYDM( 5804): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/ComposerPerformance( 5729): 1454934986905 ms / [DONE] Composer constructor
,E/CII     ( 5729): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5729): ReservationManager()
,I/Mms/ReservationManager( 5729): resetAfterConnected()
,D/TP/MmsSmsProvider( 1454): query,matched:7, calling pid = 5729
,D/TP/MmsSmsProvider( 1454): match 7:Elapsed time : 1.897 ms
,I/Mms/ReservationManager( 5729): getReservedSendMessageCount(): retMessageCount=0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Conversation( 5729): [start]    init() consume time = 142.531667
,D/TP/MmsSmsProvider( 1454): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1454): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1454): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1454): sUpgradeVersion = 0, db.getVersion() = 81
,D/Mms/MmsApp( 5729): [end]    onCreate() consume time = 9.624427
,D/TP/MmsSmsProvider( 1454): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
,D/Mms/Conversation( 5729): [end]    init consume time = 4.463489
,D/Mms/MessagingNotification( 5729): [start]    init() consume time = 2.938646
,D/Mms/DownloadManager( 5729): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5729): roaming ------> false, mSimSlot = 0
,D/Mms/MessagingNotification( 5729): [end]    init consume time = 3.589167
,D/Mms/MethodReflector( 5729): getSubId is called
D/Mms/TelephonyUtils( 5729): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5729): getTelephonyProperty is called
D/Mms/DownloadManager( 5729): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5729): auto download without roaming -> true
D/Mms/DownloadManager( 5729): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5729): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1454): query,matched:0, calling pid = 5729
,V/TP/MmsSmsProvider( 1454): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1454): match 0:Elapsed time : 2.461 ms
,D/Mms/Synchronizer( 5729): [start]    doSync consume time = 7.849219
,D/Mms/FreeMessageStatusReceiver( 5729): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/Mms/SpamFilter( 5729): [start]    SpamFilter fill() begin consume time = 1.066927
,D/ActivityManager( 1018): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
,D/TP/MmsSmsProvider( 1454): update, matched:300, calling pid = 5729
,V/TP/MmsSmsProvider( 1454): syncDBData start
,V/TP/MmsSmsProvider( 1454): syncDBData sms end
,V/TP/MmsSmsProvider( 1454): syncDBData mms end
,V/TP/MmsSmsProvider( 1454): syncDBData end
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,D/TP/MmsSmsProvider( 1454): query,matched:400, calling pid = 5729
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 5729): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5729): onHandleIntent: ACTION_PACKAGE_ADDED
D/Mms/ArtClassLoader( 5729): init [DONE] art
,E/Zygote  ( 5914): MountEmulatedStorage()
,I/libpersona( 5914): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5914): v2
I/libpersona( 5914): KNOX_SDCARD not a persona
I/SELinux ( 5914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5914): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5914 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/Mms/SpamFilter( 5729): [end]    SpamFilter fill() finished consume time = 39.541823
,D/Mms/Synchronizer( 5729): [end]    doSync consume time = 0.984791
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.gass from APK com.google.android.gms
,E/Zygote  ( 5931): MountEmulatedStorage()
E/Zygote  ( 5931): v2
I/libpersona( 5931): KNOX_SDCARD checking this for 10072
I/libpersona( 5931): KNOX_SDCARD not a persona
,I/SELinux ( 5931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5931): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5914): TimaSignature is unavailable
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5931 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityThread( 5914): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5931): TimaSignature is unavailable
,D/ActivityThread( 5931): Added TimaKeyStore provider
,W/ResourcesManager( 5914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5386:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31,
,D/BadgeProvider( 5931): onCreate
,D/BadgeProvider( 5931): DatabaseHelper
,D/Mms/MessagingNotification( 5729): checkBadgeCount unreadCount=0 badgeCount=0
,D/AsyncTaskServiceImpl( 1975): Submit a task: k
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1454): query,matched:26, calling pid = 5729,
,D/TP/SmsProvider( 1454): match 26:Elapsed time : 3.680 ms
,I/ActivityManager( 1018): Killing 5424:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/TP/MmsSmsProvider( 1454): query,matched:6, calling pid = 5729
,D/TP/MmsSmsProvider( 1454): match 6:Elapsed time : 0.818 ms
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5947): MountEmulatedStorage(),
I/libpersona( 5947): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5947): v2
I/libpersona( 5947): KNOX_SDCARD not a persona
,I/SELinux ( 5947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/SELinux ( 5947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5947 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/k       ( 1975): Processing package: com.test.thalitest
,D/TimaKeyStoreProvider( 5947): TimaSignature is unavailable
,D/ActivityThread( 5947): Added TimaKeyStore provider
,D/GassUtils( 1975): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1975): Found info for package com.test.thalitest in db.
,W/ResourcesManager( 5947): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5197:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1975): Using Auth Proxy for data requests.
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
,D/MyFiles ( 5914): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_5386/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5947): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5424/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5197/cgroup.procs: No such file or directory
,I/TactileAssist( 1018): enable value -1
,I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
,I/TactileAssist( 1018): saveAppList value true
,I/TactileAssist( 1018): List of disabled apps :
,D/Mms/Omacp( 5729): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/installd(  285): system dir 0 : /system/app/
E/installd(  285): system dir 1 : /system/priv-app/
E/installd(  285): system dir 2 : /vendor/app/
E/installd(  285): system dir 3 : /oem/app/
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,E/Zygote  ( 5971): MountEmulatedStorage()
I/libpersona( 5971): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5971): v2
I/libpersona( 5971): KNOX_SDCARD not a persona
I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5971 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/SELinux ( 5971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
E/SELinux ( 5971): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/TimaKeyStoreProvider( 5971): TimaSignature is unavailable
,D/ActivityThread( 5971): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5947): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,W/ResourcesManager( 5971): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1975): Using Auth Proxy for data requests.
,D/Compatibility( 5971): onReceive() it will make start service
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/BaseAppContext( 1975): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5887): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5887): isLoggable:: SL_DEBUG_EXIST = false
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/BaseAppContext( 1975): Using Auth Proxy for data requests.
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 5804): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/Compatibility( 5971): onHandleIntent()
,D/Compatibility( 5971): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,I/UpdateIcingCorporaServi( 5537): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 5971): found: 2
,I/DBG_POLICYDM( 5804): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,W/BaseAppContext( 1975): Using Auth Proxy for data requests.
,D/Compatibility( 5971): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5971): skipping ResolveInfo{306b95ec com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5971): considering ResolveInfo{604edb5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5971): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5971): enabling receiver ResolveInfo{1f848c4a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5971): enabling receiver ResolveInfo{196a77bb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5971): enabling receiver ResolveInfo{187224d8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5971): enabling receiver ResolveInfo{6e3b031 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5971): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,V/AlarmManager( 1018): waitForAlarm result :4
,I/PeopleDatabaseHelper( 1975): cleanUpNonGplusAccounts done.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5887): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,I/UpdateIcingCorporaServi( 5537): UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,I/ActivityManager( 1018): Killing 5216:com.google.android.gm/u0a101 (adj 15): empty #31
,W/SQLiteConnectionPool( 1975): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5887): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/Icing   ( 1975): Internal init done: storage state 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 3566(141KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 781us total 36.635ms
,E/Zygote  ( 6000): MountEmulatedStorage()
E/Zygote  ( 6000): v2
I/libpersona( 6000): KNOX_SDCARD checking this for 10041
I/libpersona( 6000): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6000 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6000): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5216/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6000): TimaSignature is unavailable
,D/ActivityThread( 6000): Added TimaKeyStore provider
,I/Icing   ( 1975): Post-init done
,I/Icing   ( 1975): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 6000): [SSP] onCreated
,I/SA      ( 6000): [TPM] There is no property file
,I/ActivityManager( 1018): Killing 5045:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SA      ( 6000): [SCU] isHaveSA() - false
,I/SA      ( 6000): [TPM] getModelProperty : null
I/SA      ( 6000): [TPM] getCSCProperty : null
,I/SA      ( 6000): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6000): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6000): [DM] TFT FEATURE: false
,I/SA      ( 6000): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6000): [DM] init START
,I/SA      ( 6000): [DM] This device is not a Vodafone
,W/ResourceType( 6000): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ResourceType( 6000): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6000): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6000): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 6000): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6000): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6000): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_5045/cgroup.procs: No such file or directory
W/ResourceType( 6000): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6000): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 6000): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6000): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 6000): [SCU] isHaveSA() - false
I/SA      ( 6000): support phone number id : false
I/SA      ( 6000): [DM] Supports Ref Jpn : true
,I/SA      ( 6000): [DM] init END
I/SA      ( 6000): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SA      ( 6000): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4526:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5821): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1018): failed to open /acct/uid_10111/pid_4526/cgroup.procs: No such file or directory
,E/SQLiteLog( 5821): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6032): MountEmulatedStorage()
,E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD checking this for 10100
I/libpersona( 6032): KNOX_SDCARD not a persona
,I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6032 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4893:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5821): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
,D/ActivityThread( 6032): Added TimaKeyStore provider
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageIntentReceiver( 6032): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6032): Not GearManger package! 
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_4893/cgroup.procs: No such file or directory
,E/Zygote  ( 6054): MountEmulatedStorage()
,E/Zygote  ( 6054): v2
I/libpersona( 6054): KNOX_SDCARD checking this for 1000
I/libpersona( 6054): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/AccountFeatureHelper( 5821): Write apps_features disabled false
,I/FaceInterface( 5060): startFaceScan() : going on
D/FaceInterface( 5060): startFaceScan() is called.
,D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
,D/ContentApp( 1227): startScan() is called.
,D/ContentApp( 1227): startScan() is end.
,D/ContentApp( 1227): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1227): isNeedToRestore : start
,D/TimaKeyStoreProvider( 6054): TimaSignature is unavailable
,D/ActivityThread( 6054): Added TimaKeyStore provider
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6074): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6074): v2
I/libpersona( 6074): KNOX_SDCARD checking this for 1000
I/libpersona( 6074): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 5401:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 6074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6074): TimaSignature is unavailable
,D/ActivityThread( 6074): Added TimaKeyStore provider
,D/AcmsPackageEventListener( 6074): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/AcmsService( 6074): Enter Oncreate
,D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6074): creating AcmsCore
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/AcmsCore( 6074): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6074): AcmsCore
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsCore( 6074): init
D/AcmsCore( 6074): Looper handler is not null
D/AcmsCore( 6074): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 1
D/AcmsCore( 6074): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6074): onStartCommand
D/AcmsService( 6074): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6074): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 2
D/AcmsService( 6074): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6074): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 6074): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6074): AcmsRevocationMngr
,D/AcmsService( 6074): Inside handle Intent
D/AcmsService( 6074): App added - package name: com.test.thalitest
D/AcmsCore( 6074): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 3
D/AcmsCore( 6074): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6074): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 2
,W/GAV2    ( 5821): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_5401/cgroup.procs: No such file or directory
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5319:com.google.android.talk/u0a104 (adj 15): empty #31
,D/SensorService( 1018): [SO] 0.038 0.115 10.113
,W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_5319/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1018): SIOP:: AP = 390
,E/SMD     (  289): DCD OFF,
,I/Icing   ( 1975): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Mms/MmsApp( 5729):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5729): [start]    fillCache consume time = 1942.272916
,D/Mms/ComposeMessageFragment( 5729): fillCache, easy = false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Icing   ( 1975): Loaded CLD2 Version V2.0 - 20141016
,D/AbsListView( 5729): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5729): [end]    fillCache consume time = 83.118177
,I/Icing   ( 1975): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5601:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5601/cgroup.procs: No such file or directory
,I/CheckinService( 1975): Done disabling old GoogleServicesFramework version
,D/Mms/BubbleViewCache( 5729): fillCache bubble = 1
,D/AcmsKeyStoreHelper( 6074):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6074): Key Store exist
I/AcmsKeyStoreHelper( 6074): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6074):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6074): getKeyStoreForApplication success 
D/AcmsCore( 6074): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 1
D/AcmsCore( 6074): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6074): This is NOT a valid MirrorLink app
D/AcmsCore( 6074): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6074): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6074): getSvcCounter - Counter value: 0
,D/AcmsService( 6074): Enter onDestroy
I/AcmsService( 6074): cleanUp(): inside service clean up
D/AcmsCore( 6074): AcmsCore: inside DeInit
D/AcmsCore( 6074): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6074): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6074): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6074): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6074): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6074): getSvcCounter - Counter value: 0
D/AcmsService( 6074): killing acms process
I/Process ( 6074): Sending signal. PID: 6074 SIG: 9
,I/ActivityManager( 1018): Process ACMS.Process (pid 6074)(adj 0) has died(54,1206)
,I/DBG_POLICYDM( 5804): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5804): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/AlarmManager( 1018): waitForAlarm result :4
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/iu.UploadsManager( 1975): End new media; added: 0, uploading: 0, time: 51 ms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5670): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 29300(1600KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.405ms total 144.605ms
,I/System.out( 5670): Thread-963(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5670): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5670): Thread-963(ApacheHTTPLog):isShipBuild true
I/System.out( 5670): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5670): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): uids 10028
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5670): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5670, getuid(): 10028
,I/qtaguid ( 5670): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5670, getuid(): 10028
,I/qtaguid ( 5670): Untagging socket 44
,I/System.out( 5670): Thread-963 calls detatch()
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5670): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5670): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5670): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5670): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5670): Untagging socket 44
,I/qtaguid ( 5670): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5670): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5670): untagSocket(44) failed with errno -22
I/System.out( 5670): Thread-962 calls detatch()
,D/Finsky  ( 5670): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6105): MountEmulatedStorage()
E/Zygote  ( 6105): v2
I/libpersona( 6105): KNOX_SDCARD checking this for 10012
I/libpersona( 6105): KNOX_SDCARD not a persona
,I/SELinux ( 6105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6105): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6105 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  305): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 661us total 20.129ms
,D/TimaKeyStoreProvider( 6105): TimaSignature is unavailable
,D/ActivityThread( 6105): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 16.849ms,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6105): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 16.988ms
,I/System.out( 5670): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5670): Thread-963(ApacheHTTPLog):isShipBuild true
,I/System.out( 5670): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5670): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/MultiDex( 6105): VM with version 2.1.0 has multidex support
I/MultiDex( 6105): install
I/MultiDex( 6105): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6105): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{23c0697d u0 com.samsung.android.MtpApplication/.MtpService}
,I/qtaguid ( 5670): Untagging socket 44
,I/qtaguid ( 5670): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5670): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5670): untagSocket(44) failed with errno -22
I/System.out( 5670): Thread-963 calls detatch()
,W/ActivityThread( 6105): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6105): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e68bfb2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6105): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6105): Reading stored module config
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/WearableService( 1869): callingUid 10012, callindPid: 1869
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6105): Loading module com.google.android.gms.car from APK com.google.android.gms
,E/MDM     ( 1869): [259] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1869): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1975): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1869): No location to return for getLastLocation()
,W/FusedLocationProvider( 1869): location=null
D/NativeLibraryUtils( 6105): Install completed successfully. count=14 extracted=0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CAR.SERVICE( 6105): Connecting to CarCallService...
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6105): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6105): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6105): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6105): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6105): Creating a new PhoneAdapter instance
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6105): setListener: com.google.android.gms.car.dn@2bf3f229
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6105): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6105): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6105): Package validated; name: com.android.vending
,V/Finsky  ( 5670): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5670): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5670): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5670): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5670): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5670): Untagging socket 44
,I/qtaguid ( 5670): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5670): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5670): untagSocket(44) failed with errno -22
,I/System.out( 5670): Thread-962 calls detatch()
,W/ResourcesManager( 5670): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5670): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SSRM:n  ( 1018): SIOP:: AP = 350,
,W/ResourcesManager( 5670): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5670): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1869): client connected with version: 8296000
,D/Finsky  ( 5670): [984] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5670): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5670): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5670): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5670): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5670): (HTTPLog)-Static: isShipBuild true
I/System.out( 5670): (HTTPLog)-Thread-973-504100672: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5670): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10028
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5670): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 1018): Killing 5520:com.samsung.aasaservice/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 5632:com.sec.knox.foldercontainer/1000 (adj 15): empty #32
,D/SensorService( 1018): [SO] 0.019 0.077 10.075
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5632/cgroup.procs: No such file or directory,
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5520/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{2f530785 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1018): lcd : 1 +
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/CAR.SERVICE( 6105): mConnectedToCar = false, abort
,E/ActivityThread( 6105): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@195d75f1 that was originally bound here
E/ActivityThread( 6105): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@195d75f1 that was originally bound here
E/ActivityThread( 6105): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6105): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6105): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6105): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6105): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6105): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6105): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6105): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6105): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6105): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6105): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6105): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6105): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6105): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6105): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6105): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6105): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6105): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6105): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6105): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6105): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@20a2d3b0 that was originally bound here
E/ActivityThread( 6105): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@20a2d3b0 that was originally bound here
E/ActivityThread( 6105): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6105): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6105): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6105): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6105): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6105): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6105): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6105): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6105): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6105): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6105): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6105): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6105): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6105): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6105): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6105): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6105): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6105): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6105): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@258292f3
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8
,E/Watchdog( 1018): !@Sync 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1018): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
,D/SensorService( 1018): [SO] activate (ident=0xb79e7078, enabled=0)
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1018): Sleeping (uid 1000)...
,D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1018): unregisterListener ::   
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createSurface: 13ms
,I/Adreno-EGL( 1018): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1018): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1018): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1018): Local Branch: 
I/Adreno-EGL( 1018): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1018): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1018):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
,V/ActivityThread( 3121): updateVisibility : ActivityRecord{30a57b65 token=android.os.BinderProxy@19aa88e0 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,W/IcingInternalCorpora( 1975): getNumBytesRead when not calculated.
,D/KeyguardViewMediator( 1181): timeout : 5000
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
D/VolumePanel( 1181): onScreenTurnedOff()
,D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglContext: 43ms
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOff
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
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
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglSurface: 10ms
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (254 us)
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PanelView( 1181): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 23ms
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
,V/voice   (  284): voice_set_parameters: enter: screen_state=on
,V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,E/WifiNative-wlan0( 1018): do suspend false
,I/wpa_supplicant( 2077): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2077): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2077): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2077): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 31ms
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PowerManagerService( 1018): Excessive delay in ColorFade prepare: 128ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1444): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1444): call the applyRouting
,D/accuweather( 1733): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1733): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1811): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for charging
,E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
,W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
,W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,E/SmartFaceService( 1018): fail to set sysfs 0
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/PanelView( 1181): There is/are notification(s) 
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1306): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1811): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/NotificationService( 1018): ACTION_SCREEN_OFF
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1306): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1306): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1306): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1306): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
,V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2),
,D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  284): adev_set_parameters: exit
D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454956500000
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454935007605
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1306): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1306): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF,
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,E/daemonapp( 1306): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1419): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1444): call the applyRouting
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,D/accuweather( 1733): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1018): lcd : 0 +
,D/accuweather( 1733): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 0 Current Level: 100 Delta: -100
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb76b1690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/accuweather( 1733): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1733): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1733): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1941): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1733): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1733): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1733): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 257ms
,D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 257ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 268ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1018, ws=null) (elapsedTime=348)
,I/BatteryStatsDumper( 1018): Writing to database completed
,E/WifiNative-wlan0( 1018): do suspend true
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 2077): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1018): InactiveState{ what=147461 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1018): DefaultState{ what=147461 },
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1181): *** Keyguard wallpaper service already unbounded
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1018): turn on LED for fully charged
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1018): mCursor = null
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181
I/PowerManagerService( 1018): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1018): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): [s] UserActivityState : 0 -> 1
,V/KeyguardServiceDelegate( 1018): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2ce484d8)
,D/KeyguardViewMediator( 1181): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1181): notifyScreenOnLocked
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Display
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DisplayPowerController( 1018): Blocking screen on until initial contents have been drawn.
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/WindowOrientationListener( 1018): sensor enabled
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns),
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
,I/libsuspend( 1018): !@autosuspend_wakeup_count_disable
,D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable done
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/SurfaceFlinger(  258): Set power mode=2, type=0 flinger=0xb76b1690
,D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 2 on display: 0
,D/DisplayManagerService( 1018): !@display_state: OFF -> ON
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,V/ActivityManager( 1018): Display changed displayId=0
D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb7aa58e0, enabled=1)
D/SensorService( 1018): [SO] AR_init
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,V/ActivityManager( 1018): Display changed displayId=0
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1181): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1181): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
,E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false,
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 29
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,D/SensorService( 1018): [SO] currT = 86020106267, prevT = 80340078978, diff = 5680027289, [0.019 0.057 10.036]
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 29
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SamsungIME( 1811): showDlgMsgBox : false true true
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3121): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/NfcService( 1444): call the applyRouting
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1018): turn off LED
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	... 10 more
D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 2 on display 0
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 114ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: ON: 114ms
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : -1
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/KeyguardServiceDelegate( 1018): **** SHOWN CALLED ****
D/DisplayPowerController( 1018): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/StatusBarKeyguardViewManager( 1181): callback.onShown()
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
I/DisplayPowerController( 1018): Unblocked screen on after 150 ms
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/DisplayPowerState( 1018): !@ ColorFade exit
V/UserPresentBroadcastReceiver( 1869): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
D/BatteryMeterView( 1181): onDraw batteryColor : -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
I/SurfaceFlinger(  258): id=12 Removed DolorFade (8/8)
,D/SensorService( 1018): [SO] currT = 86090107153, prevT = 80340078978, diff = 5750028175, [0.019 0.057 10.036]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] 0.019 0.057 10.036
,D/SensorService( 1018): [SO] [100 -> 255]
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 29
,I/SurfaceFlinger(  258): id=12 Removed DolorFade (-2/8)
D/PowerManagerService( 1018): Excessive delay in ColorFade : dismiss: 16ms
E/libEGL  ( 1018): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 5 +
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
E/WifiNative-wlan0( 1018): do suspend false
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,D/lights  ( 1018): lcd : 5 -
I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : true
I/DBG_DM  ( 3121): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3121): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/Timeline( 3121): Timeline: Activity_idle id: android.os.BinderProxy@19aa88e0 time:86141
,I/wpa_supplicant( 2077): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2077): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2077): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2077): Scan requested (ret=0) - scan timeout 30 seconds
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1444): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1444): call the applyRouting
,D/accuweather( 1733): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1733): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1733): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 36
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0,
D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1811): getNextShiftState() cursorCapsMode : 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(true) while turning screen on: 161ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(true): 162ms
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 277ms
,D/lights  ( 1018): button : 1 +
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1018): button : 1 -
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1018): SIOP:: AP = 320
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1306): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1306): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1306): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1306): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454956500000
D/daemonapp( 1306): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454935013270
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1306): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1306): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1306): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/Finsky  ( 5670): [975] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5670): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/lights  ( 1018): button : 0 +
,D/lights  ( 1018): button : 0 -
,D/SensorService( 1018): [SO] 0.019 0.077 10.056
,I/wpa_supplicant( 2077): nl80211: Received scan results (3 BSSes),
D/WifiP2pService( 1018): InactiveState{ what=147461 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147461 },
D/WifiP2pService( 1018): DefaultState{ what=147461 }
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :8
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1733): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1733): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 37
,V/AlarmManager( 1018): waitForAlarm result :8
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,E/SMD     (  289): DCD OFF,
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 310,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.019 0.057 10.036
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181 (0x0)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 300,
,E/SMD     (  289): DCD OFF,
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SensorService( 1018): [SO] 0.019 0.077 10.036
,E/SMD     (  289): DCD OFF,
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1018): lcd : 1 +
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF,
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1869): Vacuum at: now=1454935042048 tag=VacuumService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1869): Explicit concurrent mark sweep GC freed 57882(3MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 12MB/21MB, paused 1.197ms total 72.175ms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DataBuffer( 1869): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23f9aa17)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1869): Scheduling Phenotype for one-off execution 2784 seconds from now (1454935042506)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1869): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1869): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1869): Using platform SSLCertificateSocketFactory
,D/FactoryTest( 5442): Not factory mode
,D/FactoryTest( 5442): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5442): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5442): still no open session command from host, so toast
,W/ContextImpl( 5442): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5442): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5442): Timeline: Activity_launch_request id:com.android.settings time:115682
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
,I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(366/onUserLeaveHint)] ,
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx,
D/InputDispatcher( 1018): Focus left window: 3121
E/MTPRx   ( 5442): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 29
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false,
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(371/onUserLeaveHint)] Home Key!!
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 3
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3121): [com.wssyncmldm.db.file.XDB(3671/llIIIIlllllIIllllllI)] FUMO_Status : 220
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIFotaPostponeActivity(381/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityManager( 1018): Display changed displayId=0
,D/Launcher( 1480): onRestart, Launcher: 789716589
,D/Launcher( 1480): onStart, Launcher: 789716589
D/Launcher.HomeView( 1480): onStart
D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,V/ActivityThread( 1480): updateVisibility : ActivityRecord{28f8fd80 token=android.os.BinderProxy@372c803a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/SurfaceFlinger(  258): id=13 createSurf (720x1280),1 flag=4, Mauncher
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ResourcesManager( 5442): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5442): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5442): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5442): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5442): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/SettingsReceiverActivity( 5442): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 1480
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,E/ActivityManager( 1018): Invalid thumbnail dimensions: 650x650
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
,D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
,I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1018): WindowOrientationListener disabled
,D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
,D/SensorService( 1018): [SO] activate (ident=0xb7aa58e0, enabled=0)
,D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1018): handleSandman : startDream(true)
,E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1018): Sleeping (uid 1000)...
,D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=14 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1018): unregisterListener ::   
,W/OpenGLRenderer( 1480): SFEffectCache::get: create texture(0xa3569724): name, size, mSize = 36, 141264, 460788
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/KeyguardViewMediator( 1181): timeout : 5000
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 28ms
,D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 10ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/VolumePanel( 1181): onScreenTurnedOff()
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/SamsungIME( 1811): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
,E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOff
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
I/DBG_DM  ( 3121): [com.wssyncmldm.ui.XUIInstallConfirmActivity(508/onDestroy)] 
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,D/SettingsReceiverActivity( 5442): dev.kiessupport is : TRUE
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/PhoneWindow( 5442): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5442): *FMB* installDecor flags : 8388610
D/SamsungIME( 1811): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,D/NotificationService( 1018): ACTION_SCREEN_OFF
,D/Launcher.HomeView( 1480): onStop
,E/WifiNative-wlan0( 1018): do suspend true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 83998(4MB) AllocSpace objects, 30(1061KB) LOS objects, 33% free, 31MB/47MB, paused 4.005ms total 201.237ms
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
,V/voice   (  284): voice_set_parameters: enter: screen_state=off
,V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
,I/ActivityManager( 1018): Killing 5060:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/BackgroundCompactionService( 1018): onIdleStop
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1869): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1869): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/lights  ( 1018): lcd : 0 +
D/DisplayPowerState( 1018): !@ ColorFade entry
D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (7/9)
,I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (-2/9)
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,D/lights  ( 1018): lcd : 0 -
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1717d430 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:116202
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!,
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1018): Display changed displayId=0
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb76b1690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,W/DisplayManagerService( 1018): Failed to notify process 5060 that displays changed, assuming it died.
W/DisplayManagerService( 1018): android.os.TransactionTooLargeException
W/DisplayManagerService( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1018): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1018): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1018): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1018): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1018): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/qtaguid ( 1869): Tagging socket 90 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb83437c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1204537208)
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1204537208) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb83437c8
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 278ms
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 285ms
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 277ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1869, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=1274)
I/PowerManagerService( 1018): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1419): [EmergencyStateReceiver] binteractive [false] why[3]
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_5060/cgroup.procs: No such file or directory
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/SSRM:n  ( 1018): SIOP:: AP = 290
D/NfcService( 1444): call the applyRouting
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/accuweather( 1733): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1733): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1733): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1733): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1869): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/accuweather( 1733): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1941): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts,
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1733): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1733): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1733): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1733): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper( 1018): Writing to database completed
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1869): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1869): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1869, getuid(): 10012
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=7_task_thumbnail.png
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1181): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 4,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,I/BackgroundCompactionService( 1018): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1018): compact_memory command done
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 5,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/ClearcutLoggerApiImpl( 1869): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :8,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 12
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 14
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=453027 batch.start=798044,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 15
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/bootchecker(  313): bootchecker wake up!!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 18
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 19
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 20
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 21
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 22
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 23
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 25
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 680s ago,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/Watchdog( 1018): !@Sync 26
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 27
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 28
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 766s ago,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 29
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 30
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,E/SMD     (  289): DCD OFF,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 31
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 856s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 32
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 33
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 34
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 951s ago,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 35
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 36
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 37
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 38
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1051s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 39
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1454936142945
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1454936143353
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 40,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 41
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/AndroidRuntime( 6681): 
D/AndroidRuntime( 6681): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6681): CheckJNI is OFF
D/AndroidRuntime( 6681): readGMSProperty: start
D/AndroidRuntime( 6681): readGMSProperty: already setted!!
D/AndroidRuntime( 6681): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6681): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6681): readGMSProperty: end
D/AndroidRuntime( 6681): addProductProperty: start
E/AffinityControl( 6681): AffinityControl: registerfunction enter
D/AndroidRuntime( 6681): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{1005973688}
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
D/PackageManager( 1018): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5029): Explicit concurrent mark sweep GC freed 2304(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 827us total 25.375ms
I/art     ( 5537): Explicit concurrent mark sweep GC freed 351(24KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 860us total 39.166ms
I/art     ( 4808): Explicit concurrent mark sweep GC freed 14903(798KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 828us total 33.268ms
I/art     ( 1975): Explicit concurrent mark sweep GC freed 3161(192KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.532ms total 72.146ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1811): mOCRHelper is null
W/GeofencerStateMachine( 1869): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3651): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 13:56:32 GMT+01:00 2016
D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
D/PersonaManager( 1444): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3651): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3651): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3651): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  ( 6694): MountEmulatedStorage()
I/libpersona( 6694): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6694): v2
I/libpersona( 6694): KNOX_SDCARD not a persona
I/SELinux ( 6694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6694 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6701 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/Zygote  ( 6701): MountEmulatedStorage()
I/libpersona( 6701): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6701): v2
I/libpersona( 6701): KNOX_SDCARD not a persona
I/SELinux ( 6701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 6694): TimaSignature is unavailable
E/Zygote  ( 6722): MountEmulatedStorage()
E/Zygote  ( 6722): v2
I/libpersona( 6722): KNOX_SDCARD checking this for 10149
I/libpersona( 6722): KNOX_SDCARD not a persona
I/SELinux ( 6722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityThread( 6694): Added TimaKeyStore provider
I/SELinux ( 6722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6722 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6701): TimaSignature is unavailable
D/ActivityThread( 6701): Added TimaKeyStore provider
E/SMD     (  289): DCD OFF
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
D/PersonaManager( 1444): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1444): empty dynamic service
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
E/SQLiteLog( 4808): (284) automatic index on crash_info_summary(package_name_touched)
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): listeningToPackageRemoved().END
D/TimaKeyStoreProvider( 6722): TimaSignature is unavailable
D/ActivityThread( 6722): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3651): KLMSIntentService(): onDestroy()
I/art     ( 4808): Explicit concurrent mark sweep GC freed 1057(52KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 1.525ms total 48.971ms
W/ResourcesManager( 6701): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ContextImpl( 5182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/BadgeProvider( 5931): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5931): sendNotify, [notify] : null
D/BadgeProvider( 5931): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5931): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5931): update, [UpdateCount] : 1
D/RCPManager( 5616):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
D/elm:15183( 6694): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6694): ELMEngine.ELMEngine( context ).
D/elm:15183( 6694): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6742): MountEmulatedStorage()
I/libpersona( 6742): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6742): v2
I/libpersona( 6742): KNOX_SDCARD not a persona
I/SELinux ( 6742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6742 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ThemeInfoUtil( 6722): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6722): isCurrentFestival = false
D/ActivityManager( 1018): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6694): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6742): TimaSignature is unavailable
D/ActivityThread( 6742): Added TimaKeyStore provider
I/art     ( 1018): Explicit concurrent mark sweep GC freed 54832(4MB) AllocSpace objects, 81(2MB) LOS objects, 33% free, 29MB/44MB, paused 3.451ms total 396.948ms
E/Zygote  ( 6759): MountEmulatedStorage()
E/Zygote  ( 6759): v2
I/libpersona( 6759): KNOX_SDCARD checking this for 1000
I/libpersona( 6759): KNOX_SDCARD not a persona
I/SELinux ( 6759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6759 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
E/SELinux ( 6759): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/elm:15183( 6694): ElmAgentService : onCreate()
D/elm:15183( 6694): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6694): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6694): MDMBridge.getInstance()
D/elm:15183( 6694): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6694): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider( 6759): TimaSignature is unavailable
D/ActivityThread( 6759): Added TimaKeyStore provider
D/elm:15183( 6694): ElmAgentService : onDestroy().
I/TapandpayWidget:TapandpayAppWidgetProvider( 5787): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5787): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5787): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5787): Widget is not attached.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1018): delete codoeFile: 
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10155 Target=com.test.thalitest
D/AASAservice-UpdateReceiver( 6759): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
D/PackageManager( 1018): result of delete: 1{1005973688}
W/System.err( 6759): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6759): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6759): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6759): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6759): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6759): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6759): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6759): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6759): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6759): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6759): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/Zygote  ( 6777): MountEmulatedStorage()
I/libpersona( 6777): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6777): v2
I/libpersona( 6777): KNOX_SDCARD not a persona
I/SELinux ( 6777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6777 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 6777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Killing 5561:com.google.android.partnersetup/u0a15 (adj 15): empty #31
W/ContextImpl( 6742): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
E/SELinux ( 6777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5752:com.sec.pcw.device/1000 (adj 15): empty #31
D/AndroidRuntime( 6681): Shutting down VM
I/ActivityManager( 1018): Killing 5770:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1018): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
D/Launcher.Model( 1480): reloadBadges entered.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6777): TimaSignature is unavailable
D/ActivityThread( 6777): Added TimaKeyStore provider
D/NearbySource( 6701): Nearby Source Create!
D/NearbyContext( 6701): Nearby Context Create!
E/Zygote  ( 6793): MountEmulatedStorage()
E/Zygote  ( 6793): v2
I/libpersona( 6793): KNOX_SDCARD checking this for 1000
I/libpersona( 6793): KNOX_SDCARD not a persona
I/SELinux ( 6793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5583:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
D/TimaKeyStoreProvider( 6793): TimaSignature is unavailable
D/ActivityThread( 6793): Added TimaKeyStore provider
W/ResourcesManager( 6777): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6701): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6701): Samsung link source created
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1018): Exception when sending broadcast to ComponentInfo{com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.ApplicationStatusReceiver}
W/BroadcastQueue( 1018): android.os.TransactionTooLargeException
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1018): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/[0]UMC:UMCContentProvider( 6777): @onCreate
D/AcmsPackageEventListener( 6793): Received: android.intent.action.PACKAGE_REMOVED
E/Zygote  ( 6810): MountEmulatedStorage()
E/Zygote  ( 6810): v2
I/libpersona( 6810): KNOX_SDCARD checking this for 10032
I/libpersona( 6810): KNOX_SDCARD not a persona
I/SELinux ( 6810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ContextImpl( 6793): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
I/SELinux ( 6810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6810 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 6810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
D/[0]UMC:Core( 6777): onCreate(): 
D/[0]UMC:Core( 6777): @isManagedProfileUser
D/[0]UMC:Core( 6777): userId: 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 6793): Enter Oncreate
D/AcmsServiceMonitor( 6793): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6793): creating AcmsCore
D/AcmsCore( 6793): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6793): AcmsCore
D/[0]UMC:Core( 6777): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6777): userInfo.isManagedProfile() : false
D/TimaKeyStoreProvider( 6810): TimaSignature is unavailable
D/ActivityThread( 6810): Added TimaKeyStore provider
D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
D/AcmsCore( 6793): init
D/AcmsCore( 6793): Looper handler is not null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/AcmsCore( 6793): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6793): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6793): Incrementing - Counter value: 1
D/AcmsCore( 6793): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6793): onStartCommand
D/AcmsService( 6793): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6793): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6793): Incrementing - Counter value: 2
D/AcmsService( 6793): Incremented Counter Value : onStartCommand
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsCertificateMngr( 6793): AcmsCertificateMngr
D/AcmsRevocationMngr( 6793): AcmsRevocationMngr
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6793): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/[0]UMC:DeviceInfo( 6777): USA==US==
D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/art     ( 6681): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/FeatureConfig( 6810): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/Zygote  ( 6830): MountEmulatedStorage()
I/libpersona( 6830): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6830): v2
I/libpersona( 6830): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/AcmsService( 6793): Inside handle Intent
D/AcmsService( 6793): App removed - package name: com.test.thalitest
D/AcmsCore( 6793): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6793): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6793): Incrementing - Counter value: 3
D/AcmsCore( 6793): Incremented Counter Value: postToAcmsCoreHandler =>5
D/AcmsService( 6793): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6793): Decrementing - Counter value: 2
I/SELinux ( 6830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ContactProvider( 6701): getAllContactInfoList Start
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6843): MountEmulatedStorage()
E/Zygote  ( 6843): v2
I/libpersona( 6843): KNOX_SDCARD checking this for 10035
I/libpersona( 6843): KNOX_SDCARD not a persona
I/SELinux ( 6843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6843 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6843): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5804:com.policydm/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6830): TimaSignature is unavailable
D/ActivityThread( 6830): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6843): TimaSignature is unavailable
D/ActivityThread( 6843): Added TimaKeyStore provider
D/USER_AGENT( 6777): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/[0]UMC:AdminManager( 6777): init - start
E/SQLiteLog( 4808): (284) automatic index on crash_info_summary(package_name_touched)
E/SQLiteLog( 5931): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5931): (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
E/DatabaseUtils( 5931): Writing exception to parcel
E/DatabaseUtils( 5931): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
E/DatabaseUtils( 5931): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
E/DatabaseUtils( 5931): 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
E/DatabaseUtils( 5931): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/DatabaseUtils( 5931): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
E/DatabaseUtils( 5931): 	at android.os.Binder.execTransact(Binder.java:461)
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ResourcesManager( 6810): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6810): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.

```
