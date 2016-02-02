#### Test 5797209499148df_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
,I/SELinux ( 3810): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3810):  
D/QuickConnect[1.1][2] ( 3309): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1666): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 1666): performUpdate:widgetCount=0
D/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2414): getAllContactInfoList Start
D/ContactProvider( 2414): getAllContactInfoList End
I/syncContacts( 2414): thread: 164, onChange
I/SELinux ( 3810): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3810):  
I/SELinux ( 3810):  
I/SELinux ( 3810): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3810): >>>>> Normal User
E/dalvikvm( 3810): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3810): in addTimaSignatureService
D/TimaKeyStoreProvider( 3810): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3810): Added TimaKesytore provider
D/QuickConnect[1.1][2] ( 3309): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 1666): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getAccountNumber - ($)
I/QuickConnect[1.1][2] ( 3309): CONTACT_Info.getMyMobileNumber - null 
D/ContactProvider( 2414): getAllContactInfoList Start
D/ContactProvider( 2414): getAllContactInfoList End
I/syncContacts( 2414): thread: 165, onChange
V/TaskCloserActivity( 3810): TaskCloserActivity enter()
--------- beginning of /dev/log/system
W/ActivityManager(  744): Permission Denial: getCurrentUser() from pid=3810, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3828):  
I/SELinux ( 3828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3828):  
I/SELinux ( 3828):  
I/SELinux ( 3828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3828): >>>>> Normal User
E/dalvikvm( 3828): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
E/SELinux ( 3828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3828): in addTimaSignatureService
D/TimaKeyStoreProvider( 3828): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3828): Added TimaKesytore provider
D/ConnectivityService(  744): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/FactoryTestApp( 3828): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 3828): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
D/FactoryTest( 3828): User mode
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
I/ActivityManager(  744): Killing 2794:com.osp.app.signin/u0a43 (adj 15): empty #43
I/knox    ( 3252): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/knox    ( 3252): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3252): KNOXAgentService : onCreate()
D/knox    ( 3252): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3252): KNOXAgentService. startJobThread() start
D/knox    ( 3252): KNOXAgentService. JobThread()
D/knox    ( 3252): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3252): KNOXAgentService. startJobThread() wait
W/ContextImpl( 3252): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3841): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3841):  
D/knox    ( 3252): KNOXAgentService : onDestroy().
D/knox    ( 3252): ModuleBase.cancelAllAlarmManageModule()
I/SELinux ( 3841): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3841):  
I/SELinux ( 3841):  
I/SELinux ( 3841): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3841): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3841): >>>>> Normal User
E/dalvikvm( 3841): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
E/SELinux ( 3841): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3841): in addTimaSignatureService
D/TimaKeyStoreProvider( 3841): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3841): Added TimaKesytore provider
D/AndroidRuntime( 3817): 
D/AndroidRuntime( 3817): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3817): CheckJNI is OFF
D/AndroidRuntime( 3817): setted country_code = Poland
D/AndroidRuntime( 3817): setted countryiso_code = PL
D/AndroidRuntime( 3817): setted sales_code = XEO
D/AndroidRuntime( 3817): readGMSProperty: start
D/AndroidRuntime( 3817): readGMSProperty: already setted!!
D/AndroidRuntime( 3817): readGMSProperty: end
D/AndroidRuntime( 3817): addProductProperty: start
D/dalvikvm( 3817): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3817): Added shared lib libjavacore.so 0x0
E/MTPRx   ( 3841): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3841): check value of boot_completed is1
E/MTPRx   ( 3841): check booting is completed_sys.boot_completed
D/dalvikvm( 3817): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3817): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3817): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/MTPRx   ( 3841): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3841): Status for mount/Unmount :removed
E/MTPRx   ( 3841): SDcard is not available
W/MTPRx   ( 3841): value of connected istrue
W/MTPRx   ( 3841): value of configured istrue
W/MTPRx   ( 3841): value of mtpEnabled istrue
W/MTPRx   ( 3841): value of ptpEnabled isfalse
E/MTPRx   ( 3841): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 3841): mFirstTime: false
D/        ( 3841): MTP: reading debug level property
E/MTPRx   ( 3841):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3841): Getting CryptionKey from JAVA
E/MTPRx   ( 3841): currentUserId is 0
E/MTPRx   ( 3841): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3841): usbMode is 0200
E/MTPRx   ( 3841): is_secretmode is NOT 1
W/MTPRx   ( 3841): Phone is lockedtrue
D/LockPatternUtils( 1065): isPcwEnable = null
D/MTPRx   ( 3841):  inside checkKnoxStatus
D/MTPRx   ( 3841):  inside checkKnoxStatus_isKnoxModeActive : false
E/MTPRx   ( 3841): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 3841): noti = 17
E/MTPRx   ( 3841): sending MTP_ICON_ENABLED to stack
E/MTPRx   ( 3841): else part ... so first time!!!
E/MTPPlaObsrvr( 3841): inside setContext()
E/MTPPlaObsrvr( 3841):  inside createplafiles
E/MTPPlaObsrvr( 3841): playlist count is0
E/MTPPlaObsrvr( 3841):  inside try branch createplafiles
E/MTPPlaObsrvr( 3841):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 3841): Inside registerContentObserver
E/MtpAdbObserver( 3841): inside setContext()
E/MtpAdbObserver( 3841): Inside registerContentObserver
W/Settings( 3841): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
E/MtpService( 3841): onCreate.
D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
E/MtpService( 3841): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3841): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 3841): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
E/MtpService( 3841): onStartCommand.
W/MTPRx   ( 3841): calling native method
E/MTPJNIInterface( 3841): < MTP > Registering BroadCast receiver :::::
E/MtpService( 3841): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3841): < MTP > Registering BroadCast receiver :::::::
I/knox    ( 3252): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/MTPJNIInterface( 3841): noti = 10
E/MtpService( 3841): onStartCommand.
W/MTPRx   ( 3841): calling native method
E/MTPRx   ( 3841): Checking the driver time out
E/MTPJNIInterface( 3841): noti = 2
D/        ( 3841): deleting sockets before message queue initialization
D/        ( 3841): event handler thread is created, so set the flag
E/MTPRx   ( 3841): called native method
E/MTPJNIInterface( 3841): setting Media scanner status0
E/MTPJNIInterface( 3841): After setting Media scanner status0
E/MTPJNIInterface( 3841): Getting media scanner status0
W/MTPRx   ( 3841): notification from stack 1
E/MTPJNIInterface( 3841): DeviceName is Galaxy S5-2
E/MtpService( 3841): handleMessage. msg= { when=-5ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
I/knox    ( 3252): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3252): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3252): KNOXAgentService : onCreate()
D/knox    ( 3252): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3252): KNOXAgentService. startJobThread() start
D/knox    ( 3252): KNOXAgentService. JobThread()
D/knox    ( 3252): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3252): KNOXAgentService. startJobThread() wait
D/knox    ( 3252): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3252): KNOXAgentService : onDestroy().
D/knox    ( 3252): ModuleBase.cancelAllAlarmManageModule()
D/knox    ( 3252): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/daemonapp( 1461): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1461): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
I/knox    ( 3252): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
E/memtrack( 3817): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3817): failed to load memtrack module: -2
D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1461): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1461): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1461): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1461): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454438040000
D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454416511660
D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1461): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1461): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1461): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1461): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/dalvikvm( 3817): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/BluetoothNotiBroadcastReceiver( 1301): onReceive
D/AuthorizationBluetoothService( 1314): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3011): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3011): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
D/AndroidRuntime( 3817): Calling main entry com.android.commands.am.Am
I/SELinux ( 3877): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3877):  
I/SELinux ( 3877): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3877):  
I/SELinux ( 3877):  
I/SELinux ( 3877): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3877): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3877): >>>>> Normal User
E/dalvikvm( 3877): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 3877): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3877): in addTimaSignatureService
D/AndroidRuntime( 3817): Shutting down VM
D/dalvikvm( 3817): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 3ms
D/TimaKeyStoreProvider( 3877): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3877): Added TimaKesytore provider
I/System.out( 3877): Inside WakeupProvider
I/System.out( 3877): Inside onCreate() of WakeupTriggerProvide
I/VlingoApplication( 3877): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 3877): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 3877): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/dalvikvm(  744): GC_EXPLICIT freed 1919K, 13% free 23415K/26712K, paused 4ms+11ms, total 122ms
D/DialogFlow( 3877): initQueue()
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/SMD     (  240): DCD ON
D/LocalBluetoothProfileManager( 1301): Adding local A2DP profile
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 1301): Adding local HEADSET profile
E/BluetoothHeadset( 1301): BTStateChangeCB is registed
E/BluetoothHeadset( 1301): BluetoothHeadset service is binded
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
D/SensorService(  744):   -0.0 -0.1 9.6
D/Bluetoothsap( 1301): bindService called to Bluetooth SAP Service
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 1301): PANU : true
D/LocalBluetoothProfileManager( 1301): Adding local MAP profile
D/BluetoothMap( 1301): Create BluetoothMap proxy object
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 1301): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 1301): LocalBluetoothProfileManager construction complete
D/dalvikvm( 1301): GC_CONCURRENT freed 7565K, 47% free 10063K/18956K, paused 3ms+4ms, total 53ms
D/DockEventReceiver( 1301): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1301): onReceive
D/BluetoothA2dp( 1301): Proxy object connected
D/A2dpProfile( 1301): Bluetooth service connected
D/BtConfig.SecureMode( 1952): isSecureModeOn:false
D/AuthorizationBluetoothService( 1314): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1314): Proximity feature is not enabled.
D/HeadsetProfile( 1301): Bluetooth service connected
D/BluetoothInputDevice( 1301): Proxy object connected
W/BluetoothAdapter( 1952): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1952): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 1952): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/BtOppRfcommListener( 1952): Accept thread started.
D/HidProfile( 1301): Bluetooth service connected
D/BluetoothPan( 1301): BluetoothPAN Proxy object connected
D/PanProfile( 1301): Bluetooth service connected
D/BluetoothMap( 1301): Proxy object connected
D/dalvikvm( 1203): GC_EXPLICIT freed 3900K, 47% free 10046K/18956K, paused 3ms+6ms, total 50ms
D/MapProfile( 1301): Bluetooth service connected
D/BluetoothPbap( 1301): Proxy object connected
D/PbapServerProfile( 1301): Bluetooth service connected
E/MTPJNIInterface( 3841): Status for mount/Unmount :removed
E/MTPJNIInterface( 3841): SDcard is not available
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
E/MTPJNIInterface( 3841): Status for mount/Unmount :removed
E/MTPJNIInterface( 3841): SDcard is not available
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3841): notification from stack 2
D/        ( 3841): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3841): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3841): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 3841): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
