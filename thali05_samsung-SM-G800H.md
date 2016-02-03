#### Test 58135655c662d33_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/System.out( 3637): Thread-360 calls detatch()
I/SystemUpdateService( 1783): cancelUpdate (empty URL)
I/SystemUpdateService( 1783): active receiver: disabled
I/GCoreUlr( 1218): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1300): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1300): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0059
D/SystemUpdateService( 1783): onDestroy
,I/dalvikvm( 1300): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1300): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0022
D/AuthZenEventHandler( 1783): Handling event: android.intent.action.BOOT_COMPLETED
D/EnterpriseDeviceManagerService(  744): Creating context as user 0
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
I/GCoreUlr( 1218): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 1218): Unbound from all location providers
I/GCoreUlr( 1218): Place inference reporting - stopped
D/dalvikvm( 1300): GC_EXPLICIT freed 301K, 44% free 10791K/18976K, paused 3ms+6ms, total 39ms
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1783): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x00bb
E/BaseAppContext( 1783): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/GCM     ( 1300): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1300): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1300): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0053
I/GCoreUlr( 1218): DispatchingService.onDestroy()
I/GCoreUlr( 1218): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1218): Unbound from all location providers
I/GCoreUlr( 1218): Place inference reporting - stopped
I/dalvikvm( 1783): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x002f
W/Auth    ( 1300): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/AuthZen ( 1783): Fetching signing key...
V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtils( 1066): isPcwEnable = null
I/AuthZen ( 1783): Signing key fetched successfully!
D/PersistentNotificationBroadcastReceiver( 1218): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
D/AuthZenTransactionCache( 1783): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1783): Clearing transaction cache
I/GCM     ( 1300): GCM config loaded
D/AndroidRuntime( 3809): 
D/AndroidRuntime( 3809): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3809): CheckJNI is OFF
D/AndroidRuntime( 3809): setted country_code = Poland
D/AndroidRuntime( 3809): setted countryiso_code = PL
D/AndroidRuntime( 3809): setted sales_code = XEO
D/AndroidRuntime( 3809): readGMSProperty: start
D/AndroidRuntime( 3809): readGMSProperty: already setted!!
D/AndroidRuntime( 3809): readGMSProperty: end
D/AndroidRuntime( 3809): addProductProperty: start
--------- beginning of /dev/log/system
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/WearableService( 1218): callingUid 10011, callindPid: 1218
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
D/LocationInitializer( 1783): Restart initialization of location
E/MDM     ( 1218): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/dalvikvm( 3809): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3809): Added shared lib libjavacore.so 0x0
D/AuthorizationBluetoothService( 1300): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
D/dalvikvm( 3809): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3809): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3809): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  744): waitForAlarm result :8
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1667): performUpdate:widgetCount=0
D/QuickConnect[1.1][2] ( 3341): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getMyMobileNumber - 
D/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getMyMobileNumber - null 
W/GCoreFlp( 1218): No location to return for getLastLocation()
W/FusedLocationProvider( 1218): location=null
E/SMD     (  243): DCD ON
D/ContactProvider( 2414): getAllContactInfoList Start
E/MDM     ( 1218): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/AlarmManager(  744): waitForAlarm result :8
D/LocationInitializer( 1783): Restart initialization of location
D/AuthorizationBluetoothService( 1300): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
D/QuickConnect[1.1][2] ( 3341): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1667): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3341): CONTACT_Info.getMyMobileNumber - null 
V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ContactProvider( 2414): getAllContactInfoList End
I/syncContacts( 2414): thread: 167, onChange
E/memtrack( 3809): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3809): failed to load memtrack module: -2
I/SELinux ( 3865): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3865):  
W/GCoreFlp( 1218): No location to return for getLastLocation()
W/FusedLocationProvider( 1218): location=null
D/ContactProvider( 2414): getAllContactInfoList Start
V/AlarmManager(  744): waitForAlarm result :8
D/dalvikvm( 3809): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/ContactProvider( 2414): getAllContactInfoList End
I/SELinux ( 3865): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3865):  
I/SELinux ( 3865):  
I/SELinux ( 3865): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/syncContacts( 2414): thread: 167, onChange
E/SELinux ( 3865): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3865): >>>>> Normal User
E/dalvikvm( 3865): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3865): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1783): GC_CONCURRENT freed 1700K, 39% free 11680K/18976K, paused 13ms+14ms, total 58ms
D/TimaKeyStoreProvider( 3865): in addTimaSignatureService
D/TimaKeyStoreProvider( 3865): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3865): Added TimaKesytore provider
D/AndroidRuntime( 3809): Calling main entry com.android.commands.am.Am
V/TaskCloserActivity( 3865): TaskCloserActivity enter()
W/ActivityManager(  744): Permission Denial: getCurrentUser() from pid=3865, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3879): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3879):  
D/AndroidRuntime( 3809): Shutting down VM
D/dalvikvm( 3809): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 3ms
D/SensorService(  744):   -0.0 -0.1 9.6
I/SELinux ( 3879): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3879):  
I/SELinux ( 3879):  
I/SELinux ( 3879): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3879): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3879): >>>>> Normal User
E/dalvikvm( 3879): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3879): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3879): in addTimaSignatureService
D/TimaKeyStoreProvider( 3879): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3879): Added TimaKesytore provider
D/FactoryTestApp( 3879): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3879): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3879): User mode
I/knox    ( 3285): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/knox    ( 3285): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/ActivityManager(  744): Killing 2805:com.osp.app.signin/u0a43 (adj 15): empty #43
W/ContextImpl( 3285): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3285): KNOXAgentService : onCreate()
D/knox    ( 3285): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3285): KNOXAgentService. startJobThread() start
D/knox    ( 3285): KNOXAgentService. JobThread()
D/knox    ( 3285): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3285): KNOXAgentService. startJobThread() wait
D/knox    ( 3285): KNOXAgentService : onDestroy().
D/knox    ( 3285): ModuleBase.cancelAllAlarmManageModule()
I/SELinux ( 3894): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3894):  
D/ConnectivityService(  744): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 3894): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3894):  
I/SELinux ( 3894):  
I/SELinux ( 3894): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3894): >>>>> Normal User
E/dalvikvm( 3894): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
E/SELinux ( 3894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3894): in addTimaSignatureService
D/TimaKeyStoreProvider( 3894): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3894): Added TimaKesytore provider
,E/MTPRx   ( 3894): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3894): check value of boot_completed is1
,E/MTPRx   ( 3894): check booting is completed_sys.boot_completed
E/MTPRx   ( 3894): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3894): Status for mount/Unmount :removed
,E/MTPRx   ( 3894): SDcard is not available
,W/MTPRx   ( 3894): value of connected istrue
W/MTPRx   ( 3894): value of configured istrue
W/MTPRx   ( 3894): value of mtpEnabled istrue
,W/MTPRx   ( 3894): value of ptpEnabled isfalse
E/MTPRx   ( 3894): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3894): mFirstTime: false
,D/        ( 3894): MTP: reading debug level property
,E/MTPRx   ( 3894):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3894): Getting CryptionKey from JAVA
,E/MTPRx   ( 3894): currentUserId is 0
,E/MTPRx   ( 3894): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3894): usbMode is 0200
,E/MTPRx   ( 3894): is_secretmode is NOT 1
,W/MTPRx   ( 3894): Phone is lockedtrue
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/MTPRx   ( 3894):  inside checkKnoxStatus
,D/MTPRx   ( 3894):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3894): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3894): noti = 17
,E/MTPRx   ( 3894): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3894): else part ... so first time!!!
E/MTPPlaObsrvr( 3894): inside setContext()
,E/MTPPlaObsrvr( 3894):  inside createplafiles
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,D/dalvikvm(  744): GC_EXPLICIT freed 2061K, 13% free 23519K/26968K, paused 7ms+11ms, total 128ms
E/MTPPlaObsrvr( 3894): playlist count is0
,E/MTPPlaObsrvr( 3894):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3894):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3894): Inside registerContentObserver
E/MtpAdbObserver( 3894): inside setContext()
,E/MtpAdbObserver( 3894): Inside registerContentObserver
,W/Settings( 3894): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3894): onCreate.
,E/MtpService( 3894): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3894): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3894): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3894): onStartCommand.
,E/MtpService( 3894): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 3894): calling native method
,E/MTPJNIInterface( 3894): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3894): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3894): noti = 10
,E/MtpService( 3894): onStartCommand.
,E/MtpService( 3894): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3894): calling native method
E/MTPRx   ( 3894): Checking the driver time out
E/MTPJNIInterface( 3894): noti = 2
,D/        ( 3894): deleting sockets before message queue initialization
D/        ( 3894): event handler thread is created, so set the flag
D/daemonapp( 1467): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
E/MTPRx   ( 3894): called native method
E/MTPJNIInterface( 3894): Getting media scanner status0
E/MTPJNIInterface( 3894): setting Media scanner status0
E/MTPJNIInterface( 3894): After setting Media scanner status0
E/MTPJNIInterface( 3894): DeviceName is Galaxy S5-2
,W/MTPRx   ( 3894): notification from stack 1
,D/daemonapp( 1467): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1467): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1467): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454544660000
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454523114622
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1467): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1467): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,D/AuthorizationBluetoothService( 1300): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3285): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3285): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3285): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3285): KNOXAgentService : onCreate()
D/knox    ( 3285): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3285): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3285): KNOXAgentService. startJobThread() start
D/knox    ( 3285): KNOXAgentService. JobThread()
D/knox    ( 3285): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3285): KNOXAgentService. startJobThread() wait
D/knox    ( 3285): KNOXAgentService : onDestroy().
D/knox    ( 3285): ModuleBase.cancelAllAlarmManageModule()
D/knox    ( 3285): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
,I/knox    ( 3285): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/FileShare-Server( 3043): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 3043): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3923): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3923):  
,I/SELinux ( 3923): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3923):  
I/SELinux ( 3923):  
,I/SELinux ( 3923): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3923): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3923): >>>>> Normal User
,E/dalvikvm( 3923): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3923): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3923): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3923): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3923): Added TimaKesytore provider
,I/System.out( 3923): Inside WakeupProvider
,I/System.out( 3923): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3923): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3923): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3923): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/Atfwd_Daemon(  299): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  299): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  299): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  299): Trying to register 8 commands:
,I/Atfwd_Daemon(  299): cmd0: +CKPD
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd1: +CTSA
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd2: +CFUN
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd3: +CMAR
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd4: +CDIS
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd5: +CRSL
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd6: +CSS
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): cmd7: $QCPWRDN
I/Atfwd_Daemon(  299): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  299): Registered AT Commands event handler
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3923): initQueue()
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1318): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1318): Adding local HEADSET profile
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1318): BTStateChangeCB is registed
,E/BluetoothHeadset( 1318): BluetoothHeadset service is binded
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1318): bindService called to Bluetooth SAP Service
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1318): PANU : true
,D/LocalBluetoothProfileManager( 1318): Adding local MAP profile
,D/BluetoothMap( 1318): Create BluetoothMap proxy object
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1318): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1318): LocalBluetoothProfileManager construction complete
,D/dalvikvm( 1318): GC_CONCURRENT freed 7564K, 47% free 10067K/18976K, paused 3ms+3ms, total 45ms
W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/DockEventReceiver( 1318): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,D/BluetoothA2dp( 1318): Proxy object connected
,D/A2dpProfile( 1318): Bluetooth service connected
,D/BtConfig.SecureMode( 1938): isSecureModeOn:false
,D/HeadsetProfile( 1318): Bluetooth service connected
D/AuthorizationBluetoothService( 1300): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
,D/BluetoothInputDevice( 1318): Proxy object connected
,D/HidProfile( 1318): Bluetooth service connected
,D/BluetoothPan( 1318): BluetoothPAN Proxy object connected
,D/PanProfile( 1318): Bluetooth service connected
,D/BluetoothMap( 1318): Proxy object connected
D/MapProfile( 1318): Bluetooth service connected
D/BluetoothPbap( 1318): Proxy object connected
D/PbapServerProfile( 1318): Bluetooth service connected
W/BluetoothAdapter( 1938): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1938): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 1938): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1938): Accept thread started.
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1318):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1318): showing allowed
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=4, Uoast
W/ContextImpl(  744): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  744): [PWL] On : 0 (54369 ms ago)
I/PowerManagerService(  744): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService(  744): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1066, ws=null) (elapsedTime=16889)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/GKI_LINUX( 1938): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/PowerManagerService(  744): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=744
D/DisplayPowerController(  744): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  744): [s] mDisplayPowerControllerCallbacks : onStateChanged()
I/SELinux ( 3955): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3955):  
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/lights  (  744): lcd : 8 +
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/RampAnimator(  744): Light Animator Finished currentValue=8
,D/lights  (  744): lcd : 8 -
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3955): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3955):  
I/SELinux ( 3955):  
,I/SELinux ( 3955): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3955): >>>>> Normal User
,E/dalvikvm( 3955): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 3955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1206): GC_EXPLICIT freed 3900K, 48% free 10047K/18976K, paused 2ms+5ms, total 38ms
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/dalvikvm( 3955): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3955): in addTimaSignatureService
,E/MTPJNIInterface( 3894): Status for mount/Unmount :removed
E/MTPJNIInterface( 3894): SDcard is not available
,D/TimaKeyStoreProvider( 3955): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3955): Added TimaKesytore provider
,E/MTPJNIInterface( 3894): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3894): SDcard is not available
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3894): (21) API call with NULL database connection pointer
E/SQLiteLog( 3894): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3894): notification from stack 2
,D/        ( 3894): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3894): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3894): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3894): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
