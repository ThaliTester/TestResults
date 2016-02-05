#### Test 58497659c9ea290_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  730): waitForAlarm result :8
--------- beginning of /dev/log/main
D/Mms/Contact( 1670): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3334): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1670): performUpdate:widgetCount=0
D/ContactProvider( 2411): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - null 
I/SELinux ( 3840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3840):  
D/ContactProvider( 2411): getAllContactInfoList End
,I/syncContacts( 2411): thread: 164, onChange
I/SELinux ( 3840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3840):  
I/SELinux ( 3840):  
I/SELinux ( 3840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3840): >>>>> Normal User
E/dalvikvm( 3840): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/QuickConnect[1.1][2] ( 3334): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1670): sContactsObserver.onChange(),selfUpdate=false
D/TimaKeyStoreProvider( 3840): in addTimaSignatureService
D/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3334): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2411): getAllContactInfoList Start
D/TimaKeyStoreProvider( 3840): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3840): Added TimaKesytore provider
D/ContactProvider( 2411): getAllContactInfoList End
I/syncContacts( 2411): thread: 165, onChange
V/TaskCloserActivity( 3840): TaskCloserActivity enter()
W/ActivityManager(  730): Permission Denial: getCurrentUser() from pid=3840, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3855): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3855):  
I/SELinux ( 3855): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3855):  
I/SELinux ( 3855):  
I/SELinux ( 3855): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3855): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3855): >>>>> Normal User
E/dalvikvm( 3855): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3855): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3855): in addTimaSignatureService
D/TimaKeyStoreProvider( 3855): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3855): Added TimaKesytore provider
D/FactoryTestApp( 3855): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3855): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3855): User mode
I/knox    ( 3271): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/ActivityManager(  730): Killing 2807:com.osp.app.signin/u0a43 (adj 15): empty #43
W/ContextImpl( 3271): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3271): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3271): KNOXAgentService : onCreate()
D/knox    ( 3271): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3271): KNOXAgentService. startJobThread() start
D/knox    ( 3271): KNOXAgentService. JobThread()
D/knox    ( 3271): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3271): KNOXAgentService. startJobThread() wait
I/SELinux ( 3868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3868):  
D/knox    ( 3271): KNOXAgentService : onDestroy().
D/knox    ( 3271): ModuleBase.cancelAllAlarmManageModule()
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 3868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3868):  
I/SELinux ( 3868):  
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
I/SELinux ( 3868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3868): >>>>> Normal User
E/dalvikvm( 3868): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
E/SELinux ( 3868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3868): in addTimaSignatureService
D/TimaKeyStoreProvider( 3868): Cannot add TimaSignature Service, License check Failed
D/ConnectivityService(  730): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ActivityThread( 3868): Added TimaKesytore provider
E/MTPRx   ( 3868): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3868): check value of boot_completed is1
E/MTPRx   ( 3868): check booting is completed_sys.boot_completed
D/AndroidRuntime( 3853): 
D/AndroidRuntime( 3853): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/MTPRx   ( 3868): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3868): Status for mount/Unmount :removed
E/MTPRx   ( 3868): SDcard is not available
D/AndroidRuntime( 3853): CheckJNI is OFF
W/MTPRx   ( 3868): value of connected istrue
W/MTPRx   ( 3868): value of configured istrue
W/MTPRx   ( 3868): value of mtpEnabled istrue
W/MTPRx   ( 3868): value of ptpEnabled isfalse
D/AndroidRuntime( 3853): setted country_code = Poland
D/AndroidRuntime( 3853): setted countryiso_code = PL
E/MTPRx   ( 3868): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 3868): mFirstTime: false
D/AndroidRuntime( 3853): setted sales_code = XEO
D/AndroidRuntime( 3853): readGMSProperty: start
D/AndroidRuntime( 3853): readGMSProperty: already setted!!
D/AndroidRuntime( 3853): readGMSProperty: end
D/AndroidRuntime( 3853): addProductProperty: start
D/dalvikvm( 3853): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3853): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3853): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3853): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3853): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/        ( 3868): MTP: reading debug level property
E/MTPRx   ( 3868):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3868): Getting CryptionKey from JAVA
E/MTPRx   ( 3868): currentUserId is 0
E/MTPRx   ( 3868): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3868): usbMode is 0200
E/MTPRx   ( 3868): is_secretmode is NOT 1
W/MTPRx   ( 3868): Phone is lockedtrue
D/LockPatternUtils( 1069): isPcwEnable = null
D/MTPRx   ( 3868):  inside checkKnoxStatus
D/MTPRx   ( 3868):  inside checkKnoxStatus_isKnoxModeActive : false
E/MTPRx   ( 3868): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 3868): noti = 17
E/MTPRx   ( 3868): sending MTP_ICON_ENABLED to stack
E/MTPRx   ( 3868): else part ... so first time!!!
E/MTPPlaObsrvr( 3868): inside setContext()
E/MTPPlaObsrvr( 3868):  inside createplafiles
E/MTPPlaObsrvr( 3868): playlist count is0
E/MTPPlaObsrvr( 3868):  inside try branch createplafiles
E/MTPPlaObsrvr( 3868):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 3868): Inside registerContentObserver
E/MtpAdbObserver( 3868): inside setContext()
E/MtpAdbObserver( 3868): Inside registerContentObserver
W/Settings( 3868): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
E/MtpService( 3868): onCreate.
E/MtpService( 3868): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3868): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 3868): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
E/MtpService( 3868): onStartCommand.
W/MTPRx   ( 3868): calling native method
E/MTPJNIInterface( 3868): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3868): handleMessage. msg= { when=-4ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3868): < MTP > Registering BroadCast receiver :::::::
E/MTPJNIInterface( 3868): noti = 10
E/MtpService( 3868): onStartCommand.
W/MTPRx   ( 3868): calling native method
E/MTPRx   ( 3868): Checking the driver time out
E/MTPJNIInterface( 3868): noti = 2
D/        ( 3868): deleting sockets before message queue initialization
D/        ( 3868): event handler thread is created, so set the flag
D/daemonapp( 1533): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
E/MTPRx   ( 3868): called native method
E/MTPJNIInterface( 3868): setting Media scanner status0
E/MTPJNIInterface( 3868): After setting Media scanner status0
E/MtpService( 3868): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/daemonapp( 1533): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
E/MTPJNIInterface( 3868): Getting media scanner status0
W/MTPRx   ( 3868): notification from stack 1
D/daemonapp( 1533): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
E/MTPJNIInterface( 3868): DeviceName is Galaxy S5-2
D/daemonapp( 1533): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1533): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1533): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1533): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1533): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1533): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454736360000
D/daemonapp( 1533): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454714817749
D/daemonapp( 1533): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1533): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1533): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1533): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1533): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1533): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/memtrack( 3853): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3853): failed to load memtrack module: -2
I/knox    ( 3271): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/knox    ( 3271): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3271): KNOXAgentService : onCreate()
D/knox    ( 3271): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3271): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
W/ContextImpl( 3271): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3271): KNOXAgentService. startJobThread() start
D/knox    ( 3271): KNOXAgentService. JobThread()
D/knox    ( 3271): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3271): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3271): KNOXAgentService. startJobThread() wait
D/knox    ( 3271): KNOXAgentService : onDestroy().
D/knox    ( 3271): ModuleBase.cancelAllAlarmManageModule()
I/knox    ( 3271): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/dalvikvm( 3853): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/BluetoothNotiBroadcastReceiver( 1297): onReceive
D/AuthorizationBluetoothService( 1308): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3026): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3026): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
I/Atfwd_Daemon(  295): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  295): ATFWD --> QMI Port : rmnet1
I/Atfwd_Daemon(  295): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  295): Trying to register 8 commands:
I/Atfwd_Daemon(  295): cmd0: +CKPD
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd1: +CTSA
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd2: +CFUN
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd3: +CMAR
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd4: +CDIS
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd5: +CRSL
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd6: +CSS
D/AndroidRuntime( 3853): Calling main entry com.android.commands.am.Am
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): cmd7: $QCPWRDN
I/Atfwd_Daemon(  295): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  295): Registered AT Commands event handler
I/SELinux ( 3908): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3908):  
I/SELinux ( 3908): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3908):  
I/SELinux ( 3908):  
I/SELinux ( 3908): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3908): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3908): >>>>> Normal User
E/dalvikvm( 3908): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 3908): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3908): in addTimaSignatureService
D/AndroidRuntime( 3853): Shutting down VM
D/dalvikvm( 3853): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+1ms, total 3ms
D/TimaKeyStoreProvider( 3908): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3908): Added TimaKesytore provider
I/System.out( 3908): Inside WakeupProvider
I/System.out( 3908): Inside onCreate() of WakeupTriggerProvide
I/VlingoApplication( 3908): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 3908): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 3908): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
I/ActivityManager(  730): Waited long enough for: ServiceRecord{43528da8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3908): initQueue()
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1297): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1297): Adding local HEADSET profile
,E/BluetoothHeadset( 1297): BTStateChangeCB is registed
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/dalvikvm(  730): GC_EXPLICIT freed 1869K, 14% free 23484K/27252K, paused 4ms+9ms, total 117ms
,E/BluetoothHeadset( 1297): BluetoothHeadset service is binded
,D/Bluetoothsap( 1297): bindService called to Bluetooth SAP Service
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
I/PowerManagerService(  730): [PWL] On : 0 (54475 ms ago)
I/PowerManagerService(  730): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  730): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1069, ws=null) (elapsedTime=16726)
,D/LocalBluetoothProfileManager( 1297): PANU : true
,D/LocalBluetoothProfileManager( 1297): Adding local MAP profile
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl(  730): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BluetoothMap( 1297): Create BluetoothMap proxy object
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1297): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1297): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/dalvikvm( 1297): GC_CONCURRENT freed 7548K, 48% free 10085K/19176K, paused 4ms+4ms, total 60ms
,D/DockEventReceiver( 1297): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1297): onReceive
,D/BluetoothA2dp( 1297): Proxy object connected
,D/A2dpProfile( 1297): Bluetooth service connected
,D/BtConfig.SecureMode( 1958): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1308): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1308): Proximity feature is not enabled.
,D/HeadsetProfile( 1297): Bluetooth service connected
,D/BluetoothInputDevice( 1297): Proxy object connected
,D/HidProfile( 1297): Bluetooth service connected
,D/BluetoothPan( 1297): BluetoothPAN Proxy object connected
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/PanProfile( 1297): Bluetooth service connected
D/BluetoothMap( 1297): Proxy object connected
D/MapProfile( 1297): Bluetooth service connected
D/BluetoothPbap( 1297): Proxy object connected
,D/PbapServerProfile( 1297): Bluetooth service connected
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/BluetoothAdapter( 1958): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1958): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1958): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1958): Accept thread started.
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,D/dalvikvm( 1208): GC_EXPLICIT freed 3900K, 48% free 10048K/19176K, paused 3ms+5ms, total 50ms
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,E/MTPJNIInterface( 3868): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3868): SDcard is not available
,D/Toast   ( 1297):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1297): showing allowed
E/MTPJNIInterface( 3868): Status for mount/Unmount :removed
E/MTPJNIInterface( 3868): SDcard is not available
E/SQLiteLog( 3868): (21) API call with NULL database connection pointer
E/SQLiteLog( 3868): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3868): (21) API call with NULL database connection pointer
E/SQLiteLog( 3868): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3868): (21) API call with NULL database connection pointer
E/SQLiteLog( 3868): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3868): (21) API call with NULL database connection pointer
E/SQLiteLog( 3868): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3868): notification from stack 2
D/        ( 3868): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3868): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3868): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 3868): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state

```
