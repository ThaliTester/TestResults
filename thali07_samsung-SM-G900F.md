#### Test 5038801913f4183_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/Gmail   ( 5518): getAccountsCursor
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 8 -> 8
I/ActivityManager(  843): Waited long enough for: ServiceRecord{234e248d u0 com.samsung.android.providers.context/.ContextService}
W/GAV2    ( 5518): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 5518): Observing account changes for notifications
W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5518): Error finding the version of the Email provider.....
E/Gmail   ( 5518): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5518): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 5518): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 5518): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5518): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5518): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5518): We do not support migrating this version of the Email provider.
I/Gmail   ( 5518): getAccountsCursor
I/ActivityManager(  843): Killing 4257:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SettingSearchManagerReceiver( 1480): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1480): addSearchInfoDB
D/PowerManagerService(  843): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/PowerManagerService(  843): [s] DisplayPowerCallbacks : onStateChanged()
I/ActivityManager(  843): Waited long enough for: ServiceRecord{c1fe653 u0 com.android.settings/.wifi.WifiCredService}
W/libprocessgroup(  843): failed to open /acct/uid_10033/pid_4257/cgroup.procs: No such file or directory
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/lights  (  843): lcd : 1 +
I/art     (  843): Explicit concurrent mark sweep GC freed 24374(1594KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.509ms total 81.386ms
D/lights  (  843): lcd : 1 -
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
E/Zygote  ( 5558): MountEmulatedStorage()
E/Zygote  ( 5558): v2
I/libpersona( 5558): KNOX_SDCARD checking this for 10168
I/libpersona( 5558): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5558 uid=10168 gids={50168, 9997} abi=armeabi-v7a
I/SELinux ( 5558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5558): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5558): TimaSignature is unavailable
D/ActivityThread( 5558): Added TimaKeyStore provider
D/ResourcesManager( 5558): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
W/ContextImpl( 3681): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
I/DBG_DM  ( 3471): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
D/ResourcesManager( 1941): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/DBG_DM  ( 3471): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
E/DBG_DM  ( 3471): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
I/Process ( 3681): Sending signal. PID: 3681 SIG: 9
I/ActivityManager(  843): Waited long enough for: ServiceRecord{7b894af u0 com.android.settings/.wifi.hs20.Hs20UtilityService}
E/SQLiteLog( 5518): (283) recovered 666 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/DBG_DM  ( 3471): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
I/ActivityManager(  843): Process com.sec.android.app.sysscope (pid 3681)(adj 0) has died(62,674)
E/File    ( 5518): fail readDirectory() errno=2
I/Gmail   ( 5518): notifyAccountChanged
I/Gmail   ( 5518): getAccountsCursor
V/AlarmManager(  843): waitForAlarm result :4
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/LightSensor(  843): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
I/Gmail   ( 5518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5518): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5518): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/SettingSearchManagerReceiver( 1480): endInsert
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5578): MountEmulatedStorage()
E/Zygote  ( 5578): v2
I/libpersona( 5578): KNOX_SDCARD checking this for 1000
I/libpersona( 5578): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=5578 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/AndroidRuntime( 5556): 
D/AndroidRuntime( 5556): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SELinux ( 5578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BatteryService(  843): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
I/ActivityManager(  843): Killing 4403:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
I/SELinux ( 5578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BatteryService(  843): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  843): Sending ACTION_BATTERY_CHANGED.
E/SELinux ( 5578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5556): CheckJNI is OFF
D/AndroidRuntime( 5556): setted country_code = Germany
D/AndroidRuntime( 5556): setted countryiso_code = DE
D/MotionRecognitionService(  843):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/Gmail   ( 5518): getAccountsCursor
I/MotionRecognitionService(  843): Plugged
I/MotionRecognitionService(  843): setPowerConnected  = true
D/AndroidRuntime( 5556): setted sales_code = DBT
D/AndroidRuntime( 5556): readGMSProperty: start
D/AndroidRuntime( 5556): readGMSProperty: already setted!!
D/AndroidRuntime( 5556): readGMSProperty: end
D/AndroidRuntime( 5556): addProductProperty: start
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_DM  ( 3471): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 13 sec
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3471): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/TimaKeyStoreProvider( 5578): TimaSignature is unavailable
D/ActivityThread( 5578): Added TimaKeyStore provider
D/ConnectivityService(  843): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3471): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
D/ResourcesManager( 5578): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
E/DBG_DM  ( 3471): [llIlIIIIlllIlllllIll(232/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_4403/cgroup.procs: No such file or directory
I/DBG_DM  ( 3471): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
D/AssistantMenuSettingSearch( 5578): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5578): Make Setting DB
E/LightSensor(  843): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
W/ContextImpl( 5578): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
E/AffinityControl( 5556): AffinityControl: registerfunction enter
D/AndroidRuntime( 5556): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  843): inState():  stateMachine is null !!
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  843): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  843): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  843): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 843  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  843): mDVFSHelper.acquire()
D/FocusedStackFrame(  843): Set to : 0
I/HomeSyncInstallReceiver( 1473): This pkg do not need BT addr. Do nothing
D/Launcher.HomeView( 1498): onPause
D/Launcher( 1498): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 5556): Shutting down VM
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 5606): MountEmulatedStorage()
E/Zygote  ( 5606): v2
I/libpersona( 5606): KNOX_SDCARD checking this for 10015
I/libpersona( 5606): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  843): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5606 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 5606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5606): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
E/Zygote  ( 5615): MountEmulatedStorage()
E/Zygote  ( 5615): v2
I/libpersona( 5615): KNOX_SDCARD checking this for 10375
I/libpersona( 5615): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5615 uid=10375 gids={50375, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  843): Killing 4458:com.LocalFota/u0a120 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/SELinux ( 5615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 5606): TimaSignature is unavailable
E/SELinux ( 5615): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityThread( 5606): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  843): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/libprocessgroup(  843): failed to open /acct/uid_10120/pid_4458/cgroup.procs: No such file or directory
D/Launcher.HomeView( 1498): onStop
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/MicrophoneInputStream( 1594): mic_close gfk@11ea728a
D/TimaKeyStoreProvider( 5615): TimaSignature is unavailable
D/ActivityThread( 5615): Added TimaKeyStore provider
V/WindowOrientationListener(  843): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  843): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  843): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  843): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  843): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2106): [237392/6] Surface widget pause on instance = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2106): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 2106): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2106): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2106): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
V/AudioPolicyManager(  294): stopInput() input 26
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/AudioPolicyManager(  294): releaseInput() 26
V/AudioPolicyManager(  294): closeInput(26)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/HotwordRecognitionRnr( 1594): Hotword detection finished
I/HotwordRecognitionRnr( 1594): Stopping hotword detection.
V/audio_hw_primary(  294): in_standby: enter
D/ResourcesManager( 5606): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1498): destroyHardwareResources():420619034
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  843): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2106): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2106): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5615): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/audio_hw_primary(  294): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  294): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  294): disable_audio_route: reset mixer path: audio-record
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  294): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): disable_audio_route: exit
V/audio_hw_primary(  294): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: DEC2 Volume
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  294): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): stop_input_stream: exit: status(0)
V/audio_hw_primary(  294): in_standby: exit:  status(0)
V/audio_hw_primary(  294): adev_close_input_stream
V/audio_hw_primary(  294): in_standby: enter
V/audio_hw_primary(  294): in_standby: exit:  status(0)
E/audio_hw_primary(  294): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  294): releaseInput() exit
D/Launcher( 1498): onTrimMemory. Level: 20
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 5639): MountEmulatedStorage()
E/Zygote  ( 5639): v2
I/libpersona( 5639): KNOX_SDCARD checking this for 10016
I/libpersona( 5639): KNOX_SDCARD not a persona
D/SurfaceWidgetView( 1498): destroyHardwareResources():420619034
I/ActivityManager(  843): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5639 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/SELinux ( 5639): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  843): Killing 4480:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 5639): TimaSignature is unavailable
D/ActivityThread( 5639): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5639): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
I/ActivityManager(  843): Killing 4499:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
W/ResourcesManager( 5639): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5639): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 5615): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5615): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_4480/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 5615): Loading: webviewchromium
I/LibraryLoader( 5615): Time to load native libraries: 2 ms (timestamps 1642-1644)
I/LibraryLoader( 5615): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  843): failed to open /acct/uid_10138/pid_4499/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 5615): Binding Chromium to main looper Looper (main, tid 1) {8abaff1}
I/LibraryLoader( 5615): Expected native library version number "",actual native library version number ""
I/chromium( 5615): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5615): Initializing chromium process, renderers=0
W/art     ( 5615): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 5615): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/BluetoothAdapter( 5615): 102467542: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5615): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5615): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5615): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 5615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5615): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5615): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5615): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5615): Remote Branch: 
I/Adreno-EGL( 5615): Local Patches: 
I/Adreno-EGL( 5615): Reconstruct Branch: 
D/GroupCast_FileTools( 5639): [getDirectoryForImageResized : 295] cleaning!!
W/System.err( 5639): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 5639): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5639): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5639): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5639): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5639): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5639): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5639): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5639): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5639): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5639): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5639): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 5667): MountEmulatedStorage()
E/Zygote  ( 5667): v2
I/libpersona( 5667): KNOX_SDCARD checking this for 1000
I/libpersona( 5667): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5667 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  843): Killing 4521:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
I/art     (  333): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 11.057ms
I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.040ms
I/SELinux ( 5667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 8.019ms
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/libprocessgroup(  843): failed to open /acct/uid_10143/pid_4521/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5667): TimaSignature is unavailable
D/ActivityThread( 5667): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 5615): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/PCWCLIENTTRACE_LOG( 5667): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5667): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5667): new DMDBOpenHelper instance
W/chromium( 5615): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/PCWCLIENTTRACE_PushUtil( 5667): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5667): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5667): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5667): [onReceive] - android.intent.action.PACKAGE_ADDED
W/art     ( 5615): Attempt to remove local handle scope entry from IRT, ignoring
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/AwContents( 5615): onDetachedFromWindow called when already detached. Ignoring
E/Zygote  ( 5688): MountEmulatedStorage()
E/Zygote  ( 5688): v2
I/libpersona( 5688): KNOX_SDCARD checking this for 10034
I/libpersona( 5688): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5688 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  843): Killing 4563:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
I/SELinux ( 5688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SystemWebViewEngine( 5615): CordovaWebView is running on device made by: samsung
W/libprocessgroup(  843): failed to open /acct/uid_10012/pid_4563/cgroup.procs: No such file or directory
W/art     ( 5615): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5615): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 5688): TimaSignature is unavailable
D/ActivityThread( 5688): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Activity( 5615): performCreate Call secproduct feature valuefalse
D/Activity( 5615): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 5615): Render dirty regions requested: true
D/ActivityManager(  843): post active user change for 0
D/KnoxTimeoutHandler(  843): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  843): handleActiveUserChange for user 0
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/FeatureConfig( 5688): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 5688): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ResourcesManager( 5688): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 5615): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 5615): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 5688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/OpenGLRenderer( 5615): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 5688): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 5688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  843): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 5688): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 5688): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ResourcesManager( 5688): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ContextImpl(  843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl(  843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  843): Displayed com.example.hello/.MainActivity: +676ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ResourcesManager( 5688): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 5688): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 5615): Timeline: Activity_idle id: android.os.BinderProxy@30377761 time:42079
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 5688): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5688): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 5688): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 5615): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/LightSensor(  843): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
E/AndroidProtocolHandler( 5615): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/JsMessageQueue( 5615): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 5615): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5615): 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SA      ( 5010): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5010): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 5010): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10375 extra.user_handle.:0 ]
I/ActivityManager(  843): Killing 4419:com.android.vending/u0a30 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  843): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 843  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  843): mDVFSHelper.release()
I/Timeline(  843): Timeline: Activity_windows_visible id: ActivityRecord{2e6ebe78 u0 com.example.hello/.MainActivity t11} time:42235
D/CustomFrequencyManagerService(  843): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 843  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Mms/FreeMessageReceiver( 5186): onReceive, action : android.intent.action.PACKAGE_ADDED
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageReceiverService( 5186): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5186): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 5724): MountEmulatedStorage()
I/libpersona( 5724): KNOX_SDCARD checking this for 10051
E/Zygote  ( 5724): v2
I/libpersona( 5724): KNOX_SDCARD not a persona
I/ActivityManager(  843): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5724 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/SELinux ( 5724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Adreno-ES20( 5615): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5615): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/TimaKeyStoreProvider( 5724): TimaSignature is unavailable
D/ActivityThread( 5724): Added TimaKeyStore provider
,D/ResourcesManager( 5724): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/libprocessgroup(  843): failed to open /acct/uid_10030/pid_4419/cgroup.procs: No such file or directory
,W/ResourcesManager( 5724): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5724): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/jxcore_app_log( 5615): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359589760
,D/JX-Cordova( 5615): jxcore cordova android initializing
,D/MyFiles ( 5724): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,E/installd(  297): system dir 0 : /system/app/
E/installd(  297): system dir 1 : /system/priv-app/
E/installd(  297): system dir 2 : /vendor/app/
E/installd(  297): system dir 3 : /oem/app/
,I/TactileAssist(  843): enable value -1
,I/TactileAssist(  843): internal enable value -1
I/TactileAssist(  843): intensity value -1
I/TactileAssist(  843): saveAppList value true
,I/TactileAssist(  843): List of disabled apps :
,I/TactileAssist(  843): de.zalando.mobile
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  843): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,W/jxcore-log( 5615): Initializing JXcore engine
E/Zygote  ( 5751): MountEmulatedStorage()
E/Zygote  ( 5751): v2
I/libpersona( 5751): KNOX_SDCARD checking this for 10058
I/libpersona( 5751): KNOX_SDCARD not a persona
,W/jxcore-log( 5615): JXcore engine is ready
,I/ActivityManager(  843): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5751 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,W/jxcore-log( 5615): Starting JXcore engine
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/SELinux ( 5751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5751): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/auditd  ( 2075): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  843): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  843): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/TimaKeyStoreProvider( 5751): TimaSignature is unavailable
,D/ActivityThread( 5751): Added TimaKeyStore provider
,D/CustomFrequencyManagerService(  843): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 843  tag : ACTIVITY_RESUME_BOOSTER@10
D/ResourcesManager( 5751): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 5751): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 5751): onReceive() it will make start service
,D/Compatibility( 5751): onHandleIntent()
,D/Compatibility( 5751): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10375, android.intent.extra.user_handle=0}]
,D/Compatibility( 5751): found: 2
,D/Compatibility( 5751): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5751): skipping ResolveInfo{7b87175 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5751): considering ResolveInfo{3198250a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5751): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5751): enabling receiver ResolveInfo{28cd017b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5751): enabling receiver ResolveInfo{35df4b98 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 1594): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/ContextImpl( 5578): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 5751): enabling receiver ResolveInfo{8abaff1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5751): enabling receiver ResolveInfo{61b87d6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5751): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/jxcore-log( 5615): Platform android
W/jxcore-log( 5615): 
,W/jxcore-log( 5615): Process ARCH arm
W/jxcore-log( 5615): 
E/Zygote  ( 5770): MountEmulatedStorage()
E/Zygote  ( 5770): v2
I/libpersona( 5770): KNOX_SDCARD checking this for 10086
I/libpersona( 5770): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5770 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5770): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 5615): JXcore Cordova bridge is ready!
I/jxcore-log( 5615): 
,W/jxcore-log( 5615): JXcore engine is started
,D/TimaKeyStoreProvider( 5770): TimaSignature is unavailable
D/ActivityThread( 5770): Added TimaKeyStore provider
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
,D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5770): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 1941): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/jxcore-log( 5615): >> samsung-SM-G900F
E/jxcore-log( 5615): 
,I/jxcore-log( 5615): Total memory 1787449344
I/jxcore-log( 5615): 
,I/jxcore-log( 5615): Free memory 39165952
I/jxcore-log( 5615): 
I/jxcore-log( 5615): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5615): 
I/jxcore-log( 5615): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5615): 
I/jxcore-log( 5615): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5615): 
I/jxcore-log( 5615): Size 1080 1920
I/jxcore-log( 5615): 
I/jxcore-log( 5615): Screen Brightness 134
I/jxcore-log( 5615): 
E/jxcore-log( 5615): Dummy Error Log.
E/jxcore-log( 5615): 
,D/PushModule( 5770): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 5770): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 5770): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 5770): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 5770): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
W/ActivityManager(  843): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 5770): [1][a] ChatONV isn't installed.
D/ChatON  ( 5770): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5791): MountEmulatedStorage()
E/Zygote  ( 5791): v2
I/libpersona( 5791): KNOX_SDCARD checking this for 10098
I/libpersona( 5791): KNOX_SDCARD not a persona
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
I/ActivityManager(  843): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5791 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 4657:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
,I/SELinux ( 5791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5791): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  843): failed to open /acct/uid_10017/pid_4657/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5791): TimaSignature is unavailable
,D/ActivityThread( 5791): Added TimaKeyStore provider
,D/ResourcesManager( 5791): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 1594): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,D/DocsApplication( 5791): Installing DEX configuration.
,I/UpdateIcingCorporaServi( 1594): UpdateCorporaTask done [took 394 ms] updated apps [took 391 ms] 
,D/DexInstaller( 5791): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5791): Provided clientMode=RELEASE, packageInfo=PackageInfo{1befd0ac com.google.android.apps.docs}
,D/TAG     ( 5791): onCreate()
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/CrossAppStateProvider( 5791): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/jxcore-log( 5615): getBuffer is called!!!!
I/jxcore-log( 5615): 
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/SMD     (  288): DCD ON
,E/Watchdog(  843): !@Sync 1
,D/SettingsProvider(  843): name = audio_safe_volume_state
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/PackageManager(  843): [MSG] SEND_PENDING_BROADCAST
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  843): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/RegisteredServicesCache( 1473): empty dynamic service
,D/ResourcesManager( 1498): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/BitmapFactory( 1498): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SecContentProvider2(  843): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  843): mCursor = null
,D/BackupManagerService(  843): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  843): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  843): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BackupManagerService(  843): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  843): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3f9deb0f
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/GmsNetworkLocationProvi( 1554): DISABLE
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 5791): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GCoreNlp( 1554): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Zygote  ( 5836): MountEmulatedStorage()
E/Zygote  ( 5836): v2
I/libpersona( 5836): KNOX_SDCARD checking this for 10099
I/libpersona( 5836): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5836 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/SELinux ( 5836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5836): TimaSignature is unavailable
,D/ActivityThread( 5836): Added TimaKeyStore provider
,D/LocationProviderProxy(  843): applying state to connected service
,D/LocationProviderProxy(  843): applying state to connected service
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5836): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 5836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 5836): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5836): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5836): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5854): MountEmulatedStorage()
E/Zygote  ( 5854): v2
I/libpersona( 5854): KNOX_SDCARD checking this for 10033
I/libpersona( 5854): KNOX_SDCARD not a persona
,I/SELinux ( 5854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
I/SELinux ( 5854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5854): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  843): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5854 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5854): TimaSignature is unavailable
,D/ActivityThread( 5854): Added TimaKeyStore provider
,D/ResourcesManager( 5854): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 5854): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 5854): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5854): Inside WakeupProvider
,E/DatabaseUtils( 5854): Writing exception to parcel
E/DatabaseUtils( 5854): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5854): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5854): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5854): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5854): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5854): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5854): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5854): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5836): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 5836): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5836): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5836): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5836): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5836): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5836): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5836): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5836): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5836): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5836): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5836): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5836): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5836): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5836): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5836): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5836): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5836): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5836): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5836): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5836): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5836): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5836): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/VlingoApplication( 5854): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
E/DatabaseUtils( 5854): Writing exception to parcel
E/DatabaseUtils( 5854): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5854): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5854): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5854): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5854): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5854): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5854): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5854): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5854): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 5836): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 5836): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5836): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5836): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5836): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5836): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5836): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5836): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 5836): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 5836): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 5836): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 5836): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5836): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5836): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5836): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5836): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5836): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5836): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5836): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5836): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5836): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5836): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 5836): [DLApplication]-Init Called!:false
E/[CarMode]( 5836): [DLApplication]-Init Started!:true
W/GAV2    ( 5791): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/[CarModeFW]( 5836): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5836): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5836): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5836): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5836): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5836): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5836): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5836): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5836): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5836): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5836): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5836): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5836): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5836): ### com.android.internal.os.ZygoteInit::main(1194)
I/ActivityManager(  843): Killing 4901:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
D/BluetoothAdapter( 5854): 604213894: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5854): 604213894: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5854): 604213894: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5854): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 5836): initialize
D/[CarModeFW]( 5836): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5836): CDH-initiazlieCaches : after sync
W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_4901/cgroup.procs: No such file or directory
D/[CarModeFW]( 5836): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 5836): CDH-ContactDataHandler initiazlieCaches time : 14
D/[CarModeFW]( 5836): CDH-initiazlieCaches : end sync
D/BluetoothAdapter( 5836): 389616908: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5836): 389616908: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5836): DrivingManager-initialize...
I/SensorService(  843): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  843): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  843): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/VlingoApplication( 5854): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5854): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 5836): Need to enable context aware info
V/MediaPlayer-JNI( 5836): native_setup
V/MediaPlayer( 5836): constructor
,V/MediaPlayer( 5836): setListener
E/MediaPlayer-JNI( 5836): QCMediaPlayer mediaplayer NOT present
,I/art     (  843): Explicit concurrent mark sweep GC freed 43113(2MB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.089ms total 79.585ms
,D/[CarModeFW]( 5836): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5836): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5836): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450198976913
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450198976914
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450198976915
D/[CarModeFW]( 5836): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450198976916
,D/[CarModeFW]( 5836): RecommendHandler-selection = type = '3'
,D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450198976920
,D/TP/SmsProvider( 1480): query,matched:2, calling pid = 5836
,D/TP/SmsProvider( 1480): query,matched:2, calling pid = 5836
,D/[CarMode]( 5836): [DLServiceManager]-requestRecommendedLocationList
,D/TP/SmsProvider( 1480): match 2:Elapsed time : 1.291 ms
,D/TP/SmsProvider( 1480): match 2:Elapsed time : 1.306 ms
,D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450198976927
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,I/[CarMode]( 5836): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/Zygote  ( 5887): MountEmulatedStorage()
E/Zygote  ( 5887): v2
I/libpersona( 5887): KNOX_SDCARD checking this for 10020
I/libpersona( 5887): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5887 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,D/[CarModeFW]( 5836): CDH-buildContactCacheWireFrame : cur len =0
E/[CarMode]( 5836): [DLApplication]-Init End!:true
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/SELinux ( 5887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 5836):  getInboxList smsCursor : 50
,I/SELinux ( 5887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5887): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TP/MmsProvider( 1480): Query uri=content://mms/inbox, match=2, calling pid = 5836
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5902): MountEmulatedStorage()
E/Zygote  ( 5902): v2
I/libpersona( 5902): KNOX_SDCARD checking this for 10003
I/libpersona( 5902): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5902 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 5902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 5887): TimaSignature is unavailable
,I/SELinux ( 5902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ActivityThread( 5887): Added TimaKeyStore provider
,E/SELinux ( 5902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MessageDataHandler( 5836):  getInboxList mmsCursor : 54
,D/TP/MmsProvider( 1480): Query uri=content://mms, match=0, calling pid = 5836
,D/[CarMode]( 5836): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode]( 5836): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/[CarModeFW]( 5836): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5836): RecommendHandler-selection = type = '3'
,I/MessageDataHandler( 5836): getUnreadMessageCount :0
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 114
D/MessageDataHandler( 5836):  getInboxList mms,sms cursor join : 13
,I/UpdateManagerReceiver( 5836): Intent : android.intent.action.PACKAGE_ADDEDTue Dec 15 18:02:57 GMT+01:00 2015
,D/TP/MmsSmsProvider( 1480): query,matched:0, calling pid = 5836
V/TP/MmsSmsProvider( 1480): getSimpleConversations entered.
D/TimaKeyStoreProvider( 5902): TimaSignature is unavailable
,D/ActivityThread( 5902): Added TimaKeyStore provider
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1480): match 0:Elapsed time : 1.712 ms
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5887): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,E/Zygote  ( 5917): MountEmulatedStorage()
I/libpersona( 5917): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5917): v2
I/libpersona( 5917): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5917 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 4923:com.android.email/u0a163 (adj 15): bgCount ##41
,I/SELinux ( 5917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5917): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 4430): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/TP/MmsSmsProvider( 1480): query,matched:13, calling pid = 5836
,D/ResourcesManager( 5902): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/TP/MmsSmsProvider( 1480): match 13:Elapsed time : 0.710 ms
,D/[CarModeFW]( 5836): PushMessageService-onCreate
,I/ActivityManager(  843): Killing 5069:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/FaceInterface( 5320): startFaceScan() : going on
D/FaceInterface( 5320): startFaceScan() is called.
W/libprocessgroup(  843): failed to open /acct/uid_10163/pid_4923/cgroup.procs: No such file or directory
I/ActivityManager(  843): Killing 4615:com.android.providers.calendar/u0a46 (adj 15): bgCount ##42
,I/ActivityManager(  843): Killing 4952:com.sec.android.soagent/u0a37 (adj 15): bgCount ##43
,D/MessageDataHandler( 5836):  getInboxList address cursor : 12
,D/TP/MmsSmsProvider( 1480): query,matched:0, calling pid = 5836
,V/TP/MmsSmsProvider( 1480): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1480): match 0:Elapsed time : 1.182 ms
,D/ContentApp( 1223): startScan() is called.
,D/FaceValue( 1223): mSleepTime: 800
D/FaceValue( 1223): mMaxThreadNum: 2
,D/ContentApp( 1223): startScan() is end.
,D/ContentApp( 1223): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1223): isNeedToRestore : start
,D/MessageDataHandler( 5836):  getInboxList thread cursor : 13
,D/TimaKeyStoreProvider( 5917): TimaSignature is unavailable
,D/ActivityThread( 5917): Added TimaKeyStore provider
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
D/MessageDataHandler( 5836):  thread, addr result: 14
I/[CarModeFW]( 5836): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 220
I/[CarModeFW]( 5836): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 221
,D/[CarModeFW]( 5836): PushMessageManager-onServiceConnected
D/[CarModeFW]( 5836): PushMessageService-registerPushMessageServiceListener
,D/ResourcesManager( 5917): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/UserAnalysis.PlaceProvider( 5902): PlaceProvider onCreate()
,W/ContextImpl( 5917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5934): MountEmulatedStorage()
E/Zygote  ( 5934): v2
I/libpersona( 5934): KNOX_SDCARD checking this for 10112
I/libpersona( 5934): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5934 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/art     (  333): Explicit concurrent mark sweep GC freed 8746(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 13.605ms
,D/UserAnalysis.SecureDbManager( 5902): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5902): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5902): Create SecureDbHelper
,I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.816ms
,I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.074ms
,I/SELinux ( 5934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 5917): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,D/IntelligenceServiceApplication( 5902): onCreate()
,I/SQLiteSecureOpenHelper( 5902): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 5902): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5902): Open Place.db in secure mode
,D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 339
,E/FilterInstaller( 5917): There is no requred permission
,W/ContextImpl(  843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  843): Killing 4580:com.android.calendar/u0a150 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5934): TimaSignature is unavailable
,D/ActivityThread( 5934): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 5902): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 5902): ...getDatabaseLocked(b,b,pwd)
I/[CarModeFW]( 5836): -[snowdeer] Rec : Missed Call : 350
,D/[CarModeFW]( 5836): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 5836): MyPlaceProvider-=============
D/[CarModeFW]( 5836): MyPlaceProvider-=============
D/[CarModeFW]( 5836): MyPlaceProvider-=============
D/[CarModeFW]( 5836): MyPlaceProvider-=============
D/[CarModeFW]( 5836): MyPlaceProvider----End print all data in content provider---
,D/[CarModeFW]( 5836): MyPlaceProvider-==============
D/[CarModeFW]( 5836): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5836): MyPlaceProvider-==============
D/[CarModeFW]( 5836): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5836): MyPlaceProvider-==============
D/[CarModeFW]( 5836): MyPlaceProvider-latitude is not valid
,I/[CarModeFW]( 5836): -[snowdeer] Rec : Favorite : 10
,D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 359
,D/ResourcesManager( 5934): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarMode]( 5836): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@63ea90a0, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@70439816] LOCATIONS
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 5934): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5934): Not GearManger package! 
,E/Zygote  ( 5952): MountEmulatedStorage()
E/Zygote  ( 5952): v2
I/libpersona( 5952): KNOX_SDCARD checking this for 10046
I/libpersona( 5952): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5952 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[CarModeFW]( 5836): -[snowdeer] Rec : CallLog : 22
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/Zygote  ( 5958): MountEmulatedStorage()
E/Zygote  ( 5958): v2
I/libpersona( 5958): KNOX_SDCARD checking this for 10118
I/libpersona( 5958): KNOX_SDCARD not a persona
,I/FaceInterface( 5320): startFaceScan() : going on
,D/FaceInterface( 5320): startFaceScan() is called.
,I/ActivityManager(  843): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=5958 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 4198:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,I/SELinux ( 5952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SELinux ( 5958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/SELinux ( 5952): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ContentApp( 1223): startScan() is called.
,I/SELinux ( 5958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ContentApp( 1223): startScan() is end.
E/SELinux ( 5958): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  843): failed to open /acct/uid_10149/pid_5069/cgroup.procs: No such file or directory
,W/libprocessgroup(  843): failed to open /acct/uid_10046/pid_4615/cgroup.procs: No such file or directory
W/libprocessgroup(  843): failed to open /acct/uid_10037/pid_4952/cgroup.procs: No such file or directory
,D/ContentApp( 1223): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1223): isNeedToRestore : start
,D/TimaKeyStoreProvider( 5958): TimaSignature is unavailable
,D/ActivityThread( 5958): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5952): TimaSignature is unavailable
,D/ActivityThread( 5952): Added TimaKeyStore provider
,W/libprocessgroup(  843): failed to open /acct/uid_10150/pid_4580/cgroup.procs: No such file or directory
,I/ActivityManager(  843): Killing 5103:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 5958): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,D/ResourcesManager( 5952): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 5958): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SSRM:m  (  843): SIOP:: AP = 470, PST = 430, CUR = 300
D/X       (  843): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 5252): [#DCM#] [DCM_Performance] onReceive completed in time  276 microsec. 
,D/ContentApp( 1223):  LEVEL : 0
,I/SystemBroadcastReceiver( 5252): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 5252): [#DCM#] onReceive action = EVENT_SIOP
,W/libprocessgroup(  843): failed to open /acct/uid_10117/pid_4198/cgroup.procs: No such file or directory
,D/MagazineService Version( 5958): Magazine-Administrator: 11
,D/MagazineService Version( 5958): Magazine-Provider: 14
,I/CalendarProvider2( 5952): CalendarProvider2.onCreate() called
,D/MagazineService Version( 5958): Magazine-Channel: 14
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5986): MountEmulatedStorage()
I/libpersona( 5986): KNOX_SDCARD checking this for 10118
E/Zygote  ( 5986): v2
I/libpersona( 5986): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=5986 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 5958): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5958): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,E/LightSensor(  843): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/SELinux ( 5986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5986): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_5103/cgroup.procs: No such file or directory
,I/MagazineService::MagazineService( 5958): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 5998): MountEmulatedStorage()
I/libpersona( 5998): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5998): v2
I/libpersona( 5998): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 5958): [onHandleIntent] Send broadcast to (com.example.hello).
,I/SELinux ( 5998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5986): TimaSignature is unavailable
,D/ActivityThread( 5986): Added TimaKeyStore provider
,I/ActivityManager(  843): Killing 5136:com.sec.factory/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 5986): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 5986): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5998): TimaSignature is unavailable
,D/ActivityThread( 5998): Added TimaKeyStore provider
,D/ResourcesManager( 5998): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 5986): [onCreate]
,D/Headlines( 5986): Breath.onCreate
,D/HeadlinesCardManager( 5986): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 5986): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 5986): CardProvider Library : 14
,D/MagazineService::CardProviderContentProvider( 5958): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 5958): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5986): registerCardProvider: provider already exists.
,D/Headlines( 5986): HeadlinesDataCenter ctor
D/Headlines( 5986): HeadlinesDataCenter. mLocale = en_US
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_5136/cgroup.procs: No such file or directory
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6019): MountEmulatedStorage()
I/libpersona( 6019): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6019): v2
I/libpersona( 6019): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6019 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/HeadlinesChannelUtil( 5986): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 5986): HeadlinesCardManager : constructor welcome :YES
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/SELinux ( 6019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6019): TimaSignature is unavailable
,D/ActivityThread( 6019): Added TimaKeyStore provider
,I/ActivityManager(  843): Killing 4815:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 5483): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,I/[CarModeFW]( 5836): -[snowdeer] Rec : Schedule : 420
,D/ResourcesManager( 6019): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/[CarModeFW]( 5836): -[snowdeer] Rec : During DL app : 3
,I/[CarModeFW]( 5836): -[snowdeer] Rec : Location Sharing : 2
I/[CarModeFW]( 5836): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 822
,I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 5836): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5836): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 821
,I/System.out( 5854): INFO:Resource not found:/Common.properties Using default values
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6019): Received: android.intent.action.PACKAGE_ADDED
,E/Zygote  ( 6040): MountEmulatedStorage()
I/libpersona( 6040): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6040): v2
I/libpersona( 6040): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6040 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 6019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/SELinux ( 6040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6040): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  843): failed to open /acct/uid_10078/pid_4815/cgroup.procs: No such file or directory
,D/AcmsService( 6019): Enter Oncreate
,D/AcmsServiceMonitor( 6019): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6019): creating AcmsCore
D/AcmsCore( 6019): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6019): AcmsCore
,D/TimaKeyStoreProvider( 6040): TimaSignature is unavailable
,D/ActivityThread( 6040): Added TimaKeyStore provider
,D/AcmsCore( 6019): init
D/AcmsCore( 6019): Looper handler is not null
D/AcmsCore( 6019): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6019): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6019): Incrementing - Counter value: 1
,D/AcmsCore( 6019): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6019): onStartCommand
D/AcmsCertificateMngr( 6019): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6019): AcmsRevocationMngr
,D/AcmsService( 6019): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6019): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6019): Incrementing - Counter value: 2
D/AcmsService( 6019): Incremented Counter Value : onStartCommand
,I/ActivityManager(  843): Waited long enough for: ServiceRecord{900175c u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/ActivityThread( 6019): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ResourcesManager( 6040): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 6040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 6019): Inside handle Intent
,D/AcmsService( 6019): App added - package name: com.example.hello
D/AcmsCore( 6019): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6019): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6019): Incrementing - Counter value: 3
D/AcmsCore( 6019): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6019): Decremented Counter Value : handleStartIntent
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/AcmsServiceMonitor( 6019): Decrementing - Counter value: 2
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/GAV2    ( 5518): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6073): MountEmulatedStorage()
,E/Zygote  ( 6073): v2
I/libpersona( 6073): KNOX_SDCARD checking this for 10166
I/libpersona( 6073): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6073 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GLSActivity( 1672): [ac] getting account id
,D/TimaKeyStoreProvider( 6073): TimaSignature is unavailable
,D/ActivityThread( 6073): Added TimaKeyStore provider
,I/GLSUser ( 1672): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/ResourcesManager( 6073): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 6073): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/KidsPlatformStub( 6073): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6091): MountEmulatedStorage()
,E/Zygote  ( 6091): v2
I/libpersona( 6091): KNOX_SDCARD checking this for 10170
I/libpersona( 6091): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6091 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 6091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6091): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6091): TimaSignature is unavailable
,D/ActivityThread( 6091): Added TimaKeyStore provider
,D/ResourcesManager( 6091): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6091): (284) automatic index on shooting_modes(title_id)
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/art     (  843): Explicit concurrent mark sweep GC freed 17231(1013KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.180ms total 87.788ms
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6108): MountEmulatedStorage()
I/libpersona( 6108): KNOX_SDCARD checking this for 10030
E/Zygote  ( 6108): v2
I/libpersona( 6108): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6108 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 5233:com.wsomacp/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 6108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6108): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6108): TimaSignature is unavailable
,D/ActivityThread( 6108): Added TimaKeyStore provider
,W/libprocessgroup(  843): failed to open /acct/uid_10025/pid_5233/cgroup.procs: No such file or directory
,D/ResourcesManager( 6108): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/SMD     (  288): DCD ON
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,I/CalendarProvider2( 5952): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  843): Killing 5337:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/Finsky  ( 6108): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup(  843): failed to open /acct/uid_10002/pid_5337/cgroup.procs: No such file or directory
,D/Finsky  ( 6108): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  843): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 10012
I/libpersona( 6145): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6145 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6108): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6108): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
,D/ActivityThread( 6145): Added TimaKeyStore provider
,D/ResourcesManager( 6145): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6145): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6145): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6145): VM with version 2.1.0 has multidex support
,I/MultiDex( 6145): install
I/MultiDex( 6145): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  843): Killing 5392:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,V/JNIHelp ( 6145): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 6108): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6108): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/ConfigFetchService( 1941): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1941): launchTask
,D/Finsky  ( 6108): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/AcmsKeyStoreHelper( 6019):  getKeyStoreForApplication Enter
,D/Vision  ( 1941): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1941): Failed to find package metadata for com.example.hello
,D/Vision  ( 1941): No vision deps
D/ResourcesManager( 1941): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,E/Zygote  ( 6170): MountEmulatedStorage()
I/libpersona( 6170): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6170): v2
I/libpersona( 6170): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6170 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/ConfigFetchTask( 1941): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X71eMVSEdY_-eGOmvNLvjJyq8W-UGUb2zqJB5sqeF_B3XHn8_EE_PMe0FHfcf4bm3LvZ3Rz1D512UPCxlC6dVkFvxmxyfinFShzU5qQsxUFJHCR76frCGKD80Td15gv3Qp9bztoppfZ65Cr0Xc7eVavZMm-o6XgOnt453xZaGQT__3igRkDOrVA5zQ_MxsP9rT-exQhLqPL8RwqNZwxq4Oj9vCzgo4fcbAolBp6cUEV4oS-Ew
,I/art     (  333): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 10.950ms
,I/AcmsKeyStoreHelper( 6019): Key Store exist
I/AcmsKeyStoreHelper( 6019): Hence loading the keystore file
,I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 240us total 7.926ms
,W/ActivityThread( 6145): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6145): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35165058: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6145): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 6170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6170): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.741ms
,I/PeopleContactsSync( 1941): CP2 sync disabled
,W/libprocessgroup(  843): failed to open /acct/uid_10172/pid_5392/cgroup.procs: No such file or directory
,D/Finsky  ( 6108): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PowerManagerService(  843): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  843): Nap time (uid 1000)...
I/PowerManagerService(  843): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  843): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  843): setDeviceInteractive: 0
D/DisplayPowerController(  843): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  843): [s] DisplayPowerCallbacks : onStateChanged()
D/InputManager-JNI(  843): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  843): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  843): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  843): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  843): handleSandman : startDream()
,D/InputManager-JNI(  843): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  843): handleSandman : startDreaming, but isDreaming false
,D/TimaKeyStoreProvider( 6170): TimaSignature is unavailable
,D/ActivityThread( 6170): Added TimaKeyStore provider
,D/InputManager-JNI(  843): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,I/PowerManagerService(  843): Sleeping (uid 1000)...
,D/PowerManagerService(  843): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  843): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  843): [input device light] handleInputDeviceLightOff
D/SContextService(  843): 	.unregisterCallback : 1, client=
,D/SContextService(  843): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3f7828e4, Service = Auto Rotation, used = 1
,I/GoogleURLConnFactory( 1941): Using platform SSLCertificateSocketFactory
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,D/ResourcesManager( 6170): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/Adreno-EGL(  843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  843): Build Date: 03/03/15 Tue
I/Adreno-EGL(  843): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  843): Remote Branch: 
I/Adreno-EGL(  843): Local Patches: 
I/Adreno-EGL(  843): Reconstruct Branch: 
,W/CAE     (  843): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  843): stop(ContextProvider.java:149)
,V/CAE     (  843): clear(AutoRotationRunner.java:182)
,V/CAE     (  843): disable(AutoRotationRunner.java:171)
,I/CAE     (  843): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  843): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,D/CAE     (  843): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  843): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/LightSensor(  843): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/CAE     (  843): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  843): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  843): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  843): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  843): removeSContextService() : service = Auto Rotation
D/SContextService(  843): ===== SContext Service List =====
,D/SContextManager(  843):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2ee0d86d, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3305): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3305): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  843): ColorFade: onAnimationStart
D/DisplayPowerController(  843): getFinalBrightness : 8 -> 0
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
,D/DisplayPowerController(  843): getFinalBrightness : 8 -> 0
,I/CAE     (  843): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  843): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  843): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  843): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  300): sendContextData: -76, 13, -47, 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,D/DisplayPowerController(  843): getFinalBrightness : 8 -> 0
,D/lights  (  843): lcd : 0 +
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/InputMethodManagerService(  843): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/lights  (  843): lcd : 0 -
,D/MotionRecognitionService(  843):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/AcmsKeyStoreHelper( 6019):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6019): getKeyStoreForApplication success 
D/AcmsCore( 6019): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6019): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6019): Decrementing - Counter value: 1
D/AcmsCore( 6019): AcmsCore: ACMS_APP_INSTALLED
,E/MotionRecognitionService(  843):  handler : SCREEN_ON end
,D/AcmsCore( 6019): This is NOT a valid MirrorLink app
D/AcmsCore( 6019): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6019): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6019): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6019): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6019): getSvcCounter - Counter value: 0
D/AcmsService( 6019): Enter onDestroy
I/AcmsService( 6019): cleanUp(): inside service clean up
D/AcmsCore( 6019): AcmsCore: inside DeInit
D/AcmsCore( 6019): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6019): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6019): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6019): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6019): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 6019): getSvcCounter - Counter value: 0
D/AcmsService( 6019): killing acms process
I/Process ( 6019): Sending signal. PID: 6019 SIG: 9
,D/NotificationService(  843): ACTION_SCREEN_ON
,D/LightsService(  843): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 843) 
D/LightsService(  843): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  843): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  843): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=on
V/voice   (  294): voice_set_parameters: enter: screen_state=on
V/voice   (  294): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  294): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  294): adev_set_parameters: exit
I/System.out( 1941): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1941): (HTTPLog)-Static: isShipBuild true
I/System.out( 1941): (HTTPLog)-Thread-236-533430397: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SecExternalDisplayIntents_Java(  843): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/WifiNative-HAL(  843): startHal
,E/wifi    (  843): getStaticLongField sWifiHalHandle 0x956df7fc
D/wifi    (  843): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x501a22
I/WifiNative-HAL(  843): Could not start hal
,D/WifiStateMachine(  843): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  843): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  843): setSuspendOptimizations: 4 false
E/WifiStateMachine(  843): mSuspendOptNeedsDisabled 4
,D/IpRemoteDisplayController(  843): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  843): Bridge Server is not available
,W/ConfigFetchTask( 1941): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1941): fetch service done; releasing wakelock
,I/ConfigFetchService( 1941): stopping self
,I/ActivityManager(  843): Process ACMS.Process (pid 6019)(adj 0) has died(45,596)
,D/PersonaManagerService(  843): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  843): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1473): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/ResourcesManager( 6145): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/NfcService( 1473): call the applyRotuiing
,E/LightSensor(  843): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  843): mCallbacks.updateBrightness()
D/DisplayPowerController(  843): getFinalBrightness : 8 -> 0
,I/SamsungIME( 1841): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2106): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/DisplayPowerState(  843): !@ ColorFade entry
,D/DisplayPowerController(  843): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  843): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  843): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  843): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  843): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  843): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  843): unregisterListener ::   
,E/Sensors (  843): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  843): unregisterListener ::   
,D/SurfaceWidget.Renderer( 2106): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2106): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2106): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2106): [237392/6] SurfaceWidget drawing first frame
,D/DisplayPowerController(  843): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  843): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  843): Display changed displayId=0
,D/DisplayPowerController(  843): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,I/ActivityManager(  843): Killing 5252:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6145): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotifUtils( 5518): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
V/Finsky  ( 6108): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/BroadcastQueue(  843): Failure sending broadcast Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
W/BroadcastQueue(  843): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  843): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:484)
W/BroadcastQueue(  843): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:600)
W/BroadcastQueue(  843): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:870)
W/BroadcastQueue(  843): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:18912)
W/BroadcastQueue(  843): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue(  843): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2964)
W/BroadcastQueue(  843): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SSRM:m  (  843): SIOP:: AP = 470, PST = 435, CUR = 300
,W/libprocessgroup(  843): failed to open /acct/uid_10004/pid_5252/cgroup.procs: No such file or directory
,D/LightsService(  843): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 843) 
,D/LightsService(  843): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  843): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  843): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  843): turn on LED for charging
,I/NotifUtils( 5518): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
,I/CAE     (  843): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  843): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  843): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  843): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
,I/CAE     (  843): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 2, 59,
D/SensorHubManager(  843): SendSensorHubData: send data = -63, 14, 17, 2, 59
,D/Sensorhubs(  300): sendContextData: -63, 14, 17, 2, 59
I/NotifUtils( 5518): Showing notification with unreadCount of 7 and unseenCount of 7
,E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  843): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6205): MountEmulatedStorage()
E/Zygote  ( 6205): v2
I/libpersona( 6205): KNOX_SDCARD checking this for 10117
I/libpersona( 6205): KNOX_SDCARD not a persona
,I/ActivityManager(  843): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6205 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6205): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/MotionRecognitionService(  843):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  843):  handler : SCREEN_OFF end 
,D/NotificationService(  843): ACTION_SCREEN_OFF
I/WifiNative-HAL(  843): startHal
D/LightsService(  843): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 843) 
E/wifi    (  843): getStaticLongField sWifiHalHandle 0x956df7fc
D/LightsService(  843): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/wifi    (  843): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x401612
I/WifiNative-HAL(  843): Could not start hal
D/WifiStateMachine(  843): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  843): handleScreenStateChanged Exit: false
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  294): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  294): adev_set_parameters: exit
,E/WifiStateMachine(  843): setSuspendOptimizations: 4 true
E/WifiStateMachine(  843): mSuspendOptNeedsDisabled 0
,I/SecExternalDisplayIntents_Java(  843): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  843): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  843): Bridge Server is not available
,D/TimaKeyStoreProvider( 6205): TimaSignature is unavailable
,D/ActivityThread( 6205): Added TimaKeyStore provider
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/ResourcesManager( 6205): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/PersonaManagerService(  843): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  843): MSG_ACTION_SCREEN_OFF called
,W/ResourcesManager( 6205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NfcService( 1473): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  843): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService(  843): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  843): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  843): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  843): Invalid hint ID.
,I/QCOM PowerHAL(  843): Got set_interactive hint
,I/PowerManagerService(  843): [PWL] Off : 0s ago
I/PowerManagerService(  843): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  843): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  843): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=843, ws=WorkSource{10117}) (elapsedTime=18614)
I/PowerManagerService(  843): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1941, ws=null) (elapsedTime=14102)
I/PowerManagerService(  843): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  843): [PWL]     mDisplayReady : false
I/PowerManagerService(  843): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  843): getFinalBrightness : 0 -> 0
D/PowerManagerService(  843): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  843): [PWL] sb release: PowerManagerService.Display
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2106): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2106): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  843): waitForAlarm result :4
,W/ActivityManager(  843): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  843): getTasks: caller 10086 does not hold GET_TASKS; limiting output
D/PowerManagerService(  843): [PWL] sb release: PowerManagerService.Broadcasts
D/Finsky  ( 6108): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/SSRM:m  (  843): SIOP:: AP = 470, PST = 440, CUR = 300
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleDatabaseHelper( 1941): cleanUpNonGplusAccounts done.
,V/AlarmManager(  843): waitForAlarm result :8
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
,W/Finsky  ( 6108): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothAdapter( 5615): disable()
,E/BluetoothManagerService(  843): Bluetooth is already disabled. DO NOT disable again.
,D/ResourcesManager( 6205): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/WifiService(  843): New client listening to asynchronous messages
,I/WifiManager( 5615): packageName : com.example.hello
,D/SecContentProvider(  843): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  843): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  843): mCursor = null
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiService(  843): setWifiEnabled: false pid=5615, uid=10375
E/WifiService(  843): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  843): name = wifi_on
I/jxcore-log( 5615): ****TEST TOOK:  5044  ms ****
I/jxcore-log( 5615): 
,I/jxcore-log( 5615): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5615): 
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  843): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/LightsService(  843): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  843): Light old sensor_state 8704, new sensor_state : 8192 en : 0
I/Babel   ( 6205): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6205): MmsConfig.loadMmsSettings
D/SensorManager(  843): unregisterListener ::   
D/lights  (  843): led_pattern : 1 +
D/lights  (  843): led_pattern : 1 -
D/LightsService(  843): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/Babel   ( 6205): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,I/Babel   ( 6205): MmsConfig.loadFromDatabase
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6205): MmsConfig.loadFromResources
,W/VideoCapabilities( 6205): Unrecognized profile 2130706433 for video/avc
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc nullnull
,W/Settings( 6205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 6205): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ms-wma
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6205): Unsupported mime audio/amr-wb-plus
,W/Finsky  ( 6108): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6205): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6205): Unsupported mime video/mp43
,W/VideoCapabilities( 6205): Unsupported mime video/sorenson
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,I/VideoCapabilities( 6205): Unsupported profile 4 for video/mp4v-es
,D/AndroidRuntime( 6238): 
D/AndroidRuntime( 6238): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6238): CheckJNI is OFF
,D/AndroidRuntime( 6238): setted country_code = Germany
,D/AndroidRuntime( 6238): setted countryiso_code = DE
,D/AndroidRuntime( 6238): setted sales_code = DBT
D/AndroidRuntime( 6238): readGMSProperty: start
D/AndroidRuntime( 6238): readGMSProperty: already setted!!
,D/AndroidRuntime( 6238): readGMSProperty: end
D/AndroidRuntime( 6238): addProductProperty: start
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,D/SSRM:a  (  843): DeviceInfo:: 000000000000
D/SSRM:a  (  843): SettingsAirViewInfo:: 000000000
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,I/art     (  843): Explicit concurrent mark sweep GC freed 31034(2MB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 35MB/51MB, paused 1.442ms total 102.346ms
,E/AffinityControl( 6238): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6238): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  843): START PACKAGE DELETE: observer{497229299}
D/PackageManager(  843): pkg{<packageName>}
D/PackageManager(  843): user{0}
D/PackageManager(  843): caller{2000}
D/PackageManager(  843): flags{3}
D/PersonaManagerService(  843): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  843): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  843): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  843): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  843): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  843): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  843): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  843): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  843): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  843): getApplicationUninstallationEnabled :  enabled true
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/PackageManager(  843): !@killApplicatoin: 10375, uninstall pkg
,I/ActivityManager(  843): Force stopping com.example.hello appid=10375 user=0: pkg removed
,I/ActivityManager(  843): Killing 5615:com.example.hello/u0a375 (adj 0): stop com.example.hello
,I/ActivityManager(  843):   Force finishing activity ActivityRecord{2e6ebe78 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  843): Set to : 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/WindowState(  843): WIN DEATH: Window{5461897 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  843): Client connection lost with reason: 4
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
,I/ActivityManager(  843): Force stopping com.example.hello appid=10375 user=-1: uninstall pkg
,I/art     ( 4430): Explicit concurrent mark sweep GC freed 2863(161KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 306us total 24.140ms
,I/ActivityManager(  843):   Force finishing activity ActivityRecord{2e6ebe78 u0 com.example.hello/.MainActivity t11 f}
W/ActivityManager(  843): Duplicate finish request for ActivityRecord{2e6ebe78 u0 com.example.hello/.MainActivity t11 f}
,I/art     ( 5917): Explicit concurrent mark sweep GC freed 9290(428KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 356us total 32.792ms
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1498): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SamsungIME( 1841): mOCRHelper is null
,W/ResourcesManager( 1498): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/InputReader(  843): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1554): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1498): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1498): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 1498): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1498): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1498): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ConnectivityService(  843): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SecContentProvider2(  843): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  843): mCursor = null
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/RegisteredServicesCache( 1473): empty dynamic service
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/EnterpriseDeviceManagerService(  843): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  843): Admin package name: com.google.android.gms
V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService(  843): PackageReceiver onReceive()
,I/HarmonyEASService(  843): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  843): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/art     (  843): Explicit concurrent mark sweep GC freed 20113(1685KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 4.558ms total 239.809ms
,D/BackupManagerService(  843): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  843): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  843): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  843): uID is 10375
V/EnterpriseBillingPolicy(  843): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  843): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  843): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  843): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  843): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  843): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  843): getBillingProfileForVpnEngine - end - null
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TaskPersister(  843): removeObsoleteFile: deleting file=11_task.xml
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/PackageManager(  843): delete codoeFile: 
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/PackageManager(  843): result of delete: 1{497229299}
,D/AndroidRuntime( 6238): Shutting down VM
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ResourcesManager(  843): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/GCM     ( 1672): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1672): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/GmsCoreStatsServiceLauncher( 1941): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/WearableService( 5043): callingUid 10012, callindPid: 5043
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,E/MDM     ( 1554): [154] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1941): Restart initialization of location
,D/ResourcesManager(  843): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  843): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  843): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  843): clearDefaults: com.example.hello
,I/CrashAnrDetector(  843): onPackageRemoved : com.example.hello
,I/art     ( 1672): Explicit concurrent mark sweep GC freed 14438(796KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 569us total 33.377ms
,V/BitmapFactory( 5518): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/NotifUtils( 5518): Account: 61035162 vibrate: false
,I/NotifUtils( 5518): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|1729800001|null|10114
,D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  843): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,V/AudioPolicyManager(  294): getOutputsForDevice device 0002 -> 0002
I/AudioService(  843): getStreamVolume 5 index 110
,D/LightsService(  843): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 843) 
D/LightsService(  843): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x12 | SvcLED(id=4) set On
E/LightSensor(  843): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  843): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/ResourcesManager( 1169): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1803): (284) automatic index on sqlite_sq_A15501F0(STAT_DATA_ID)
,I/GAV2    ( 5791): Thread[GAThread,5,main]: No campaign data found.
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
,D/SecContentProvider2(  843): mCursor = null
D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
I/ValidateNoPeople(  843): final affinity: 0.0
I/ValidateNoPeople(  843): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
,I/ValidateNoPeople(  843): final affinity: 0.0
D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  843): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|-865450363|null|10114
I/ValidateNoPeople(  843): final affinity: 0.0
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,I/ValidateNoPeople(  843): final affinity: 0.0
,W/Finsky  ( 6108): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  843): final affinity: 0.0
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4545): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4545): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4545): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Finsky  ( 6108): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,D/Finsky  ( 6108): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
,F/libc    ( 4545): Fatal signal 7 (SIGBUS), code 2, fault addr 0x79882de5 in tid 4545 (oid.app.shealth)
,D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2ef88311
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,D/Finsky  ( 6108): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,E/SharedPreferencesImpl( 6108): Couldn't create directory for SharedPreferences file /data/data/com.android.vending/shared_prefs/finsky.xml
,E/audit_log( 2075): File locking failed. error= Bad file number
,F/libc    ( 4545): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2075): File locking failed. error= Bad file number
,F/libc    ( 1169): Fatal signal 7 (SIGBUS), code 2, fault addr 0x75da8bc8 in tid 1169 (ndroid.systemui)
,F/libc    ( 1169): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
F/libc    ( 5836): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78f364ae in tid 5848 (HeapTrimmerDaem)
F/libc    ( 5836): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2075): File locking failed. error= Bad file number
,D/DeviceConnectionService( 1554): client connected with version: 7571000
,F/libc    ( 1554): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f92efe0 in tid 1566 (Binder_1)
,F/libc    ( 1554): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2075): File locking failed. error= Bad file number
,I/ActivityManager(  843): Process com.sec.android.automotive.drivelink (pid 5836)(adj 15) has died(166,558)
,I/ActivityManager(  843): Process com.sec.android.app.shealth (pid 4545)(adj 0) has died(168,556)
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  843): final affinity: 0.0
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,I/EventHub(  843): Removing device '/dev/input/event4' due to inotify event
,D/SecContentProvider2(  843): uri = 14 selection = getSealedState
D/SecContentProvider2(  843): mCursor = null
,D/SecContentProvider2(  843): KnoxCustomManagerService offline: service is not available
,I/Zygote  (  333): Process 4545 exited due to signal (7)
,D/ApplicationPolicy(  843): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  843): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  843): Validating: 0|com.google.android.gm|1919793178|null|10114
I/ValidateNoPeople(  843): final affinity: 0.0
D/WindowManager(  843): showStatusBarByNotification() mOpenByNotification=false
,I/Zygote  (  333): Process 5836 exited due to signal (7)
,I/EventHub(  843): Removing device '/dev/input/event5' due to inotify event
,I/WindowState(  843): WIN DEATH: Window{8b6dda7 u0 StatusBar}
,F/libc    (  843): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747937b0 in tid 843 (system_server)
F/libc    (  843): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,I/SurfaceFlinger(  249): id=9 Removed StatusBar (6/7)
,W/GmsClient( 6108): service died
,F/libc    ( 6108): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa06dc700 in tid 6108 (android.vending)
,F/libc    ( 6108): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,I/Zygote  (  333): Process 1169 exited due to signal (7)
,I/Zygote  (  333): Process 1554 exited due to signal (7)
,I/Zygote  (  333): Process 6108 exited due to signal (7)
,I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'wifi' died
E/audit_log( 2075): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
F/libc    ( 1941): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b73a8 in tid 1941 (gle.android.gms)
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_,service' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
F/libc    ( 1941): Unable to open connection to debuggerd: Connection refused
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
W/Sensors ( 1293): sensorservice died [0xaed21300]
W/AudioFlinger(  294): power manager service died !!!
W/AudioFlinger(  294): power manager service died !!!,
W/Sensors ( 1480): sensorservice died [0xaef63340]
W/Sensors ( 1459): sensorservice died [0xaef99b80]
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/6)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/4)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/3)
,I/SurfaceFlinger(  249): id=6 Removed DimLayer (1/2)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/2)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/2)
E/audit_log( 2075): File locking failed. error= Bad file number
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/2)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/2)
,I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/2)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/1)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/1)
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (0/0)
I/SurfaceFlinger(  249): id=14 Removed ColorFade (-2/0)
W/Sensors ( 1498): sensorservice died [0xaef63380],
W/Sensors ( 5320): sensorservice died [0xaeffb600]
F/libc    ( 1672): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f245fac in tid 6278 (IntentService[L)
F/libc    ( 1672): Unable to open connection to debuggerd: Connection refused
,W/Sensors ( 2178): sensorservice died [0xaef99bc0]
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
E/WifiManager( 1594): Channel connection lost
E/WifiManager( 1480): Channel connection lost
,E/WifiManager( 1293): Channel connection lost
,F/libc    ( 5518): Fatal signal 7 (SIGBUS), code 2, fault addr 0x744058fe in tid 6201 (IntentService[G)
F/libc    ( 5518): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,F/libc    ( 5854): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb4aee61c in tid 5867 (HeapTrimmerDaem)
,F/libc    ( 5854): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,F/libc    ( 1594): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78a7ed8f in tid 1594 (earchbox:search)
F/libc    ( 1594): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,F/libc    ( 6145): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6dd5 in tid 6145 (android.gms:car)
,F/libc    ( 6145): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2075): File locking failed. error= Bad file number
,I/Zygote  (  333): Process 5518 exited due to signal (7)
I/Zygote  (  333): Process 1941 exited due to signal (7)
I/Zygote  (  333): Process 5854 exited due to signal (7)
,I/Zygote  (  333): Process 6145 exited due to signal (7)
,I/Zygote  (  333): Process 1672 exited due to signal (7)
,E/SMD     (  288): DCD ON
,I/Zygote  (  333): Process 1594 exited due to signal (7)
,F/libc    ( 4430): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78057c17 in tid 4464 (AppProvider)
,F/libc    ( 4430): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2075): File locking failed. error= Bad file number
,I/Zygote  (  333): Process 4430 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,E/installd(  297): eof
E/installd(  297): failed to read size
I/installd(  297): closing connection
,I/SurfaceFlinger(  249): Disp[0] Orientation 0=>0
,E/qdoverlay(  249): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  249): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  249): hwc_set_primary: display commit fail for 0 dpy!
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
