#### Test 61248225a3bd1fe_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2751): TimaSignature is unavailable
D/ActivityThread( 2751): Added TimaKeyStore provider
--------- beginning of system
W/ResourcesManager( 2751): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2751): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/CursorWrapperInner( 2364): Cursor finalized without prior close()
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1020): Killing 1190:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
E/SmartFaceService( 1020): onReceive: android.intent.action.BOOT_COMPLETED
D/SmartFaceIndicator( 1020): no icon
E/SmartFaceService( 1020): mActiveServiceType: 0
E/SmartFaceService( 1020): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1020): updateClientsDone. def. do nothing.
E/SmartFaceService( 1020): Service Type to Worker: 0
E/SmartFaceService( 1020): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1020): Last Smart Pause clients: 0 Current Smart Pause clients: 0
V/AlarmManagerEXT( 1020): mGmsLocationBundling: false
D/RCPManagerService( 1020): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1020):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
D/RCPManagerService( 1020): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/RCPManagerService( 1020):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
D/MotionRecognitionService( 1020):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1190/cgroup.procs: No such file or directory
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=0)
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/SensorManager( 1020): unregisterListener ::   
I/ActivityManager( 1020): Killing 1401:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
D/BluetoothAdapterState( 2614): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2614): enable
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 200000000(ns)
I/bt_hci_bdroid( 2614): init
I/GKI_LINUX( 2614): gki_task_entry task_id=0 [BTU] starting
D/SensorService( 1020): [SO] changed settle time [0]
D/SensorService( 1020): [SO] setDelay [200000000]
D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/bt_vendor( 2614): bt-vendor : init
I/bt_vendor( 2614): bt-vendor : get_bt_soc_type
E/bt_vendor( 2614): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 2614): init: Local BD Address : 27:76:50:a9:ec:08
D/bt_userial_mct( 2614): userial_init
I/bt_vendor( 2614): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2614): Starting hciattach daemon
I/bt_vendor( 2614): try to set false
I/bt_vendor( 2614): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 2614): Starting hciattach daemon
I/bt_vendor( 2614): try to set true
D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/EnterpriseDeviceManagerService( 1020): android.intent.action.BOOT_COMPLETED
V/ApplicationPolicy( 1020): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1020): refresh widget status for user 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.vending
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.email
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BadgeProvider( 1581): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
D/EnterpriseDeviceManagerService( 1020): runAdminUpdate
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
D/EnterpriseUtils( 1020): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1020): nothing to selfUpdate
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
D/Launcher.Model( 1483): reloadBadges entered.
D/BadgeProvider( 1581): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1581): sendNotify, [notify] : null
D/BadgeProvider( 1581): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1581): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1581): update, [UpdateCount] : 1
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
I/i       ( 1020): No model
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/FactoryTest( 1020): Not factory mode
D/FactoryTest( 1020): Not factory mode. isFactoryMode() returend false
D/w       ( 1020): isUserBuild = true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/qcom-bluetooth( 2802): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/SSRM:n  ( 1020): SIOP:: AP = 370
W/libprocessgroup( 1020): failed to open /acct/uid_10092/pid_1401/cgroup.procs: No such file or directory
W/PhoneRestrictionPolicy( 1020): Message received - msg { when=-3ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1020): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
E/ConnectivityChangeReceiver( 2038): Ignoring connectivity change
W/PhoneRestrictionPolicy( 1020):  >>>> deliveryBlockedMsgs
I/KnoxMUMContainerPolicy( 1020): MSG_REMOVE_ORPHANED_CONTAINERS received
D/SSRM:a  ( 1020): DeviceInfo:: 000000000000
D/SSRM:a  ( 1020): SettingsAirViewInfo:: 000000000
D/WifiP2pService( 1020): InactiveState{ what=143415 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143415 }
D/WifiP2pService( 1020): DefaultState{ what=143415 }
D/ConnectivityService( 1020): Got NetworkFactory Messenger for WIFI_P2P
D/WIFI_P2P( 1020): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/qcom-bluetooth( 2811): /system/etc/init.qcom.bt.sh: Transport : smd 
W/PhoneRestrictionPolicy( 1020): cvList size 0
W/PhoneRestrictionPolicy( 1020):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1020): cvList size 0
D/ConnectivityService( 1020): Got NetworkFactory Messenger for WIFI
I/qcom-bluetooth( 2812): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/Tethering( 1020): Boot complete.
V/EnterpriseBillingEngine( 1020): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1020): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1020): getCurrentActiveProfiles - start - 
V/EnterpriseBillingPolicyStorage( 1020): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1020): handleAllprofiles - end
D/ConnectivityManager( 2038): CallingUid : 10011, CallingPid : 2038
E/WifiStateMachine( 1020): Blacklist file delete
D/UsbHostNotification( 1020): boot completed
I/qcom-bluetooth( 2816): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/ConnectivityService( 1020): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2038): CM callback handler got msg 524290
D/ConnectivityService( 1020): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityService( 1020): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1020): apparently satisfied.  currentScore=60
D/UsbHostRestrictor( 1020): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1020): initSetUsbBlock STARTED
I/qcom-bluetooth( 2817): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
I/qcom-bluetooth( 2818): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 2820): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/UsbHostRestrictor( 1020): SIM was never inserted
D/UsbHostRestrictor( 1020): writableHostSysNode[false]
D/UsbHostRestrictor( 1020): Can NOT Write Disable Sys Node to [ON]
D/PersonaManagerService( 1020): ACTION_BOOT_COMPLETED
D/UsbStorageNotification( 1020): boot completed
E/PersonaManagerServiceHandler( 1020):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/StorageNotification( 1173): boot completed
D/WIFI    ( 1020): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/KnoxKeyguardUpdateMonitor( 1020): onBootComplete
D/GpsLocationProvider( 1020): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1020): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1020): set_capabilities_callback: 55u
I/KnoxKeyguardUpdateMonitor( 1020): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1020): onTrustChanged user:0, enable:false
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
D/KeyguardViewMediator( 1173): onTrustChanged( Showing = false , userId = 0 )
E/LocSvc_api_v02( 1020): I/locClientOpen:2279]: Service instance id is -1
E/Geofence_Adapter( 1020): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1020): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1020): BOOT_COMPLETED native_cleanup 
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2832): MountEmulatedStorage()
E/Zygote  ( 2832): v2
I/libpersona( 2832): KNOX_SDCARD checking this for 10087
I/libpersona( 2832): KNOX_SDCARD not a persona
I/SELinux ( 2832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=2832 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2832): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService( 1020): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1173): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2832): TimaSignature is unavailable
D/ActivityThread( 2832): Added TimaKeyStore provider
E/Zygote  ( 2847): MountEmulatedStorage()
E/Zygote  ( 2847): v2
I/libpersona( 2847): KNOX_SDCARD checking this for 1000
I/libpersona( 2847): KNOX_SDCARD not a persona
I/SELinux ( 2847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2847 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/SensorService( 1020): [SO] currT = 31061093000, prevT = 30581044000, diff = 480049000, [-0.364 0.249 9.864]
D/SensorService( 1020): [SO] -0.364 0.249 9.864
D/SensorService( 1020): [SO] [100 -> 255]
D/TimaKeyStoreProvider( 2847): TimaSignature is unavailable
D/ActivityThread( 2847): Added TimaKeyStore provider
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1020): qmi_secgps_client_init()
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
I/qcom-bluetooth( 2864): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
I/qcom-bluetooth( 2867): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/art     ( 1020): Explicit concurrent mark sweep GC freed 48973(2MB) AllocSpace objects, 16(280KB) LOS objects, 33% free, 22MB/33MB, paused 2.750ms total 181.776ms
,I/bt_vendor( 2614): bluetooth satus is on
E/USB_UICC(  299): Timeout! No signal received. Retry num = 25
D/bt_userial_mct( 2614): userial_open(port:0)
I/bt_vendor( 2614): bt-vendor : BT_VND_OP_USERIAL_OPEN
E/SMD     (  290): DCD OFF
I/bt_vendor( 2614): Done intiailizing UART
I/bt_vendor( 2614): Done intiailizing UART
I/bt_userial_mct( 2614): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2614): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2614): Entering userial_read_thread()
E/LocSvc_utils_cfg( 1020): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1020): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
W/ContextImpl( 2847): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
I/splitIntent( 1020): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
I/splitIntent( 1020): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
D/DocsApplication( 2832): Installing DEX configuration.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1020): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1020): SECGPS: Set GNSS RF CONFIG : 1
E/Zygote  ( 2876): MountEmulatedStorage()
E/Zygote  ( 2876): v2
I/libpersona( 2876): KNOX_SDCARD checking this for 10097
I/libpersona( 2876): KNOX_SDCARD not a persona
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1020): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
I/ActivityManager( 1020): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2876 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2876): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/        ( 2614): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2614): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2614): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2614): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2614): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2614): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2614): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2614): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2614): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2614): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2614): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2614): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2614): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2614): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2614): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2614): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2614): BTE_InitTraceLevels -- TRC_PROTOCOL
E/Zygote  ( 2888): MountEmulatedStorage()
E/Zygote  ( 2888): v2
I/libpersona( 2888): KNOX_SDCARD checking this for 10081
I/libpersona( 2888): KNOX_SDCARD not a persona
I/SELinux ( 2888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 2876): TimaSignature is unavailable
E/SELinux ( 2888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2888 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 2876): Added TimaKeyStore provider
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1020): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
I/art     (  308): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 21.708ms
D/TimaKeyStoreProvider( 2888): TimaSignature is unavailable
D/ActivityThread( 2888): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.546ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.618ms
E/Zygote  ( 2907): MountEmulatedStorage()
I/libpersona( 2907): KNOX_SDCARD checking this for 1101
E/Zygote  ( 2907): v2
I/libpersona( 2907): KNOX_SDCARD not a persona
I/SELinux ( 2907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/bt-l2cap( 2614): l2c_link_processs_ble_num_bufs 16
E/SELinux ( 2907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2907 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/bt-btm  ( 2614): BTM_SecRegister:p_cb_info->p_le_callback == 0xa43beead 
E/bt-btm  ( 2614): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa43beead 
D/BluetoothAdapterProperties( 2614): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
E/bt-btif ( 2614):                : sec
E/bt-btif ( 2614): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 2614): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 2614): populateRssiValuesNative
I/bluedroid( 2614): getModelRssiValues
E/BluetoothServiceJni( 2614): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2614): modelRssiValuesCallback, low, mid, high = -70,-60,127
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
D/BluetoothAdapterProperties( 2614): Name is: Thali Test (Galaxy A3)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 2907): TimaSignature is unavailable
D/ActivityThread( 2907): Added TimaKeyStore provider
D/DexInstaller( 2832): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/SettingsProvider( 1020): name = bluetooth_name
D/BluetoothAdapterProperties( 2614): Scan Mode:20
D/BluetoothAdapterProperties( 2614): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2614): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 2614): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2614): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2614): btif_sock_init: !radio_req && !rfc_init
W/ResourcesManager( 2888): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/bt-btif ( 2614): btif_sock_init: !vhci_init
W/ResourcesManager( 2888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/IOP_DB_BT( 2614): db_open: file /etc/bluetooth/iop_bt.db
E/bt_mct  ( 2614): hci lib postload completed
W/ResourcesManager( 2888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1020): Killing 1520:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
D/SensorService( 1020): [SO] -0.364 0.249 9.883
D/IOP_DB_BT( 2614): db_open: db_open : handle 3027734544l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2614): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2614): db_query: result 1
I/        ( 2614): iop_db_open: iop_db_open status 0
D/bte_conf( 2614): Device ID record 1 : primary
D/bte_conf( 2614):   vendorId            = 0075
D/bte_conf( 2614):   vendorIdSource      = 0001
D/bte_conf( 2614):   product             = 0100
D/bte_conf( 2614):   version             = 0200
D/bte_conf( 2614):   clientExecutableURL = 
D/bte_conf( 2614):   serviceDescription  = 
D/bte_conf( 2614):   documentationURL    = 
D/bte_conf( 2614): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2614): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2614): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2614): ScanMode =  20
D/BluetoothAdapterProperties( 2614): State =  11
I/PackageInfoHelper( 2832): Provided clientMode=RELEASE, packageInfo=PackageInfo{254489e7 com.google.android.apps.docs}
D/SecContentProvider( 1020): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 2614): Setting state to 12
I/BluetoothAdapterState( 2614): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 2614): Scan Mode:21
D/BluetoothAdapterProperties( 2614): Discoverable Timeout:120
D/SettingsProvider( 1020): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
W/ResourcesManager( 2907): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
D/TAG     ( 2832): onCreate()
V/DownloadManager( 1229): onReceive intent + android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
V/SmartcardService( 2907): main Received broadcast
V/SmartcardService( 2907): Starting smartcard service after boot completed
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
D/CrossAppStateProvider( 2832): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1020): mCursor = null
W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/SSRM:a  ( 1020): DeviceInfo:: 000000000000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/SSRM:a  ( 1020): SettingsAirViewInfo:: 000000000
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1520/cgroup.procs: No such file or directory
I/ActivityManager( 1020): Killing 1546:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2929): MountEmulatedStorage()
D/MediaScannerReceiver( 1229): action: android.intent.action.BOOT_COMPLETED
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD checking this for 1000
I/libpersona( 2929): KNOX_SDCARD not a persona
I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/BluetoothAdapterService( 2614): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2614): updateAdapterState state is 12
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/ActivityThread( 2929): Added TimaKeyStore provider
D/BluetoothAdapterService( 2614): Autoconnection is available 
D/BluetoothAdapterService( 2614): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2614): starting service from this receiver
D/BluetoothAdapter( 1173): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1173): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1458): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1458): onBluetoothStateChange: Bluetooth is on
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/BluetoothAdapter( 2182): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2182): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1432): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1432): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothAdapterState( 2614): Entering On State from state = 11
D/BluetoothAdapter( 1440): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1440): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1792): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1792): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1020): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1020): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2614): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2614): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1020): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2614): onBluetoothStateChange: up=true
I/BluetoothPbapService( 2614): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =12
I/InputMethodManagerService( 1020): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothTile( 1173):  onBluetoothStateChange:
D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1173):  getBluetoothState : 12
I/SamsungIME( 1836): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
W/ContextImpl( 2929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
W/libprocessgroup( 1020): failed to open /acct/uid_10052/pid_1546/cgroup.procs: No such file or directory
E/Zygote  ( 2949): MountEmulatedStorage()
E/Zygote  ( 2949): v2
I/libpersona( 2949): KNOX_SDCARD checking this for 10153
I/libpersona( 2949): KNOX_SDCARD not a persona
I/SELinux ( 2949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2949 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/SELinux ( 2949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/BluetoothPbapService( 2614): Handler(): got msg=1
D/SecContentProvider( 1020): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/TimaKeyStoreProvider( 2949): TimaSignature is unavailable
D/ActivityThread( 2949): Added TimaKeyStore provider
W/ResourcesManager( 2949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2965): MountEmulatedStorage()
E/Zygote  ( 2965): v2
I/libpersona( 2965): KNOX_SDCARD checking this for 1000
I/libpersona( 2965): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/SELinux ( 2965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/SELinux ( 2965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1645): Explicit concurrent mark sweep GC freed 7265(360KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 975us total 34.685ms
D/BluetoothHeadset( 1432): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2028a751, true
D/BluetoothHeadset( 1432): registerMessageListener
D/HeadsetService( 2614): registerMessageListener
D/HeadsetService( 2614): registerMessageListener
I/Telecom ( 1432): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 2614): Disconnected process message: 70
D/HeadsetStateMachine( 2614): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2cfaa7cb
I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
W/DriveInitializer( 2038): Awaiting to be initialized
I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/HeadsetStateMachine( 2614): Disconnected process message: 9
D/HeadsetStateMachine( 2614): mNumActive: 0 mNumHeld: 0 mCallState: 6
W/DriveInitializer( 2038): Background init thread started
D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
D/TimaKeyStoreProvider( 2965): TimaSignature is unavailable
D/ActivityThread( 2965): Added TimaKeyStore provider
V/audio_hw_primary(  285): adev_set_parameters: exit
E/HeadsetStateMachine( 2614): terminateScoUsingVirtualVoiceCall:No present call to terminate
I/ActivityManager( 1020): Killing 1939:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
V/BluetoothPbapService( 2614): PBAP Service initSocket try: 0
D/BluetoothMapMasInstance( 2614): set MAP SDP message type : 1
W/BluetoothAdapter( 2614): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 2614): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2614): bindListen(), new LocalSocket 
D/BluetoothSocket( 2614): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2614): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17db7ba8
D/BluetoothSocket( 2614): channel: 19
D/BluetoothPbapService( 2614): PBAP Socket is BluetoothServerSocket
W/BluetoothAdapter( 2614): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 2614): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2614): bindListen(), new LocalSocket 
D/BluetoothSocket( 2614): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2614): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@141106c1
D/BluetoothSocket( 2614): channel: 5
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2990): MountEmulatedStorage()
I/libpersona( 2990): KNOX_SDCARD checking this for 10155
E/Zygote  ( 2990): v2
I/libpersona( 2990): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2990 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 2990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityThread( 2876): Failed to find provider info for flipboard.auth.internal.debug
E/SELinux ( 2990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityThread( 2876): Failed to find provider info for flipboard.auth.internal
I/ActivityManager( 1020): Killing 2152:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
D/AndroidRuntime( 2872): 
D/AndroidRuntime( 2872): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/DrmEventReceiver( 1020): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1020): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
D/AndroidRuntime( 2872): CheckJNI is OFF
D/AndroidRuntime( 2872): readGMSProperty: start
D/AndroidRuntime( 2872): readGMSProperty: already setted!!
D/AndroidRuntime( 2872): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2872): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2872): readGMSProperty: end
D/AndroidRuntime( 2872): addProductProperty: start
I/DrmEventReceiver( 1020): DrmEventReceiver : beginStartingService
I/System.out( 1020): start Service
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/TimaKeyStoreProvider( 2990): TimaSignature is unavailable
D/ActivityThread( 2990): Added TimaKeyStore provider
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
D/SettingsProvider( 1020): name = next_alarm_formatted
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10081
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
W/ResourcesManager( 2990): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/MediaScannerService( 1229): !@start scanning volume internal: [/system/media, /oem/media]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/TP/MmsProvider( 1458): Update uri=content://mms, match=0
D/MtpService( 1229): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1458): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
I/Mms:transaction( 2364): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2364): [start]    nonBlockingUpdateMessageIndicator() consume time = 3763.111093
I/Mms/ReservationManager( 2364): resetAfterConnected()
W/libprocessgroup( 1020): failed to open /acct/uid_10134/pid_1939/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10064/pid_2152/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2364): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2364): isDefault true
D/TP/MmsSmsProvider( 1458): query,matched:7, calling pid = 2364
D/TP/MmsProvider( 1458): Query uri=content://mms, match=0, calling pid = 2364
D/TP/MmsSmsProvider( 1458): match 7:Elapsed time : 4.587 ms
I/Mms/ReservationManager( 2364): getReservedSendMessageCount(): retMessageCount=0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/TP/MmsSmsProvider( 1458): query,matched:200, calling pid = 2364
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1458): match 200:Elapsed time : 1.053 ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/[0]UMC:Core( 2990): onCreate(): 
E/Zygote  ( 3010): MountEmulatedStorage()
E/Zygote  ( 3010): v2
I/libpersona( 3010): KNOX_SDCARD checking this for 10043
I/libpersona( 3010): KNOX_SDCARD not a persona
I/SELinux ( 3010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3010 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2364): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2364): isDefault true
D/Mms/SmsReceiverService( 2364): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/TP/SmsProvider( 1458): query,matched:0, calling pid = 2364
D/Mms/SmsReceiverService( 2364): [start]    handleBootCompleted() consume time = 59.874583
D/TP/SmsProvider( 1458): match 0:Elapsed time : 1.161 ms
D/TimaKeyStoreProvider( 3010): TimaSignature is unavailable
D/ActivityThread( 3010): Added TimaKeyStore provider
D/[0]UMC:DeviceInfo( 2990): USA==US==
D/TP/MmsSmsProvider( 1458): getThreadUnReadCount unreadCount=0 imUnreadCount=0
W/ResourcesManager( 3010): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1458): deleteConversation threadId: 9223372036854775806
W/ResourcesManager( 3010): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3010): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1458): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1458): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1458): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1458): (284) automatic index on im_threads(normal_thread_id)
E/USB_UICC(  299): Timeout! No signal received. Retry num = 26
D/TP/MmsSmsProvider( 1458): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
D/Mms/Conversation( 2364): deleteTempConversation(),deleted=0
D/SmsProvider( 1458): Update uri=content://sms/outbox, match=8
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
D/Mms/SmsReceiverService( 2364): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2364): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2364): [SIM-1]sendFirstQueuedMessage()
D/USER_AGENT( 2990): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/TP/SmsProvider( 1458): query,matched:26, calling pid = 2364
D/[0]UMC:AdminManager( 2990): init - start
D/TP/SmsProvider( 1458): match 26:Elapsed time : 4.732 ms
D/[0]UMC:AdminManager( 2990): loadAdmins
D/Mms/SmsReceiver( 2364): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2364): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2364): isDefault true
D/[0]UMC:AdminManager( 2990): init - end
D/GSLBManager( 2990): migrateStoredUrlFromOldPref
D/SettingsProvider( 1020): name = block_emergency_message
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10043
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
W/ActivityManager( 1020): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onInitialize : 3951
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onSetOnInfoListener : add 3951
D/TP/MmsProvider( 1458): Query uri=content://mms, match=0, calling pid = 2364
I/art     ( 1458): Explicit concurrent mark sweep GC freed 33704(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 8.316ms total 118.299ms
D/TP/MmsSmsProvider( 1458): query,matched:200, calling pid = 2364
D/TP/MmsSmsProvider( 1458): match 200:Elapsed time : 6.538 ms
D/TP/SmsProvider( 1458): query,matched:51, calling pid = 2364
D/TP/SmsProvider( 1458): match 51:Elapsed time : 1.186 ms
D/Mms/MessagingNotification( 2364): isBlockingModeEnabled() = false, Zen mode = 0
D/BadgeProvider( 1581): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/DrmEventService( 1020): action event :android.intent.action.BOOT_COMPLETED
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
I/TimaServiceEventReceiver( 1020): TimaServiceEventReceiver : onReceive
D/GSLBManager( 2990): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2990): deactivateUMCAdminIfNotRequired : -1
D/TP/SmsProvider( 1458): query,matched:0, calling pid = 2364
I/ANDROID_DRM_FRWORKS_DrmManager(  284): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
E/[0]UMC:Utils( 2990): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2990): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/TP/SmsProvider( 1458): match 0:Elapsed time : 3.699 ms
D/[0]UMC:UMCAdmin( 2990): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2990): isContainer : 0
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
E/CscReceiver( 1458): onReceive android.intent.action.BOOT_COMPLETED
D/EnterpriseDeviceManagerService( 1020): isManagedProfileUser(): userId = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1581): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1483): reloadBadges entered.
D/BadgeProvider( 1581): sendNotify, [notify] : null
D/BadgeProvider( 1581): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1581): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1581): update, [UpdateCount] : 1
D/TP/SmsProvider( 1458): query,matched:51, calling pid = 2364
D/TP/SmsProvider( 1458): match 51:Elapsed time : 1.151 ms
D/CscUpdateService( 1458): onStart
E/CscUpdateService( 1458): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1458): set_CSC_version
E/Zygote  ( 3045): MountEmulatedStorage()
I/libpersona( 3045): KNOX_SDCARD checking this for 10002
E/Zygote  ( 3045): v2
I/libpersona( 3045): KNOX_SDCARD not a persona
E/CscParser( 1458): update(): xml file exist
I/SELinux ( 3045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3045 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
E/SQLiteLog( 1229): (283) recovered 128 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/CscUtil ( 1458): isWifiOnly = false
I/System.out( 1458): HandDataNode = null
I/CscUpdateService( 1458): PATH_CSCNAME =CustomerDataSet.CSCName
I/CscUpdateService( 1458): This is normal boot : CSC not updated
D/Mms/MessagingNotification( 2364): setBadgeCount(), count=0
D/TimaKeyStoreProvider( 3045): TimaSignature is unavailable
D/ActivityThread( 3045): Added TimaKeyStore provider
E/CscParser( 1458): update(): xml file exist
D/Mms/MessagingNotification( 2364): remove alarm
D/TP/SmsProvider( 1458): query,matched:0, calling pid = 2364
D/TP/SmsProvider( 1458): match 0:Elapsed time : 1.038 ms
D/CscGPS  ( 1458): CSCGPS.updateParameters
E/[0]UMC:UMCAdmin( 2990): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2990): isContainer : 0
D/[0]UMC:UMCAdmin( 2990): deactivateUMCAdmin - UMC App Admin deactivated
W/DriveInitializer( 2038): Background init thread ended
D/CscGPS  ( 1458): supl host : null
D/CscGPS  ( 1458): SUPL Host is null or invalid
D/CscGPS  ( 1458): supl_ver : null
D/CscGPS  ( 1458): SUPL Ver is null or invalid
D/CscGPS  ( 1458): supl port : null
D/CscGPS  ( 1458): SUPL PORT is null or invalid
D/CscGPS  ( 1458): LPP : null
D/CscGPS  ( 1458): LPP is null or invalid
D/CscGPS  ( 1458): CSC don't have any AGPS value.
I/WifiCredService( 1322): onCreate
D/Mms/MessagingNotification( 2364): updateAllHistoryAsRead()
D/[0]UMC:CoreReceiver( 2990): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2990):  check PreETag 
D/Mms/MessagingNotification( 2364): [end]    nonBlockingUpdateMessageIndicator() consume time = 311.981093
D/Mms/MessagingNotification( 2364): isBlockingModeEnabled() = false, Zen mode = 0
D/WifiTimerReceiver( 1322): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1322): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1322): Action boot completed received
I/CscUpdateService( 1458): same CSC Version
D/CscUtil ( 1458): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/WifiCredService( 1322): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/[0]UMC:ByodSetupStarter( 2990): Container ID : 0
W/art     ( 2888): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 173.403ms
E/WifiStateMachine( 1020): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1020): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1020): invaild command id : 215
V/[0]UMC:Utils( 2990): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2990): shutdown
I/art     ( 2990): System.exit called, status: 0
I/AndroidRuntime( 2990): VM exiting with result code 0, cleanup skipped.
W/art     ( 2667): Attempt to remove local handle scope entry from IRT, ignoring
E/AffinityControl( 2872): AffinityControl: registerfunction enter
I/ActivityManager( 1020): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2990)(adj 0) has died(24,671)
D/AndroidRuntime( 2872): Calling main entry com.android.commands.am.Am
D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/dhcpcd  ( 1820): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 1820): wlan0: no IPv6 Routers available
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1020): mDVFSHelper.acquire()
I/art     ( 1020): Explicit concurrent mark sweep GC freed 16882(843KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 7.041ms total 180.109ms
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1483
D/Launcher.HomeView( 1483): onPause
D/AndroidRuntime( 2872): Shutting down VM
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/MediaScanner( 1229): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/Launcher( 1483): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1020): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/NearbySettings( 1322): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1322): MountReceiver.onReceive - Internal Path
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1770): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1770): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
D/BadgeProvider( 1581): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
E/Zygote  ( 3079): MountEmulatedStorage()
I/libpersona( 3079): KNOX_SDCARD checking this for 10168
E/Zygote  ( 3079): v2
I/libpersona( 3079): KNOX_SDCARD not a persona
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3079 uid=10168 gids={50168, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3079): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/Activit,yManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3094): MountEmulatedStorage()
E/Zygote  ( 3094): v2
I/libpersona( 3094): KNOX_SDCARD checking this for 1000
I/SELinux ( 3094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3094): KNOX_SDCARD not a persona
I/SELinux ( 3094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 3079): TimaSignature is unavailable
I/ActivityManager( 1020): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3079): Added TimaKeyStore provider
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SettingsProvider( 1020): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10157
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/TimaKeyStoreProvider( 3094): TimaSignature is unavailable
D/ActivityThread( 3094): Added TimaKeyStore provider
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
V/ActivityThread( 1483): updateVisibility : ActivityRecord{1d9124a7 token=android.os.BinderProxy@2f8833ed {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1483): onStop
V/ActivityThread( 1483): updateVisibility : ActivityRecord{1d9124a7 token=android.os.BinderProxy@2f8833ed {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1483): onTrimMemory. Level: 20
W/art     ( 2872): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SettingsProvider( 1020): name = personal_mode_enabled
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/daemonapp( 1770): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/BadgeProvider( 1581): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1581): sendNotify, [notify] : null
D/BadgeProvider( 1581): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1581): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1581): update, [UpdateCount] : 1
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/SensorManager( 1020): unregisterListener ::   
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1020): [SO] changed settle time [1]
,D/SensorService( 1020): [SO] setDelay [66000000]
D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=1)
,D/SensorService( 1020): [SO] AR_init
,I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/Mms/MessagingNotification( 2364): setBadgeCount(), count=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Mms/MessagingNotification( 2364): remove alarm
,E/Zygote  ( 3119): MountEmulatedStorage(),
,E/Zygote  ( 3119): v2
,W/ResourcesManager( 1458): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/libpersona( 3119): KNOX_SDCARD checking this for 1000
I/libpersona( 3119): KNOX_SDCARD not a persona,
,D/Launcher.Model( 1483): reloadBadges entered.
,I/SELinux ( 3119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1],
,D/Mms/MessagingNotification( 2364): updateAllHistoryAsRead()
,I/SmartcardBootCompleteReceiver( 1322): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1322): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10117
,V/MediaScanner( 1229): processDirectory :  /system/media
,D/TimaKeyStoreProvider( 3119): TimaSignature is unavailable
,D/ActivityThread( 3119): Added TimaKeyStore provider
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/SensorService( 1020): [SO] currT = 33021253000, prevT = 32671030000, diff = 350223000, [-0.364 0.268 9.883]
,D/SensorService( 1020): [SO] -0.364 0.268 9.883
D/SensorService( 1020): [SO] [100 -> 255]
D/TP/SmsProvider( 1458): query,matched:0, calling pid = 2364
,D/daemonapp( 1770): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1456842806137
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1456864380000
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,I/SmartcardBootCompleteReceiver( 1322): Broadcast sent with current lockscreen type
,D/TP/SmsProvider( 1458): match 0:Elapsed time : 4.982 ms
,D/daemonapp( 1770): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1456864380000
,D/Mms/SmsReceiverService( 2364): [end]    handleBootCompleted() consume time = 620.270313
,I/ActivityManager( 1020): Killing 2167:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 2182:com.vlingo.midas/u0a28 (adj 15): empty #31
,V/MediaScanner( 1229):  prescan time: 883ms (DB items: 138)
V/MediaScanner( 1229):     scan time: 75ms (Caching mode: true), (makeEntry time: 25ms ~33%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1229): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1229):    total time: 958ms
V/MediaScanner( 1229): checked files: 130  directories : 6  (I: 0, U: 0)
W/ResourcesManager( 3119): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaScanner( 1229): checkDefaultSounds
D/MediaScanner( 1229): system alarm_alert  : Vwiurug_etwofi5wgg
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 65
,D/daemonapp( 1770): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1456864380000
,D/MediaScanner( 1229): OK. alarm_alert is already exist in setting DB.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3141 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 3141): MountEmulatedStorage()
I/libpersona( 3141): KNOX_SDCARD checking this for 10082
E/Zygote  ( 3141): v2
I/libpersona( 3141): KNOX_SDCARD not a persona
,I/SELinux ( 3141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SQLiteLog( 3094): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
E/SELinux ( 3141): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1229): system notification_sound  : K_Oprkltf5wgg
,I/WebViewFactory( 3079): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/MediaScanner( 1229): OK. notification_sound is already exist in setting DB.
,I/ActivityManager( 1020): Killing 2207:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
,I/LibraryLoader( 3079): Loading: webviewchromium
,I/LibraryLoader( 3079): Time to load native libraries: 6 ms (timestamps 3169-3175)
I/LibraryLoader( 3079): Expected native library version number "",actual native library version number ""
,I/art     (  308): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 40.307ms
E/USB_UICC(  299): Timeout! No signal received. Retry num = 27
,D/MediaScanner( 1229): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/DSM     ( 3094): [Lines:107] Normal booted
,D/DSM     ( 3094): [Lines:114] Boot completed
D/MediaScanner( 1229): OK. ringtone is already exist in setting DB.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 17.018ms
,V/WebViewChromiumFactoryProvider( 3079): Binding Chromium to main looper Looper (main, tid 1) {3d0f6b00}
,D/TimaKeyStoreProvider( 3141): TimaSignature is unavailable
,D/ActivityThread( 3141): Added TimaKeyStore provider
,I/LibraryLoader( 3079): Expected native library version number "",actual native library version number ""
,I/chromium( 3079): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 17.167ms
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/[SBeam] ( 1322): SBeamEnabler.initPreferenceForSbeam : 0
,D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/BrowserStartupController( 3079): Initializing chromium process, renderers=0
,W/art     ( 3079): Attempt to remove local handle scope entry from IRT, ignoring
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,W/chromium( 3079): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 3079): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3079): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/FactoryTestApp( 2572): [DummyFtClient$mBroadcastReceiver](2572) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2572): [DummyFtClient$mBroadcastReceiver](2572) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2572): [DummyFtClient$mBroadcastReceiver](2572) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/MediaScannerService( 1229): !@done scanning volume internal
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/SettingSearch/SearchIntentReceiver( 1322): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1322): search setting db init!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/Adreno-EGL( 3079): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3079): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3079): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3079): Local Branch: 
I/Adreno-EGL( 3079): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3079): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3079):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,E/Zygote  ( 3170): MountEmulatedStorage()
E/Zygote  ( 3170): v2
I/libpersona( 3170): KNOX_SDCARD checking this for 10161
I/libpersona( 3170): KNOX_SDCARD not a persona
,I/SELinux ( 3170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3170 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MediaScannerService( 1229): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,E/SELinux ( 3170): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 1322): BOOT_COMPLETED call InitSerachDBThread thread start!
,W/libprocessgroup( 1020): failed to open /acct/uid_10028/pid_2182/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3182): MountEmulatedStorage()
E/Zygote  ( 3182): v2
I/libpersona( 3182): KNOX_SDCARD checking this for 1000
I/libpersona( 3182): KNOX_SDCARD not a persona
,I/SELinux ( 3182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3170): TimaSignature is unavailable
I/ActivityManager( 1020): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3182 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 3170): Added TimaKeyStore provider
I/ActivityManager( 1020): Killing 2265:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3182): TimaSignature is unavailable
,D/ActivityThread( 3182): Added TimaKeyStore provider
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3205): MountEmulatedStorage(),
E/Zygote  ( 3205): v2
I/libpersona( 3205): KNOX_SDCARD checking this for 10146
I/libpersona( 3205): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3205 uid=10146 gids={50146, 9997} abi=armeabi-v7a
I/SELinux ( 3205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3205): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 1499:com.android.printspooler/u0a132 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10065/pid_2167/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10045/pid_2207/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,W/ResourcesManager( 3182): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3205): TimaSignature is unavailable
,D/ActivityThread( 3205): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10132/pid_1499/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10110/pid_2265/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1229): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1229): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/Zygote  ( 3222): MountEmulatedStorage()
E/Zygote  ( 3222): v2
I/libpersona( 3222): KNOX_SDCARD checking this for 1000
I/libpersona( 3222): KNOX_SDCARD not a persona
,I/SELinux ( 3222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1229): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1229): Skipping:
D/MediaScanner( 1229): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1229): Skipping:
D/MediaScanner( 1229): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/TimaKeyStoreProvider( 3222): TimaSignature is unavailable
,V/MediaScanner( 1229): processDirectory :  /storage/extSdCard
W/MediaScanner( 1229): Error opening directory, reason : Permission denied.
W/MediaScanner( 1229): 7klwibgf7fxlKdCbid7
D/ActivityThread( 3222): Added TimaKeyStore provider
,V/MediaScanner( 1229):  prescan time: 30ms (DB items: 26)
V/MediaScanner( 1229):     scan time: 18ms (Caching mode: true), (makeEntry time: 10ms ~55%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1229): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1229):    total time: 51ms
V/MediaScanner( 1229): checked files: 10  directories : 16  (I: 0, U: 0)
,D/MediaScannerService( 1229): !@done scanning volume external
,W/chromium( 3079): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/FactoryTestApp( 2572): [DummyFtClient$mBroadcastReceiver](2572) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2572): [DummyFtClient$mBroadcastReceiver](2572) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2572): [DummyFtClient$sendBootCompletedAndFinish](2572) ...
D/FactoryTestApp( 2572): [Support$Values.getString](2572) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2572): [ModuleCommon$isConnectionModeNone](2572) mConnectionMode = gsm
D/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$ResponseWriter](2572) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$connectToSecPhoneService](2572)  
,W/ContextImpl( 2572): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ResourcesManager( 3222): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,W/chromium( 3079): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityThread( 3182): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,E/UpdateRequestReceiver( 3141): ignoring update request
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
E/UpdateRequestReceiver( 3141): ignoring update request
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 3182): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,E/UpdateRequestReceiver( 3141): ignoring update request
,I/LcdtestApp( 3182): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/art     ( 2652): Suspending all threads took: 118.231ms
,E/Zygote  ( 3251): MountEmulatedStorage()
,E/Zygote  ( 3251): v2
I/libpersona( 3251): KNOX_SDCARD checking this for 1000
I/libpersona( 3251): KNOX_SDCARD not a persona
I/SELinux ( 3251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3251): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 3079): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3079): onDetachedFromWindow called when already detached. Ignoring
,D/TimaKeyStoreProvider( 3251): TimaSignature is unavailable
D/PhoneWindow( 3079): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3079): *FMB* installDecor flags : 8456448
,D/ActivityThread( 3251): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3141): ignoring update request
,D/SystemWebViewEngine( 3079): CordovaWebView is running on device made by: samsung
,E/UpdateRequestReceiver( 3141): ignoring update request
,W/art     ( 3079): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3079): Attempt to remove local handle scope entry from IRT, ignoring
,E/UpdateRequestReceiver( 3141): ignoring update request
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3170): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3170): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 3273): MountEmulatedStorage(),
E/Zygote  ( 3273): v2
,I/libpersona( 3273): KNOX_SDCARD checking this for 10088
I/libpersona( 3273): KNOX_SDCARD not a persona,
,I/ActivityManager( 1020): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3273 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 1631:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/BluetoothMediaBrowser( 2614):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 2614): no now playing list
D/BluetoothMediaBrowser( 2614):  getNowPlayingId now playing id : -1
,V/JNIHelp ( 3170): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/DIAGMON_AGENT( 3251): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/ActivityThread( 3170): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3170): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f9dee08: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3170): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 3273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3273): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3273): TimaSignature is unavailable
,D/ActivityThread( 3273): Added TimaKeyStore provider
,I/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$onServiceConnected](2572) connected done
,D/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$write](2572) Send Response Message to SecPhone
D/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$write](2572) Response ��
,D/AT_Distributor(  313): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3170): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_1631/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/OpenGLRenderer( 3079): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/AT_Distributor(  313): SetAtdStatus(), 1_1_0
D/AT_Distributor(  313): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,D/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$handleMessage](2572) Send BOOTING COMPLETED done
,D/PhoneWindow( 3079): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 3079): *FMB* isFloatingMenuEnabled return false
,I/FOTA    ( 3222): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/GAV2    ( 2832): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 28
,E/SMD     (  290): DCD OFF
,D/InputDispatcher( 1020): Focus entered window: 3079
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3079): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3079): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3079): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3079): Enabling debug mode 0
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s617ms
,I/Timeline( 3079): Timeline: Activity_idle id: android.os.BinderProxy@36539430 time:34293
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1020): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{1174ea77 u0 com.example.hello/.MainActivity t7} time:34300
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{23e6a742 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DIAGMON_AGENT( 3251): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 3251): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
I/DIAGMON_AGENT( 3251): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 3251): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3251): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3251): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 17737(868KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.321ms total 290.016ms
,I/SamsungIME( 1836): getCurrentCandidateView
,E/Zygote  ( 3334): MountEmulatedStorage()
,E/Zygote  ( 3334): v2
I/libpersona( 3334): KNOX_SDCARD checking this for 10088
I/libpersona( 3334): KNOX_SDCARD not a persona
,I/SELinux ( 3334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3334 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 3334): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 3222): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 3222): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 3222): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/TimaKeyStoreProvider( 3334): TimaSignature is unavailable
D/ActivityThread( 3334): Added TimaKeyStore provider
,D/OverheatReceiver( 1173): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1173): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1173): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1173): isSafeMode = false
,I/SurfaceFlinger(  259): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  259): id=10 Removed iello (-2/8)
,D/BootupListener( 1458): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = internet_call_settings_visibility,
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1001
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/PhoneUtilsCommon( 1458): isSupportVoLTE is false.
,E/AndroidProtocolHandler( 3079): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 3079): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3222): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,E/Zygote  ( 3355): MountEmulatedStorage()
I/libpersona( 3355): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3355): v2
I/libpersona( 3355): KNOX_SDCARD not a persona
,I/SELinux ( 3355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 3222): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true,
I/ActivityManager( 1020): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3222): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
E/SELinux ( 3355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3222): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3222): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3222): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 3222): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,D/TimaKeyStoreProvider( 3355): TimaSignature is unavailable
,D/ActivityThread( 3355): Added TimaKeyStore provider
W/ContextImpl( 3222): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,I/DBG_DM  ( 3222): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3273): Setting receiver enabled: false
,D/JsMessageQueue( 3079): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/System.out( 2832): Thread-334(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/DBG_DM  ( 3222): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/DBG_DM  ( 3222): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,I/System.out( 2832): Thread-334(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2832): Thread-334(ApacheHTTPLog):isShipBuild true
I/System.out( 2832): Thread-334(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2832): Thread-334(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10087
,E/ActivityThread( 3273): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/DBG_DM  ( 3222): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/YouTube MDX( 3170): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/SamsungIME( 1836): Dismiss ExpandCandiate
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/dbxyzptlk.db240408.D.h( 3273): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/dbxyzptlk.db240408.D.h( 3273): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/DBG_POLICYDM( 3355): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/dbxyzptlk.db240408.D.h( 3273): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3355): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3390 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3390): MountEmulatedStorage()
I/libpersona( 3390): KNOX_SDCARD checking this for 10008
E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD not a persona
,I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3222): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/Telecom ( 1432): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,I/DBG_DM  ( 3222): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
D/ActivityThread( 3390): Added TimaKeyStore provider
,I/chromium( 3079): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3079): 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Zygote  ( 3410): MountEmulatedStorage()
E/Zygote  ( 3410): v2
I/libpersona( 3410): KNOX_SDCARD checking this for 10052
I/libpersona( 3410): KNOX_SDCARD not a persona
I/SELinux ( 3410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3410 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 3410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3410): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 3410): TimaSignature is unavailable
D/ActivityThread( 3410): Added TimaKeyStore provider
,I/AudioService( 1020): getStreamVolume 3 index 0
,I/Telecom ( 1432): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/dbxyzptlk.db240408.D.h( 3273): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/SamsungIME( 1836): getDebugLevel  : 0x4f4c
,E/Tethering( 1020): No numeric data
,I/DBG_POLICYDM( 3355): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/Tethering( 1020): No numeric data
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 3355): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/breakpad( 3273): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,D/jxcore_app_log( 3079): JniHelper::setJavaVM(0xb7a7a448), pthread_self() = -1207074320
,D/JX-Cordova( 3079): jxcore cordova android initializing
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 29
,I/GAV2    ( 2667): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/com.dropbox.sync.android.a( 3273): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/[SBeam] ( 1322): SBeamEnabler.isSBeamSupported : [-1],
D/[SBeam] ( 1322): SBeamEnabler.isSBeamSupported : EXIST
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 3355): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,W/ContextImpl( 3170): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3170): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,V/audio_hw_primary(  285): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  285): audio_extn_get_parameters: returns 
V/msm8974_platform(  285): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  285): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  285): key: 'call_forwarding' value: ''
,V/InCall  ( 1870): ProximitySensor -  - screenonImmediately: false
,V/InCall  ( 1870): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1870): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3170): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ScoverManager( 1870): serviceVersion : 16908288
W/jxcore-log( 3079): Initializing JXcore engine
W/jxcore-log( 3079): JXcore engine is ready
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,W/jxcore-log( 3079): Starting JXcore engine
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/InCall  ( 1870): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/Telecom ( 1432): ProximitySensorManager: Proximity wake lock already released
,E/Tethering( 1020): No numeric data
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1870): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/InCall  ( 1870): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1870): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1870): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1870): CallSContextMotion - stopPutDownListening
,I/SamsungIME( 1836): getDebugLevel  : 0x4f4c
,D/InCall  ( 1870): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/PhoneStatusBarView( 1173): setCallBackground:0
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1870): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,E/Tethering( 1020): No numeric data
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/audit   ( 1833): type=1400 msg=audit(1456842808.585:205): avc:  denied  { ioctl } for  pid=3079 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1833):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1833): type=1300 msg=audit(1456842808.585:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=bec34d58 items=0 ppid=308 ppcomm=main pid=3079 auid=4294967295 uid=10168 gid=10168 euid=10168 suid=10168 fsuid=10168 egid=10168 sgid=10168 fsgid=10168 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1833): type=1320 msg=audit(1456842808.585:205): 
,I/SamsungIME( 1836): KeybaordView init() : load resources
,I/com.dropbox.sync.android.ad( 3273): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,D/VideoCallManager( 1870): Instantiating VideoCallManager
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 3355): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3355): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/LocationManagerService( 1020): getProviders()=[passive]
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/SamsungIME( 1836): getCurrentKeyboard,
I/libpersona( 3465): KNOX_SDCARD checking this for 10014
I/SamsungIME( 1836): getTextKeyboard,
I/libpersona( 3465): KNOX_SDCARD not a persona
E/Zygote  ( 3465): MountEmulatedStorage()
E/Zygote  ( 3465): v2,
I/SELinux ( 3465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GFX construct_block_size_descriptor_2d second part( 1870): took 2.671460ms for 0*0 texture 0,
I/SELinux ( 3465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3465): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/GFX generate_partition_tables( 1870): took 5.319115ms for 0*0 texture 0
,I/ActivityManager( 1020): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3465 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,I/GFX raster( 1870): took 12.206407ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb7e27550 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7e26e20 counterpartCT=4 counterpartW=176 counterparth=144
I/System.out( 2832): SyncManager calls detatch()
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240,
,I/Adreno-EGL( 1870): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 1870): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1870): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1870): Local Branch: 
I/Adreno-EGL( 1870): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1870): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1870):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/art     (  308): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 7.337ms total 31.071ms,
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 21.710ms
,W/jxcore-log( 3079): Platform android
W/jxcore-log( 3079): 
W/jxcore-log( 3079): Process ARCH arm
W/jxcore-log( 3079): 
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 17.220ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus,
,D/TimaKeyStoreProvider( 3465): TimaSignature is unavailable
D/ActivityThread( 3465): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/06/11:32:20
I/GFX GPU raster( 1870): eglCreateImageKHR: EGL_SUCCESS
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/glCompressedTexImage2D( 1870): took 0.407343ms for 320*61440 texture 37809
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/01/15:33:28
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 3355): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/draw setup( 1870): took 11.645417ms for 320*240 texture 37809
I/DBG_POLICYDM( 3355): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
E/GFX GPU raster( 1870): drawn
,I/DBG_POLICYDM( 3355): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/GFX GPU raster ASTC( 1870): took 44.442864ms for 320*240 texture 12
I/GFX raster( 1870): took 44.504426ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb7e274d0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7e27038 counterpartCT=4 counterpartW=320 counterparth=240
D/SamsungIME( 1836): [SwiftkeyWrapper] currentLangauge : 1701729619
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_POLICYDM( 3355): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/jxcore-log( 3079): JXcore Cordova bridge is ready!
I/jxcore-log( 3079): 
W/jxcore-log( 3079): JXcore engine is started
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/DBG_POLICYDM( 3355): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/GFX GPU raster( 1870): eglCreateImageKHR: EGL_SUCCESS
,I/DBG_POLICYDM( 3355): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/glCompressedTexImage2D( 1870): took 0.424427ms for 480*122880 texture 37813
I/draw setup( 1870): took 1.059063ms for 480*640 texture 37813
E/GFX GPU raster( 1870): drawn
,I/GFX GPU raster ASTC( 1870): took 9.879219ms for 480*640 texture 12
I/GFX raster( 1870): took 9.954688ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb7e27038 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8068a90 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_POLICYDM( 3355): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/Velvet.VelvetFactory( 3410): refreshing internal icing corpora
,I/Velvet.VelvetFactory( 3410): checking for language pack updates
,W/NotificationAccessSettings( 1322): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1870): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1870): took 0.312396ms for 440*116864 texture 37809
I/draw setup( 1870): took 0.870677ms for 440*330 texture 37809
E/GFX GPU raster( 1870): drawn
,I/GFX GPU raster ASTC( 1870): took 5.870834ms for 440*330 texture 12
I/GFX raster( 1870): took 6.006302ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb8068a70 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8068e40 counterpartCT=4 counterpartW=440 counterparth=330
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
I/GFX GPU raster( 1870): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1870): took 0.421250ms for 480*163840 texture 37811
I/draw setup( 1870): took 0.874427ms for 480*640 texture 37811
E/GFX GPU raster( 1870): drawn
E/Zygote  ( 3494): MountEmulatedStorage()
E/Zygote  ( 3494): v2
I/libpersona( 3494): KNOX_SDCARD checking this for 10090
I/libpersona( 3494): KNOX_SDCARD not a persona
I/SELinux ( 3494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GFX GPU raster ASTC( 1870): took 6.123281ms for 480*640 texture 12
I/GFX raster( 1870): took 6.203645ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb80688b0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb807b8d8 counterpartCT=4 counterpartW=480 counterparth=640
I/SELinux ( 3494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3494 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2345:com.sec.modem.settings/1000 (adj 15): empty #31
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,W/ResourcesManager( 1322): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/TimaKeyStoreProvider( 3494): TimaSignature is unavailable
,D/ActivityThread( 3494): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/DBG_POLICYDM( 3355): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/ActivityManager( 1020): Killing 2383:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/GFX construct_block_size_descriptor_2d second part( 1870): took 3.128334ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1870): took 7.819374ms for 0*0 texture 0,
,I/GFX raster( 1870): took 13.414323ms for 176*144 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb80589c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb807b8f8 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3355): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,E/jxcore-log( 3079): >> samsung-SM-A300FU
E/jxcore-log( 3079): 
,I/jxcore-log( 3079): Total memory 1451114496
I/jxcore-log( 3079): 
,I/jxcore-log( 3079): Free memory 22097920
I/jxcore-log( 3079): 
I/jxcore-log( 3079): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3079): 
I/jxcore-log( 3079): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3079): 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/jxcore-log( 3079): userPath [ 'www' ]
I/jxcore-log( 3079): 
,I/jxcore-log( 3079): Size 540 960
I/jxcore-log( 3079): 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4295, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
I/jxcore-log( 3079): Screen Brightness 31
I/jxcore-log( 3079): 
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,E/jxcore-log( 3079): Dummy Error Log.
E/jxcore-log( 3079): 
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/PowerUI ( 1173): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1173): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/MessageQueue( 3170): Handler (android.os.Handler) {44f826f} sending message to a Handler on a dead thread
W/MessageQueue( 3170): java.lang.IllegalStateException: Handler (android.os.Handler) {44f826f} sending message to a Handler on a dead thread
W/MessageQueue( 3170): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3170): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3170): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3170): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3170): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3170): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3170): 	at guw.a(SourceFile:120)
W/MessageQueue( 3170): 	at guf.c(SourceFile:26)
W/MessageQueue( 3170): 	at gui.run(SourceFile:297)
W/MessageQueue( 3170): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3170): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3170): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,E/        ( 1870): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1870): took 3.368750ms for 0*0 texture 0
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,I/GFX generate_partition_tables( 1870): took 6.825469ms for 0*0 texture 0
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/GFX raster( 1870): took 13.022187ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1870): Bitmap=0xb8068f20 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb807d5e8 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1870): registerListener
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManager.StateNotifier( 1020): registerListenerCallback : binder = android.os.BinderProxy@19b87d5, pid : 1870, uid : 1001, type : 1
,D/PackageManager( 1020): [MSG] MCS_UNBIND
,D/InCall  ( 1870): InCallPresenter -  - Finished InCallPresenter.setUp
,I/ActivityManager( 1020): Killing 2411:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,W/ContextImpl( 1856): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/elm:15121( 3494): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3494): ELMEngine.ELMEngine( context ).
,I/System.out( 3273): Thread-429(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3273): Thread-429(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3273): Thread-429(ApacheHTTPLog):isShipBuild true
,I/System.out( 3273): Thread-429(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 3273): Thread-429(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10088
,D/SecUISvc( 1856): Service started flags 0 startId 1
D/elm:15121( 3494): MDMBridge.setEnterpriseBridge()
,D/SecUISvc( 1856): Thread created.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2345/cgroup.procs: No such file or directory
,D/elm:15121( 3494): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/elm:15121( 3494): ElmAgentService : onCreate()
,D/elm:15121( 3494): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3494): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3494): BootCompletedState : startBootCompleted() call
,D/AndroidHttpClient( 3170): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3170): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3170): Thread-452(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3170): Thread-452(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3170): Thread-452(ApacheHTTPLog):isShipBuild true
I/System.out( 3170): Thread-452(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3170): Thread-452(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/EmergencyMode( 1417): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2411/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10127/pid_2383/cgroup.procs: No such file or directory
,D/elm:15121( 3494): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15121( 3494): Get License : 0
D/elm:15121( 3494): ElmAgentService : onDestroy().
,V/EmergencyMode( 1417): [EmergencyBase] setBootTime
V/EmergencyMode( 1417): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1322): serviceVersion : 16908288
,E/Zygote  ( 3530): MountEmulatedStorage()
I/libpersona( 3530): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3530): v2
I/libpersona( 3530): KNOX_SDCARD not a persona
,I/SELinux ( 3530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 2432:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3544): MountEmulatedStorage()
,E/Zygote  ( 3544): v2
I/libpersona( 3544): KNOX_SDCARD checking this for 1000
I/libpersona( 3544): KNOX_SDCARD not a persona
I/SELinux ( 3544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
I/ActivityManager( 1020): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3544): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3530): TimaSignature is unavailable
I/ActivityManager( 1020): Killing 2521:com.wsomacp/u0a23 (adj 15): empty #31
,D/ActivityThread( 3530): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 2508:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
,I/ActivityManager( 1020): Killing 2543:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 3544): TimaSignature is unavailable
,D/ActivityThread( 3544): Added TimaKeyStore provider
,I/AudioService( 1020): getStreamVolume 3 index 0
,I/MediaRouter( 3410): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/FavoriteContactNamesSup( 3410): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3410): get() : Execute runnable (UI thread)
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ContactLabelSupplier( 3410): get() : OptedIn = false
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2432/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_2521/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_2508/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10135/pid_2543/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3562): MountEmulatedStorage(),
E/Zygote  ( 3562): v2
I/libpersona( 3562): KNOX_SDCARD checking this for 10055
I/libpersona( 3562): KNOX_SDCARD not a persona
,I/SELinux ( 3562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3562 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 3562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 30
I/DBG_FMMDM( 3544): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/CameraApp( 3530): CameraApp.onCreate()... mFeature : null
I/testFeature( 3530): Feature.Feature(context)
I/testFeature( 3530): Feature.readInternalDefaultXml()
I/testFeature( 3530): ResetFeatureValue
,I/Velvet.VelvetFactory( 3410): refreshing search history.
,D/TimaKeyStoreProvider( 3562): TimaSignature is unavailable
,D/ActivityThread( 3562): Added TimaKeyStore provider
,I/CameraFirmware_broadcast( 3530): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3530): CameraApp.getAppFeature()...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_FMMDM( 3544): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3544): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3544): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Zygote  ( 3578): MountEmulatedStorage()
E/Zygote  ( 3578): v2
I/libpersona( 3578): KNOX_SDCARD checking this for 10095
I/libpersona( 3578): KNOX_SDCARD not a persona
,I/SELinux ( 3578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3578 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2334:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1322): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 3578): TimaSignature is unavailable
,D/ActivityThread( 3578): Added TimaKeyStore provider
,E/Zygote  ( 3593): MountEmulatedStorage()
I/libpersona( 3593): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3593): v2
I/libpersona( 3593): KNOX_SDCARD not a persona
,I/SELinux ( 3593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/UserAnalysis.PlaceProvider( 3562): PlaceProvider onCreate()
,I/SELinux ( 3593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/USB_UICC(  299): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  299): usb_uicc_init_qmi failed ! 
I/USB_UICC(  299): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  299): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/Settings_Utils( 1322): isSupportVNFestival SM-A300FU XEO
,D/TimaKeyStoreProvider( 3593): TimaSignature is unavailable
,D/ActivityThread( 3593): Added TimaKeyStore provider
,D/UserAnalysis.SecureDbManager( 3562): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3562): SecurePlaceDbHelper() 
D/UserAnalysis( 3562): Create SecureDbHelper,
,W/ResourceType( 1322): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2334/cgroup.procs: No such file or directory
,I/jxcore-log( 3079): getBuffer is called!!!!
I/jxcore-log( 3079): 
,W/ResourceType( 1322): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/Search.GservicesUpdateTask( 3410): Updating Gservices keys
,I/PCWCLIENTTRACE_LOG( 3593): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3593): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3593): new DMDBOpenHelper instance
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/PreloadFilterInstaller( 3578): uses FILTER_DB_VER_1
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/IntelligenceServiceApplication( 3562): onCreate()
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3562): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/SQLiteLog( 3578): (284) automatic index on titles(filter_id)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  ( 3616): MountEmulatedStorage(),
,E/Zygote  ( 3616): v2
I/libpersona( 3616): KNOX_SDCARD checking this for 10056,
I/libpersona( 3616): KNOX_SDCARD not a persona,
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3616 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
I/SELinux ( 3616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 1734:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/SELinux ( 3616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3616): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/IntelligenceServiceApplication( 3562): no applications having user consent for prediction
,I/FilterProviderReceiver( 3578): onReceive in FilterProviderReceiver
,I/FilterProviderReceiver( 3578): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/PCWCLIENTTRACE_DMContentProvider( 3593): [URIMatcher] - result : 2,
,D/TimaKeyStoreProvider( 3616): TimaSignature is unavailable
D/ActivityThread( 3616): Added TimaKeyStore provider
,E/Zygote  ( 3632): MountEmulatedStorage(),
E/Zygote  ( 3632): v2
I/SELinux ( 3632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3632): KNOX_SDCARD checking this for 10098
I/libpersona( 3632): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3632 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2588:com.android.calendar/u0a131 (adj 15): empty #31
,I/SELinux ( 3632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3562): [PlaceDetection::stopService] Service stopped.
,I/DBG_FMMDM( 3544): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3544): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 3632): TimaSignature is unavailable
I/DBG_FMMDM( 3544): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
D/ActivityThread( 3632): Added TimaKeyStore provider
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3648): MountEmulatedStorage()
,E/Zygote  ( 3648): v2
I/libpersona( 3648): KNOX_SDCARD checking this for 1000
I/libpersona( 3648): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2691:com.android.chrome/u0a77 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 2637:com.android.keychain/1000 (adj 15): empty #32
,W/art     ( 3410): Suspending all threads took: 105.770ms
,I/SELinux ( 3648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3562): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3562): Constructor Preference
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3648): TimaSignature is unavailable
,D/ActivityThread( 3648): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1734/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10131/pid_2588/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10077/pid_2691/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2637/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 3632): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3632): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3671): MountEmulatedStorage()
E/Zygote  ( 3671): v2
I/libpersona( 3671): KNOX_SDCARD checking this for 10099
I/libpersona( 3671): KNOX_SDCARD not a persona
,I/SELinux ( 3671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3671): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3671 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,D/TimaKeyStoreProvider( 3671): TimaSignature is unavailable
,D/ActivityThread( 3671): Added TimaKeyStore provider
,I/System.out( 3170): Thread-452 calls detatch()
,I/UpdateLanguagePacksTask( 3410): Checking for language pack updates.
,D/WearableService( 1792): callingUid 10011, callindPid: 1792
,I/ActivityManager( 1020): Killing 2481:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,E/GmsWearableNodeHelper( 1792): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/UpdateIcingCorporaServi( 3410): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/WebViewFactory( 3410): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 3410): Loading: webviewchromium
,I/LibraryLoader( 3410): Time to load native libraries: 4 ms (timestamps 6883-6887)
I/LibraryLoader( 3410): Expected native library version number "",actual native library version number ""
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 21381(1212KB) AllocSpace objects, 4(70KB) LOS objects, 33% free, 22MB/33MB, paused 5.051ms total 184.157ms
,I/ActivityManager( 1020): Killing 2751:com.android.email/u0a141 (adj 15): empty #31
,I/sCloudBackupApp( 3616): sCloudBackupApp Version Info : 4.04.7.KK_APP
,W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_2481/cgroup.procs: No such file or directory
,W/GAV2    ( 3410): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 3410): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,W/art     ( 3410): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDS( 3648): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3648): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3295)  
,I/ActivityManager( 1020): Killing 2847:com.mobeam.barcodeService/1000 (adj 15): empty #31
,D/PCWCLIENTTRACE_DMContentProvider( 3593): [URIMatcher] - result : 2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/DBG_FMMDS( 3648): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/DBG_FMMDS( 3648): [50.18.150420][Line:43][xdbDBInit] 
,I/LockPatternUtils( 1322): isSmartCardAuthenticationAvailable: false
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1020): failed to open /acct/uid_10141/pid_2751/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2847/cgroup.procs: No such file or directory
,I/System.out( 3273): pool-10-thread-1 calls detatch()
,E/SMD     (  290): DCD OFF
,I/DBG_FMMDS( 3648): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10052
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDS( 3648): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3648): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 2038): Spent 52ms computing apk sha1.
,D/FileApkUtils( 2038): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2038): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-cf053f76526e84be2388d3f24ecde21377d895e5@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/DBG_FMMDS( 3648): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3648): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3648): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3648): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,E/Zygote  ( 3707): MountEmulatedStorage()
E/Zygote  ( 3707): v2
I/libpersona( 3707): KNOX_SDCARD checking this for 10058
I/libpersona( 3707): KNOX_SDCARD not a persona
,I/SELinux ( 3707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  308): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 647us total 20.215ms
,I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3707 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3707): TimaSignature is unavailable
,D/ActivityThread( 3707): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 19.451ms
,I/qtaguid ( 3410): Tagging socket 42 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
,D/DexOptUtils( 2038): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2038): Keeping up-to-date module: module-cf053f76526e84be2388d3f24ecde21377d895e5
,D/ChimeraCfgMgr( 2038): Reading stored module config
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 18.609ms
,I/FOTA_Client( 3390): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3390): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3390): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/Gmail   ( 3671): getAccountsCursor
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/FOTA_Client( 3390): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3726): MountEmulatedStorage()
,E/Zygote  ( 3726): v2
I/libpersona( 3726): KNOX_SDCARD checking this for 10013
I/libpersona( 3726): KNOX_SDCARD not a persona
,I/SELinux ( 3726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3726): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1020): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3726 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,D/GmsModuleFndr( 2038): Beginning GMS chimera module scan
,D/TimaKeyStoreProvider( 3726): TimaSignature is unavailable
,D/ActivityThread( 3726): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 2876:flipboard.boxer.app/u0a97 (adj 15): empty #31
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1322): InitSerachDBThread thread end!
,D/GmsModuleFndr( 2038): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ChimeraCfgMgr( 2038): Beginning module configuration check
,I/ExternalOEMControlProvider( 3707): onCreate
D/btif_config_util( 2614): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,D/ChimeraCfgMgr( 2038): Module APKs unchanged, check complete
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 3671): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 3745): MountEmulatedStorage()
,E/Zygote  ( 3745): v2
I/libpersona( 3745): KNOX_SDCARD checking this for 1000
I/libpersona( 3745): KNOX_SDCARD not a persona
I/SELinux ( 3745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3745 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 2907:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/SettingsProvider( 1020): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1020): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,E/AclDataUtils( 2667): Circle ID not found for type: 9
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3745): TimaSignature is unavailable
,D/ActivityThread( 3745): Added TimaKeyStore provider
,I/Gmail   ( 3671): Observing account changes for notifications
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
,I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
,I/qtaguid ( 3410): Untagging socket 46
I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
I/qtaguid ( 3410): Untagging socket 46
,W/libprocessgroup( 1020): failed to open /acct/uid_10097/pid_2876/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1101/pid_2907/cgroup.procs: No such file or directory
,V/OneTimeInitializerReceiver( 3726): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3726): OneTimeService.onHandleIntent,
,W/ResourcesManager( 3745): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/ServiceMode( 3745): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3745): setReferenceIsDumpState : 0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3768): MountEmulatedStorage()
,E/Zygote  ( 3768): v2
I/libpersona( 3768): KNOX_SDCARD checking this for 1000
I/libpersona( 3768): KNOX_SDCARD not a persona
,I/SELinux ( 3768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/System.out( 1792): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1792): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1792): (HTTPLog)-Static: isShipBuild true
I/System.out( 1792): (HTTPLog)-Thread-170-346377573: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1792): (HTTPLog)-Static: isSBSettingEnabled false
,I/SELinux ( 3768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2949:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
I/System.out( 1792): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1792): (HTTPLog)-Static: isShipBuild true
I/System.out( 1792): (HTTPLog)-Thread-154-867690076: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1792): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/qtaguid ( 3410): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3410, getuid(): 10052
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/TimaKeyStoreProvider( 3768): TimaSignature is unavailable
,D/ActivityThread( 3768): Added TimaKeyStore provider
I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,E/Gmail   ( 3671): Error finding the version of the Email provider.....
E/Gmail   ( 3671): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3671): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3671): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3671): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3671): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3671): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/File    ( 3410): fail readDirectory() errno=2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3410): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/Icing   ( 2038): Storage manager: low false usage 2.08MB avail 9.99GB capacity 11.63GB
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/InstanceID/Rpc( 2038): Found 10011
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,E/ActivityThread( 3671): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@312ef024 that was originally bound here
E/ActivityThread( 3671): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@312ef024 that was originally bound here
E/ActivityThread( 3671): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3671): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3671): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3671): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3671): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3671): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3671): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3671): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3671): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3671): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3671): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3671): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3671): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1020): Unbind failed: could not find connection for android.os.BinderProxy@13f46b0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3798): MountEmulatedStorage(),
I/libpersona( 3798): KNOX_SDCARD checking this for 10102
E/Zygote  ( 3798): v2
I/libpersona( 3798): KNOX_SDCARD not a persona
,I/SELinux ( 3798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3798 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3798): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3798): TimaSignature is unavailable
,D/ActivityThread( 3798): Added TimaKeyStore provider
,I/System.out( 1792): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1792): Tagging socket 54 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1792, getuid(): 10011
I/System.out( 1792): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1792): Tagging socket 68 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1792, getuid(): 10011
,I/GoogleHttpClient( 1645): GMS http client unavailable, use old client
,D/NPS_WSSNPS( 3768): [] android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ContextImpl( 3768): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ResourcesManager( 3798): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 3215(140KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 889us total 28.127ms
,D/NPS_WSSNPS( 3768): [] Service onCreate!!
,W/SQLiteConnectionPool( 1645): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #4
,I/Hs20UtilService( 1664): Message received 5003
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3823): MountEmulatedStorage()
,E/Zygote  ( 3823): v2
I/libpersona( 3823): KNOX_SDCARD checking this for 1000
I/libpersona( 3823): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 3831): MountEmulatedStorage()
I/libpersona( 3831): KNOX_SDCARD checking this for 10018
E/Zygote  ( 3831): v2
I/libpersona( 3831): KNOX_SDCARD not a persona
,I/SELinux ( 3831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3831 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10153/pid_2949/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3823): TimaSignature is unavailable
,D/ActivityThread( 3823): Added TimaKeyStore provider
,I/qtaguid ( 1792): Tagging socket 71 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1792, getuid(): 10011
I/qtaguid ( 1792): Tagging socket 72 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1792, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3768): [50.150321] NpsServiceTask Start
,D/NPS_WSSNPS( 3768): [50.150321] smlDBHelper
,D/TimaKeyStoreProvider( 3831): TimaSignature is unavailable
,D/ActivityThread( 3831): Added TimaKeyStore provider
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.123: ( 3831): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 01 15:33:31 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3831): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3831): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3831): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3831): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 3859): MountEmulatedStorage()
I/libpersona( 3859): KNOX_SDCARD checking this for 10020
E/Zygote  ( 3859): v2
I/libpersona( 3859): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3831): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/ActivityManager( 1020): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3859 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/KLMS-2.5.123: ( 3831): KLMSIntentService(): BOOT_COMPLETED
,I/SELinux ( 3859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3859): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1020): name = access_control_enabled
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3859): TimaSignature is unavailable
,D/ActivityThread( 3859): Added TimaKeyStore provider
,E/Zygote  ( 3875): MountEmulatedStorage(),
E/Zygote  ( 3875): v2
I/libpersona( 3875): KNOX_SDCARD checking this for 10065
I/libpersona( 3875): KNOX_SDCARD not a persona
,I/SELinux ( 3875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3875 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Killing 2965:com.sec.usbsettings/1000 (adj 15): empty #31
E/SELinux ( 3875): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/NPS_WSSNPS( 3768): [50.150321] AsyncBulkFlagCheck
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3768): [50.150321] IsRemain_AsyncBulkCheck
,I/KLMS-2.5.123: ( 3831): KLMSIntentService(): onDestroy()
,I/NPS_WSSNPS( 3768): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3768): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,D/TimaKeyStoreProvider( 3875): TimaSignature is unavailable
,D/ActivityThread( 3875): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/NPS_WSSNPS( 3768): [50.150321] Service onDestroy
,I/NPS_WSSNPS( 3768): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRMessageDelete
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3768): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3768): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3768): [50.150321] cpuBooster release : false
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2965/cgroup.procs: No such file or directory
,D/NPS_WSSNPS( 3768): [50.150321] dsServerSocket close
,I/ActivityManager( 1020): Killing 2224:flipboard.app/u0a96 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3895): MountEmulatedStorage()
,E/Zygote  ( 3895): v2
I/libpersona( 3895): KNOX_SDCARD checking this for 1000
I/libpersona( 3895): KNOX_SDCARD not a persona
I/SELinux ( 3895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2364:com.android.mms/u0a41 (adj 15): empty #31
,I/RlzPingService( 3465): Setting next ping for 1457447611589
,D/FileShare-Server( 3875): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/CountryDetector( 1020): No listener is left
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3895): TimaSignature is unavailable
,D/ActivityThread( 3895): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 3010:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_2364/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10096/pid_2224/cgroup.procs: No such file or directory
,E/MTPRx   ( 3895): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,V/MTPRx   ( 3895): sealedState: false
V/MTPRx   ( 3895): sealedUsbMassStorageState: false
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = mtp_usb_connection_status
,D/ChimeraCfgMgr( 2038): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/SettingsProvider( 1020): name = media_player_mode
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/GCM     ( 2038): COMPAT: Multi user not supported
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,D/GCM     ( 1792): COMPAT: Multi user not supported
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BootCompletedReceiver( 2038): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2038): Got an BootCompleted event.
,D/SettingsProvider( 1020): name = mtp_running_status
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BootCompletedReceiver( 2038): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SettingsProvider( 1020): name = media_mount_count
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3798): MmsConfig: mnc/mcc: 0/0
,D/SettingsProvider( 1020): name = mtp_sync_alive
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3798): MmsConfig.loadMmsSettings
,I/Babel   ( 3798): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3798): MmsConfig.loadFromDatabase
D/SettingsProvider( 1020): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/GCoreUlr( 2038): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/libprocessgroup( 1020): failed to open /acct/uid_10043/pid_3010/cgroup.procs: No such file or directory
,D/SettingsProvider( 1020): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 1581:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/CheckinService( 2038): Checkin interval check for package: unspecified last checkin: 1456599118758 min interval config: 0 actual interval: 243693081
,E/Babel   ( 3798): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3798): MmsConfig.loadFromResources
E/Babel   ( 3798): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3798): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/VideoCapabilities( 3798): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_1581/cgroup.procs: No such file or directory
,D/FactoryTestApp( 2572): [DummyFtClient$onDestroy](2572) Destroy DummyFtClient service
,W/AudioCapabilities( 3798): Unsupported mime audio/evrc
,W/AudioCapabilities( 3798): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3798): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3798): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3798): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3798): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3798): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3798): Unsupported mime audio/evrc
,I/CheckinService( 2038): Disabling old GoogleServicesFramework version
,W/VideoCapabilities( 3798): Unsupported mime video/wvc1
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 26548(1380KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.697ms total 195.546ms
,W/bdH     ( 2832): Application name is not set. Call Builder#setApplicationName.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2038): onCreate
,W/VideoCapabilities( 3798): Unsupported mime video/x-ms-wmv
,D/FactoryTestApp( 2572): [Support$Values.getString](2572) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2572): [ModuleCommon$isConnectionModeNone](2572) mConnectionMode = gsm
I/FactoryTestApp( 2572): [ModuleCommon$isRunningFtClient](2572) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2572): [DummyFtClient$onDestroy](2572) kill process
I/Process ( 2572): Sending signal. PID: 2572 SIG: 9
,I/ActivityManager( 1020): Killing 2888:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1020): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,I/System.out( 2832): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2832): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 2832): (HTTPLog)-Static: isShipBuild true
I/System.out( 2832): (HTTPLog)-Thread-334-292639383: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 2832): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10087
,I/System.out( 2832): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 3593): SPPPushClient is installed : true
,I/Gmail   ( 3671): getAccountsCursor
I/PCWCLIENTTRACE_PushUtil( 3593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3593): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3593): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3593): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3593): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/ActivityManager( 1020): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3943): MountEmulatedStorage()
E/Zygote  ( 3943): v2
I/libpersona( 3943): KNOX_SDCARD checking this for 1000
I/libpersona( 3943): KNOX_SDCARD not a persona
,I/SELinux ( 3943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 2832): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 3943): TimaSignature is unavailable
,D/ActivityThread( 3943): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3798): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/Settings( 3798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SystemUpdateService( 2038): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/SQLiteLog( 3671): (283) recovered 4 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager( 1020): Process com.sec.factory (pid 2572)(adj 0) has died(50,623)
,I/DBG_POLICYDM( 3355): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/VideoCapabilities( 3798): Unsupported mime video/wvc1
,W/VideoCapabilities( 3798): Unsupported mime video/x-ms-wmv
,W/PCWCLIENTTRACE_AccountUtil( 3593): [hasSamungAccount] - No Samsung Account
,V/AuthZen ( 2038): Handling intent: android.intent.action.BOOT_COMPLETED
,I/CheckinService( 2038): Checking schedule, now: 1456842812251 next: 1457166045303
I/CheckinService( 2038): active receiver: disabled
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3798): Unsupported mime video/x-ms-wmv7
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenEventHandler( 2038): Handling event: android.intent.action.BOOT_COMPLETED
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3593): [GetString-S]
,W/VideoCapabilities( 3798): Unsupported mime video/x-ms-wmv8
,I/DBG_POLICYDM( 3355): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,W/VideoCapabilities( 3798): Unsupported mime video/mp43
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3355): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/SystemUpdateService( 2038): cancelUpdate (empty URL)
I/SystemUpdateService( 2038): active receiver: disabled
,I/System.out( 1792): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1792): Tagging socket 68 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1792, getuid(): 10011
,W/libprocessgroup( 1020): failed to open /acct/uid_10081/pid_2888/cgroup.procs: No such file or directory
,W/VideoCapabilities( 3798): Unsupported mime video/sorenson
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/ReactiveServiceManager( 3593): Supported : 1
,W/VideoCapabilities( 3798): Unsupported mime video/mp4v-esdp
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
,I/VideoCapabilities( 3798): Unsupported profile 4 for video/mp4v-es
,W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/SystemUpdateService( 2038): onDestroy
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3966): MountEmulatedStorage()
E/Zygote  ( 3966): v2
I/libpersona( 3966): KNOX_SDCARD checking this for 1000
I/libpersona( 3966): KNOX_SDCARD not a persona
,I/SELinux ( 3966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/File    ( 3671): fail readDirectory() errno=2
I/SELinux ( 3966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/QSEECOMAPI: ( 1020): Loaded image: APP id = 9
,E/SELinux ( 3966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/BaseAppContext( 2038): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 3593): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3593): [GetString-E]
,I/Gmail   ( 3671): notifyAccountChanged
,I/art     (  308): Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.689ms total 34.265ms
,I/Gmail   ( 3671): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/TimaKeyStoreProvider( 3966): TimaSignature is unavailable
,D/ActivityThread( 3966): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 642us total 19.259ms
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 3995(162KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 822us total 30.198ms
I/Gmail   ( 3671): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.825ms
,I/PCWCLIENTTRACE_PushUtil( 3593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3593): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3593): [ensureRegistration] - No Samsung account
,V/Babel   ( 3798): babel boot account: SMS
V/Babel   ( 3798): babel boot account: thalitester@gmail.com
,I/Gmail   ( 3671): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3671): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3992): MountEmulatedStorage()
E/Zygote  ( 3992): v2
I/libpersona( 3992): KNOX_SDCARD checking this for 1000
I/libpersona( 3992): KNOX_SDCARD not a persona
I/SELinux ( 3992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
W/ResourcesManager( 3966): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SELinux ( 3992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3119:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,V/AlarmManager( 1020): waitForAlarm result :4
E/Zygote  ( 4009): MountEmulatedStorage()
I/libpersona( 4009): KNOX_SDCARD checking this for 10028
E/Zygote  ( 4009): v2
I/libpersona( 4009): KNOX_SDCARD not a persona
I/SELinux ( 4009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3992): TimaSignature is unavailable
D/ActivityThread( 3992): Added TimaKeyStore provider
I/SELinux ( 4009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4009): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4009 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3094:com.sec.dsm.system/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
I/EventLogService( 2038): Aggregate from 1456840265440 (log), 1456840265440 (data)
,W/PsynchoHelperImpl( 2832): Error fetching or saving configuration
W/PsynchoHelperImpl( 2832): bdz: 404 Not Found
W/PsynchoHelperImpl( 2832): {
W/PsynchoHelperImpl( 2832):   "errors": [
W/PsynchoHelperImpl( 2832):     {
W/PsynchoHelperImpl( 2832):       "domain": "global",
W/PsynchoHelperImpl( 2832):       "reason": "notFound",
W/PsynchoHelperImpl( 2832):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl( 2832):       "locationType": "other",
W/PsynchoHelperImpl( 2832):       "location": "setting"
W/PsynchoHelperImpl( 2832):     }
W/PsynchoHelperImpl( 2832):   ],
W/PsynchoHelperImpl( 2832):   "code": 404,
W/PsynchoHelperImpl( 2832):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl( 2832): }
W/PsynchoHelperImpl( 2832): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl( 2832): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl( 2832): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl( 2832): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl( 2832): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl( 2832): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl( 2832): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl( 2832): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl( 2832): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 2832): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 2832): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 2832): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 2832): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 2832): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 2832): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 2832): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 2832): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 2832): 	at agP.run(LegacySyncManager.java:416)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4009): TimaSignature is unavailable,
D/ActivityThread( 4009): Added TimaKeyStore provider,
,E/Zygote  ( 4023): MountEmulatedStorage(),
E/Zygote  ( 4023): v2
I/libpersona( 4023): KNOX_SDCARD checking this for 1000
I/libpersona( 4023): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/F_PHONE ( 3966): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/SELinux ( 4023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AuthZen ( 2038): Fetching signing key...
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,V/AlarmManager( 1020): waitForAlarm result :4
,D/TimaKeyStoreProvider( 4023): TimaSignature is unavailable
,D/ActivityThread( 4023): Added TimaKeyStore provider
,D/F_PHONE ( 3966): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3966): default registerAction()
I/F_PHONE ( 3966): [[com.sec.bcservice]] sendPendingMessage()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ResourcesManager( 4023): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/BluetoothBDAdrressReceiver( 4023): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4023): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ResourcesManager( 1458): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/BluetoothBDTestService( 1458): onCreate()
,E/BluetoothBDTestService( 1458): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1458): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1458): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 4043): MountEmulatedStorage()
E/Zygote  ( 4043): v2
I/libpersona( 4043): KNOX_SDCARD checking this for 1000
I/libpersona( 4043): KNOX_SDCARD not a persona
,I/SELinux ( 4043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3182:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,I/SELinux ( 4043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4043): TimaSignature is unavailable
,D/ActivityThread( 4043): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3119/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3094/cgroup.procs: No such file or directory
,W/ResourcesManager( 4043): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AuthZen ( 2038): Signing key fetched successfully!
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3182/cgroup.procs: No such file or directory
,I/Gmail   ( 3671): getAccountsCursor
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 4043): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3943): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3943): Resource data:2131165186
,I/KnoxUsageLogPro( 4043): premStatus:2
,D/GCM     ( 1792): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/KnoxUsageLogPro( 4043): isEulaShown : false
I/KnoxUsageLogPro( 4043): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1020): Killing 3205:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/KnoxUsageLogPro( 4043): savePreference: key = previous_sys_time value = 1456842812865
,W/ResourcesManager( 3943): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 4009): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 4009): Inside WakeupProvider
,I/KnoxUsageLogPro( 4043): savePreference: key = previous_elapsed_time value = 39595
,I/AMMetaDataParserService( 3943): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 3943): getResourceTypeNamexml
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 2038): Using Auth Proxy for data requests.
I/AMMetaDataParserService( 3943): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,E/Zygote  ( 4067): MountEmulatedStorage()
,E/Zygote  ( 4067): v2
I/libpersona( 4067): KNOX_SDCARD checking this for 1000
I/libpersona( 4067): KNOX_SDCARD not a persona
I/SELinux ( 4067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4067): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Killing 3251:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3943): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/ContactAccountLoggerTas( 3410): canRun() : Opted Out
,I/AMMetaDataParserService( 3943): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.f,irefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
D/PowerManagerService( 1020): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1173 (0x0)
,W/art     ( 4009): Verification of void com.vlingo.midas.settings.MidasSettings.<clinit>() took 100.190ms
,D/TimaKeyStoreProvider( 4067): TimaSignature is unavailable
,D/ActivityThread( 4067): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131034113
,I/VlingoApplication( 4009): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,W/ResourcesManager( 3943): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3943): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3943): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3943): getResourceTypeNamexml
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1020): failed to open /acct/uid_10146/pid_3205/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3251/cgroup.procs: No such file or directory
,I/GFX construct_block_size_descriptor_2d second part( 3943): took 7.303281ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3943): took 11.758756ms for 0*0 texture 0
,I/GFX raster( 3943): took 21.104641ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e50e78 counterpartCT=4 counterpartW=96 counterparth=96
,E/KnoxSetupWizardClient( 4067): isShipMode : 1
I/KnoxSetupWizardClient( 4067): onReceive : android.intent.action.BOOT_COMPLETED
,I/VlingoAndroidCore( 4009): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,I/AMMetaDataParserService( 3943): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 1.121250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e373e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ShortcutReceiver( 4067):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3943): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/GCM     ( 1792): GCM config loaded
,D/KnoxShortcutUtil( 4067): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4067):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4067):  shortcut migration not required 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4093): MountEmulatedStorage()
I/libpersona( 4093): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4093): v2
I/libpersona( 4093): KNOX_SDCARD not a persona
,I/SELinux ( 4093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3141:com.google.android.configupdater/u0a82 (adj 15): empty #31
,I/SELinux ( 4093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/System.err( 4067): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4067): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4067): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4067): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4067): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4067): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4067): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/a       ( 2038): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2038): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2038): Clearing transaction cache
,D/TimaKeyStoreProvider( 4093): TimaSignature is unavailable
,D/ActivityThread( 4093): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 3273:com.dropbox.android/u0a88 (adj 15): empty #31
,D/VlingoApplication( 4009): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 4009): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GCoreUlr( 1792): DispatchingService.onCreate()
,I/GFX construct_block_size_descriptor_2d second part( 3943): took 2.663749ms for 0*0 texture 0,
,I/GFX generate_partition_tables( 3943): took 8.681823ms for 0*0 texture 0
,I/GFX raster( 3943): took 12.302290ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e37f68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e37fc8 counterpartCT=4 counterpartW=96 counterparth=96
,D/DialogFlow( 4009): initQueue()
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/AMMetaDataParserService( 3943): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4112): MountEmulatedStorage()
E/Zygote  ( 4112): v2
I/libpersona( 4112): KNOX_SDCARD checking this for 10029
I/libpersona( 4112): KNOX_SDCARD not a persona
I/SELinux ( 4112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4112 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusChecker( 4093): onReceive : android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1020): Killing 3334:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 4112): TimaSignature is unavailable
,D/ActivityThread( 4112): Added TimaKeyStore provider
,I/StatusChecker( 4093): onReceive : net.mt.init : DONE
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4128): MountEmulatedStorage()
E/Zygote  ( 4128): v2
I/libpersona( 4128): KNOX_SDCARD checking this for 10113
I/libpersona( 4128): KNOX_SDCARD not a persona
,I/SELinux ( 4128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/GFX raster( 3943): took 0.673697ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e369d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1020): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4128 uid=10113 gids={50113, 9997} abi=armeabi-v7a
E/SELinux ( 4128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Killing 3355:com.policydm/1000 (adj 15): empty #31
,E/SMD     (  290): DCD OFF
,I/Icing   ( 2038): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4128): TimaSignature is unavailable
,D/ActivityThread( 4128): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10082/pid_3141/cgroup.procs: No such file or directory
,D/SyncManager( 1020): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 30987, mTimeoutStartTime 30987, mHistoryRowId 7, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 22727, reason: Periodic
,I/AMMetaDataParserService( 3943): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_3273/cgroup.procs: No such file or directory
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.915781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e369d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c5c4c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 2832): Thread-334(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2832): Thread-334(ApacheHTTPLog):isShipBuild true
I/System.out( 2832): Thread-334(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2832): Thread-334(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10087
,I/AMMetaDataParserService( 3943): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/Gmail   ( 3671): getAccountsCursor
,I/GCoreUlr( 1792): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/PageBuddyNotiSvc( 4128): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_3334/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 2396:com.android.defcontainer/u0a3 (adj 15): empty #31
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4128): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4128): onCreate mCpBitFlag=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4155): MountEmulatedStorage(),
E/Zygote  ( 4155): v2,
I/libpersona( 4155): KNOX_SDCARD checking this for 10030
I/SELinux ( 4155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4155): KNOX_SDCARD not a persona
,I/SELinux ( 4155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1020): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4155 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4155): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3494:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.683230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e373e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e37fc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
E/Zygote  ( 4167): MountEmulatedStorage()
I/libpersona( 4167): KNOX_SDCARD checking this for 10121
E/Zygote  ( 4167): v2
I/libpersona( 4167): KNOX_SDCARD not a persona
,I/SELinux ( 4167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4167 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3355/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4155): TimaSignature is unavailable
,D/ActivityThread( 4155): Added TimaKeyStore provider
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.723073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7c5c4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e37fc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/TimaKeyStoreProvider( 4167): TimaSignature is unavailable
,D/ActivityThread( 4167): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10003/pid_2396/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10090/pid_3494/cgroup.procs: No such file or directory
,W/ResourcesManager( 4167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4167): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/Auth    ( 1792): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1792): No location to return for getLastLocation()
,W/FusedLocationProvider( 1792): location=null
,V/GLSActivity( 1792): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1792): No location to return for getLastLocation()
,W/FusedLocationProvider( 1792): location=null
,D/QuickConnect( 4167): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = scon_is_running
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10121
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4167): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4167): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/QuickConnect( 4167): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.575052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e37fc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4194): MountEmulatedStorage()
E/Zygote  ( 4194): v2
I/libpersona( 4194): KNOX_SDCARD checking this for 10127
I/libpersona( 4194): KNOX_SDCARD not a persona
,I/SELinux ( 4194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3943): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
E/SELinux ( 4194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4194 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131034113
,I/AMMetaDataParserService( 3943): getResourceName:com.android.contacts:xml/assistant_main
W/ResourcesManager( 4155): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3943): getResourceTypeNamexml
W/ResourcesManager( 4155): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4155): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/GFX raster( 3943): took 0.838490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
I/art     (  308): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 21.265ms
,I/AMMetaDataParserService( 3943): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.531ms
,D/TimaKeyStoreProvider( 4194): TimaSignature is unavailable
D/ActivityThread( 4194): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.561ms
,I/GCoreUlr( 1792): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ResourcesManager( 4194): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/PersistentNotificationBroadcastReceiver( 1792): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ResourcesManager( 4194): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4194): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4194): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4155): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4155): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4155): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4155): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 1020): SIOP:: AP = 400
,D/BluetoothAdapter( 3079): disable()
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4212 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4212): MountEmulatedStorage()
I/libpersona( 4212): KNOX_SDCARD checking this for 10026
E/Zygote  ( 4212): v2
I/libpersona( 4212): KNOX_SDCARD not a persona
I/SELinux ( 4212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/SettingsProvider( 1020): name = bluetooth_on
,I/SELinux ( 4212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4212): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.881250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/BluetoothAdapterState( 2614): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2614): Setting state to 13
I/BluetoothAdapterState( 2614): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2614): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2614): updateAdapterState state is 13
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2614): Autoconnection is available 
,D/BluetoothAdapterService( 2614): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2614): terminating service from this receiver
I/BluetoothPbapService( 2614): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothSocket( 2614): close() in, this: android.bluetooth.BluetoothSocket@3594de66, channel: 19, state: LISTENING
D/BluetoothSocket( 2614): close() this: android.bluetooth.BluetoothSocket@3594de66, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17db7ba8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1509f5a7mSocket: android.net.LocalSocket@2440aa54 impl:android.net.LocalSocketImpl@34664dfd fd:FileDescriptor[74]
D/BluetoothSocket( 2614): Closing mSocket: android.net.LocalSocket@2440aa54 impl:android.net.LocalSocketImpl@34664dfd fd:FileDescriptor[74]
,I/AMMetaDataParserService( 3943): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533,
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
D/WifiService( 1020): setWifiEnabled: false pid=3079, uid=10168
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2614): onBluetoothDisable()
,D/BluetoothAdapterProperties( 2614): mDiscovering is false
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =13
,D/SecContentProvider( 1020): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2614): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/SettingsProvider( 1020): name = wifi_on
,D/TimaKeyStoreProvider( 4212): TimaSignature is unavailable
,D/ActivityThread( 4212): Added TimaKeyStore provider
,I/jxcore-log( 3079): ****TEST TOOK:  5154  ms ****
I/jxcore-log( 3079): 
,I/jxcore-log( 3079): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3079): 
E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.612812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e37f68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
E/WifiStateMachine( 1020): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1391): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1391): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1391): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1391): Scan requested (ret=0) - scan timeout 30 seconds
I/art     ( 1020): Explicit concurrent mark sweep GC freed 36882(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 22MB/34MB, paused 26.574ms total 209.029ms
,D/BluetoothTile( 1173):  onBluetoothStateChange:
,I/AMMetaDataParserService( 3943): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  getBluetoothState : 13
,E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,I/SamsungIME( 1836): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,D/BluetoothAdapterProperties( 2614): Scan Mode:20
,D/STATUSBAR-QSTileView( 1173): onStateChanged: Bluetooth
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=false
,D/BluetoothAdapterState( 2614): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2614): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,E/bt-btif ( 2614): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,E/bt-btif ( 2614): cmd socket is not created
,D/btif_config_util( 2614): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2614): btm_ble_start_auto_conn start : 0, 0,
W/bt-btif ( 2614): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2614): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x001b not found for deregistration
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1792): Read error: ssl=0xb803ddc8: I/O error during system call, Connection timed out
,I/System.out( 2832): SyncManager calls detatch()
,E/HttpIssuerBase( 2832): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 2832): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 2832): java.io.IOException
E/HttpIssuerBase( 2832): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 2832): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 2832): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 2832): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 2832): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 2832): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 2832): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 2832): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 2832): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 2832): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 2832): 	at agP.run(LegacySyncManager.java:416)
,D/BluetoothSocket( 2614): close() in, this: android.bluetooth.BluetoothSocket@30d64543, channel: 5, state: LISTENING
D/BluetoothSocket( 2614): close() this: android.bluetooth.BluetoothSocket@30d64543, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@141106c1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@292817c0mSocket: android.net.LocalSocket@1bceccf9 impl:android.net.LocalSocketImpl@1b17543e fd:FileDescriptor[76]
D/BluetoothSocket( 2614): Closing mSocket: android.net.LocalSocket@1bceccf9 impl:android.net.LocalSocketImpl@1b17543e fd:FileDescriptor[76]
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NativeCrypto( 1792): SSL shutdown failed: ssl=0xb803ddc8: I/O error during system call, Broken pipe
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityService( 1020): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1020): Tagging socket 343 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
,I/qtaguid ( 1020): Untagging socket 343
I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiP2pService( 1020): InactiveState{ what=131204 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 1020): sending p2p connection changed broadcast: FAILED
,D/WifiNetworkAgent( 1020): NetworkAgent: NetworkAgent channel lost
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiScanningService( 1020): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1020): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1020): SCAN_AVAILABLE : 1
,D/RttService( 1020): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/GCoreUlr( 1792): Unbound from all location providers
,I/GCoreUlr( 1792): Place inference reporting - stopped
,D/WifiDisplayController( 1020): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1020): onP2pDisconnected
,D/WifiP2pService( 1020): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 1020): P2pDisablingState
,D/WifiP2pService( 1020): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1020): p2p socket connection lost
,D/WifiP2pService( 1020): P2pDisabledState
,E/WifiStateMachine( 1020): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiP2pService( 1020): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1020): DefaultState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GCoreUlr( 1792): DispatchingService.onDestroy()
,I/GCoreUlr( 1792): Stopping handler for UlrDispSvcFast
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/GCoreUlr( 1792): Unbound from all location providers
I/GCoreUlr( 1792): Place inference reporting - stopped
,D/SBrowserFeatureFlag( 4194): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 4194): onCreate()
,E/NetworkSettingsReceiver( 4194): onReceive: android.intent.action.BOOT_COMPLETED
,D/IpRemoteDisplayController( 1020): disconnectWfdBridgeServer,
D/IpRemoteDisplayController( 1020): WfdBridgeServer is already null
D/WifiDisplayController( 1020): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1020): disconnect
D/WifiDisplayController( 1020): updateConnection
D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1020): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1020): onP2pDisconnected
,D/IpRemoteDisplayController( 1020): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1020): WfdBridgeServer is already null
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,W/bt-l2cap( 2614): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x0017 not found for deregistration,
W/bt-l2cap( 2614): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2614): L2CAP - PSM: 0x001b not found for deregistration
,W/bt-l2cap( 2614): btif_in_execute_service_request : 20 disabled
W/bt-l2cap( 2614): L2CAP - PSM: 0x0017 not found for deregistration
D/AllShareCastTile( 1173): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
W/bt-l2cap( 2614): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2614): ag scb idx 1 not allocated
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/bt-btif ( 2614): ag scb idx 2 not allocated
E/bt-btif ( 2614): HC lpm_result_cb 0
,I/bt_userial_mct( 2614): exiting userial_read_thread
D/bt_userial_mct( 2614): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2614): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2614): hw_epilog_process,
D/bt_userial_mct( 2614): userial_close
I/bt_vendor( 2614): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/AllShareCastTile( 1173): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1020): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1020): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1020): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.107/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1020): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1458): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/wpa_supplicant( 1391): p2p0: State: DISCONNECTED -> DISCONNECTED
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524292
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false,
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
D/ConnectivityManager.CallbackHandler( 2038): CM callback handler got msg 524292
D/ConnectivityService( 1020): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): doQuit - quitNow()
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1020): updateNetworkInfo()
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): updateIfacesLocked()
V/NetworkStats( 1020): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit,
V/NetworkStats( 1020): performPollLocked() took 4ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1173): EthernetConnected: false
,D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
,D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(0)
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi
D/SecContentProvider2( 1020): mCursor = null
,D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1173): onReceive : 0, 0
,D/WifiCredService( 1322): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/System.err( 4194): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4194): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4194): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4194): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4194): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4194): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4194): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4194): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,E/SBrowserFeatureFlag( 4194): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@177b2f8a
,D/SBrowserFeatureFlag( 4194): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4194): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/wpa_supplicant( 1391): Blacklist: Clear (all) 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3593): unregister AuthInfo UpdateReceiver v2.0
,E/Zygote  ( 4244): MountEmulatedStorage()
I/libpersona( 4244): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4244): v2
I/libpersona( 4244): KNOX_SDCARD not a persona
,I/SELinux ( 4244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4244 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/SELinux ( 4244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Killing 3530:com.sec.factory.camera/1000 (adj 15): empty #31
E/SELinux ( 4244): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1391): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1020): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,D/TimaKeyStoreProvider( 4244): TimaSignature is unavailable
,D/ActivityThread( 4244): Added TimaKeyStore provider
,I/System.out( 4009): INFO:Resource not found:/Common.properties Using default values
,I/wpa_supplicant( 1391): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
I/wpa_supplicant( 1391): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1391): Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
I/wpa_supplicant( 1391): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1391): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/Tethering( 1020): InitialState.processMessage what=4
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,E/Tethering( 1020): No numeric data
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/AndroidRuntime( 4231): 
D/AndroidRuntime( 4231): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1173): updateTetherState():false, false
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
V/NetworkStats( 1020): performPollLocked() took 8ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3530/cgroup.procs: No such file or directory
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 4244): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4244): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3,
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/bt_vendor( 2614): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2614): bluetooth satus is on
I/bt_vendor( 2614): bt-vendor : resetting BT status
I/bt_vendor( 2614): Starting hciattach daemon
I/bt_vendor( 2614): try to set false
I/bt_vendor( 2614): Starting hciattach daemon
I/bt_vendor( 2614): try to set false
,I/bt_vendor( 2614): cleanup
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/GKI_LINUX( 2614): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2614): GKI_exit_task 0 done
I/GKI_LINUX( 2614): GKI_shutdown(): task [BTU] terminated
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterState( 2614): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2614): isSecureModeOn:false
D/BluetoothAdapterService( 2614): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.gatt.GattService
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/BtGatt.DebugUtils( 2614): handleDebugAction() action=null
D/BtGatt.GattService( 2614): Received stop request...Stopping profile...
D/BtGatt.GattService( 2614): stop()
D/BtGatt.AdvertiseManager( 2614): advertise clients cleared
,W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.hid.HidService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2614): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2614): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2614): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2614): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2614): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2614): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2614): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2614): Stopping profile services that were post enabled
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HeadsetService( 2614): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
,D/AudioService( 1020): onServiceDisconnected: Bluetooth profile: 1
,D/A2dpService( 2614): Received stop request...Stopping profile...
D/A2dpStateMachine( 2614): Exit Disconnected: -1
D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
D/BluetoothA2dp( 1020): Proxy object disconnected
D/AudioService( 1020): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 2614): Received stop request...Stopping profile...
D/HidService( 2614): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2614): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2614): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2614): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
D/HealthService( 2614): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
D/PanService( 2614): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
,D/BluetoothPan( 1020): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 2614): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
,D/SapService( 2614): Received stop request...Stopping profile...
D/SapService( 2614): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2614): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b8cf97e
,E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2614): Profile still running: com.android.bluetooth.hid.HidService
,W/BluetoothHeadsetServiceJni( 2614): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2614): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2614): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2614): Proxy object disconnected
D/BluetoothAdapterService( 2614): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2614): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2614): GKI_exit_task 2 done
I/GKI_LINUX( 2614): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2614): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2614): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 2614): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2614): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2614): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2614): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2614): Cleaning up Bluetooth PAN callback object
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2614): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2614): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(462223742)( 2614): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2614): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2614): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 2614): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2614): Setting state to 10
I/BluetoothAdapterState( 2614): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2614): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2614): updateAdapterState state is 10
,D/BluetoothAdapterService( 2614): Autoconnection is available 
D/BluetoothAdapterService( 2614): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2614): Entering OffState
D/BluetoothAdapter( 1173): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1173): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1458): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1458): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1432): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1432): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1440): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1792): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1792): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1020): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1020): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 2614): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2614): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1020): onBluetoothStateChange: up=false
D/BluetoothAdapter( 4009): onBluetoothStateChange: up=false
D/BluetoothAdapter( 4009): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2614): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 3079): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3079): Bluetooth is turned off, stop adv and scan
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/AndroidRuntime( 4231): CheckJNI is OFF
,D/AndroidRuntime( 4231): readGMSProperty: start
D/AndroidRuntime( 4231): readGMSProperty: already setted!!
D/AndroidRuntime( 4231): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4231): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4231): readGMSProperty: end
D/AndroidRuntime( 4231): addProductProperty: start
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
I/InputMethodManagerService( 1020): [BT Setting State] State =10
I/InputMethodManagerService( 1020): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,E/SyncManager( 2832): Network error,
E/SyncManager( 2832): javax.net.ssl.SSLException: Read error: ssl=0xb7e60088: I/O error during system call, Connection timed out
E/SyncManager( 2832): 	at com.android.org.conscrypt.NativeCrypto.SSL_read(Native Method)
E/SyncManager( 2832): 	at com.android.org.conscrypt.OpenSSLSocketImpl$SSLInputStream.read(OpenSSLSocketImpl.java:728)
E/SyncManager( 2832): 	at org.apache.http.impl.io.AbstractSessionInputBuffer.fillBuffer(AbstractSessionInputBuffer.java:103)
E/SyncManager( 2832): 	at org.apache.http.impl.io.AbstractSessionInputBuffer.readLine(AbstractSessionInputBuffer.java:191)
E/SyncManager( 2832): 	at org.apache.http.impl.conn.DefaultResponseParser.parseHead(DefaultResponseParser.java:82)
E/SyncManager( 2832): 	at org.apache.http.impl.io.AbstractMessageParser.parse(AbstractMessageParser.java:174)
E/SyncManager( 2832): 	at org.apache.http.impl.AbstractHttpClientConnection.receiveResponseHeader(AbstractHttpClientConnection.java:180)
E/SyncManager( 2832): 	at org.apache.http.impl.conn.DefaultClientConnection.receiveResponseHeader(DefaultClientConnection.java:235)
E/SyncManager( 2832): 	at org.apache.http.impl.conn.AbstractClientConnAdapter.receiveResponseHeader(AbstractClientConnAdapter.java:259),
E/SyncManager( 2832): 	at org.apache.http.protocol.HttpRequestExecutor.doReceiveResponse(HttpRequestExecutor.java:279)
E/SyncManager( 2832): 	at org.apache.http.protocol.HttpRequestExecutor.execute(HttpRequestExecutor.java:121)
E/SyncManager( 2832): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1393)
E/SyncManager( 2832): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
E/SyncManager( 2832): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
E/SyncManager( 2832): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
E/SyncManager( 2832): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
E/SyncManager( 2832): 	at TC.execute(HttpClientImpl.java:255)
E/SyncManager( 2832): 	at Tx.a(DefaultHttpIssuer.java:54)
E/SyncManager( 2832): 	at TG.b(HttpIssuerBase.java:120)
E/SyncManager( 2832): 	at TG.a(HttpIssuerBase.java:108)
E/SyncManager( 2832): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:235)
E/SyncManager( 2832): 	at Tj.a(DefaultAuthenticatedHttpIssuer.java:171)
E/SyncManager( 2832): 	at Tj.a(DefaultAuthenticatedHttpIssuer.java:104)
E/SyncManager( 2832): 	at afE.a(AccountMetadataUpdater.java:218)
E/SyncManager( 2832): 	at afE.a(AccountMetadataUpdater.java:140)
E/SyncManager( 2832): 	at agO.a(LegacySyncManager.java:828)
E/SyncManager( 2832): 	at agO.b(LegacySyncManager.java:588)
E/SyncManager( 2832): 	at agO.a(LegacySyncManager.java:467)
E/SyncManager( 2832): 	at agO.a(LegacySyncManager.java:97)
E/SyncManager( 2832): 	at agQ.run(LegacySyncManager.java:419)
E/SyncManager( 2832): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/SyncManager( 2832): 	at agP.run(LegacySyncManager.java:416)
W/GAV2    ( 2832): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/BluetoothAdapter( 1173): 681872985: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1173): 681872985: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  getBluetoothState : 10
D/BluetoothAdapter( 1173): 681872985: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1173): 681872985: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1173): 681872985: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/SamsungIME( 1836): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/wpa_supplicant( 1391): Blacklist: Clear (all) 
I/GKI_LINUX( 2614): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2614): GKI_exit_task 1 done
I/GKI_LINUX( 2614): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2614): cleanupNative: return from cleanup
,I/art     ( 2614): System.exit called, status: 0
I/AndroidRuntime( 2614): VM exiting with result code 0, cleanup skipped.
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1391): wlan0: CTRL-EVENT-TERMINATING ,
,D/BluetoothAdapter( 1792): 1069656338: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1792): 1069656338: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 4112): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1020): updateDataUsageMap
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,V/AlarmManager( 1020): waitForAlarm result :8
,I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/ActivityManager( 1020): Process com.android.bluetooth (pid 2614)(adj 0) has died(25,625)
,E/WifiStateMachine( 1020): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
I/DBG_DM  ( 3222): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/WifiNative-wlan0( 1020): callSECApiBoolean - ID [21]
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3943): took 0.606562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(1)
I/AMMetaDataParserService( 3943): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 3798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiCredService( 1322): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1173): onReceive : 1, 0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 1.050990ms for 96*96 texture 0
W/ResourcesManager( 4112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Settings( 1792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 4112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e369d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 4112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3943): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3410): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/Finsky  ( 4212): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/AffinityControl( 4231): AffinityControl: registerfunction enter
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3943): took 0.820833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e373e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime( 4231): Calling main entry com.android.commands.pm.Pm
,W/art     ( 4009): Suspending all threads took: 68.279ms
,E/Zygote  ( 4302): MountEmulatedStorage()
,E/Zygote  ( 4302): v2
I/libpersona( 4302): KNOX_SDCARD checking this for 10037
I/libpersona( 4302): KNOX_SDCARD not a persona
,I/SELinux ( 4302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4302 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GFX raster( 3943): took 0.691198ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7c5c4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/SELinux ( 4302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4302): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3943): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4317 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/Zygote  ( 4317): MountEmulatedStorage()
I/libpersona( 4317): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4317): v2
I/libpersona( 4317): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{173c315b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/SELinux ( 4317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4317): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4302): TimaSignature is unavailable
D/ActivityThread( 4302): Added TimaKeyStore provider
,D/PackageManager( 1020): START PACKAGE DELETE: observer{488024969}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3943): took 0.543229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e37fc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4317): TimaSignature is unavailable
D/ActivityThread( 4317): Added TimaKeyStore provider
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
I/AMMetaDataParserService( 3943): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,I/AMMetaDataParserService( 3943): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3943): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3943): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131034112
,I/AMMetaDataParserService( 3943): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3943): getResourceTypeNamexml
E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3943): took 0.610833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
I/AMMetaDataParserService( 3943): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
W/ResourcesManager( 4317): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10168, uninstall pkg
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10168 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3079:com.example.hello/u0a168 (adj 0): stop com.example.hello cause uninstall pkg
,W/ResourcesManager( 4317): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4317): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4317): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4317): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): Force removing ActivityRecord{1174ea77 u0 com.example.hello/.MainActivity t7}: app died, no saved state
,W/ResourcesManager( 4302): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/FocusedStackFrame( 1020): Set to : 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/InputDispatcher( 1020): Focus left window: 3079
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.610469ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e50a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e060d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/Tethering( 1020): interfaceRemoved wlan0
,E/Tethering( 1020): attempting to remove unknown iface (wlan0), ignoring
,W/PackageSettings( 1020): Skipping PackageSetting{948f44b com.test.thalitest/10167} due to missing metadata
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.822812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e060d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e30f68 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 1.617969ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e373e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2f2c8 counterpartCT=4 counterpartW=96 counterparth=96
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,I/AMMetaDataParserService( 3943): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10168 user=0: pkg removed
,D/Tethering( 1020): interfaceRemoved p2p0
E/Tethering( 1020): attempting to remove unknown iface (p2p0), ignoring
,D/Launcher( 1483): onRestart, Launcher: 393949066
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1483): onStart, Launcher: 393949066
D/Launcher.HomeView( 1483): onStart
,D/Launcher( 1483): onResume, Launcher: 393949066
,D/SettingsProvider( 1020): name = kids_home_mode
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/Launcher.HomeView( 1483): onResume
,I/CalendarProvider2( 4302): CalendarProvider2.onCreate() called
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131034113
,I/AMMetaDataParserService( 3943): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3943): getResourceTypeNamexml
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.896042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7ad4470 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e2bf28 counterpartCT=4 counterpartW=96 counterparth=96
,E/SamsungIME( 1836): mOCRHelper is null
,W/GeofencerStateMachine( 1792): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3943): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/Launcher( 1483): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.872240ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7ad4470 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e2f2c8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3943): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/MenuAppsGridFragment( 1483): onResume
,I/ActivityManager( 1020): Killing 3544:com.fmm.dm/1000 (adj 15): empty #31
,D/ActivityManager( 1020): handle home activity for 0
I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/SurfaceFlinger(  259): id=12 createSurf (540x960),1 flag=4, Mauncher
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.619948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e22c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2bf28 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/GAV2    ( 3671): Thread[GAThread,5,main]: No campaign data found.
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3943): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/InputDispatcher( 1020): Focus entered window: 1483
,D/SRIB_DCS( 1483): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/Finsky  ( 4212): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/Launcher( 1483): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.597448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e5a278 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e37fc8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3943): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4364 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 4364): MountEmulatedStorage()
I/libpersona( 4364): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4364): v2
I/libpersona( 4364): KNOX_SDCARD not a persona
,I/SELinux ( 4364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/Process ( 4155): Sending signal. PID: 4155 SIG: 9
,E/SELinux ( 4364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3079 uid 10168
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4364): TimaSignature is unavailable
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,D/ActivityThread( 4364): Added TimaKeyStore provider
W/ActivityManager( 1020): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/GFX raster( 3943): took 0.819219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e305d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2f2c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/AMMetaDataParserService( 3943): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
,W/Settings( 4212): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1020): uID is 10168
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,D/SamsungIME( 1836): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/Settings( 4212): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,W/ResourcesManager( 4364): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4364): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4364): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10168
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
D/TaskPersister( 1020): removeObsoleteFile: deleting file=7_task.xml
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1020): unregisterListener ::   
,I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1020): [SO] changed settle time [0]
D/SensorService( 1020): [SO] setDelay [200000000]
D/SensorService( 1020): [SO] activate (ident=0xb81e6560, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/ActivityManager( 1020): Process com.sec.android.app.sns3 (pid 4155)(adj 0) has died(41,629)
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 4382): MountEmulatedStorage()
,E/Zygote  ( 4382): v2
I/libpersona( 4382): KNOX_SDCARD checking this for 10031
I/libpersona( 4382): KNOX_SDCARD not a persona
,I/SELinux ( 4382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4382): TimaSignature is unavailable
,D/ActivityThread( 4382): Added TimaKeyStore provider
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4382 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1020): Displayed Component not be shown by security: +463ms
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.687031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e373e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e37fc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 54390(3MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 22MB/34MB, paused 3.260ms total 438.095ms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,I/Icing   ( 2038): Internal init done: storage state 0
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.684323ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e2f2c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2bf28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3943): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 3404(133KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 801us total 42.827ms
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Volley  ( 4212): [628] DiskBasedCache.clear: Cache cleared.
E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3943): took 0.524011ms for 96*96 texture 0
,D/PackageManager( 1020): delete codoeFile: 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7c5c4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b763a0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4402): MountEmulatedStorage()
E/Zygote  ( 4402): v2
I/libpersona( 4402): KNOX_SDCARD checking this for 1000
I/libpersona( 4402): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3943): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/SELinux ( 4402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SELinux ( 4402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10168, packageName = com.example.hello
,D/Volley  ( 4212): [621] DiskBasedCache.clear: Cache cleared.
,I/AASA_removePackage( 1020): UID=10168 Target=com.example.hello
,E/SELinux ( 4402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/ActivityManager( 1020): Killing 3562:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 3578:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,D/PackageManager( 1020): result of delete: 1{488024969}
,D/TimaKeyStoreProvider( 4402): TimaSignature is unavailable
,D/ActivityThread( 4402): Added TimaKeyStore provider
,I/DBG_DM  ( 3222): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/WifiStateMachine( 1020): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/AndroidRuntime( 4231): Shutting down VM
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131165203
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ResourcesManager( 3943): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3943): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3943): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3943): getResourceTypeNamexml
,D/PackageManager( 1020): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/Ads     ( 4212): Skipping gmscore version check
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3943): took 3.831561ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3943): took 17.169376ms for 0*0 texture 0
,I/GFX raster( 3943): took 21.607188ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e1bcc0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7e1e6d8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3943): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/SensorService( 1020): [SO] currT = 43161072000, prevT = 42701111000, diff = 459961000, [-0.364 0.268 9.902]
,D/SensorService( 1020): [SO] -0.364 0.268 9.902
D/SensorService( 1020): [SO] [100 -> 255]
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3943): took 2.369375ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3943): took 5.178386ms for 0*0 texture 0
,I/GFX raster( 3943): took 8.549480ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb81ac468 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81ac510 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3943): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/SMD     (  290): DCD OFF
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3943): took 0.685677ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb81ac468 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7e440f0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3943): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{6e69e86 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:43224
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/Finsky  ( 4212): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4212): [1] Libraries$2.run: Finished loading 1 libraries.
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3943): took 1.473698ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb81ac468 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7e440f0 counterpartCT=4 counterpartW=80 counterparth=80
,I/Icing   ( 2038): Post-init done
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3943): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3943): took 0.755677ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e440f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb834e510 counterpartCT=4 counterpartW=80 counterparth=80
,W/art     ( 4231): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/AMMetaDataParserService( 3943): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/Finsky  ( 4212): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/        ( 3943): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3943): took 0.667031ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3943): Bitmap=0xb7e440f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb834f690 counterpartCT=4 counterpartW=80 counterparth=80
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3943): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4430): MountEmulatedStorage(),
I/libpersona( 4430): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4430): v2
I/libpersona( 4430): KNOX_SDCARD not a persona
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/SELinux ( 4430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4430): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4430 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/TimaKeyStoreProvider( 4430): TimaSignature is unavailable
,D/ActivityThread( 4430): Added TimaKeyStore provider
,V/AlarmManager( 1020): waitForAlarm result :4
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 ,
,D/Finsky  ( 4212): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DBG_POLICYDM( 4402): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4402): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4402): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/FileUtils( 2929): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 2929): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3943): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3943): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3943): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3943): getResourcePackageName:assistant
I/AMMetaDataParserService( 3943): Resource data:2131099648
,E/SQLiteDatabase( 2929): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2929): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 3943): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3943): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3943): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3943): getResourceTypeNamexml
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/Zygote  ( 4458): MountEmulatedStorage(),
E/Zygote  ( 4458): v2
I/libpersona( 4458): KNOX_SDCARD checking this for 10142
I/libpersona( 4458): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4458 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 4458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SELinux ( 4458): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 2929): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1020): Killing 3632:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
I/ActivityManager( 1020): Killing 3616:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #32
,E/SQLiteDatabase( 2929): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2929): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2929): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2929): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2929): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager( 1020): Killing 3648:com.fmm.ds/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4458): TimaSignature is unavailable
,D/ActivityThread( 4458): Added TimaKeyStore provider
,E/SQLiteLog( 2929): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/SensorService( 1020): [SO] -0.364 0.249 9.902
,D/UsbSettingsManager( 1020): clearDefaults: com.example.hello
I/AMMetaDataParserService( 3943): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/SQLiteDatabase( 2929): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2929): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3943): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,D/BadgeProvider( 4430): onCreate
D/BadgeProvider( 4430): DatabaseHelper
E/SQLiteLog( 2929): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2929): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2929): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2929): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3943): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3943): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQ,LiteOpenHelper.java:163)
E/SQLiteDatabase( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3943): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3943): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3943): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3943): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3943): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
