#### Test 575312431be71d2_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1752): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1752): Got an BootCompleted event.
--------- beginning of /dev/log/system
D/SSRMv2:SIOP(  779): SIOP:: AP = 330, Delta = 0
D/dalvikvm( 1752): GC_CONCURRENT freed 1583K, 41% free 11255K/18952K, paused 4ms+5ms, total 52ms
D/dalvikvm( 1287): GC_EXPLICIT freed 807K, 46% free 10393K/18952K, paused 12ms+5ms, total 59ms
D/dalvikvm( 1212): GC_CONCURRENT freed 1710K, 40% free 11424K/18952K, paused 5ms+3ms, total 60ms
I/dalvikvm( 1287): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x0010
D/BootCompletedReceiver( 1752): Will NOT schedule AdAttestation signal task because it's disabled.
D/SystemUpdateService( 1752): onCreate
D/SystemUpdateService( 1752): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/GCoreUlr( 1212): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1752): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1752): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
D/dalvikvm( 1752): VFY: replacing opcode 0x6e at 0x0409
I/CheckinService( 1752): Checking schedule, now: 1454419032771 next: 1454573107295
I/CheckinService( 1752): active receiver: disabled
V/AuthZen ( 1752): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1752): cancelUpdate (empty URL)
,I/SystemUpdateService( 1752): active receiver: disabled
I/dalvikvm( 1752): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1752): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 1752): VFY: replacing opcode 0x6e at 0x002b
D/EnterpriseDeviceManagerService(  779): Creating context as user 0
W/dalvikvm( 1752): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1287): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1287): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1287): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1287): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x00bb
D/dalvikvm( 1287): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1287): VFY: unable to resolve instance field 161
D/dalvikvm( 1287): VFY: replacing opcode 0x52 at 0x0006
D/dalvikvm( 1752): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425d7da8
D/SystemUpdateService( 1752): onDestroy
D/dalvikvm( 1752): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425d7da8
D/dalvikvm( 1752): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425d7da8, skipping init
D/AuthZenEventHandler( 1752): Handling event: android.intent.action.BOOT_COMPLETED
D/EnterpriseDeviceManagerService(  779): Creating context as user 0
I/GCoreUlr( 1212): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1212): Unbound from all location providers
I/GCoreUlr( 1212): Place inference reporting - stopped
I/GCoreUlr( 1212): DispatchingService.onDestroy()
I/GCoreUlr( 1212): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1212): Unbound from all location providers
I/GCoreUlr( 1212): Place inference reporting - stopped
I/dalvikvm( 1287): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1287): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x0059
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
W/dalvikvm( 1752): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1287): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1287): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x0022
W/dalvikvm( 1752): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1752): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1752): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1752): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1752): VFY: replacing opcode 0x6e at 0x00bb
E/BaseAppContext( 1752): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/dalvikvm( 1752): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1752): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/dalvikvm( 1752): VFY: replacing opcode 0x6e at 0x002f
I/AuthZen ( 1752): Fetching signing key...
D/GCM     ( 1287): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1287): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x001c
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AuthZen ( 1752): Signing key fetched successfully!
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1287): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x0053
W/Auth    ( 1287): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtils( 1064): isPcwEnable = null
D/AuthZenTransactionCache( 1752): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1752): Clearing transaction cache
D/PersistentNotificationBroadcastReceiver( 1212): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/dalvikvm( 1287): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x001f
D/AndroidRuntime( 3814): 
D/AndroidRuntime( 3814): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3814): CheckJNI is OFF
D/AndroidRuntime( 3814): setted country_code = Poland
D/AndroidRuntime( 3814): setted countryiso_code = PL
I/dalvikvm( 1287): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1287): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1287): VFY: replacing opcode 0x6e at 0x0041
D/AndroidRuntime( 3814): setted sales_code = XEO
D/AndroidRuntime( 3814): readGMSProperty: start
D/AndroidRuntime( 3814): readGMSProperty: already setted!!
D/AndroidRuntime( 3814): readGMSProperty: end
D/AndroidRuntime( 3814): addProductProperty: start
D/WearableService( 1212): callingUid 10011, callindPid: 1212
I/GCM     ( 1287): GCM config loaded
E/MDM     ( 1212): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/dalvikvm( 3814): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3814): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3814): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3814): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3814): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/LocationInitializer( 1752): Restart initialization of location
D/AuthorizationBluetoothService( 1287): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1287): Proximity feature is not enabled.
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SMD     (  241): DCD ON
W/GCoreFlp( 1212): No location to return for getLastLocation()
W/FusedLocationProvider( 1212): location=null
E/MDM     ( 1212): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/AlarmManager(  779): waitForAlarm result :8
V/AlarmManager(  779): waitForAlarm result :8
D/LocationInitializer( 1752): Restart initialization of location
D/AuthorizationBluetoothService( 1287): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1287): Proximity feature is not enabled.
W/GCoreFlp( 1212): No location to return for getLastLocation()
W/FusedLocationProvider( 1212): location=null
V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  779): waitForAlarm result :8
E/memtrack( 3814): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3814): failed to load memtrack module: -2
D/dalvikvm( 3814): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 3864): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3864):  
D/QuickConnect[1.1][2] ( 3334): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1664): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1664): performUpdate:widgetCount=0
D/AndroidRuntime( 3814): Calling main entry com.android.commands.am.Am
I/SELinux ( 3864): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3864):  
I/SELinux ( 3864):  
I/SELinux ( 3864): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3864): >>>>> Normal User
E/dalvikvm( 3864): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
D/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - null 
E/SELinux ( 3864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ContactProvider( 2396): getAllContactInfoList Start
D/TimaKeyStoreProvider( 3864): in addTimaSignatureService
D/TimaKeyStoreProvider( 3864): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3864): Added TimaKesytore provider
D/ContactProvider( 2396): getAllContactInfoList End
I/syncContacts( 2396): thread: 164, onChange
D/AndroidRuntime( 3814): Shutting down VM
W/ActivityManager(  779): Permission Denial: getCurrentUser() from pid=3864, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 3814): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 1ms+0ms, total 3ms
D/QuickConnect[1.1][2] ( 3334): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1664): sContactsObserver.onChange(),selfUpdate=false
V/TaskCloserActivity( 3864): TaskCloserActivity enter()
D/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - null 
I/SELinux ( 3881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3881):  
D/ContactProvider( 2396): getAllContactInfoList Start
D/ContactProvider( 2396): getAllContactInfoList End
I/syncContacts( 2396): thread: 165, onChange
I/SELinux ( 3881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3881):  
I/SELinux ( 3881):  
I/SELinux ( 3881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3881): >>>>> Normal User
E/dalvikvm( 3881): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3881): in addTimaSignatureService
D/TimaKeyStoreProvider( 3881): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3881): Added TimaKesytore provider
D/FactoryTestApp( 3881): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3881): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3881): User mode
I/knox    ( 3275): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/knox    ( 3275): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3275): KNOXAgentService : onCreate()
D/knox    ( 3275): KNOXAgentService : set alarms for deniallog and usage data upload
I/ActivityManager(  779): Killing 2810:com.osp.app.signin/u0a43 (adj 15): empty #43
W/ContextImpl( 3275): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3275): KNOXAgentService. startJobThread() start
D/knox    ( 3275): KNOXAgentService. JobThread()
D/knox    ( 3275): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3275): KNOXAgentService. startJobThread() wait
I/SELinux ( 3894): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3894):  
D/knox    ( 3275): KNOXAgentService : onDestroy().
D/knox    ( 3275): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 3894): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3894):  
I/SELinux ( 3894):  
,I/SELinux ( 3894): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3894): >>>>> Normal User
,E/dalvikvm( 3894): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3894): in addTimaSignatureService
D/ConnectivityService(  779): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/TimaKeyStoreProvider( 3894): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3894): Added TimaKesytore provider
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,E/MTPRx   ( 3894): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3894): check value of boot_completed is1
,E/MTPRx   ( 3894): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3894): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3894): Status for mount/Unmount :removed
,E/MTPRx   ( 3894): SDcard is not available
W/MTPRx   ( 3894): value of connected istrue
W/MTPRx   ( 3894): value of configured istrue
W/MTPRx   ( 3894): value of mtpEnabled istrue
,W/MTPRx   ( 3894): value of ptpEnabled isfalse
E/MTPRx   ( 3894): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3894): mFirstTime: false
,D/        ( 3894): MTP: reading debug level property
E/MTPRx   ( 3894):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 3894): Getting CryptionKey from JAVA
,E/MTPRx   ( 3894): currentUserId is 0
,E/MTPRx   ( 3894): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3894): usbMode is 0200
,E/MTPRx   ( 3894): is_secretmode is NOT 1
,W/MTPRx   ( 3894): Phone is lockedtrue
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/MTPRx   ( 3894):  inside checkKnoxStatus
,D/MTPRx   ( 3894):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3894): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3894): noti = 17
,E/MTPRx   ( 3894): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3894): else part ... so first time!!!
,E/MTPPlaObsrvr( 3894): inside setContext()
,E/MTPPlaObsrvr( 3894):  inside createplafiles
,E/MTPPlaObsrvr( 3894): playlist count is0
E/MTPPlaObsrvr( 3894):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3894):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3894): Inside registerContentObserver
,E/MtpAdbObserver( 3894): inside setContext()
E/MtpAdbObserver( 3894): Inside registerContentObserver
,W/Settings( 3894): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/dalvikvm(  779): GC_EXPLICIT freed 2090K, 14% free 23437K/27024K, paused 4ms+10ms, total 118ms
,E/MtpService( 3894): onCreate.
,E/MtpService( 3894): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3894): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3894): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3894): onStartCommand.
W/MTPRx   ( 3894): calling native method
E/MTPJNIInterface( 3894): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3894): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3894): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3894): noti = 10
,E/MtpService( 3894): onStartCommand.
I/knox    ( 3275): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/MTPRx   ( 3894): calling native method
,E/MTPRx   ( 3894): Checking the driver time out
,E/MTPJNIInterface( 3894): noti = 2
D/        ( 3894): deleting sockets before message queue initialization
,D/        ( 3894): event handler thread is created, so set the flag
E/MTPRx   ( 3894): called native method
E/MTPJNIInterface( 3894): setting Media scanner status0
E/MTPJNIInterface( 3894): After setting Media scanner status0
,E/MTPJNIInterface( 3894): Getting media scanner status0
W/MTPRx   ( 3894): notification from stack 1
E/MTPJNIInterface( 3894): DeviceName is Galaxy S5-2
W/ContextImpl( 3275): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/MtpService( 3894): handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
I/knox    ( 3275): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3275): KNOXAgentService : onCreate()
D/knox    ( 3275): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3275): KNOXAgentService. startJobThread() start
D/knox    ( 3275): KNOXAgentService. JobThread()
D/knox    ( 3275): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3275): KNOXAgentService. startJobThread() wait
D/knox    ( 3275): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3275): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3275): KNOXAgentService : onDestroy().
D/knox    ( 3275): ModuleBase.cancelAllAlarmManageModule()
I/knox    ( 3275): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454440560000
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454419034168
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/AuthorizationBluetoothService( 1287): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/FileShare-Server( 3013): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 3013): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3919):  
,I/SELinux ( 3919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3919):  
I/SELinux ( 3919):  
,I/SELinux ( 3919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3919): >>>>> Normal User
,E/dalvikvm( 3919): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3919): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3919): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3919): Added TimaKesytore provider
,I/Atfwd_Daemon(  318): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  318): ATFWD --> QMI Port : rmnet1
,I/System.out( 3919): Inside WakeupProvider
,I/System.out( 3919): Inside onCreate() of WakeupTriggerProvide
I/Atfwd_Daemon(  318): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  318): Trying to register 8 commands:
,I/Atfwd_Daemon(  318): cmd0: +CKPD
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd1: +CTSA
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd2: +CFUN
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd3: +CMAR
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd4: +CDIS
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd5: +CRSL
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd6: +CSS
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): cmd7: $QCPWRDN
I/Atfwd_Daemon(  318): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  318): Registered AT Commands event handler
,I/VlingoApplication( 3919): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3919): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3919): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DialogFlow( 3919): initQueue()
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
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1315): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1315): LocalBluetoothProfileManager construction complete
,D/dalvikvm( 1315): GC_CONCURRENT freed 7548K, 47% free 10085K/18952K, paused 3ms+9ms, total 52ms
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/DockEventReceiver( 1315): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1315): onReceive
D/BluetoothA2dp( 1315): Proxy object connected
D/A2dpProfile( 1315): Bluetooth service connected
D/BtConfig.SecureMode( 1936): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1287): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1287): Proximity feature is not enabled.
,W/BluetoothAdapter( 1936): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1936): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1936): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/BtOppRfcommListener( 1936): Accept thread started.
,D/HeadsetProfile( 1315): Bluetooth service connected
,D/BluetoothInputDevice( 1315): Proxy object connected
,D/HidProfile( 1315): Bluetooth service connected
,D/BluetoothPan( 1315): BluetoothPAN Proxy object connected
,D/PanProfile( 1315): Bluetooth service connected
,D/BluetoothMap( 1315): Proxy object connected
,D/MapProfile( 1315): Bluetooth service connected
,D/BluetoothPbap( 1315): Proxy object connected
,D/PbapServerProfile( 1315): Bluetooth service connected
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,W/ContextImpl(  779): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/GKI_LINUX( 1936): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/Toast   ( 1315):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1315): showing allowed
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=4, Uoast
,I/SELinux ( 3952): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3952):  
,D/dalvikvm( 1202): GC_EXPLICIT freed 3900K, 47% free 10047K/18952K, paused 3ms+4ms, total 39ms
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  779): Waited long enough for: ServiceRecord{431c8050 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,E/MTPJNIInterface( 3894): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3894): SDcard is not available
,D/PowerManagerService(  779): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=779
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,E/MTPJNIInterface( 3894): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3894): SDcard is not available
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 93298 of [00bb9c9ce4]
,E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3894): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3894): notification from stack 2
,D/        ( 3894): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3894): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3894): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3894): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
I/SELinux ( 3952): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3952):  
I/SELinux ( 3952):  
,I/SELinux ( 3952): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3952): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3952): >>>>> Normal User
,E/dalvikvm( 3952): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]

```
