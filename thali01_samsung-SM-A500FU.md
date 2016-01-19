#### Test 564317025f150b2_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
--------- beginning of main
D/Mms/MmsApp( 5772): [end]    initCountryIso consume time = 33.434427
D/Mms/MmsConfig( 5772): [start]    MmsConfig.init() consume time = 0.14776
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/PhotosPlugin( 5855): Loading PhotosPlugin
E/Zygote  ( 5925): MountEmulatedStorage()
E/Zygote  ( 5925): v2
I/SELinux ( 5925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5925): KNOX_SDCARD checking this for 10012
I/libpersona( 5925): KNOX_SDCARD not a persona
I/SELinux ( 5925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5925): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5925 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/Mms/MmsConfig( 5772): before partial update
D/TimaKeyStoreProvider( 5905): TimaSignature is unavailable
D/ActivityThread( 5905): Added TimaKeyStore provider
D/lights  ( 1014): lcd : 0 +
D/DisplayPowerState( 1014): !@ ColorFade entry
D/DisplayPowerController( 1014): ColorFade: onAnimationEnd
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
D/Mms/MmsConfig( 5772): Load Resize quality : 80
D/lights  ( 1014): lcd : 0 -
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 0
I/ActivityManager( 1014): Killing 5281:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Display
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/EasySignUpManager_1.0.1( 5772): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 5772): isAuth is false
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1014): Got set_interactive hint
D/Mms/MmsConfig( 5772): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
I/DBG_POLICYDM( 5840): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/DisplayManagerService( 1014): !@display_state: ON -> OFF
I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1014): Display changed displayId=0
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb7553690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/PackageBroadcastService( 2035): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_ON
V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TP/MmsSmsProvider( 1456): query,matched:2117, calling pid = 5772
D/PersonaManagerService( 1014): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_ON called
D/TP/MmsSmsProvider( 1456): match 2117:Elapsed time : 4.606 ms
W/DisplayManagerService( 1014): Failed to notify process 5281 that displays changed, assuming it died.
W/DisplayManagerService( 1014): android.os.TransactionTooLargeException
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1014): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1014): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/TimaKeyStoreProvider( 5925): TimaSignature is unavailable
D/ActivityThread( 5925): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5840): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2035): Loading module APK com.google.android.play.games
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/EasySignUpManager_1.0.1( 5772): isAuth is false
D/EasySignUpManager_1.0.1( 5772): getServiceStatus : serviceId (1) is OFF
E/CscParser( 5772): mps_code.dat does not exist
E/CscParser( 5772): customer_path =/system/csc/customer.xml
E/CscParser( 5772): fileName + /system/csc/customer.xml
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/CscParser( 5772): mps_code.dat does not exist
E/CscParser( 5772): customer_path =/system/csc/customer.xml
E/CscParser( 5772): fileName + /system/csc/customer.xml
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/CscParser( 5772): getInstance fileName =/system/csc/customer.xml
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/Mms/MmsConfig( 5772):  enable multiwindow = true
E/SPPClientService( 5905): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5905): [PushClientApplication] Push log off : This is Ship build version
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5925): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5925): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/NfcService( 1439): call the applyRouting
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5261/cgroup.procs: No such file or directory
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SPPClientService( 5905): PushLog.txt file is not deleted.
D/SPPClientService( 5905): PushLog.txt file is not deleted.
D/SPPClientService( 5905): ============PushLog. stop!
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/Mms/MessageUtils( 5772): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5772): updateCountryIso : update country iso info 
W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5281/cgroup.procs: No such file or directory
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5954 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 5954): MountEmulatedStorage()
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
E/Zygote  ( 5954): v2
I/libpersona( 5954): KNOX_SDCARD checking this for 10038
I/libpersona( 5954): KNOX_SDCARD not a persona
I/SELinux ( 5954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5840): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/SELinux ( 5954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
E/SELinux ( 5954): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/Mms/MmsConfig( 5772): [end]    init() consume time = 275.012917
D/Mms/Contact( 5772): [start]    init() consume time = 1.087864
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/25/12:51:01
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/19/09:05:30
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
D/TimaKeyStoreProvider( 5954): TimaSignature is unavailable
D/ActivityThread( 5954): Added TimaKeyStore provider
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/MultiDex( 5925): VM with version 2.1.0 has multidex support
I/MultiDex( 5925): install
I/MultiDex( 5925): VM has multidex support, MultiDex support library is disabled.
I/DBG_POLICYDM( 5840): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
D/TP/MmsSmsProvider( 1456): query,matched:13, calling pid = 5772
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/TP/MmsSmsProvider( 1456): match 13:Elapsed time : 2.065 ms
D/accuweather( 1734): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1734): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
D/Mms/Contact( 5772): [end]    init consume time = 39.588073
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/Mms/DraftCache( 5772): [start]    rebuildCache consume time = 11.553021
I/SamsungIME( 1815): getNextShiftState() cursorCapsMode : 0
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
W/ResourcesManager( 5954): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5954): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 265ms
D/PowerManagerService( 1014): Excessive delay in !@display_state: OFF: 266ms
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable done
D/TP/MmsSmsProvider( 1456): query,matched:12, calling pid = 5772
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 278ms
I/PowerManagerService( 1014): [PWL] Off : 0s ago
D/TP/MmsSmsProvider( 1456): match 12:Elapsed time : 1.355 ms
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10012, pid=1845, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=6)
I/PowerManagerService( 1014): [PWL]   PowerManagerService.Broadcasts: ref count=1
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DraftCache( 5772): [end]    rebuildCache consume time = 27.808802
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/BatteryService( 1014): turn on LED for charging
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_int failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Mms/MethodReflector( 5772): getSubId is called
D/Mms/TelephonyUtils( 5772): getLongSubId from simSlot 0, return Value = -1
E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1014): fail to set sysfs 0
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
V/JNIHelp ( 5925): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Mms/MethodReflector( 5772): getTelephonyProperty is called
D/Mms/DownloadManager( 5772): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5772): auto download without roaming -> true
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5772): getSubId is called
D/Mms/MethodReflector( 5772): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5772): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5772): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5772): getTelephonyProperty is called
D/Mms/DownloadManager( 5772): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5772): auto download without roaming -> true
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5772): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5772): mAutoDownload ------> true
D/SSRM:n  ( 1014): SIOP:: AP = 320
D/PanelView( 1177): There is/are notification(s) 
D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService( 1014):  handler : SCREEN_OFF end 
D/SamsungIME( 1815): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/NotificationService( 1014): ACTION_SCREEN_OFF
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
I/BackgroundCompactionService( 1014): Schedule Type1 BGCompaction
D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1014): Bridge Server is not available
D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PersonaManagerService( 1014): ACTION_SCREEN_OFF onReceive
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_OFF called
V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
D/ComposerPerformance( 5772): 1453190731171 ms / [DONE] Composer constructor
E/CII     ( 5772): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5772): ReservationManager()
I/Mms/ReservationManager( 5772): resetAfterConnected()
D/NfcService( 1439): call the applyRouting
W/ActivityThread( 5925): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5925): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@366fd1e1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5925): Installed default security provider GmsCore_OpenSSL
D/Mms/Conversation( 5772): [start]    init() consume time = 111.955052
D/TP/MmsSmsProvider( 1456): query,matched:7, calling pid = 5772
D/TP/MmsSmsProvider( 1456): match 7:Elapsed time : 1.699 ms
I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true
D/TP/MmsSmsProvider( 1456): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1456): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1456): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1456): sUpgradeVersion = 0, db.getVersion() = 81
E/SMD     (  289): DCD OFF
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/TP/MmsSmsProvider( 1456): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1456): need read changed broadcast:false
W/art     ( 2035): Verification of void com.google.android.gms.games.service.PlayGamesAsyncService.<clinit>() took 105.925ms
D/Mms/ArtClassLoader( 5772): init [DONE] art
I/DBG_POLICYDM( 5840): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
I/ServiceManager(  326): Waiting for service AtCmdFwd...
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/Mms/Conversation( 5772): [end]    init consume time = 64.553646
D/accuweather( 1734): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/Mms/MessagingNotification( 5772): [start]    init() consume time = 3.207917
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
I/Mms/ReservationManager( 5772): getReservedSendMessageCount(): retMessageCount=0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/Mms/MessagingNotification( 5772): [end]    init consume time = 8.916771
D/accuweather( 1734): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/Mms/MmsApp( 5772): [end]    onCreate() consume time = 1.954114
D/ChimeraCfgMgr( 5925): Reading stored module config
I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/Mms/DownloadManager( 5772): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5772): roaming ------> false, mSimSlot = 0
D/Mms/SpamFilter( 5772): [start]    SpamFilter fill() begin consume time = 16.948594
D/Mms/MethodReflector( 5772): getSubId is called
D/Mms/TelephonyUtils( 5772): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5772): getTelephonyProperty is called
D/TP/MmsSmsProvider( 1456): query,matched:0, calling pid = 5772
V/TP/MmsSmsProvider( 1456): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1456): query,matched:400, calling pid = 5772
D/Mms/DownloadManager( 5772): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5772): auto download without roaming -> true
D/Mms/DownloadManager( 5772): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5772): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1456): match 0:Elapsed time : 0.835 ms
D/Mms/Synchronizer( 5772): [start]    doSync consume time = 10.72151
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/SpamFilter( 5772): [end]    SpamFilter fill() finished consume time = 12.818386
D/TP/MmsSmsProvider( 1456): update, matched:300, calling pid = 5772
V/TP/MmsSmsProvider( 1456): syncDBData start
V/TP/MmsSmsProvider( 1456): syncDBData sms end
V/TP/MmsSmsProvider( 1456): syncDBData mms end
V/TP/MmsSmsProvider( 1456): syncDBData end
D/Mms/Synchronizer( 5772): [end]    doSync consume time = 10.312135
D/ChimeraCfgMgr( 5925): Loading module com.google.android.gms.car from APK com.google.android.gms
D/Mms/FreeMessageStatusReceiver( 5772): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5986): MountEmulatedStorage()
E/Zygote  ( 5986): v2
I/libpersona( 5986): KNOX_SDCARD checking this for 10072
I/libpersona( 5986): KNOX_SDCARD not a persona
I/SELinux ( 5986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5986): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5986 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6001): MountEmulatedStorage()
I/libpersona( 6001): KNOX_SDCARD checking this for 10047
E/Zygote  ( 6001): v2
I/libpersona( 6001): KNOX_SDCARD not a persona
I/SELinux ( 6001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/NativeLibraryUtils( 5925): Install completed successfully. count=14 extracted=0
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6001 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 6001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6001): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/Mms/FreeMessageReceiverService( 5772): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageReceiverService( 5772): onHandleIntent: ACTION_PACKAGE_ADDED
E/WifiNative-wlan0( 1014): do suspend true
D/TimaKeyStoreProvider( 5986): TimaSignature is unavailable
D/ActivityThread( 5986): Added TimaKeyStore provider
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SSRM:n  ( 1014): SIOP:: AP = 330
D/TimaKeyStoreProvider( 6001): TimaSignature is unavailable
D/ActivityThread( 6001): Added TimaKeyStore provider
E/LibSecureUISvc( 1949): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
I/ActivityManager( 1014): Killing 5330:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ResourcesManager( 6001): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5840): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/BadgeProvider( 5986): onCreate
D/BadgeProvider( 5986): DatabaseHelper
I/System.out( 5574): Thread-958(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5574): Thread-958(ApacheHTTPLog):isShipBuild true
I/System.out( 5574): Thread-958(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5574): Thread-958(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2035): Module APK com.google.android.play.games already loaded
D/Mms/MessagingNotification( 5772): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1456): query,matched:26, calling pid = 5772
D/TP/SmsProvider( 1456): match 26:Elapsed time : 1.097 ms
D/TP/MmsSmsProvider( 1456): query,matched:6, calling pid = 5772
D/TP/MmsSmsProvider( 1456): match 6:Elapsed time : 1.550 ms
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6023): MountEmulatedStorage()
I/libpersona( 6023): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD not a persona
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6023 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 5368:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
W/ResourcesManager( 6023): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/AsyncTaskServiceImpl( 2035): Submit a task: k
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5330/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_5368/cgroup.procs: No such file or directory
D/CAR.SERVICE( 5925): Connecting to CarCallService...
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6023): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/k       ( 2035): Processing package: com.test.thalitest
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/MyFiles ( 6001): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/Mms/Omacp( 5772): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/art     ( 5925): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5925): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager( 1014): Killing 5385:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/TactileAssist( 1014): List of disabled apps :
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
E/installd(  285): system dir 0 : /system/app/
E/installd(  285): system dir 1 : /system/priv-app/
E/installd(  285): system dir 2 : /vendor/app/
E/installd(  285): system dir 3 : /oem/app/
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6023): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/GassUtils( 2035): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6046 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/k       ( 2035): Found info for package com.test.thalitest in db.
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 6046): MountEmulatedStorage()
E/Zygote  ( 6046): v2
I/libpersona( 6046): KNOX_SDCARD checking this for 10053
I/libpersona( 6046): KNOX_SDCARD not a persona
I/SELinux ( 6046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6046): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/CAR.SERVICE( 5925): com.google.android.projection.gearhead isn't installed.
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6046): TimaSignature is unavailable
D/ActivityThread( 6046): Added TimaKeyStore provider
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_5385/cgroup.procs: No such file or directory
W/ResourcesManager( 6046): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
I/SL_DEBUG( 5954): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5954): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 6046): onReceive() it will make start service
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/Compatibility( 6046): onHandleIntent()
D/Compatibility( 6046): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/CAR.TEL.Service( 5925): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5925): Creating a new PhoneAdapter instance
D/CAR.SERVICE( 5925): Package validated; name: com.android.vending
I/UpdateIcingCorporaServi( 5443): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/CAR.TEL.PhoneAdapter( 5925): setListener: com.google.android.gms.car.dn@14b11624
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5925): Returning an existing PhoneAdapter instance.
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/CAR.TEL.Service( 5925): Starting CarCallService with initial phone null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/Compatibility( 6046): found: 2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/Finsky  ( 5574): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6046): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6046): skipping ResolveInfo{14d22fa3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6046): considering ResolveInfo{231422a0 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6046): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Compatibility( 6046): enabling receiver ResolveInfo{39dfae59 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6046): enabling receiver ResolveInfo{3d328a1e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6046): enabling receiver ResolveInfo{25ce22ff com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6046): enabling receiver ResolveInfo{37a8c8cc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6046): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 5443): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
I/art     ( 1014): Explicit concurrent mark sweep GC freed 253291(17MB) AllocSpace objects, 14(5MB) LOS objects, 33% free, 27MB/41MB, paused 3.173ms total 255.247ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
I/BatteryStatsDumper( 1014): Writing to database completed
D/AndroidRuntime( 6039): 
D/AndroidRuntime( 6039): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6039): CheckJNI is OFF
D/AndroidRuntime( 6039): readGMSProperty: start
D/AndroidRuntime( 6039): readGMSProperty: already setted!!
D/AndroidRuntime( 6039): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6039): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6039): readGMSProperty: end
D/AndroidRuntime( 6039): addProductProperty: start
I/ServiceManager(  326): Waiting for service AtCmdFwd...
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PeopleDatabaseHelper( 2035): cleanUpNonGplusAccounts done.
I/ActivityManager( 1014): Killing 5305:com.google.android.talk/u0a104 (adj 15): empty #31
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5954): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2035): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5954): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6091): MountEmulatedStorage()
E/Zygote  ( 6091): v2
I/libpersona( 6091): KNOX_SDCARD checking this for 10041
I/libpersona( 6091): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6091 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6091): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  310): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 22.389ms
D/TimaKeyStoreProvider( 6091): TimaSignature is unavailable
D/ActivityThread( 6091): Added TimaKeyStore provider
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 17.081ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 17.493ms
W/GAV2    ( 5855): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_5305/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Killing 5506:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 6091): [SSP] onCreated
I/SA      ( 6091): [TPM] There is no property file
I/SA      ( 6091): [SCU] isHaveSA() - false
I/SA      ( 6091): [TPM] getModelProperty : null
I/SA      ( 6091): [TPM] getCSCProperty : null
I/SA      ( 6091): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6091): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6091): [DM] TFT FEATURE: false
I/SA      ( 6091): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6091): [DM] init START
I/SA      ( 6091): [DM] This device is not a Vodafone
W/ResourceType( 6091): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6091): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6091): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6091): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6091): [SCU] isHaveSA() - false
I/SA      ( 6091): support phone number id : false
I/SA      ( 6091): [DM] Supports Ref Jpn : true
I/SA      ( 6091): [DM] init END
I/SA      ( 6091): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6091): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5506/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Killing 5537:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
E/AffinityControl( 6039): AffinityControl: registerfunction enter
W/art     ( 5855): Suspending all threads took: 7.567ms
D/AndroidRuntime( 6039): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5537/cgroup.procs: No such file or directory
W/ActivityManager( 1014): mDVFSHelper.acquire()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/Zygote  ( 6122): MountEmulatedStorage()
E/Zygote  ( 6122): v2
I/libpersona( 6122): KNOX_SDCARD checking this for 10155
I/libpersona( 6122): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6122 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
I/SELinux ( 6122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/InputDispatcher( 1014): Focus left window: 3143
D/AndroidRuntime( 6039): Shutting down VM
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/SELinux ( 6122): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
E/Zygote  ( 6139): MountEmulatedStorage()
E/Zygote  ( 6139): v2
I/libpersona( 6139): KNOX_SDCARD checking this for 10100
I/libpersona( 6139): KNOX_SDCARD not a persona
I/SELinux ( 6139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6139 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 6122): TimaSignature is unavailable
D/ActivityThread( 6122): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 5553:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/SELinux ( 6139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/wpa_supplicant( 1993): nl80211: Received scan results (5 BSSes)
V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiP2pService( 1014): InactiveState{ what=147461 }
D/WifiP2pService( 1014): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1014): DefaultState{ what=147461 }
W/GAV2    ( 5855): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityManager( 1014): Display changed displayId=0
E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
W/DisplayManagerService( 1014): Failed to notify process 5553 that displays changed, assuming it died.
W/DisplayManagerService( 1014): android.os.TransactionTooLargeException
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1014): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1014): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1014): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/TimaKeyStoreProvider( 6139): TimaSignature is unavailable
D/ActivityThread( 6139): Added TimaKeyStore provider
D/PersonaManager( 1014): isKioskContainerExistOnDevice
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (-2/9)
V/ActivityThread( 3143): updateVisibility : ActivityRecord{2f27aa10 token=android.os.BinderProxy@220073a7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/PackageIntentReceiver( 6139): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6139): Not GearManger package! 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_5553/cgroup.procs: No such file or directory
W/AccountFeatureHelper( 5855): Write apps_features disabled false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6162): MountEmulatedStorage()
E/Zygote  ( 6162): v2
I/libpersona( 6162): KNOX_SDCARD checking this for 1000
I/SELinux ( 6162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6162): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6162): TimaSignature is unavailable
D/ActivityThread( 6162): Added TimaKeyStore provider
W/art     ( 6039): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/WebViewFactory( 6122): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 6122): Time to load native libraries: 2 ms (timestamps 1371-1373)
I/LibraryLoader( 6122): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 6178): MountEmulatedStorage()
E/Zygote  ( 6178): v2,
I/libpersona( 6178): KNOX_SDCARD checking this for 1000
I/SELinux ( 6178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6178): KNOX_SDCARD not a persona
I/SELinux ( 6178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5173:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31,
,E/SELinux ( 6178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 6122): Binding Chromium to main looper Looper (main, tid 1) {39dfae59}
I/qtaguid ( 5574): Untagging socket 44
I/LibraryLoader( 6122): Expected native library version number "",actual native library version number ""
I/chromium( 6122): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/qtaguid ( 5574): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5574): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5574): untagSocket(44) failed with errno -22
I/System.out( 5574): Thread-958 calls detatch()
,W/GAV2    ( 5855): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1014): Killing 5676:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6178): TimaSignature is unavailable
D/ActivityThread( 6178): Added TimaKeyStore provider
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/BrowserStartupController( 6122): Initializing chromium process, singleProcess=true
,W/art     ( 6122): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6122): ApplicationContext is null in ApplicationStatus
,W/chromium( 6122): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6122): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 6122): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6122): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6122): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6122): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6122): Local Branch: 
I/Adreno-EGL( 6122): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6122): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6122):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_5173/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_5676/cgroup.procs: No such file or directory
,E/Zygote  ( 6199): MountEmulatedStorage(),
E/Zygote  ( 6199): v2
I/libpersona( 6199): KNOX_SDCARD checking this for 10120
I/SELinux ( 6199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6199): KNOX_SDCARD not a persona
,I/SELinux ( 6199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6199): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6199 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4519:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/AcmsPackageEventListener( 6178): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6178): Enter Oncreate
,D/AcmsServiceMonitor( 6178): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6178): creating AcmsCore
,D/TimaKeyStoreProvider( 6199): TimaSignature is unavailable
D/ActivityThread( 6199): Added TimaKeyStore provider
D/AcmsCore( 6178): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6178): AcmsCore
,D/AcmsCore( 6178): init
D/AcmsCore( 6178): Looper handler is not null
D/AcmsCore( 6178): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6178): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6178): Incrementing - Counter value: 1
D/AcmsCore( 6178): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6178): onStartCommand
D/AcmsService( 6178): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6178): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6178): Incrementing - Counter value: 2
D/AcmsService( 6178): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6178): AcmsCertificateMngr
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6178): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6178): AcmsRevocationMngr
,W/ResourcesManager( 6199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ChimeraCfgMgr( 2035): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2035): Module APK com.google.android.play.games already loaded
,D/AcmsService( 6178): Inside handle Intent
,D/AcmsService( 6178): App added - package name: com.test.thalitest
,D/AcmsCore( 6178): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6178): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6178): Incrementing - Counter value: 3
D/AcmsCore( 6178): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6178): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6178): Decrementing - Counter value: 2
,W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4519/cgroup.procs: No such file or directory
,I/Icing   ( 2035): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Mms/MmsApp( 5772):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5772): [start]    fillCache consume time = 1949.987447
,D/Mms/ComposeMessageFragment( 5772): fillCache, easy = false
,W/chromium( 6122): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{3dbd6c65 u0 com.test.thalitest/.MainActivity t8}
,W/art     ( 6122): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6122): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6122): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6122): *FMB* installDecor flags : 8456448
,D/AbsListView( 5772): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 5772): [end]    fillCache consume time = 121.257084
,D/SystemWebViewEngine( 6122): CordovaWebView is running on device made by: samsung
,W/art     ( 6122): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6122): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6122): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,V/ActivityThread( 6122): updateVisibility : ActivityRecord{2799af85 token=android.os.BinderProxy@28bbc9ef {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6122): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6122): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,D/InputDispatcher( 1014): Focus entered window: 6122
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6122): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6122): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6122): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6122): Enabling debug mode 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/Icing   ( 2035): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1014): Displayed Component not be shown by security: +803ms (total +904ms)
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{3dbd6c65 u0 com.test.thalitest/.MainActivity t8} time:82004
W/ActivityManager( 1014): mDVFSHelper.release()
,I/SamsungIME( 1815): getCurrentCandidateView
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6122): showStatusIcon on inactive InputConnection
,I/Timeline( 6122): Timeline: Activity_idle id: android.os.BinderProxy@28bbc9ef time:82020
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/BubbleViewCache( 5772): fillCache bubble = 1
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/BindingManager( 6122): Cannot call determinedVisibility() - never saw a connection for the pid: 6122
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1295): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1295): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1295): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1295): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453212240000
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453190733743
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SamsungIME( 1815): Dismiss ExpandCandiate
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1295): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1295): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1845): callingUid 10012, callindPid: 1845
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1845): [258] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 6122): Set native->JS mode to OnlineEventsBridgeMode
,D/AuthorizationBluetoothService( 1845): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2035): Restart initialization of location
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1734): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,W/GCoreFlp( 1845): No location to return for getLastLocation()
,W/FusedLocationProvider( 1845): location=null
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1734): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/jxcore_app_log( 6122): JniHelper::setJavaVM(0xb841d450), pthread_self() = -1198070856
,D/JX-Cordova( 6122): jxcore cordova android initializing
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,I/io.jxcore.node.ConnectionHelper( 6122): Build version SDK_INT: 21
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,I/SamsungIME( 1815): KeybaordView init() : load resources
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/ActivityManager( 1014): Killing 4875:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/accuweather( 1734): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1734): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SamsungIME( 1815): getCurrentKeyboard
,I/SamsungIME( 1815): getTextKeyboard
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_4875/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 5840): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5574): Thread-957(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5574): Thread-957(ApacheHTTPLog):isShipBuild true
I/System.out( 5574): Thread-957(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5574): Thread-957(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/qtaguid ( 5574): Untagging socket 44
,I/qtaguid ( 5574): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5574): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5574): untagSocket(44) failed with errno -22
,I/System.out( 5574): Thread-957 calls detatch()
,W/ResourcesManager( 5574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5574): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5574): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1845): client connected with version: 8296000
,D/Finsky  ( 5574): [979] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5574): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5574): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,W/jxcore-log( 6122): Initializing JXcore engine
W/jxcore-log( 6122): JXcore engine is ready
,V/AlarmManager( 1014): waitForAlarm result :4
,W/jxcore-log( 6122): Starting JXcore engine
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,I/System.out( 5574): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5574): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5574): (HTTPLog)-Static: isShipBuild true
I/System.out( 5574): (HTTPLog)-Thread-968-424315060: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5574): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10028
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10028
,E/audit   ( 1893): type=1400 msg=audit(1453190735.403:205): avc:  denied  { ioctl } for  pid=6122 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1893):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1893): type=1300 msg=audit(1453190735.403:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=befcbd58 items=0 ppid=310 ppcomm=main pid=6122 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1893): type=1320 msg=audit(1453190735.403:205): 
,I/System.out( 5574): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/jxcore-log( 6122): Platform android
W/jxcore-log( 6122): 
W/jxcore-log( 6122): Process ARCH arm
W/jxcore-log( 6122): 
,I/ActivityManager( 1014): Killing 5191:com.google.android.gm/u0a101 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5346:com.android.calendar/u0a135 (adj 15): empty #32
,W/art     ( 5574): Suspending all threads took: 12.331ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_5191/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_5346/cgroup.procs: No such file or directory
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,I/jxcore-log( 6122): JXcore Cordova bridge is ready!
I/jxcore-log( 6122): 
,W/jxcore-log( 6122): JXcore engine is started
,I/Choreographer( 6122): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6122): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6122): Toggling radios to true
I/jxcore-log( 6122): 
,D/BluetoothAdapter( 6122): enable()
,D/BluetoothAdapter( 6122): enable(): BT is already enabled..!
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=6122, uid=10155
W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=6122, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6122, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1014): name = wifi_on
,I/WifiService( 1014): disconnect: pid=6122, uid=10155
,I/jxcore-log( 6122): Radios toggled
I/jxcore-log( 6122): 
I/wpa_supplicant( 1993): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6122): My device name is: samsung-SM-A500FU
I/jxcore-log( 6122): 
,I/wpa_supplicant( 1993): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1993): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1993): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1993): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1993): Cmd 35605 not handled
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine( 1014): WifiStateMachine: Leaving Connected state
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1993): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1993): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1993): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1993): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1993): First Scan Start
,I/wpa_supplicant( 1993): Scan requested (ret=0) - scan timeout 30 seconds
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering( 1014): InitialState.processMessage what=4
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
,E/Tethering( 1014): No numeric data
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false,
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
V/NativeCrypto( 1845): Read error: ssl=0xb8940e88: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit,
V/NetworkStats( 1014): performPollLocked() took 17ms
,E/ConnectivityService( 1014): updateNetworkInfo(),
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit,
E/WifiStateMachine( 1014): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1993): wlan0: Setting scan request: 0 sec 0 usec
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1014): do suspend true,
D/WifiP2pService( 1014): InactiveState{ what=143375 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1014): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
,D/ConnectivityService( 1014): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 2035): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 1014): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1014): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,D/WifiNetworkAgent( 1014): NetworkAgent: NetworkAgent channel lost
,V/NetworkStats( 1014): updateIfacesLocked()
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,V/NetworkStats( 1014): performPollLocked() took 11ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 46877(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.786ms total 218.085ms
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1014): nai.networkMonitor.doQuit()
E/ConnectivityService( 1014): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): doQuit - quitNow()
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,V/NativeCrypto( 1845): SSL shutdown failed: ssl=0xb8940e88: I/O error during system call, Broken pipe
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,I/Hs20UtilService( 3484): Starting #8
,I/Hs20UtilService( 3484): Message received 5007
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1326): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1326): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1326): MountReceiver.mPrefHandler - 7002,
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3484): Starting #9
,I/Hs20UtilService( 3484): Message received 5007
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1326): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1326): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1326): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3,
,I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6274 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,E/Zygote  ( 6274): MountEmulatedStorage(),
I/libpersona( 6274): KNOX_SDCARD checking this for 10104
E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD not a persona
,I/SELinux ( 6274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TimaKeyStoreProvider( 6274): TimaSignature is unavailable
,D/ActivityThread( 6274): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,W/ResourcesManager( 6274): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 5925): mConnectedToCar = false, abort
,E/ActivityThread( 5925): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@133a218c that was originally bound here
E/ActivityThread( 5925): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@133a218c that was originally bound here
E/ActivityThread( 5925): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5925): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5925): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5925): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5925): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5925): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5925): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5925): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5925): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5925): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5925): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5925): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5925): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5925): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5925): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5925): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5925): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5925): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5925): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5925): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5925): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5925): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5925): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2dac6eb7 that was originally bound here
E/ActivityThread( 5925): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2dac6eb7 that was originally bound here
E/ActivityThread( 5925): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5925): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5925): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5925): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5925): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5925): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5925): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5925): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5925): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5925): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5925): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5925): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5925): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5925): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5925): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5925): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5925): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5925): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5925): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5925): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5925): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@28f3f79e
,I/Babel   ( 6274): MmsConfig: mnc/mcc: 0/0,
I/Babel   ( 6274): MmsConfig.loadMmsSettings
I/Babel   ( 6274): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6274): MmsConfig.loadFromDatabase
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ApplicationPolicy( 1014): updateDataUsageMap
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3143): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3143): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/SMD     (  289): DCD OFF
,E/Babel   ( 6274): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6274): MmsConfig.loadFromResources
,E/Babel   ( 6274): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6274): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6274): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6274): App launched.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
,I/wpa_supplicant( 1993): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1993): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1993): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1993): Trying to associate with  'G700'
I/wpa_supplicant( 1993): Re-associate with C0.AA.48
I/wpa_supplicant( 1993): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700'
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for charging
,W/VideoCapabilities( 6274): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6274): Unsupported mime audio/evrc
,W/AudioCapabilities( 6274): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6274): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6274): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6274): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6274): Unsupported mime audio/x-ima
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,W/AudioCapabilities( 6274): Unsupported mime audio/qcelp
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/wpa_supplicant( 1993): Cmd 35605 not handled
I/wpa_supplicant( 1993): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1993): Associated with C0.AA.48
,I/wpa_supplicant( 1993): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1993): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 1993): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1993): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1993): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1993): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1993): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1993): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1993): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1993): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,W/AudioCapabilities( 6274): Unsupported mime audio/evrc,
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/SecContentProvider2( 1014): mCursor = null
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/MotionRecognitionService( 1014): Plugged
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,W/VideoCapabilities( 6274): Unsupported mime video/wvc1
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1014): interfaceStatusChanged wlan0, true
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,W/VideoCapabilities( 6274): Unsupported mime video/x-ms-wmv
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/Tethering( 1014): No numeric data
,D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,V/NetworkStats( 1014): performPollLocked() took 3ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6274): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/VideoCapabilities( 6274): Unsupported mime video/wvc1,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6274): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6274): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6274): Unsupported mime video/x-ms-wmv8
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/VideoCapabilities( 6274): Unsupported mime video/mp43
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/CommandListener(  279): Setting iface cfg
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/WifiStateMachine( 1014): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6274): Unsupported mime video/sorenson
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/WifiNative-wlan0( 1014): do suspend false
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): noConnectivity : true
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,W/VideoCapabilities( 6274): Unsupported mime video/mp4v-esdp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6318): MountEmulatedStorage()
,E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10111,
I/libpersona( 6318): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6318 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 6274): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6331 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6331): MountEmulatedStorage()
E/Zygote  ( 6331): v2
I/libpersona( 6331): KNOX_SDCARD checking this for 10009
I/libpersona( 6331): KNOX_SDCARD not a persona
,I/SELinux ( 6331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/accuweather( 1734): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
,I/SELinux ( 6331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6331): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 6318): Added TimaKeyStore provider
,E/Zygote  ( 6347): MountEmulatedStorage(),
E/Zygote  ( 6347): v2
I/libpersona( 6347): KNOX_SDCARD checking this for 10145
,I/libpersona( 6347): KNOX_SDCARD not a persona
,I/SELinux ( 6347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6347 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/SELinux ( 6347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6347): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6331): TimaSignature is unavailable
,D/ActivityThread( 6331): Added TimaKeyStore provider
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1734): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1734): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1734): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6347): TimaSignature is unavailable
,D/ActivityThread( 6347): Added TimaKeyStore provider
,D/accuweather( 1734): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1734): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6347): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6363 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6363): MountEmulatedStorage()
,E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD checking this for 10081
I/libpersona( 6363): KNOX_SDCARD not a persona
,I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 6372): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6372): version 5.5.6 starting
E/dhcpcd  ( 6372): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6372): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6372): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6372): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6372): bssid match
I/dhcpcd  ( 6372): wlan0: rebinding lease of 192.168.1.129
,D/TimaKeyStoreProvider( 6363): TimaSignature is unavailable
,D/ActivityThread( 6363): Added TimaKeyStore provider
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/ActivityManager( 1014): Killing 5423:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:05:38 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive().END.
,I/dhcpcd  ( 6372): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onCreate()
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/KLMS-2.5.183: ( 3508): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/Zygote  ( 6391): MountEmulatedStorage()
,I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6391 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6391): v2
I/libpersona( 6391): KNOX_SDCARD checking this for 10034
I/SELinux ( 6391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6391): KNOX_SDCARD not a persona
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 6391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/SELinux ( 6391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3508): StateImplV2(): networkChangeListener().END
,I/art     (  310): Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 29.050ms
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6391): TimaSignature is unavailable
,D/ActivityThread( 6391): Added TimaKeyStore provider
,I/dhcpcd  ( 6372): wlan0: leased 192.168.1.129 for 86400 seconds
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 19.035ms,
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.115ms total 19.103ms
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5423/cgroup.procs: No such file or directory
,I/MusicStore( 6318): Database version: 108
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId,
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6434 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 5039:com.sec.android.gallery3d/u0a44 (adj 15): empty #31,
,E/Zygote  ( 6434): MountEmulatedStorage()
E/Zygote  ( 6434): v2
I/libpersona( 6434): KNOX_SDCARD checking this for 10113
I/libpersona( 6434): KNOX_SDCARD not a persona
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
I/SELinux ( 6434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6434): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiNative-wlan0( 1014): do suspend true
,D/TimaKeyStoreProvider( 6434): TimaSignature is unavailable
,D/ActivityThread( 6434): Added TimaKeyStore provider
,I/SO_AGENT( 6391): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,W/art     ( 6347): Verification of void com.android.email.activity.MessageListItemOuterContainer.<init>(android.content.Context) took 149.041ms
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1014): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
D/ConnectivityService( 1014): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1014): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1014): LTETest block dns file not exists
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1014): updateNetworkInfo()
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1014):    accepting network in place of null
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EnterpriseController(  279): uids 1000
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1456): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
,I/WifiTrafficPoller( 1014): current booster mode : FullMode
,I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2035): CM callback handler got msg 524290
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,I/DBG_POLICYDM( 5840): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,V/NetworkStats( 1014): updateIfacesLocked()
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked() took 16ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
W/ActivityManager( 1014): Failed to clear dns cache for: com.sec.android.gallery3d
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/BadgeProvider( 5986): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_5039/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5840): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/BadgeProvider( 5986): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5986): sendNotify, [notify] : null
D/BadgeProvider( 5986): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5986): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5986): update, [UpdateCount] : 1
,D/Launcher.Model( 1480): reloadBadges entered.
,E/DBG_POLICYDM( 5840): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered,
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/SPPClientService( 5905): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,W/art     ( 6347): Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 133.364ms
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SA      ( 6091): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6091): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6091): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/Zygote  ( 6461): MountEmulatedStorage()
E/Zygote  ( 6461): v2
,I/libpersona( 6461): KNOX_SDCARD checking this for 1000,
I/SA      ( 6091): [SLFUCHKMGR] constructor called
I/libpersona( 6461): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6461 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SELinux ( 6461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 5905): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6461): TimaSignature is unavailable
,I/SA      ( 6091): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6091): [OR] == isSIMCardReady false ==
,I/SA      ( 6091): [SCU] == networkStateCheck == true
,D/ActivityThread( 6461): Added TimaKeyStore provider
,I/SA      ( 6091): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6091): isChinaCountryCode : false
I/SA      ( 6091): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6091): [OR] == networkStateCheck true ==
,I/SA      ( 6091): [OR] GetMyCountryZoneTask
,I/SA      ( 6091): [OR] onReceive END
,W/ResourcesManager( 6318): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6318): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SA      ( 6091): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 1014): Killing 4782:com.samsung.android.sm/1000 (adj 15): empty #31
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
I/SA      ( 6091): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6091): [SSP] query invoked
D/SecContentProvider2( 1014): mCursor = null
,D/SecurityLogAgent( 6461): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6461): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6461): StateMachine : Current State = 1
,I/SA      ( 6091): [TPMU] GetMccFromDB : null
,D/SecurityLogAgent( 6461): StateMachine : Changed Current State = 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6091): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6091): [TPM] isNoProxy(default) : true
,V/JNIHelp ( 6318): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Zygote  ( 6484): MountEmulatedStorage(),
E/Zygote  ( 6484): v2
I/libpersona( 6484): KNOX_SDCARD checking this for 10159,
I/libpersona( 6484): KNOX_SDCARD not a persona
,I/SELinux ( 6484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6484): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6484 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5462:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4782/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6484): TimaSignature is unavailable
,D/ActivityThread( 6484): Added TimaKeyStore provider
,E/File    ( 6091): fail readDirectory() errno=2
,I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WaitQueueForNetworkActivate( 5883): notifyNetworkActivated
,W/ActivityThread( 6318): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6318): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e7d6f60: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6318): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6318): GMSCore installation verified
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 6318): Config Database version: 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 08:05:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453190738883], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453190738858]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2035): CM callback handler got msg 524290
,W/ContextImpl( 5883): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_5462/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3143): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1014): Killing 5759:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6318): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6318): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6318): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5759/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/MediaRouter( 6318): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6318): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6318): type=WIFI subType= reason=null isConnected=true
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6434): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 6434): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1014): Killing 5155:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 6318): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6515): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6515 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6515): v2
I/libpersona( 6515): KNOX_SDCARD checking this for 10002
,I/libpersona( 6515): KNOX_SDCARD not a persona
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,I/SELinux ( 6515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,W/ContextImpl( 6434): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/SELinux ( 6515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5883): AutoUpdateManager:IDLE:execute
,D/TimaKeyStoreProvider( 6515): TimaSignature is unavailable
,D/InitializeManagerStateMachine( 5883): execute::IDLE:EXECUTE
D/ActivityThread( 6515): Added TimaKeyStore provider
D/InitializeManagerStateMachine( 5883): exit::IDLE
D/InitializeManagerStateMachine( 5883): entry::NETWORK_CHECK
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6434): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/InitializeManagerStateMachine( 5883): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5883): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5883): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5883): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5883): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5883): entry::SUCCESS
D/hcjo    ( 5883): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5883): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5883): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5883): exit::SUCCESS
D/InitializeManagerStateMachine( 5883): entry::IDLE
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5155/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6318): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6318): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6318): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1014): Killing 5810:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5487:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ConnectivityService( 1014): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6547): MountEmulatedStorage()
E/Zygote  ( 6547): v2
I/libpersona( 6547): KNOX_SDCARD checking this for 1000
I/libpersona( 6547): KNOX_SDCARD not a persona
,I/SELinux ( 6547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6547): TimaSignature is unavailable
,D/ActivityThread( 6547): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6434): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6434): Time to load native libraries: 2 ms (timestamps 7909-7911)
,I/LibraryLoader( 6434): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6434): Binding Chromium to main looper Looper (main, tid 1) {2dac6eb7}
,I/LibraryLoader( 6434): Expected native library version number "",actual native library version number ""
,I/chromium( 6434): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/DIAGMON_AGENT( 6547): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/BrowserStartupController( 6434): Initializing chromium process, singleProcess=true
,W/art     ( 6434): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6434): ApplicationContext is null in ApplicationStatus
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5810/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_5487/cgroup.procs: No such file or directory
,W/chromium( 6434): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6434): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6434): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6434): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6434): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6434): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6434): Local Branch: 
I/Adreno-EGL( 6434): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6434): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6434):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 6547): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6547): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6547): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/NSApplication( 6434): Starting up...
,W/AudioManagerAndroid( 6434): Requires BLUETOOTH permission
,I/ActivityManager( 1014): Killing 5825:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5522:com.sec.knox.bridge/1000 (adj 15): empty #32
,D/AcmsKeyStoreHelper( 6178):  getKeyStoreForApplication Enter
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5825/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5522/cgroup.procs: No such file or directory
,I/AcmsKeyStoreHelper( 6178): Key Store exist
,I/AcmsKeyStoreHelper( 6178): Hence loading the keystore file
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6581): MountEmulatedStorage(),
E/Zygote  ( 6581): v2
I/libpersona( 6581): KNOX_SDCARD checking this for 10125
I/libpersona( 6581): KNOX_SDCARD not a persona,
I/SELinux ( 6581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6581): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6581 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5772:com.android.mms/u0a46 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 6581): TimaSignature is unavailable
,D/ActivityThread( 6581): Added TimaKeyStore provider
,W/ResourcesManager( 6581): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6581): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6581): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6581): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 6581): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/AcmsKeyStoreHelper( 6178):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6178): getKeyStoreForApplication success 
D/AcmsCore( 6178): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6178): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6178): Decrementing - Counter value: 1
D/AcmsCore( 6178): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 6178): This is NOT a valid MirrorLink app
D/AcmsCore( 6178): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6178): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6178): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6178): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6178): getSvcCounter - Counter value: 0
D/AcmsService( 6178): Enter onDestroy
I/AcmsService( 6178): cleanUp(): inside service clean up
D/AcmsCore( 6178): AcmsCore: inside DeInit
D/AcmsCore( 6178): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6178): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6178): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6178): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6178): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6178): getSvcCounter - Counter value: 0
D/AcmsService( 6178): killing acms process
I/Process ( 6178): Sending signal. PID: 6178 SIG: 9
,D/CountryDetector( 1014): No listener is left
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 52980(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.744ms total 161.106ms
,I/ActivityManager( 1014): Process ACMS.Process (pid 6178)(adj 0) has died(46,1104)
,I/QuickConnect( 6581): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 6001:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5772/cgroup.procs: No such file or directory
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1326): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3484): Starting #10
,I/Hs20UtilService( 3484): Message received 5007
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1326): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3484): Starting #11
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1326): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3484): Message received 5007
,I/SA      ( 6091): [RC New] Execute method=[GET] start
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3484): Starting #12
,I/Hs20UtilService( 3484): Message received 5007
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1326): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1326): DMSUtil.isNetworkConnected - P2P: IDLE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/NearbySettings( 1326): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1326): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,I/SA      ( 6091): [RC New] Security=[true]
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,I/System.out( 6091): Thread-1055(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/System.out( 6091): Thread-1055(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6091): Thread-1055(ApacheHTTPLog):isShipBuild true
I/System.out( 6091): Thread-1055(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6091): Thread-1055(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/EnterpriseController(  279): uids 10041
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10041
,I/Hs20UtilService( 3484): Starting #13
,I/Hs20UtilService( 3484): Message received 5007
,D/NearbySettings( 1326): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1326): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1014): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1014): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6318): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_6001/cgroup.procs: No such file or directory
,D/accuweather( 1734): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,E/SMD     (  289): DCD OFF
D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,I/FOTA_Client( 6331): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,D/accuweather( 1734): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 6461): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6461): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6461): StateMachine : Current State = 1
,D/SecurityLogAgent( 6461): StateMachine : Changed Current State = 1
,I/FOTA_Client( 6331): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6331): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 6331): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/accuweather( 1734): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1734): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6547): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6547): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5883): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5883): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5883): exit::IDLE
,D/InitializeManagerStateMachine( 5883): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5883): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5883): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5883): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5883): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5883): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5883): entry::SUCCESS
D/hcjo    ( 5883): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5883): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5883): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5883): exit::SUCCESS
D/InitializeManagerStateMachine( 5883): entry::IDLE
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:05:40 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3508): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3508): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3508): NetworkChangeOperations(): uploadRequestLog().START 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 6581): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6581): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6581): PeriphStartReceiver.onReceive - no need to start
,I/KLMS-2.5.183: ( 3508): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3508): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,E/SPPClientService( 5905): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6091): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6091): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6091): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6091): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6091): [OR] == isSIMCardReady false ==
,I/SA      ( 6091): [SCU] == networkStateCheck == true
,I/SA      ( 6091): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6091): isChinaCountryCode : false
,I/SA      ( 6091): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6091): [OR] == networkStateCheck true ==
,I/SA      ( 6091): [OR] GetMyCountryZoneTask
I/SA      ( 6091): [OR] onReceive END
,I/SA      ( 6091): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6091): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6091): [SSP] query invoked
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1014): mCursor = null
,I/SA      ( 6091): [TPMU] GetMccFromDB : null
I/SA      ( 6091): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6091): [TPM] isNoProxy(default) : true
I/SA      ( 6091): [RC New] Execute method=[GET] start
,I/splitIntent( 1014): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/SA      ( 6091): [RC New] Security=[true]
,I/System.out( 6091): Thread-1057(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6091): Thread-1057(ApacheHTTPLog):isShipBuild true
I/System.out( 6091): Thread-1057(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6091): Thread-1057(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6091): [RC New] [v2liruge] api execute + 657
,I/SA      ( 6091): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6091): AsyncTask #1 calls detatch()
,I/SA      ( 6091): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6091): [OCP] update openData : PL
,I/SA      ( 6091): [TPMU] getNetworkMcc : 
,I/SA      ( 6091): [SCU] saveMccToPreferece Start
,I/SA      ( 6091): [SCU] RegionMCC : 260
I/SA      ( 6091): [SSP] query invoked
,I/SA      ( 6091): [TPMU] GetMccFromDB : null
,I/SA      ( 6091): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6091): [SCU] saveMccToPreferece End
,I/SA      ( 6091): [RC New] executeRequest [v2liruge] end. 723
I/SA      ( 6091): [RC New] Execute end
I/SA      ( 6091): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6091): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6122): 
,I/SA      ( 6091): [RC New] [v2liruge] api execute + 580
,I/SA      ( 6091): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6091): AsyncTask #2 calls detatch()
,I/SA      ( 6091): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6091): [OCP] update openData : PL
,I/SA      ( 6091): [TPMU] getNetworkMcc : 
,I/SA      ( 6091): [SCU] saveMccToPreferece Start
,I/SA      ( 6091): [SCU] RegionMCC : 260
I/SA      ( 6091): [SSP] query invoked
,I/SA      ( 6091): [TPMU] GetMccFromDB : null
,I/SA      ( 6091): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6091): [SCU] saveMccToPreferece End
,I/SA      ( 6091): [RC New] executeRequest [v2liruge] end. 622
I/SA      ( 6091): [RC New] Execute end
,I/SA      ( 6091): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6091): [OR] GetMyCountryZoneTask Success
,V/AlarmManager( 1014): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6122): 
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6122): 
,D/SSRM:n  ( 1014): SIOP:: AP = 350
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6122): 
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6122): 
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6122): 
,I/jxcore-log( 6122): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6122): 
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 2035): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2035): CM callback handler got msg 524295
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 6023:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_6023/cgroup.procs: No such file or directory
,I/jxcore-log( 6122): Test app app.js loaded
I/jxcore-log( 6122): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6122): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6122): BLE advertisement is supported
I/jxcore-log( 6122): 
,I/chromium( 6122): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 6372): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9),
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 92080
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3479)
,W/SQLiteConnectionPool( 2035): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GAV4    ( 6434): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/AlarmManager( 1014): waitForAlarm result :8
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1845): callingUid 10012, callindPid: 1845
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6318): Conditions not met for autocaching.
I/MusicLeanback( 6318): Stop autocaching.
,E/GmsUtils( 6318): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6318): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5793): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): [GetString-S]
,I/ReactiveServiceManager( 5793): Supported : 1
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1014): handleString: Failed to handle string(-4)
E/terrier ( 1014): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5793): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{33052c3c u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,I/dhcpcd  ( 6372): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/lights  ( 1014): write_int failed to open -1
D/BatteryService( 1014): turn on LED for fully charged
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState,
,D/SecContentProvider2( 1014): mCursor = null
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1014): skipping global notification
D/WindowManager( 1014): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1177
I/PowerManagerService( 1014): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1014): Waking up from sleep (uid 10054)...
,V/KeyguardServiceDelegate( 1014): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@344cf60b),
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/KeyguardViewMediator( 1177): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1177): notifyScreenOnLocked
,D/PowerManagerService( 1014): [s] UserActivityState : 0 -> 1
,D/WindowOrientationListener( 1014): sensor enabled
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Display
I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
I/DisplayPowerController( 1014): Blocking screen on until initial contents have been drawn.
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorService( 1014): [SO] changed settle time [1]
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb8c1d190, enabled=1)
D/SensorService( 1014): [SO] AR_init
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1014): !@autosuspend_wakeup_count_disable
D/DisplayManagerService( 1014): !@display_state: OFF -> ON
I/libsuspend( 1014): !@autosuspend_wakeup_count_disable done
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb7553690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1014): Display changed displayId=0
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1177): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1177): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1177): onScreenTurnedOn,
I/PalmMotion( 1014): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1014): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1014): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1014): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
E/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,D/NfcService( 1439): call the applyRouting
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SamsungIME( 1815): showDlgMsgBox : false true true
,D/SensorService( 1014): [SO] currT = 96210090482, prevT = 78680168354, diff = 17529922128, [0.077 0.115 10.075]
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,E/lights  ( 1014): write_led_info failed to open -1
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_led_info failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1014): write_led_info failed to open -1
D/BatteryService( 1014): turn off LED
E/lights  ( 1014): write_led_info failed to open -1
,E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
E/lights  ( 1014): write_led_info failed to open -1
,E/lights  ( 1014): write_led_info failed to open -1
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1014): fail to set sysfs 1
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
,D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 110ms
,D/PowerManagerService( 1014): Excessive delay in !@display_state: ON: 112ms
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1845): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,D/InputMethodManagerService( 1014): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : -1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/SensorService( 1014): [SO] currT = 96280105534, prevT = 78680168354, diff = 17599937180, [0.096 0.096 10.036]
,D/SensorService( 1014): [SO] 0.096 0.096 10.036
D/SensorService( 1014): [SO] [100 -> 255]
,E/MotionRecognitionService( 1014):  handler : SCREEN_ON end
,D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBarKeyguardViewManager( 1177): callback.onShown()
D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/KeyguardServiceDelegate( 1014): **** SHOWN CALLED ****
D/NotificationService( 1014): ACTION_SCREEN_ON
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/DisplayPowerController( 1014): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 1014): Unblocked screen on after 170 ms
D/DisplayPowerState( 1014): !@ ColorFade exit
,D/BatteryMeterView( 1177): onDraw batteryColor : -1
,I/SurfaceFlinger(  256): id=12 Removed DolorFade (8/8)
,I/SurfaceFlinger(  256): id=12 Removed DolorFade (-2/8)
,E/libEGL  ( 1014): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1014): Excessive delay in ColorFade : dismiss: 16ms
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Timeline( 6122): Timeline: Activity_idle id: android.os.BinderProxy@28bbc9ef time:96315
,D/lights  ( 1014): lcd : 5 +
,D/lights  ( 1014): lcd : 5 -
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
,D/DisplayPowerController( 1014): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : true
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,E/WifiNative-wlan0( 1014): do suspend false
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
,V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  284): adev_set_parameters: exit
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1014): onStart. jobID=801
I/BackgroundCompactionService( 1014): onStart done. jobID=801
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/wpa_supplicant( 1993): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1993): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1993): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1993): Scan requested (ret=0) - scan timeout 30 seconds
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1014): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1734): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1734): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1734): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 09 05
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1014): Excessive delay in MISC setInteractive(true) while turning screen on: 175ms
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/lights  ( 1014): button : 1 +
,D/PowerManagerService( 1014): Excessive delay in nativeSetInteractive(true): 179ms
,D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 294ms
,I/SamsungIME( 1815): getNextShiftState() cursorCapsMode : 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1014): button : 1 -
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1014): SIOP:: AP = 340,
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1295): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1295): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1295): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1295): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453212240000
D/daemonapp( 1295): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453190748129
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1295): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1295): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
,I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper( 1014): Writing to database completed
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  289): DCD OFF
,D/Finsky  ( 5574): [970] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5574): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5883): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5883): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5883): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5883): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5883): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5883): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5883): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5883): entry::IDLE
,D/lights  ( 1014): button : 0 +
,D/lights  ( 1014): button : 0 -
,I/dhcpcd  ( 6372): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6372): wlan0: no IPv6 Routers available
,I/wpa_supplicant( 1993): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1014): InactiveState{ what=147461 }
D/WifiP2pService( 1014): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1014): DefaultState{ what=147461 }
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5883): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5883): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5883): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5883): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5883): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5883): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5883): entry::IDLE
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1014): [SO] 0.096 0.096 10.036
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{13f2b85d u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1014): !@Sync 3,
,V/AlarmManager( 1014): waitForAlarm result :8
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1734): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1734): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1734): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1734): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1734): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 09 06
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {1e12475d}
,D/SensorService( 1014): [SO] 0.077 0.077 10.036
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): start check captive portal 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1014): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,I/art     ( 1845): Explicit concurrent mark sweep GC freed 32535(2MB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 12MB/21MB, paused 1.099ms total 70.868ms
,E/DataBuffer( 1845): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37dc3e9a)
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1845): Vacuum at: now=1453190764365 tag=VacuumService
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1845): Scheduling Phenotype for one-off execution 1297 seconds from now (1453190764738)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1845): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1845): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1845): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1845): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1845): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1845): (HTTPLog)-Static: isShipBuild true
I/System.out( 1845): (HTTPLog)-Thread-265-316161315: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1845): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1845): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1845): Tagging socket 80 with tag 3000120100000000{805310977,0} for uid -1, pid: 1845, getuid(): 10012
,I/qtaguid ( 1845): Tagging socket 84 with tag 3000120100000000{805310977,0} for uid -1, pid: 1845, getuid(): 10012
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/FactoryTest( 5403): Not factory mode
,D/FactoryTest( 5403): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5403): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5403): still no open session command from host, so toast
,W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5403): Timeline: Activity_launch_request id:com.android.settings time:113901
,E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 6122
,E/MTPRx   ( 5403): started activity for popup
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,V/ActivityManager( 1014): Display changed displayId=0
,I/System.out( 1845): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1845): Tagging socket 80 with tag 3000120100000000{805310977,0} for uid -1, pid: 1845, getuid(): 10012
,W/ResourcesManager( 5403): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5403): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5403): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5403): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5403): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 6122
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@b1b8cc7 attribute=null, token = android.os.BinderProxy@9b16cc1
,E/ActivityManager( 1014): Invalid thumbnail dimensions: 650x650
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1845): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1845): Tagging socket 80 with tag 3000120100000000{805310977,0} for uid -1, pid: 1845, getuid(): 10012
,D/SettingsReceiverActivity( 5403): dev.kiessupport is : TRUE
,D/PhoneWindow( 5403): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5403): *FMB* installDecor flags : 8388610
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,I/Timeline( 6122): Timeline: Activity_idle id: android.os.BinderProxy@28bbc9ef time:114098
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1177 (0x0)
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 310
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1014): lcd : 1 +
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1014): lcd : 1 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1014): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SensorService( 1014): [SO] 0.077 0.096 10.036
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1014): [s] UserActivityState : 2 -> 4,
V/WindowOrientationListener( 1014): WindowOrientationListener disabled
,I/PowerManagerService( 1014): Nap time (uid 1000)...
D/SensorService( 1014): [SO] activate (ident=0xb8c1d190, enabled=0)
D/PowerManagerService( 1014): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/PowerManagerService( 1014): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/SurfaceFlinger(  256): id=16 createSurf (720x1280),-1 flag=20004, DolorFade
I/PowerManagerService( 1014): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1014): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1014): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1014): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1014): handleSandman : startDream(true)
E/PowerManagerService( 1014): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1014): Sleeping (uid 1000)...
D/PowerManagerService( 1014): [s] UserActivityState : 4 -> 0,
,D/SensorManager( 1014): unregisterListener ::   
,D/KeyguardViewMediator( 1177): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1177): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1177): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1177): notifyScreenOffLocked
,D/KeyguardViewMediator( 1177): timeout : 5000
,D/PowerManagerService( 1014): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 41ms
,D/DisplayPowerController( 1014): ColorFade: onAnimationStart
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,V/ActivityThread( 6122): updateVisibility : ActivityRecord{2799af85 token=android.os.BinderProxy@28bbc9ef {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/KeyguardViewMediator( 1177): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1177): handleNotifyScreenOff
,D/VolumePanel( 1177): onScreenTurnedOff()
,D/VolumePanel( 1177): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1177): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1177): onScreenTurnedOff
D/LightsService( 1014): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1014): write_int failed to open -1
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/BatteryService( 1014): turn on LED for fully charged
,E/SmartFaceService( 1014): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1014): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1014): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1014): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1014): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1014): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1014): fail to set sysfs 0
W/System.err( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1014): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1014): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1014): 	... 10 more
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1014):  handler : SCREEN_OFF end 
,E/WifiNative-wlan0( 1014): do suspend true
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/NotificationService( 1014): ACTION_SCREEN_OFF
,D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,I/BackgroundCompactionService( 1014): Schedule Type1 BGCompaction
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/BackgroundCompactionService( 1014): onIdleStop
,D/IpRemoteDisplayController( 1014): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1014): Bridge Server is not available
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1014): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1014): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1734): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1734): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DisplayPowerState( 1014): !@ ColorFade entry
,D/DisplayPowerController( 1014): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
,D/lights  ( 1014): lcd : 0 +
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,D/accuweather( 1734): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1734): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1734): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1734): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,E/LibSecureUISvc( 1949): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/SSRM:n  ( 1014): SIOP:: AP = 300
,D/lights  ( 1014): lcd : 0 -
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1014): performScreenOffTransition : no brightness animation
D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1014): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1014): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1014): Got set_interactive hint
,D/DisplayManagerService( 1014): !@display_state: ON -> OFF
,D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb7553690
I/DisplayManagerService( 1014): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager( 1014): Display changed displayId=0
,D/PowerManagerService( 1014): [PWL] sb release: PowerManagerService.Broadcasts
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/daemonapp( 1295): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1734): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1734): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1734): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8e887c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1192721096)
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: true,
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1192721096) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8e887c8,
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
,I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
D/PowerManagerService( 1014): Excessive delay in !@display_state: OFF: 266ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1014): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 276ms
D/SurfaceControl( 1014): Excessive delay in setPowerMode(): 266ms
I/PowerManagerService( 1014): [PWL] Off : 0s ago
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable
I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/libsuspend( 1014): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1014, ws=null) (elapsedTime=184)
,I/BatteryStatsDumper( 1014): Writing to database completed
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1014): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1014): [PWL] Off : 15s ago,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/BackgroundCompactionService( 1014): onStart. jobID=801
,I/BackgroundCompactionService( 1014): onStart done. jobID=801
,I/BackgroundCompactionService( 1014): Execute BGCompaction (type1). (0 times)
I/BackgroundCompactionService( 1014): compact_memory command done
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1014): !@Sync 5
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 50s ago,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 6
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,I/ClearcutLoggerApiImpl( 1845): disconnect managed GoogleApiClient
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 8
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 9
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6122): --= Surplus to requirements =--
I/jxcore-log( 6122): 
,I/jxcore-log( 6122): ****TEST TOOK:  ms ****
I/jxcore-log( 6122): 
I/jxcore-log( 6122): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6122): 
,D/AndroidRuntime( 6760): 
D/AndroidRuntime( 6760): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6760): CheckJNI is OFF
,D/AndroidRuntime( 6760): readGMSProperty: start
D/AndroidRuntime( 6760): readGMSProperty: already setted!!
D/AndroidRuntime( 6760): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6760): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6760): readGMSProperty: end
D/AndroidRuntime( 6760): addProductProperty: start
,E/AffinityControl( 6760): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6760): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{812030531}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1014): !@killApplicatoin: 10155, uninstall pkg
,I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,I/ActivityManager( 1014): Killing 6122:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/WindowState( 1014): WIN DEATH: Window{df44c66 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1014): Focus left window: 6122
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1014):   Force finishing activity ActivityRecord{3dbd6c65 u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,V/ActivityManager( 1014): Display changed displayId=0
,W/ActivityManager( 1014): Spurious death for ProcessRecord{318248c0 6122:com.test.thalitest/u0a155}, curProc for 6122: null
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,I/ActivityManager( 1014):   Force finishing activity ActivityRecord{3dbd6c65 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager( 1014): Duplicate finish request for ActivityRecord{3dbd6c65 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
,I/DBG_DM  ( 3143): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/InputDispatcher( 1014): Focused application released
,I/art     ( 5658): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 766us total 25.729ms
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 17,
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3143): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 17
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,E/SamsungIME( 1815): mOCRHelper is null
,W/GeofencerStateMachine( 1845): Ignoring removeGeofence because network location is disabled.
,I/art     ( 2035): Explicit concurrent mark sweep GC freed 6131(329KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.585ms total 84.588ms
,I/DBG_DM  ( 3143): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,I/DBG_DM  ( 3143): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/art     ( 5443): Explicit concurrent mark sweep GC freed 10060(608KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 743us total 102.051ms
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:09:22 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 17
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onCreate()
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3143): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3143): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3143): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3143): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,I/KLMS-2.5.183: ( 3508): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6777): MountEmulatedStorage()
E/Zygote  ( 6777): v2
I/libpersona( 6777): KNOX_SDCARD checking this for 10094
I/libpersona( 6777): KNOX_SDCARD not a persona
,I/SELinux ( 6777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6777 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): PACKAGE_REMOVED
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
E/Zygote  ( 6791): MountEmulatedStorage()
E/Zygote  ( 6791): v2
I/libpersona( 6791): KNOX_SDCARD checking this for 10044
I/libpersona( 6791): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3508): KLMSIntentService(): listeningToPackageRemoved().START
I/SELinux ( 6791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6791 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6791): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
I/KLMS-2.5.183: ( 3508): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1014): PackageReceiver onReceive()
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
,I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/TextServicesManagerService( 1014): no available spell checker services found
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
,D/TimaKeyStoreProvider( 6777): TimaSignature is unavailable
,D/ActivityThread( 6777): Added TimaKeyStore provider
,E/Zygote  ( 6807): MountEmulatedStorage()
E/Zygote  ( 6807): v2
I/libpersona( 6807): KNOX_SDCARD checking this for 1000
I/libpersona( 6807): KNOX_SDCARD not a persona
,I/SELinux ( 6807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6807 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
I/SELinux ( 6807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6791): TimaSignature is unavailable
,D/ActivityThread( 6791): Added TimaKeyStore provider,
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1014): uID is 10155
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,E/Zygote  ( 6821): MountEmulatedStorage()
E/Zygote  ( 6821): v2
I/libpersona( 6821): KNOX_SDCARD checking this for 10149
I/libpersona( 6821): KNOX_SDCARD not a persona
,I/SELinux ( 6821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false,
I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6821 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3143): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,E/SELinux ( 6821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 6807): TimaSignature is unavailable
D/ActivityThread( 6807): Added TimaKeyStore provider
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SurfaceFlinger(  256): id=17 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10155
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1014): com.test.thalitest(10155) is removed.
,D/InputDispatcher( 1014): Focus entered window: 3143
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3143): log_dcs ThreadedRenderer::initialize entered! 
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): listeningToPackageRemoved().END
,V/ActivityThread( 3143): updateVisibility : ActivityRecord{2f27aa10 token=android.os.BinderProxy@220073a7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/TimaKeyStoreProvider( 6821): TimaSignature is unavailable
,D/ActivityThread( 6821): Added TimaKeyStore provider
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ResourcesManager( 6791): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6791): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6791): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:15183( 6777): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6777): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6777): MDMBridge.setEnterpriseBridge()
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 35273(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 7.137ms total 339.427ms
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onDestroy()
,W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 6122 uid 10155
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/SamsungIME( 1815): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/elm:15183( 6777): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/Timeline( 3143): Timeline: Activity_idle id: android.os.BinderProxy@220073a7 time:310884
,D/elm:15183( 6777): ElmAgentService : onCreate()
W/ResourcesManager( 6807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:15183( 6777): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6777): MainReceiver.listeningToPackageRemoved()
W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/elm:15183( 6777): MDMBridge.getInstance()
D/elm:15183( 6777): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6777): MDMBridge.getAllLicenseInfoFromSDK()
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=8_task.xml
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=7_task.xml
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=8_task_thumbnail.png
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6841): MountEmulatedStorage()
,E/Zygote  ( 6841): v2
I/libpersona( 6841): KNOX_SDCARD checking this for 1000,
,I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 6841): KNOX_SDCARD not a persona
,I/SELinux ( 6841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ActivityManager( 1014): mDVFSHelper.release(),
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{38aa4f46 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:310940
,I/SELinux ( 6841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ThemeInfoUtil( 6821): getCurrentFestivalName is [null]
I/art     (  310): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 29.650ms
,D/ThemeInfoUtil( 6821): isCurrentFestival = false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/SQLiteLog( 6807): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/TimaKeyStoreProvider( 6841): TimaSignature is unavailable
,D/ActivityThread( 6841): Added TimaKeyStore provider
,D/PackageManager( 1014): delete codoeFile: 
,D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 16.967ms
I/AASA_removePackage( 1014): UID=10155 Target=com.test.thalitest
,D/PackageManager( 1014): result of delete: 1{812030531}
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/AndroidRuntime( 6760): Shutting down VM
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 18.899ms
,I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6859 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
E/Zygote  ( 6859): MountEmulatedStorage(),
E/Zygote  ( 6859): v2
I/libpersona( 6859): KNOX_SDCARD checking this for 10152
I/libpersona( 6859): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Killing 6046:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
I/SELinux ( 6859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6859): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
I/ActivityManager( 1014): Killing 5443:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/elm:15183( 6777): ElmAgentService : onDestroy().
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6859): TimaSignature is unavailable
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread( 6859): Added TimaKeyStore provider
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAservice-UpdateReceiver( 6841): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/System.err( 6841): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6841): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6841): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6841): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6841): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6841): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6841): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6841): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6841): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6841): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 6841): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6841): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 1014): Killing 5954:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteLog( 6859): (284) automatic index on shooting_modes(title_id)
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,D/UsbSettingsManager( 1014): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1014): onPackageRemoved : com.test.thalitest
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     ( 6807): Explicit concurrent mark sweep GC freed 8589(404KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 984us total 57.939ms
,E/Zygote  ( 6876): MountEmulatedStorage()
E/Zygote  ( 6876): v2
I/libpersona( 6876): KNOX_SDCARD checking this for 10032
I/libpersona( 6876): KNOX_SDCARD not a persona
,I/SELinux ( 6876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/SQLiteLog( 6807): (284) automatic index on crash_info_summary(package_name_touched)
D/NearbySource( 6791): Nearby Source Create!
,D/NearbyContext( 6791): Nearby Context Create!
I/SELinux ( 6876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6876 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6889): MountEmulatedStorage(),
E/Zygote  ( 6889): v2
I/libpersona( 6889): KNOX_SDCARD checking this for 10156
I/libpersona( 6889): KNOX_SDCARD not a persona
I/SELinux ( 6889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6889 uid=10156 gids={50156, 9997} abi=armeabi-v7a
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_5443/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_6046/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10038/pid_5954/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6876): TimaSignature is unavailable
,D/ActivityThread( 6876): Added TimaKeyStore provider
,D/BadgeProvider( 5986): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5986): sendNotify, [notify] : null
D/BadgeProvider( 5986): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5986): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5986): update, [UpdateCount] : 1
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,D/SLinkSource( 6791): Samsung link source created
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6889): TimaSignature is unavailable
,D/ActivityThread( 6889): Added TimaKeyStore provider
,E/Zygote  ( 6907): MountEmulatedStorage()
,E/Zygote  ( 6907): v2
I/libpersona( 6907): KNOX_SDCARD checking this for 1000
I/libpersona( 6907): KNOX_SDCARD not a persona
W/art     ( 6760): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/SELinux ( 6907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 6139:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/ActivityManager( 1014): Killing 5855:com.google.android.apps.docs/u0a91 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6907): TimaSignature is unavailable
,D/ActivityThread( 6907): Added TimaKeyStore provider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6889): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6889): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/FeatureConfig( 6876): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/TapandpayWidget:Utils( 6889): Clear T&P info.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6928): MountEmulatedStorage()
E/Zygote  ( 6928): v2
I/libpersona( 6928): KNOX_SDCARD checking this for 10035
I/libpersona( 6928): KNOX_SDCARD not a persona
,I/SELinux ( 6928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6928 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 6162:com.samsung.helphub/1000 (adj 15): empty #31
E/SELinux ( 6928): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6876): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 6907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6889): Widget is not attached.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6928): TimaSignature is unavailable
,W/ResourcesManager( 6876): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/ActivityThread( 6928): Added TimaKeyStore provider
W/ResourcesManager( 6876): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ContactProvider( 6791): getAllContactInfoList Start
,I/PackagesMonitor( 6791): PackagesMonitor onReceive :com.test.thalitest
,E/Zygote  ( 6946): MountEmulatedStorage()
,E/Zygote  ( 6946): v2
I/libpersona( 6946): KNOX_SDCARD checking this for 1000
I/libpersona( 6946): KNOX_SDCARD not a persona
,I/SELinux ( 6946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
W/ResourcesManager( 6876): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 6907): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/SQLiteDatabase( 6907): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6907): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6907): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 6907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6907): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 6907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 6907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 6907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 6907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 6907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 6907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 6907): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6907): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 690,7): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/SELinux ( 6946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/System.err( 6907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
E/SELinux ( 6946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
E/SharedPreferencesImpl( 6791): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 6807): Error inserting name=this value=SmartManager LowpowerContextEngine
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method),
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:183)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
,E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
W/ResourcesManager( 6876): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
W/ResourcesManager( 6876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteDatabase( 6807): Error inserting name=now value=Tue Jan 19 09:09:23 GMT+01:00 2016
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:184)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager( 6876): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6807): Error inserting name=isSystemBuild value=false
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): ,	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6807): Error inserting name=isDevelopVersion value=false
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6807): Error inserting name=DBVersion value=2003
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOExcep,tion: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
I/libpersona( 6960): KNOX_SDCARD checking this for 10160
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
I/libpersona( 6960): KNOX_SDCARD not a persona
E/SQLiteDatabase( 6807): Error inserting name=LPCSystemVersion value=1.0.0
E/SQLiteDatabase( 6807): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6807): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6807): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6807): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6807): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6807): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6807): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Zygote  ( 6960): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6960 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/Zygote  ( 6960): v2
I/ActivityManager( 1014): Killing 5925:com.google.android.gms:car/u0a12 (adj 15): empty #31
I/SELinux ( 6960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 6876): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SQLiteLog( 6807): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6807): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error

```
