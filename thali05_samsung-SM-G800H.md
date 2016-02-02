#### Test 57972094912017a_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/BootCompletedReceiver( 1782): Will NOT schedule AdAttestation signal task because it's disabled.
D/SystemUpdateService( 1782): onCreate
D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/dalvikvm( 1782): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0409
D/dalvikvm( 1782): GC_CONCURRENT freed 1567K, 41% free 11259K/19084K, paused 4ms+6ms, total 42ms
D/dalvikvm( 1303): GC_EXPLICIT freed 808K, 46% free 10394K/19084K, paused 5ms+6ms, total 53ms
I/dalvikvm( 1303): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x0010
V/AuthZen ( 1782): Handling intent: android.intent.action.BOOT_COMPLETED
D/dalvikvm( 1213): GC_CONCURRENT freed 1622K, 41% free 11423K/19084K, paused 3ms+4ms, total 51ms
,I/dalvikvm( 1782): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x002b
D/EnterpriseDeviceManagerService(  751): Creating context as user 0
I/GCoreUlr( 1213): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/CheckinService( 1782): Checking schedule, now: 1454420763778 next: 1454573107295
I/CheckinService( 1782): active receiver: disabled
I/SystemUpdateService( 1782): cancelUpdate (empty URL)
I/SystemUpdateService( 1782): active receiver: disabled
D/dalvikvm( 1782): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42afbbb8
W/dalvikvm( 1303): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1303): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1303): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1303): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x00bb
D/dalvikvm( 1782): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42afbbb8
D/dalvikvm( 1782): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42afbbb8, skipping init
D/dalvikvm( 1303): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1303): VFY: unable to resolve instance field 161
D/dalvikvm( 1303): VFY: replacing opcode 0x52 at 0x0006
D/SystemUpdateService( 1782): onDestroy
D/EnterpriseDeviceManagerService(  751): Creating context as user 0
D/AuthZenEventHandler( 1782): Handling event: android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1213): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1213): Unbound from all location providers
I/GCoreUlr( 1213): Place inference reporting - stopped
I/GCoreUlr( 1213): DispatchingService.onDestroy()
I/GCoreUlr( 1213): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1213): Unbound from all location providers
I/GCoreUlr( 1213): Place inference reporting - stopped
W/BaseAppContext( 1782): Using Auth Proxy for data requests.
I/dalvikvm( 1303): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1303): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x0059
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1782): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x00bb
E/BaseAppContext( 1782): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/dalvikvm( 1303): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1303): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x0022
I/dalvikvm( 1782): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x002f
I/AuthZen ( 1782): Fetching signing key...
I/dalvikvm( 1303): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x001c
D/GCM     ( 1303): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/AuthZen ( 1782): Signing key fetched successfully!
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1303): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x0053
W/BaseAppContext( 1782): Using Auth Proxy for data requests.
W/Auth    ( 1303): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1782): GC_EXPLICIT freed 844K, 41% free 11327K/19084K, paused 5ms+5ms, total 52ms
D/LockPatternUtils( 1064): isPcwEnable = null
D/AuthZenTransactionCache( 1782): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1782): Clearing transaction cache
D/AndroidRuntime( 3755): 
D/AndroidRuntime( 3755): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3755): CheckJNI is OFF
D/AndroidRuntime( 3755): setted country_code = Poland
D/AndroidRuntime( 3755): setted countryiso_code = PL
D/AndroidRuntime( 3755): setted sales_code = XEO
D/AndroidRuntime( 3755): readGMSProperty: start
D/AndroidRuntime( 3755): readGMSProperty: already setted!!
D/AndroidRuntime( 3755): readGMSProperty: end
D/AndroidRuntime( 3755): addProductProperty: start
D/PersistentNotificationBroadcastReceiver( 1213): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/dalvikvm( 1303): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x001f
D/dalvikvm( 3755): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3755): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3755): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3755): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3755): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCM     ( 1303): GCM config loaded
I/dalvikvm( 1303): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x0041
D/WearableService( 1213): callingUid 10011, callindPid: 1213
D/QuickConnect[1.1][2] ( 3312): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1667): performUpdate:widgetCount=0
E/MDM     ( 1213): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1303): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1303): Proximity feature is not enabled.
D/LocationInitializer( 1782): Restart initialization of location
--------- beginning of /dev/log/system
V/AlarmManager(  751): waitForAlarm result :8
D/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getMyMobileNumber - null 
E/memtrack( 3755): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3755): failed to load memtrack module: -2
D/ContactProvider( 2449): getAllContactInfoList Start
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 3755): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
W/GCoreFlp( 1213): No location to return for getLastLocation()
W/FusedLocationProvider( 1213): location=null
V/AlarmManager(  751): waitForAlarm result :8
E/MDM     ( 1213): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1303): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1303): Proximity feature is not enabled.
D/LocationInitializer( 1782): Restart initialization of location
D/ContactProvider( 2449): getAllContactInfoList End
I/syncContacts( 2449): thread: 170, onChange
D/AndroidRuntime( 3755): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SELinux ( 3806): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3806):  
W/GCoreFlp( 1213): No location to return for getLastLocation()
W/FusedLocationProvider( 1213): location=null
V/AlarmManager(  751): waitForAlarm result :8
D/QuickConnect[1.1][2] ( 3312): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/SSRMv2:SIOP(  751): SIOP:: AP = 330, Delta = 0
D/ContactProvider( 2449): getAllContactInfoList Start
D/AndroidRuntime( 3755): Shutting down VM
D/dalvikvm( 3755): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
D/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3312): CONTACT_Info.getMyMobileNumber - null 
I/SELinux ( 3806): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3806):  
I/SELinux ( 3806):  
I/SELinux ( 3806): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3806): >>>>> Normal User
E/dalvikvm( 3806): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ContactProvider( 2449): getAllContactInfoList End
I/syncContacts( 2449): thread: 171, onChange
D/TimaKeyStoreProvider( 3806): in addTimaSignatureService
D/TimaKeyStoreProvider( 3806): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3806): Added TimaKesytore provider
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=3806, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3806): TaskCloserActivity enter()
I/SELinux ( 3820): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3820):  
I/SELinux ( 3820): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3820):  
I/SELinux ( 3820):  
I/SELinux ( 3820): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3820): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3820): >>>>> Normal User
E/dalvikvm( 3820): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3820): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3820): in addTimaSignatureService
D/TimaKeyStoreProvider( 3820): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3820): Added TimaKesytore provider
D/FactoryTestApp( 3820): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3820): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3820): User mode
,I/SELinux ( 3832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3832):  
I/ActivityManager(  751): Killing 2810:com.osp.app.signin/u0a43 (adj 15): empty #43
,E/SMD     (  241): DCD ON
D/ConnectivityService(  751): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 3832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3832):  
I/SELinux ( 3832):  
,I/SELinux ( 3832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3832): >>>>> Normal User
,E/dalvikvm( 3832): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3832): Added TimaKesytore provider
,E/MTPRx   ( 3832): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3832): check value of boot_completed is1
,E/MTPRx   ( 3832): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3832): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3832): Status for mount/Unmount :removed
,E/MTPRx   ( 3832): SDcard is not available
,W/MTPRx   ( 3832): value of connected istrue
W/MTPRx   ( 3832): value of configured istrue
W/MTPRx   ( 3832): value of mtpEnabled istrue
,W/MTPRx   ( 3832): value of ptpEnabled isfalse
E/MTPRx   ( 3832): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3832): mFirstTime: false
,D/        ( 3832): MTP: reading debug level property
,E/MTPRx   ( 3832):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3832): Getting CryptionKey from JAVA
,E/MTPRx   ( 3832): currentUserId is 0
,E/MTPRx   ( 3832): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3832): usbMode is 0200
,E/MTPRx   ( 3832): is_secretmode is NOT 1
,W/MTPRx   ( 3832): Phone is lockedtrue
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/MTPRx   ( 3832):  inside checkKnoxStatus
,D/MTPRx   ( 3832):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3832): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3832): noti = 17
,E/MTPRx   ( 3832): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3832): else part ... so first time!!!
,E/MTPPlaObsrvr( 3832): inside setContext()
,E/MTPPlaObsrvr( 3832):  inside createplafiles
,E/MTPPlaObsrvr( 3832): playlist count is0
E/MTPPlaObsrvr( 3832):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3832):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3832): Inside registerContentObserver
,E/MtpAdbObserver( 3832): inside setContext()
E/MtpAdbObserver( 3832): Inside registerContentObserver
,W/Settings( 3832): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/dalvikvm(  751): GC_EXPLICIT freed 2110K, 14% free 23430K/27040K, paused 4ms+10ms, total 115ms
,E/MtpService( 3832): onCreate.
,E/MtpService( 3832): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3832): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3832): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/MTPRx   ( 3832): calling native method
E/MTPJNIInterface( 3832): < MTP > Registering BroadCast receiver :::::
E/MTPJNIInterface( 3832): < MTP > Registering BroadCast receiver :::::::
I/knox    ( 3253): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/MTPJNIInterface( 3832): noti = 10
E/MtpService( 3832): onStartCommand.
I/knox    ( 3253): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/MtpService( 3832): handleMessage. msg= { when=-4ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/knox    ( 3253): KNOXAgentService : onCreate()
D/knox    ( 3253): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3253): KNOXAgentService. startJobThread() start
D/knox    ( 3253): KNOXAgentService. JobThread()
D/knox    ( 3253): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3253): KNOXAgentService. startJobThread() wait
E/MtpService( 3832): onStartCommand.
W/MTPRx   ( 3832): calling native method
E/MTPRx   ( 3832): Checking the driver time out
E/MTPJNIInterface( 3832): noti = 2
D/        ( 3832): deleting sockets before message queue initialization
D/        ( 3832): event handler thread is created, so set the flag
E/MTPRx   ( 3832): called native method
E/MTPJNIInterface( 3832): setting Media scanner status0
E/MTPJNIInterface( 3832): After setting Media scanner status0
E/MTPJNIInterface( 3832): Getting media scanner status0
D/knox    ( 3253): KNOXAgentService : onDestroy().
W/MTPRx   ( 3832): notification from stack 1
D/knox    ( 3253): ModuleBase.cancelAllAlarmManageModule()
E/MTPJNIInterface( 3832): DeviceName is Galaxy S5-2
E/MtpService( 3832): handleMessage. msg= { when=-6ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1460): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1460): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1460): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1460): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1460): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1460): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1460): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454442300000
D/daemonapp( 1460): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454420765199
,D/daemonapp( 1460): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1460): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1460): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/AuthorizationBluetoothService( 1303): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3253): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3253): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3253): KNOXAgentService : onCreate()
,D/knox    ( 3253): KNOXAgentService : set alarms for deniallog and usage data upload
,W/ContextImpl( 3253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3253): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/knox    ( 3253): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
D/knox    ( 3253): KNOXAgentService. startJobThread() start
D/knox    ( 3253): KNOXAgentService. JobThread()
D/FileShare-Server( 3010): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
I/knox    ( 3253): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/FileShare-Server( 3010): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
D/knox    ( 3253): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3253): KNOXAgentService. startJobThread() wait
D/knox    ( 3253): KNOXAgentService : onDestroy().
D/knox    ( 3253): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 3858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3858):  
,I/SELinux ( 3858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3858):  
I/SELinux ( 3858):  
,I/SELinux ( 3858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3858): >>>>> Normal User
,E/dalvikvm( 3858): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3858): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3858): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3858): Added TimaKesytore provider
,I/System.out( 3858): Inside WakeupProvider
,I/System.out( 3858): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3858): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3858): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3858): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3858): initQueue()
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1315): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1315): Adding local HEADSET profile
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1315): BTStateChangeCB is registed
,E/BluetoothHeadset( 1315): BluetoothHeadset service is binded
,D/Bluetoothsap( 1315): bindService called to Bluetooth SAP Service
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1315): PANU : true
,D/LocalBluetoothProfileManager( 1315): Adding local MAP profile
,D/BluetoothMap( 1315): Create BluetoothMap proxy object
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1315): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1315): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/dalvikvm( 1315): GC_CONCURRENT freed 7578K, 48% free 10057K/19084K, paused 3ms+2ms, total 44ms
,D/DockEventReceiver( 1315): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/BluetoothA2dp( 1315): Proxy object connected
,D/A2dpProfile( 1315): Bluetooth service connected
,D/BtConfig.SecureMode( 1940): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1303): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1303): Proximity feature is not enabled.
,W/BluetoothAdapter( 1940): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1940): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1940): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1940): Accept thread started.
,D/HeadsetProfile( 1315): Bluetooth service connected
,D/BluetoothInputDevice( 1315): Proxy object connected
,D/HidProfile( 1315): Bluetooth service connected
,D/BluetoothPan( 1315): BluetoothPAN Proxy object connected
,D/PanProfile( 1315): Bluetooth service connected
,D/BluetoothMap( 1315): Proxy object connected
D/MapProfile( 1315): Bluetooth service connected
D/BluetoothPbap( 1315): Proxy object connected
D/PbapServerProfile( 1315): Bluetooth service connected
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1315):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1315): showing allowed
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/GKI_LINUX( 1940): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
I/SELinux ( 3890): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3890):  
,I/SurfaceFlinger(  247): id=16 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  751): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=751
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 3890): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3890):  
I/SELinux ( 3890):  
,I/SELinux ( 3890): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3890): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3890): >>>>> Normal User
,E/dalvikvm( 3890): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 3890): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 3890): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3890): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3890): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3890): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/Atfwd_Daemon(  290): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  290): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  290): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  290): Trying to register 8 commands:
,I/Atfwd_Daemon(  290): cmd0: +CKPD
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd1: +CTSA
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd2: +CFUN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd3: +CMAR
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd4: +CDIS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd5: +CRSL
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd6: +CSS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd7: $QCPWRDN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): Registered AT Commands event handler
,D/dalvikvm( 1202): GC_EXPLICIT freed 3899K, 48% free 10046K/19084K, paused 4ms+7ms, total 45ms
,E/MTPJNIInterface( 3832): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3832): SDcard is not available
,I/PCWCLIENTTRACE_PushUtil( 3890): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3890): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3890): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_LOG( 3890): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3890): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3890): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/MTPJNIInterface( 3832): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3832): SDcard is not available
E/SQLiteLog( 3832): (21) API call with NULL database connection pointer
E/SQLiteLog( 3832): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3832): (21) API call with NULL database connection pointer
E/SQLiteLog( 3832): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3832): (21) API call with NULL database connection pointer
E/SQLiteLog( 3832): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3832): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3832): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3832): notification from stack 2
D/        ( 3832): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3832): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3832): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3832): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
