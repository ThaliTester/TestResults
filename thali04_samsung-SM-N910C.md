#### Test 61703351436c7c0_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
--------- beginning of main
E/CscReceiver( 3979): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 3979): Recieve Sim State Changed : ABSENT
I/splitIntent( 3527): Split this intent : android.intent.action.SIM_STATE_CHANGED !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10 divideNum= 2 r.nextReceiver= 1 receivers.size=12
I/splitIntent( 3527): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=3979, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/WifiApBroadcastReceiver( 7690): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 9184): MountEmulatedStorage()
I/libpersona( 9184): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9184): v2
I/libpersona( 9184): KNOX_SDCARD not a persona
I/SELinux ( 9184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9184): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=9184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9199): MountEmulatedStorage()
E/Zygote  ( 9199): v2
I/libpersona( 9199): KNOX_SDCARD checking this for 1000
I/libpersona( 9199): KNOX_SDCARD not a persona
I/SELinux ( 9199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=9199 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 9184): TimaSignature is unavailable
V/AlarmManager( 3527): waitForAlarm result :4
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 9184): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 9199): TimaSignature is unavailable
D/ActivityThread( 9199): Added TimaKeyStore provider
E/Zygote  ( 9214): MountEmulatedStorage()
I/libpersona( 9214): KNOX_SDCARD checking this for 10017
E/Zygote  ( 9214): v2
I/libpersona( 9214): KNOX_SDCARD not a persona
I/SELinux ( 9214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=9214 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 9214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9214): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 3527): name = internet_call_settings_visibility
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1001
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/BootupListener( 3979): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 889us total 13.310ms
D/Finsky  ( 9045): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/TimaKeyStoreProvider( 9214): TimaSignature is unavailable
D/ActivityThread( 9214): Added TimaKeyStore provider
D/ResourcesManager( 9199): creating new AssetManager and set to /system/app/SilentLog/SilentLog.apk
D/ResourcesManager( 9184): creating new AssetManager and set to /system/app/MobileTrackerEngineTwo/MobileTrackerEngineTwo.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 501us total 10.878ms
V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 9214): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 389us total 11.033ms
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 8052): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
E/Zygote  ( 9231): MountEmulatedStorage()
E/Zygote  ( 9231): v2
I/libpersona( 9231): KNOX_SDCARD checking this for 1000
I/libpersona( 9231): KNOX_SDCARD not a persona
I/SELinux ( 9231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=9231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/StatusChecker( 9184): onReceive : android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiver( 8464): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 9231): TimaSignature is unavailable
D/ActivityThread( 9231): Added TimaKeyStore provider
E/Zygote  ( 9247): MountEmulatedStorage()
I/libpersona( 9247): KNOX_SDCARD checking this for 10156
E/Zygote  ( 9247): v2
I/libpersona( 9247): KNOX_SDCARD not a persona
I/SELinux ( 9247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/SELinux ( 9247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=9247 uid=10156 gids={50156, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 9247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Killing 8407:com.sec.android.app.SPenKeeper/u0a161 (adj 13): bgCount ##31
D/Mms/SmsReceiverService( 8464): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 8464): isDefault true
D/Mms/SmsReceiverService( 8464): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 8464): handleSIMStatus()
D/Mms/SmsReceiverService( 8464): handleSIMStatus(): SIM_STATUS = ABSENT
D/TimaKeyStoreProvider( 9247): TimaSignature is unavailable
D/ActivityThread( 9247): Added TimaKeyStore provider
D/ResourcesManager( 9231): creating new AssetManager and set to /system/app/TcpdumpService/TcpdumpService.apk
I/ActivityManager( 3527): Killing 8423:com.sec.android.app.videoplayer/u0a56 (adj 13): bgCount ##31
D/ResourcesManager( 9247): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 9247): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9247): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9247): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 3527): Killing 8511:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
I/System.out( 9045): Thread-1132(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 9045): Thread-1132(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 9045): Thread-1132(ApacheHTTPLog):isShipBuild true
I/System.out( 9045): Thread-1132(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 10031
I/System.out( 9045): Thread-1132 calls detatch()
W/Finsky  ( 9045): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 9045): Thread-1133 calls detatch()
I/FaceInterface( 8569): startFaceScan() : going on
D/FaceInterface( 8569): startFaceScan() is called.
D/ContentApp( 3717): startScan() is called.
D/FaceValue( 3717): mSleepTime: 800
D/FaceValue( 3717): mMaxThreadNum: 2
V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ContentApp( 3717): startScan() is end.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ContentApp( 3717): face_restore FINISHED_TYPE: 3
D/FaceScanner( 3717): isNeedToRestore : start
E/Zygote  ( 9269): MountEmulatedStorage()
E/Zygote  ( 9269): v2
I/libpersona( 9269): KNOX_SDCARD checking this for 10014
I/libpersona( 9269): KNOX_SDCARD not a persona
I/SELinux ( 9269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=9269 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 9269): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/VerificationLog( 9247): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
E/OperatorBookmarksSIMReceiver( 9247): onReceive runs..android.intent.action.SIM_STATE_CHANGED
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 9269): TimaSignature is unavailable
D/ActivityThread( 9269): Added TimaKeyStore provider
E/Zygote  ( 9286): MountEmulatedStorage()
I/libpersona( 9286): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9286): v2
I/libpersona( 9286): KNOX_SDCARD not a persona
I/SELinux ( 9286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=9286 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9286): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Killing 8591:com.sec.smartcard.manager/u0a187 (adj 13): bgCount ##31
D/ResourcesManager( 9269): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider( 9286): TimaSignature is unavailable
D/ActivityThread( 9286): Added TimaKeyStore provider
W/ResourcesManager( 9269): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9269): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/System.out( 9045): Thread-1132 calls detatch()
W/Finsky  ( 9045): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ResourcesManager( 9286): creating new AssetManager and set to /system/app/SecSetupWizard2013/SecSetupWizard2013.apk
I/splitIntent( 3527): Queue : backgroundsplit_1 intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 3527): Killing 8496:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##31
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/FaceInterface( 8569): startFaceScan() : going on
D/FaceInterface( 8569): startFaceScan() is called.
D/ContentApp( 3717): startScan() is called.
D/ContentApp( 3717): startScan() is end.
D/ContentApp( 3717): face_restore FINISHED_TYPE: 3
D/FaceScanner( 3717): isNeedToRestore : start
I/MultiDex( 9269): VM with version 2.1.0 has multidex support
I/MultiDex( 9269): install
I/MultiDex( 9269): VM has multidex support, MultiDex support library is disabled.
D/MediaScannerReceiver( 3717): action: android.intent.action.MTP_FILE_SCAN
V/JNIHelp ( 9269): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9306): MountEmulatedStorage()
I/libpersona( 9306): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9306): v2
I/libpersona( 9306): KNOX_SDCARD not a persona
I/SELinux ( 9306): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9306): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9306): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=9306 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 9306): TimaSignature is unavailable
D/ActivityThread( 9306): Added TimaKeyStore provider
W/ActivityThread( 9269): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9269): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2006f24: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9269): Installed default security provider GmsCore_OpenSSL
D/ResourcesManager( 9306): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
D/ChimeraCfgMgr( 9269): Reading stored module config
D/ChimeraCfgMgr( 9269): Loading module com.google.android.gms.car from APK com.google.android.gms
E/MTPRx   ( 9306): In MtpReceiverandroid.hardware.usb.action.USB_STATE
D/SecContentProvider2( 3527): uri = 14 selection = getSealedState
D/SecContentProvider2( 3527): mCursor = null
D/SecContentProvider2( 3527): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 3527): mCursor = null
V/MTPRx   ( 9306): sealedState: false
V/MTPRx   ( 9306): sealedUsbMassStorageState: false
E/MTPRx   ( 9306): check value of boot_completed is1
E/MTPRx   ( 9306): check booting is completed_sys.boot_completed
E/MTPRx   ( 9306): Sd-Card path/storage/extSdCard
E/MTPRx   ( 9306): Status for mount/Unmount :removed
E/MTPRx   ( 9306): SDcard is not available
W/MTPRx   ( 9306): value of connected istrue
W/MTPRx   ( 9306): value of configured istrue
W/MTPRx   ( 9306): value of mtpEnabled isfalse
W/MTPRx   ( 9306): value of ptpEnabled istrue
E/MTPRx   ( 9306): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 9306): mFirstTime: false
D/        ( 9306): MTP: reading debug level property
E/MTPJNIInterface( 9306): Getting CryptionKey from JAVA
E/MTPRx   ( 9306): currentUserId is 0
D/CAR.SERVICE( 9269): Connecting to CarCallService...
E/MTPRx   ( 9306): Start observing USB_STATE_MATCH 
E/MTPRx   ( 9306): usbMode is 0200
E/MTPRx   ( 9306): is_Privatemode is NOT 1
D/SettingsProvider( 3527): name = mtp_usb_conditions_met
D/SecContentProvider( 3527): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 9306): sending PTP_ICON_ENABLED to stack 
D/SettingsProvider( 3527): name = mtp_running_status
I/art     ( 9269): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9269): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/SettingsProvider( 3527): name = mtp_usb_conditions_met
E/MTPRx   ( 9306): else part ... so first time!!!
E/MTPPlaObsrvr( 9306): inside setContext()
E/MTPPlaObsrvr( 9306):  inside createplafiles
D/CAR.SERVICE( 9269): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 9269): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 9269): Creating a new PhoneAdapter instance
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/CAR.TEL.PhoneAdapter( 9269): setListener: com.google.android.gms.car.dn@3101d043
W/ActivityManager( 3527): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/MediaScannerService( 3717): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
E/MTPPlaObsrvr( 9306): playlist count is0
E/MTPPlaObsrvr( 9306):  inside try branch createplafiles
W/ActivityManager( 3527): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
E/MTPPlaObsrvr( 9306):  inside deleteing plas createplafiles
D/CAR.TEL.PhoneAdapter( 9269): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 9269): Starting CarCallService with initial phone null
E/MTPPlaObsrvr( 9306): Inside registerContentObserver
E/MtpAdbObserver( 9306): inside setContext()
E/MtpAdbObserver( 9306): Inside registerContentObserver
W/Settings( 9306): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/NativeLibraryUtils( 9269): Install completed successfully. count=14 extracted=0
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 3717): savePlaylistTableInBulkDeleter finished
D/SettingsProvider( 3527): name = mtp_running_status
D/SettingsProvider( 3527): name = mtp_usb_conditions_met
E/MtpService( 9306): onCreate.
E/MtpService( 9306): < MTP > Registering BroadCast receiver :::::
D/MediaScanner( 3717): Prescan. DB items number : 62 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/MtpService( 9306): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 9306): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
D/MtpService( 3717): updating state; isCurrentUser=true, mMtpLocked=false
E/MtpService( 9306): onStartCommand.
W/MTPRx   ( 9306): calling native method
E/MTPJNIInterface( 9306): < MTP > Registering BroadCast receiver :::::
E/MtpService( 9306): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 9306): < MTP > Registering BroadCast receiver :::::::
E/MTPJNIInterface( 9306): noti = 11
V/MediaScanner( 3717): processDirectory :  /storage/emulated/0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 3717): Skipping:
D/MediaScanner( 3717): 7klwibgf7fvntblfd7(75ebcf7
D/MediaScanner( 3717): Skipping:
D/MediaScanner( 3717): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
E/Zygote  ( 9333): MountEmulatedStorage()
I/libpersona( 9333): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9333): v2
I/libpersona( 9333): KNOX_SDCARD not a persona
I/SELinux ( 9333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=9333 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/MtpService( 9306): onStartCommand.
W/MTPRx   ( 9306): calling native method
E/MTPRx   ( 9306): Checking the driver time out
E/MTPJNIInterface( 9306): noti = 2
D/        ( 9306): deleting sockets before message queue initialization
E/MtpService( 9306): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/        ( 9306): event handler thread is created, so set the flag
V/MediaScanner( 3717): processDirectory :  /storage/extSdCard
W/MediaScanner( 3717): Error opening directory, reason : Permission denied.
W/MediaScanner( 3717): 7klwibgf7fxlKdCbid7
E/MTPRx   ( 9306): called native method
E/MTPJNIInterface( 9306): setting Media scanner status0
E/MTPJNIInterface( 9306): After setting Media scanner status0
W/MTPRx   ( 9306): notification from stack 1
E/        ( 9306): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 9306): Getting media scanner status0
E/MTPJNIInterface( 9306): DeviceName is Note4-1
V/MediaScanner( 3717):  prescan time: 28ms (DB items: 62)
V/MediaScanner( 3717):     scan time: 28ms (Caching mode: true), (makeEntry time: 21ms ~75%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 3717): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 3717):    total time: 59ms
V/MediaScanner( 3717): checked files: 19  directories : 36  (I: 0, U: 0)
E/MTPJNIInterface( 9306): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 3717): !@done scanning volume external
D/TimaKeyStoreProvider( 9333): TimaSignature is unavailable
D/ActivityThread( 9333): Added TimaKeyStore provider
D/ResourcesManager( 9333): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
I/iu.UploadsManager( 4494): End new media; added: 0, uploading: 0, time: 84 ms
I/art     ( 3527): Explicit concurrent mark sweep GC freed 73039(4MB) AllocSpace objects, 12(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.480ms total 100.844ms
D/TMNetworkReceiver( 9333): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() Exit 
D/TMNetworkReceiver( 9333): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
D/TMSLogRemovalReceiver( 9333): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 9333): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 9333): TMLogRemovalReceiver.onReceive() Exit
D/CAR.SERVICE( 9269): Package validated; name: com.android.vending
V/Finsky  ( 9045): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AndroidRuntime( 9353): 
D/AndroidRuntime( 9353): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9353): CheckJNI is OFF
D/AndroidRuntime( 9353): readGMSProperty: start
D/AndroidRuntime( 9353): readGMSProperty: already setted!!
D/AndroidRuntime( 9353): readGMSProperty: end
D/AndroidRuntime( 9353): addProductProperty: start
V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 9045): Thread-1133 calls detatch()
W/Finsky  ( 9045): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 9045): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager( 3527): waitForAlarm result :4
D/Finsky  ( 9045): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
I/ActivityManager( 3527): Waited long enough for: ServiceRecord{201c3efb u0 com.samsung.hs20settings/.WifiHs20UtilityService}
D/DeviceConnectionService( 4306): client connected with version: 8296000
D/Finsky  ( 9045): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 9045): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager( 3527): Killing 8569:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
I/ActivityManager( 3527): Killing 8548:com.sec.android.app.music:service/u0a44 (adj 13): bgCount ##32
E/AffinityControl( 9353): AffinityControl: registerfunction enter
D/AndroidRuntime( 9353): Calling main entry com.android.commands.am.Am
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/PersonaManagerService( 3527): inState():  stateMachine is null !!
I/PersonaManagerService( 3527): PersonaId don't exist
I/ActivityManager( 3527): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3527): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService( 3527): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3527): mDVFSHelper.acquire()
D/FocusedStackFrame( 3527): Set to : 0
E/libEGL  ( 4000): call to OpenGL ES API with no current context (logged once per thread)
D/Launcher.HomeView( 4000): onPause
D/AndroidRuntime( 9353): Shutting down VM
D/Launcher( 4000): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 2850): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9366): MountEmulatedStorage()
I/libpersona( 9366): KNOX_SDCARD checking this for 10687
E/Zygote  ( 9366): v2
I/libpersona( 9366): KNOX_SDCARD not a persona
I/SELinux ( 9366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9366): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9366 uid=10687 gids={50687, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/MicrophoneInputStream( 4048): mic_close gfk@338a4f84
D/TimaKeyStoreProvider( 9366): TimaSignature is unavailable
D/ActivityThread( 9366): Added TimaKeyStore provider
V/ActivityThread( 4000): updateVisibility : ActivityRecord{600749 token=android.os.BinderProxy@3313a52d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager( 3527): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/Launcher.HomeView( 4000): onStop
V/ActivityThread( 4000): updateVisibility : ActivityRecord{600749 token=android.os.BinderProxy@3313a52d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 9366): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/AudioPolicyManager( 2855): stopInput() input 16
V/AudioPolicyManager( 2855): releaseInput() 16
V/AudioPolicyManager( 2855): closeInput(16)
I/HotwordRecognitionRnr( 4048): Stopping hotword detection.
D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
I/HotwordRecognitionRnr( 4048): Hotword detection finished
I/AudioHardwareTinyALSA( 2855): Close mHandle:b00a9600
I/AudioHardwareTinyALSA( 2855): closeInputStream +
D/TinyUCM ( 2855): Disable Input dev(0x80000004)
D/TinyUCM ( 2855): set channel: None
D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
V/AudioPolicyManager( 2855): releaseInput() exit
D/Launcher( 4000): onTrimMemory. Level: 20
I/GAV2    ( 8756): Thread[GAThread,5,main]: No campaign data found.
I/WebViewFactory( 9366): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 9366): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 9366): Loading: webviewchromium
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/LibraryLoader( 9366): Time to load native libraries: 4 ms (timestamps 8681-8685)
I/LibraryLoader( 9366): Expected native library version number "",actual native library version number ""
E/MTPJNIInterface( 9306): Status for mount/Unmount :removed
E/MTPJNIInterface( 9306): SDcard is not available
E/        ( 9306): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
V/WebViewChromiumFactoryProvider( 9366): Binding Chromium to main looper Looper (main, tid 1) {3376a30b}
I/LibraryLoader( 9366): Expected native library version number "",actual native library version number ""
I/chromium( 9366): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/MTPJNIInterface( 9306): Status for mount/Unmount :removed
E/MTPJNIInterface( 9306): SDcard is not available
E/SQLiteLog( 9306): (21) API call with NULL database connection pointer
E/SQLiteLog( 9306): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 9306): (21) API call with NULL database connection pointer
E/SQLiteLog( 9306): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9306): (21) API call with NULL database connection pointer
E/SQLiteLog( 9306): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9306): (21) API call with NULL database connection pointer
E/SQLiteLog( 9306): (21) misuse at line 105958 of [9491ba7d73]
W/MTPRx   ( 9306): notification from stack 2
D/        ( 9306): [mtp_init_device] Library open with 32 bits.
D/        ( 9306): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 9306): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 9306): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 9306):  [sua_support_present:1277] returning false 
D/        ( 9306): *****Starting mtp_io()
W/MTPRx   ( 9306): notification from stack 3
D/        ( 9306): [mtp_start_io] source_thread Creation 
D/        ( 9306): [mtp_start_io] sink_thread Creation 
D/        ( 9306): [mtp_start_io:368] sink thread created so set th_sink
I/BrowserStartupController( 9366): Initializing chromium process, renderers=0
W/art     ( 9366): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 9366): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 9366): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 9366): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 9366): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 9366): 884143592: getState() :  mService = null. Returning STATE_OFF
,D/Widget  ( 8368): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 8368): widgetUpdate 5
D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/Widget  ( 8368): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,I/SettingSearch/SearchIntentReceiver( 7690): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 7690): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 7690): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 7690): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 7690): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/SQLiteLog( 8668): (284) automatic index on view_events(_id)
,W/chromium( 9366): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 9366): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/CalendarAlarmManager( 8668): sys current time:1457533327775
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/CalendarAlarmManager( 8668): reminder amount:0
,W/art     ( 9366): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 9366): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 9428): MountEmulatedStorage()
E/Zygote  ( 9428): v2
I/libpersona( 9428): KNOX_SDCARD checking this for 1000
I/libpersona( 9428): KNOX_SDCARD not a persona
,I/SELinux ( 9428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/SystemWebViewEngine( 9366): CordovaWebView is running on device made by: samsung
,I/SELinux ( 9428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=9428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/art     ( 9366): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 9366): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 3527): Killing 8438:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9428): TimaSignature is unavailable
,D/ActivityThread( 9428): Added TimaKeyStore provider
,I/SettingSearch/SettingsSearchManager( 7690): Infomation -> numtitleinfo : 0 numSearchinfo : 367
,D/Activity( 9366): performCreate Call secproduct feature valuefalse
D/Activity( 9366): performCreate Call debug elastic valuetrue
,D/ResourcesManager( 9428): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/OpenGLRenderer( 9366): Render dirty regions requested: true
,D/ActivityManager( 3527): post active user change for 0
D/KnoxTimeoutHandler( 3527): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3527): handleActiveUserChange for user 0
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 2850): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 9366): Initialized EGL, version 1.4
,I/DIAGMON_AGENT( 9428): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/OpenGLRenderer( 9366): HWUI protection enabled for context ,  &this =0xaf745060 ,&mEglDisplay = 1 , &mEglConfig = -1278959344 
,D/OpenGLRenderer( 9366): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 9366): Enabling debug mode 0
I/SettingSearch/SettingsSearchManager( 7690):  Infomation -> getItem size : 367
D/mali_winsys( 9366): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/InputMethodManagerService( 3527): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3527): Displayed com.example.hello/.MainActivity: +402ms
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 9366): Timeline: Activity_idle id: android.os.BinderProxy@2f9747ce time:38968
,I/DIAGMON_AGENT( 9428): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 9428): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 9428): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 3527): Killing 8260:com.sec.android.app.popupuireceiver/1000 (adj 13): bgCount ##31
,I/DBG_DM  ( 5941): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,D/LocationWidgetUtils( 8633): getUpcommingInstances() start: 1457533327988, end: 1458082799999
D/LocationWidgetUtils( 8633): getUpcommingInstances() DB begin time >= start:1457533327988, DB begin time <= end:1458082799999
,I/chromium( 9366): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 9366): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/BluetoothManager( 8841): getConnectedDevices
,D/JsMessageQueue( 9366): Set native->JS mode to OnlineEventsBridgeMode
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8841): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8841): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8841): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 8841): getConnectedDevices
,I/SurfaceFlinger( 2850): id=8 Removed Mauncher (4/9)
,I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/9)
D/BluetoothManager( 8841): getConnectedDevices
,I/chromium( 9366): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 9366): 
,D/BluetoothManager( 8841): getConnectedDevices
,D/BluetoothManager( 8841): getConnectedDevices
,D/BluetoothManager( 8841): getConnectedDevices
,D/BluetoothManager( 8841): getConnectedDevices
,D/BluetoothManager( 8841): getConnectedDevices
D/BluetoothManager( 8841): getConnectedDevices
,D/jxcore_app_log( 9366): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,I/SurfaceFlinger( 2850): id=10 Removed iello (7/8)
,I/SurfaceFlinger( 2850): id=10 Removed iello (-2/8)
,W/jxcore-log( 9366): Initializing JXcore engine
W/jxcore-log( 9366): JXcore engine is ready
,D/PowerManagerService( 3527): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3527): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3527): [s] DisplayPowerCallbacks : onStateChanged()
D/RampAnimator( 3527): mAnimationCallback timeDelta calculate error!! -4.2548E-5
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/lights  ( 3527): lcd : 1 +
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SettingSearch/SearchIntentReceiver( 7690): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 7690): LOCALE_CHANGED call search setting db finish!!
,E/auditd  ( 4551): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3527): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3527): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/lights  ( 3527): lcd : 1 -
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/jxcore-log( 9366): Starting JXcore engine
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LWLocationManager( 8633): getDeviceLocationId :  id = -100
D/LocationWidgetApplication( 8633): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9477): MountEmulatedStorage()
E/Zygote  ( 9477): v2
I/libpersona( 9477): KNOX_SDCARD checking this for 10035
I/libpersona( 9477): KNOX_SDCARD not a persona
,I/SELinux ( 9477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9477 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 9477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 7690): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/TimaKeyStoreProvider( 9477): TimaSignature is unavailable
,D/ActivityThread( 9477): Added TimaKeyStore provider
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/jxcore-log( 9366): Platform android
W/jxcore-log( 9366): 
W/jxcore-log( 9366): Process ARCH arm
W/jxcore-log( 9366): 
,I/SettingSearch/SearchIntentReceiver( 7690): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 7690): LOCALE_CHANGED call search setting db finish!!
,I/FeatureConfig( 9477): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/CustomFrequencyManagerService( 3527): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3527): mDVFSHelper.release()
I/Timeline( 3527): Timeline: Activity_windows_visible id: ActivityRecord{1b53cbc u0 com.example.hello/.MainActivity t27} time:39348
D/CustomFrequencyManagerService( 3527): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ResourcesManager( 9477): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/jxcore-log( 9366): JXcore Cordova bridge is ready!
I/jxcore-log( 9366): 
W/jxcore-log( 9366): JXcore engine is started
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 9477): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/ActivityManager( 3527): Killing 8741:com.samsung.android.app.powersharing/u0a149 (adj 13): bgCount ##31
,W/ResourcesManager( 9477): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 9477): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 9495): MountEmulatedStorage()
I/libpersona( 9495): KNOX_SDCARD checking this for 10050
E/Zygote  ( 9495): v2
I/libpersona( 9495): KNOX_SDCARD not a persona
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux ( 9495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=9495 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 9495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 9477): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/jxcore-log( 9366): >> samsung-SM-N910C
E/jxcore-log( 9366): 
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/jxcore-log( 9366): Total memory 2970812416
I/jxcore-log( 9366): 
W/ResourcesManager( 9477): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/jxcore-log( 9366): Free memory 74764288
I/jxcore-log( 9366): 
I/jxcore-log( 9366): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9366): 
I/jxcore-log( 9366): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9366): 
,D/TimaKeyStoreProvider( 9495): TimaSignature is unavailable
,I/jxcore-log( 9366): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log( 9366): 
,D/ActivityThread( 9495): Added TimaKeyStore provider
I/jxcore-log( 9366): Size 1440 2560
I/jxcore-log( 9366): 
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/jxcore-log( 9366): Screen Brightness 134
I/jxcore-log( 9366): 
E/jxcore-log( 9366): Dummy Error Log.
E/jxcore-log( 9366): 
,W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9495): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager( 9495): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 9495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 9495): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9477): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager( 9477): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 9477): system/finder_cp/cpdata.xml file not found
,D/PackageManager( 3527): findPreferredActivity: No PreferredActivities set
,D/NearbySource( 9495): Nearby Source Create!
,D/NearbyContext( 9495): Nearby Context Create!
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9495): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 9495): Samsung link source created
,D/ContactProvider( 9495): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/UpdateIcingCorporaServi( 4048): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9516): MountEmulatedStorage()
E/Zygote  ( 9516): v2
I/libpersona( 9516): KNOX_SDCARD checking this for 10079
I/libpersona( 9516): KNOX_SDCARD not a persona
,I/SELinux ( 9516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=9516 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 8862:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,D/ContactProvider( 9495): getAllContactInfoList End
I/syncContacts( 9495): thread: 1213, sync time = 51
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8795(374KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 891us total 12.848ms
,D/TimaKeyStoreProvider( 9516): TimaSignature is unavailable
,D/ActivityThread( 9516): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 397us total 9.936ms
,D/ResourcesManager( 9516): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 427us total 10.578ms
,D/ResourcesManager( 4494): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/FileShare-Server( 9516): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/CustomFrequencyManagerService( 3527): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  tag : ACTIVITY_RESUME_BOOSTER@6
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9532): MountEmulatedStorage()
E/Zygote  ( 9532): v2
I/libpersona( 9532): KNOX_SDCARD checking this for 1000
I/libpersona( 9532): KNOX_SDCARD not a persona
,I/SELinux ( 9532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=9532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9532): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 9007:com.sec.android.app.sns3/u0a37 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9532): TimaSignature is unavailable
,D/ActivityThread( 9532): Added TimaKeyStore provider
,D/ResourcesManager( 9532): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 9532): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9547): MountEmulatedStorage()
I/libpersona( 9547): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9547): v2
I/libpersona( 9547): KNOX_SDCARD not a persona
,I/SELinux ( 9547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=9547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9089:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9547): TimaSignature is unavailable
,D/ActivityThread( 9547): Added TimaKeyStore provider
,D/ResourcesManager( 9547): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 9547):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9562): MountEmulatedStorage()
E/Zygote  ( 9562): v2
I/libpersona( 9562): KNOX_SDCARD checking this for 10147
I/libpersona( 9562): KNOX_SDCARD not a persona
,I/SELinux ( 9562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9562 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9562): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 9111:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9562): TimaSignature is unavailable
,D/ActivityThread( 9562): Added TimaKeyStore provider
,D/ResourcesManager( 9562): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/ResourcesManager( 9562): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 4048): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/UpdateIcingCorporaServi( 4048): UpdateCorporaTask done [took 265 ms] updated apps [took 265 ms] 
,I/jxcore-log( 9366): getBuffer is called!!!!
I/jxcore-log( 9366): 
,D/PackageBroadcastService( 4494): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4494): Null package name or gms related package.  Ignoreing.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9593): MountEmulatedStorage()
I/libpersona( 9593): KNOX_SDCARD checking this for 10063
E/Zygote  ( 9593): v2
I/libpersona( 9593): KNOX_SDCARD not a persona
,I/SELinux ( 9593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SELinux ( 9593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9593 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Icing   ( 4494): updateResources: need to parse f{com.google.android.gms}
,D/TimaKeyStoreProvider( 9593): TimaSignature is unavailable
,D/ActivityThread( 9593): Added TimaKeyStore provider
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 44336(3MB) AllocSpace objects, 15(4MB) LOS objects, 24% free, 48MB/64MB, paused 1.366ms total 88.366ms
,D/ResourcesManager( 9593): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/VRSetupWizardStub/PackageIntentReceiver( 9593): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver( 9593): ACTION_PACKAGE_ADDED
,I/ActivityManager( 3527): Killing 9131:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 13): bgCount ##31
,I/HomeSyncInstallReceiver( 3962): This pkg do not need BT addr. Do nothing
,I/splitIntent( 3527): Split this intent : android.intent.action.PACKAGE_ADDED !!   mSplitNum[0]=15, mSplitNum[1]=27, mSplitNum[2]=39 divideNum= 12 r.nextReceiver= 3 receivers.size=51
,I/splitIntent( 3527): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9616): MountEmulatedStorage()
E/Zygote  ( 9616): v2
I/libpersona( 9616): KNOX_SDCARD checking this for 10101
I/libpersona( 9616): KNOX_SDCARD not a persona
,I/SELinux ( 9616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9616 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9616): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9616): TimaSignature is unavailable
E/Zygote  ( 9629): MountEmulatedStorage()
I/libpersona( 9629): KNOX_SDCARD checking this for 10010
E/Zygote  ( 9629): v2
I/libpersona( 9629): KNOX_SDCARD not a persona
,I/SELinux ( 9629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ActivityThread( 9616): Added TimaKeyStore provider
,I/SELinux ( 9629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9629): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=9629 uid=10010 gids={50010, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9629): TimaSignature is unavailable
,D/ActivityThread( 9629): Added TimaKeyStore provider
,D/ResourcesManager( 9616): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9629): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,E/Zygote  ( 9650): MountEmulatedStorage()
I/libpersona( 9650): KNOX_SDCARD checking this for 10019
E/Zygote  ( 9650): v2
I/libpersona( 9650): KNOX_SDCARD not a persona
I/SELinux ( 9650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9650): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=9650 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/PackageBroadcastService( 4494): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/Mms/FreeMessageStatusReceiver( 8464): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/TimaKeyStoreProvider( 9650): TimaSignature is unavailable
,D/ActivityThread( 9650): Added TimaKeyStore provider
,D/DocsApplication( 9616): Installing DEX configuration.
,D/Mms/FreeMessageReceiverService( 8464): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 8464): onHandleIntent: ACTION_PACKAGE_ADDED
,D/DexInstaller( 9616): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 9616): Provided clientMode=RELEASE, packageInfo=PackageInfo{3205cd0 com.google.android.apps.docs}
,D/TAG     ( 9616): onCreate()
,D/ResourcesManager( 9650): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/CrossAppStateProvider( 9616): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ChimeraCfgMgr( 4494): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4494): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4494): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4494): Module APK com.google.android.play.games already loaded
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9671): MountEmulatedStorage()
E/Zygote  ( 9671): v2
I/libpersona( 9671): KNOX_SDCARD checking this for 10053
I/libpersona( 9671): KNOX_SDCARD not a persona
,I/SELinux ( 9671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=9671 uid=10053 gids={50053, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/SELinux ( 9671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 9650): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 9650): onReceive called  PACKAGE_ADDED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9650): onReceive() : package name is not s health. Return !!!
,I/ActivityManager( 3527): Killing 9162:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/ChimeraCfgMgr( 4494): Loading module com.google.android.gms.gass from APK com.google.android.gms
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/AsyncTaskServiceImpl( 4494): Submit a task: k
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9671): TimaSignature is unavailable
,D/ActivityThread( 9671): Added TimaKeyStore provider
,E/Zygote  ( 9688): MountEmulatedStorage()
,E/Zygote  ( 9688): v2
I/libpersona( 9688): KNOX_SDCARD checking this for 1000
I/libpersona( 9688): KNOX_SDCARD not a persona
,I/SELinux ( 9688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9184:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,I/GAV3    ( 8841): Thread[GAThread,5,main]: No campaign data found.
,D/ChimeraCfgMgr( 4494): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 4494): Processing package: com.example.hello
,D/TimaKeyStoreProvider( 9688): TimaSignature is unavailable
,D/ResourcesManager( 9671): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ActivityThread( 9688): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 4494): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/ResourcesManager( 9671): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9671): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9671): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/GassUtils( 4494): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
D/k       ( 4494): Found info for package com.example.hello in db.
,D/ResourcesManager( 9688): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 9688): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9688): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9688): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 9688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9688): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9688): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  ( 9045): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9706): MountEmulatedStorage()
E/Zygote  ( 9706): v2
I/libpersona( 9706): KNOX_SDCARD checking this for 10114
I/libpersona( 9706): KNOX_SDCARD not a persona
,I/SELinux ( 9706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=9706 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 9706): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/MyFiles ( 9671): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,E/installd( 2859): system dir 0 : /system/app/
E/installd( 2859): system dir 1 : /system/priv-app/
E/installd( 2859): system dir 2 : /vendor/app/
E/installd( 2859): system dir 3 : /oem/app/
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9721): MountEmulatedStorage()
E/Zygote  ( 9721): v2
I/libpersona( 9721): KNOX_SDCARD checking this for 1000
D/TimaKeyStoreProvider( 9706): TimaSignature is unavailable
I/libpersona( 9721): KNOX_SDCARD not a persona
,I/SELinux ( 9721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ActivityThread( 9706): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=9721 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9199:com.sec.modem.settings/1000 (adj 13): bgCount ##31
,I/SELinux ( 9721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9721): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8777(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 867us total 23.287ms
,I/TactileAssist( 3527): enable value -1
I/TactileAssist( 3527): internal enable value -1
I/TactileAssist( 3527): intensity value -1
I/TactileAssist( 3527): saveAppList value true
,I/TactileAssist( 3527): List of disabled apps :
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 309us total 14.317ms
,D/PackageManager( 3527): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 439us total 9.974ms
,D/TimaKeyStoreProvider( 9721): TimaSignature is unavailable
,D/ActivityThread( 9721): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9706): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  ( 9739): MountEmulatedStorage()
E/Zygote  ( 9739): v2
I/libpersona( 9739): KNOX_SDCARD checking this for 10059
I/libpersona( 9739): KNOX_SDCARD not a persona
,I/SELinux ( 9739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9739 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 9739): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 9231:com.sec.tcpdumpservice/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9739): TimaSignature is unavailable
,D/ActivityThread( 9739): Added TimaKeyStore provider
,D/ResourcesManager( 9721): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ResourcesManager( 9739): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 9739): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Compatibility( 9739): onReceive() it will make start service
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Compatibility( 9739): onHandleIntent()
,D/Compatibility( 9739): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10687, android.intent.extra.user_handle=0}]
,D/Compatibility( 9739): found: 2
,D/Compatibility( 9739): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 9739): skipping ResolveInfo{9ef14c9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 9739): considering ResolveInfo{2f9747ce com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 9739): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 9739): enabling receiver ResolveInfo{329e86ef com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ResourcesManager( 9706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Compatibility( 9739): enabling receiver ResolveInfo{267675fc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 4048): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 9739): enabling receiver ResolveInfo{354b3485 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 9739): enabling receiver ResolveInfo{3ee412da com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl( 8725): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
,D/Compatibility( 9739): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/SSRM:n  ( 3527): SIOP:: AP = 360, PST = 346, CUR = -706
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9764): MountEmulatedStorage()
E/Zygote  ( 9764): v2
I/libpersona( 9764): KNOX_SDCARD checking this for 10039
I/libpersona( 9764): KNOX_SDCARD not a persona
,I/SELinux ( 9764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=9764 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9764): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Killing 9247:com.sec.android.app.sbrowser/u0a156 (adj 13): bgCount ##31
I/AppStateLoggerExceptionHandler( 9706): Installed uncaught exception handler for app state logging
D/AppStateLogger( 9706): Attempting to open app state logging file
I/ActivityManager( 3527): Killing 9286:com.sec.android.app.SecSetupWizard/1000 (adj 13): bgCount ##31
D/AppStateLogger( 9706): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/8ad17441-86b8-1298-3acc-d357b0305f45.txt
D/ACRA    ( 9706): ACRA is enabled for com.facebook.katana, intializing...
,D/TimaKeyStoreProvider( 9764): TimaSignature is unavailable
,D/ActivityThread( 9764): Added TimaKeyStore provider
,D/ResourcesManager( 4048): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/fb-UnpackingSoSource( 9706): locked dso store /data/data/com.facebook.katana/lib-main
,I/fb-UnpackingSoSource( 9706): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource( 9706): releasing dso store lock for /data/data/com.facebook.katana/lib-main
,V/fb-UnpackingSoSource( 9706): locked dso store /data/data/com.facebook.katana/lib-assets
,I/fb-UnpackingSoSource( 9706): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource( 9706): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource( 9706): locked dso store /data/data/com.facebook.katana/lib-xzs
I/fb-UnpackingSoSource( 9706): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource( 9706): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
,I/art     ( 9706): Thread[1,tid=9706,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,V/appstatelogger( 9706): Registered App State Logger stream with Breakpad
,V/MemoryEnlargementHack( 9706): largeHeap already enabled in manifest
V/DexLibLoader( 9706): DLL.loadAll betaBuild:false flags:0x00000004
,D/ResourcesManager( 9764): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,V/dalvik-internals( 9706): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9706): hooked signal using trap ()
V/dalvik-internals( 9706): hooked sysv_signal using trap ()
V/dalvik-internals( 9706): hooked bsd_signal using trap ()
V/dalvik-internals( 9706): hooked sigaction using jump ()
V/dalvik-internals( 9706): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9706): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9706): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader( 9706): patched ART 5.0.x miranda bug
,V/DexLibLoader( 9706): opening dex store /data/data/com.facebook.katana/dex
,V/DexLibLoader( 9706): Secondary program dex metadata: [.root_relative]
V/DexLibLoader( 9706): Secondary program dex metadata: [.locators]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader( 9706): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
,E/Zygote  ( 9785): MountEmulatedStorage()
,E/Zygote  ( 9785): v2
I/libpersona( 9785): KNOX_SDCARD checking this for 10102
I/libpersona( 9785): KNOX_SDCARD not a persona
,I/SELinux ( 9785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=9785 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager( 3527): Killing 9333:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
,I/SELinux ( 9785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9785): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/UpdateIcingCorporaServi( 4048): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,W/GAV2    ( 9616): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/DexLibLoader( 9706): read status:9 check:faceb007faceb00e
,V/DexLibLoader( 9706): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader( 9706): verified deps file
I/DexLibLoader( 9706): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader( 9706): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9706): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9706): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader( 9706): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9706): Setup multi dex took 0 ms.
V/DexLibLoader( 9706): optimization needed: no
,D/MemoryReductionHack( 9706): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
,D/TimaKeyStoreProvider( 9785): TimaSignature is unavailable
,D/ActivityThread( 9785): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SPPClientService( 9764): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9764): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 9785): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 9764): PushLog.txt file is not deleted.
D/SPPClientService( 9764): PushLog.txt file is not deleted.
D/SPPClientService( 9764): ============PushLog. stop!
,W/ResourcesManager( 9785): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 9807): MountEmulatedStorage()
E/Zygote  ( 9807): v2
I/libpersona( 9807): KNOX_SDCARD checking this for 10042
I/libpersona( 9807): KNOX_SDCARD not a persona
,I/SELinux ( 9807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=9807 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 9807): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/GMPM    ( 9706): App measurement is starting up
,E/GMPM    ( 9706): getGoogleAppId failed with status: 10
,E/GMPM    ( 9706): Uploading is not possible. App measurement disabled
,D/TimaKeyStoreProvider( 9807): TimaSignature is unavailable
,D/ActivityThread( 9807): Added TimaKeyStore provider
,D/ResourcesManager( 9807): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,E/[CarMode]( 9785): [DLApplication]-onCreate: Applicatino Started!
W/ResourcesManager( 9807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9807): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/SampleAppCoreManager( 9785): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager( 9785): mContext is not null
,I/VlingoAndroidCore( 9785): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,W/StaticBindingVerifier( 9706): Verify
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9832): MountEmulatedStorage()
E/Zygote  ( 9832): v2
I/libpersona( 9832): KNOX_SDCARD checking this for 10034
I/libpersona( 9832): KNOX_SDCARD not a persona
,I/SELinux ( 9832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=9832 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 9832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9832): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9832): TimaSignature is unavailable
,D/ActivityThread( 9832): Added TimaKeyStore provider
,W/LightSharedPreferencesImpl( 9706): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl( 9706): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9706): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl( 9706): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl( 9706): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl( 9706): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl( 9706): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl( 9706): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl( 9706): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl( 9706): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl( 9706): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl( 9706): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl( 9706): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl( 9706): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9706): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl( 9706): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl( 9706): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl( 9706): 	... 10 more
D/ResourcesManager( 9832): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/SL_DEBUG( 9807): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 9807): isLoggable:: SL_DEBUG_EXIST = false
,D/WifiService( 3527): New client listening to asynchronous messages
,I/Icing   ( 4494): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 9832): Inside WakeupProvider
,E/DatabaseUtils( 9832): Writing exception to parcel
E/DatabaseUtils( 9832): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9832): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9832): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9832): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9832): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9832): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9832): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9832): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 9785): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 9785): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9785): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9785): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9785): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9785): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9785): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 9785): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 9785): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 9785): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 9785): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err( 9785): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err( 9785): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9785): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9785): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9785): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9785): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9785): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9785): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9785): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/fb4a(:<default>):UserScope( 9706): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/DatabaseUtils( 9832): Writing exception to parcel
E/DatabaseUtils( 9832): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9832): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9832): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9832): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9832): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9832): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9832): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9832): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9832): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 9785): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/fb4a(:<default>):UserScope( 9706): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/ContextImpl( 9807): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/System.err( 9785): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9785): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9785): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9785): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9785): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9785): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9785): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 9785): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 9785): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 9785): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err( 9785): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9785): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9785): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9785): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9785): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9785): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9785): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9785): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 9785): [DLApplication]-Init Called!:false
W/[CarMode]( 9785): [CommonUtil]-=========================================
W/[CarMode]( 9785): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode]( 9785): [CommonUtil]-=========================================
E/[CarMode]( 9785): [DLApplication]-Init Started!:true
I/VlingoApplication( 9832): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/[CarModeFW]( 9785): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 9785): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW]( 9785): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW]( 9785): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW]( 9785): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 9785): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW]( 9785): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW]( 9785): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW]( 9785): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 9785): ### android.os.Looper::loop(145)
I/[CarModeFW]( 9785): ### android.app.ActivityThread::main(5944)
I/[CarModeFW]( 9785): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 9785): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 9785): ### com.android.internal.os.ZygoteInit::main(1194)
E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/fb4a(:<default>):UserScope( 9706): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/ContextImpl( 9807): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/BluetoothAdapter( 9832): 525788810: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9832): 525788810: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9832): 525788810: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 9832): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
V/Transcoder( 9807): Transcoder(0xb3c2e560)::constructor
V/Transcoder( 9807): addObitRecipient
V/TMI-JNI ( 9807): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,V/xAnalytics( 9706): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics( 9706): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics( 9706): JNI_OnLoad XAnalyticsNative complete
V/xAnalytics( 9706): tigon: 0x0 - xanalytics: 0xffffffff93814220
V/xAnalytics( 9706): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics( 9706): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     ( 9706): Attempt to remove local handle scope entry from IRT, ignoring
I/MessageDataHandler( 9785): initialize
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/[CarModeFW]( 9785): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 9785): CDH-initiazlieCaches : after sync
E/Zygote  ( 9892): MountEmulatedStorage()
E/Zygote  ( 9892): v2
I/libpersona( 9892): KNOX_SDCARD checking this for 10045
I/libpersona( 9892): KNOX_SDCARD not a persona
I/ActivityManager( 3527): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=9892 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9892): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 9785): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 9785): CDH-ContactDataHandler initiazlieCaches time : 41
,D/[CarModeFW]( 9785): CDH-initiazlieCaches : end sync
,D/TimaKeyStoreProvider( 9892): TimaSignature is unavailable
,D/ActivityThread( 9892): Added TimaKeyStore provider
,W/GAV2    ( 9616): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 3527): Killing 8368:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/BluetoothAdapter( 9785): 471499568: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9785): 471499568: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 9785): DrivingManager-initialize...
,I/SensorService( 3527): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
,I/SensorService( 3527): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3527): Skipped sensor MAX86902 because it requires permission 
I/ActivityManager( 3527): Killing 8668:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
I/SensorService( 3527): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3527): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/ResourcesManager( 9892): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/VlingoApplication( 9832): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 9832): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 9832): initQueue()
,D/ResourcesManager( 4494): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,D/Icing   ( 4494): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4494): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/SA      ( 9892): [SSP] onCreated
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9912): MountEmulatedStorage()
E/Zygote  ( 9912): v2
I/libpersona( 9912): KNOX_SDCARD checking this for 10110
I/libpersona( 9912): KNOX_SDCARD not a persona
,I/SELinux ( 9912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=9912 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9912): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 8710:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
,I/SA      ( 9892): [TPM] There is no property file
,I/SA      ( 9892): [SCU] isHaveSA() - false
,I/SA      ( 9892): [TPM] getModelProperty : null
I/SA      ( 9892): [TPM] getCSCProperty : null
,I/SA      ( 9892): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 9892): [DM] init START
,I/SA      ( 9892): [DM] This device is not a Vodafone
,I/SA      ( 9892): checkReactivationActive for LOLLIPOP
I/SA      ( 9892): checkReactivationActive for reactiveActive
I/SA      ( 9892): setSupportRL : true
,I/SA      ( 9892): [SCU] isHaveSA() - false
I/SA      ( 9892): support phone number id : false
I/SA      ( 9892): [DM] init END
,I/SA      ( 9892): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      ( 9892): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10687 extra.user_handle.:0 ]
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9912): TimaSignature is unavailable
,D/ActivityThread( 9912): Added TimaKeyStore provider
,I/MediaPlayer( 9785): Need to enable context aware info
V/MediaPlayer-JNI( 9785): native_setup
V/MediaPlayer( 9785): constructor
,E/Zygote  ( 9930): MountEmulatedStorage()
E/Zygote  ( 9930): v2
I/libpersona( 9930): KNOX_SDCARD checking this for 10046
I/libpersona( 9930): KNOX_SDCARD not a persona
,I/SELinux ( 9930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/MediaPlayer( 9785): setListener
,I/SELinux ( 9930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=9930 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 9930): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 8756:com.google.android.gm/u0a122 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9930): TimaSignature is unavailable
,D/ActivityThread( 9930): Added TimaKeyStore provider
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 23187(1526KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 1.138ms total 102.801ms
,D/ResourcesManager( 9912): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/[CarModeFW]( 9785): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW]( 9785): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 9785): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/ResourcesManager( 9930): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457533330496
D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457533330497
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457533330495
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457533330500
,W/ResourcesManager( 9930): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9930): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/[CarMode]( 9785): [DLServiceManager]-updateLocationList
D/[CarMode]( 9785): [DLServiceManager]-requestRecommendedLocationList
,W/ResourcesManager( 9930): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457533330506
,I/Icing   ( 4494): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457533330508
D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457533330508
I/Icing   ( 4494): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
D/[CarModeFW]( 9785): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,F/DLApplication( 9785): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 9785
,I/[CarMode]( 9785): [LogNotNull]-Package name is: com.here.app.maps
D/TP/SmsProvider( 3979): match 2:Elapsed time : 1.468 ms
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 9785
,I/System.out( 9832): INFO:Resource not found:/Common.properties Using default values
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 3979): match 2:Elapsed time : 6.517 ms
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/[CarModeFW]( 9785): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9785): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 36
,E/Zygote  ( 9947): MountEmulatedStorage()
E/Zygote  ( 9947): v2
I/libpersona( 9947): KNOX_SDCARD checking this for 10047
I/libpersona( 9947): KNOX_SDCARD not a persona
,I/SELinux ( 9947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=9947 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 32
,E/SELinux ( 9947): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/[CarMode]( 9785): [DLApplication]-Init End!:true
,D/[CarMode]( 9785): [TAG]-phone sound mode is: 0
V/[CarMode]( 9785): [DLApplication]-savePreviousGpsState
,D/MessageDataHandler( 9785):  getInboxList smsCursor : 48
D/[CarModeFW]( 9785): CalllogDataHandler-getCalllogList : cur len = 0
,V/[CarMode]( 9785): [DLApplication]-savePreviousGpsState: Previous state = 0
D/TP/MmsProvider( 3979): Query uri=content://mms/inbox, match=2, calling pid = 9785
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 57
,D/TP/MmsProvider( 3979): Query uri=content://mms, match=0, calling pid = 9785
,D/MessageDataHandler( 9785):  getInboxList mmsCursor : 12
,D/[CarModeFW]( 9785): ContactDataHandler-getFavoriteContactList : cur len = 0
,I/MessageDataHandler( 9785): getUnreadMessageCount :0
D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 62
,D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 54
,D/MessageDataHandler( 9785):  getInboxList mms,sms cursor join : 9
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 9785
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 1.468 ms
,D/[CarMode]( 9785): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode]( 9785): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,E/Minikin ( 9930): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/TimaKeyStoreProvider( 9947): TimaSignature is unavailable
,D/ActivityThread( 9947): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 9785
,D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 2.863 ms
,I/[CarMode]( 9785): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode]( 9785): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/MessageDataHandler( 9785):  getInboxList address cursor : 13
,I/RelayReceiver_PinBoard( 9930): onReceive... android.intent.action.PACKAGE_ADDED
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 9785
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 1.353 ms
,I/UpdateManagerReceiver( 9785): Intent : android.intent.action.PACKAGE_ADDEDWed Mar 09 15:22:10 GMT+01:00 2016
,I/RelayService_PinBoard( 9930): RelayService Started!! : android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/DialogFlow( 9785): initQueue()
,D/ResourcesManager( 9947): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 9947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  ( 9963): MountEmulatedStorage()
,E/Zygote  ( 9963): v2
I/libpersona( 9963): KNOX_SDCARD checking this for 1000
I/libpersona( 9963): KNOX_SDCARD not a persona
,I/SELinux ( 9963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=9963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 8687:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 8655:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##32
,I/CalendarProvider2( 9947): CalendarProvider2.onCreate() called
,I/ActivityManager( 3527): Killing 9428:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##33
,D/MessageDataHandler( 9785):  getInboxList thread cursor : 54
,V/fb-UnpackingSoSource( 9912): locked dso store /data/data/com.facebook.appmanager/lib-main
I/fb-UnpackingSoSource( 9912): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource( 9912): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource( 9912): locked dso store /data/data/com.facebook.appmanager/lib-assets
,I/fb-UnpackingSoSource( 9912): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource( 9912): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource( 9912): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource( 9912): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource( 9912): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    ( 9912): ACRA is enabled for com.facebook.appmanager, intializing...
,D/MessageDataHandler( 9785):  thread, addr result: 10
I/[CarModeFW]( 9785): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 157
I/[CarModeFW]( 9785): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 157
,D/TimaKeyStoreProvider( 9963): TimaSignature is unavailable
,V/DexLibLoader( 9912): DLL.loadAll betaBuild:true flags:0x00000001
,D/ActivityThread( 9963): Added TimaKeyStore provider
,V/dalvik-internals( 9912): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9912): hooked signal using trap ()
V/dalvik-internals( 9912): hooked sysv_signal using trap ()
V/dalvik-internals( 9912): hooked bsd_signal using trap ()
V/dalvik-internals( 9912): hooked sigaction using jump ()
,V/DexLibLoader( 9912): opening dex store /data/data/com.facebook.appmanager/dex
,V/DexLibLoader( 9912): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
V/DexLibLoader( 9912): read status:9 check:faceb007faceb00e
,V/DexLibLoader( 9912): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader( 9912): verified deps file
I/DexLibLoader( 9912): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader( 9912): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9912): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader( 9912): Setup multi dex took 0 ms.
V/DexLibLoader( 9912): optimization needed: no
,D/ResourcesManager( 9963): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/GMPM    ( 9912): App measurement is starting up
,E/GMPM    ( 9912): getGoogleAppId failed with status: 10
,E/GMPM    ( 9912): Uploading is not possible. App measurement disabled
,W/cn      ( 9912): Verify
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 9963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9912): 	... 10 more
,E/Zygote  ( 9998): MountEmulatedStorage()
E/Zygote  ( 9998): v2
I/libpersona( 9998): KNOX_SDCARD checking this for 10013
I/libpersona( 9998): KNOX_SDCARD not a persona
,I/SELinux ( 9998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=9998 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 9998): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/appmanager(:<default>):b( 9912): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b( 9912): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 893us total 24.186ms
,D/[CarModeFW]( 9785): LocationDataHandler-No schedules found.
D/ResourcesManager( 9963): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/FilterInstaller( 9963): installFilters
,E/FilterInstaller( 9963): There is no requred permission
,D/TimaKeyStoreProvider( 9998): TimaSignature is unavailable
,D/ActivityThread( 9998): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 627us total 19.159ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 449us total 14.027ms
,E/Zygote  (10017): MountEmulatedStorage()
I/libpersona(10017): KNOX_SDCARD checking this for 10121
E/Zygote  (10017): v2
I/libpersona(10017): KNOX_SDCARD not a persona
,I/SELinux (10017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=10017 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux (10017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 9785): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,D/AppStateLogger( 9706): Successfully dumped app state to log file
,D/TimaKeyStoreProvider(10017): TimaSignature is unavailable
,D/ActivityThread(10017): Added TimaKeyStore provider
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9998): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/Zygote  (10032): MountEmulatedStorage()
E/Zygote  (10032): v2
I/libpersona(10032): KNOX_SDCARD checking this for 10003
I/libpersona(10032): KNOX_SDCARD not a persona
,I/SELinux (10032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10032 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux (10032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10032): TimaSignature is unavailable
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/ActivityThread(10032): Added TimaKeyStore provider
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10017): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/ActivityManager( 3527): Killing 8803:com.google.android.talk/u0a125 (adj 15): bgCount ##31
,D/ResourcesManager(10032): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/PackageIntentReceiver(10017): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(10017): Not GearManger package! 
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 4494): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,D/UserAnalysis.PlaceProvider(10032): PlaceProvider onCreate()
,E/Zygote  (10050): MountEmulatedStorage()
I/libpersona(10050): KNOX_SDCARD checking this for 1000
E/Zygote  (10050): v2
I/libpersona(10050): KNOX_SDCARD not a persona
,I/SELinux (10050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 8633:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/SELinux (10050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10050): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UserAnalysis.SecureDbManager(10032): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(10032): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10032): Create SecureDbHelper
,D/TimaKeyStoreProvider(10050): TimaSignature is unavailable
,D/ActivityThread(10050): Added TimaKeyStore provider
,D/IntelligenceServiceApplication(10032): onCreate()
,I/ActivityManager( 3527): Killing 9516:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
,W/appmanager(:<default>):QuickExperimentControllerImpl( 9912): Exposure of experiment com.facebook.http.g.c@414734c occurred when no user was logged in
,I/art     ( 9912): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     ( 9912): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
D/ResourcesManager(10050): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/System.out( 9912): Thread-1326(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 9912): Thread-1326(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 9912): Thread-1326(ApacheHTTPLog):isShipBuild true
I/System.out( 9912): Thread-1326(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 10110
,I/System.out( 9912): P[5]_NetworkDispatch1 calls detatch()
,W/appmanager(:<default>):ae( 9912): Got java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname while executing fetchSessionlessGKInfo, retrying on a safe network stack
,I/System.out( 9912): P[5]_NetworkDispatch1 calls detatch()
,E/appmanager(:<default>):p( 9912): Sessionless gatekeeper fetch with SingleMethodRunner failed
E/appmanager(:<default>):p( 9912): java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname
E/appmanager(:<default>):p( 9912): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
E/appmanager(:<default>):p( 9912): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
E/appmanager(:<default>):p( 9912): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1288)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:700)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:691)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:514)
E/appmanager(:<default>):p( 9912): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:492)
E/appmanager(:<default>):p( 9912): 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:302)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:477)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.c(FbHttpRequestProcessor.java:398)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.b(FbHttpRequestProcessor.java:342)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:328)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:256)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:1183)
E/appmanager(:<default>):p( 9912): 	at com.facebook.http.common.ai.run(FbHttpRequestProcessor.java:1204)
E/appmanager(:<default>):p( 9912): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p( 9912): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
E/appmanager(:<default>):p( 9912): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p( 9912): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/appmanager(:<default>):p( 9912): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
E/appmanager(:<default>):p( 9912): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/appmanager(:<default>):p( 9912): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/appmanager(:<default>):p( 9912): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
E/appmanager(:<default>):p( 9912): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 3527): Killing 9532:com.sec.knox.bridge/1000 (adj 15): bgCount ##31
,D/[CarModeFW]( 9785): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 9785): MyPlaceProvider-=============
D/[CarModeFW]( 9785): MyPlaceProvider-=============
D/[CarModeFW]( 9785): MyPlaceProvider-=============
D/[CarModeFW]( 9785): MyPlaceProvider-=============
,D/[CarModeFW]( 9785): MyPlaceProvider-=============
D/[CarModeFW]( 9785): MyPlaceProvider-=============
D/[CarModeFW]( 9785): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 9785): MyPlaceProvider-==============
D/[CarModeFW]( 9785): MyPlaceProvider-==============
D/[CarModeFW]( 9785): MyPlaceProvider-==============
D/[CarModeFW]( 9785): MyPlaceProvider-==============
D/[CarModeFW]( 9785): MyPlaceProvider-==============
,D/[CarModeFW]( 9785): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457533331049 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW]( 9785): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList( 9785): loadLocationDestinationList is null
D/[CarModeFW]( 9785): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 545
,I/Icing   ( 4494): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10076): MountEmulatedStorage()
E/Zygote  (10076): v2
I/libpersona(10076): KNOX_SDCARD checking this for 1000
I/libpersona(10076): KNOX_SDCARD not a persona
,I/SELinux (10076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10076 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10076): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 9547:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10076): TimaSignature is unavailable
,D/ActivityThread(10076): Added TimaKeyStore provider
,D/ResourcesManager(10076): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener(10076): Received: android.intent.action.PACKAGE_ADDED
,I/ActivityManager( 3527): Killing 4182:com.google.process.gapps/u0a14 (adj 15): bgCount ##31
W/ContextImpl(10076): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService(10076): Enter Oncreate
D/AcmsServiceMonitor(10076): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10076): creating AcmsCore
D/AcmsCore(10076): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10076): AcmsCore
,D/AcmsCore(10076): init
D/AcmsCore(10076): Looper handler is not null
D/AcmsCore(10076): Post to AcmsCoreHandler
,D/AcmsCertificateMngr(10076): AcmsCertificateMngr
,D/AcmsRevocationMngr(10076): AcmsRevocationMngr
,D/AcmsServiceMonitor(10076): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor(10076): Incrementing - Counter value: 1
D/AcmsCore(10076): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService(10076): onStartCommand
D/ActivityThread(10076): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsService(10076): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10076): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10076): Incrementing - Counter value: 2
D/AcmsService(10076): Incremented Counter Value : onStartCommand
,D/AcmsService(10076): Inside handle Intent
D/AcmsService(10076): App added - package name: com.example.hello
D/AcmsCore(10076): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10076): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10076): Incrementing - Counter value: 3
D/AcmsCore(10076): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10076): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10076): Decrementing - Counter value: 2
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10101): MountEmulatedStorage()
E/Zygote  (10101): v2
I/libpersona(10101): KNOX_SDCARD checking this for 10160
I/libpersona(10101): KNOX_SDCARD not a persona
,I/SELinux (10101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10101 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,E/SELinux (10101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10101): TimaSignature is unavailable
,D/ActivityThread(10101): Added TimaKeyStore provider
,D/ResourcesManager(10101): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(10101): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10101): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,V/Common  (10101): getScreenSize 1440 2560
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/JAM     (10101): Load The ApaService JNI
,I/JAM     (10101): version: ProfessionalAudio_v1.0.b5
I/JAM     (10101): Try v1.0.b3 ...
,D/Spen    (10101): SpenSdk version level = 55
D/Spen    (10101): SpenSdk jar version = 3.0.243
,D/Spen    (10101): SpenSdk apk version = 3.0.235
D/Spen    (10101): Server UPDATE Check
,W/linker  (10101): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
I/libpersona(10119): KNOX_SDCARD checking this for 10160
E/Zygote  (10119): MountEmulatedStorage()
I/libpersona(10119): KNOX_SDCARD not a persona
E/Zygote  (10119): v2
D/SPenError(10101): JNI_OnLoad
I/SELinux (10119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/JNI_Bitmap(10101): Init .. Done
D/SPenSpiDecoder(10101): JNI_OnLoad .. Done
D/SPenError(10101): JNI_OnLoad Success
,D/PluginManager(10101): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(10101): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(10101): JNI_OnLoad
,I/ActivityManager( 3527): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=10119 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/Init_SPenSdk_Jni(10101): AndroidSDK: 21
D/Init_SPenSdk_Jni(10101): JNI_OnLoad .. Done
I/SELinux (10119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Waited long enough for: ServiceRecord{38ad0276 u0 com.sec.android.service.sm/.service.SecurityManagerService}
E/SELinux (10119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Model_ObjectBase_Jni(10101): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(10101): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(10101): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(10101): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(10101): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(10101): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(10101): check build type eng[0]
D/Model_NoteDoc_Jni(10101): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(10101): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(10101): JNI_OnLoad .. Done
D/Model   (10101): OnLoad class Done
,D/spe_log (10101): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(10101): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10101): Canvas JNI_OnLoad enter!!
,D/SPen_Library(10101): Canvas JNI_OnLoad Success
D/SPen_Library(10101): TextView JNI_OnLoad enter!!
,D/SPen_Library(10101): TextView JNI_OnLoad Success
D/SPen_Library(10101): Text JNI_OnLoad enter!!
D/SPen_Library(10101): Text JNI_OnLoad Success
D/SPen_Library(10101): FontManager JNI_OnLoad enter!!
D/SPen_Library(10101): FontManager JNI_OnLoad Success
D/SPen_Library(10101): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10101): CapturePage JNI_OnLoad Success
D/SPen_Library(10101): Multi JNI_OnLoad enter!!
,D/SPen_Library(10101): Multi JNI_OnLoad Success
D/SPen_Library(10101): Draw Engine JNI_OnLoad Success
,D/SPen_Library(10101): Brush JNI_OnLoad enter!!
,D/SPen_Library(10101): Brush JNI_OnLoad Success
,D/SPen_Library(10101): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(10101): ChineseBrush JNI_OnLoad Success
,D/TimaKeyStoreProvider(10119): TimaSignature is unavailable
,D/SPen_Library(10101): InkPen JNI_OnLoad enter!!
D/SPen_Library(10101): InkPen JNI_OnLoad Success
D/ActivityThread(10119): Added TimaKeyStore provider
,D/SPen_Library(10101): Marker JNI_OnLoad enter!!
,D/SPen_Library(10101): Marker JNI_OnLoad Success
,D/SPen_Library(10101): Pencil JNI_OnLoad enter!!
,D/SPen_Library(10101): Pencil JNI_OnLoad Success
,D/SPen_Library(10101): NativePen JNI_OnLoad enter!!
D/SPen_Library(10101): NativePen JNI_OnLoad Success
,D/SPen_Library(10101): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(10101): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(10101): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(10101): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(10101): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(10101): MagicPen JNI_OnLoad Success
,D/SPen_Library(10101): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(10101): ObliquePen JNI_OnLoad Success
,D/SPen_Library(10101): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(10101): FountainPen JNI_OnLoad Success
D/Spen    (10101): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10101): SPenSdk_init2
D/Init_SPenSdk(10101): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(10101): Total S Pen SDK Directory Size = 0
D/Spen    (10101): initialize complete
,W/linker  (10101): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager(10119): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(10101): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,W/ResourcesManager(10119): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10119): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10119): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10136): MountEmulatedStorage()
,E/Zygote  (10136): v2
I/libpersona(10136): KNOX_SDCARD checking this for 10183
I/libpersona(10136): KNOX_SDCARD not a persona
,I/SELinux (10136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10136 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9593:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
,E/SELinux (10136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10136): TimaSignature is unavailable
,D/ActivityThread(10136): Added TimaKeyStore provider
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9912): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9912): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/SNoteProvider(10119): onCreate enableSnoteSync = true
,D/ResourcesManager(10136): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/SNoteProvider(10119): ===query=== 
,V/Common  (10119): getScreenSize 1440 2560
,E/SQLiteLog(10136): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl( 9912): Exposure of experiment com.facebook.imagepipeline.m.d@25c60ae6 occurred when no user was logged in
,W/appmanager(:<default>):aa( 9912): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,W/appmanager(:<default>):aa( 9912): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
E/Zygote  (10155): MountEmulatedStorage()
I/libpersona(10155): KNOX_SDCARD checking this for 10190
E/Zygote  (10155): v2
I/libpersona(10155): KNOX_SDCARD not a persona
,I/SELinux (10155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10155 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (10155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 9629:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/SNoteProvider(10119): ===query=== 
,D/TimaKeyStoreProvider(10155): TimaSignature is unavailable
,D/ActivityThread(10155): Added TimaKeyStore provider
,D/ResourcesManager(10155): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/art     ( 9912): Explicit concurrent mark sweep GC freed 49394(2MB) AllocSpace objects, 5(80KB) LOS objects, 22% free, 27MB/35MB, paused 558us total 34.108ms
,W/appmanager(:<default>):m( 9912): No feature status reporters found; is this dead code?
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10155): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10155): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(10155): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10155): Widget is not attached.
,I/splitIntent( 3527): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3527): Killing 9214:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10174): MountEmulatedStorage()
E/Zygote  (10174): v2
I/libpersona(10174): KNOX_SDCARD checking this for 10135
I/libpersona(10174): KNOX_SDCARD not a persona
,I/SELinux (10174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=10174 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10174): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10174): TimaSignature is unavailable
,D/ActivityThread(10174): Added TimaKeyStore provider
,D/ResourcesManager(10174): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MusicStore(10174): Database version: 104
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 9947): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/Zygote  (10196): MountEmulatedStorage()
E/Zygote  (10196): v2
I/libpersona(10196): KNOX_SDCARD checking this for 10014
I/libpersona(10196): KNOX_SDCARD not a persona
,I/SELinux (10196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=10196 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9495:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10196): TimaSignature is unavailable
,D/ActivityThread(10196): Added TimaKeyStore provider
,D/ResourcesManager(10196): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GservicesProvider(10196): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient(10196): GMS http client unavailable, use old client
,D/ResourcesManager(10196): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/GoogleHttpClient(10196): GMS http client unavailable, use old client
,D/ResourcesManager(10174): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(10174): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10174): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10174): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityThread(10174): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10174): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b2c3aaf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10174): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10174): GMSCore installation verified
,I/ConfigStore(10174): Config Database version: 1
,E/Watchdog( 3527): !@Sync 1
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/SettingsProvider( 3527): name = audio_safe_volume_state
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3527): getStreamVolume 3 index 0
,I/MediaRouter(10174): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 3527): Killing 8464:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10223): MountEmulatedStorage()
E/Zygote  (10223): v2
I/libpersona(10223): KNOX_SDCARD checking this for 10022
I/libpersona(10223): KNOX_SDCARD not a persona
,I/SELinux (10223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10223 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10223): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 271us total 9.799ms
,D/TimaKeyStoreProvider(10223): TimaSignature is unavailable
,D/ActivityThread(10223): Added TimaKeyStore provider
,I/MusicLeanback(10174): Stop autocaching.
,I/MusicLeanback(10174): Stop autocaching.
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 288us total 7.995ms
,I/MusicLeanback(10174): Stop autocaching.
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
I/MusicLeanback(10174): Stop autocaching.
,W/ResourcesManager(10223): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10223): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10223): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/CountryDetector( 3527): No listener is left
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 444us total 9.025ms
,I/GHttpClientFactory(10174): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(10174): Conditions not met for autocaching.
,I/MusicLeanback(10174): Stop autocaching.
,D/WearableClient(10174): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10174): WearableClientImpl.onPostInitHandler: done
I/LocationWidgetApplication(10223): onCreate() : start
,D/LocationWidgetApplication(10223): countryCode = POLAND
,D/WearableClient(10174): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10174): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10174): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(10174): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationManagerService( 3527): getProviders()=[]
D/LocationManagerService( 3527): getProviders()=[passive]
D/LocationManagerService( 3527): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,E/ActivityThread(10174): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@c36c28b that was originally bound here
E/ActivityThread(10174): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@c36c28b that was originally bound here
E/ActivityThread(10174): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10174): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10174): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10174): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10174): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10174): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(10174): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10174): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10174): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10174): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(10174): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(10174): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(10174): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(10174): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(10174): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(10174): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10174): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10174): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10174): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10174): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10174): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10174): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10174): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10174): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 3527): Killing 9650:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,D/LWLocationManager(10223): mPrivacy is null
,W/ContextImpl(10223): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3527): Killing 9671:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/ContextFramework:PrivacyManager(10223): Service for PrivacyManager is connected
,I/splitIntent( 3527): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,I/splitIntent( 3527): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LWLocationManager(10223): Privacy service : STATUS_PLACE
D/LWLocationManager(10223): updateLocationStatus()
,D/AuthorizationBluetoothService( 4306): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/LocationWidgetFuctionData(10223): readDB
,I/LocationWidgetFuctionData(10223): selectedAppSize: 3
I/LocationWidgetFuctionData(10223): configPlaceList aroundMeItems
,D/LocationInitializer( 4494): Restart initialization of location
,E/MDM     ( 4306): [263] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 4306): No location to return for getLastLocation()
,W/FusedLocationProvider( 4306): location=null
,I/art     ( 4306): Explicit concurrent mark sweep GC freed 39963(2MB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 29MB/45MB, paused 731us total 33.771ms
,D/CAR.SERVICE( 9269): mConnectedToCar = false, abort
,E/ActivityThread( 9269): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@78bd2cb that was originally bound here
E/ActivityThread( 9269): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@78bd2cb that was originally bound here
E/ActivityThread( 9269): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 9269): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 9269): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread( 9269): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread( 9269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 9269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 9269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 9269): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 9269): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 9269): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 9269): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 9269): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 9269): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 9269): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread( 9269): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread( 9269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread( 9269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 9269): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 9269): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread( 9269): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 9269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 9269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 9269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 9269): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c751f2 that was originally bound here
E/ActivityThread( 9269): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c751f2 that was originally bound here
E/ActivityThread( 9269): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 9269): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 9269): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread( 9269): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread( 9269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 9269): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 9269): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 9269): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 9269): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 9269): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 9269): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 9269): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 9269): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread( 9269): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread( 9269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread( 9269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 9269): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 9269): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread( 9269): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 9269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 9269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 9269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 3527): Unbind failed: could not find connection for android.os.BinderProxy@5e4d913
,I/splitIntent( 3527): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 19275(1305KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 1.415ms total 77.071ms
,D/AcmsKeyStoreHelper(10076):  getKeyStoreForApplication Enter
,I/LocationWidgetFuctionData(10223): selectedAppSize: 3
,I/LocationWidgetFuctionData(10223): selectedAppSize: 3
,I/LocationWidgetFuctionData(10223): selectedAppSize: 3
,I/LocationWidgetFuctionData(10223): selectedAppSize: 3
,I/AcmsKeyStoreHelper(10076): Key Store exist
I/AcmsKeyStoreHelper(10076): Hence loading the keystore file
,E/CscFactoryReceiver( 3979): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 3979): Media DB Scanner finished.
D/CscFactoryReceiver( 3979): start service to Set Ringtone
,D/CscFactoryReceiver( 3979): start service to Set Notification
,D/CscFactoryReceiver( 3979): start service to Set Alarmtone
,D/CscUpdateService( 3979): onStart
E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3979): only ringtone update
,D/CscUpdateService( 3979): onStart
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 3979): only notification update
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 3979): onStart
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/CscParser( 3979): update(): xml file exist
E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 3979): only alarmtone update
E/CscParser( 3979): update(): xml file exist
E/CscParser( 3979): update(): xml file exist
,W/CSCSettings( 3979): Setting Ringtones (type) : 1
,D/CscParser( 3979): RingTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,W/CSCSettings( 3979): Setting Ringtones (type) : 2
D/CscParser( 3979): MessageTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,W/CSCSettings( 3979): Setting Ringtones (type) : 4
D/CscParser( 3979): AlarmTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,E/Zygote  (10255): MountEmulatedStorage()
,E/Zygote  (10255): v2
I/libpersona(10255): KNOX_SDCARD checking this for 10004
I/libpersona(10255): KNOX_SDCARD not a persona
,I/SELinux (10255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=10255 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10255): TimaSignature is unavailable
,D/ActivityThread(10255): Added TimaKeyStore provider
E/LWLocationManager(10223): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(10223): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10223): setShouldUpdateLocationId
D/LWLocationManager(10223): setShouldUpdateLocationId return false
D/LWLocationManager(10223): setShouldUpdateLocationId
D/LWLocationManager(10223): setShouldUpdateLocationId return false
D/LWLocationManager(10223): setShouldUpdateLocationId
D/LWLocationManager(10223): setShouldUpdateLocationId return false
D/LWLocationManager(10223): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/AcmsKeyStoreHelper(10076):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10076): getKeyStoreForApplication success 
D/AcmsCore(10076): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10076): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10076): Decrementing - Counter value: 1
D/AcmsCore(10076): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(10076): This is NOT a valid MirrorLink app
D/AcmsCore(10076): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10076): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10076): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10076): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(10076): getSvcCounter - Counter value: 0
D/AcmsService(10076): Enter onDestroy
I/AcmsService(10076): cleanUp(): inside service clean up
D/AcmsCore(10076): AcmsCore: inside DeInit
D/AcmsCore(10076): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10076): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10076): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10076): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10076): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10076): getSvcCounter - Counter value: 0
D/AcmsService(10076): killing acms process
I/Process (10076): Sending signal. PID: 10076 SIG: 9
,D/ResourcesManager(10255): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,I/DCMProvider(10255): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@3205cd0 Provider Ref Count:1
,I/DCMConfig(10255): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController(10255): [#DCM#]  state through storage volume =  mounted
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
I/StorageController(10255): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/StorageController(10255): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10255): [#DCM#]  state through storage volume =  unmounted
I/StorageController(10255): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager(10255): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager(10255): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig(10255): [#DCM#] initializeTransport.DCMPolicyManager  10 ms
,I/DCMConfig(10255): [#DCM#] initializeTransport.MediaManager  11 ms
,I/ActivityManager( 3527): Process ACMS.Process (pid 10076)(adj 0) has died(87,1250)
,I/DCMConfig(10255): [#DCM#] initializeTransport.DCMNRTManager  15 ms
,I/DCMConfig(10255): [#DCM#] No of CPU Core 8
I/DCMConfig(10255): [#DCM#] initializeTransport took  15 ms
I/DCMProvider(10255): [#DCM#] onCreate end 
,I/DCMNRTManager(10255): [#DCM#] intialize 
,I/SystemBroadcastReceiver(10255): [#DCM#] [DCM_Performance] onReceive completed in time  12 microsec. 
,I/SystemBroadcastReceiver(10255): [#DCM#] Calling notifyListeners. 
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/StorageController(10255): [#DCM#]  state through storage volume =  mounted
I/StorageController(10255): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10255): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10255): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
,I/StorageController(10255): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10255): [#DCM#]  state through storage volume =  removed
I/StorageController(10255): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController(10255): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController(10255): [#DCM#] Sending intent for OS Upgrade for Phone contents 
I/DCMUtilities(10255): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,I/SystemUtils(10255): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils(10255): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
,I/DCMUtilities(10255): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver(10255): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10255): [#DCM#] onReceive action = EVENT_SIOP
I/WriterFactory(10255): [#DCM#] verifyLuceneDB ++ 
,E/Zygote  (10274): MountEmulatedStorage()
I/libpersona(10274): KNOX_SDCARD checking this for 10007
E/Zygote  (10274): v2
I/libpersona(10274): KNOX_SDCARD not a persona
I/SELinux (10274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=10274 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9688:com.sec.pcw.device/1000 (adj 13): bgCount ##31
I/WriterFactory(10255): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory(10255): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory(10255): [#DCM#] TAXO in mode CREATE_OR_APPEND
,D/TimaKeyStoreProvider(10274): TimaSignature is unavailable
I/WriterFactory(10255): [#DCM#] Before facet 
I/WriterFactory(10255): [#DCM#] After facet=!null ? true
,D/ActivityThread(10274): Added TimaKeyStore provider
,I/DCMUtilities(10255): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController(10255): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
I/DCMConfig(10255): [#DCM#] setSuccessState =  true
,D/ResourcesManager(10274): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,I/ThumbnailProvider(10274): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver(10274): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService(10274): [START] processBroadcastIntent ...
,I/BroadcastProcessorService(10274): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo(10274): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService(10274): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService(10274): [START] DocumentService startDocumentService
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10292): MountEmulatedStorage()
I/libpersona(10292): KNOX_SDCARD checking this for 10044
E/Zygote  (10292): v2
I/libpersona(10292): KNOX_SDCARD not a persona
,I/SELinux (10292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=10292 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/DocumentService(10274): DocumentService onCreate ... service
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10274): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,D/TimaKeyStoreProvider(10292): TimaSignature is unavailable
W/ContextImpl(10274): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/ActivityThread(10292): Added TimaKeyStore provider
,D/ResourcesManager(10292): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(10292): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10292): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(10292): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10292): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10292): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10292): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo(10274): [SIOP LEVEL] : -2
,I/DocumentService(10274): [BEGIN SYNC] DocumentService beginIndexing :17
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10274): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/DocumentServiceUtils(10274):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo(10274): DocumentService [SIOP LEVEL] changed to -2
E/SystemInfo(10274): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10311): MountEmulatedStorage()
E/Zygote  (10311): v2
I/libpersona(10311): KNOX_SDCARD checking this for 10050
I/libpersona(10311): KNOX_SDCARD not a persona
,I/SELinux (10311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=10311 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9269:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,I/SystemInfo(10274): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10274): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10274): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/TimaKeyStoreProvider(10311): TimaSignature is unavailable
,D/ActivityThread(10311): Added TimaKeyStore provider
,I/SystemInfo(10274): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService(10274): [VERIFY] verifyThumbnailImages
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
D/ResourcesManager(10311): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10274): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
I/DocumentService(10274): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService(10274): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :56
E/DocumentService(10274): [THUMBNAIL] Total Time taken for each file :0
E/        (10274): [INDEX] Total time taken for each file :0
W/ResourcesManager(10311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/DocumentService(10274): DocumentService onDestroy start
,W/ResourcesManager(10311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DocumentService(10274): DocumentService onDestroy end
W/ResourcesManager(10311): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DocumentService(10274): DocumentService cleanupEverything start
W/ResourcesManager(10311): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
W/ResourcesManager(10311): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
W/ResourcesManager(10311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/IndexParserThreadsManager(10274): InterruptedException: null
W/ResourcesManager(10311): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 3527): Killing 9477:com.samsung.android.app.galaxyfinder/u0a35 (adj 13): bgCount ##31
,I/SystemInfo(10274): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10274): DocumentService cleanupEverything end
,I/Process (10274): Sending signal. PID: 10274 SIG: 9
,I/ActivityManager( 3527): Process com.samsung.indexservice (pid 10274)(adj 9) has died(116,1251)
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4260, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:-707, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-765
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3527): findPreferredActivity: No PreferredActivities set
,D/NearbySource(10311): Nearby Source Create!
,D/NearbyContext(10311): Nearby Context Create!
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10311): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(10311): Samsung link source created
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(10311): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady(10311): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady(10311): handleMeidaScanFinish()
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10311): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10311): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10311): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10311): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/FaceInterface(10311): requestFaceScan() is called.
,I/FaceInterface(10311): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData(10311): query fail: 
,W/LocalSuggestAlbumData(10311): query fail: 
,D/ContactProvider(10311): getAllContactInfoList End
I/syncContacts(10311): thread: 1403, sync time = 27
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 9045): [1157] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/Zygote  (10335): MountEmulatedStorage()
I/libpersona(10335): KNOX_SDCARD checking this for 10173
E/Zygote  (10335): v2
I/libpersona(10335): KNOX_SDCARD not a persona
,I/SELinux (10335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10335 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(10335): TimaSignature is unavailable
,D/ActivityThread(10335): Added TimaKeyStore provider
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(10335): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,I/System.out( 9045): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 10031
,V/TaskCloserActivity(10335): TaskCloserActivity enter()
,V/TaskCloserActivity(10335): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/art     ( 3717): Explicit concurrent mark sweep GC freed 5182(365KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 307us total 11.988ms
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10352): MountEmulatedStorage()
I/libpersona(10352): KNOX_SDCARD checking this for 10122
E/Zygote  (10352): v2
I/libpersona(10352): KNOX_SDCARD not a persona
I/SELinux (10352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=10352 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10352): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10352): TimaSignature is unavailable
,D/ActivityThread(10352): Added TimaKeyStore provider
,D/ResourcesManager(10352): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/MediaStoreImporter(10174): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager( 3527): Killing 8841:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(10352): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   (10352): getAccountsCursor
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/GAV2    (10352): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   (10352): Observing account changes for notifications
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3527): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/BootupListener( 3979): ACTION_DRIVELINK
D/SettingsProvider( 3527): name = drivelink_navigation
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1001
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/BootupListener( 3979): NAVI : com.here.app.maps
D/SettingsProvider( 3527): name = internet_call_settings_visibility
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1001
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/BootupListener( 3979): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,E/Gmail   (10352): Error finding the version of the Email provider.....
E/Gmail   (10352): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (10352): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (10352): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (10352): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (10352): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (10352): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (10352): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (10352): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(10352): We do not support migrating this version of the Email provider.
,I/Gmail   (10352): getAccountsCursor
,D/Widget  (10101): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Widget  (10101): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  (10101): widgetUpdate 5
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/LocationWidgetUtils(10223): getUpcommingInstances() start: 1457533332767, end: 1458082799999
,D/LocationWidgetUtils(10223): getUpcommingInstances() DB begin time >= start:1457533332767, DB begin time <= end:1458082799999
,E/SQLiteLog(10352): (283) recovered 66 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/Zygote  (10395): MountEmulatedStorage()
I/libpersona(10395): KNOX_SDCARD checking this for 10163
E/Zygote  (10395): v2
I/libpersona(10395): KNOX_SDCARD not a persona
,I/SELinux (10395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10395): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=10395 uid=10163 gids={50163, 9997} abi=armeabi-v7a
I/ActivityManager( 3527): Killing 7690:com.android.settings/1000 (adj 13): bgCount ##31
,I/Gmail   (10352): notifyAccountChanged
,I/Gmail   (10352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   (10352): getAccountsCursor
,I/Gmail   (10352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/TimaKeyStoreProvider(10395): TimaSignature is unavailable
V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread(10395): Added TimaKeyStore provider
I/Gmail   (10352): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (10352): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ResourcesManager(10395): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(10395): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10395): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 4494): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10415): MountEmulatedStorage()
I/libpersona(10415): KNOX_SDCARD checking this for 10164
E/Zygote  (10415): v2
I/libpersona(10415): KNOX_SDCARD not a persona
,I/SELinux (10415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=10415 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9721:com.policydm/1000 (adj 13): bgCount ##31
,I/Gmail   (10352): getAccountsCursor
,V/GLSActivity( 4306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(10415): TimaSignature is unavailable
,D/ActivityThread(10415): Added TimaKeyStore provider
,D/ResourcesManager(10415): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10415): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10415): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10415): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10415): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3779): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 3527): Killing 9739:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BluetoothAdapter( 9366): disable()
,E/BluetoothManagerService( 3527): Bluetooth is already disabled. DO NOT disable again.
,I/ActivityManager( 3527): Waited long enough for: ServiceRecord{cb12c01 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/WifiManager( 9366): packageName : com.example.hello
,D/SecContentProvider( 3527): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3527): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3527): mCursor = null
,D/WifiService( 3527): setWifiEnabled: false pid=9366, uid=10687
,E/WifiService( 3527): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3527): name = wifi_on
,I/jxcore-log( 9366): ****TEST TOOK:  5087  ms ****,
I/jxcore-log( 9366): 
,I/jxcore-log( 9366): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9366): 
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 18318(1160KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.077ms total 163.982ms
,D/WifiService( 3527): New client listening to asynchronous messages
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AndroidRuntime(10440): 
D/AndroidRuntime(10440): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10440): CheckJNI is OFF
,D/AndroidRuntime(10440): readGMSProperty: start
D/AndroidRuntime(10440): readGMSProperty: already setted!!
,D/AndroidRuntime(10440): readGMSProperty: end
D/AndroidRuntime(10440): addProductProperty: start
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/AffinityControl(10440): AffinityControl: registerfunction enter
,D/AndroidRuntime(10440): Calling main entry com.android.commands.pm.Pm
I/GAV2    ( 9562): Thread[GAThread,5,main]: No campaign data found.
,D/PersonaManagerService( 3527): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3527): START PACKAGE DELETE: observer{162781298}
D/PackageManager( 3527): pkg{<packageName>}
D/PackageManager( 3527): user{0}
D/PackageManager( 3527): caller{2000}
D/PackageManager( 3527): flags{3}
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3527): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3527): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3527): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3527): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3527): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3527): !@killApplicatoin: 10687, uninstall pkg
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10687 user=-1: uninstall pkg
,I/ActivityManager( 3527): Killing 9366:com.example.hello/u0a687 (adj 0): stop com.example.hello
,W/ActivityManager( 3527): Force removing ActivityRecord{1b53cbc u0 com.example.hello/.MainActivity t27}: app died, no saved state
,I/SurfaceFlinger( 2850): id=11 Removed NainActivit (5/7)
,I/SurfaceFlinger( 2850): id=11 Removed NainActivit (-2/7)
,D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
,D/CustomFrequencyManagerService( 3527): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  pkgName : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3527): mDVFSHelper.acquire()
,W/PackageSettings( 3527): Skipping PackageSetting{2b1fcd94 com.test.thalitest/10686} due to missing metadata
,V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager( 3527): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10687 user=0: pkg removed
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiService( 3527): Client connection lost with reason: 4
,D/Launcher( 4000): onRestart, Launcher: 678061287
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 8052): Explicit concurrent mark sweep GC freed 27961(1578KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 376us total 22.406ms
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/InputReader( 3527): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/art     ( 4494): Explicit concurrent mark sweep GC freed 49562(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 31MB/47MB, paused 838us total 35.010ms
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/GeofencerStateMachine( 4306): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/SamsungIME( 4443): mOCRHelper is null
,D/LWLocationManager(10223): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10223): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10453): MountEmulatedStorage()
E/Zygote  (10453): v2
I/libpersona(10453): KNOX_SDCARD checking this for 10063
I/libpersona(10453): KNOX_SDCARD not a persona
,I/SELinux (10453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10453 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Launcher( 4000): onStart, Launcher: 678061287
D/Launcher.HomeView( 4000): onStart
D/Launcher( 4000): onResume, Launcher: 678061287
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/SettingsProvider( 3527): name = kids_home_mode
,W/ResourceType( 4950): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4950): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10008
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/Launcher.HomeView( 4000): onResume
,I/ActivityManager( 3527): Killing 8725:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10453): TimaSignature is unavailable
,D/ActivityThread(10453): Added TimaKeyStore provider
,D/Launcher( 4000): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 4000): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/MenuAppsGridFragment( 4000): onResume
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ActivityManager( 3527): handle home activity for 0
,D/ResourcesManager(10453): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/WallpaperManagerService( 3527): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 3527): post home show event for user 0
D/ActivityManager( 3527): post active user change for 0
D/KnoxTimeoutHandler( 3527): postActiveUserChange for user 0
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,I/SurfaceFlinger( 2850): id=12 createSurf (1440x2560),1 flag=4, Mauncher
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
,D/PowerManagerService( 3527): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 3527): !@[ps] Screen__Off - 0 : timeout (0x4) (2)
I/PowerManagerService( 3527): Going to sleep due to screen timeout (uid 1000)...
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/InputManager-JNI( 3527): setDeviceInteractive: 0
D/DisplayPowerController( 3527): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3527): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/InputManager-JNI( 3527): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService( 3527): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI( 3527): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 3527): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 3527): SecHardwareInterface.setBatteryADC : false
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/VRSetupWizardStub/PackageIntentReceiver(10453): onReceive()
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
D/VRSetupWizardStub/PackageIntentReceiver(10453): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10453): packagename:com.example.hello
,D/InputManager-JNI( 3527): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/InputManager-JNI( 3527): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/InputManager-JNI( 3527): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/mali_winsys( 4000): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/InputManager-JNI( 3527): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/Launcher( 4000): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 4000): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/InputMethodManagerService( 3527): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/PowerManagerService( 3527): handleSandman : startDream()
,D/SContextService( 3527): 	.unregisterCallback : 1, client=
D/SContextService( 3527): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@9e8c930, Service = Auto Rotation, used = 1
,W/CAE     ( 3527): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3527): stop(ContextProvider.java:149)
,V/CAE     ( 3527): clear(AutoRotationRunner.java:182)
V/CAE     ( 3527): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3527): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3527): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2867): sendContextData: -78, 7, 0, 0
,W/InputMethodManagerService( 3527): Got RemoteException sending setActive(false) notification to pid 9366 uid 10687
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/CAE     ( 3527): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     ( 3527): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (10475): MountEmulatedStorage()
E/Zygote  (10475): v2
I/libpersona(10475): KNOX_SDCARD checking this for 10021
I/libpersona(10475): KNOX_SDCARD not a persona
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/SELinux (10475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10475 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/SELinux (10475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Killing 9764:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,E/SELinux (10475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/PowerManagerService( 3527): handleSandman : startDreaming, but isDreaming false
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/PowerManagerService( 3527): Sleeping (uid 1000)...
D/PowerManagerService( 3527): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3527): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService( 3527): [input device light] handleInputDeviceLightOff
,D/RegisteredServicesCache( 3962): empty dynamic service
,D/TimaKeyStoreProvider(10475): TimaSignature is unavailable
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ActivityThread(10475): Added TimaKeyStore provider
I/SurfaceFlinger( 2850): id=13 createSurf (1440x2560),2 flag=404, DolorFade
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/EnterpriseDeviceManagerService( 3527): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3527): Admin package name: com.google.android.gms
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/PowerManagerService( 3527): Excessive delay in ColorFade : createSurface: 20ms
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 21033(1696KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 5.341ms total 123.742ms
,D/CAE     ( 3527): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3527): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     ( 3527): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3527): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,I/MicrophoneInputStream( 4048): mic_starting gfk@277f5186
,D/SContextService( 3527): removeSContextService() : service = Auto Rotation
D/SContextService( 3527): ===== SContext Service List =====
D/SContextManager( 3527):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@6272f18, service=Auto Rotation
,D/KeyguardViewMediator( 3695): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3695): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3695): changeWallpaperByScreenOff()
,V/AudioPolicyManager( 2855): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager( 2855): getDeviceForInputSource()input source 1999, device 80000004
E/AudioHardwareTinyALSA( 2855): AudioStreamInALSA userDefined 0, pSize 960, pCount 2, buffer 1920, latency 120000
,E/AudioHardwareTinyALSA( 2855): can not make /data/snd/input_after_ns2.pcm
D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
E/AudioHardwareTinyALSA( 2855): can not make /data/snd/input_before_ns2.pcm
E/AudioHardwareTinyALSA( 2855): can not make /data/snd/input2.pcm
E/AudioHardwareTinyALSA( 2855): can not make /data/snd/seamless_compress_16k_mono.bin
E/AudioHardwareTinyALSA( 2855): can not make /data/snd/seamless_decode_16k_stereo.pcm
D/AudioHardwareTinyALSA( 2855): Input	: format = 1, channels = 16, rate = 16000
D/AudioHardwareTinyALSA( 2855): default	: format = 0, channelCount = 2, rate = 16000
D/AudioHardwareTinyALSA( 2855): AudioStreamOps::set set IN_Channels : 10
D/AudioHardwareTinyALSA( 2855): mInputs.size : 1
I/HotwordRecognitionRnr( 4048): Starting hotword detection.
,I/AudioFlinger( 2855): AudioFlinger's thread 0xaed33000 ready to run
D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/KeyguardViewMediator( 3695): notifyScreenOffLocked
,I/EDMNativeHelperService( 3527): isMicrophoneEnabled
,D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
,D/ResourcesManager(10475): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/KeyguardViewMediator( 3695): timeout : 5000
V/AudioPolicyManager( 2855): startInput() input 20
V/AudioPolicyManager( 2855): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager( 2855): getNewInputDevice() selected device 80000004
I/AudioPolicyManager( 2855): ### Device reset for Normal
V/AudioPolicyManager( 2855): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager( 2855): DeviceVector::getDevicesFromType() for type 80000004 found 0xb235b280
,I/AudioHardwareTinyALSA( 2855): virtual android::status_t android::AudioStreamInALSA::setParameters(const android::String8&): input_source=6;keyIsHotword=true;routing=-2147483644
I/samsungRecord( 2855): [samsungrecord] SamsungRecInit 
I/samsungRecord( 2855): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord( 2855): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord( 2855): 1
D/AudioHardwareTinyALSA( 2855): InALSA::setDevice: mode = 0, newDevice=0x80000004, currentDevice=0x0 ,force= 0
I/AudioHardwareTinyALSA( 2855): InALSA::setDevice: mode[0], Device[80000004] force=0
D/AudioHardwareTinyALSA( 2855): getInputScenario: input scenario = Voice
D/TinyUCM ( 2855): Enable Input dev(0x80000004)
,D/TinyUCM ( 2855): setScenario: Voice
D/TinyUCM ( 2855): set default scenario
,D/TinyUCM ( 2855): Disable Output dev(0x0)
D/TinyUCM ( 2855): getInputChannel: inputs = 0x80000004
D/TinyUCM ( 2855): set channel: Left
I/AudioHardwareTinyALSA( 2855): InALSA::setDevice: mHandle NULL mode[0], Device[80000004]
I/AudioHardwareTinyALSA( 2855): Open:+ mDefaults->direction=10000000 device=0
D/AudioHardwareTinyALSA( 2855): Channel: 2, Samplerate: 48000, Format: 0, Period Size: 960, Period Count: 2
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/KeyguardViewMediator( 3695): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 3695): handleNotifyScreenOff
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (10475): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 09 15:22:14 GMT+01:00 2016
,D/PowerManagerService( 3527): Excessive delay in ColorFade : createEglContext: 52ms
,D/mali_winsys( 3527): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PermissionCache( 2850): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
,D/PackageManager( 3527): delete codoeFile: 
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/KLMS-2.4.521: (10475): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3527): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3527): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/AASAUninstall( 3527):  com.example.hello not target!
,D/PackageManager( 3527): result of delete: 1{162781298}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/KLMS-2.4.521: (10475): KLMSIntentService(): onCreate()
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10475): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/AndroidRuntime(10440): Shutting down VM
,I/KLMS-2.4.521: (10475): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/fb4a(:<default>):QeInternalImpl( 9706): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
E/Zygote  (10511): MountEmulatedStorage()
I/libpersona(10511): KNOX_SDCARD checking this for 10106
E/Zygote  (10511): v2
I/libpersona(10511): KNOX_SDCARD not a persona
,D/RCPManagerService( 3527): PackageReceiver onReceive()
I/HarmonyEASService( 3527): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/SELinux (10511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/KnoxMUMContainerPolicy( 3527): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3527): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 3527): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3527): uID is 10687
V/EnterpriseBillingPolicy( 3527): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3527): getProfileForApplication - enter
I/KLMS-2.4.521: (10475): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,V/EnterpriseBillingPolicyStorage( 3527): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3527): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3527): getBillingProfileForVpnEngine - start - com.example.hello
,I/ActivityManager( 3527): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10511 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
V/EnterpriseBillingPolicyStorage( 3527): getBillingProfileForVpnEngine - end - null
I/KLMS-2.4.521: (10475): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (10475): KLMSIntentService(): listeningToPackageRemoved().START
,I/SELinux (10511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/AudioHardwareTinyALSA( 2855): Open:- mDefaults->direction=10000000 device=0 mHandle: b00a9600
D/AudioHardwareTinyALSA( 2855): setInputVolume
D/TinyUCM ( 2855): setModifier Recognition, en=1
D/TinyUCM ( 2855): Recognition doesn't have param
D/AudioHardwareTinyALSA( 2855): setPcmInterface: Stream=0x2, iSamplerate=16000++
D/AudioHardwareTinyALSA( 2855): setPcmInterface--
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (10475): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
V/AudioPolicyManager( 2855): setInputDevice() createAudioPatch returned -22 patchHandle 0
V/AudioPolicyManager( 2855): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 4048): mic_started gfk@277f5186
,E/SELinux (10511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WallpaperManagerService( 3527):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 3527): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 3527): handleActiveUserChange for user 0
,D/PowerManagerService( 3527): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8725(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 415us total 11.034ms
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/CheckinService( 4494): Done disabling old GoogleServicesFramework version
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 273us total 9.322ms
,D/TimaKeyStoreProvider(10511): TimaSignature is unavailable
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ActivityThread(10511): Added TimaKeyStore provider
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 355us total 8.576ms
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10223): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PowerManagerService( 3527): Excessive delay in ColorFade : initGLShaders: 23ms
,E/Zygote  (10528): MountEmulatedStorage()
E/Zygote  (10528): v2
I/libpersona(10528): KNOX_SDCARD checking this for 1000
I/libpersona(10528): KNOX_SDCARD not a persona
,I/SELinux (10528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10528 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 3527): Excessive delay in ColorFade : draw: 15ms
,I/HotwordWorker( 4048): onReady
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.521: (10475): KLMSIntentService(): listeningToPackageRemoved().END
,D/TimaKeyStoreProvider(10528): TimaSignature is unavailable
,D/ActivityThread(10528): Added TimaKeyStore provider
,D/PowerManagerService( 3527): Excessive delay in ColorFade : draw: 15ms
,D/ResourcesManager(10511): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/PowerManagerService( 3527): Excessive delay in ColorFade : draw: 13ms
D/PowerManagerService( 3527): Excessive delay in ColorFade prepare: 183ms
D/DisplayPowerController( 3527): ColorFade: onAnimationStart
,D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3527): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3527): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (10475): KLMSIntentService(): onDestroy()
,D/ResourcesManager(10528): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10528): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10223): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10223): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10223): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10223): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(10511): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(10511): ELMEngine.ELMEngine( context ).
,D/elm:14491(10511): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/TaskPersister( 3527): removeObsoleteFile: deleting file=27_task.xml
,D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 0
D/lights  ( 3527): lcd : 0 +
D/DisplayPowerController( 3527): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3527): lcd : 0 -
,D/elm:14491(10511): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/RCPManager(10528):  in createShortcut() for packageName: com.example.hello userId0
,D/elm:14491(10511): ElmAgentService : onCreate()
D/RCPManagerService( 3527):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3527): queryAllProviders():  providerCallBack is not register for 0
,D/elm:14491(10511): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14491(10511): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10511): MDMBridge.getInstance()
D/elm:14491(10511): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(10511): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
W/fb4a(:<default>):UserScope( 9706): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3527): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/Zygote  (10554): MountEmulatedStorage()
E/Zygote  (10554): v2
I/libpersona(10554): KNOX_SDCARD checking this for 10019
I/libpersona(10554): KNOX_SDCARD not a persona
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/SELinux (10554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10554 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,I/SELinux (10554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/elm:14491(10511): ElmAgentService : onDestroy().
W/ResourcesManager( 3527): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/CustomFrequencyManagerService( 3527): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3527): mDVFSHelper.release()
D/CustomFrequencyManagerService( 3527): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/TimaKeyStoreProvider(10554): TimaSignature is unavailable
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ActivityThread(10554): Added TimaKeyStore provider
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/CAE     ( 3527): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3527): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     ( 3527): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3527): SendSensorHubData: send data = -76, 13, -47, 0
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/Sensorhubs( 2867): sendContextData: -76, 13, -47, 0
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 9706): Thread[1,tid=9706,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 0
E/Zygote  (10569): MountEmulatedStorage()
D/DisplayPowerController( 3527): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Zygote  (10569): v2
I/libpersona(10569): KNOX_SDCARD checking this for 10052
I/libpersona(10569): KNOX_SDCARD not a persona
,I/SELinux (10569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/InputMethodManagerService( 3527): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
I/ActivityManager( 3527): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=10569 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (10569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/SELinux (10569): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9706): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/MotionRecognitionService( 3527):   mReceiver.onReceive : ACTION_SCREEN_ON
I/CrashAnrDetector( 3527): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 3527): clearDefaults: com.example.hello
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/ResourcesManager(10223): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(10554): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/MotionRecognitionService( 3527):  handler : SCREEN_ON end
,I/WifiNative-HAL( 3527): startHal
E/wifi    ( 3527): getStaticLongField sWifiHalHandle 0x8f88c7fc
D/wifi    ( 3527): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x30208a
I/WifiNative-HAL( 3527): Could not start hal
D/WifiStateMachine( 3527): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3527): handleScreenStateChanged Exit: true
,E/WifiStateMachine( 3527): setSuspendOptimizations: 4 false
E/WifiStateMachine( 3527): mSuspendOptNeedsDisabled 4
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10155): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10155): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(10155): Clear T&P info.
,D/TimaKeyStoreProvider(10569): TimaSignature is unavailable
D/ActivityThread(10569): Added TimaKeyStore provider
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10155): Widget is not attached.
,D/NotificationService( 3527): ACTION_SCREEN_ON
D/LightsService( 3527): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3527) 
D/LightsService( 3527): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3527): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3527): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ResourcesManager(10223): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/ActivityManager( 3527): Killing 9832:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10554): onReceive()
I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=on)
I/com.sec.android.service.health.upgrade.UninstallReceiver(10554): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10554): onReceive() : package name is not s health. Return !!!
,W/ContextImpl( 9963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/ActivityManager( 3527): Killing 9807:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
E/lowmemorykiller( 2825): Error writing /proc/9807/oom_score_adj; errno=22
,D/ResourcesManager(10569): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/LocationWidgetApplication(10223): getLastUiLocationId() : mLastUiLocationId = -100
W/ResourcesManager(10569): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(10569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10569): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/SecExternalDisplayIntents_Java( 3527): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
I/Timeline( 3527): Timeline: Activity_windows_visible id: ActivityRecord{3c94732f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t26} time:45595
,D/PackageBroadcastService( 4494): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 4494): Clearing selected account for com.example.hello
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/art     ( 9706): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (10590): MountEmulatedStorage()
I/libpersona(10590): KNOX_SDCARD checking this for 1000
E/Zygote  (10590): v2
I/libpersona(10590): KNOX_SDCARD not a persona
,I/SELinux (10590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider(10590): TimaSignature is unavailable
,D/ActivityThread(10590): Added TimaKeyStore provider
,D/ResourcesManager(10223): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/Zygote  (10607): MountEmulatedStorage()
E/Zygote  (10607): v2
I/libpersona(10607): KNOX_SDCARD checking this for 10116
I/libpersona(10607): KNOX_SDCARD not a persona
,I/SELinux (10607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10607 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,D/Mms/MmsApp(10569): [start]    onCreate() consume time = 0.0
D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Books/Books.apk
,E/SQLiteLog( 4494): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4494): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/DisplayPowerState( 3527): !@ ColorFade entry
,E/DriveAsyncService( 4494): disk I/O error (code 3850)
E/DriveAsyncService( 4494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4494): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4494): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4494): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4494): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4494): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4494): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4494): 	at java.lang.Thread.run(Thread.java:818)
D/DisplayPowerController( 3527): ColorFade: onAnimationEnd
,D/Mms/ArtClassLoader(10569): init before art
,D/Mms/ArtClassLoader(10569): init [DONE] art
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/TimaKeyStoreProvider(10607): TimaSignature is unavailable
,D/ActivityThread(10607): Added TimaKeyStore provider
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
,D/AutomaticBrightnessController( 3527): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3527): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController( 3527): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3527): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/Sensors ( 3527): Light old sensor_state 513, new sensor_state : 1 en : 0
,I/AutomaticBrightnessController( 3527): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3527): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3527): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 3527): getFinalBrightness : 0 -> 0
D/SensorManager( 3527): unregisterListener ::   
D/DisplayPowerController( 3527): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 3527): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/DisplayPowerController( 3527): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3527): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3527): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3527): [PWL] sb release: PowerManagerService.Display
I/DisplayManagerService( 3527): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/LocationSettingsChecker( 4494): Removing dialog suppression flag for package com.example.hello
D/SurfaceFlinger( 2850): Set power mode=0, type=0 flinger=0xb6a62000
I/hwcomposer( 2850): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/SensorManager( 3527): unregisterListener ::   
,D/Mms/TelephonyPermission(10569): start operation mode monitor
,V/ActivityManager( 3527): Display changed displayId=0
,D/ResourcesManager(10569): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(10607): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,E/SQLiteLog( 4494): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4494): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4494): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4494): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4494): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4494): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4494): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4494): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4494): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4494): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4494): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4494): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4494): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4494): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4494): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4494): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4494): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4494): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/IpRemoteDisplayController( 3527): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3527): Bridge Server is not available
,D/ResourcesManager(10590): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/SQLiteLog( 4494): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/ResourcesManager(10223): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/gH_CompatibleDatabase( 4494): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 4494): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4494): Process: com.google.android.gms, PID: 4494
E/AndroidRuntime( 4494): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4494): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4494): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4494): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4494): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4494): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4494): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4494): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4494): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4494): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4494): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4494): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearPendingStateOp( 4494): Runtime exception while performing operation
E/ClearPendingStateOp( 4494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4494): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4494): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4494): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 4494): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4494): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4494): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4494): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4494): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4494): 	at java.lang.Thread.run(Thread.java:818)
D/ResourcesManager(10223): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,E/SQLiteLog( 4494): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4494): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4494): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4494): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4494): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 4494): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 4494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4494): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4494): 	at com.google.android.g,ms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4494): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4494): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4494): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Mms/TelephonyPermission(10569): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(10569): isDefault true
,E/SQLiteLog( 4494): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4494): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 4494): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/GpsLocationProvider( 3527): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/Mms/MmsApp(10569): onCreate() com.android.mms
E/SharedPreferencesImpl( 4494): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
D/ResourcesManager(10223): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/SQLiteLog( 4494): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4494): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/Launcher.HomeView( 4000): onPause
,D/Launcher( 4000): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/GpsLocationProvider( 3527): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3527): sExerciseIterface is not available
,D/Mms/MmsApp(10569): [start]    initCountryIso consume time = 86.06275
,D/CountryDetector( 3527): The first listener is added
,I/PCWCLIENTTRACE_LOG(10590): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10590): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10590): new DMDBOpenHelper instance
,D/Mms/MmsApp(10569): [end]    initCountryIso consume time = 4.325541
D/Mms/MmsConfig(10569): [start]    MmsConfig.init() consume time = 0.061542
,I/Process ( 4494): Sending signal. PID: 4494 SIG: 9
,E/SQLiteLog(10590): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/Mms/MmsConfig(10569): before partial update
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/DropBoxManagerService( 3527): Can't write: system_app_wtf
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
D/ResourcesManager(10223): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/Mms/MmsConfig(10569): Load Resize quality : 80
,D/Mms/MmsConfig(10569):  enable multiwindow = true
,E/SQLiteLog(10607): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/SQLiteDatabase(10607): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(10607): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10607): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10607): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10607): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10607): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(10607): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(10607): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(10607): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(10607): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteOpenHelper(10607): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(10607): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10607): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10607): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10607): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10607): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(10607): 	at android.content.Conte,ntProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(10607): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(10607): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(10607): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteDatabase(10590): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10590): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10590): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10590): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10590): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10590): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10590): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10590): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10590): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10590): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10590): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10590): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10590): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10590): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10590): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10590): Shutting down VM
,E/AndroidRuntime(10590): FATAL EXCEPTION: main
E/AndroidRuntime(10590): Process: com.sec.pcw.device, PID: 10590
E/AndroidRuntime(10590): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10590): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10590): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10590): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10590): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10590): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10590): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10590): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10590): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10590): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10590): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10590): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10590): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10590): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10590): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10590): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10590): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10590): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10590): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10590): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10590): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10590): 	... 11 more
I/ActivityManager( 3527): Killing 9785:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/SQLiteLog( 4306): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4306): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4306): Shutting down VM
W/SQLiteOpenHelper(10607): Opened filter.db in read-only mode
,E/AndroidRuntime( 4306): FATAL EXCEPTION: main
E/AndroidRuntime( 4306): Process: com.google.android.gms.persistent, PID: 4306
E/AndroidRuntime( 4306): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4306): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4306): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4306): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4306): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4306): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4306): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4306): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4306): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4306): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4306): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4306): 	... 9 more
,E/SQLiteLog(10607): (284) automatic index on titles(filter_id)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{600749 token=android.os.BinderProxy@3313a52d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 4000): onStop
,E/Mms/MessageUtils(10569): setCountryDetector : update country detector info 
E/Mms/MessageUtils(10569): updateCountryIso : update country iso info 
,D/ConnectivityService( 3527): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@18610108)
,I/MicrophoneInputStream( 4048): mic_close gfk@277f5186
I/Timeline( 4000): Timeline: Activity_idle id: android.os.BinderProxy@3313a52d time:45784
,D/ConnectivityService( 3527): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3527): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3527): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3527): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3527): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3527): displayNotification : [09h,00h,00h]
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ConnectivityService( 3527): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/UsbHostManager( 3527): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3527): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3527): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/Mms/PackageInfo(10569): com.sec.imsservice is not installed
D/Mms/MmsConfig(10569): [end]    init() consume time = 38.4535
,D/Mms/Contact(10569): [start]    init() consume time = 0.378875
,D/Mms/Contact(10569): [end]    init consume time = 4.921667
,V/AudioPolicyManager( 2855): stopInput() input 20
V/AudioPolicyManager( 2855): releaseInput() 20
V/AudioPolicyManager( 2855): closeInput(20)
,D/Mms/DraftCache(10569): [start]    rebuildCache consume time = 1.489875
,D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2855): Close mHandle:b00a9600
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  (10645): MountEmulatedStorage()
I/libpersona(10645): KNOX_SDCARD checking this for 1000
E/Zygote  (10645): v2
I/libpersona(10645): KNOX_SDCARD not a persona
,I/HotwordRecognitionRnr( 4048): Hotword detection finished
I/HotwordRecognitionRnr( 4048): Stopping hotword detection.
,I/ActivityManager( 3527): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/AudioHardwareTinyALSA( 2855): closeInputStream +
D/TinyUCM ( 2855): Disable Input dev(0x80000004)
,I/ActivityManager( 3527): Process com.google.android.gms (pid 4494)(adj 0) has died(262,1243)
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
I/SELinux (10645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 11000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 21000ms
,W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 31000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 41000ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 40999ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 40999ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 50999ms
D/CustomFrequencyManagerService( 3527): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 60999ms
,D/TinyUCM ( 2855): set channel: None
,D/AudioHardwareTinyALSA( 2855): Entering AudioStreamInALSA standby mode
,I/SELinux (10645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
E/SELinux (10645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AudioPolicyManager( 2855): releaseInput() exit
,D/TP/MmsSmsProvider( 3979): query,matched:12, calling pid = 10569
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/UsbHostManager( 3527): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3527): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/TP/MmsSmsProvider( 3979): match 12:Elapsed time : 4.249 ms
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/ActivityManager( 3527): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3527): Killing 4306:com.google.android.gms.persistent/u0a14 (adj 0): crash
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,D/TimaKeyStoreProvider(10645): TimaSignature is unavailable
,V/BackupManagerService( 3527): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityThread(10645): Added TimaKeyStore provider
D/ResourcesManager(10223): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,V/BackupManagerService( 3527): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/Mms/TelephonyUtils(10569): getSubId from simSlot 0, return Value = -1
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager(10569): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10569): auto download without roaming -> true
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Mms/TelephonyUtils(10569): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(10569): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(10569): roaming -> false (slotId = 1)
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(10569): auto download without roaming -> true
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(10569): auto download during roaming secondary -> false
D/Mms/DownloadManager(10569): mAutoDownload ------> true
,D/MtpClient(10311): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(10311): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/ResourcesManager(10223): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  (10669): MountEmulatedStorage()
,E/Zygote  (10669): v2
I/libpersona(10669): KNOX_SDCARD checking this for 10014
I/libpersona(10669): KNOX_SDCARD not a persona
,I/SELinux (10669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=10669 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux (10669): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/fb4a(:<default>):QeInternalImpl( 9706): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/fb4a(:<default>):QeInternalImpl( 9706): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9706): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9706): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/SurfaceControl( 3527): Excessive delay in setPowerMode(): 205ms
,D/PowerManagerService( 3527): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL( 3527): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3527): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService( 3527): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 211ms
I/PowerManagerService( 3527): [PWL] Off : 0s ago
I/PowerManagerService( 3527): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3527): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3527): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=3527, ws=null) (elapsedTime=581)
,I/PowerManagerService( 3527): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/Mms/MmsApp(10569): [end]    onCreate() consume time = 102.296583
,D/Mms/FreeMessageStatusReceiver(10569): onReceive, action : android.intent.action.PACKAGE_REMOVED
,E/Zygote  (10684): MountEmulatedStorage()
E/Zygote  (10684): v2
I/libpersona(10684): KNOX_SDCARD checking this for 10014
I/libpersona(10684): KNOX_SDCARD not a persona
,I/SELinux (10684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.gms.persistent for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver: pid=10684 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux (10684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10684): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10669): TimaSignature is unavailable
,D/ActivityThread(10669): Added TimaKeyStore provider
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,I/GAV2    ( 9616): Thread[GAThread,5,main]: No campaign data found.
,D/GpsStatusListenerHelper( 3527): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@3907774c
D/LocationManagerService( 3527): Location listener died
,D/LocationManagerService( 3527): Location listener died
I/LocationManagerService( 3527): remove 2c27ddb3 by com.google.android.gms
D/WifiService( 3527): Client connection lost with reason: 4
,D/PersonaManagerService( 3527): ACTION_SCREEN_ON onReceive
,D/LocationManagerService( 3527): provider request: passive ProviderRequest[ON interval=0]
I/LocationManagerService( 3527): remove ccfa19d by com.google.android.gms
,D/LocationManagerService( 3527): provider request: passive ProviderRequest[ON interval=0]
,D/PersonaManagerServiceHandler( 3527): MSG_ACTION_SCREEN_ON called
,D/Mms/Conversation(10569): [start]    init() consume time = 36.8775
,D/TimaKeyStoreProvider(10684): TimaSignature is unavailable
,D/ActivityThread(10684): Added TimaKeyStore provider
,D/ResourcesManager(10645): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/ResourcesManager(10223): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3527): Killing 9706:com.facebook.katana/u0a114 (adj 15): bgCount ##31
,D/Mms/DownloadManager(10569): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(10569): roaming ------> false, mSimSlot = 0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/Mms/TelephonyUtils(10569): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10569): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10569): auto download without roaming -> true
D/Mms/DownloadManager(10569): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/ResourcesManager(10669): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/Mms/DownloadManager(10569): mAutoDownload ------> true
,D/Mms/FreeMessageReceiverService(10569): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService(10569): onHandleIntent: ACTION_PACKAGE_REMOVED
,W/ResourcesManager(10669): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10669): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  (10709): MountEmulatedStorage()
I/libpersona(10709): KNOX_SDCARD checking this for 10035
E/Zygote  (10709): v2
I/libpersona(10709): KNOX_SDCARD not a persona
I/SELinux (10709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10709 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/ContextImpl(10645): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,D/TimaKeyStoreProvider(10709): TimaSignature is unavailable
,D/ActivityThread(10709): Added TimaKeyStore provider
,D/ResourcesManager(10684): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiService( 3527): Client connection lost with reason: 4
,I/Process (10590): Sending signal. PID: 10590 SIG: 9
,W/ResourcesManager(10684): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10684): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteLog(10645): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10645): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10645): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10645): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10645): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10645): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10645): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10645): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(10645): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10645): Process: com.android.keychain, PID: 10645
E/AndroidRuntime(10645): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10645): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10645): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:55,4)
E/AndroidRuntime(10645): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10645): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10645): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 10569
,D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 2.538 ms
,D/Mms/DraftCache(10569): [end]    rebuildCache consume time = 98.778708
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3979): deleteConversation threadId: 9223372036854775807
,E/Zygote  (10727): MountEmulatedStorage()
I/libpersona(10727): KNOX_SDCARD checking this for 1000
E/Zygote  (10727): v2
I/libpersona(10727): KNOX_SDCARD not a persona
,I/SELinux (10727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10727): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=10727 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 9892:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop187.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/FeatureConfig(10709): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/TimaKeyStoreProvider(10727): TimaSignature is unavailable
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(10709): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityThread(10727): Added TimaKeyStore provider
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/Zygote  (10746): MountEmulatedStorage()
E/Zygote  (10746): v2
I/libpersona(10746): KNOX_SDCARD checking this for 1000
I/libpersona(10746): KNOX_SDCARD not a persona
,I/SELinux (10746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10746 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Process com.sec.pcw.device (pid 10590)(adj 9) has died(259,1246)
,W/ResourcesManager(10709): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/MultiDex(10669): VM with version 2.1.0 has multidex support
W/ResourcesManager(10709): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/MultiDex(10669): install
I/MultiDex(10669): VM has multidex support, MultiDex support library is disabled.
,D/ResourcesManager(10709): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/Process (10645): Sending signal. PID: 10645 SIG: 9
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8781(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 328us total 21.287ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 291us total 10.127ms
D/ResourcesManager(10727): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager(10709): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/lowmemorykiller( 2825): Error writing /proc/10645/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(10746): TimaSignature is unavailable
,D/ActivityThread(10746): Added TimaKeyStore provider
,W/ResourcesManager(10727): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(10727): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 291us total 9.788ms
W/ResourcesManager(10727): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10727): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(10727): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10727): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/NfcService( 3962): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(10709): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/NfcService( 3962): call the applyRouting
,E/Zygote  (10764): MountEmulatedStorage()
I/libpersona(10764): KNOX_SDCARD checking this for 10036
E/Zygote  (10764): v2
I/libpersona(10764): KNOX_SDCARD not a persona
,I/SELinux (10764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=10764 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/SELinux (10764): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/MultiDex(10684): VM with version 2.1.0 has multidex support
I/MultiDex(10684): install
I/MultiDex(10684): VM has multidex support, MultiDex support library is disabled.
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/ActivityManager( 3527): Process com.android.keychain (pid 10645)(adj 5) has died(240,1246)
,W/ResourcesManager(10709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ActivityManager( 3527): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(10764): TimaSignature is unavailable
,D/ActivityThread(10764): Added TimaKeyStore provider
,D/ResourcesManager(10746): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 9963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:44 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:149 android.os.Handler.dispatchMessage:102 
,W/System.err(10727): java.io.FileNotFoundException: /data/log/settingsprovider.txt: open failed: EROFS (Read-only file system)
,D/ResourcesManager(10764): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/System.err(10727): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(10727): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/System.err(10727): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:149)
W/ResourcesManager(10709): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/System.err(10727): 	at com.android.settings.favorite.LogMsg.writeLog(LogMsg.java:51)
W/ResourcesManager(10709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/System.err(10727): 	at com.android.settings.favorite.LogMsg.out(LogMsg.java:29)
W/ResourcesManager(10709): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/System.err(10727): 	at com.android.settings.favorite.MySettingsProvider$DatabaseHelper.<init>(MySettingsProvider.java:167)
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/System.err(10727): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:345)
W/ResourcesManager(10709): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/System.err(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
W/System.err(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
W/System.err(10727): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
W/System.err(10727): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
W/System.err(10727): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
W/System.err(10727): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10727): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10727): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10727): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10727): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10727): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10727): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10727): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10727): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err(10727): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(10727): 	at libcore.io.Posix.open(Native Method)
W/System.err(10727): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(10727): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(10727): 	... 20 more
D/MySettingsProvider(10727): DatabaseHelper(Context context):DATABASE_VERSION=1
E/SQLiteLog(10727): (28) failed to open "/data/data/com.android.settings/databases/mysettings.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10727): Failed to open database '/data/data/com.android.settings/databases/mysettings.db'.
E/SQLiteDatabase(10727): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10727): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10727): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/SQLiteDatabase(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10727): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10727): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10727): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10727): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10727): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10727): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10727): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10727): Shutting down VM
,E/AndroidRuntime(10727): FATAL EXCEPTION: main
E/AndroidRuntime(10727): Process: com.android.settings, PID: 10727
E/AndroidRuntime(10727): java.lang.RuntimeException: Unable to get provider com.android.settings.favorite.MySettingsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10727): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10727): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10727): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10727): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10727): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10727): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10727): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10727): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10727): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10727): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10727): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10727): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10727): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10727): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10727): 	at com.android.settings.favorite.MySettingsProvider.onCreate(MySettingsProvider.java:346)
E/AndroidRuntime(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10727): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10727): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10727): 	... 11 more
,D/ResourcesManager(10709): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ResourcesManager(10709): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(10709): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/ActivityManager( 3527): Killing 9947:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop188.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,D/AcmsPackageEventListener(10746): Received: android.intent.action.PACKAGE_REMOVED
W/ContextImpl(10746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
I/ActivityManager( 3527): Killing 9998:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
D/ResourcesManager(10709): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/AcmsService(10746): Enter Oncreate
D/AcmsServiceMonitor(10746): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10746): creating AcmsCore
D/AcmsCore(10746): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10746): AcmsCore
W/ResourcesManager(10709): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/AcmsCore(10746): init
D/AcmsCore(10746): Looper handler is not null
D/AcmsCore(10746): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10746): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10746): Incrementing - Counter value: 1
D/AcmsCore(10746): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr(10746): AcmsCertificateMngr
D/AcmsService(10746): onStartCommand
D/AcmsService(10746): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor(10746): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10746): Incrementing - Counter value: 2
D/AcmsService(10746): Incremented Counter Value : onStartCommand
D/AcmsRevocationMngr(10746): AcmsRevocationMngr
D/ActivityThread(10746): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,I/Process (10727): Sending signal. PID: 10727 SIG: 9
,E/SQLiteLog(10746): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(10709): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SQLiteDatabase(10746): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10746): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/SQLiteDatabase(10746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10746): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10746): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10746): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10746): Shutting down VM
W/,BroadcastQueue( 3527): Skipping deliver [sec] BroadcastRecord{3d2d8449 u-1 android.intent.action.SCREEN_ON} to ReceiverList{8d09f90 4306 com.google.android.gms.persistent/10014/u0 remote:284fca53}: filter unregistered
E/AndroidRuntime(10746): FATAL EXCEPTION: main
E/AndroidRuntime(10746): Process: ACMS.Process, PID: 10746
E/AndroidRuntime(10746): java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@329e86ef with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10746): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3326)
E/AndroidRuntime(10746): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/AndroidRuntime(10746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/AndroidRuntime(10746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10746): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10746): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10746): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10746): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10746): Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10746): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/AndroidRuntime(10746): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/AndroidRuntime(10746): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/AndroidRuntime(10746): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/AndroidRuntime(10746): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/AndroidRuntime(10746): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/AndroidRuntime(10746): 	... 9 more
E/AndroidRuntime(10746): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10746): 	at android.databa,se.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10746): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/AndroidRuntime(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10746): 	... 20 more
D/ResourcesManager(10709): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ActivityThread(10746): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
E/SQLiteLog(10746): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(10709): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/SQLiteDatabase(10746): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10746): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10746): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10746): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:118)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:128)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
E/SQLiteDatabase(10746): 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:138)
E/SQLiteDatabase(10746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10746): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10746): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process (10746): Sending signal. PID: 10746 SIG: 9
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname ACMS.Process
V/JNIHelp (10684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/JNIHelp (10669): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager(10709): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SamsungIME( 4443): getNextShiftState() cursorCapsMode : 0
W/BroadcastQueue( 3527): Skipping deliver [sec] BroadcastRecord{3d2d8449 u-1 android.intent.action.SCREEN_ON} to ReceiverList{3786d9dc 4306 com.google.android.gms.persistent/10014/u0 remote:26a48e4f}: filter unregistered
D/ResourcesManager(10709): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/ResourcesManager(10709): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(10709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteLog(10764): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(10764): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(10764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10764,): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(10764): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(10764): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(10764): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(10764): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(10764): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(10764): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(10764): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(10764): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(10764): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(10764): 	at java.lang.Thread.run(Thread.java:818)
W/GalaxyFinderApplication(10709): system/finder_cp/cpdata.xml file not found
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop189.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
W/ActivityThread(10684): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (10684): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@940728e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10684): Installed default security provider GmsCore_OpenSSL
W/BroadcastQueue( 3527): Skipping deliver [sec] BroadcastRecord{3d2d8449 u-1 android.intent.action.SCREEN_ON} to ReceiverList{11c5c06b 4306 com.google.android.gms.persistent/10014/u0 remote:e71c9ba}: filter unregistered
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
W/BroadcastQueue( 3527): Skipping deliver [sec] BroadcastRecord{3d2d8449 u-1 android.intent.action.SCREEN_ON} to ReceiverList{37247979 4306 com.google.android.gms.persistent/10014/u0 remote:3fcea640}: filter unregistered
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  (10793): MountEmulatedStorage()
E/Zygote  (10793): v2
I/libpersona(10793): KNOX_SDCARD checking this for 1000
I/libpersona(10793): KNOX_SDCARD not a persona
W/System  (10669): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3866d416: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread(10669): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller(10669): Installed default security provider GmsCore_OpenSSL
I/SELinux (10793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=10793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/accuweather( 5241): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5241): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5241): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5241): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): checkState() : APP TYPE = Full
,I/ActivityManager( 3527): Process ACMS.Process (pid 10746)(adj 0) has died(241,1246)
,W/ActivityManager( 3527): Scheduling restart of crashed service com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService in 1000ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/TimaKeyStoreProvider(10793): TimaSignature is unavailable
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/ActivityManager( 3527): Process com.android.settings (pid 10727)(adj 0) has died(241,1246)
,D/ActivityThread(10793): Added TimaKeyStore provider
,W/NativeLibraryUtils(10684): Failed to open lock file
W/NativeLibraryUtils(10684): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils(10684): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils(10684): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils(10684): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils(10684): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils(10684): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils(10684): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils(10684): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils(10684): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils(10684): 	... 3 more
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/GCM     (10684): COMPAT: Multi user not supported
,E/Zygote  (10814): MountEmulatedStorage()
E/Zygote  (10814): v2
I/libpersona(10814): KNOX_SDCARD checking this for 10059
I/libpersona(10814): KNOX_SDCARD not a persona
,I/SELinux (10814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10814): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10814 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthServiceInstalled() : HealthService is Installed.
,W/BroadcastQueue( 3527): Skipping deliver [sec] BroadcastRecord{3d2d8449 u-1 android.intent.action.SCREEN_ON} to ReceiverList{3c70a424 4306 com.google.android.gms.persistent/10014/u0 remote:119974b7}: filter unregistered
,D/ResourcesManager(10793): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(10764): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/SystemBroadcastReceiver(10255): [#DCM#] [DCM_Performance] onReceive completed in time  264 microsec. 
,I/SystemBroadcastReceiver(10255): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager(10255): [#DCM#] onReceive action = EVENT_SCREEN_ON
,I/DCMController(10255): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,W/NativeLibraryUtils(10669): Failed to open lock file
W/NativeLibraryUtils(10669): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils(10669): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils(10669): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils(10669): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils(10669): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils(10669): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils(10669): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils(10669): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils(10669): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils(10669): 	... 3 more
,D/com.sec.android.service.health.keyManager.KeyManager(10764): Current encrypted state : -1
,I/SecSQLiteOpenHelper(10764): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(10764): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper(10764): Open platform.db in secure mode
,D/SecSQLiteDatabase(10764): Android Version: 5.0.1
D/SecSQLiteDatabase(10764): Load library secsqlite.so for Android 5.0.1
,D/TimaKeyStoreProvider(10814): TimaSignature is unavailable
,D/ActivityThread(10814): Added TimaKeyStore provider
,D/LightsService( 3527): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3527) 
I/GAv4-SVC(10669): Google Analytics 8.4.89 is starting up.
D/LightsService( 3527): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,I/Sensors ( 3527): Light old sensor_state 0, new sensor_state : 512 en : 1
D/SensorManager( 3527): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService( 3527): turn on LED for fully charged
,I/SecSQLiteDatabase(10764): openSecureDatabase...
,I/SecSQLiteDatabase(10764): private openSecureDatabase...
I/SecSQLiteConnectionPool(10764): OpenSecure
I/SecSQLiteConnectionPool(10764): OpenSecure with password
I/SecSQLiteConnectionPool(10764): openSecureConnectionLocked
D/ResourcesManager(10814): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(10814): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/PopupuiReceiver(10793): onReceive() getAction : android.intent.action.PACKAGE_REMOVED
I/CAE     ( 3527): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3527): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3527): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3527): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2867): sendContextData: -76, 13, -46, 0
,D/SecContentProvider2( 3527): uri = -1 selection = getSealedState
D/SecContentProvider2( 3527): mCursor = null
I/PopupuiReceiver_KNOX(10793): getSealedState : true
,D/SecContentProvider2( 3527): uri = 15 selection = getSealedHideNotificationMessages
E/SecSQLiteDatabase(10764): Failed to open database '/data/data/com.sec.android.app.shealth/databases/platform.db'.
E/SecSQLiteDatabase(10764): samsung.database.sqlite.SecSQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnection.nativeOpen(Native Method)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnection.open(SecSQLiteConnection.java:233)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnection.openSecure(SecSQLiteConnection.java:217)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecureConnectionLocked(SecSQLiteConnectionPool.java:472)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecure(SecSQLiteConnectionPool.java:214)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecure(SecSQLiteConnectionPool.java:195)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteDatabase.openInnerSecureDatabase(SecSQLiteDatabase.java:821)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteDatabase.openSecureDatabase(SecSQLiteDatabase.java:794)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteDatabase.openSecureDatabase(SecSQLiteDatabase.java:678)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteOpenHelper.getDatabaseLocked(SecSQLiteOpenHelper.java:306)
E/SecSQLiteDatabase(10764): 	at samsung.database.sqlite.SecSQLiteOpenHelper.getWritableDatabase(SecSQLiteOpenHelper.java:243)
E/SecSQLiteDatabase(10764): 	at com.sec.android.service.health.keyManager.KeyManager.isDbOpened(Unknown Source)
E/SecSQLiteDatabase(10764): 	at com.sec.android.service.health.keyManager.KeyManager.arrangeDbKey(Unknown Source)
E/SecSQLiteDatabase(10764): 	at com.sec.android.service.health.keyManager.KeyManager.isDefaultPassword(Unknown Source)
E/SecSQLiteDatabase(10764): 	at com.sec.android.service.health.keyManager.KeyManager.isSecureStorageSupported(Unknown Source)
E/SecSQLiteDatabase(10764): 	at com.sec.android.service.health.keyManager.KeyManager.isSecureStorageSupported(Unknown Source)
E/SecSQLiteDatabase(10764): 	at com.sec.android.app.shealth.SHealthApplication.startKeyManager(SHealthApplication.java:221)
E/SecSQLiteDatabase(10764): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:199)
E/SecSQLiteDatabase(10764): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SecSQLiteDatabase(10764): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SecSQLiteDatabase(10764): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SecSQLiteDatabase(10764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SecSQLiteDatabase(10764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SecSQLiteDatabase(10764): 	at android.os.Looper.loop(Looper.java:145)
E/SecSQLiteDatabase(10764): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SecSQLiteDatabase(10764): 	at java.lang.reflect.Method.invoke(Native Method)
E/SecSQLiteDatabase(10764): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SecSQLiteDatabase(10764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SecSQLiteDatabase(10764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/SecSQLiteOpenHelper(10764): ...getDatabaseLocked(b,b,pwd)
,D/Compatibility(10814): onReceive() it will make start service
D/SecContentProvider2( 3527): mCursor = null
I/CAE     ( 3527): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 22, 15,
D/SensorHubManager( 3527): SendSensorHubData: send data = -63, 14, 14, 22, 15
,D/Sensorhubs( 2867): sendContextData: -63, 14, 14, 22, 15
,I/PopupuiReceiver_KNOX(10793): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 3527): uri = 15 selection = getCheckCoverPopupState
,D/SecContentProvider2( 3527): mCursor = null
,I/PopupuiReceiver_KNOX(10793): getCheckCoverPopupState : true
E/SQLiteLog(10684): (28) failed to open "/data/data/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
D/PopupuiReceiver(10793): Action package removed
,E/SQLiteDatabase(10684): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase(10684): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10684): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10684): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10684): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10684): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:67)
E/SQLiteDatabase(10684): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:409)
E/SQLiteDatabase(10684): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:416)
E/SQLiteDatabase(10684): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:329)
E/SQLiteDatabase(10684): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:121)
E/SQLiteDatabase(10684): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(10684): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(10684): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(10684): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10684): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10684): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10684): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10684): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10684): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(10684): Couldn't open ns.db for writing (will try read-only):
E/SQLiteOpenHelper(10684): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10684): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10684): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10684): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10684): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:67)
E/SQLiteOpenHelper(10684): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:409)
E/SQLiteOpenHelper(10684): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:416)
E/SQLiteOpenHelper(10684): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:329)
E/SQLiteOpenHelper(10684): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:121)
E/SQLiteOpenHelper(10684): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteOpenHelper(10684): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteOpenHelper(10684): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteOpenHelper(10684): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(10684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(10684): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(10684): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(10684): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(10684): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(10684): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/Compatibility(10814): onHandleIntent()
,D/Compatibility(10814): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10687, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/MotionRecognitionService( 3527):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/Compatibility(10814): found: 2
,W/SQLiteOpenHelper(10684): Opened ns.db in read-only mode
,D/Compatibility(10814): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10814): skipping ResolveInfo{9ef14c9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10814): considering ResolveInfo{2f9747ce com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10814): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10814): enabling receiver ResolveInfo{329e86ef com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,E/NetworkScheduler.SchedulerReceiver(10684): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver(10684): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/Compatibility(10814): enabling receiver ResolveInfo{267675fc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/MotionRecognitionService( 3527):  handler : SCREEN_OFF end 
,I/SecureStorage(10554): [INFO]: SPID(0x00000000)Processing data
,I/WifiNative-HAL( 3527): startHal
E/wifi    ( 3527): getStaticLongField sWifiHalHandle 0x8f88c7fc
D/wifi    ( 3527): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x801c16
I/WifiNative-HAL( 3527): Could not start hal
D/WifiStateMachine( 3527): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3527): handleScreenStateChanged Exit: false
,D/NotificationService( 3527): ACTION_SCREEN_OFF
,D/LightsService( 3527): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3527) 
D/LightsService( 3527): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
E/WifiStateMachine( 3527): setSuspendOptimizations: 4 true
E/WifiStateMachine( 3527): mSuspendOptNeedsDisabled 0
,D/Compatibility(10814): enabling receiver ResolveInfo{354b3485 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Credentials: uid 10019, gid 10019, pid 10554
I/SecureStorage( 2920): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/Compatibility(10814): enabling receiver ResolveInfo{3ee412da com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/EventHub( 3527): Removing device '/dev/input/event10' due to inotify event
,I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=off)
,D/Compatibility(10814): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/EventHub( 3527): Removing device '/dev/input/event7' due to inotify event
,I/UpdateIcingCorporaServi( 4048): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/SecExternalDisplayIntents_Java( 3527): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,I/EventHub( 3527): Removing device '/dev/input/event8' due to inotify event
,I/EventHub( 3527): Removing device '/dev/input/event9' due to inotify event
,D/SSRM:n  ( 3527): SIOP:: AP = 370, PST = 352, CUR = -707
,I/EventHub( 3527): Removing device '/dev/input/event11' due to inotify event
,D/IpRemoteDisplayController( 3527): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 3527): Bridge Server is not available
,E/SQLiteLog(10669): (28) failed to open "/data/data/com.google.android.gms/databases/google_analytics_v4.db" with flag (131138) and mode_t (0) due to error (30)
,D/UserAnalysis.UserAnalysisBroadcastReceiver(10032): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/UserAnalysis.SecurePlaceDbHelper(10032): SecurePlaceDbHelper() 
E/SQLiteLog( 4048): (10) POSIX Error : 9 SQLite Error : 3850
D/UserAnalysis.UserAnalysisBroadcastReceiver(10032): Create SecureDbHelper
E/SQLiteLog( 4048): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 4048): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4048): Process: com.google.android.googlequicksearchbox:search, PID: 4048
E/AndroidRuntime( 4048): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4048): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4048): 	at csx.d(PG:186)
E/AndroidRuntime( 4048): 	at cun.g(PG:594)
E/AndroidRuntime( 4048): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4048): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
E/AndroidRuntime( 4048): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4048): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4048): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4048): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4048): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4048): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4048): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4048): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4048): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3527): Removing device '/dev/input/event12' due to inotify event
,E/SQLiteLog(10032): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/SQLiteDatabase(10669): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase(10669): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10669): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10669): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:870)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase(10669): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase(10669): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(10669): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(10669): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(10669): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase(10669): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
,E/SQLiteDatabase(10032): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteDatabase(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteDatabase(10032): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10032): 	at java.lang.Thread.run(Thread.java:818)
E/GAv4-SVC(10669): Opening the database failed, dropping the table and recreating it
,E/SQLiteOpenHelper(10032): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10032): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteOpenHelper(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteOpenHelper(10032): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteOpenHelper(10032): 	at java.lang.Thread.run(Thread.java:818)
,E/SharedPreferencesImpl(10669): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog(10669): (28) failed to open "/data/data/com.google.android.gms/databases/google_analytics_v4.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10669): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase(10669): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10669): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10669): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10669): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:883)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase(10669): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase(10669): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase(10669): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(10669): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(10669): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(10669): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase(10669): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
E/GAv4-SVC(10669): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl(10669): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4-SVC(10669): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4-SVC(10669): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl(10669): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl(10669): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl(10669): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/EventHub( 3527): Removing device '/dev/input/event13' due to inotify event
,W/SQLiteOpenHelper(10032): Opened privacy in read-only mode
,E/SQLiteLog(10032): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10032): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
E/SQLiteDatabase(10032): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10032): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(10032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(10032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(10032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(10032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(10032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
I/libpersona(10853): KNOX_SDCARD checking this for 1000
W/System.err(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
I/libpersona(10853): KNOX_SDCARD not a persona
W/System.err(10032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10032): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
W/System.err(10032): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroad,castReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
W/System.err(10032): 	at java.lang.Thread.run(Thread.java:818)
E/Zygote  (10853): MountEmulatedStorage()
E/Zygote  (10853): v2
,I/SELinux (10853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=10853 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/GpsLocationProvider( 3527): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/EventHub( 3527): Removing device '/dev/input/event14' due to inotify event
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
,E/GpsLocationProvider( 3527): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3527): sExerciseIterface is not available
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop190.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,I/Process ( 4048): Sending signal. PID: 4048 SIG: 9
,D/TimaKeyStoreProvider(10853): TimaSignature is unavailable
,D/ActivityThread(10853): Added TimaKeyStore provider
,D/VolumePanel( 3695): registerReceiver: onReceive start 
,D/VolumePanel( 3695): registerReceiver ACTION_SCREEN_OFF start
,D/VolumePanel( 3695): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3695): registerReceiver: onReceive end 

```
