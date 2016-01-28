#### Test 573480789efee08_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/CrashAnrDetector( 1015): onPackageAdded : com.test.thalitest
D/TP/MmsSmsProvider( 1451): query,matched:2117, calling pid = 5726
D/TP/MmsSmsProvider( 1451): match 2117:Elapsed time : 4.602 ms
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
D/TimaKeyStoreProvider( 5851): TimaSignature is unavailable
D/ActivityThread( 5851): Added TimaKeyStore provider
V/JNIHelp ( 5793): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
--------- beginning of system
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/DisplayPowerState( 1015): !@ ColorFade entry
D/DisplayPowerController( 1015): ColorFade: onAnimationEnd
D/lights  ( 1015): lcd : 0 +
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
W/ResourcesManager( 5471): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1015): Bridge Server is not available
D/lights  ( 1015): lcd : 0 -
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1015): Got set_interactive hint
W/ResourcesManager( 5471): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/DisplayManagerService( 1015): !@display_state: ON -> OFF
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb718a690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
I/DisplayManagerService( 1015): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1015): Display changed displayId=0
W/DisplayManagerService( 1015): Failed to notify process 5209 that displays changed, assuming it died.
W/DisplayManagerService( 1015): android.os.TransactionTooLargeException
W/DisplayManagerService( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1015): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1015): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/EasySignUpManager_1.0.1( 5726): isAuth is false
D/EasySignUpManager_1.0.1( 5726): getServiceStatus : serviceId (1) is OFF
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
E/CscParser( 5726): mps_code.dat does not exist
E/CscParser( 5726): customer_path =/system/csc/customer.xml
E/CscParser( 5726): fileName + /system/csc/customer.xml
D/StatusBar.NetworkController( 1174): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/CscParser( 5726): mps_code.dat does not exist
E/CscParser( 5726): customer_path =/system/csc/customer.xml
E/CscParser( 5726): fileName + /system/csc/customer.xml
W/ResourcesManager( 5471): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/CscParser( 5726): getInstance fileName =/system/csc/customer.xml
I/GCoreNlp( 1812): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/Mms/MmsConfig( 5726):  enable multiwindow = true
W/ActivityThread( 5793): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5793): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20fb5efd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5793): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 5471): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 4045:com.sec.spp.push/u0a35 (adj 15): empty #31
E/Mms/MessageUtils( 5726): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5726): updateCountryIso : update country iso info 
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/ChimeraCfgMgr( 5793): Reading stored module config
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MmsConfig( 5726): [end]    init() consume time = 334.872552
D/PackageBroadcastService( 1998): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Mms/Contact( 5726): [start]    init() consume time = 6.836563
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1998): Loading module APK com.google.android.play.games
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ResourcesManager( 5471): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/Mms/Contact( 5726): [end]    init consume time = 26.499427
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 5793): Loading module com.google.android.gms.car from APK com.google.android.gms
I/DBG_POLICYDM( 5819): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/DBG_POLICYDM( 5819): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10122/pid_5111/cgroup.procs: No such file or directory
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5819): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
W/ResourcesManager( 5471): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1451): query,matched:13, calling pid = 5726
D/TP/MmsSmsProvider( 1451): match 13:Elapsed time : 2.324 ms
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Mms/DraftCache( 5726): [start]    rebuildCache consume time = 52.853072
W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5159/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1451): query,matched:12, calling pid = 5726
D/TP/MmsSmsProvider( 1451): match 12:Elapsed time : 1.546 ms
I/DBG_POLICYDM( 5819): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/Mms/DraftCache( 5726): [end]    rebuildCache consume time = 15.123542
D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/Mms/MethodReflector( 5726): getSubId is called
D/Mms/TelephonyUtils( 5726): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5726): getTelephonyProperty is called
D/Mms/DownloadManager( 5726): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5726): auto download without roaming -> true
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5726): getSubId is called
D/Mms/MethodReflector( 5726): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5726): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5726): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5726): getTelephonyProperty is called
D/Mms/DownloadManager( 5726): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5726): auto download without roaming -> true
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5726): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5726): mAutoDownload ------> true
D/PersonaManagerService( 1015): ACTION_SCREEN_ON onReceive
I/DBG_POLICYDM( 5819): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_ON called
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/NativeLibraryUtils( 5793): Install completed successfully. count=14 extracted=0
I/DBG_POLICYDM( 5819): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5819): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/SurfaceControl( 1015): Excessive delay in setPowerMode(): 255ms
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
D/PowerManagerService( 1015): Excessive delay in !@display_state: OFF: 271ms
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1015): [PWL] Off : 0s ago
I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wakeLock' (uid=1000, pid=5819, ws=null) (elapsedTime=153)
I/PowerManagerService( 1015): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/PowerManagerService( 1015): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 286ms
W/libprocessgroup( 1015): failed to open /acct/uid_10033/pid_5209/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1015): applying state to connected service
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4045/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
D/Mms/ArtClassLoader( 5726): init [DONE] art
I/DBG_POLICYDM( 5819): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/accuweather( 1698): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/accuweather( 1698): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1698): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1698): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/NfcService( 1439): call the applyRouting
D/ComposerPerformance( 5726): 1453981575552 ms / [DONE] Composer constructor
E/CII     ( 5726): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5726): ReservationManager()
I/Mms/ReservationManager( 5726): resetAfterConnected()
E/Zygote  ( 5894): MountEmulatedStorage()
E/Zygote  ( 5894): v2
I/libpersona( 5894): KNOX_SDCARD checking this for 10035
I/libpersona( 5894): KNOX_SDCARD not a persona
I/SELinux ( 5894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5894 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
I/SELinux ( 5894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/Mms/Conversation( 5726): [start]    init() consume time = 110.586875
E/SELinux ( 5894): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1451): query,matched:7, calling pid = 5726
D/TP/MmsSmsProvider( 1451): match 7:Elapsed time : 1.807 ms
D/TP/MmsSmsProvider( 1451): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1451): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1451): sUpgradeVersion = 0, db.getVersion() = 81
I/Mms/ReservationManager( 5726): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1451): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): need read changed broadcast:false
I/SamsungIME( 1789): getNextShiftState() cursorCapsMode : 0
D/Mms/MmsApp( 5726): [end]    onCreate() consume time = 23.620781
D/Mms/Conversation( 5726): [end]    init consume time = 1.646042
I/DBG_POLICYDM( 5819): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/TimaKeyStoreProvider( 5894): TimaSignature is unavailable
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5894): Added TimaKeyStore provider
I/DBG_POLICYDM( 5819): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/Mms/MessagingNotification( 5726): [start]    init() consume time = 8.990573
D/Mms/MessagingNotification( 5726): [end]    init consume time = 2.249687
D/TP/MmsSmsProvider( 1451): query,matched:0, calling pid = 5726
V/TP/MmsSmsProvider( 1451): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1451): match 0:Elapsed time : 1.543 ms
D/Mms/DownloadManager( 5726): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5726): roaming ------> false, mSimSlot = 0
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5819): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
D/Mms/Synchronizer( 5726): [start]    doSync consume time = 13.439011
D/Mms/MethodReflector( 5726): getSubId is called
D/Mms/TelephonyUtils( 5726): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5726): getTelephonyProperty is called
D/Mms/DownloadManager( 5726): roaming -> false (slotId = 0)
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/TP/MmsSmsProvider( 1451): update, matched:300, calling pid = 5726
V/TP/MmsSmsProvider( 1451): syncDBData start
V/TP/MmsSmsProvider( 1451): syncDBData sms end
V/TP/MmsSmsProvider( 1451): syncDBData mms end
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5726): auto download without roaming -> true
D/Mms/DownloadManager( 5726): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5726): mAutoDownload ------> true
V/TP/MmsSmsProvider( 1451): syncDBData end
D/Mms/SpamFilter( 5726): [start]    SpamFilter fill() begin consume time = 14.266875
D/TP/MmsSmsProvider( 1451): query,matched:400, calling pid = 5726
D/Mms/Synchronizer( 5726): [end]    doSync consume time = 8.705573
D/Mms/FreeMessageStatusReceiver( 5726): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SSRM:n  ( 1015): SIOP:: AP = 330
E/PhotosPlugin( 5851): Loading PhotosPlugin
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/Zygote  ( 5915): MountEmulatedStorage()
E/Zygote  ( 5915): v2
I/libpersona( 5915): KNOX_SDCARD checking this for 10072
I/libpersona( 5915): KNOX_SDCARD not a persona
I/SELinux ( 5915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5915 uid=10072 gids={50072, 9997} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/SELinux ( 5915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5915): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/SpamFilter( 5726): [end]    SpamFilter fill() finished consume time = 30.47651
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
E/lights  ( 1015): write_int failed to open -1
D/LightsService( 1015): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1015): turn on LED for fully charged
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_POLICYDM( 5819): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5819): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TimaKeyStoreProvider( 5915): TimaSignature is unavailable
D/Mms/FreeMessageReceiverService( 5726): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5726): onHandleIntent: ACTION_PACKAGE_ADDED
D/ActivityThread( 5915): Added TimaKeyStore provider
E/SPPClientService( 5894): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5894): [PushClientApplication] Push log off : This is Ship build version
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/02/14:24:23
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/28/12:46:15
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
E/Zygote  ( 5933): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5933 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/Zygote  ( 5933): v2
I/libpersona( 5933): KNOX_SDCARD checking this for 10047
I/libpersona( 5933): KNOX_SDCARD not a persona
I/SELinux ( 5933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1015): fail to set sysfs 0
E/SELinux ( 5933): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5819): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5819): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: true
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
D/SPPClientService( 5894): PushLog.txt file is not deleted.
D/SPPClientService( 5894): PushLog.txt file is not deleted.
D/SPPClientService( 5894): ============PushLog. stop!
I/DBG_POLICYDM( 5819): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5819): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5819): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5819): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/TimaKeyStoreProvider( 5933): TimaSignature is unavailable
D/ActivityThread( 5933): Added TimaKeyStore provider
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
E/Zygote  ( 5949): MountEmulatedStorage()
E/Zygote  ( 5949): v2
I/libpersona( 5949): KNOX_SDCARD checking this for 10038
I/SELinux ( 5949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5949): KNOX_SDCARD not a persona
I/SELinux ( 5949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5949): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5949 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5270:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
I/ActivityManager( 1015): Killing 5250:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #32
I/DBG_POLICYDM( 5819): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/TimaKeyStoreProvider( 5949): TimaSignature is unavailable
D/ActivityThread( 5949): Added TimaKeyStore provider
I/ServiceManager(  318): Waiting for service AtCmdFwd...
W/ResourcesManager( 5933): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5933): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5933): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/BadgeProvider( 5915): onCreate
D/BadgeProvider( 5915): DatabaseHelper
D/SamsungIME( 1789): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
E/MotionRecognitionService( 1015):  handler : SCREEN_OFF end 
W/ResourcesManager( 5949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5949): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5819): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/NotificationService( 1015): ACTION_SCREEN_OFF
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
D/Mms/MessagingNotification( 5726): checkBadgeCount unreadCount=0 badgeCount=0
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5270/cgroup.procs: No such file or directory
D/CAR.SERVICE( 5793): Connecting to CarCallService...
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5250/cgroup.procs: No such file or directory
I/BackgroundCompactionService( 1015): Schedule Type1 BGCompaction
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1451): query,matched:26, calling pid = 5726
E/WifiNative-wlan0( 1015): do suspend true
D/TP/SmsProvider( 1451): match 26:Elapsed time : 1.793 ms
D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1015): Bridge Server is not available
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PersonaManagerService( 1015): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_OFF called
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1413): [EmergencyStateReceiver] binteractive [false] why[3]
D/TP/MmsSmsProvider( 1451): query,matched:6, calling pid = 5726
D/TP/MmsSmsProvider( 1451): match 6:Elapsed time : 2.533 ms
I/art     ( 5793): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5793): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NfcService( 1439): call the applyRouting
D/accuweather( 1698): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1698): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/CAR.SERVICE( 5793): com.google.android.projection.gearhead isn't installed.
I/ActivityManager( 1015): Killing 5313:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/accuweather( 1698): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,E/Zygote  ( 5969): MountEmulatedStorage()
I/libpersona( 5969): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5969): v2
I/libpersona( 5969): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5969 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5313/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5969): TimaSignature is unavailable
D/ActivityThread( 5969): Added TimaKeyStore provider
D/SSRM:n  ( 1015): SIOP:: AP = 340
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/MyFiles ( 5933): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5330:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/LibSecureUISvc( 1939): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
D/CAR.TEL.Service( 5793): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5793): Creating a new PhoneAdapter instance
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5793): setListener: com.google.android.gms.car.dn@2fd35f0
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5793): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5793): Starting CarCallService with initial phone null
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/CAR.SERVICE( 5793): Package validated; name: com.android.vending
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
I/DBG_POLICYDM( 5819): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5993): MountEmulatedStorage()
E/Zygote  ( 5993): v2
I/libpersona( 5993): KNOX_SDCARD checking this for 10053
I/libpersona( 5993): KNOX_SDCARD not a persona
I/SELinux ( 5993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5993 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5993): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5819): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5969): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/TimaKeyStoreProvider( 5993): TimaSignature is unavailable
D/ActivityThread( 5993): Added TimaKeyStore provider
W/ResourcesManager( 5993): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5330/cgroup.procs: No such file or directory
D/Compatibility( 5993): onReceive() it will make start service
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5993): onHandleIntent()
D/Compatibility( 5993): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/Compatibility( 5993): found: 2
I/UpdateIcingCorporaServi( 5427): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5993): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5993): skipping ResolveInfo{31257df com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5993): considering ResolveInfo{3b0f8c2c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5993): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5993): enabling receiver ResolveInfo{385c46f5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5993): enabling receiver ResolveInfo{33670c8a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1998): Module APK com.google.android.play.games already loaded
V/Finsky  ( 5561): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/Compatibility( 5993): enabling receiver ResolveInfo{56e92fb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Mms/Omacp( 5726): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Compatibility( 5993): enabling receiver ResolveInfo{29ff3f18 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5993): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AsyncTaskServiceImpl( 1998): Submit a task: k
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5969): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 1998): Processing package: com.test.thalitest
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
D/GassUtils( 1998): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1998): Found info for package com.test.thalitest in db.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5819): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1015): Explicit concurrent mark sweep GC freed 248696(16MB) AllocSpace objects, 12(5MB) LOS objects, 33% free, 27MB/41MB, paused 3.080ms total 243.047ms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
I/art     ( 1812): Explicit concurrent mark sweep GC freed 53103(2MB) AllocSpace objects, 20(512KB) LOS objects, 40% free, 12MB/21MB, paused 1.251ms total 83.119ms
E/DataBuffer( 1812): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@60a6166)
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 5984): 
D/AndroidRuntime( 5984): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5984): CheckJNI is OFF
D/AndroidRuntime( 5984): readGMSProperty: start
D/AndroidRuntime( 5984): readGMSProperty: already setted!!
D/AndroidRuntime( 5984): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5984): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5984): readGMSProperty: end
D/AndroidRuntime( 5984): addProductProperty: start
I/PeopleDatabaseHelper( 1998): cleanUpNonGplusAccounts done.
I/SL_DEBUG( 5949): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5949): isLoggable:: SL_DEBUG_EXIST = false
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1998): Using Auth Proxy for data requests.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 5427): UpdateCorporaTask done [took 520 ms] updated apps [took 520 ms] 
I/ActivityManager( 1015): Killing 5369:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ServiceManager(  318): Waiting for service AtCmdFwd...
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5949): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5369/cgroup.procs: No such file or directory
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5949): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 5984): AffinityControl: registerfunction enter
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6041): MountEmulatedStorage()
E/Zygote  ( 6041): v2
I/libpersona( 6041): KNOX_SDCARD checking this for 10041
I/libpersona( 6041): KNOX_SDCARD not a persona
I/SELinux ( 6041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6041): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6041 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5984): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6041): TimaSignature is unavailable
D/ActivityThread( 6041): Added TimaKeyStore provider
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6060): MountEmulatedStorage()
E/Zygote  ( 6060): v2
I/libpersona( 6060): KNOX_SDCARD checking this for 10155
I/libpersona( 6060): KNOX_SDCARD not a persona
I/SELinux ( 6060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, uhalitest
E/SELinux ( 6060): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6060 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SA      ( 6041): [SSP] onCreated
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 3080
D/AndroidRuntime( 5984): Shutting down VM
D/TimaKeyStoreProvider( 6060): TimaSignature is unavailable
D/ActivityThread( 6060): Added TimaKeyStore provider
I/SA      ( 6041): [TPM] There is no property file
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SA      ( 6041): [SCU] isHaveSA() - false
I/SA      ( 6041): [TPM] getModelProperty : null
I/SA      ( 6041): [TPM] getCSCProperty : null
I/SA      ( 6041): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6041): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6041): [DM] TFT FEATURE: false
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
I/SA      ( 6041): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/SA      ( 6041): [DM] init START
I/SA      ( 6041): [DM] This device is not a Vodafone
I/ActivityManager( 1015): Killing 5288:com.google.android.talk/u0a104 (adj 15): empty #31
W/ResourceType( 6041): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
I/wpa_supplicant( 2073): nl80211: Received scan results (3 BSSes)
D/WifiP2pService( 1015): InactiveState{ what=147461 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (-2/9)
W/ResourceType( 6041): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6041): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6041): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
V/ActivityThread( 3080): updateVisibility : ActivityRecord{1422d29c token=android.os.BinderProxy@c661a23 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/SA      ( 6041): [SCU] isHaveSA() - false
I/SA      ( 6041): support phone number id : false
I/SA      ( 6041): [DM] Supports Ref Jpn : true
I/SA      ( 6041): [DM] init END
I/SA      ( 6041): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6041): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 5490:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/WebViewFactory( 6060): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/BatteryStatsDumper( 1015): Writing to database completed
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5490/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5288/cgroup.procs: No such file or directory
W/art     ( 5984): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 6060): Time to load native libraries: 2 ms (timestamps 2350-2352)
I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
W/GAV2    ( 5851): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/WebViewChromiumFactoryProvider( 6060): Binding Chromium to main looper Looper (main, tid 1) {385c46f5}
,I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
,I/chromium( 6060): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6060): Initializing chromium process, singleProcess=true
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6060): ApplicationContext is null in ApplicationStatus
,W/chromium( 6060): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6060): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6060): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 6060): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6060): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6060): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6060): Local Branch: 
I/Adreno-EGL( 6060): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6060): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6060):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/qtaguid ( 5561): Untagging socket 44
I/qtaguid ( 5561): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5561): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5561): untagSocket(44) failed with errno -22
I/System.out( 5561): Thread-953 calls detatch()
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,I/Mms/MmsApp( 5726):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5726): [start]    fillCache consume time = 1919.78401
D/Mms/ComposeMessageFragment( 5726): fillCache, easy = false
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
W/GAV2    ( 5851): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6112): MountEmulatedStorage()
,E/Zygote  ( 6112): v2
I/libpersona( 6112): KNOX_SDCARD checking this for 10100
I/libpersona( 6112): KNOX_SDCARD not a persona,
,I/SELinux ( 6112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6112 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6112): TimaSignature is unavailable
,D/ActivityThread( 6112): Added TimaKeyStore provider
,W/chromium( 6060): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/PackageIntentReceiver( 6112): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6112): Not GearManger package! 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,I/Icing   ( 1998): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{2f5d0abb u0 com.test.thalitest/.MainActivity t8}
,E/Zygote  ( 6127): MountEmulatedStorage()
E/Zygote  ( 6127): v2
I/libpersona( 6127): KNOX_SDCARD checking this for 1000
I/libpersona( 6127): KNOX_SDCARD not a persona
,I/SELinux ( 6127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6127): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/AwContents( 6060): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 24.332ms
,D/PhoneWindow( 6060): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6060): *FMB* installDecor flags : 8456448
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.578ms
,D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1998): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 6127): TimaSignature is unavailable
,D/ActivityThread( 6127): Added TimaKeyStore provider
,D/SystemWebViewEngine( 6060): CordovaWebView is running on device made by: samsung
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 16.943ms
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,D/AbsListView( 5726): Get MotionRecognitionManager
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/MotionRecognitionService( 1015):  ssp status : false
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/ComposeMessageFragment( 5726): [end]    fillCache consume time = 217.904219
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/OpenGLRenderer( 6060): Render dirty regions requested: true
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6154): MountEmulatedStorage()
,E/Zygote  ( 6154): v2
I/libpersona( 6154): KNOX_SDCARD checking this for 1000
I/libpersona( 6154): KNOX_SDCARD not a persona
,I/SELinux ( 6154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6154 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Killing 5521:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
E/SELinux ( 6154): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/GAV2    ( 5851): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1015): Killing 5539:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5006:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,V/ActivityThread( 6060): updateVisibility : ActivityRecord{320984e1 token=android.os.BinderProxy@2b8630eb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6060): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6060): *FMB* isFloatingMenuEnabled return false
,D/TimaKeyStoreProvider( 6154): TimaSignature is unavailable
,D/ActivityThread( 6154): Added TimaKeyStore provider
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 6060,
,W/AccountFeatureHelper( 5851): Write apps_features disabled false
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6060): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6060): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6060): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6060): Enabling debug mode 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_5539/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5006/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5521/cgroup.procs: No such file or directory
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 1998): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 1998): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,I/ActivityManager( 1015): Displayed Component not be shown by security: +844ms (total +946ms)
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{2f5d0abb u0 com.test.thalitest/.MainActivity t8} time:83028
W/ActivityManager( 1015): mDVFSHelper.release()
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
D/Mms/BubbleViewCache( 5726): fillCache bubble = 1
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SamsungIME( 1789): getCurrentCandidateView
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (7/9)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6060): showStatusIcon on inactive InputConnection
,I/Timeline( 6060): Timeline: Activity_idle id: android.os.BinderProxy@2b8630eb time:83045
,E/Zygote  ( 6177): MountEmulatedStorage()
,E/Zygote  ( 6177): v2
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6177 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6177): KNOX_SDCARD checking this for 10120
I/libpersona( 6177): KNOX_SDCARD not a persona
,I/SELinux ( 6177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Killing 4519:com.google.android.music:main/u0a111 (adj 15): empty #31
I/SELinux ( 6177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6177): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6177): TimaSignature is unavailable
,D/ActivityThread( 6177): Added TimaKeyStore provider
,D/AcmsPackageEventListener( 6154): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6154): Enter Oncreate
,W/ResourcesManager( 6177): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsServiceMonitor( 6154): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6154): creating AcmsCore
D/AcmsCore( 6154): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6154): AcmsCore
,D/AcmsCore( 6154): init
,D/AcmsCore( 6154): Looper handler is not null
,D/AcmsCore( 6154): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6154): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6154): Incrementing - Counter value: 1
D/AcmsCore( 6154): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6154): onStartCommand
D/AcmsService( 6154): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6154): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6154): Incrementing - Counter value: 2
D/AcmsService( 6154): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6154): AcmsCertificateMngr
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6154): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6154): AcmsRevocationMngr
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4519/cgroup.procs: No such file or directory
,D/SamsungIME( 1789): Dismiss ExpandCandiate
,W/BindingManager( 6060): Cannot call determinedVisibility() - never saw a connection for the pid: 6060
,D/AcmsService( 6154): Inside handle Intent
D/AcmsService( 6154): App added - package name: com.test.thalitest
D/AcmsCore( 6154): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6154): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6154): Incrementing - Counter value: 3
D/AcmsCore( 6154): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6154): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6154): Decrementing - Counter value: 2
,D/JsMessageQueue( 6060): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1789): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/SamsungIME( 1789): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6060): JniHelper::setJavaVM(0xb725e450), pthread_self() = -1216670048
,I/SamsungIME( 1789): KeybaordView init() : load resources
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/Icing   ( 1998): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,I/chromium( 6060): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SamsungIME( 1789): getCurrentKeyboard
,I/SamsungIME( 1789): getTextKeyboard
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1789): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1812): callingUid 10012, callindPid: 1812
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1812): [257] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1998): Restart initialization of location
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1812): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4855:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1812): No location to return for getLastLocation()
,W/FusedLocationProvider( 1812): location=null
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1303): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1303): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454003100000
D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453981578862
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1303): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1698): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4855/cgroup.procs: No such file or directory
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/accuweather( 1698): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1698): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1698): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1698): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1698): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1698): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1698): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1698): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1698): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1698): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SamsungIME( 1789): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5561): Thread-952(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5561): Thread-952(ApacheHTTPLog):isShipBuild true
I/System.out( 5561): Thread-952(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5561): Thread-952(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/DBG_POLICYDM( 5819): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5819): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1174): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1174): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1174): *** Keyguard wallpaper service already unbounded
,W/jxcore-log( 6060): Initializing JXcore engine
W/jxcore-log( 6060): JXcore engine is ready
,E/audit   ( 1927): type=1400 msg=audit(1453981579.955:205): avc:  denied  { ioctl } for  pid=6202 comm="Thread-1060" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1927):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1927): type=1300 msg=audit(1453981579.955:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8fe8f8 items=0 ppid=309 ppcomm=main pid=6202 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1060" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1927): type=1320 msg=audit(1453981579.955:205): 
,W/jxcore-log( 6060): Starting JXcore engine
,W/jxcore-log( 6060): Platform android
W/jxcore-log( 6060): 
W/jxcore-log( 6060): Process ARCH arm
W/jxcore-log( 6060): 
,I/qtaguid ( 5561): Untagging socket 44
,I/qtaguid ( 5561): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5561): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5561): untagSocket(44) failed with errno -22
I/System.out( 5561): Thread-952 calls detatch()
,D/Finsky  ( 5561): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to true
,W/ResourcesManager( 5561): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5561): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5561): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5561): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/DeviceConnectionService( 1812): client connected with version: 8296000
,D/Finsky  ( 5561): [974] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5561): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5561): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/jxcore-log( 6060): JXcore Cordova bridge is ready!
I/jxcore-log( 6060): 
,W/jxcore-log( 6060): JXcore engine is started
,E/jxcore  ( 6060): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6060): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6060): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1015): Focused application set to: xxxx
,I/ActivityManager( 1015): Killing 5348:com.android.calendar/u0a135 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5348/cgroup.procs: No such file or directory
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 44437(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.630ms total 160.762ms
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focus left window: 6060
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,E/ViewRootImpl( 6060): sendUserActionEvent() mView == null
,E/SMD     (  288): DCD OFF
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 23
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/System.out( 5561): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5561): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5561): (HTTPLog)-Static: isShipBuild true
I/System.out( 5561): (HTTPLog)-Thread-963-446630040: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5561): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only,
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3080): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3080): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  258): id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/System.out( 5561): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/InputDispatcher( 1015): Focus entered window: 3080,
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3080): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3080): updateVisibility : ActivityRecord{1422d29c token=android.os.BinderProxy@c661a23 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6060): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1789): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,I/Timeline( 3080): Timeline: Activity_idle id: android.os.BinderProxy@c661a23 time:85924
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{fd5cf00 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:85948
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryService( 1015): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CAR.SERVICE( 5793): mConnectedToCar = false, abort
,I/ActivityManager( 1015): Killing 5175:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityThread( 5793): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@415c3d8 that was originally bound here
E/ActivityThread( 5793): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@415c3d8 that was originally bound here
E/ActivityThread( 5793): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5793): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5793): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5793): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5793): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5793): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5793): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5793): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5793): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5793): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5793): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5793): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5793): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5793): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5793): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5793): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5793): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5793): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5793): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5793): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5793): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5793): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5793): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35513e33 that was originally bound here
E/ActivityThread( 5793): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35513e33 that was originally bound here
E/ActivityThread( 5793): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5793): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5793): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5793): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5793): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5793): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5793): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5793): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5793): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5793): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5793): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5793): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5793): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5793): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5793): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5793): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5793): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5793): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5793): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5793): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5793): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@357ec861
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5175/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5407:com.samsung.aasaservice/1000 (adj 15): empty #31
,E/SMD     (  288): DCD OFF
,D/AcmsKeyStoreHelper( 6154):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6154): Key Store exist
I/AcmsKeyStoreHelper( 6154): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6154):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6154): getKeyStoreForApplication success 
D/AcmsCore( 6154): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6154): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6154): Decrementing - Counter value: 1
D/AcmsCore( 6154): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6154): This is NOT a valid MirrorLink app
D/AcmsCore( 6154): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6154): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6154): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6154): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6154): getSvcCounter - Counter value: 0
D/AcmsService( 6154): Enter onDestroy
I/AcmsService( 6154): cleanUp(): inside service clean up
D/AcmsCore( 6154): AcmsCore: inside DeInit
D/AcmsCore( 6154): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6154): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6154): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 6154): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 6154): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 6154): getSvcCounter - Counter value: 0
D/AcmsService( 6154): killing acms process
I/Process ( 6154): Sending signal. PID: 6154 SIG: 9
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5407/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Process ACMS.Process (pid 6154)(adj 0) has died(60,1134)
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5025:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_5025/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{36737839 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/PowerManagerService( 1015): [PWL] Off : 15s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,D/Finsky  ( 5561): [965] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5561): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1812): Vacuum at: now=1453981609033 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1812): Scheduling Phenotype for one-off execution 2817 seconds from now (1453981609409)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1812): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1812): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1812): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1812): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1812): Tagging socket 88 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1812, getuid(): 10012
,I/qtaguid ( 1812): Tagging socket 91 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1812, getuid(): 10012
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/FactoryTest( 5387): Not factory mode
,D/FactoryTest( 5387): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5387): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5387): still no open session command from host, so toast
W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5387): Timeline: Activity_launch_request id:com.android.settings time:115186
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire(),
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 3080
,E/MTPRx   ( 5387): started activity for popup,
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5387): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5387): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5387): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5387): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5387): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5387): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5387): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 3080
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@23520ebe attribute=null, token = android.os.BinderProxy@97af830
,D/SettingsReceiverActivity( 5387): dev.kiessupport is : TRUE
,D/PhoneWindow( 5387): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5387): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 23
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false,
,I/DBG_DM  ( 3080): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3080): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,I/DBG_DM  ( 3080): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3080): Timeline: Activity_idle id: android.os.BinderProxy@c661a23 time:115423,
V/ActivityThread( 3080): updateVisibility : ActivityRecord{1422d29c token=android.os.BinderProxy@c661a23 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
I/System.out( 1812): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1812): Tagging socket 79 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,I/qtaguid ( 1812): Tagging socket 94 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1812): Tagging socket 79 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1812): Tagging socket 79 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1812): Tagging socket 79 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1812): Tagging socket 79 with tag 1000120100000000{268440065,0} for uid -1, pid: 1812, getuid(): 10012
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryService( 1015): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 5
,E/SMD     (  288): DCD OFF
,I/ClearcutLoggerApiImpl( 1812): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1998): Aggregate from 1453979843517 (log), 1453979843517 (data)
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...,
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040,
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 11
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1015): [PWL] Off : 275s ago,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 12
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 13,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=424980 batch.start=797838
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 14,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 15,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 391s ago,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  315): bootchecker wake up!!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 17,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1015): [PWL] Off : 456s ago
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/Atfwd_Daemon(  318): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 19,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 526s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 20
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 21
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 22
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1015): [PWL] Off : 601s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 23,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 24
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 681s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 25,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/Watchdog( 1015): !@Sync 26,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 27,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 766s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 28
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 29,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 856s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate,
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GoogleURLConnFactory( 1812): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1812): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1812): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out( 1812): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1812): Tagging socket 53 with tag 1000120300000000{268440067,0} for uid -1, pid: 1812, getuid(): 10012
,I/qtaguid ( 1812): Tagging socket 78 with tag 1000120300000000{268440067,0} for uid -1, pid: 1812, getuid(): 10012,
,W/PhenotypeConfigurator( 1812): Server returned 404
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 31
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 32,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 33
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 951s ago
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 34
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 35
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 36,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 37
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1051s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 38
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1453982710762
,I/ApplicationPolicy( 1015): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1015): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1015): ::isTableExists: Table exists 
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1453982711199
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 40
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1156s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 41
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1015): !@Sync 42
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 6177): Attempt to remove local handle scope entry from IRT, ignoring
,D/EnterpriseController(  278): uids 10120
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10120
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  288): DCD OFF
D/AndroidRuntime( 6759): 
D/AndroidRuntime( 6759): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6759): CheckJNI is OFF
D/AndroidRuntime( 6759): readGMSProperty: start
D/AndroidRuntime( 6759): readGMSProperty: already setted!!
D/AndroidRuntime( 6759): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6759): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6759): readGMSProperty: end
D/AndroidRuntime( 6759): addProductProperty: start
E/AffinityControl( 6759): AffinityControl: registerfunction enter
D/AndroidRuntime( 6759): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{949201278}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): !@killApplicatoin: 10155, uninstall pkg
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1015): Killing 6060:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4775): Explicit concurrent mark sweep GC freed 15317(823KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 830us total 46.090ms
I/art     ( 3824): Explicit concurrent mark sweep GC freed 2652(162KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 896us total 40.064ms
W/ActivityManager( 1015): Spurious death for ProcessRecord{29f7bedf 6060:com.test.thalitest/u0a155}, curProc for 6060: null
I/art     ( 5427): Explicit concurrent mark sweep GC freed 11667(771KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 936us total 52.386ms
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1789): mOCRHelper is null
I/art     ( 1998): Explicit concurrent mark sweep GC freed 2534(112KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/18MB, paused 1.509ms total 78.847ms
W/SQLiteConnectionPool( 1998): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.183: ( 3543): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 28 13:06:28 GMT+01:00 2016
D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3543): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6773): MountEmulatedStorage()
I/libpersona( 6773): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6773): v2
I/libpersona( 6773): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6773 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): onCreate()
I/SELinux ( 6773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
I/SELinux ( 6773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6787): MountEmulatedStorage()
I/libpersona( 6787): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6787): v2
I/libpersona( 6787): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3543): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6773): TimaSignature is unavailable
D/ActivityThread( 6773): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6787 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3543): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6802 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6802): MountEmulatedStorage()
E/Zygote  ( 6802): v2
I/libpersona( 6802): KNOX_SDCARD checking this for 10149
I/libpersona( 6802): KNOX_SDCARD not a persona
I/SELinux ( 6802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 6787): TimaSignature is unavailable
D/ActivityThread( 6787): Added TimaKeyStore provider
E/SQLiteLog( 4775): (284) automatic index on crash_info_summary(package_name_touched)
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): PACKAGE_REMOVED
I/art     ( 1015): Explicit concurrent mark sweep GC freed 49814(4MB) AllocSpace objects, 135(2MB) LOS objects, 33% free, 28MB/42MB, paused 3.081ms total 244.484ms
I/art     ( 1015): WaitForGcToComplete blocked for 163.031ms for cause Explicit
D/TimaKeyStoreProvider( 6802): TimaSignature is unavailable
D/ActivityThread( 6802): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): listeningToPackageRemoved().START
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15183( 6773): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6773): ELMEngine.ELMEngine( context ).
D/elm:15183( 6773): MDMBridge.setEnterpriseBridge()
D/RegisteredServicesCache( 1439): empty dynamic service
D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/art     ( 4775): Explicit concurrent mark sweep GC freed 1136(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 4.543ms total 39.970ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6773): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 6773): ElmAgentService : onCreate()
W/ResourcesManager( 6787): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/elm:15183( 6773): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6773): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6773): MDMBridge.getInstance()
D/elm:15183( 6773): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6773): MDMBridge.getAllLicenseInfoFromSDK()
D/ThemeInfoUtil( 6802): getCurrentFestivalName is [null]
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/ThemeInfoUtil( 6802): isCurrentFestival = false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5915): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5915): sendNotify, [notify] : null
D/BadgeProvider( 5915): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5915): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5915): update, [UpdateCount] : 1
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6821): MountEmulatedStorage()
E/Zygote  ( 6821): v2
I/libpersona( 6821): KNOX_SDCARD checking this for 1000
I/libpersona( 6821): KNOX_SDCARD not a persona
I/SELinux ( 6821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6821 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15183( 6773): ElmAgentService : onDestroy().
W/ContextImpl( 5144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): listeningToPackageRemoved().END
D/TimaKeyStoreProvider( 6821): TimaSignature is unavailable
D/ActivityThread( 6821): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3543): KLMSIntentService(): onDestroy()
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/RCPManager( 5505):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
I/TapandpayWidget:TapandpayAppWidgetProvider( 5758): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5758): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5758): Clear T&P info.
D/AASAservice-UpdateReceiver( 6821): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6821): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6821): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6821): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6821): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6821): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6821): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6821): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6821): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6821): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6821): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6821): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6821): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/TapandpayWidget:TapandpayAppWidgetProvider( 5758): Widget is not attached.
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6840): MountEmulatedStorage()
I/libpersona( 6840): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6840): v2
I/libpersona( 6840): KNOX_SDCARD not a persona
I/SELinux ( 6840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6840 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5446:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/TimaKeyStoreProvider( 6840): TimaSignature is unavailable
D/ActivityThread( 6840): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/art     ( 1015): Explicit concurrent mark sweep GC freed 12632(731KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.873ms total 272.964ms
E/Zygote  ( 6855): MountEmulatedStorage()
I/libpersona( 6855): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6855): v2
I/libpersona( 6855): KNOX_SDCARD not a persona
I/SELinux ( 6855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 6840): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5745:com.sec.pcw.device/1000 (adj 15): empty #31
D/[0]UMC:UMCContentProvider( 6840): @onCreate
D/TimaKeyStoreProvider( 6855): TimaSignature is unavailable
D/ActivityThread( 6855): Added TimaKeyStore provider
D/[0]UMC:Core( 6840): onCreate(): 
D/[0]UMC:Core( 6840): @isManagedProfileUser
D/[0]UMC:Core( 6840): userId: 0
D/[0]UMC:Core( 6840): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6840): userInfo.isManagedProfile() : false
D/[0]UMC:DeviceInfo( 6840): USA==US==
D/NearbySource( 6787): Nearby Source Create!
D/NearbyContext( 6787): Nearby Context Create!
W/ContextImpl( 6855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ActivityManager( 1015): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
E/Zygote  ( 6871): MountEmulatedStorage()
E/Zygote  ( 6871): v2
I/libpersona( 6871): KNOX_SDCARD checking this for 1000
I/libpersona( 6871): KNOX_SDCARD not a persona
I/SELinux ( 6871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6871): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ContextImpl( 6787): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6787): Samsung link source created
D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/USER_AGENT( 6840): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/[0]UMC:AdminManager( 6840): init - start
D/TimaKeyStoreProvider( 6871): TimaSignature is unavailable
D/ActivityThread( 6871): Added TimaKeyStore provider
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
D/[0]UMC:AdminManager( 6840): loadAdmins
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5776:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/PackageManager( 1015): delete codoeFile: 
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
D/TaskPersister( 1015): removeObsoleteFile: deleting file=8_task.xml
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1015): UID=10155 Target=com.test.thalitest
D/PackageManager( 1015): result of delete: 1{949201278}
D/[0]UMC:AdminManager( 6840): init - end
D/GSLBManager( 6840): migrateStoredUrlFromOldPref
V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is removed.
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener( 6871): Received: android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 6871): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/GSLBManager( 6840): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 6840): deactivateUMCAdminIfNotRequired : -1
E/Zygote  ( 6889): MountEmulatedStorage()
E/Zygote  ( 6889): v2
I/libpersona( 6889): KNOX_SDCARD checking this for 1000
I/libpersona( 6889): KNOX_SDCARD not a persona
E/[0]UMC:Utils( 6840): Admin not found in package com.samsung.knoxpb.mdm
D/AndroidRuntime( 6759): Shutting down VM
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/[0]UMC:Utils( 6840): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
I/SELinux ( 6889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/[0]UMC:UMCAdmin( 6840): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 6840): isContainer : 0
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 6871): Enter Oncreate
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/AcmsServiceMonitor( 6871): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6871): creating AcmsCore
D/AcmsCore( 6871): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6871): AcmsCore
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/[0]UMC:UMCAdmin( 6840): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 6840): isContainer : 0
D/[0]UMC:UMCAdmin( 6840): deactivateUMCAdmin - UMC App Admin deactivated
D/AcmsCore( 6871): init
D/AcmsCore( 6871): Looper handler is not null
D/AcmsCore( 6871): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6871): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6871): Incrementing - Counter value: 1
D/AcmsCore( 6871): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6871): onStartCommand
D/AcmsService( 6871): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6871): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6871): Incrementing - Counter value: 2
D/AcmsService( 6871): Incremented Counter Value : onStartCommand
D/TimaKeyStoreProvider( 6889): TimaSignature is unavailable
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6889): Added TimaKeyStore provider
D/ActivityThread( 6871): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsCertificateMngr( 6871): AcmsCertificateMngr
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
D/AcmsRevocationMngr( 6871): AcmsRevocationMngr
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider( 6787): getAllContactInfoList Start
D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest

```
