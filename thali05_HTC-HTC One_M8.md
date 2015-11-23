#### Test 5038801932cd575_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of system
I/ActivityManager(  964): Recipient 1944
--------- beginning of main
D/Process (  964): killProcessQuiet, pid=1944
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10025/pid_1944/cgroup.procs: No such file or directory
I/ActionCombine( 1199): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/DotMatrix( 1199): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/Process (  964): killProcessQuiet, pid=3574
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/DotMatrix( 1199): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1123): setHTCTheme(com.android.settings,true,33751145)
I/ActivityManager(  964): Killing 3574:com.htc.cs.pns/u0a74 (adj 15): empty #17
I/RemoteViews( 1123): apply : com.android.settings 2 6 2 36
I/ActivityManager(  964): Recipient 3574
I/RemoteViews( 1123): reapply : com.android.settings 0 36
D/Process (  964): killProcessQuiet, pid=3574
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10074/pid_3574/cgroup.procs: No such file or directory
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  964): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4031 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
D/SmartDim(  964): Init customizeScreenOffDelayClass error
E/MP-Decision( 2271): Update arg 2
W/BroadcastQueue(  964): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{12555433 u0 ReceiverList{f47afa2 964 system/1000/u0 local:1a0ba76d}}
I/SensorManager(  964): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@3680f597, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): enable: get sensor name = Accelerometer Sensor
W/SensorService(  964): pid=964, uid=1000
W/SensorService(  964): Active sensors: size = 2
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  964): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3680f597, eanble = 1, strlen(mName) = 36
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  964): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@33a4b944
W/SensorService(  964): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@38371fb6
W/SensorService(  964): Listener[2] = com.htc.smartdim.sensor_eye@3680f597
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  964): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@3680f597, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): enable: get sensor name = CM36282 Proximity sensor
W/SensorService(  964): pid=964, uid=1000
W/SensorService(  964): Active sensors: size = 3
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  964): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  964): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3680f597, eanble = 1, strlen(mName) = 36
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  964): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@33a4b944
W/SensorService(  964): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@38371fb6
W/SensorService(  964): Listener[2] = com.htc.smartdim.sensor_eye@3680f597
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  964): Killing 3605:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3605
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  964): Recipient 3605
D/Process (  964): killProcessQuiet, pid=3605
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_3605/cgroup.procs: No such file or directory
I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4052 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/MP-Decision( 2271): Update arg 1
I/Prism.ItemManager( 1476): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1476): loadItems() com.htc.launcher.pageview.WidgetManager@22d8110d +
I/Prism.WidgetManager( 1476): onLoadItems() +
W/ResourcesManager( 1476): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4052, uid=10075, userID:0
D/Finsky  ( 4052): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/ResourcesManager( 1476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Prism.WidgetManager( 1476): onLoadItems() -
I/Prism.ItemManager( 1476): loadItems() com.htc.launcher.pageview.WidgetManager@22d8110d -
D/Finsky  ( 4052): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4088 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 4052): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4052): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 4088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4052, uid=10075, userID:0
D/Volley  ( 4052): [543] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4052): [536] DiskBasedCache.clear: Cache cleared.
I/MultiDex( 4088): VM with version 2.1.0 has multidex support
I/MultiDex( 4088): install
I/MultiDex( 4088): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  964): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4109 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  964): Killing 3634:com.htc.showme/u0a85 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3634
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  964): Recipient 3634
D/Process (  964): killProcessQuiet, pid=3634
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10085/pid_3634/cgroup.procs: No such file or directory
D/Finsky  ( 4052): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4052): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 4052): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 4109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4088): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 4052): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/MultiDex( 4109): VM with version 2.1.0 has multidex support
I/MultiDex( 4109): install
I/MultiDex( 4109): VM has multidex support, MultiDex support library is disabled.
W/ActivityThread( 4088): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4088): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2815e518: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4088): Installed default security provider GmsCore_OpenSSL
D/PhoneApp( 1412): EVENT_QUERY_MO_PACKAGES
I/CalendarProvider2( 4003): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4003): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/PhoneApp( 1412): -- N1 =0
I/ActivityManager(  964): Killing 3653:com.htc.feedback/u0a87 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3653
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/PhoneApp( 1412): -- N2 =0
D/PhoneApp( 1412): -- N3 =0
I/ActivityManager(  964): Recipient 3653
D/Process (  964): killProcessQuiet, pid=3653
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10087/pid_3653/cgroup.procs: No such file or directory
I/ActivityManager(  964): Killing 3674:com.htc.updater/u0a88 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3674
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
V/JNIHelp ( 4109): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  964): Recipient 3674
W/ActivityThread( 4109): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4109): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37005eb6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4109): Installed default security provider GmsCore_OpenSSL
I/HtcModeClient( 3072): handler message = 4011
E/HtcModeClient( 3072): Check connection and retry 2 times.
D/Process (  964): killProcessQuiet, pid=3674
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10088/pid_3674/cgroup.procs: No such file or directory
V/Finsky  ( 4052): [1] GearheadStateMonitor.onReady: sIsProjecting:false
E/MP-Decision( 2271): Update arg 2
V/GLSUser ( 1753): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  964): Killing 3544:com.htc.sense.mms/u0a67 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3544
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  964): Recipient 3544
D/PMS     (  964): acquireWL(16c2ac38): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1753 10025 null
D/Process (  964): killProcessQuiet, pid=3544
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10067/pid_3544/cgroup.procs: No such file or directory
V/GmsCoreStatsServiceLauncher( 4109): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
I/NotificationStore( 1753): System rebooted after Notification storage file was last written
I/NotificationStore( 1753): Deleting the file
D/PMS     (  964): releaseWL(16c2ac38): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
D/PersistentNotificationBroadcastReceiver( 1753): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
W/InstanceID/Rpc( 4109): Found 10025
E/MP-Decision( 2271): Update arg 1
D/FileApkUtils( 4109): Spent 34ms computing apk sha1.
D/FileApkUtils( 4109): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4109): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/PMS     (  964): acquireWL(361fa702): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4109 10025 null
D/DexOptUtils( 4109): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4109): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
D/PMS     (  964): acquireWL(1de8e813): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1753, uid=10025, userID:0
I/ActivityManager(  964): Delay finish: com.google.android.gms/.nearby.sharing.NearbySharingBroadcastReceiver
D/GmsModuleFndr( 4109): Beginning GMS chimera module scan
W/asset   ( 4109): Copying FileAsset 0xb81bea10 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
D/PMS     (  964): acquireWL(3604b449): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
D/GmsModuleFndr( 4109): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/PMS     (  964): acquireWL(2865314e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
D/ChimeraCfgMgr( 4109): Beginning module configuration check
D/PMS     (  964): releaseWL(1de8e813): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  964): releaseWL(361fa702): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  964): releaseWL(3604b449): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
I/ActivityManager(  964): Resuming delayed broadcast
D/ChimeraCfgMgr( 4109): Module APKs unchanged, check complete
I/CheckinService( 4109): Disabling old GoogleServicesFramework version
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4109, uid=10025, userID:0
I/CheckinService( 4109): Checking schedule, now: 1448315195966 next: 1448301414586
I/CheckinService( 4109): active receiver: enabled
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/art     (  964): Explicit concurrent mark sweep GC freed 23546(1234KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 993us total 80.946ms
D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PMS     (  964): acquireWL(a721c26): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  964): acquireWL(14ebf6bd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4109 10025 null
D/GCM     ( 4109): COMPAT: Multi user not supported
D/GCM     ( 1753): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/ActivityManager(  964): Delay finish: com.google.android.gms/.kids.chimera.SystemEventReceiverProxy
I/GCoreUlr( 4109): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/PMS     (  964): acquireWL(2c697bac): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
,D/SystemUpdateService( 4109): onCreate
I/GCoreUlr( 1694): DispatchingService.onCreate()
D/SystemUpdateService( 4109): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/ConfigService( 1753): onCreate
D/PMS     (  964): acquireWL(3451b0b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4109, uid=10025, userID:0
I/art     ( 4109): Background sticky concurrent mark sweep GC freed 379(48KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 4MB/4MB, paused 7.346ms total 21.858ms
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4109, uid=10025, userID:0
I/ConfigFetchService( 4109): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
V/AuthZen ( 4109): Handling intent: android.intent.action.BOOT_COMPLETED
D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/AuthZenEventHandler( 4109): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
D/PMS     (  964): releaseWL(2865314e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4109, uid=10025, userID:0
I/Kids    ( 4109): [KidAccountFixer] No network connection
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4109, uid=10025, userID:0
W/art     ( 4109): Suspending all threads took: 7.654ms
I/art     ( 4109): Background partial concurrent mark sweep GC freed 2903(258KB) AllocSpace objects, 3(48KB) LOS objects, 49% free, 4MB/8MB, paused 10.239ms total 43.709ms
I/SystemUpdateService( 4109): cancelUpdate (empty URL)
I/SystemUpdateService( 4109): active receiver: disabled
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4109, uid=10025, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4109, uid=10025, userID:0
D/PMS     (  964): acquireWL(2b2a586): PARTIAL_WAKE_LOCK  Icing 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
I/ConfigFetchService( 4109): service connected
W/BaseAppContext( 4109): Using Auth Proxy for data requests.
I/GCoreUlr( 1694): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/art     ( 1753): Explicit concurrent mark sweep GC freed 5501(348KB) AllocSpace objects, 6(96KB) LOS objects, 51% free, 3MB/7MB, paused 1.130ms total 28.627ms
I/GLSUser ( 4109): [ChannelManager] Attempting to channel bind connection HttpClient.
D/ConfigFetchService( 4109): ConfigApi connection successful.
D/PMS     (  964): releaseWL(a721c26): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
D/SystemUpdateService( 4109): onDestroy
I/GLSUser ( 4109): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
D/PMS     (  964): releaseWL(2b2a586): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
W/System.err(  964): java.lang.Throwable: stack dump
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0fb7e3:true
I/AuthZen ( 4109): Fetching signing key...
I/ActivityManager(  964): Resuming delayed broadcast
I/AuthZen ( 4109): Signing key fetched successfully!
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1694, uid=10025, userID:0
W/BaseAppContext( 4109): Using Auth Proxy for data requests.
I/AuthZen ( 4109): Starting Enrollment...
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4207 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/AuthZen ( 4109): getting auth token. Attempt 0
I/GLSActivity( 1753): [ac] getting account id
W/ResourcesManager( 4207): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/PMS     (  964): releaseWL(2c697bac): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10025 com.google.android.gms}
I/GLSUser ( 1753): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1753): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/GLSUser ( 1753): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AuthZen ( 4109): Error getting auth token
E/AuthZen ( 4109): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4109): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4109): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4109): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4109): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4109): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4109): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4109): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4109): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4109): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4109): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GCoreUlr( 1694): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  964): acquireWL(1810cf79): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  964): releaseWL(1810cf79): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/GCoreUlr( 1694): Unbound from all location providers
D/PMS     (  964): releaseWL(3451b0b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
D/a       ( 4109): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 4109): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4109): Clearing transaction cache
I/GCoreUlr( 1694): DispatchingService.onDestroy()
D/PMS     (  964): acquireWL(ef564be): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  964): releaseWL(ef564be): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/GCoreUlr( 1694): Unbound from all location providers
E/cutils-trace( 4189): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4189): ====startRecUseTime====
D/htc.customization.log.level( 4189):  is 
W/CustomizationLogLevel( 4189): Level value is invalid, use default level 2
I/ActivityManager(  964): Waited long enough for: ServiceRecord{2222d08d u0 com.google.android.gms/.gcm.GcmService}
D/CustomizationManager( 4189):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__203
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__304
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 4189): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 4189): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4189): Parsing tag category name = system
I/CustomizationCIDLoader( 4189): Parsing tag category name = application
I/CustomizationCIDLoader( 4189): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4189): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4189): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4189): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4189): Parsing tag category name = ACC
D/CustomizationManager( 4189):  Read CID file spent 0.085 (s)
D/CustomizationManager( 4189):  All configurations done spent 0.086 (s)
E/ActTriggerJNI( 4189): open library fail.
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
E/MP-Decision( 2271): Update arg 2
W/asset   (  964): Copying FileAsset 0xb858b008 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  964): acquireHCC(2145ea35): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 964 1000 null
E/MP-Decision( 2271): Update arg 4
E/MP-Decision( 2271): Update arg "0 190 240 240".
E/MP-Decision( 2271): Update arg "0 75 400 400".
I/AnimationUtil(  964): isHTCRecent(HelloWorld/Recent screens.)/3
D/PMS     (  964): acquireWL(27f7083b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 964 1000 null
D/PMS     (  964): acquireHCC(3e77f4b1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 964 1000 null
I/FeedHostManager( 1476): [onPause]
I/FeedProviderManager( 1476): onPause
I/FeedHostManager( 1476): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@114bb16
I/SocialFeedProvider( 1476): +onPause
I/SocialFeedProvider( 1476): -onPause
D/HtcSystemUPManager(  964): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager(  964): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4237 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService(  964): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
W/asset   ( 4237): Copying FileAsset 0xb81226f0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1476): [trimMemory] 20
D/PMS     (  964): acquireWL(36a2796e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 964 1000 null
D/PMS     (  964): releaseWL(36a2796e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/WebViewFactory( 4237): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4237): Time to load native libraries: 6 ms (timestamps 4016-4022)
I/LibraryLoader( 4237): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4237): Binding Chromium to main looper Looper (main, tid 1) {16e8166e}
I/LibraryLoader( 4237): Expected native library version number "",actual native library version number ""
I/chromium( 4237): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4237): Initializing chromium process, singleProcess=true
W/art     ( 4237): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4237): ApplicationContext is null in ApplicationStatus
,W/chromium( 4237): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4237): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 4237): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 4237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4237): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 4237): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4237): Build Date: 12/11/14 Thu
I/Adreno-EGL( 4237): Local Branch: 
I/Adreno-EGL( 4237): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 4237): Local Patches: NONE
I/Adreno-EGL( 4237): Reconstruct Branch: NOTHING
,I/Babel_SMS( 4207): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4207): MmsConfig.loadMmsSettings
,I/ActivityManager(  964): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4269 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/art     (  471): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 140us total 10.428ms,
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 8.958ms,
,W/System.err(  964): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3674a2d2:true
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  964): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4207, uid=10120, userID:0
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 9.656ms,
D/BluetoothAdapter( 4237): 510975787: getState() :  mService = null. Returning STATE_OFF
,W/HtcWrapAdjustableCursorFactory( 4269): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 4269): onCreate
,D/MmsCustomizationProvider( 4269): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4269): GetPrviateResource
,V/GetPrviateResource( 4269): GetPrviateResource
,D/MessageCustFlag( 4269): sense_version=6.0
,D/BTAccessoryUtil( 4269): createReceiver
,D/BTAccessoryUtil( 4269): registerReceiver return intent = null
,D/MessageCustFlag( 4269): sku_id=99
,D/HtcBuildUtils( 4269): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4269): Cannot find qct_8960_interface, use default value instead
,W/Settings( 4207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4269): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_Crash( 4207): startup - clean
,I/Babel_SMS( 4207): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
I/Babel_SMS( 4207): MmsConfig.loadFromDatabase
,W/art     ( 4207): Suspending all threads took: 21.478ms
,W/art     ( 4237): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4237): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4237): CordovaWebView is running on device made by: HTC
,E/Babel_SMS( 4207): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4207): MmsConfig.loadFromResources
,E/Babel_SMS( 4207): canonicalizeMccMnc: invalid mccmnc nullnull
W/art     ( 4237): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4237): Attempt to remove local handle scope entry from IRT, ignoring
I/Babel   ( 4207): deleted: false for 0
I/Babel_SMS( 4207): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4207, uid=10120, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4207, uid=10120, userID:0
,W/VideoCapabilities( 4207): Unrecognized profile 2130706433 for video/avc
,D/Atlas   ( 4237): Validating map...
,W/chromium( 4237): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/VideoCapabilities( 4207): Unsupported mime video/x-ms-wmv
,W/AudioCapabilities( 4207): Unsupported mime audio/qcelp,
W/AudioCapabilities( 4207): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4207): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4207): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4207): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4207): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4207): onServiceConnected
,W/Babel   ( 4207): Attempted to change video mute state without an active call.
,I/InputMethodManager( 4237): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@e8fe91b, mServedView=org.apache.cordova.engine.SystemWebView{322eaab8 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1832f091
,I/InputMethodManagerService(  964): Disable input method client, pid=1476
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  964): Enable input method client, pid=4237
,I/ActivityManager(  964): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4311 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Process (  964): killProcessQuiet, pid=3733
,I/ActivityManager(  964): Killing 3733:com.htc.android.worldclock/u0a96 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
,I/ActivityManager(  964): Recipient 3733
,D/Process (  964): killProcessQuiet, pid=3733
D/PMS     (  964): releaseWL(27f7083b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10096/pid_3733/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Displayed com.example.hello/.MainActivity: +755ms
,W/XT9_C   ( 1280): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
,I/XT9_C   ( 1280): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1280): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1280): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 4237): Cannot call determinedVisibility() - never saw a connection for the pid: 4237
,I/chromium( 4237): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10),
,D/JsMessageQueue( 4237): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4237): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ResourcesManager( 4311): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4311): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4311): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/jxcore_app_log( 4237): JniHelper::setJavaVM(0xb7077b98), pthread_self() = -1204921816
,D/JX-Cordova( 4237): jxcore cordova android initializing
,W/System  ( 4311): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4311): Installed default security provider GmsCore_OpenSSL
,W/jxcore-log( 4237): Initializing JXcore engine,
W/jxcore-log( 4237): JXcore engine is ready
,W/jxcore-log( 4237): Starting JXcore engine,
,E/cutils-trace( 4344): Error opening trace file: No such file or directory (2)
,I/dex2oat ( 4344): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-337265094.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-337265094.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/jxcore-log( 4237): Platform android
W/jxcore-log( 4237): 
,W/jxcore-log( 4237): Process ARCH arm
W/jxcore-log( 4237): 
,I/dex2oat ( 4344): dex2oat took 57.716ms (threads: 4)
,E/YouTube MDX( 4311): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 4311): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4311): [NET] android_getaddrinfofornet-, SUCCESS
,I/jxcore-log( 4237): JXcore Cordova bridge is ready!
I/jxcore-log( 4237): 
W/jxcore-log( 4237): JXcore engine is started
,E/jxcore-log( 4237): >> HTC-HTC One_M8,
E/jxcore-log( 4237): 
I/jxcore-log( 4237): Total memory 1912020992,
I/jxcore-log( 4237): 
I/jxcore-log( 4237): Free memory 165281792
I/jxcore-log( 4237): 
I/jxcore-log( 4237): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4237): 
I/jxcore-log( 4237): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4237): 
,I/jxcore-log( 4237): userPath [ 'www' ]
I/jxcore-log( 4237): 
E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
I/jxcore-log( 4237): Size 1080 1776
I/jxcore-log( 4237): 
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4311): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
I/jxcore-log( 4237): Screen Brightness 142
I/jxcore-log( 4237): 
E/jxcore-log( 4237): Dummy Error Log.
E/jxcore-log( 4237): 
,I/art     (  964): Explicit concurrent mark sweep GC freed 14887(814KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 16MB/24MB, paused 846us total 66.670ms,
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4311): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4311): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4311): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4311): Found 10025
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4311): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  964): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4398 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/Process (  964): killProcessQuiet, pid=3713,
I/ActivityManager(  964): Killing 3713:com.htc.videocenter/u0a91 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 3713
,D/Process (  964): killProcessQuiet, pid=3713
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10091/pid_3713/cgroup.procs: No such file or directory
,D/PMS     (  964): releaseWL(b764a18): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,I/jxcore-log( 4237): getBuffer is called!!!!,
I/jxcore-log( 4237): 
,D/LocationManagerService(  964): getProviders()=[passive, network],
,D/PMS     (  964): releaseHCC(2145ea35): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  964): releaseHCC(3e77f4b1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/MP-Decision( 2271): Update arg 1,
,I/ActivityManager(  964): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4424 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4398, uid=10089, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4398, uid=10089, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4398, uid=10089, userID:0
,I/ActivityManager(  964): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4451 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  964): Killing 3758:com.htc.tiber2/u0a91 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=3758,
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  964): Recipient 3758,
,D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 6
,I/VelvetNetworkClient( 4398): Network connection not availble,
,I/ActivityManager(  964): Killing 3799:com.google.android.configupdater/u0a104 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=3799
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 3799,
,D/Process (  964): killProcessQuiet, pid=3758
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10091/pid_3758/cgroup.procs: No such file or directory
,D/Process (  964): killProcessQuiet, pid=3799,
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10104/pid_3799/cgroup.procs: No such file or directory
,W/LocationOracleImpl( 4398): Best location was null,
,I/WebViewFactory( 4398): Loading com.google.android.webview version 44.0.2403.90 (code 240309000),
,I/LibraryLoader( 4398): Time to load native libraries: 2 ms (timestamps 6209-6211),
I/LibraryLoader( 4398): Expected native library version number "",actual native library version number ""
,W/art     ( 4398): Attempt to remove local handle scope entry from IRT, ignoring,
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,D/Messaging( 4269): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 4269): networkCode: 
D/MessageCustFlag( 4269): sku_id=99
,D/MmsConfig( 4269): SIE smsPri: null
D/MmsConfig( 4269): networkCode: 
,D/MmsConfig( 4269): packageName: com.htc.vvm.att does not exist
,D/Messaging( 4269): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 4269): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 4269): 
D/MmsAsyncWorkHandler( 4269): HM tk = 20001
D/ReportIndicatorCache( 4269): MSG_QUERY_REPORTS >>
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/MmsSmsV2Provider( 1412):  slotId = -1000
D/SettingsManager( 4269): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3ebb410f
D/MmsSmsV2Provider( 1412): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/DraftCache( 4269): [DraftCache/1] DraftCache.constructor
D/AccFlag ( 1412): sku_id=99
D/DraftCache( 4269): [DraftCache/1] refresh
,D/DraftCache( 4269): [DraftCache/556] rebuildCache
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1412):  slotId = -1000
D/MmsSmsV2Provider( 1412): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4269): mNeedToUpdateDate2: false,
,D/MmsConfig( 4269): networkCode: 
D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 107,
D/MmsSmsV2Provider( 1412):  slotId = -1000
D/MmsSmsV2Provider( 1412): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null,
I/Messaging( 4269): mccmnc> 
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103,
D/MmsSmsV2Provider( 1412):  slotId = -1000
D/MmsSmsV2Provider( 1412): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,W/GAV2    ( 4451): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 4451): getAccountsCursor
D/Messaging( 4269): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/Jerry   ( 1412): URI_DRAFT
,W/art     ( 4398): Attempt to remove local handle scope entry from IRT, ignoring
,D/Messaging( 4269): ViewCache CreatePreloadOnlyConversationList
,D/DraftCache( 4269): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 4269): [DraftCache/556] rebuildCache time: 7
D/MmsAsyncWorkHandler( 4269): 
D/MmsAsyncWorkHandler( 4269): HM tk = 20002
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
D/AccFlag ( 1412): sku_id=99
,D/MessageCustFlag( 4269): sense_version=6.0
D/Jerry   ( 4269): start to preload cursor >>>>>>>
D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/AccFlag ( 1412): sku_id=99
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 107
D/MmsSmsV2Provider( 1412):  slotId = -1000
,D/PhoneStorageUtil( 4269): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 4269): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4269): createReceiver
,D/Messaging( 4269): ViewCache CreatePreload
D/Messaging( 4269): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4269): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4269): def_index: 0
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/MsgPreferenceUtils( 4269): globalIndex = 1,
,D/TelephUtils( 1412): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
V/MmsProvider( 1412): Update uri=content://mms, match=0
,V/MmsProvider( 1412): selection=st=129 AND m_type!=134
D/MsgPreferenceUtils( 4269): phone state: true
D/MsgPreferenceUtils( 4269): sd state: false
D/MsgPreferenceUtils( 4269): vIndex = 0
D/Messaging( 4269): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4269): TransactionService is going to be woken up.
,V/TransactionService( 4269): 1-Creating TransactionService
,E/Gmail   ( 4451): Error finding the version of the Email provider.....,
E/Gmail   ( 4451): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4451): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4451): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4451): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4451): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Gmail   ( 4451): getAccountsCursor
,V/TransactionService( 4269): onStartCommand: 1
D/MmsSystemEventReceiver( 4269): unRegisterForConnectionStateChanges
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/EmailMigration( 4451): We do not support migrating this version of the Email provider.
V/TransactionService( 4269): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4269): Loading previous transactions.
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4451, uid=10115, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4451, uid=10115, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4451, uid=10115, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4451, uid=10115, userID:0
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/AccFlag ( 1412): device_type: 1
,D/TransactionService( 4269): Force set service start id to 1
,V/TransactionService( 4269): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4269): unRegisterForConnectionStateChanges
,D/TransactionService( 4269): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4269): Destroying TransactionService
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/htcbackup-core( 3858): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
I/htcbackup-core( 3858): SuperSaverModeReceiver: going to send resume event
,V/TransactionService( 4269): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4109): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/htcbackup-core( 3858): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 3858): BackupRestoreManager: resume
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4451, uid=10115, userID:0,
,I/ActivityManager(  964): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4551 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
W/ActivityManager(  964): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/AlarmManager(  964): sending alarm PendingIntent{15545c4e: PendingIntentRecord{3b5f416f com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44407, Int=259200000
V/AlarmManager(  964): sending alarm PendingIntent{188b305: PendingIntentRecord{89def5a com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448315199150, Int=0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4451, uid=10115, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4451, uid=10115, userID:0
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4109, uid=10025, userID:0,
,I/Gmail   ( 4451): Observing account changes for notifications
,I/DeviceManagement( 3837): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
,I/DeviceManagement( 3837): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup],
,I/DeviceManagement( 3837): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 107,
D/AccFlag ( 1412): sku_id=99
I/DeviceManagement( 3837): WorkflowService: Starting workflow service
,I/DeviceManagement( 3837): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c6f02] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3837): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3837): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,D/LocationInitializer( 4109): Restart initialization of location
W/ResourcesManager( 4551): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 103
W/ResourcesManager( 4551): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AccFlag ( 1412): sku_id=99
D/PMS     (  964): acquireWL(2f1a9a80): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
I/DeviceManagement( 3837): SessionStateController: Checking invariants...
,E/SQLiteLog( 4451): (283) recovered 12 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/GCoreUlr( 1694): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}],
I/iu.UploadsManager( 4109): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/GCoreUlr( 1694): DispatchingService.onCreate()
D/PMS     (  964): acquireWL(8cedeac): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4109 10025 null
I/MultiDex( 4551): VM with version 2.1.0 has multidex support
I/MultiDex( 4551): install
I/MultiDex( 4551): VM has multidex support, MultiDex support library is disabled.
,D/PMS     (  964): acquireWL(2cf56775): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4109 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  964): releaseWL(8cedeac): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null,
D/PMS     (  964): releaseWL(2cf56775): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  964): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4585 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,V/JNIHelp ( 4551): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
D/PMS     (  964): acquireWL(2ca13998): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1694 10025 WorkSource{10025 com.google.android.gms},
I/art     (  964): Explicit concurrent mark sweep GC freed 10013(516KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.342ms total 73.383ms
D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 97
D/AccFlag ( 1412): sku_id=99
,D/TelephUtils( 1412): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
,D/AccFlag ( 1412): sku_id=99
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4451, uid=10115, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4451, uid=10115, userID:0
E/ActivityThread( 4451): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@38e02001 that was originally bound here
E/ActivityThread( 4451): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@38e02001 that was originally bound here
E/ActivityThread( 4451): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4451): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4451): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4451): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4451): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4451): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4451): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4451): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4451): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4451): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4451): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4451): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4451): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  964): Unbind failed: could not find connection for android.os.BinderProxy@3c205f1
,W/ActivityThread( 4551): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/iu.UploadsManager( 4109): End new media; added: 0, uploading: 0, time: 101 ms
W/System  ( 4551): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2815e518: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4551): Installed default security provider GmsCore_OpenSSL
D/PMS     (  964): acquireWL(d225d6): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1694 10025 null
D/WearableService( 4551): callingUid 10025, callindPid: 4551
D/PMS     (  964): acquireWL(3a858057): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1694 10025 null
D/PMS     (  964): acquireWL(323c5744): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1694 10025 null
I/SensorManager( 1694): registerListenerImpl: listener = com.google.android.location.collectionlib.cm@20b8c2e, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 0, handler = Handler (com.google.android.location.collectionlib.ak) {3d34e3cf}
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): enable: get sensor name = Accelerometer Sensor
W/SensorService(  964): pid=1694, uid=10025
W/SensorService(  964): Active sensors: size = 3
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=3)
W/SensorService(  964): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  964): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  964): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@20b8c2e, eanble = 1, strlen(mName) = 52
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 4
W/SensorService(  964): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@33a4b944
W/SensorService(  964): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@38371fb6
W/SensorService(  964): Listener[2] = com.htc.smartdim.sensor_eye@3680f597
W/SensorService(  964): Listener[3] = com.google.android.location.collectionlib.cm@20b8c2e
W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/DeviceManagement( 3837): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm,
D/PMS     (  964): acquireWL(1f49a3b0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
I/DeviceManagement( 3837): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3837): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3837): SessionStateController: Checking invariants...
I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced
I/GCoreUlr( 1694): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4451, uid=10115, userID:0
I/Gmail   ( 4451): getAccountsCursor
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced
D/PMS     (  964): acquireWL(1a2238c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
,D/WifiService(  964): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@11861974}
,I/GoogleURLConnFactory( 1694): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1694): Ignoring unsupported parameter: http.conn-manager.max-per-route
,D/PMS     (  964): releaseWL(2f1a9a80): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,E/MDM     ( 1694): [163] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ImageRamCache( 4585): create image Cache, size: 31457280.,
I/ImageRamCache( 4585): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4585): create image Cache, size: 31457280.
,D/libc    ( 1694): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1694): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1694): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1694): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1694): [NET] android_getaddrinfo_proxy+
D/libc    ( 1694): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  459): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  459): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  459): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  459): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1694): [NET] android_getaddrinfo_proxy-, NODATA
,W/System.err( 1694): java.net.UnknownHostException: Unable to resolve host "www.google.com": No address associated with hostname
,I/FeedSettings( 4585): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false,
I/FeedSettings( 4585): GroupBudget 0.500000 0.380000
I/FeedSettings( 4585): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4585): changeLocale(): en_GB
,W/System.err( 1694): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
,W/System.err( 1694): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 1694): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 1694): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 1694): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 1694): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
,W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
W/System.err( 1694): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
W/System.err( 1694): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
W/System.err( 1694): 	,at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:933)
W/System.err( 1694): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:775)
W/System.err( 1694): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:676)
W/System.err( 1694): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:660)
W/System.err( 1694): 	at com.google.t.a.b.a.b.g(SourceFile:126)
W/System.err( 1694): 	at com.google.t.a.b.a.b.c(SourceFile:172)
W/System.err( 1694): 	at com.google.aa.a.d.run(SourceFile:435)
W/System.err( 1694): 	at com.google.aa.a.c.c(SourceFile:232)
W/System.err( 1694): 	at com.google.aa.a.c.run(SourceFile:206)
W/System.err( 1694): 	at com.google.t.a.c.b.run(SourceFile:96)
W/System.err( 1694): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 1694): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 1694): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 1694): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
,W/System.err( 1694): 	... 22 more
D/PMS     (  964): releaseWL(1f49a3b0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/DeviceManagement( 3837): ConfigManagerController: There is no cached content available: appID=com.htc.backup
,D/WifiService(  964): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@11861974}
I/DeviceManagement( 3837): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c6f02]
D/PMS     (  964): releaseWL(1a2238c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/DeviceManagement( 3837): WorkflowService: Stopping workflow service
,I/htcbackup-core( 3858): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
E/htcbackup-core( 3858): DMConfiguredIntentService: Interupted <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]> 
E/htcbackup-core( 3858): BackupRestoreManager: Can not get DM configured
,I/htcbackup-core( 3858): DMConfiguredIntentService: Config model load failed: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
W/htcbackup-core( 3858): DMConfiguredIntentService: reason null 
,I/Prism.AllAppsOptionsMa_( 4585): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4585): loadGridSize() with Alternative
,I/DeviceManagement( 3837): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 3837): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,I/DeviceManagement( 3837): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/Gmail   ( 4451): master sync=false, engine sync=true
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 9815(544KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 2.063ms total 28.741ms
,I/DeviceManagement( 3837): WorkflowService: Starting workflow service
,I/DeviceManagement( 3837): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c6f02] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3837): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3837): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3837): SessionStateController: Checking invariants...
,D/CustomHighlightReceiver( 4585): [custom highlight] onReceive
,D/CustomHighlightService( 4585): [custom highlight] onHandleIntent
,D/NewsDB  ( 4585): set custom highlight []
,I/ActivityManager(  964): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4617 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,E/Gmail.LabelManager( 4451): Unable to get label ^i for account thalitester@gmail.com
,E/Gmail   ( 4451): Couldn't find label: ^i
,I/DeviceManagement( 3837): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,I/DeviceManagement( 3837): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 3837): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3837): SessionStateController: Checking invariants...
,D/CustomHighlightService( 4585): [custom highlight] set tags 
,I/GCoreUlr( 1694): WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/MessagingShortcutReceiver( 4269): keep hiding shortcut bubble
,D/MessagingShortcut( 4269): updateMsgShortcut, msg count> -1
,D/MessagingShortcut( 4269): After query: 0
D/MessagingShortcut( 4269): mPresentUnreadCount: -1
,D/MessageUtils( 4269): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 4269): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 4269): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1199): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1199): [EventService] reorderNotification, total:0
D/DotMatrix( 1199): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1199): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/DeviceManagement( 3837): ConfigManagerController: There is no cached content available: appID=com.htc.backup,
I/art     ( 1694): Explicit concurrent mark sweep GC freed 14962(812KB) AllocSpace objects, 4(64KB) LOS objects, 43% free, 5MB/9MB, paused 1.275ms total 37.248ms
I/DeviceManagement( 3837): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@92c6f02]
,D/PMS     (  964): acquireWL(7c9bb28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  964): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4636 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
I/DeviceManagement( 3837): WorkflowService: Stopping workflow service
D/PMS     (  964): releaseWL(7c9bb28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/htcbackup-core( 3858): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
I/ActivityManager(  964): Killing 3891:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3891
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,I/Gmail   ( 4451): getAccountsCursor
I/htcbackup-core( 3858): DMConfiguredIntentService: Config model load failed: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
W/htcbackup-core( 3858): DMConfiguredIntentService: reason null 
,E/htcbackup-core( 3858): DMConfiguredIntentService: Interupted <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]> ,
E/htcbackup-core( 3858): BackupRestoreManager: Can not get DM configured
,I/ActivityManager(  964): Recipient 3891
,D/Process (  964): killProcessQuiet, pid=3891
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_3891/cgroup.procs: No such file or directory
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4451): master sync=false, engine sync=true
,E/Gmail.LabelManager( 4451): Unable to get label ^i for account thalitester@gmail.com
,E/Gmail   ( 4451): Couldn't find label: ^i
,W/ResourcesManager( 4636): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  964): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4653 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 3911:com.htc.htccupd/u0a13 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=3911
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 3911
,I/GCoreUlr( 1694): Unbound from all location providers
,D/Process (  964): killProcessQuiet, pid=3911
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10013/pid_3911/cgroup.procs: No such file or directory
,D/PMS     (  964): releaseWL(2ca13998): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,D/TodoTaskshortcut( 4636): update TASK shortcut>
,I/ActivityManager(  964): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4671 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 3986:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3986
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,I/ActivityManager(  964): Recipient 3986
,D/MdScBootUi( 4617): [a22.1.2.] boot 99,
,D/MdScBoot( 4617): [a22.1.] 30@-214617 -> 40,
,D/Process (  964): killProcessQuiet, pid=3986,
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  964): failed to open /acct/uid_10013/pid_3986/cgroup.procs: No such file or directory
,D/MdUtils ( 4617): [a22.1.2.] subId list: (0)r0 (s0)-1,
,I/GCoreUlr( 1694): DispatchingService.onDestroy()
,D/PMS     (  964): acquireWL(3a08679): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  964): releaseWL(3a08679): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
I/GCoreUlr( 1694): Unbound from all location providers
,I/ActivityManager(  964): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4692 uid=10079 gids={50079, 9997} abi=armeabi-v7a
,D/Process (  964): killProcessQuiet, pid=3951
I/ActivityManager(  964): Killing 3951:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/art     (  471): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 152us total 11.622ms,
,I/ActivityManager(  964): Recipient 3951,
I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 8.998ms
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 129us total 9.119ms,
,D/Process (  964): killProcessQuiet, pid=3951
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_3951/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  964): Killing 4003:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4003
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  964): Recipient 4003,
,D/Process (  964): killProcessQuiet, pid=4003
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_4003/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 4031:com.android.smith/1000 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4031,
D/SMSBackup( 4692): Got a database change event
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4031
,D/Process (  964): killProcessQuiet, pid=4031
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_4031/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  964): acquireWL(2ee84fbe): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4636 10072 null,
,I/ActivityManager(  964): Killing 3969:com.android.settings/1000 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=3969
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PMS     (  964): acquireWL(2c2a081f): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4636 10072 null
,I/ActivityManager(  964): Recipient 3969
,D/Process (  964): killProcessQuiet, pid=3969
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_3969/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  964): releaseWL(2ee84fbe): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4636): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4636): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4636): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4636): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4636): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4636): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  964): releaseWL(2c2a081f): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4636): stopSelfResult true
,D/PMS     (  964): acquireWL(1b9a1135): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1753): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1753): [NET] android_getaddrinfo_proxy+
D/libc    ( 1753): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  459): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  459): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  459): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  459): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1753): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(1b9a1135): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  964): acquireWL(35d5a9ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/MtpReceiver( 3487): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3487): [MTP][handleUsbStateAsync]1:1-
,D/MtpReceiver( 3487): [MTP][handleUsbState]+
,D/PMS     (  964): releaseWL(35d5a9ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  964): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4715 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a
,D/MtpReceiver( 3487): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3487): [MTP][handleUsbState]-
D/MtpReceiver( 3487): [MTP][handleMessage]-
,D/MtpService( 3487): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3487): TotalSize=1867208,MediaCacheLimit=6000
D/MtpService( 3487): [isMtpConnected] connected: true
,D/SyncApplication( 4715): Loading default preferences
,W/Resources( 4715): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  964): New client listening to asynchronous messages,
E/WifiTrafficPoller(  964): ADD_CLIENT: 7
,D/SyncApplication( 4715): Overriding preferences with custom values,
,E/MediaScannerService( 3487): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3487): [handleMessage] --- Should not be here, ignore request. ----
,D/SyncApplication( 4715): Updating preferences succeeded
,E/SyncApplication( 4715): Application created.,
,W/VolumeInfo( 4715): Unable to read mount points,
W/VolumeInfo( 4715): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4715): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4715): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4715): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4715): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4715): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4715): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4715): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4715): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4715): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
,W/VolumeInfo( 4715): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4715): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4715): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4715): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4715): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4715): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4715): 	... 13 more
V/VolumeInfo( 4715): Found 0 mount point(s)
V/VolumeInfo( 4715): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4715): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4715): getNewCalendarAuthority()...
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4715, uid=10005, userID:0
W/PackageManager(  964): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4715, uid=10005, userID:0
W/PackageManager(  964): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4715): enableAppOperation()+
D/VolumeInfo( 4715): Read the volume-id from the sd card: {54B52547-6D62-4DBB-8855-618616DC8272}
D/SyncApplication( 4715): enableAppOperation()-
W/VolumeInfo( 4715): Can not create volume ID for unmounted volume null
D/HTCUtilities( 4715): isNeorSinged() + 
D/HTCUtilities( 4715): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4715): isNeorSinged() return false
D/CDMountReceiver( 4715): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4715): USB connected to PC
D/FOTAReceiver( 4715): onReceive() enter 
D/FOTAReceiver( 4715): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  964): killProcessQuiet, pid=4088
I/ActivityManager(  964): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=4745 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  964): Killing 4088:com.google.android.gms:car/u0a25 (adj 15): empty #17
,I/ActivityManager(  964): Recipient 4088
,I/ActivityManager(  964): Waited long enough for: ServiceRecord{11b38ebe u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,E/MediaScannerServiceEx( 3487): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3487): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/Process (  964): killProcessQuiet, pid=4088,
W/libprocessgroup(  964): failed to open /acct/uid_10025/pid_4088/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/ActivityManager(  964): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,D/MediaScannerServiceEx( 3487): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3487): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3487): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 3487): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3487): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3487): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3487): [update][4]#0#,
,D/MediaProvider( 3487): [IsTableExist] Table:files_65537, result:false
D/MediaProvider( 3487): [update][1]#0#
,D/HtcFingerPrintQuickLaunchProvider( 4745): -onCreate(),
,I/art     (  964): Explicit concurrent mark sweep GC freed 10350(548KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 16MB/24MB, paused 865us total 71.108ms
,V/Settings:HtcSettingsApplication( 4745): [4745/4745] onCreate()
D/MediaProvider( 3487): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3487): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3487): [update][6]#1#
,D/MediaScannerServiceEx( 3487): [AliveExtStorageRows]-0, -1, 0, -1
,D/PMS     (  964): acquireWL(6b831ed): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3487 10017 null
,D/TetherSettings( 4745): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4745): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4745): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4745): Cust_ConnectToPC   : spcsc>false
D/        ( 4745): Cust_ConnectToPC   : IPT>true
D/        ( 4745): Cust_ConnectToPC   : Singel_USB>false
,D/MediaScanner( 3487): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
,W/Settings( 4745): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 4745): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4745): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4745): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4745): usb_cable_connect = 1
,D/SmartNS_Utility( 4745): usb_denied = 0
,I/SmartNS_NSReceiver( 4745): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 4745): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4745): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 4745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  964): acquireWL(156b22b3): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null,
,I/SmartNS_PSService( 4745): onReceive:com.htc.intent.action.USB_CONNECT2PC
,D/PMS     (  964): releaseWL(156b22b3): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,W/Settings( 4745): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4745):  defaultType:0
I/SmartNS_PSService( 4745): fail notificaiton:false
,D/SmartNS_Utility( 4745): usb_cable_connect = 1
,D/SmartNS_Utility( 4745): usb_denied = 0
I/SmartNS_PSService( 4745): usb notificaiton:true
,E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  964): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4764 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a,
I/ActionCombine( 4745): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4745): usb_cable_connect = 1,
,D/DotMatrix( 1199): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
D/SmartNS_Utility( 4745): usb_denied = 0
I/SmartNS_PSService( 4745): usb notificaiton:true
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1123): reapply : com.android.settings 1 36
,D/SmartNS_Utility( 4745): usb_cable_connect = 1,
,D/SmartNS_Utility( 4745): usb_denied = 0
D/DotMatrix( 1199): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
,I/SmartNS_PSService( 4745): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 4745): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  964): killProcessQuiet, pid=4052
I/ActivityManager(  964): Killing 4052:com.android.vending/u0a75 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/RemoteViews( 1123): reapply : com.android.settings 1 36
,W/ResourcesManager( 4764): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  964): Recipient 4052
,D/Process (  964): killProcessQuiet, pid=4052
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10075/pid_4052/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4764): Created com.android.providers.calendar.CalendarAlarmManager@16e8166e(com.htc.providers.calendar.HtcCalendarProvider@3ebb410f)
,D/CalendarProvider2( 4764): wait start:true
,I/HtcModeClient( 3072): handler message = 4011,
E/HtcModeClient( 3072): Check connection and retry 3 times.
,D/FlexNetS( 4764): updateSvcAllowedInSettings:false,
,D/CalendarProvider2( 4764): wait end:false
,I/ActivityManager(  964): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,W/ContextImpl( 4785): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 4785): MY_DEBUG = false,
,D/PMS     (  964): acquireWL(1b58f907): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4785 1000 null
,D/WeatherUtility( 1371): Weather sync is On,
,I/ActivityManager(  964): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4806 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
,D/WSP     ( 1371): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PowerUsageService( 4785): repeat time = 1448316100739
,W/BatSI   (  964): Couldn't get kernel wake lock stats
,D/MediaProvider( 3487): [update][18]#1#
,I/ActivityManager(  964): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4827 uid=10029 gids={50029, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,D/WeatherUtility( 4806): Weather sync is On,
,W/BatSI   (  964): Couldn't get kernel wake lock stats
,W/ResourcesManager( 4827): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PowerUsageList:PowerUsageHelper( 4785): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 4785): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 4785): gen(), null == sipper.uidObj, userId = 0,
I/ActivityManager(  964): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4849 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/PowerUsageList:BatterySipperExt( 4785): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 4785): gen(), null == sipper.uidObj, userId = 0
,I/EASAppSvc( 4849): [ NA ]onCreate,
,I/VersionUtil( 4849): [ NA ]setIsFOTAing: true
,I/VersionUtil( 4849): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 4849): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 4849): Set CursorWindow size to: 4194304 KB, Tid: 4870,
,D/ORMLib  ( 4636): put(),
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4875 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/MediaScanner( 3487):  prescan time: 265ms,
D/MediaScanner( 3487):     scan time: 497ms
,D/MediaScanner( 3487): postscan time: 1ms
D/MediaScanner( 3487):    total time: 763ms
D/MediaScanner( 3487): -----------------------------------------------------------------
D/MediaScanner( 3487): firstscan(media) time: 377ms,
D/MediaScanner( 3487): secondscan(non-media) time: 120ms
D/MediaScanner( 3487):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3487):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3487):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3487):  [Total]    File(Image+Video+Audio+Others) in database : 1533
,E/SQLiteLog( 4827): (283) recovered 55 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,D/PowerUsageService( 4785): calcPower(), no data,
,I/ActivityManager(  964): Killing 4311:com.google.android.youtube/u0a186 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=4311,
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4311,
,D/MediaProvider( 3487): [delete][177]
D/MediaProvider( 3487): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/WeatherUtility( 4806): Weather sync is On
,D/MediaProvider( 3487): [recoverParentNodes] - 0
,D/MediaProvider( 3487): [update][5]
D/MediaScannerServiceEx( 3487): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3487): [updateImage]+
,D/Process (  964): killProcessQuiet, pid=4311
W/libprocessgroup(  964): failed to open /acct/uid_10186/pid_4311/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/Settings( 4806): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Process (  964): killProcessQuiet, pid=4424
,I/ActivityManager(  964): Killing 4424:com.google.android.partnersetup/u0a28 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,E/WifiTrafficPoller(  964): ADD_CLIENT: 8
,D/WifiService(  964): New client listening to asynchronous messages
W/EAS_NetworkUtil( 4849): [ NA ]getNetworkInfo: NetworkInfo is null,
,I/ActivityManager(  964): Recipient 4424,
,D/PMS     (  964): acquireWL(302fdf82): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1371 10054 null,
,D/MediaScannerServiceEx( 3487): [updateImage]-0
,I/ActionCombine( 4806): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/MusicStore( 4875): Database version: 120,
,D/Process (  964): killProcessQuiet, pid=4424,
W/libprocessgroup(  964): failed to open /acct/uid_10028/pid_4424/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  964): releaseWL(6b831ed): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
,D/MediaScannerServiceEx( 3487): [1] scan finished
D/MediaProviderUtils( 3487): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3487): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3487): calcVolumeId: /storage/usb,
,D/MediaScannerServiceEx( 3487): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3487): Process mounted intent for unmounted storage: /storage/ext_sd
,I/EASAppSvc( 4849): [ NA ]onDestroy
,D/MediaScannerServiceEx( 3487): [disAliveExtStorageRows]+131073
,I/EASAppSvc( 4849): [ NA ]> uninitEASService
,I/EASAppSvc( 4849): [ NA ]onCreate
I/EASRequestController( 4849): [ NA ]release
D/EASPublicBinder( 4849): [ NA ]release,
D/TaskBinder( 4849): [ NA ]release
D/TaskBinder( 4849): [ NA ]release
I/EASAppSvc( 4849): [ NA ]< uninitEASService
,I/VersionUtil( 4849): [ NA ]setIsFOTAing: true
I/RemoteViews( 1476): reapply : com.htc.widget.weatherclock 4 21
I/VersionUtil( 4849): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 4849): [ NA ]setIsFOTAing: false
W/EAS_NetworkUtil( 4849): [ NA ]getNetworkInfo: NetworkInfo is null
D/MediaProvider( 3487): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3487): [update][6]#1#
D/ORMLib  ( 4636): put()
D/MediaProvider( 3487): [update][4]#0#
,D/MediaProvider( 3487): [update][44]#0#,
,D/MediaScannerServiceEx( 3487): [disAliveExtStorageRows]--1, 0, 0,
,I/EASAppSvc( 4849): [ NA ]onDestroy
I/EASAppSvc( 4849): [ NA ]> uninitEASService
,D/MediaProviderUtils( 3487): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3487): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3487): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3487): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3487): Process mounted intent for unmounted storage: /storage/usb
,I/ActivityManager(  964): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4925 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a,
I/EASRequestController( 4849): [ NA ]release,
D/MediaScannerServiceEx( 3487): [disAliveExtStorageRows]+196609
,D/EASPublicBinder( 4849): [ NA ]release,
D/TaskBinder( 4849): [ NA ]release
D/TaskBinder( 4849): [ NA ]release
I/EASAppSvc( 4849): [ NA ]< uninitEASService
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 4875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,D/MediaProvider( 3487): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
D/MediaProvider( 3487): [update][5]#1#,
,D/MediaProvider( 3487): [update][6]#0#,
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 4875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,I/ActivityManager(  964): Killing 4398:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=4398
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/CalendarProvider2( 4764): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ResourcesManager( 4875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ContentResolver( 4764): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/ResourcesManager( 4875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ORMLib  ( 4636): put()
,I/ActivityManager(  964): Recipient 4398
,D/WifiService(  964): Client connection lost with reason: 4
,D/MediaProvider( 3487): [update][80]#0#
,D/MediaScannerServiceEx( 3487): [disAliveExtStorageRows]--1, 0, 0
,D/Process (  964): killProcessQuiet, pid=4398,
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_4398/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  964): killProcessQuiet, pid=4451,
I/ActivityManager(  964): Killing 4451:com.google.android.gm/u0a115 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4451,
,V/JNIHelp ( 4875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 4875): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8131590: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4875): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 4875): GMSCore installation verified
,V/AlarmManager(  964): sending alarm PendingIntent{24d2ea7e: PendingIntentRecord{cb46bdf com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448315201766, Int=0,
,D/Process (  964): killProcessQuiet, pid=4451
W/libprocessgroup(  964): failed to open /acct/uid_10115/pid_4451/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  964): Killing 3858:com.htc.backup/u0a118 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=3858
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 3858
,D/Process (  964): killProcessQuiet, pid=3858,
W/libprocessgroup(  964): failed to open /acct/uid_10118/pid_3858/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/ConfigStore( 4875): Config Database version: 1
,D/Process (  964): killProcessQuiet, pid=4585
I/ActivityManager(  964): Killing 4585:com.htc.sense.news/u0a77 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4585
,D/Process (  964): killProcessQuiet, pid=4585
,W/libprocessgroup(  964): failed to open /acct/uid_10077/pid_4585/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4875, uid=10167, userID:0
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,D/MediaRouterService(  964): Client com.google.android.music (pid 4875): Registered
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,I/MediaRouter( 4875): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/TelephonyReceiver( 1412): bind: true
,I/ActivityManager(  964): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4960 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GenericMessagesProvider( 4269): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 4269): (14) cannot open file at line 30046 of [9491ba7d73]
E/SQLiteLog( 4269): (14) os_unix.c:30046: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4269): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 4269): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 4269): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.,
E/SQLiteDatabase( 4269): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 4269): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4269): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4269): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4269): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 4269): 	at android.os.Binder.execTransact(Binder.java:454)
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4875, uid=10167, userID:0
,W/System.err( 4269): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,W/System.err( 4269): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
W/System.err( 4269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
,W/System.err( 4269): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 4269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 4269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,W/System.err( 4269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,I/GHttpClientFactory( 4875): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/System.err( 4269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 4269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 4269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 4269): ,	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4269): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 4269): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
,W/System.err( 4269): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
I/GoogleURLConnFactory( 4875): Using platform SSLCertificateSocketFactory
,W/System.err( 4269): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/TelephonyReceiver( 1412): switchBindHtcMsgCursor: null,
,I/DFPI.ApkInstallService( 4960): onHandleIntent
,I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  964): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4990 uid=10051 gids={50051, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/art     (  471): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 142us total 9.740ms
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 9.625ms,
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 9.274ms
,I/art     (  964): Explicit concurrent mark sweep GC freed 18560(893KB) AllocSpace objects, 3(719KB) LOS objects, 33% free, 16MB/24MB, paused 826us total 69.130ms
,I/ActivityManager(  964): Killing 4617:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4617
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4617
,D/Process (  964): killProcessQuiet, pid=4617
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10048/pid_4617/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5017 uid=10082 gids={50082, 9997, 5001, 1028, 1015} abi=armeabi-v7a,
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
W/ContextImpl( 4990): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm),
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
D/PMS     (  964): acquireWL(5c77bc1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4764 10011 null
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
,I/ActivityManager(  964): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
I/ActivityManager(  964): Resuming delayed broadcast
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
E/SQLiteLog( 4764): (284) automatic index on view_events(_id)
I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 4960): onHandleIntent
I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  964): Resuming delayed broadcast
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  964): releaseWL(5c77bc1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  964): releaseWL(1b58f907): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  964): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5042 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
,D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma),
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 4960): onHandleIntent,
I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4960): check CID = HTC__032
,I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  964): Resuming delayed broadcast
,I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  964): Killing 3837:com.htc.cs.dm/u0a105 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=3837
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/ActivityManager(  964): Recipient 3837
,I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
W/libprocessgroup(  964): failed to open /acct/uid_10105/pid_3837/cgroup.procs: No such file or directory
D/Process (  964): killProcessQuiet, pid=3837
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActivityManager(  964): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  964): Resuming delayed broadcast
,D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 4960): onHandleIntent
,I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  964): Resuming delayed broadcast
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279,
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/TelephonyReceiver( 1412): bind: false
D/TelephonyReceiver( 1412): switchBindHtcMsgCursor: null
D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 4960): onHandleIntent
I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  964): Resuming delayed broadcast
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
I/DFPI.ApkInstallService( 4960): onHandleIntent
I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/ActivityManager(  964): Resuming delayed broadcast
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
D/DFPI.PIReciver( 4960): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  964): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/DFPI.ApkInstallService( 4960): onHandleIntent
I/DFPI.ApkInstallService( 4960): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 4960): check CID = HTC__032
I/DFPI.ApkInstallService( 4960): There is no Demo.apk in sd card or phone storage
I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  964): Resuming delayed broadcast
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5017): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  964): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5071 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SensorManager( 1694): unregisterListenerImpl++: listener = com.google.android.location.collectionlib.cm@20b8c2e
W/SensorService(  964): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  964): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  964): pid=1694, uid=10025
W/SensorService(  964): Active sensors: size = 3
W/SensorService(  964): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  964): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  964): CM36282 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  964): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@20b8c2e, eanble = 0, strlen(mName) = 52
W/SensorService(  964): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  964): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@33a4b944
W/SensorService(  964): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@38371fb6
D/PMS     (  964): acquireWL(1dcd774a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
W/SensorService(  964): Listener[2] = com.htc.smartdim.sensor_eye@3680f597
,W/SensorService(  964): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  964): releaseWL(1dcd774a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  964): releaseWL(323c5744): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,D/PMS     (  964): acquireWL(181086bb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
,D/PMS     (  964): releaseWL(3a858057): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,D/PMS     (  964): releaseWL(181086bb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  964): acquireWL(37b887d8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1694 10025 null
,D/PMS     (  964): releaseWL(d225d6): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,D/PMS     (  964): releaseWL(37b887d8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
,D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/ActivityManager(  964): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/ActivityManager(  964): Resuming delayed broadcast
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/art     (  964): Explicit concurrent mark sweep GC freed 8863(399KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 793us total 60.419ms
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/ActivityManager(  964): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActionCombine( 5042): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/ActivityManager(  964): Resuming delayed broadcast
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/RemoteViews( 1123): setHTCTheme(com.htc.updater,true,33751145)
,D/Prism.PackageStateRece_( 1476): action: android.intent.action.PACKAGE_ADDED
D/DotMatrix( 1199): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/[PluginManager]RegisterService( 1371): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/[PluginManager]RegisterService( 1371): handle notify Blinkfeed plugin client changed
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
,I/RemoteViews( 1123): apply : com.htc.updater 0 7 2 36,
,I/ActivityManager(  964): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5093 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  964): Killing 4653:com.htc.mobiledata/u0a48 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=4653
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/ActivityManager(  964): Recipient 4653
,D/Process (  964): killProcessQuiet, pid=4653
W/libprocessgroup(  964): failed to open /acct/uid_10048/pid_4653/cgroup.procs: No such file or directory
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  964): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  964): MONITOR_LOG
,W/Settings:Agent(  964): name: bluetooth_on
W/Settings:Agent(  964): value: 0
W/Settings:Agent(  964): >> traceCallingStack()
W/Settings:Agent(  964): Process.myPid(): 964
W/Settings:Agent(  964): Process.myTid(): 1277
W/Settings:Agent(  964): Process.myUid(): 1000
W/Settings:Agent(  964): 
W/Settings:Agent(  964): 
W/System.err(  964): java.lang.Throwable: stack dump
,W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  964): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  964): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  964): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  964): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  964): 
W/Settings:Agent(  964): << traceCallingStack(): 1(ms)
D/BluetoothManagerService(  964): Message: MESSAGE_DISABLE
D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 8
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
D/WifiManager( 4237): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281,
D/WifiService(  964): setWifiEnabled: false pid=4237, uid=10380
W/Settings:Agent(  964): MONITOR_LOG
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  964): name: wifi_on
I/WifiService(  964): isSprintWifiRestricted(): false
W/Settings:Agent(  964): value: 0
I/WifiService(  964): isMdmWifiRestricted(): false
,W/Settings:Agent(  964): >> traceCallingStack()
W/Settings:Agent(  964): Process.myPid(): 964
W/Settings:Agent(  964): Process.myTid(): 980
W/Settings:Agent(  964): Process.myUid(): 1000
W/Settings:Agent(  964): 
W/Settings:Agent(  964): 
W/System.err(  964): java.lang.Throwable: stack dump
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  964): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  964): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  964): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  964): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
,W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  964): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  964): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  964): 
,W/Settings:Agent(  964): << traceCallingStack(): 1(ms)
I/jxcore-log( 4237): ****TEST TOOK:  5029  ms ****
I/jxcore-log( 4237): 
I/jxcore-log( 4237): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4237): 
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/MediaStoreImporter( 4875): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  964): Killing 4671:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4671
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4671,
,D/Process (  964): killProcessQuiet, pid=4671,
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10037/pid_4671/cgroup.procs: No such file or directory
,I/DeviceManagement( 5093): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=5093 dbg=false s=true
,I/DeviceManagement( 5093): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/ActivityManager(  964): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=5114 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/Process (  964): killProcessQuiet, pid=4692
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  964): Killing 4692:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  964): Recipient 4692,
,D/Process (  964): killProcessQuiet, pid=4692
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_4692/cgroup.procs: No such file or directory
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
,I/htcbackup-core( 5114): ModelRegistry: Loading model meta data from resources...
,I/art     ( 3487): Explicit concurrent mark sweep GC freed 33299(2MB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1488KB/5MB, paused 375us total 18.883ms
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/ActivityManager(  964): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5137 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,D/Process (  964): killProcessQuiet, pid=4207
I/ActivityManager(  964): Killing 4207:com.google.android.talk/u0a120 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/DeviceManagement( 5093): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 5093): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,I/DeviceManagement( 5093): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]],
,I/ActivityManager(  964): Recipient 4207,
,E/cutils-trace( 5119): Error opening trace file: No such file or directory (2),
,D/CustomizationManager( 5119): ====startRecUseTime====,
D/htc.customization.log.level( 5119):  is 
W/CustomizationLogLevel( 5119): Level value is invalid, use default level 2
,D/Process (  964): killProcessQuiet, pid=4207,
W/libprocessgroup(  964): failed to open /acct/uid_10120/pid_4207/cgroup.procs: No such file or directory
I/DeviceManagement( 5093): WorkflowService: Starting workflow service
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/DeviceManagement( 5093): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1a044f88] args=[Bundle[mParcelledData.dataSize=132]],
I/DeviceManagement( 5093): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287,
,I/DeviceManagement( 5093): ModelRegistry: Loading model meta data from resources...
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5017): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5017): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/HtcCupdReceiver(Provider)( 5137):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
,W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/305
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/251
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/279
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/285
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/287
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
W/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=1
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/DeviceManagement( 5093): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 5093): SessionStateController: Checking invariants...
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5170 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=2
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/305 type=3
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/305
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=4
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5017): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/251 type=5
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/251
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/279 type=6
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/279
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/285 type=7
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/285
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/287 type=8
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/287
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/CustomizationManager( 5119):  Read ACC file spent 0.059 (s)
,D/CIDMapFileReader( 5119): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 5119): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__203
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__405
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__304
,D/CIDMapFileReader( 5119): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 5119): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 5119): Parsing tag item name = HTC__K18
,D/CIDMapFileReader( 5119): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 5119): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5119): Parsing tag category name = system
,I/CustomizationCIDLoader( 5119): Parsing tag category name = application
,I/CustomizationCIDLoader( 5119): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 5119): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5119): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 5119): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5119): Parsing tag category name = ACC
,D/CustomizationManager( 5119):  Read CID file spent 0.117 (s)
,D/CustomizationManager( 5119):  All configurations done spent 0.117 (s)
,I/ActivityManager(  964): Waited long enough for: ServiceRecord{12810c71 u0 com.htc.HTCSpeaker/.NGFService}
,E/ActTriggerJNI( 5119): open library fail.
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5017): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/281 type=9
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/281,
E/Settings:HtcWrapHeaderInfo( 4745): no such activity!,
,I/SoundPicker( 5017): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5017): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/PackageManager(  964): deletePackageAsUser: pkg=com.example.hello, pid=5119, uid=2000 userid=0
,D/Process (  964): killProcessQuiet, pid=4715,
I/ActivityManager(  964): Killing 4715:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4745): The wrap header doesn't exist in header list.,
,I/ActivityManager(  964): Recipient 4715,
D/WifiService(  964): Client connection lost with reason: 4
,E/Settings:HtcWrapHeaderInfo( 4745): updateDevelopment, bPrefShow = true,
,D/Process (  964): killProcessQuiet, pid=4715
,W/libprocessgroup(  964): failed to open /acct/uid_10005/pid_4715/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/Process (  964): killProcessQuiet, pid=4237
I/ActivityManager(  964): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
I/ActivityManager(  964): Killing 4237:com.example.hello/u0a380 (adj 0): stop com.example.hello
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,W/PackageSettings(  964): Skipping PackageSetting{6f9153b com.test.thalitest/10373} due to missing metadata
,I/ActivityManager(  964): Recipient 4237,
I/WindowState(  964): WIN DEATH: Window{245561a6 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5170, uid=10075, userID:0
,E/Settings:HtcUmcWidgetEnabler( 4745): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]support         :false
,I/DeviceManagement( 5093): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]support         :false
,W/ActivityManager(  964): Force removing ActivityRecord{c21f91f u0 com.example.hello/.MainActivity t27}: app died, no saved state
,E/MP-Decision( 2271): Update arg "0 380 380 380".
,E/MP-Decision( 2271): Update arg "0 400 400 400".
,W/ActivityManager(  964): Spurious death for ProcessRecord{3d7f451c 4237:com.example.hello/u0a380}, curProc for 4237: null
,I/ActivityManager(  964): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/DeviceManagement( 5093): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 5093): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 5093): SessionStateController: Checking invariants...
,I/FeedHostManager( 1476): [onResume]
I/FeedProviderManager( 1476): onResume
,D/DotMatrix( 1199): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1199): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1199): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/SocialFeedProvider( 1476): +onResume
I/SocialFeedProvider( 1476): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1476): -onResume
I/ConnectivityHelper( 1476): [getCurrentConnectionType] no network connection
,D/AccTypeManager( 1550): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1412): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 5170): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/PMS     (  964): acquireWL(182c2d4c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1694 10025 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  964): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4745): isSupportVoWifi: null,
E/ActivityThread( 4745): Failed to find provider info for com.htc.vowifi
D/PMS     (  964): releaseWL(182c2d4c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
D/StatusBarManagerService(  964): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,I/Prism.ItemManager( 1476): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1476): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PhoneApp( 1412): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4745): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4745): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 4745): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4745): [supportHomeButton]support         :false
W/PackageManager(  964): Unable to load service info ResolveInfo{31bb817c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  964): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  964): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  964): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  964): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  964): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
D/AccTypeManager( 1550): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  964): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4745): isSupportVoWifi: null
E/ActivityThread( 4745): Failed to find provider info for com.htc.vowifi
,I/DeviceManagement( 5093): ConfigManagerController: There is no cached content available: appID=com.htc.backup
I/DeviceManagement( 5093): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1a044f88]
,I/DeviceManagement( 5093): WorkflowService: Stopping workflow service
,E/ExternalAccountType( 1550): Unsupported attribute readOnly
,I/ActivityManager(  964): Killing 4785:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4785
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4785
,D/JobSchedulerService(  964): Receieved: android.intent.action.PACKAGE_REMOVED
,I/InputMethodManagerService(  964): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4237 uid 10380,
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  964): Enable input method client, pid=1476
,W/ResourcesManager(  964): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,D/Process (  964): killProcessQuiet, pid=4785,
D/TaskPersister(  964): removeObsoleteFile: deleting file=27_task.xml
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_4785/cgroup.procs: No such file or directory
,I/htcbackup-core( 5114): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>,
,I/art     (  964): Explicit concurrent mark sweep GC freed 20891(1398KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 16MB/25MB, paused 1.450ms total 198.718ms,
,D/Finsky  ( 5170): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5212 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 5170): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5170): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5170, uid=10075, userID:0
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Process (  964): killProcessQuiet, pid=4806
,I/ActivityManager(  964): Killing 4806:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/MultiDex( 5212): VM with version 2.1.0 has multidex support
I/MultiDex( 5212): install
I/MultiDex( 5212): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  964): Recipient 4806
,D/Process (  964): killProcessQuiet, pid=4806
,D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  964): failed to open /acct/uid_10042/pid_4806/cgroup.procs: No such file or directory
,D/Finsky  ( 5170): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5170): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5170): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 4109): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraModuleLdr( 4109): Loading module APK com.google.android.play.games
,D/PMS     (  964): acquireWL(1aeaf01e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4109 10025 null
,D/Finsky  ( 5170): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 5212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5212): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2815e518: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5212): Installed default security provider GmsCore_OpenSSL
,I/ConfigFetchService( 4109): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,E/WorkSourceUtil( 4109): Could not find package: com.example.hello
,D/PMS     (  964): acquireWL(31a5593): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4109 10025 null
,I/ConfigFetchService( 4109): launchTask
,D/PMS     (  964): releaseWL(1aeaf01e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/Process (  964): killProcessQuiet, pid=4636,
I/ActivityManager(  964): Killing 4636:com.htc.task/u0a72 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,V/ConfigFetchTask( 4109): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U-uH4BQBZo79oi1COJNc1h2UanV5TZEo1-Xs-L3Is_AoBcE4ONS6qUpMaA7cU8HNSeMlPSFH1-J8hwqPZtCSDGHC_Ni9njWGqH9T6XJPdZJ4Bpbuxqar60poPA0cv7BpZpz9DqtcjT9ve4ZstRzFMigMEYCYWh1ItCFYPIKVtRtBMK-hBr0R5uvdHbLoyCvXNdmQSR
,E/ConfigFetchTask( 4109): failed to build request; aborting config fetch
,I/ConfigFetchTask( 4109):   purging config for com.test.thalitest
,I/ActivityManager(  964): Recipient 4636,
,D/PMS     (  964): acquireWL(1afb69d0): PARTIAL_WAKE_LOCK  Icing 0x1 4109 10025 WorkSource{10025 com.google.android.gms}
D/Process (  964): killProcessQuiet, pid=4636
W/libprocessgroup(  964): failed to open /acct/uid_10072/pid_4636/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/PeopleContactsSync( 4109): CP2 sync disabled
,D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4109): Module APK com.google.android.play.games already loaded
,V/Finsky  ( 5170): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4109, uid=10025, userID:0
,D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 4109): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4109): No vision deps
I/ConfigFetchService( 4109): fetch service done; releasing wakelock
D/PMS     (  964): releaseWL(31a5593): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 null
I/ConfigFetchService( 4109): stopping self
,I/ActivityManager(  964): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5253 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/OpenGLRenderer( 1476): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/Icing   ( 4109): Storage manager: low false usage 1.66MB avail 7.34GB capacity 9.08GB
,W/Icing   ( 4109): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4109): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4109): Received bad json for section weights override -- ignoring.
W/Icing   ( 4109): Received bad json for corpus context scoring override -- ignoring.
,E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
,E/Icing   ( 4109): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4109): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
,E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4109): Trie initialize fail
,E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
,E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
,E/Icing   ( 4109): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4109): Init docstore failed
E/Icing   ( 4109): Index init failed, resetting corpora
,E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
,W/BaseAppContext( 4109): Using Auth Proxy for data requests.
E/Icing   ( 4109): Clearing index failed
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
W/BaseAppContext( 4109): Using Auth Proxy for data requests.
,E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
,E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
,E/Icing   ( 4109): Clearing docstore failed
E/Icing   ( 4109): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
E/Icing   ( 4109): Deleting compact status failed
,E/Icing   ( 4109): Couldn't handle android.intent.action.PACKAGE_ADDED intent due to initialization failure.
D/PMS     (  964): releaseWL(1afb69d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  964): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5274 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 4109): Using Auth Proxy for data requests.
,W/BaseAppContext( 4109): Using Auth Proxy for data requests.
,W/BaseAppContext( 4109): Using Auth Proxy for data requests.
,W/BaseAppContext( 4109): Using Auth Proxy for data requests.
,D/Process (  964): killProcessQuiet, pid=4849,
I/ActivityManager(  964): Killing 4849:com.htc.android.mail:sync/u0a65 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,D/WifiService(  964): Client connection lost with reason: 4,
I/ActivityManager(  964): Recipient 4849
,E/Search.SharedPreferencesProto( 5253): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/Process (  964): killProcessQuiet, pid=4849
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  964): failed to open /acct/uid_10065/pid_4849/cgroup.procs: No such file or directory
,D/LocationManagerService(  964): getProviders()=[passive, network]
,I/ActivityManager(  964): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5301 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SharedPreferencesImpl( 5253): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/AndroidRuntime( 5253): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5253): Process: com.google.android.googlequicksearchbox:search, PID: 5253
E/AndroidRuntime( 5253): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 5253): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 5253): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 5253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5253): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5253): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5253): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 5253): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 5253): 	... 7 more
E/AndroidRuntime( 5253): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5253): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5253): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5253): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5253): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5253): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5253): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 5253): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 5253): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 5253): 	... 9 more
E/AndroidRuntime( 5253): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5253): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 5253): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 5253): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 5253): 	... 11 more
E/ActivityManager(  964): App crashed! Process: com.google.android.googlequicksearchbox:search
,I/art     (  471): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 171us total 13.501ms,
,I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 164us total 10.876ms,
,D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,E/DropBoxManagerService(  964): Can't write: system_app_crash,
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 167us total 11.200ms
,I/ActivityManager(  964): Killing 4925:com.htc.task.gtask/u0a69 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=4925
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  964): Recipient 4925,
,D/Process (  964): killProcessQuiet, pid=4925
W/libprocessgroup(  964): failed to open /acct/uid_10069/pid_4925/cgroup.procs: No such file or directory
D/Process (  964): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/ChimeraCfgMgr( 4109): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4109): Module APK com.google.android.play.games already loaded
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 4947(208KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 668us total 29.395ms
,V/AlarmManager(  964): sending alarm PendingIntent{145d43eb: PendingIntentRecord{929b548 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448315204842, Int=0
,D/Finsky  ( 5170): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/GFEEDBACK_SendErrorReportOperation( 4109): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4109): Error saving report: java.io.IOException: failed to create reports directory
,E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4109): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
,E/SQLiteDatabase( 4109): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteDatabase( 4109): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteDatabase( 4109): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 4109): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteDatabase( 4109): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteDatabase( 4109): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
E/SQLiteDatabase( 4109): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 4109): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 4109): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 4109): 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
E/SQLiteDatabase( 4109): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
E/SQLiteDatabase( 4109): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteDatabase( 4109): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/SQLiteDatabase( 4109): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteDatabase( 4109): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4109): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4109): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 4109): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteOpenHelper( 4109): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteOpenHelper( 4109): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 4109): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteOpenHelper( 4109): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteOpenHelper( 4109): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
,E/SQLiteOpenHelper( 4109): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 4109): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 4109): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/SQLiteOpenHelper( 4109): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteOpenHelper( 4109): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4109): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4109): 	at java.lang.Thread.run(Thread.java:818)
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5170): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SQLiteOpenHelper( 4109): Opened games_3a3529a.db in read-only mode
E/AndroidRuntime( 4109): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 4109): Process: com.google.android.gms, PID: 4109
E/AndroidRuntime( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 4109): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4109): 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
E/AndroidRuntime( 4109): 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
E/AndroidRuntime( 4109): 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
E/AndroidRuntime( 4109): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1577)
E/AndroidRuntime( 4109): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1510)
E/AndroidRuntime( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4109): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4109): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  964): App crashed! Process: com.google.android.gms
,W/ResourcesManager(  964): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  964): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GAv4    ( 5274): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5274):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5274):   adb logcat -s GAv4
,E/DropBoxManagerService(  964): Can't write: system_app_crash,
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 5274): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
E/PlayEventLogger( 5170): Could not write string (client_ve: ""
E/PlayEventLogger( 5170): exp <
E/PlayEventLogger( 5170):   play_experiment: 739
E/PlayEventLogger( 5170):   play_experiment: 741
E/PlayEventLogger( 5170):   play_experiment: 12602035
E/PlayEventLogger( 5170):   play_experiment: 12602049
E/PlayEventLogger( 5170):   play_experiment: 12602373
E/PlayEventLogger( 5170):   play_experiment: 12602392
E/PlayEventLogger( 5170):   play_experiment: 12602761
E/PlayEventLogger( 5170):   play_experiment: 12602795
E/PlayEventLogger( 5170):   play_experiment: 12603067
E/PlayEventLogger( 5170):   unsupported_play_experiment: 18
E/PlayEventLogger( 5170):   unsupported_play_experiment: 19
,E/PlayEventLogger( 5170):   unsupported_play_experiment: 20
E/PlayEventLogger( 5170):   unsupported_play_experiment: 21
E/PlayEventLogger( 5170):   unsupported_play_experiment: 24
E/PlayEventLogger( 5170):   unsupported_play_experiment: 35
E/PlayEventLogger( 5170):   unsupported_play_experiment: 220
E/PlayEventLogger( 5170):   unsupported_play_experiment: 259
E/PlayEventLogger( 5170):   unsupported_play_experiment: 296
E/PlayEventLogger( 5170):   unsupported_play_experiment: 473
E/PlayEventLogger( 5170):   unsupported_play_experiment: 578
E/PlayEventLogger( 5170):   unsupported_play_experiment: 580,
E/PlayEventLogger( 5170):   unsupported_play_experiment: 744
E/PlayEventLogger( 5170):   unsupported_play_experiment: 748
E/PlayEventLogger( 5170):   unsupported_play_experiment: 793
E/PlayEventLogger( 5170):   unsupported_play_experiment: 855
E/PlayEventLogger( 5170):   unsupported_play_experiment: 901
E/PlayEventLogger( 5170):   unsupported_play_experiment: 910
E/PlayEventLogger( 5170):   unsupported_play_experiment: 955,
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602000
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602001
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602002
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602003
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602005
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602007
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602008
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602010,
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602011
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602020
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602021
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602028
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602029
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602036
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602037
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602038
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602040
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602042
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602044
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602048
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602051
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602052
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602053
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602055
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602056
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602057
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602062,
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602063
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602064
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602068
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602073
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602076
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602091
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602092
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602093
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602098
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602104
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602106
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602117
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602120
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602123
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602125
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602128
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602350
,E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602351
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602370
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602377
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602418
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602430
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602604
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602716
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602787
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602797
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602825
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602826
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602827
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602837
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12602868
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603075,
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603076
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603077
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603078
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603079
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603152
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603212
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603217
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603283
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603355
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603471
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603527
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603539
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603595
E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603596
,E/PlayEventLogger( 5170):   unsupported_play_experiment: 12603597
E/PlayEventLogger( 5170): >
E/PlayEventLogger( 5170): source_extension: "\"/\010w\022\023com.android.vending*\020AuthFailureErrorZ\004\020\000\030\001"
E/PlayEventLogger( 5170): source_extension_js: ""
E/PlayEventLogger( 5170): source_extension_json: ""
E/PlayEventLogger( 5170): tag
W/GAv4    ( 5274): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5274): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteDatabase( 5274): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5274): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5274): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5274): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5274): 	at gir$c.run(Unknown Source)
W/AnalyticsTrackerProxyImpl( 5274): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,E/GAv4    ( 5274): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/Finsky  ( 5170): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
E/SQLiteDatabase( 5274): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5274): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267),
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5274): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5274): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5274): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5274): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5274): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5274): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5170): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5170): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5170): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5170): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5170): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5170): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 5170): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:234)
E/SQLiteDatabase( 5170): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:95),
E/SQLiteDatabase( 5170): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5170): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5170): Process: com.android.vending, PID: 5170
E/AndroidRuntime( 5170): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5170): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 5170): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5170): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5170): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 5170): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:234)
E/AndroidRuntime( 5170): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5170): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  964): App crashed! Process: com.android.vending,
E/DropBoxManagerService(  964): Can't write: system_app_crash
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269),
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
,E/GAv4    ( 5274): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,D/AutoSetting( 1371): service - mHandler: update timezone
,E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5274): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5274): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5274): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5274): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5274): 	at aen.run(PG:536)
,I/GAv4-SVC( 4109): Google Analytics 7.8.99 is starting up.
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5274): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,E/SQLiteDatabase( 5274): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5274): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5274): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5274): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5274): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5274): 	at aej.c(PG:139)
E/SQLiteDatabase( 5274): 	at aej.b(PG:398)
E/SQLiteDatabase( 5274): 	at agf.f(PG:417)
E/SQLiteDatabase( 5274): 	at oe.run(PG:1112)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5274): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5274): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 5274): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AbstractDatabaseInstance( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 5274): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 5274): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 5274): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 5274): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 5274): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 5274): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 5274): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 5274): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 5274): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 5274): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 5274): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 5274): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 5274): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5274): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5274): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5274): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5274): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5274): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/CAKEMIX_CRASHED( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 5274): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 5274): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 5274): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 5274): 	at aen.run(PG:536)
,W/ResourcesManager( 5274): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5274): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/MP-Decision( 2271): Update arg 2,
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5344 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
I/AnimationUtil(  964): isHTCRecent(Drive/Recent screens.)/0,
D/PMS     (  964): acquireWL(3d19add): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 964 1000 null
E/MP-Decision( 2271): Update arg "0 190 240 240".
E/MP-Decision( 2271): Update arg "0 75 400 400".
D/Process ( 5274): killProcess, pid=5274
,D/Process ( 5274): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
I/FeedHostManager( 1476): [onPause]
I/FeedProviderManager( 1476): onPause
I/FeedHostManager( 1476): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@114bb16
I/SocialFeedProvider( 1476): +onPause
I/SocialFeedProvider( 1476): -onPause
,E/lowmemorykiller(  359): Error writing /proc/5274/oom_score_adj; errno=22,
D/HtcSystemUPManager(  964): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,E/JavaBinder(  964): !!! FAILED BINDER TRANSACTION !!!,
E/ActivityManager(  964): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,W/ActivityManager(  964): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  964): android.os.TransactionTooLargeException,
W/ActivityManager(  964): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  964): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  964): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2009)
,W/ActivityManager(  964): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1547)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1060)
W/ActivityManager(  964): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:958)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6859)
W/ActivityManager(  964): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  964): ,	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  964): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  964): Recipient 5274
,I/Prism.ItemManager( 1476): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1476): loadItems() com.htc.launcher.pageview.WidgetManager@22d8110d +
I/Prism.WidgetManager( 1476): onLoadItems() +
,I/ActivityManager(  964): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5361 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/TrimMemoryManager( 1476): [trimMemory] 20
,W/ActivityManager(  964): Spurious death for ProcessRecord{7f224ee 5361:com.google.android.apps.docs/u0a107}, curProc for 5274: null
,W/ResourcesManager( 5344): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1476): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  964): setSystemUiVisibility(0x8000)
,D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5170): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 5170): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5170): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5170): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,E/SharedPreferencesImpl( 5170): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,D/DeviceConnectionService( 1694): client connected with version: 7571000,
,W/ServiceConnection( 1694): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1694): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 1694): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 1694): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1088)
W/ServiceConnection( 1694): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
W/ServiceConnection( 1694): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 1694): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 1694): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 1694): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1694): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1694): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 1694): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 1694): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 1694): 	... 7 more
,W/FileUtils( 1694): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=11
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,W/ResourcesManager( 1476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10,
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=10
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted,
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,I/GAv4    ( 5361): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5361):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5361):   adb logcat -s GAv4
,W/GAv4    ( 5361): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5361): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5361): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5361): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 5361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5361): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5361): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5361): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5361): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5361): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 5361): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,E/SQLiteDatabase( 5361): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237),
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218),
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5361): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5361): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5361): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5361): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5361): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5361): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5361): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5361): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5361): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5361): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5361): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5361): ,	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5361): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5361): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5361): 	at aen.run(PG:536)
,E/qdoverlay(  364): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  364): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  364): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  364): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  364): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
E/qdhwcomposer(  364): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=11
E/qdoverlay(  364): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  364): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  364): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  364): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted,
E/qdoverlay(  364): MdpCtrl close error in unset
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/,
W/ContextImpl( 5361): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
E/SQLiteDatabase( 5361): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5361): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5361): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5361): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5361): 	at aej.c(PG:139)
E/SQLiteDatabase( 5361): 	at aej.b(PG:398)
E/SQLiteDatabase( 5361): 	at agf.f(PG:417)
E/SQLiteDatabase( 5361): 	at oe.run(PG:1112)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5361): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 5361): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 5361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 5361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AbstractDatabaseInstance( 5361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 5361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 5361): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 5361): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 5361): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 5361): 	at aej.c(PG:139)

```
