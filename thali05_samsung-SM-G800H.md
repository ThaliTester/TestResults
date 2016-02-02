#### Test 5753124305d96c2_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/dalvikvm( 1316): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1316): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1316): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x00bb
D/dalvikvm( 1316): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1316): VFY: unable to resolve instance field 161
D/dalvikvm( 1316): VFY: replacing opcode 0x52 at 0x0006
D/dalvikvm( 1783): GC_CONCURRENT freed 2271K, 41% free 11214K/18936K, paused 5ms+7ms, total 39ms
V/AuthZen ( 1783): Handling intent: android.intent.action.BOOT_COMPLETED
I/CheckinService( 1783): Checking schedule, now: 1454422500870 next: 1454573107295
I/CheckinService( 1783): active receiver: disabled
I/dalvikvm( 1783): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x002b
I/SystemUpdateService( 1783): cancelUpdate (empty URL)
I/SystemUpdateService( 1783): active receiver: disabled
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/EnterpriseDeviceManagerService(  741): Creating context as user 0
D/dalvikvm( 1783): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4257ec68
,D/SystemUpdateService( 1783): onDestroy
I/GCoreUlr( 1220): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/dalvikvm( 1316): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1316): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x0059
I/GCoreUlr( 1220): Unbound from all location providers
I/GCoreUlr( 1220): Place inference reporting - stopped
D/AuthZenEventHandler( 1783): Handling event: android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1220): DispatchingService.onDestroy()
I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
D/dalvikvm( 1783): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4257ec68
D/dalvikvm( 1783): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4257ec68, skipping init
I/dalvikvm( 1316): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1316): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x0022
I/GCoreUlr( 1220): Unbound from all location providers
I/GCoreUlr( 1220): Place inference reporting - stopped
--------- beginning of /dev/log/system
D/SSRMv2:SIOP(  741): SIOP:: AP = 330, Delta = 0
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
D/GCM     ( 1316): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1316): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1316): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x0053
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1783): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x00bb
E/BaseAppContext( 1783): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/dalvikvm( 1316): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1316): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x001f
I/dalvikvm( 1783): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x002f
I/AuthZen ( 1783): Fetching signing key...
V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1316): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1316): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x0041
W/Auth    ( 1316): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtils( 1068): isPcwEnable = null
I/AuthZen ( 1783): Signing key fetched successfully!
D/PersistentNotificationBroadcastReceiver( 1220): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
I/BootupListener( 1241): mPendingNetworkManualSelection : false
D/StatusChecker( 3334): onReceive : android.intent.action.SERVICE_STATE
D/StatusChecker( 3334): Service state changed : 3
I/GCM     ( 1316): GCM config loaded
D/AuthZenTransactionCache( 1783): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1783): Clearing transaction cache
V/AlarmManager(  741): waitForAlarm result :8
D/AndroidRuntime( 3804): 
D/AndroidRuntime( 3804): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3804): CheckJNI is OFF
D/AndroidRuntime( 3804): setted country_code = Poland
D/AndroidRuntime( 3804): setted countryiso_code = PL
D/AndroidRuntime( 3804): setted sales_code = XEO
D/AndroidRuntime( 3804): readGMSProperty: start
D/AndroidRuntime( 3804): readGMSProperty: already setted!!
D/AndroidRuntime( 3804): readGMSProperty: end
D/AndroidRuntime( 3804): addProductProperty: start
D/dalvikvm( 3804): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3804): Added shared lib libjavacore.so 0x0
D/WearableService( 1220): callingUid 10011, callindPid: 1220
D/dalvikvm( 3804): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3804): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3804): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/MDM     ( 1220): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1783): Restart initialization of location
D/QuickConnect[1.1][2] ( 3348): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1667): performUpdate:widgetCount=0
D/AuthorizationBluetoothService( 1316): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1316): Proximity feature is not enabled.
D/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2455): getAllContactInfoList Start
V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1220): No location to return for getLastLocation()
W/FusedLocationProvider( 1220): location=null
V/AlarmManager(  741): waitForAlarm result :8
E/MDM     ( 1220): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1783): Restart initialization of location
D/ContactProvider( 2455): getAllContactInfoList End
I/syncContacts( 2455): thread: 173, onChange
D/AuthorizationBluetoothService( 1316): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1316): Proximity feature is not enabled.
V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1220): No location to return for getLastLocation()
W/FusedLocationProvider( 1220): location=null
V/AlarmManager(  741): waitForAlarm result :8
E/memtrack( 3804): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3804): failed to load memtrack module: -2
I/SELinux ( 3851): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3851):  
D/QuickConnect[1.1][2] ( 3348): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - null 
D/dalvikvm( 3804): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/ContactProvider( 2455): getAllContactInfoList Start
I/SELinux ( 3851): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3851):  
I/SELinux ( 3851):  
I/SELinux ( 3851): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3851): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3851): >>>>> Normal User
E/dalvikvm( 3851): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3851): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ContactProvider( 2455): getAllContactInfoList End
I/syncContacts( 2455): thread: 174, onChange
D/TimaKeyStoreProvider( 3851): in addTimaSignatureService
D/TimaKeyStoreProvider( 3851): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3851): Added TimaKesytore provider
D/AndroidRuntime( 3804): Calling main entry com.android.commands.am.Am
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=3851, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3851): TaskCloserActivity enter()
I/SELinux ( 3866): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3866):  
D/AndroidRuntime( 3804): Shutting down VM
D/dalvikvm( 3804): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 1ms+1ms, total 3ms
I/SELinux ( 3866): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3866):  
I/SELinux ( 3866):  
I/SELinux ( 3866): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3866): >>>>> Normal User
E/dalvikvm( 3866): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3866): in addTimaSignatureService
D/TimaKeyStoreProvider( 3866): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3866): Added TimaKesytore provider
D/FactoryTestApp( 3866): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3866): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3866): User mode
I/SELinux ( 3878): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3878):  
D/ConnectivityService(  741): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ActivityManager(  741): Killing 2814:com.osp.app.signin/u0a43 (adj 15): empty #43
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 3878): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3878):  
I/SELinux ( 3878):  
I/SELinux ( 3878): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3878): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3878): >>>>> Normal User
E/dalvikvm( 3878): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
E/SELinux ( 3878): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3878): in addTimaSignatureService
D/TimaKeyStoreProvider( 3878): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3878): Added TimaKesytore provider
,E/MTPRx   ( 3878): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 3878): check value of boot_completed is1
,E/MTPRx   ( 3878): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3878): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3878): Status for mount/Unmount :removed
,E/MTPRx   ( 3878): SDcard is not available
,W/MTPRx   ( 3878): value of connected istrue
W/MTPRx   ( 3878): value of configured istrue
W/MTPRx   ( 3878): value of mtpEnabled istrue
,W/MTPRx   ( 3878): value of ptpEnabled isfalse
E/MTPRx   ( 3878): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3878): mFirstTime: false
,D/        ( 3878): MTP: reading debug level property
,E/MTPRx   ( 3878):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3878): Getting CryptionKey from JAVA
,E/MTPRx   ( 3878): currentUserId is 0
,E/MTPRx   ( 3878): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3878): usbMode is 0200
,E/MTPRx   ( 3878): is_secretmode is NOT 1
,W/MTPRx   ( 3878): Phone is lockedtrue
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/MTPRx   ( 3878):  inside checkKnoxStatus
,D/MTPRx   ( 3878):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3878): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3878): noti = 17
,E/MTPRx   ( 3878): sending MTP_ICON_ENABLED to stack
,E/SMD     (  241): DCD ON
,E/MTPRx   ( 3878): else part ... so first time!!!
E/MTPPlaObsrvr( 3878): inside setContext()
,E/MTPPlaObsrvr( 3878):  inside createplafiles
,E/MTPPlaObsrvr( 3878): playlist count is0
E/MTPPlaObsrvr( 3878):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3878):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3878): Inside registerContentObserver
,E/MtpAdbObserver( 3878): inside setContext()
E/MtpAdbObserver( 3878): Inside registerContentObserver
,W/Settings( 3878): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3878): onCreate.
,E/MtpService( 3878): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3878): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/dalvikvm(  741): GC_EXPLICIT freed 2089K, 13% free 23442K/26880K, paused 5ms+10ms, total 118ms
,E/MtpService( 3878): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3878): onStartCommand.
W/MTPRx   ( 3878): calling native method
,E/MTPJNIInterface( 3878): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3878): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3878): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3878): noti = 10
E/MtpService( 3878): onStartCommand.
,W/MTPRx   ( 3878): calling native method
,I/knox    ( 3290): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/MtpService( 3878): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPRx   ( 3878): Checking the driver time out
,E/MTPJNIInterface( 3878): noti = 2
D/        ( 3878): deleting sockets before message queue initialization
,D/        ( 3878): event handler thread is created, so set the flag
E/MTPRx   ( 3878): called native method
,E/MTPJNIInterface( 3878): Getting media scanner status0
E/MTPJNIInterface( 3878): setting Media scanner status0
E/MTPJNIInterface( 3878): After setting Media scanner status0
W/MTPRx   ( 3878): notification from stack 1
,E/MTPJNIInterface( 3878): DeviceName is Galaxy S5-2
,I/knox    ( 3290): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3290): KNOXAgentService : onCreate()
D/knox    ( 3290): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3290): KNOXAgentService. startJobThread() start
D/knox    ( 3290): KNOXAgentService. JobThread()
D/knox    ( 3290): KNOXAgentService. JobThread. notifyAll().
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3290): KNOXAgentService. startJobThread() wait
D/knox    ( 3290): KNOXAgentService : onDestroy().
D/knox    ( 3290): ModuleBase.cancelAllAlarmManageModule()
D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1462): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1462): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454444040000
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454422502240
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1292): onReceive
,D/AuthorizationBluetoothService( 1316): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3290): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3290): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 3290): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3290): KNOXAgentService : onCreate()
D/knox    ( 3290): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3290): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3290): KNOXAgentService. startJobThread() start
D/knox    ( 3290): KNOXAgentService. JobThread()
D/knox    ( 3290): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3290): KNOXAgentService. startJobThread() wait
D/knox    ( 3290): KNOXAgentService : onDestroy().
D/knox    ( 3290): ModuleBase.cancelAllAlarmManageModule()
D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
I/knox    ( 3290): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3019): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3019): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3901): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3901):  
,I/SELinux ( 3901): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3901):  
I/SELinux ( 3901):  
,I/SELinux ( 3901): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3901): >>>>> Normal User
,E/dalvikvm( 3901): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3901): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3901): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3901): Added TimaKesytore provider
,I/System.out( 3901): Inside WakeupProvider
,I/System.out( 3901): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3901): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3901): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3901): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/DialogFlow( 3901): initQueue()
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1292): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1292): Adding local HEADSET profile
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1292): BTStateChangeCB is registed
,E/BluetoothHeadset( 1292): BluetoothHeadset service is binded
,D/Bluetoothsap( 1292): bindService called to Bluetooth SAP Service
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1292): PANU : true
,D/LocalBluetoothProfileManager( 1292): Adding local MAP profile
,D/BluetoothMap( 1292): Create BluetoothMap proxy object
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/dalvikvm( 1292): GC_CONCURRENT freed 7561K, 47% free 10049K/18936K, paused 3ms+3ms, total 41ms
D/Bluetoothsap( 1292): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1292): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1292): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1292): onReceive
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BluetoothA2dp( 1292): Proxy object connected
D/A2dpProfile( 1292): Bluetooth service connected
D/BtConfig.SecureMode( 1936): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1316): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1316): Proximity feature is not enabled.
,W/BluetoothAdapter( 1936): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1936): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1936): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1936): Accept thread started.
,D/HeadsetProfile( 1292): Bluetooth service connected
,D/BluetoothInputDevice( 1292): Proxy object connected
,D/HidProfile( 1292): Bluetooth service connected
,D/BluetoothPan( 1292): BluetoothPAN Proxy object connected
,D/PanProfile( 1292): Bluetooth service connected
,D/BluetoothMap( 1292): Proxy object connected
,D/MapProfile( 1292): Bluetooth service connected
,D/BluetoothPbap( 1292): Proxy object connected
,D/PbapServerProfile( 1292): Bluetooth service connected
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1292):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1292): showing allowed
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,D/GKI_LINUX( 1936): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/SurfaceFlinger(  247): id=16 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 3928): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3928):  
D/PowerManagerService(  741): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=741
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/Atfwd_Daemon(  285): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  285): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  285): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  285): Trying to register 8 commands:
,I/Atfwd_Daemon(  285): cmd0: +CKPD
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd1: +CTSA
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd2: +CFUN
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd3: +CMAR
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd4: +CDIS
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd5: +CRSL
I/SELinux ( 3928): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3928):  
I/SELinux ( 3928):  
,I/SELinux ( 3928): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd6: +CSS
E/SELinux ( 3928): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3928): >>>>> Normal User
,E/dalvikvm( 3928): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  285): cmd7: $QCPWRDN
I/Atfwd_Daemon(  285): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  285): Registered AT Commands event handler
,E/SELinux ( 3928): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/dalvikvm( 3928): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3928): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3928): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3928): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1208): GC_EXPLICIT freed 3900K, 47% free 10042K/18936K, paused 2ms+4ms, total 39ms
,E/MTPJNIInterface( 3878): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3878): SDcard is not available
,I/PCWCLIENTTRACE_PushUtil( 3928): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3928): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3928): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 3928): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3928): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3928): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/MTPJNIInterface( 3878): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3878): SDcard is not available
E/SQLiteLog( 3878): (21) API call with NULL database connection pointer
E/SQLiteLog( 3878): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3878): (21) API call with NULL database connection pointer
E/SQLiteLog( 3878): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3878): (21) API call with NULL database connection pointer
E/SQLiteLog( 3878): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3878): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3878): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3878): notification from stack 2
D/        ( 3878): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 3878): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3878): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3878): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
