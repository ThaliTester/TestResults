#### Test 575312435db8e90_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 1309): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0041
D/WearableService( 1218): callingUid 10011, callindPid: 1218
E/MDM     ( 1218): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/dalvikvm( 1309): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 1309): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0046
D/LocationInitializer( 1647): Restart initialization of location
D/AuthorizationBluetoothService( 1309): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1309): Proximity feature is not enabled.
V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 1309): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1309): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1309): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
D/dalvikvm( 1309): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1309): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x003d
,W/GCoreFlp( 1218): No location to return for getLastLocation()
W/FusedLocationProvider( 1218): location=null
--------- beginning of /dev/log/system
V/AlarmManager(  747): waitForAlarm result :8
E/MDM     ( 1218): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/System.out( 1309): Thread-71(HTTPLog):isShipBuild true
I/System.out( 1309): Thread-71(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/LocationInitializer( 1647): Restart initialization of location
D/AuthorizationBluetoothService( 1309): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1309): Proximity feature is not enabled.
V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1218): No location to return for getLastLocation()
W/FusedLocationProvider( 1218): location=null
V/AlarmManager(  747): waitForAlarm result :8
D/QuickConnect[1.1][2] ( 3359): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1723): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1723): performUpdate:widgetCount=0
I/SELinux ( 3846): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3846):  
D/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2412): getAllContactInfoList Start
D/ContactProvider( 2412): getAllContactInfoList End
I/syncContacts( 2412): thread: 167, onChange
I/SELinux ( 3846): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3846):  
I/SELinux ( 3846):  
I/SELinux ( 3846): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3846): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3846): >>>>> Normal User
E/dalvikvm( 3846): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3846): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1309): GC_CONCURRENT freed 1560K, 44% free 10849K/19080K, paused 2ms+3ms, total 29ms
D/dalvikvm( 1309): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 1309): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/TimaKeyStoreProvider( 3846): in addTimaSignatureService
I/GCM     ( 1309): GCM config loaded
D/TimaKeyStoreProvider( 3846): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3846): Added TimaKesytore provider
D/QuickConnect[1.1][2] ( 3359): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1723): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3359): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2412): getAllContactInfoList Start
D/AndroidRuntime( 3834): 
D/AndroidRuntime( 3834): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3834): CheckJNI is OFF
D/AndroidRuntime( 3834): setted country_code = Poland
D/AndroidRuntime( 3834): setted countryiso_code = PL
D/AndroidRuntime( 3834): setted sales_code = XEO
D/AndroidRuntime( 3834): readGMSProperty: start
D/AndroidRuntime( 3834): readGMSProperty: already setted!!
D/AndroidRuntime( 3834): readGMSProperty: end
D/AndroidRuntime( 3834): addProductProperty: start
W/ActivityManager(  747): Permission Denial: getCurrentUser() from pid=3846, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3846): TaskCloserActivity enter()
D/dalvikvm( 3834): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3834): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3834): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3834): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3834): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/AlarmManager(  747): waitForAlarm result :8
I/SELinux ( 3865): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3865):  
D/ContactProvider( 2412): getAllContactInfoList End
I/syncContacts( 2412): thread: 168, onChange
E/SMD     (  240): DCD ON
I/SELinux ( 3865): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3865):  
I/SELinux ( 3865):  
I/SELinux ( 3865): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3865): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3865): >>>>> Normal User
E/dalvikvm( 3865): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3865): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3865): in addTimaSignatureService
D/TimaKeyStoreProvider( 3865): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3865): Added TimaKesytore provider
D/FactoryTestApp( 3865): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3865): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3865): User mode
E/memtrack( 3834): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3834): failed to load memtrack module: -2
I/ActivityManager(  747): Killing 2800:com.osp.app.signin/u0a43 (adj 15): empty #43
I/knox    ( 3302): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/knox    ( 3302): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3302): KNOXAgentService : onCreate()
D/knox    ( 3302): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3302): KNOXAgentService. startJobThread() start
D/knox    ( 3302): KNOXAgentService. JobThread()
D/knox    ( 3302): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3302): KNOXAgentService. startJobThread() wait
D/knox    ( 3302): KNOXAgentService : onDestroy().
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3302): ModuleBase.cancelAllAlarmManageModule()
D/dalvikvm( 3834): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 3886): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3886):  
D/AndroidRuntime( 3834): Calling main entry com.android.commands.am.Am
I/SELinux ( 3886): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3886):  
I/SELinux ( 3886):  
I/SELinux ( 3886): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3886): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3886): >>>>> Normal User
E/dalvikvm( 3886): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
E/SELinux ( 3886): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3886): in addTimaSignatureService
D/TimaKeyStoreProvider( 3886): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3886): Added TimaKesytore provider
D/AndroidRuntime( 3834): Shutting down VM
D/dalvikvm( 3834): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
E/MTPRx   ( 3886): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3886): check value of boot_completed is1
E/MTPRx   ( 3886): check booting is completed_sys.boot_completed
E/MTPRx   ( 3886): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3886): Status for mount/Unmount :removed
E/MTPRx   ( 3886): SDcard is not available
W/MTPRx   ( 3886): value of connected istrue
W/MTPRx   ( 3886): value of configured istrue
W/MTPRx   ( 3886): value of mtpEnabled istrue
W/MTPRx   ( 3886): value of ptpEnabled isfalse
E/MTPRx   ( 3886): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 3886): mFirstTime: false
D/        ( 3886): MTP: reading debug level property
E/MTPRx   ( 3886):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3886): Getting CryptionKey from JAVA
E/MTPRx   ( 3886): currentUserId is 0
E/MTPRx   ( 3886): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3886): usbMode is 0200
E/MTPRx   ( 3886): is_secretmode is NOT 1
W/MTPRx   ( 3886): Phone is lockedtrue
D/LockPatternUtils( 1069): isPcwEnable = null
D/MTPRx   ( 3886):  inside checkKnoxStatus
D/MTPRx   ( 3886):  inside checkKnoxStatus_isKnoxModeActive : false
E/MTPRx   ( 3886): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 3886): noti = 17
E/MTPRx   ( 3886): sending MTP_ICON_ENABLED to stack
E/MTPRx   ( 3886): else part ... so first time!!!
E/MTPPlaObsrvr( 3886): inside setContext()
E/MTPPlaObsrvr( 3886):  inside createplafiles
E/MTPPlaObsrvr( 3886): playlist count is0
E/MTPPlaObsrvr( 3886):  inside try branch createplafiles
E/MTPPlaObsrvr( 3886):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 3886): Inside registerContentObserver
E/MtpAdbObserver( 3886): inside setContext()
E/MtpAdbObserver( 3886): Inside registerContentObserver
W/Settings( 3886): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/SensorService(  747):   -0.0 -0.1 9.5
E/MtpService( 3886): onCreate.
D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
E/MtpService( 3886): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3886): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 3886): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
E/MtpService( 3886): onStartCommand.
W/MTPRx   ( 3886): calling native method
E/MTPJNIInterface( 3886): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3886): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3886): < MTP > Registering BroadCast receiver :::::::
E/MTPJNIInterface( 3886): noti = 10
E/MtpService( 3886): onStartCommand.
W/MTPRx   ( 3886): calling native method
E/MTPRx   ( 3886): Checking the driver time out
E/MtpService( 3886): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3886): noti = 2
D/        ( 3886): deleting sockets before message queue initialization
D/        ( 3886): event handler thread is created, so set the flag
E/MTPRx   ( 3886): called native method
E/MTPJNIInterface( 3886): Getting media scanner status0
E/MTPJNIInterface( 3886): setting Media scanner status0
E/MTPJNIInterface( 3886): After setting Media scanner status0
W/MTPRx   ( 3886): notification from stack 1
E/MTPJNIInterface( 3886): DeviceName is Galaxy S5-2
D/daemonapp( 1467): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1467): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1467): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1467): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454433780000
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454412264543
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1467): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1467): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/ConnectivityService(  747): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/AuthZen ( 1647): successfully got auth token
D/AuthZen ( 1647): Starting authzen enrollment
D/dalvikvm( 1647): GC_CONCURRENT freed 1734K, 40% free 11482K/19080K, paused 3ms+5ms, total 41ms
I/System.out( 1647): Thread-143(HTTPLog):isShipBuild true
I/System.out( 1647): Thread-143(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/dalvikvm(  747): GC_EXPLICIT freed 2051K, 14% free 23466K/27012K, paused 5ms+11ms, total 186ms
D/BluetoothNotiBroadcastReceiver( 1304): onReceive
D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/knox    ( 3302): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3302): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
I/knox    ( 3302): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3302): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3302): KNOXAgentService : onCreate()
D/knox    ( 3302): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3302): KNOXAgentService. startJobThread() start
D/knox    ( 3302): KNOXAgentService. JobThread()
D/knox    ( 3302): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3302): KNOXAgentService. startJobThread() wait
I/knox    ( 3302): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/knox    ( 3302): KNOXAgentService : onDestroy().
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/knox    ( 3302): ModuleBase.cancelAllAlarmManageModule()
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3040): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3040): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
I/SELinux ( 3919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3919):  
I/SELinux ( 3919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3919):  
I/SELinux ( 3919):  
I/SELinux ( 3919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3919): >>>>> Normal User
E/dalvikvm( 3919): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 3919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3919): in addTimaSignatureService
D/TimaKeyStoreProvider( 3919): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3919): Added TimaKesytore provider
I/System.out( 3919): Inside WakeupProvider
I/System.out( 3919): Inside onCreate() of WakeupTriggerProvide
I/VlingoApplication( 3919): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 3919): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 3919): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
I/ActivityManager(  747): Killing 2816:com.android.providers.calendar/u0a44 (adj 15): empty #43
D/DialogFlow( 3919): initQueue()
D/daemonapp( 1467): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1467): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1467): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1467): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1467): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 1467): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1467): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
I/Atfwd_Daemon(  298): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  298): ATFWD --> QMI Port : rmnet1
I/Atfwd_Daemon(  298): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  298): Trying to register 8 commands:
I/Atfwd_Daemon(  298): cmd0: +CKPD
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd1: +CTSA
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd2: +CFUN
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd3: +CMAR
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd4: +CDIS
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd5: +CRSL
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd6: +CSS
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): cmd7: $QCPWRDN
I/Atfwd_Daemon(  298): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  298): Registered AT Commands event handler
,D/LocalBluetoothProfileManager( 1304): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1304): Adding local HEADSET profile
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1304): BTStateChangeCB is registed
,E/BluetoothHeadset( 1304): BluetoothHeadset service is binded
W/ContextImpl(  747): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  747): [PWL] On : 0 (54236 ms ago)
I/PowerManagerService(  747): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  747): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1069, ws=null) (elapsedTime=16707)
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,I/AuthZen ( 1647): Enrollment phase1 complete.
,D/Bluetoothsap( 1304): bindService called to Bluetooth SAP Service
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/AuthZen ( 1647): Adding new credential
,D/AuthZen ( 1647): Encryption key data:  Account: thalitester@gmail.comCreation Time: 1454412265281Expiration Time: 1454412385281
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,I/AuthZen ( 1647): Successfully generated encryption key.
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/LockPatternUtils( 1069): isPcwEnable = null
D/LocalBluetoothProfileManager( 1304): PANU : true
,D/LocalBluetoothProfileManager( 1304): Adding local MAP profile
,D/BluetoothMap( 1304): Create BluetoothMap proxy object
,D/dalvikvm( 1206): GC_EXPLICIT freed 3901K, 48% free 10044K/19080K, paused 3ms+4ms, total 39ms
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,E/MTPJNIInterface( 3886): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3886): SDcard is not available
,I/dalvikvm( 1647): Total arena pages for JIT: 11
,I/dalvikvm( 1647): Total arena pages for JIT: 12
I/dalvikvm( 1647): Total arena pages for JIT: 13
,I/dalvikvm( 1647): Total arena pages for JIT: 14
,D/dalvikvm( 1304): GC_CONCURRENT freed 7565K, 48% free 10053K/19080K, paused 3ms+9ms, total 62ms
D/Bluetoothsap( 1304): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1304): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/DockEventReceiver( 1304): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
E/MTPJNIInterface( 3886): Status for mount/Unmount :removed
E/MTPJNIInterface( 3886): SDcard is not available
E/SQLiteLog( 3886): (21) API call with NULL database connection pointer
E/SQLiteLog( 3886): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3886): (21) API call with NULL database connection pointer
E/SQLiteLog( 3886): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3886): (21) API call with NULL database connection pointer
E/SQLiteLog( 3886): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3886): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3886): (21) misuse at line 96833 of [00bb9c9ce4]
D/        ( 3886): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,W/MTPRx   ( 3886): notification from stack 2
E/        ( 3886): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3886): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3886): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/BluetoothA2dp( 1304): Proxy object connected
,D/A2dpProfile( 1304): Bluetooth service connected

```
