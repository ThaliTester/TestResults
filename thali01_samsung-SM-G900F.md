#### Test 80912877ffdb7be_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-24 10:04:06.531  5451  5451 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
,08-24 10:04:06.531  5451  5451 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-24 10:04:06.531  5451  5451 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-24 10:04:06.531  5451  5451 I art     : System.exit called, status: 0
08-24 10:04:06.531  5451  5451 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-24 10:04:06.571   749  1220 I ActivityManager: Process com.samsung.aasaservice (pid 5451)(adj 0) has died(114,719)
08-24 10:04:06.571   749  1220 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-24 10:04:06.571   749  1220 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-24 10:04:06.571   749  1220 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-24 10:04:06.571  5406  5406 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-24 10:04:06.601   749   806 I ActivityManager: Start proc 6330:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-24 10:04:06.611  6330  6330 E Zygote  : v2
08-24 10:04:06.611  6330  6330 I libpersona: KNOX_SDCARD checking this for 10014
08-24 10:04:06.611   749  1325 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 10:04:06.611  6330  6330 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:06.611  6330  6330 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:06.611  6330  6330 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:06.611  6330  6330 E Zygote  : accessInfo : 0
08-24 10:04:06.621  6330  6330 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-24 10:04:06.671  6330  6330 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:06.671  6330  6330 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:06.671   749  2142 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7616826 6330:com.google.android.partnersetup/u0a14}
08-24 10:04:06.681   749  1325 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-24 10:04:06.681  6330  6330 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-24 10:04:06.691  6330  6330 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-24 10:04:06.711   749  2143 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7616826 6330:com.google.android.partnersetup/u0a14}
08-24 10:04:06.731  6355  6355 E Zygote  : v2
08-24 10:04:06.731  6355  6355 I libpersona: KNOX_SDCARD checking this for 10015
08-24 10:04:06.731  6355  6355 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:06.731  6355  6355 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:06.731  6355  6355 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:06.731   749   764 I ActivityManager: Start proc 6355:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-24 10:04:06.741  6355  6355 E Zygote  : accessInfo : 0
08-24 10:04:06.741  6355  6355 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-24 10:04:06.761  6355  6355 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:06.761  6355  6355 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:06.761   749  2126 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ecb2bd 6355:com.samsung.groupcast/u0a15}
08-24 10:04:06.771   749  1220 I ActivityManager: Killing 5484:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-24 10:04:06.771  6355  6355 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-24 10:04:06.781   749  1322 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-24 10:04:06.801  6355  6355 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-24 10:04:06.821  6355  6355 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-24 10:04:06.821  6355  6355 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-24 10:04:06.821  6355  6355 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-24 10:04:06.821  6355  6355 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 10:04:06.821  6355  6355 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 10:04:06.821  6355  6355 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 10:04:06.821  6355  6355 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 10:04:06.821  6355  6355 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 10:04:06.831   749  2209 I ActivityManager: Killing 5496:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-24 10:04:06.831   749  2209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63632e1 2035:com.sec.android.app.shealth:remote/u0a34}
08-24 10:04:06.851  6367  6367 E Zygote  : v2
08-24 10:04:06.851  6367  6367 I libpersona: KNOX_SDCARD checking this for 10041
08-24 10:04:06.851  6367  6367 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:06.851   749  2142 I ActivityManager: Start proc 6367:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-24 10:04:06.851  6367  6367 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:06.851  6367  6367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:06.851  6367  6367 E Zygote  : accessInfo : 0
08-24 10:04:06.851  6367  6367 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-24 10:04:06.851   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-24 10:04:06.871  6367  6367 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:06.871  6367  6367 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:06.881   749  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6be0b2 6367:com.samsung.android.sdk.samsunglink/u0a41}
08-24 10:04:06.891  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-24 10:04:06.971  6367  6367 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 10:04:06.971  6367  6367 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 10:04:07.011   749  3460 D SSRM:n  : SIOP:: AP = 480, PST = 453, CUR = 350, LCD = 0
08-24 10:04:07.031  6367  6367 I SL_DEBUG: isLoggable:: isProductShip = 1
08-24 10:04:07.031  6367  6367 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-24 10:04:07.041   749  2126 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.041   749  1591 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-24 10:04:07.051   749   762 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.051   749  1593 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.051   749  1590 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.051   749  2143 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.061   749  1220 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: onUnbind
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: CSB onClientsDisconnected
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDown
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDownCarState
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: Skip, car not connected.
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDownClientState
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: requestStop
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: onDestroy
08-24 10:04:07.061   749  2218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDown
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDownCarState
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: Skip, car not connected.
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: tearDownClientState
08-24 10:04:07.061  6216  6216 D CAR.SERVICE: requestStop
08-24 10:04:07.071   749  1500 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.071   749  2126 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-24 10:04:07.081  6216  6216 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@292fb57 that was originally bound here
08-24 10:04:07.081  6216  6216 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@292fb57 that was originally bound here
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 10:04:07.081  6216  6216 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 10:04:07.081   749  1590 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@c7c7c75
08-24 10:04:07.171  6367  6367 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-24 10:04:07.171  6367  6367 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-24 10:04:07.171  6367  6367 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-24 10:04:07.171  6367  6367 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-24 10:04:07.171  6367  6367 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-24 10:04:07.171  6367  6367 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 10:04:07.171  6367  6367 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 10:04:07.171  6367  6367 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 10:04:07.171  6367  6367 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 10:04:07.171  6367  6367 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 10:04:07.181   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6cdf3a 1654:android.process.acore/u0a19}
08-24 10:04:07.191  5118  5118 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-24 10:04:07.191   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{15d63a7 5118:com.sec.android.gallery3d/u0a47}
08-24 10:04:07.201   749  1220 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 10:04:07.221   749   764 I ActivityManager: Start proc 6390:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-24 10:04:07.221  6390  6390 E Zygote  : v2
08-24 10:04:07.221  6390  6390 I libpersona: KNOX_SDCARD checking this for 10050
08-24 10:04:07.221  6390  6390 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.221  6390  6390 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.221  6390  6390 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.221  6390  6390 E Zygote  : accessInfo : 0
08-24 10:04:07.221  6390  6390 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-24 10:04:07.251  6390  6390 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.251  6390  6390 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.251   749  2142 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf807f3 6390:com.sec.android.app.myfiles/u0a50}
08-24 10:04:07.261  6390  6390 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-24 10:04:07.281  6390  6390 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-24 10:04:07.321  6390  6390 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 10:04:07.331   749  2142 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6e4de5 2875:com.android.settings/1000}
08-24 10:04:07.341   331   331 E installd: system dir 0 : /system/app/
08-24 10:04:07.341   331   331 E installd: system dir 1 : /system/priv-app/
08-24 10:04:07.341   331   331 E installd: system dir 2 : /vendor/app/
08-24 10:04:07.341   331   331 E installd: system dir 3 : /oem/app/
08-24 10:04:07.351   749  2209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6e4de5 2875:com.android.settings/1000}
08-24 10:04:07.351   749   892 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 10:04:07.371   749  1322 I ActivityManager: Start proc 6405:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-24 10:04:07.371  6405  6405 E Zygote  : v2
08-24 10:04:07.371  6405  6405 I libpersona: KNOX_SDCARD checking this for 10169
08-24 10:04:07.371  6405  6405 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.371  6405  6405 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.371  6405  6405 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.371  6405  6405 E Zygote  : accessInfo : 0
08-24 10:04:07.371  6405  6405 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-24 10:04:07.391  6405  6405 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.391  6405  6405 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.401   749   764 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{881304f 6405:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-24 10:04:07.411  6405  6405 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-24 10:04:07.411  6405  6405 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-24 10:04:07.431   749  1591 I ActivityManager: Killing 4836:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-24 10:04:07.431   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2daf2c2 1738:com.android.phone/1001}
08-24 10:04:07.441  2084  2084 E audit   : type=1400 msg=audit(1472025847.441:284): avc:  denied  { execmod } for  pid=6328 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 10:04:07.441  2084  2084 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.441  2084  2084 E audit   : type=1300 msg=audit(1472025847.441:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd6000 a1=51000 a2=5 a3=4 items=0 ppid=3590 ppcomm=adbd pid=6328 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 10:04:07.441  2084  2084 E audit   : type=1327 msg=audit(1472025847.441:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 10:04:07.441  2084  2084 E audit   : type=1320 msg=audit(1472025847.441:284): 
08-24 10:04:07.441   749  1322 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a466ad 1831:com.google.android.googlequicksearchbox:search/u0a61}
08-24 10:04:07.461   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-24 10:04:07.471   749  2142 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a466ad 1831:com.google.android.googlequicksearchbox:search/u0a61}
08-24 10:04:07.471   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e66ce5 6257:com.samsung.android.sm.provider/1000}
08-24 10:04:07.491   749  1593 I ActivityManager: Start proc 6419:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-24 10:04:07.491  6419  6419 E Zygote  : v2
08-24 10:04:07.491  6419  6419 I libpersona: KNOX_SDCARD checking this for 5012
08-24 10:04:07.491  6419  6419 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.491  6419  6419 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.491  6419  6419 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.491  6419  6419 E Zygote  : accessInfo : 0
08-24 10:04:07.491  6419  6419 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-24 10:04:07.491  1831  6417 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 10:04:07.501  2084  2084 E audit   : type=1400 msg=audit(1472025847.501:285): avc:  denied  { execmod } for  pid=6328 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 10:04:07.501  2084  2084 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.501  2084  2084 E audit   : type=1300 msg=audit(1472025847.501:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f96000 a1=51000 a2=5 a3=4 items=0 ppid=3590 ppcomm=adbd pid=6328 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 10:04:07.501  2084  2084 E audit   : type=1327 msg=audit(1472025847.501:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 10:04:07.501  2084  2084 E audit   : type=1320 msg=audit(1472025847.501:285): 
08-24 10:04:07.531  6419  6419 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.531  6419  6419 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.541   749  2201 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6853ba 6419:com.samsung.android.sm.devicesecurity/5012}
08-24 10:04:07.551  2084  2084 E audit   : type=1400 msg=audit(1472025847.551:286): avc:  denied  { execmod } for  pid=6328 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 10:04:07.551  2084  2084 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.551  2084  2084 E audit   : type=1300 msg=audit(1472025847.551:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f96000 a1=51000 a2=5 a3=4 items=0 ppid=3590 ppcomm=adbd pid=6328 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 10:04:07.551  2084  2084 E audit   : type=1327 msg=audit(1472025847.551:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 10:04:07.551  2084  2084 E audit   : type=1320 msg=audit(1472025847.551:286): 
08-24 10:04:07.551  6419  6419 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-24 10:04:07.551  6328  6328 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 10:04:07.551  1831  6417 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 10:04:07.551  6328  6328 D AndroidRuntime: CheckJNI is OFF
08-24 10:04:07.551  6328  6328 D AndroidRuntime: readGMSProperty: start
08-24 10:04:07.551  6328  6328 D AndroidRuntime: readGMSProperty: already setted!!
08-24 10:04:07.551  6328  6328 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 10:04:07.551  6328  6328 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 10:04:07.551  6328  6328 D AndroidRuntime: readGMSProperty: end
08-24 10:04:07.551  6328  6328 D AndroidRuntime: addProductProperty: start
08-24 10:04:07.561  6419  6419 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-24 10:04:07.561  6328  6328 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 10:04:07.561  6328  6328 W art     : aedfd000-b1d23000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 10:04:07.561  6328  6328 W art     : b1d23000-b3f92000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 10:04:07.561  6328  6328 W art     : b3f92000-b3f93000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 10:04:07.561  6328  6328 W art     : b3f93000-b3f94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 10:04:07.561  6328  6328 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 10:04:07.561  6328  6328 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 10:04:07.561  6328  6328 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 10:04:07.561  6328  6328 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 10:04:07.561  6328  6328 W art     : b4868000-b486b000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 10:04:07.561  6328  6328 W art     : b486b000-b486c000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 10:04:07.561  6328  6328 W art     : b486c000-b486d000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 10:04:07.561  6328  6328 W art     : b486d000-b486e000 r--p 00000000 00:00 0 
08-24 10:04:07.561  1831  6417 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 10:04:07.561  6328  6328 W art     : b486e000-b488e000 r--s 00000000 00:0b 6572       /dev/__properties__
08-24 10:04:07.561  6328  6328 W art     : b488e000-b529f000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 10:04:07.561  6328  6328 W art     : b529f000-b52a0000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b52a0000-b52e9000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 10:04:07.561  6328  6328 W art     : b52e9000-b52ea000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 10:04:07.561  6328  6328 W art     : b52ea000-b52f2000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b52f2000-b52f3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b52f3000-b5328000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 10:04:07.561  6328  6328 W art     : b5328000-b5329000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5329000-b532a000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 10:04:07.561  6328  6328 W art     : b532a000-b532b000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 10:04:07.561  6328  6328 W art     : b532b000-b5383000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 10:04:07.561  6328  6328 W art     : b5383000-b5384000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5384000-b5385000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 10:04:07.561  6328  6328 W art     : b5385000-b5386000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 10:04:07.561  6328  6328 W art     : b5387000-b538d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 10:04:07.561  6328  6328 W art     : b538d000-b538e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 10:04:07.561  6328  6328 W art     : b538e000-b538f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 10:04:07.561  6328  6328 W art     : b538f000-b5391000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5392000-b539c000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 10:04:07.561  6328  6328 W art     : b539c000-b539f000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 10:04:07.561  6328  6328 W art     : b539f000-b53a0000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 10:04:07.561  6328  6328 W art     : b53a1000-b53b8000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 10:04:07.561  6328  6328 W art     : b53b8000-b53b9000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b53b9000-b53ba000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 10:04:07.561  6328  6328 W art     : b53ba000-b53bb000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 10:04:07.561  6328  6328 W art     : b53bc000-b53c6000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 10:04:07.561  6328  6328 W art     : b53c6000-b53c7000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 10:04:07.561  6328  6328 W art     : b53c7000-b53c8000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 10:04:07.561  6328  6328 W art     : b53c8000-b53cc000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 10:04:07.561  6328  6328 W art     : b53cc000-b53cd000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 10:04:07.561  6328  6328 W art     : b53cd000-b53ce000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 10:04:07.561  6328  6328 W art     : b53ce000-b53e4000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 10:04:07.561  6328  6328 W art     : b53e4000-b53e5000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 10:04:07.561  6328  6328 W art     : b53e5000-b53e6000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 10:04:07.561  6328  6328 W art     : b53e6000-b53f3000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 10:04:07.561  6328  6328 W art     : b53f3000-b53f4000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 10:04:07.561  6328  6328 W art     : b53f4000-b53f5000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 10:04:07.561  6328  6328 W art     : b53f5000-b5455000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 10:04:07.561  6328  6328 W art     : b5455000-b5458000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 10:04:07.561  6328  6328 W art     : b5458000-b545c000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b545c000-b54bd000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 10:04:07.561  6328  6328 W art     : b54bd000-b54be000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 10:04:07.561  6328  6328 W art     : b54be000-b550d000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 10:04:07.561  6328  6328 W art     : b550d000-b550f000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 10:04:07.561  6328  6328 W art     : b550f000-b5510000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 10:04:07.561  6328  6328 W art     : b5510000-b5511000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5511000-b5518000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 10:04:07.561  6328  6328 W art     : b5518000-b5519000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 10:04:07.561  6328  6328 W art     : b5519000-b551a000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-24 10:04:07.561  6328  6328 W art     : avc_common.so
08-24 10:04:07.561  6328  6328 W art     : b551b000-b551e000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 10:04:07.561  6328  6328 W art     : b551e000-b551f000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 10:04:07.561  6328  6328 W art     : b551f000-b5520000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-24 10:04:07.561  6328  6328 W art     : enc_common.so
08-24 10:04:07.561  6328  6328 W art     : b5521000-b5525000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 10:04:07.561  6328  6328 W art     : b5525000-b5526000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5526000-b5527000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 10:04:07.561  6328  6328 W art     : b5527000-b5528000 rw-p 00005000 b3:17 2510       /syste
08-24 10:04:07.561  6328  6328 W art     : m/lib/libpowermanager.so
08-24 10:04:07.561  6328  6328 W art     : b5529000-b5546000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 10:04:07.561  6328  6328 W art     : b5546000-b5547000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 10:04:07.561  6328  6328 W art     : b5547000-b5548000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 10:04:07.561  6328  6328 W art     : b5549000-b554e000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 10:04:07.561  6328  6328 W art     : b554e000-b554f000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 10:04:07.561  6328  6328 W art     : b554f000-b5550000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 10:04:07.561  6328  6328 W art     : b5551000-b5582000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 10:04:07.561  6328  6328 W art     : b5582000-b5585000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 10:04:07.561  6328  6328 W art     : b5585000-b5586000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 10:04:07.561  6328  6328 W art     : b5587000-b55c2000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 10:04:07.561  6328  6328 W art     : b55c2000-b55c3000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 10:04:07.561  6328  6328 W art     : b55c3000-b55c4000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 10:04:07.561  6328  6328 W art     : b55c5000-b55cc000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 10:04:07.561  6328  6328 W art     : b55cc000-b55cd000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b55cd000-b55ce000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 10:04:07.561  6328  6328 W art     : b55ce000-b55cf000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 10:04:07.561  6328  6328 W art     : b55cf000-b55d0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b55d0000-b55e7000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 10:04:07.561  6328  6328 W art     : b55e7000-b55e8000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b55e8000-b55eb000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 10:04:07.561  6328  6328 W art     : b55eb000-b55ec000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 10:04:07.561  6328  6328 W art     : b55ec000-b560b000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 10:04:07.561  6328  6328 W art     : b560b000-b560c000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 10:04:07.561  6328  6328 W art     : b560c000-b560d000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 10:04:07.561  6328  6328 W art     : b560d000-b564b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 10:04:07.561  6328  6328 W art     : b564b000-b564c000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b564c000-b564e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 10:04:07.561  6328  6328 W art     : b564e000-b564f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 10:04:07.561  6328  6328 W art     : b5650000-b5657000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 10:04:07.561  6328  6328 W art     : b5657000-b5658000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 10:04:07.561  6328  6328 W art     : b5658000-b5659000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 10:04:07.561  6328  6328 W art     : b565a000-b565d000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 10:04:07.561  6328  6328 W art     : b565d000-b565e000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 10:04:07.561  6328  6328 W art     : b565e000-b565f000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 10:04:07.561  6328  6328 W art     : b565f000-b5665000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 10:04:07.561  6328  6328 W art     : b5665000-b5666000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5666000-b5667000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 10:04:07.561  6328  6328 W art     : b5667000-b5668000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 10:04:07.561  6328  6328 W art     : b5668000-b5671000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 10:04:07.561  6328  6328 W art     : b5671000-b5672000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 10:04:07.561  6328  6328 W art     : b5672000-b5673000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 10:04:07.561  6328  6328 W art     : b5673000-b5704000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 10:04:07.561  6328  6328 W art     : b5704000-b5705000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5705000-b5710000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 10:04:07.561  6328  6328 W art     : b5710000-b5711000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 10:04:07.561  6328  6328 W art     : b5712000-b5724000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 10:04:07.561  6328  6328 W art     : b5724000-b5725000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 10:04:07.561  6328  6328 W art     : b5725000-b5726000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 10:04:07.561  6328  6328 W art     : b5727000-b572c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 10:04:07.561  6328  6328 W art     : b572c000-b572d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 10:04:07.561  6328  6328 W art     : b572d000-b572e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 10:04:07.561  6328  6328 W art     : b572f000-b579c000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 10:04:07.561  6328  6328 W art     : b579c000-b579d000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b579d000-b579f000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 10:04:07.561  6328  6328 W art     : b579f000-b57a0000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 10:04:07.561  6328  6328 W art     : b57a0000-b57a1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b57a1000-b57a8000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 10:04:07.561  6328  6328 W art     : b57a8000-b57a9000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 10:04:07.561  6328  6328 W art     : b57a9000-b57aa000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 10:04:07.561  6328  6328 W art     : b57ab000-b582b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 10:04:07.561  6328  6328 W art     : b582b000-b582c000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b582c000-b582d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 10:04:07.561  6328  6328 W art     : b582d000-b582e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 10:04:07.561  6328  6328 W art     : b582e000-b5845000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5845000-b587c000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 10:04:07.561  6328  6328 W art     : ib/libqc-opt.so
08-24 10:04:07.561  6328  6328 W art     : b587c000-b587d000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 10:04:07.561  6328  6328 W art     : b587d000-b587e000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 10:04:07.561  6328  6328 W art     : b587e000-b589a000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 10:04:07.561  6328  6328 W art     : b589a000-b589b000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 10:04:07.561  6328  6328 W art     : b589b000-b589c000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 10:04:07.561  6328  6328 W art     : b589d000-b58fe000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 10:04:07.561  6328  6328 W art     : b58fe000-b5900000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 10:04:07.561  6328  6328 W art     : b5900000-b5901000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 10:04:07.561  6328  6328 W art     : b5902000-b5929000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 10:04:07.561  6328  6328 W art     : b5929000-b592a000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b592a000-b592b000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 10:04:07.561  6328  6328 W art     : b592b000-b592c000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 10:04:07.561  6328  6328 W art     : b592d000-b5935000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 10:04:07.561  6328  6328 W art     : b5935000-b5937000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 10:04:07.561  6328  6328 W art     : b5937000-b5938000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 10:04:07.561  6328  6328 W art     : b5939000-b593c000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 10:04:07.561  6328  6328 W art     : b593c000-b593d000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 10:04:07.561  6328  6328 W art     : b593d000-b593e000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 10:04:07.561  6328  6328 W art     : b593e000-b5942000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 10:04:07.561  6328  6328 W art     : b5942000-b5943000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5943000-b5944000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 10:04:07.561  6328  6328 W art     : b5944000-b5945000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 10:04:07.561  6328  6328 W art     : b5945000-b5955000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 10:04:07.561  6328  6328 W art     : b5955000-b5956000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 10:04:07.561  6328  6328 W art     : b5956000-b5957000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 10:04:07.561  6328  6328 W art     : b5957000-b599d000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b599d000-b59a6000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 10:04:07.561  6328  6328 W art     : b59a6000-b59a7000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 10:04:07.561  6328  6328 W art     : b59a7000-b59a8000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 10:04:07.561  6328  6328 W art     : b59a9000-b59ae000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 10:04:07.561  6328  6328 W art     : b59ae000-b59af000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 10:04:07.561  6328  6328 W art     : b59af000-b59b0000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 10:04:07.561  6328  6328 W art     : b59b0000-b59b3000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 10:04:07.561  6328  6328 W art     : b59b3000-b59b4000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b59b4000-b59b5000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 10:04:07.561  6328  6328 W art     : b59b5000-b59b6000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 10:04:07.561  6328  6328 W art     : b59b7000-b59cf000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 10:04:07.561  6328  6328 W art     : b59cf000-b59d0000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b59d0000-b59d1000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 10:04:07.561  6328  6328 W art     : b59d1000-b59d2000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 10:04:07.561  6328  6328 W art     : b59d3000-b5b6d000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 10:04:07.561  6328  6328 W art     : b5b6d000-b5b6e000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5b6e000-b5b7b000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 10:04:07.561  6328  6328 W art     : b5b7b000-b5b7c000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 10:04:07.561  6328  6328 W art     : b5b7c000-b5b80000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 10:04:07.561  6328  6328 W art     : b5b80000-b5b81000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5b81000-b5b82000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 10:04:07.561  6328  6328 W art     : b5b82000-b5b83000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 10:04:07.561  6328  6328 W art     : b5b83000-b5b96000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 10:04:07.561  6328  6328 W art     : b5b96000-b5b97000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 10:04:07.561  6328  6328 W art     : b5b97000-b5b98000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 10:04:07.561  6328  6328 W art     : b5b98000-b5b99000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 10:04:07.561  6328  6328 W art     : b5b99000-b5be4000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 10:04:07.561  6328  6328 W art     : b5be4000-b5be5000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 10:04:07.561  6328  6328 W art     : b5be5000-b5be6000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 10:04:07.561  6328  6328 W art     : b5be6000-b5be8000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5be9000-b5bfa000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 10:04:07.561  6328  6328 W art     : b5bfa000-b5bfb000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5bfb000-b5bfc000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 10:04:07.561  6328  6328 W art     : b5bfc000-b5bfd000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 10:04:07.561  6328  6328 W art     : b5bfe000-b5c08000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 10:04:07.561  6328  6328 W art     : b5c08000-b5c0a000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 10:04:07.561  6328  6328 W art     : b5c0a000-b5c0b000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 10:04:07.561  6328  6328 W art     : b5c0b000-b5c24000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 10:04:07.561  6328  6328 W art     : b5c24000-b5c25000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 10:04:07.561  6328  6328 W art     : b5c25000-b5c28000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 10:04:07.561  6328  6328 W art     : b5c28000-b5c2c000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5c2c000-b5ca0000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 10:04:07.561  6328  6328 W art     : b5ca0000-b5ca1000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5ca1000-b5ca4000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 10:04:07.561  6328  6328 W art     : b5ca4000-b5ca5000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 10:04:07.561  6328  6328 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5ca6000-b5ca9000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 10:04:07.561  6328  6328 W art     : b5ca9000-b5caa000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 10:04:07.561  6328  6328 W art     : b5caa000-b5cab000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 10:04:07.561  6328  6328 W art     : b5cab000-b5cac000 r--p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5cac000-b5cb1000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 10:04:07.561  6328  6328 W art     : b5cb1000-b5cb2000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 10:04:07.561  6328  6328 W art     : b5cb2000-b5cb3000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 10:04:07.561  6328  6328 W art     : b5cb3000-b5cb4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b5cb4000-b5cb7000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 10:04:07.561  6328  6328 W art     : b5cb7000-b5cb8000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 10:04:07.561  6328  6328 W art     : b5cb8000-b5cb9000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 10:04:07.561  6328  6328 W art     : b5cb9000-b5cba000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b5cba000-b5cbe000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 10:04:07.561  6328  6328 W art     : b5cbe000-b5cbf000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 10:04:07.561  6328  6328 W art     : b5cbf000-b5cc0000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 10:04:07.561  6328  6328 W art     : b5cc0000-b5cc1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 10:04:07.561  6328  6328 W art     : b5cc1000-b5cc5000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 10:04:07.561  6328  6328 W art     : b5cc5000-b5cc6000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 10:04:07.561  6328  6328 W art     : b5cc6000-b5cc7000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 10:04:07.561  6328  6328 W art     : b5cc7000-b5cc8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b5cc8000-b5cd6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 10:04:07.561  6328  6328 W art     : b5cd6000-b5cd7000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b5cd7000-b5cd8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 10:04:07.561  6328  6328 W art     : b5cd8000-b5cd9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 10:04:07.561  6328  6328 W art     : b5cd9000-b5ce3000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 10:04:07.561  6328  6328 W art     : b5ce3000-b5ce6000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 10:04:07.561  6328  6328 W art     : b5ce6000-b5ce7000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 10:04:07.561  6328  6328 W art     : b5ce7000-b5ce8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b5ce8000-b5cf2000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 10:04:07.561  6328  6328 W art     : b5cf2000-b5cf5000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 10:04:07.561  6328  6328 W art     : b5cf5000-b5cf6000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 10:04:07.561  6328  6328 W art     : b5cf6000-b5cfa000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 10:04:07.561  6328  6328 W art     : b5cfa000-b5cfb000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 10:04:07.561  6328  6328 W art     : b5cfb000-b5cfc000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 10:04:07.561  6328  6328 W art     : b5cfc000-b5cfd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b5cfd000-b5d0a000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 10:04:07.561  6328  6328 W art     : b5d0a000-b5d0c000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 10:04:07.561  6328  6328 W art     : b5d0c000-b5d0d000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 10:04:07.561  6328  6328 W art     : b5d0d000-b611f000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 10:04:07.561  6328  6328 W art     : b611f000-b6120000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6120000-b6129000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 10:04:07.561  6328  6328 W art     : b6129000-b612d000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 10:04:07.561  6328  6328 W art     : b612d000-b612e000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b612e000-b6135000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 10:04:07.561  6328  6328 W art     : b6135000-b6136000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 10:04:07.561  6328  6328 W art     : b6136000-b6137000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 10:04:07.591  6431  6431 I libpersona: KNOX_SDCARD checking this for 10210
08-24 10:04:07.561  6328  6328 W art     : b6137000-b6138000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.591  6431  6431 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.561  6328  6328 W art     : b6138000-b6153000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 10:04:07.561  6328  6328 W art     : b6153000-b6154000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 10:04:07.561  6328  6328 W art     : b6154000-b6155000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 10:04:07.561  6328  6328 W art     : b6155000-b6156000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b6156000-b61a2000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 10:04:07.561  6328  6328 W art     : b61a2000-b61a3000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b61a3000-b61a4000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 10:04:07.561  6328  6328 W art     : b61a4000-b61a5000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 10:04:07.561  6328  6328 W art     : b61a5000-b61a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b61a6000-b61aa000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 10:04:07.561  6328  6328 W art     : b61aa000-b61ab000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b61ab000-b61ac000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 10:04:07.561  6328  6328 W art     : b61ac000-b61ad000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 10:04:07.561  6328  6328 W art     : b61ad000-b61e5000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 10:04:07.561  6328  6328 W art     : b61e5000-b61e6000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 10:04:07.561  6328  6328 W art     : b61e6000-b61e7000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 10:04:07.591   749   806 I ActivityManager: Start proc 6431:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-24 10:04:07.561  6328  6328 W art     : b61e7000-b61e8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.561  6328  6328 W art     : b61e8000-b6286000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 10:04:07.561  6328  6328 W art     : b6286000-b6287000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6287000-b62a5000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 10:04:07.561  6328  6328 W art     : b62a5000-b62a6000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 10:04:07.561  6328  6328 W art     : b62a6000-b6419000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 10:04:07.561  6328  6328 W art     : b6419000-b6424000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 10:04:07.561  6328  6328 W art     : b6424000-b6425000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 10:04:07.561  6328  6328 W art     : b6425000-b653c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 10:04:07.561  6328  6328 W art     : b653c000-b6547000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 10:04:07.561  6328  6328 W art     : b6547000-b6548000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 10:04:07.561  6328  6328 W art     : b6548000-b654c000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b654c000-b6570000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 10:04:07.561  6328  6328 W art     : b6570000-b6572000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 10:04:07.561  6328  6328 W art     : b6572000-b6573000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 10:04:07.561  6328  6328 W art     : b6573000-b6619000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 10:04:07.561  6328  6328 W art     : b6619000-b6626000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 10:04:07.561  6328  6328 W art     : b6626000-b6627000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 10:04:07.561  6328  6328 W art     : b6627000-b6628000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6628000-b667b000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 10:04:07.561  6328  6328 W art     : b667b000-b667c000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b667c000-b667d000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 10:04:07.561  6328  6328 W art     : b667d000-b667e000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 10:04:07.561  6328  6328 W art     : b667e000-b6683000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6683000-b6695000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 10:04:07.561  6328  6328 W art     : b6695000-b6696000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6696000-b6697000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 10:04:07.561  6328  6328 W art     : b6697000-b6698000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 10:04,:07.561  6328  6328 W art     : b6698000-b669f000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 10:04:07.561  6328  6328 W art     : b669f000-b66a0000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 10:04:07.561  6328  6328 W art     : b66a0000-b66a1000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 10:04:07.561  6328  6328 W art     : b66a1000-b66a2000 rw-p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b66a2000-b66a5000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 10:04:07.561  6328  6328 W art     : b66a5000-b66a6000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 10:04:07.561  6328  6328 W art     : b66a6000-b66a7000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 10:04:07.561  6328  6328 W art     : b66a7000-b66ab000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 10:04:07.561  6328  6328 W art     : b66ab000-b66ac000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 10:04:07.561  6328  6328 W art     : b66ac000-b66ad000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 10:04:07.561  6328  6328 W art     : b66ad000-b66bb000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 10:04:07.561  6328  6328 W art     : b66bb000-b66bc000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b66bc000-b66bd000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 10:04:07.561  6328  6328 W art     : b66bd000-b66be000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 10:04:07.561  6328  6328 W art     : b66be000-b66c7000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 10:04:07.561  6328  6328 W art     : b66c7000-b66c8000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 10:04:07.561  6328  6328 W art     : b66c8000-b66c9000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 10:04:07.561  6328  6328 W art     : b66c9000-b672f000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 10:04:07.561  6328  6328 W art     : b672f000-b6730000 ---p 00000000 00:00 0 
08-24 10:04:07.561  6328  6328 W art     : b6730000-b6732000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 10:04:07.571  6328  6328 W art     : b6732000-b673b000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 10:04:07.571  6328  6328 W art     : b673b000-b673e000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b673e000-b67d5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 10:04:07.571  6328  6328 W art     : b67d5000-b67d7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 10:04:07.571  6328  6328 W art     : b67d7000-b67d8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 10:04:07.571  6328  6328 W art     : b67d8000-b67d9000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b67d9000-b6afa000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 10:04:07.571  6328  6328 W art     : b6afa000-b6afb000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6afb000-b6b16000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 10:04:07.571  6328  6328 W art     : b6b16000-b6b1a000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 10:04:07.571  6328  6328 W art     : b6b1a000-b6b1f000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6b1f000-b6b27000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 10:04:07.571  6328  6328 W art     : b6b27000-b6b28000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 10:04:07.571  6328  6328 W art     : b6b28000-b6b29000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 10:04:07.571  6328  6328 W art     : b6b29000-b6b57000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 10:04:07.571  6328  6328 W art     : b6b57000-b6b58000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6b58000-b6b5f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 10:04:07.571  6328  6328 W art     : b6b5f000-b6b60000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 10:04:07.571  6328  6328 W art     : b6b60000-b6ba6000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 10:04:07.571  6328  6328 W art     : b6ba6000-b6ba7000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6ba7000-b6baa000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 10:04:07.571  6328  6328 W art     : b6baa000-b6bab000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 10:04:07.571  6328  6328 W art     : b6bab000-b6bc6000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 10:04:07.571  6328  6328 W art     : b6bc6000-b6bca000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 10:04:07.571  6328  6328 W art     : b6bca000-b6bcb000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 10:04:07.571  6328  6328 W art     : b6bcb000-b6c18000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 10:04:07.571  6328  6328 W art     : b6c18000-b6c19000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6c19000-b6c25000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 10:04:07.571  6328  6328 W art     : b6c25000-b6c26000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 10:04:07.571  6328  6328 W art     : b6c26000-b6c33000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 10:04:07.571  6328  6328 W art     : b6c33000-b6c34000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6c34000-b6c35000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 10:04:07.571  6328  6328 W art     : b6c35000-b6c36000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 10:04:07.571  6328  6328 W art     : b6c36000-b6c3e000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 10:04:07.571  6328  6328 W art     : b6c3e000-b6c3f000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6c3f000-b6c40000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 10:04:07.571  6328  6328 W art     : b6c40000-b6c41000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 10:04:07.571  6328  6328 W art     : b6c41000-b6c48000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 10:04:07.571  6328  6328 W art     : b6c48000-b6c49000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 10:04:07.571  6328  6328 W art     : b6c49000-b6c4a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 10:04:07.571  6328  6328 W art     : b6c4a000-b6c5e000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 10:04:07.571  6328  6328 W art     : b6c5e000-b6c60000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 10:04:07.571  6328  6328 W art     : b6c60000-b6c61000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 10:04:07.571  6328  6328 W art     : b6c61000-b6c89000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 10:04:07.571  6328  6328 W art     : b6c89000-b6c8b000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 10:04:07.571  6328  6328 W art     : b6c8b000-b6c8c000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 10:04:07.571  6328  6328 W art     : b6c8c000-b6c8f000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 10:04:07.571  6328  6328 W art     : b6c8f000-b6c90000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 10:04:07.571  6328  6328 W art     : b6c90000-b6c91000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 10:04:07.571  6328  6328 W art     : b6c91000-b6c9a000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 10:04:07.571  6328  6328 W art     : b6c9a000-b6c9b000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 10:04:07.571  6328  6328 W art     : b6c9b000-b6c9c000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 10:04:07.571  6328  6328 W art     : b6c9c000-b6cbc000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 10:04:07.571  6328  6328 W art     : b6cbc000-b6cbd000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 10:04:07.571  6328  6328 W art     : b6cbd000-b6cbe000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 10:04:07.571  6328  6328 W art     : b6cbe000-b6d31000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 10:04:07.571  6328  6328 W art     : b6d31000-b6d35000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 10:04:07.571  6328  6328 W art     : b6d35000-b6d38000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 10:04:07.571  6328  6328 W art     : b6d38000-b6d42000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6d42000-b6dca000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 10:04:07.571  6328  6328 W art     : b6dca000-b6dcb000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6dcb000-b6dcf000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 10:04:07.571  6328  6328 W art     : b6dcf000-b6dd0000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 10:04:07.571  6328  6328 W art     : b6dd0000-b6dd1000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6dd1000-b6dfa000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 10:04:07.571  6328  6328 W art     : b6dfa000-b6dfb000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6dfb000-b6dfe000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 10:04:07.571  6328  6328 W art     : b6dfe000-b6dff000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 10:04:07.571  6328  6328 W art     : b6dff000-b6ed9000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 10:04:07.571  6328  6328 W art     : b6ed9000-b6ee0000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 10:04:07.571  6328  6328 W art     : b6ee0000-b6ee8000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 10:04:07.571  6328  6328 W art     : b6ee8000-b6ee9000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6ee9000-b6eea000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 10:04:07.571  6328  6328 W art     : b6eea000-b6eeb000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 10:04:07.571  6328  6328 W art     : b6eeb000-b6eec000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6eec000-b6eef000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6eef000-b6f14000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 10:04:07.571  6328  6328 W art     : b6f14000-b6f15000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f15000-b6f1c000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 10:04:07.571  6328  6328 W art     : b6f1c000-b6f1d000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 10:04:07.571  6328  6328 W art     : b6f1d000-b6f24000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 10:04:07.571  6328  6328 W art     : b6f24000-b6f25000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 10:04:07.571  6328  6328 W art     : b6f25000-b6f26000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 10:04:07.571  6328  6328 W art     : b6f26000-b6f27000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6f27000-b6f3f000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f3f000-b6f40000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f40000-b6f41000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f41000-b6f42000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f42000-b6f50000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f50000-b6f51000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f51000-b6f52000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f52000-b6f53000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 10:04:07.571  6328  6328 W art     : b6f53000-b6f54000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 10:04:07.571  6328  6328 W art     : b6f54000-b6f56000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6f56000-b6f57000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6f57000-b6f58000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 10:04:07.571  6328  6328 W art     : b6f58000-b6f59000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 10:04:07.571  6328  6328 W art     : b6f59000-b6f5a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 10:04:07.571  6328  6328 W art     : b6f5a000-b6f7a000 r--s 00000000 00:0b 6572       /dev/__properties__
08-24 10:04:07.571  6328  6328 W art     : b6f7a000-b6f7b000 r--p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f7b000-b6f7c000 ---p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f7c000-b6f7e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 10:04:07.571  6328  6328 W art     : b6f7e000-b6f7f000 r-xp 00000000 00:00 0          [sigpage]
08-24 10:04:07.571  6328  6328 W art     : b6f7f000-b6f9a000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 10:04:07.571  6328  6328 W art     : b6f9a000-b6f9b000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 10:04:07.571  6328  6328 W art     : b6f9b000-b6f9d000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 10:04:07.571  6328  6328 W art     : b6f9d000-b6f9f000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : b6f9f000-b6fa4000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 10:04:07.571  6328  6328 W art     : b6fa4000-b6fa5000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 10:04:07.571  6328  6328 W art     : b6fa5000-b6fa6000 rw-p 00000000 00:00 0 
08-24 10:04:07.571  6328  6328 W art     : bea2f000-bea50000 rw-p 00000000 00:00 0          [stack]
08-24 10:04:07.571  6328  6328 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-24 10:04:07.591  6431  6431 E Zygote  : v2
08-24 10:04:07.591  6431  6431 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.591  6431  6431 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.591  6431  6431 E Zygote  : accessInfo : 0
08-24 10:04:07.591  6431  6431 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-24 10:04:07.611  6328  6328 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 10:04:07.621   749  2143 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-24 10:04:07.651  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.651  6431  6431 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.651  6328  6328 I Radio-JNI: register_android_hardware_Radio DONE
08-24 10:04:07.661  6328  6328 E AffinityControl: AffinityControl: registerfunction enter
08-24 10:04:07.671  6431  6431 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-24 10:04:07.681  6328  6328 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 10:04:07.691  6431  6431 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-24 10:04:07.701  2796  6448 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-24 10:04:07.711   749  1592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3942e07 3213:com.android.contacts/u0a19}
,08-24 10:04:07.721  6431  6431 D AASAservice: onCreate()
08-24 10:04:07.721   749  1590 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-24 10:04:07.731   749  1590 D ActivityManager: mDVFSHelper.acquire()
08-24 10:04:07.731   749  1590 V WindowManager: addAppToken: AppWindowToken{ad18c99 token=Token{5c591e0 ActivityRecord{b32d3e3 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-24 10:04:07.741   749   860 D SecWifiDisplayUtil: Metadata value : none
08-24 10:04:07.741   749   860 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2af35d1 V.E...... R.....ID 0,0-0,0}
08-24 10:04:07.741   749   860 D ISSUE_DEBUG: InputChannelName : 45ae337 Starting com.test.thalitest
08-24 10:04:07.751   749  1590 I ActivityManager: Start proc 6452:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-24 10:04:07.751  6452  6452 E Zygote  : v2
08-24 10:04:07.751  6452  6452 I libpersona: KNOX_SDCARD checking this for 10004
08-24 10:04:07.751  6452  6452 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.751  6452  6452 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.751  6452  6452 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.751  6452  6452 E Zygote  : accessInfo : 0
08-24 10:04:07.751  6452  6452 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-24 10:04:07.751   749  1590 D InputDispatcher: Focused application set to: xxxx
08-24 10:04:07.751   749  1590 D InputDispatcher: Focus left window: 4533
08-24 10:04:07.751  6328  6328 D AndroidRuntime: Shutting down VM
08-24 10:04:07.761   295   295 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-24 10:04:07.761   749   807 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{604815a u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-24 10:04:07.771  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-24 10:04:07.771  6464  6464 E Zygote  : v2
08-24 10:04:07.771  6464  6464 I libpersona: KNOX_SDCARD checking this for 10049
08-24 10:04:07.771  6464  6464 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:07.771  6464  6464 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:07.771  5406  5406 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-24 10:04:07.771  6464  6464 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:07.781  6464  6464 E Zygote  : accessInfo : 0
08-24 10:04:07.781  6464  6464 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-24 10:04:07.781   749  1591 I ActivityManager: Start proc 6464:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-24 10:04:07.781   749  1325 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 10:04:07.781   749   860 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
08-24 10:04:07.781   749   860 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 10:04:07.781   749   860 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
08-24 10:04:07.781   749   860 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 10:04:07.781   749   860 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-24 10:04:07.791   749  1325 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:04:07.791  6,452  6452 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.791  6452  6452 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.801   749  2201 I ActivityManager: Killing 5175:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-24 10:04:07.811   749   860 V WindowStateAnimator: Finishing drawing window Window{45ae337 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-24 10:04:07.821   749  2142 V WindowOrientationListener: setCurrentAppOrientation :-1
08-24 10:04:07.821   749  2142 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-24 10:04:07.821  6464  6464 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:07.821  6464  6464 D ActivityThread: Added TimaKeyStore provider
08-24 10:04:07.831   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
08-24 10:04:07.841  1831  6417 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 351 ms] updated apps [took 351 ms] 
08-24 10:04:07.841   749   807 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{45ae337 u0 d0 Starting com.test.thalitest}
08-24 10:04:07.851  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-24 10:04:07.851   295   355 I SurfaceFlinger: id=19 Removed YUIInstallC (7/10)
08-24 10:04:07.851   295   372 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-24 10:04:07.861  4533  4533 V ActivityThread: updateVisibility : ActivityRecord{ff87ea7 token=android.os.BinderProxy@949c978 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-24 10:04:07.861   749  2142 D ActivityManager:  Launching com.test.thalitest, updated priority
08-24 10:04:07.881  1752  1918 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-24 10:04:07.881  1752  1752 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-24 10:04:07.891   295   372 D libEGL  : eglTerminate EGLDisplay = 0xb667f64c
08-24 10:04:07.891   295   372 D libEGL  : eglTerminate EGLDisplay = 0xb667f64c
08-24 10:04:07.901   749   806 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-24 10:04:07.901   295  1298 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-24 10:04:07.901   295   372 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-24 10:04:07.911  6452  6452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 10:04:07.911   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbed7e3a4
08-24 10:04:07.911  2366  2464 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-24 10:04:07.921  1752  1752 V ActivityThread: updateVisibility : ActivityRecord{4874e20 token=android.os.BinderProxy@8c4deaa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 10:04:07.921  1752  1752 D Launcher: onTrimMemory. Level: 20
08-24 10:04:07.921   749   764 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9d13310 6464:com.android.mms/u0a49}
08-24 10:04:07.921   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-24 10:04:07.941   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 10:04:07.951  6464  6464 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 10:04:07.951  6452  6452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 10:04:07.961  6452  6452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 10:04:07.971  6452  6452 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-24 10:04:07.981  6464  6464 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-24 10:04:07.981  6464  6464 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-24 10:04:08.001  6452  6452 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 10:04:08.011  6452  6452 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 10:04:08.021  6452  6452 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 9949-9953)
08-24 10:04:08.021  6452  6452 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 10:04:08.031  6464  6464 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-24 10:04:08.041  6452  6452 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a79eba}
08-24 10:04:08.041  6452  6452 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 10:04:08.041  6452  6452 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 10:04:08.041  6452  6479 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-24 10:04:08.041  6464  6482 D Mms/ArtClassLoader: init before art third
,08-24 10:04:08.041  6464  6481 D Mms/ArtClassLoader: init before art second
,08-24 10:04:08.041  6464  6480 D Mms/ArtClassLoader: init before art first
,08-24 10:04:08.051  6464  6464 D Mms/TelephonyPermission: start operation mode monitor
,08-24 10:04:08.051  6464  6464 D Mms/TelephonyPermission: User ID is null set current User Id
08-24 10:04:08.051  6452  6452 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 10:04:08.061   749   759 I art     : Background partial concurrent mark sweep GC freed 146851(8MB) AllocSpace objects, 11(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.889ms total 158.314ms
,08-24 10:04:08.071  6452  6452 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 10:04:08.071  6452  6452 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 10:04:08.071  6452  6452 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 10:04:08.071  6452  6452 I Adreno-EGL: Local Branch: ss
08-24 10:04:08.071  6452  6452 I Adreno-EGL: Remote Branch: 
08-24 10:04:08.071  6452  6452 I Adreno-EGL: Local Patches: 
08-24 10:04:08.071  6452  6452 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:04:08.071  6464  6464 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 10:04:08.071  6464  6464 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 10:04:08.081  6452  6452 D libEGL  : eglInitialize EGLDisplay = 0xbedb7dac
,08-24 10:04:08.091  6464  6482 D Mms/ArtClassLoader: init [DONE] art
,08-24 10:04:08.101  6464  6464 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,08-24 10:04:08.101  6464  6464 D Mms/TelephonyPermission: isDefault true
,08-24 10:04:08.111  6464  6464 D Mms/MmsApp: onCreate() com.android.mms
,08-24 10:04:08.111   749  2218 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-24 10:04:08.111   749  2218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-24 10:04:08.151  6452  6452 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-24 10:04:08.171  6464  6464 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-24 10:04:08.171  6452  6452 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 10:04:08.171  6452  6452 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-24 10:04:08.171  6452  6452 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-24 10:04:08.171  6452  6452 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-24 10:04:08.181  6464  6464 D Mms/MmsApp: [start]    initCountryIso consume time = 144.51599
,08-24 10:04:08.181   749  2218 D CountryDetector: The first listener is added
,08-24 10:04:08.191  6464  6464 D Mms/MmsApp: [end]    initCountryIso consume time = 9.111459
,08-24 10:04:08.191  6464  6464 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.262656
,08-24 10:04:08.191  6452  6452 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-24 10:04:08.201  6464  6464 D Mms/MmsConfig: before partial update
08-24 10:04:08.201  6452  6452 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 10:04:08.221  6464  6481 D Mms/ArtClassLoader: init [DONE] art
,08-24 10:04:08.231  6464  6480 D Mms/ArtClassLoader: init [DONE] art
,08-24 10:04:08.241  6464  6464 D Mms/MmsConfig: Load Resize quality : 80
,08-24 10:04:08.261  6464  6464 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 10:04:08.261  6464  6464 D EasySignUpManager_1.0.5: isAuth is false
08-24 10:04:08.261  6464  6464 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-24 10:04:08.261  6464  6464 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-24 10:04:08.261  6464  6464 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-24 10:04:08.261  6464  6464 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 10:04:08.261  6464  6464 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-24 10:04:08.261  6464  6464 D EasySignUpManager_1.0.5: isAuth is false
08-24 10:04:08.261  6464  6464 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 10:04:08.261  6464  6464 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-24 10:04:08.261  6464  6464 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-24 10:04:08.271  1738  1751 D TP/MmsSmsProvider: query, match:2117, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.271  1738  1751 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.175 ms
,08-24 10:04:08.281  6464  6464 E CscParser: mps_code.dat does not exist
,08-24 10:04:08.281  6464  6464 E CscParser: customer_path =/system/csc/customer.xml
08-24 10:04:08.281  6464  6464 E CscParser: fileName + /system/csc/customer.xml
,08-24 10:04:08.291  6464  6464 E CscParser: mps_code.dat does not exist
,08-24 10:04:08.291  6464  6464 E CscParser: customer_path =/system/csc/customer.xml
08-24 10:04:08.291  6464  6464 E CscParser: fileName + /system/csc/customer.xml
,08-24 10:04:08.301  6464  6464 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-24 10:04:08.301  6464  6464 D Mms/MmsConfig:  enable multiwindow = true
,08-24 10:04:08.301  6464  6464 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-24 10:04:08.301  6464  6464 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-24 10:04:08.301  6464  6464 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-24 10:04:08.301  6464  6464 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-24 10:04:08.301  6464  6464 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-24 10:04:08.301  6464  6464 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-24 10:04:08.301  6464  6464 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 10:04:08.311  6452  6452 D SecWifiDisplayUtil: Metadata value : none
,08-24 10:04:08.311  6452  6452 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5919728 I.E...... R.....ID 0,0-0,0}
,08-24 10:04:08.311  6464  6464 D Mms/MmsConfig: [end]    init() consume time = 126.772864
,08-24 10:04:08.321  6452  6510 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 10:04:08.321   749  1590 D ISSUE_DEBUG: InputChannelName : bcb04e9 com.test.thalitest/com.test.thalitest.MainActivity
,08-24 10:04:08.321   749  2209 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-24 10:04:08.321   749  2209 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 10:04:08.321   749   749 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 10:04:08.331   749   749 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 10:04:08.341  6464  6464 D Mms/Contact: [start]    init() consume time = 21.174636
,08-24 10:04:08.351  6452  6452 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6452
,08-24 10:04:08.351   749  1592 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6452 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 10:04:08.351   749  1334 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-24 10:04:08.361   749  1334 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 10:04:08.361   749  1334 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 10:04:08.361   749  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-24 10:04:08.361   749  1334 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 10:04:08.361  1738  1750 D TP/MmsSmsProvider: query, match:13, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.371  1738  1750 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.588 ms
,08-24 10:04:08.371  6452  6479 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-24 10:04:08.381  6452  6452 D SecWifiDisplayUtil: Metadata value : none
,08-24 10:04:08.381  6464  6464 D Mms/Contact: [end]    init consume time = 42.992083
,08-24 10:04:08.391  6464  6464 D Mms:transaction: roaming -> false (slotId = 0)
08-24 10:04:08.391  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 10:04:08.391  6464  6464 D Mms:transaction: auto download without roaming -> true
08-24 10:04:08.391  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 10:04:08.391  6464  6464 D Mms:transaction: roaming -> false (slotId = 1)
08-24 10:04:08.391  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 10:04:08.391  6464  6464 D Mms:transaction: auto download without roaming -> true
08-24 10:04:08.391  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 10:04:08.391  6464  6464 D Mms:transaction: auto download during roaming secondary -> false
08-24 10:04:08.391  6464  6464 D Mms:transaction: mAutoDownload ------> true
,08-24 10:04:08.391   295   295 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
08-24 10:04:08.391  6464  6516 D Mms/DraftCache: [start]    rebuildCache consume time = 15.385469
,08-24 10:04:08.411  1738  1939 D TP/MmsSmsProvider: query, match:12, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.411  1738  1939 D TP/MmsSmsProvider: query, match 12:Elapsed time : 2.297 ms
,08-24 10:04:08.411   749  2126 D InputDispatcher: Focus entered window: 6452
,08-24 10:04:08.411  6464  6516 D Mms/DraftCache: [end]    rebuildCache consume time = 18.258333
,08-24 10:04:08.421   749   860 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
,08-24 10:04:08.421   749   860 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 10:04:08.421   749   860 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
08-24 10:04:08.421   749   860 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 10:04:08.421  6452  6510 D libEGL  : eglInitialize EGLDisplay = 0x9c9797c4
08-24 10:04:08.421  6452  6510 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 10:04:08.451  6464  6464 D ComposerPerformance: 1472025848467 ms / [DONE] Composer constructor
,08-24 10:04:08.451  6464  6464 D CII     : Log Level [5]
,08-24 10:04:08.451  6464  6464 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-24 10:04:08.461  6464  6519 D Mms/Conversation: [start]    init() consume time = 43.81948
,08-24 10:04:08.461  1738  1750 D TP/MmsSmsProvider: delete, match:1, calling pid = 6464
,08-24 10:04:08.461  1738  1750 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-24 10:04:08.461  1738  1750 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-24 10:04:08.461  1738  1750 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-24 10:04:08.461  1738  1750 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-24 10:04:08.461  1738  1750 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-24 10:04:08.461  6464  6464 I Mms/ReservationManager: ReservationManager()
,08-24 10:04:08.461  6464  6464 I Mms/ReservationManager: resetAfterConnected()
,08-24 10:04:08.471  1738  1750 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-24 10:04:08.471  1738  1899 D TP/MmsSmsProvider: query, match:7, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.481  6452  6452 V ActivityThread: updateVisibility : ActivityRecord{1cf4ec3 token=android.os.BinderProxy@92014b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 10:04:08.481  6452  6452 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 10:04:08.491  1738  1750 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-24 10:04:08.491  1738  1899 D TP/MmsSmsProvider: query, match 7:Elapsed time : 10.896 ms
08-24 10:04:08.491  1738  1750 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-24 10:04:08.491  1738  1750 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 10:04:08.491  1738  1750 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 11.254 ms
08-24 10:04:08.491  1738  1750 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 10:04:08.491  6464  6519 D Mms/Conversation: [end]    init consume time = 30.533854
,08-24 10:04:08.491  6464  6464 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 10:04:08.491  6464  6519 D Mms/MessagingNotification: [start]    init() consume time = 3.254114
,08-24 10:04:08.491  6464  6519 D Mms/MessagingNotification: [end]    init consume time = 1.357083
,08-24 10:04:08.491  6464  6464 D Mms/MmsApp: [end]    onCreate() consume time = 1.492865
,08-24 10:04:08.491  6464  6464 D Mms/MmsApp: [end]    onCreate() consume time = 0.218333
,08-24 10:04:08.491  6464  6521 D Mms/Synchronizer: [start]    doSync consume time = 1.606615
,08-24 10:04:08.501  6464  6464 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-24 10:04:08.501   749  1322 V WindowStateAnimator: Finishing drawing window Window{bcb04e9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-24 10:04:08.501  6452  6452 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-24 10:04:08.511   749  1220 I ActivityManager: Start proc 6523:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-24 10:04:08.511  6452  6452 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 10:04:08.511  6464  6520 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 13.664948
,08-24 10:04:08.511  6523  6523 E Zygote  : v2
08-24 10:04:08.511  6523  6523 I libpersona: KNOX_SDCARD checking this for 1000
08-24 10:04:08.511  6523  6523 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:08.511  6523  6523 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:08.511  6523  6523 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:08.511   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
08-24 10:04:08.511  6523  6523 E Zygote  : accessInfo : 0
,08-24 10:04:08.511   749  2218 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 10:04:08.521   749  1220 I ActivityManager: Killing 5147:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-24 10:04:08.521  6464  6464 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-24 10:04:08.521  6464  6464 D Mms:transaction: roaming -> false (slotId = 0)
08-24 10:04:08.521  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 10:04:08.521  6464  6464 D Mms:transaction: auto download without roaming -> true
08-24 10:04:08.521  6464  6464 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 10:04:08.521  6464  6464 D Mms:transaction: mAutoDownload ------> true
,08-24 10:04:08.521  1738  1751 D TP/MmsSmsProvider: query, match:0, calling pid = 6464, accessRestricted = false
08-24 10:04:08.521  1738  1751 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 10:04:08.521   749   860 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 10:04:08.521   749   749 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 10:04:08.521  1738  1751 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.128 ms
,08-24 10:04:08.521   749   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +622ms (total +786ms)
,08-24 10:04:08.521   749   749 I KnoxTimeoutHandler: SD activityfalse
08-24 10:04:08.521   749   860 D ActivityManager: mDVFSHelper.release()
08-24 10:04:08.521   749   860 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b32d3e3 u0 com.test.thalitest/.MainActivity t168} time:100457
,08-24 10:04:08.521   749   860 D ViewRootImpl: #3 mView = null
,08-24 10:04:08.521  1738  1750 D TP/MmsSmsProvider: update, match:300, calling pid = 6464
,08-24 10:04:08.531   295   355 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
08-24 10:04:08.531   295   355 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
08-24 10:04:08.531   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbed7e3a4
08-24 10:04:08.531  1738  1750 V TP/MmsSmsProvider: syncDBData start
08-24 10:04:08.531  1738  1750 V TP/MmsSmsProvider: syncDBData sms end
,08-24 10:04:08.541  1738  1750 V TP/MmsSmsProvider: syncDBData mms end
,08-24 10:04:08.541  1738  1750 V TP/MmsSmsProvider: syncDBData end
,08-24 10:04:08.541  1738  1750 D TP/MmsSmsProvider: update, match 300:Elapsed time : 12.270 ms
,08-24 10:04:08.551   749  1593 V WindowStateAnimator: Finishing drawing window Window{bcb04e9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-24 10:04:08.551  6452  6452 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 10:04:08.551  6452  6452 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@92014b time:100484
,08-24 10:04:08.561  6132  6143 D BadgeProvider: query, [selection] : package=?
,08-24 10:04:08.561   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
,08-24 10:04:08.561  6464  6519 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-24 10:04:08.571  6464  6521 D Mms/Synchronizer: [end]    doSync consume time = 59.166094
,08-24 10:04:08.581  1738  1939 D TP/SmsProvider: query,matched:26, calling pid = 6464
,08-24 10:04:08.581  1738  1939 D TP/SmsProvider: query, match 26:Elapsed time : 0.928 ms
,08-24 10:04:08.581  6523  6523 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:04:08.581  6523  6523 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:08.581  1738  1899 D TP/MmsSmsProvider: query, match:400, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.591   749  1591 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-24 10:04:08.591   749  1500 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be4e61e 6523:com.samsung.android.bbc.bbcagent/1000}
,08-24 10:04:08.601  6452  6537 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 10:04:08.601  6452  6537 D libEGL  : eglInitialize EGLDisplay = 0x99a7f3ec
,08-24 10:04:08.611  6523  6523 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
08-24 10:04:08.611  6464  6520 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 38.856823
,08-24 10:04:08.611  1738  1751 D TP/MmsSmsProvider: query, match:6, calling pid = 6464, accessRestricted = false
,08-24 10:04:08.611  1738  1751 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.193 ms
,08-24 10:04:08.641   749  1220 I ActivityManager: Start proc 6540:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-24 10:04:08.641  6540  6540 E Zygote  : v2
08-24 10:04:08.641  6540  6540 I libpersona: KNOX_SDCARD checking this for 10024
08-24 10:04:08.641  6540  6540 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:08.641  6540  6540 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:08.641  6540  6540 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:08.641  6540  6540 E Zygote  : accessInfo : 0
,08-24 10:04:08.641  6540  6540 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-24 10:04:08.641  6523  6523 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-24 10:04:08.651  6452  6452 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6452
,08-24 10:04:08.671  6540  6540 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:08.671  6540  6540 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:08.681   749  2209 I ActivityManager: Start proc 6553:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-24 10:04:08.681  6553  6553 E Zygote  : v2
08-24 10:04:08.681  6553  6553 I libpersona: KNOX_SDCARD checking this for 10097
08-24 10:04:08.681  6553  6553 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:08.681  6553  6553 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:08.681  6553  6553 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:08.681  6553  6553 E Zygote  : accessInfo : 0
,08-24 10:04:08.681  6553  6553 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-24 10:04:08.681   749  2209 I ActivityManager: Killing 5203:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-24 10:04:08.691   749  2126 I ActivityManager: Killing 4691:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-24 10:04:08.711   749  2142 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-24 10:04:08.711  6553  6553 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:04:08.711  6553  6553 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:08.721   749   764 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c74eff 6553:com.google.android.apps.docs/u0a97}
08-24 10:04:08.721  6540  6540 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-24 10:04:08.731  6553  6553 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 10:04:08.741   749  2142 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-24 10:04:08.751  6540  6540 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-24 10:04:08.761  6553  6553 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-24 10:04:08.801  6540  6540 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-24 10:04:08.811  6464  6519 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 10:04:08.811  6452  6452 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-24 10:04:08.831  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-24 10:04:08.841   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-24 10:04:08.841  2796  5094 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-24 10:04:08.841  6540  6540 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-24 10:04:08.871  2796  5094 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-24 10:04:08.931  6452  6566 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1723082448
,08-24 10:04:08.931   749  3461 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 10:04:08.931  6452  6566 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b37b1 added. We now have 1 listener(s)
,08-24 10:04:08.941  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-24 10:04:08.941  6452  6566 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-24 10:04:08.941  6452  6566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 10:04:08.941  6452  6566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 10:04:08.951  2796  5094 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 10:04:08.951  6452  6566 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7458404 added. We now have 1 listener(s)
,08-24 10:04:08.951  6452  6566 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 10:04:08.951  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 10:04:08.951  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 10:04:08.951  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 10:04:08.951  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 10:04:08.951  6452  6566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 10:04:08.961  6452  6566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 10:04:08.961  6452  6566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-24 10:04:08.961  6452  6566 D BluetoothAdapter: STATE_ON
,08-24 10:04:08.971  6452  6566 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:04:08.971  6452  6566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 10:04:08.971  6452  6566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 10:04:08.971  6452  6566 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 10:04:08.971  6452  6452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 10:04:08.971  6452  6566 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 10:04:08.971  6452  6452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 10:04:09.021  6452  6452 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 10:04:09.131  6553  6570 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-24 10:04:09.131  6553  6570 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 10:04:09.131  6553  6570 I GAv4    :   adb logcat -s GAv4
,08-24 10:04:09.161  6553  6570 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 10:04:09.161   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{e695fcd: PendingIntentRecord{39c7082 com.google.android.apps.docs broadcastIntent}}
,08-24 10:04:09.171  6553  6570 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:04:09.171  6553  6570 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:04:09.191  6553  6576 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:04:09.301  6553  6553 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-24 10:04:09.301  6553  6553 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-24 10:04:09.321  6553  6570 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-24 10:04:09.321  6553  6570 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-24 10:04:09.321  6553  6570 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-24 10:04:09.321  6553  6570 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-24 10:04:09.331  1457  1457 D Recents : onTaskStackChanged
,08-24 10:04:09.341  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 10:04:09.381  6582  6582 E Zygote  : v2
08-24 10:04:09.381  6582  6582 I libpersona: KNOX_SDCARD checking this for 10098
08-24 10:04:09.381  6582  6582 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:09.381  6582  6582 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:09.381  6582  6582 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:09.381   749  1592 I ActivityManager: Start proc 6582:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-24 10:04:09.381  6582  6582 E Zygote  : accessInfo : 0
,08-24 10:04:09.381  6582  6582 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-24 10:04:09.381   749  1592 I ActivityManager: Killing 5511:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-24 10:04:09.411   749  1590 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-24 10:04:09.411  6582  6582 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:09.411  6582  6582 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:09.431   749  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea512ce 6582:com.sec.android.automotive.drivelink/u0a98}
,08-24 10:04:09.441  6582  6582 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 10:04:09.451   749  6239 I HarmonyEASService: Updating for all 1
,08-24 10:04:09.461  6582  6582 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-24 10:04:09.491  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:09.491  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:09.501  6582  6582 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 10:04:09.511   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{8838dda: PendingIntentRecord{5d8020b com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 10:04:09.511  6582  6599 I GMPM    : App measurement is starting up
,08-24 10:04:09.511  6582  6582 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-24 10:04:09.521  6582  6599 E GMPM    : getGoogleAppId failed with status: 10
,08-24 10:04:09.521  6582  6599 E GMPM    : Uploading is not possible. App measurement disabled
,08-24 10:04:09.521   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{d1a68e8: PendingIntentRecord{5d8020b com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 10:04:09.531  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:09.541  6582  6582 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-24 10:04:09.551  6582  6582 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-24 10:04:09.591  6605  6605 E Zygote  : v2
08-24 10:04:09.591  6605  6605 I libpersona: KNOX_SDCARD checking this for 10032
08-24 10:04:09.591  6605  6605 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:09.591  6605  6605 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:09.591  6605  6605 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:09.591  6553  6571 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-24 10:04:09.591   749  2201 I ActivityManager: Start proc 6605:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-24 10:04:09.591   749  1325 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 10:04:09.591  6605  6605 E Zygote  : accessInfo : 0
,08-24 10:04:09.591  6605  6605 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-24 10:04:09.621  6605  6605 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:04:09.631  6605  6605 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:09.631   749  1325 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-24 10:04:09.641  6605  6605 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-24 10:04:09.641  6553  6571 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-24 10:04:09.651  6605  6605 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-24 10:04:09.691  6553  6571 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 10:04:09.691  6553  6571 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-24 10:04:09.691  6553  6571 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 10:04:09.731  6553  6571 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 10:04:09.751  6582  6582 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-24 10:04:09.751  6582  6582 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-24 10:04:09.751  6582  6582 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-24 10:04:09.781  6582  6582 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 24 10:04:09 GMT+02:00 2016
,08-24 10:04:09.781  6605  6605 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
08-24 10:04:09.781  6582  6582 D DialogFlow: initQueue()
,08-24 10:04:09.791  6619  6619 E Zygote  : v2
,08-24 10:04:09.791  6619  6619 I libpersona: KNOX_SDCARD checking this for 1000
08-24 10:04:09.791  6619  6619 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:09.791  6619  6619 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:04:09.791   749  2142 I ActivityManager: Start proc 6619:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-24 10:04:09.791   749  2142 I ActivityManager: Killing 5095:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
08-24 10:04:09.791   749  2142 I ActivityManager: Killing 5565:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
08-24 10:04:09.791  6619  6619 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:09.791  6619  6619 E Zygote  : accessInfo : 0
,08-24 10:04:09.811   749  1590 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-24 10:04:09.811  6452  6567 W jxcore-log: Initializing JXcore engine
08-24 10:04:09.811  6452  6567 W jxcore-log: JXcore engine is ready
,08-24 10:04:09.821  6605  6605 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-24 10:04:09.821  6619  6619 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:09.821  6619  6619 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:09.841   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{89838df 6619:com.samsung.android.app.filterinstaller/1000}
,08-24 10:04:09.841   749  2218 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-24 10:04:09.851  6619  6619 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-24 10:04:09.861  2084  2084 E audit   : type=1400 msg=audit(1472025849.861:287): avc:  denied  { ioctl } for  pid=6567 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 10:04:09.861  2084  2084 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:09.861  2084  2084 E audit   : type=1300 msg=audit(1472025849.861:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=993b03c8 items=0 ppid=359 ppcomm=main pid=6567 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 10:04:09.861  2084  2084 E audit   : type=1327 msg=audit(1472025849.861:287): proctitle="com.test.thalitest"
08-24 10:04:09.861  2084  2084 E audit   : type=1320 msg=audit(1472025849.861:287): 
08-24 10:04:09.861  6619  6619 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-24 10:04:09.861  2084  2084 E audit   : type=1400 msg=audit(1472025849.861:288): avc:  denied  { ioctl } for  pid=6567 comm="Thread-899" path="socket:[40349]" dev="sockfs" ino=40349 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 10:04:09.861  2084  2084 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:09.861  2084  2084 E audit   : type=1300 msg=audit(1472025849.861:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=993b03c8 items=0 ppid=359 ppcomm=main pid=6567 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 10:04:09.861  2084  2084 E audit   : type=1327 msg=audit(1472025849.861:288): proctitle="com.test.thalitest"
08-24 10:04:09.861  2084  2084 E audit   : type=1320 msg=audit(1472025849.861:288): 
,08-24 10:04:09.871  6619  6619 E FilterPackageIntentReceiver: This package is not a effect filter
,08-24 10:04:09.871  6452  6567 W jxcore-log: Starting JXcore engine
,08-24 10:04:09.881  6635  6635 E Zygote  : v2
08-24 10:04:09.881  6635  6635 I libpersona: KNOX_SDCARD checking this for 1000
08-24 10:04:09.881  6635  6635 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:09.881   749   762 I ActivityManager: Start proc 6635:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-24 10:04:09.881  6635  6635 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:09.881  6635  6635 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:09.881   749   762 I ActivityManager: Killing 5613:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-24 10:04:09.891   749  1322 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-24 10:04:09.891   749  1592 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-24 10:04:09.911  6605  6605 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-24 10:04:09.911  6605  6605 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-24 10:04:09.921  6605  6605 D DialogFlow: initQueue()
,08-24 10:04:09.931  6635  6635 E Zygote  : accessInfo : 0
,08-24 10:04:09.951  6635  6635 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:09.951  6635  6635 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:09.951   749  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f41cc56 6635:com.samsung.helphub/1000}
,08-24 10:04:09.961  6635  6635 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-24 10:04:09.961  6452  6567 W jxcore-log: Platform android
08-24 10:04:09.961  6452  6567 W jxcore-log: 
08-24 10:04:09.961  6452  6567 W jxcore-log: Process ARCH arm
08-24 10:04:09.961  6452  6567 W jxcore-log: 
,08-24 10:04:09.971  6635  6635 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-24 10:04:10.021  6647  6647 E Zygote  : v2
,08-24 10:04:10.021  6647  6647 I libpersona: KNOX_SDCARD checking this for 1000
08-24 10:04:10.021  6647  6647 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:10.021   749   762 I ActivityManager: Start proc 6647:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-24 10:04:10.021  6647  6647 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:04:10.021  6647  6647 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:04:10.021  6647  6647 E Zygote  : accessInfo : 0
,08-24 10:04:10.021   749   762 I ActivityManager: Killing 5394:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-24 10:04:10.051  6647  6647 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:04:10.051  6647  6647 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:10.051   749  2142 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-24 10:04:10.061   749  2209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bca64d7 6647:com.samsung.android.app.mirrorlink/1000}
,08-24 10:04:10.071  6647  6647 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-24 10:04:10.091  6647  6647 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-24 10:04:10.131  6647  6647 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-24 10:04:10.131  6647  6647 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-24 10:04:10.131   749  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc816e9 5748:com.google.android.apps.plus/u0a134}
,08-24 10:04:10.141   749  2142 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc816e9 5748:com.google.android.apps.plus/u0a134}
,08-24 10:04:10.161   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc816e9 5748:com.google.android.apps.plus/u0a134}
,08-24 10:04:10.161  6452  6567 I jxcore-log: JXcore Cordova bridge is ready!
08-24 10:04:10.161  6452  6567 I jxcore-log: 
,08-24 10:04:10.161  6452  6567 W jxcore-log: JXcore engine is started
,08-24 10:04:10.161  6452  6566 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 10:04:10.171  6452  6452 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 10:04:10.191   749  2201 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-24 10:04:10.191   749  2143 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-24 10:04:10.191   749  1593 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-24 10:04:10.201   749  1590 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-24 10:04:10.201   749  2209 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-24 10:04:10.201   749  1322 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-24 10:04:10.211   749  1592 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-24 10:04:10.211   749  1591 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-24 10:04:10.251   749  1590 I ActivityManager: Start proc 6661:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-24 10:04:10.251  6661  6661 E Zygote  : v2
08-24 10:04:10.251  6661  6661 I libpersona: KNOX_SDCARD checking this for 10165
08-24 10:04:10.251  6661  6661 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:10.251  6661  6661 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:10.251  6661  6661 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:10.251  6661  6661 E Zygote  : accessInfo : 0
08-24 10:04:10.251  6661  6661 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-24 10:04:10.261   749  1590 I ActivityManager: Killing 5646:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-24 10:04:10.271   749  1322 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-24 10:04:10.281  6661  6661 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:10.281  6661  6661 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:10.291   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c2657e2 6661:com.sec.kidsplat.installer/u0a165}
,08-24 10:04:10.301  6661  6661 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-24 10:04:10.311  6661  6661 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-24 10:04:10.321   749  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c2657e2 6661:com.sec.kidsplat.installer/u0a165}
,08-24 10:04:10.321  6661  6661 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-24 10:04:10.331   749   764 I ActivityManager: Start proc 6673:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-24 10:04:10.331  6673  6673 E Zygote  : v2
08-24 10:04:10.331   749  1325 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 10:04:10.331  6673  6673 I libpersona: KNOX_SDCARD checking this for 10142
08-24 10:04:10.331  6673  6673 I libpersona: KNOX_SDCARD not a persona
08-24 10:04:10.331  6673  6673 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 10:04:10.331  6673  6673 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:10.331  6673  6673 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:10.331  6673  6673 E Zygote  : accessInfo : 64
08-24 10:04:10.331   749   764 I ActivityManager: Killing 4810:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
08-24 10:04:10.331  6673  6673 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 10:04:10.331  6673  6673 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-24 10:04:10.341  6673  6673 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-24 10:04:10.341   749  1325 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:04:10.361  6673  6673 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:10.361  6673  6673 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:10.371   749  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5e67773 6673:com.sec.android.app.sbrowser/u0a142}
,08-24 10:04:10.371  6673  6673 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 10:04:10.381   749  1593 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-24 10:04:10.391  6673  6673 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-24 10:04:10.441  6673  6673 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 10:04:10.461  6673  6673 D ManifestProvider: onCreate()
,08-24 10:04:10.471  6673  6673 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-24 10:04:10.471  6673  6673 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 10:04:10.471  6673  6673 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 10:04:10.471  6673  6673 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-24 10:04:10.481  6673  6673 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-24 10:04:10.481  6673  6673 D [MM]MHDataBaseProvider: onCreate()
,08-24 10:04:10.491  6673  6673 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@539b947)
,08-24 10:04:10.511   749  2218 I ActivityManager: Killing 5625:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-24 10:04:10.511   749  2218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
,08-24 10:04:10.521   749  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{509aeed 2796:com.google.android.gms/u0a11}
,08-24 10:04:10.531  2796  6688 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 10:04:10.531  6464  6464 I Mms/MmsApp:  start initViewCache mms
,08-24 10:04:10.541   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-24 10:04:10.551  2796  6687 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-24 10:04:10.551  2796  6688 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 10:04:10.551  2796  2796 D AsyncTaskServiceImpl: Submit a task: nzm
08-24 10:04:10.561  2796  5094 D nzm     : Processing package: com.test.thalitest
08-24 10:04:10.571   749  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
08-24 10:04:10.591  2796  6688 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-24 10:04:10.591   749  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{509aeed 2796:com.google.android.gms/u0a11}
08-24 10:04:10.601  2796  2796 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
08-24 10:04:10.601  2796  6688 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-24 10:04:10.661  2796  5094 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-24 10:04:10.661  2796  5094 D nzm     : Found info for package com.test.thalitest in db.
08-24 10:04:10.681   749   759 I art     : Background partial concurrent mark sweep GC freed 24953(1603KB) AllocSpace objects, 1(20KB) LOS objects, 27% free, 42MB/58MB, paused 1.744ms total 119.191ms
08-24 10:04:10.711   749  2209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98fefe1 5779:com.android.vending/u0a29}
08-24 10:04:10.761   749  2143 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d520eb8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cb2b47 6163:com.sec.android.app.samsungapps/u0a39}
08-24 10:04:10.771  5779  5779 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
08-24 10:04:10.771   749  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d87d92 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
08-24 10:04:10.781   749  1592 V AlarmManager:  remove PendingIntent] PendingIntent{a5c2363: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
08-24 10:04:10.801  5779  5779 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
08-24 10:04:10.801   749  2143 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a6392bf u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98fefe1 5779:com.android.vending/u0a29}
08-24 10:04:10.821  5779  6695 I Finsky  : [831] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
08-24 10:04:10.821   749  1367 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
08-24 10:04:10.821   749  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6722cea u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c47942 5839:com.sec.android.app.shealth/u0a34}
08-24 10:04:10.831  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-24 10:04:10.831   749  2126 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6722cea u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63632e1 2035:com.sec.android.app.shealth:remote/u0a34}
08-24 10:04:10.841  5779  6696 I PlayCommon: [832] com.google.android.play.a.w.a(27553): Starting to flush logs
08-24 10:04:10.841  5779  6696 I PlayCommon: [832] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
08-24 10:04:10.861  6605  6633 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 10:04:10.861  6605  6633 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 10:04:10.911  1959  1959 D WearableService: callingUid 10011, callindPid: 1959
08-24 10:04:10.911  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 10:04:10.911  5779  5779 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-24 10:04:10.911  5779  5779 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
08-24 10:04:10.921   749  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6722cea u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63632e1 2035:com.sec.android.app.shealth:remote/u0a34}
08-24 10:04:10.931  6464  6464 D Mms/BubbleViewCache: fillCache bubble = 4
08-24 10:04:10.951  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
08-24 10:04:10.961  6605  6633 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 10:04:10.961  6605  6633 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 10:04:10.961  6605  6633 I System.out: INFO:Resource not found:/Common.properties Using default values
08-24 10:04:10.961  5779  5815 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:10.961  5779  5815 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:10.961   749  2209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a6c90 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
08-24 10:04:10.961   316  1188 D EnterpriseController: netId is 0
08-24 10:04:10.961   316  1188 D Netd    : getNetworkForDns: using netid 502 for uid 10029
08-24 10:04:10.971  6605  6633 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 10:04:10.971  6605  6633 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 10:04:11.231  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.a(945): Successfully uploaded logs.
08-24 10:04:11.231  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-24 10:04:11.231  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(732): No file ready to send
,08-24 10:04:11.951  2796  5013 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-24 10:04:12.011  2796  5013 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 10:04:12.031  2796  5013 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 10:04:12.031  2796  5013 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-24 10:04:13.841   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:04:13.951   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 10:04:15.731  3704  3704 D FactoryTest: User mode
,08-24 10:04:15.731  3704  3704 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 10:04:15.731  3704  3704 D MTPRx   : still no open session command from host, so toast
,08-24 10:04:15.731   749  1593 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 10:04:15.741   749  1593 D ActivityManager: mDVFSHelper.acquire()
,08-24 10:04:15.741   749  1593 V WindowManager: addAppToken: AppWindowToken{86ca9af token=Token{913d8e ActivityRecord{8e44989 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,08-24 10:04:15.741   749  1593 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-24 10:04:15.751   749   806 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-24 10:04:15.771   749  1593 D InputDispatcher: Focused application set to: xxxx
,08-24 10:04:15.771   749  1593 D InputDispatcher: Focus left window: 6452
,08-24 10:04:15.771   749   860 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
,08-24 10:04:15.771   749   860 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 10:04:15.771   749   860 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
08-24 10:04:15.771   749   860 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 10:04:15.781  3704  3704 E MTPRx   : started activity for popup
,08-24 10:04:15.781  3704  3704 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 10:04:15.781  3704  3704 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 10:04:15.791   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 10:04:15.801  3704  3704 D MTPUSBConnection: onCreate in USBConnection
,08-24 10:04:15.801  3704  3704 V MTPUSBConnection: Registering broadcast receiver.
,08-24 10:04:15.801  3704  3704 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-24 10:04:15.801   749  2142 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-24 10:04:15.851  3704  3704 D TAG     : dev.kiessupport is : TRUE
,08-24 10:04:15.871  3704  3704 D SecWifiDisplayUtil: Metadata value : none
,08-24 10:04:15.871  3704  3704 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ca2b2fb V.E...... R.....I. 0,0-0,0}
,08-24 10:04:15.891  3704  6733 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 10:04:15.891   749  1500 D ISSUE_DEBUG: InputChannelName : 8021fa7 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 10:04:15.891   749  1500 D InputDispatcher: Focus entered window: 3704
,08-24 10:04:15.891   749   807 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8021fa7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-24 10:04:15.891  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-24 10:04:15.891   749   860 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
,08-24 10:04:15.891   749   860 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 10:04:15.891   749   860 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
08-24 10:04:15.891   749   860 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 10:04:15.901  3704  3704 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fae8673 I.E...... R.....I. 0,0-0,0}
,08-24 10:04:15.911   749   764 D ISSUE_DEBUG: InputChannelName : 97387fd com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 10:04:15.911   749  2218 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-24 10:04:15.911   749  2218 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 10:04:15.911   749   749 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 10:04:15.911   749   749 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 10:04:15.911   749   749 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-24 10:04:15.951   295   295 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-24 10:04:15.961  3704  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 10:04:15.961  3704  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 10:04:15.961  3704  6733 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 10:04:15.961  3704  6733 I Adreno-EGL: Local Branch: ss
08-24 10:04:15.961  3704  6733 I Adreno-EGL: Remote Branch: 
08-24 10:04:15.961  3704  6733 I Adreno-EGL: Local Patches: 
08-24 10:04:15.961  3704  6733 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:04:15.971  3704  6733 D libEGL  : eglInitialize EGLDisplay = 0x9f0447c4
,08-24 10:04:15.971  3704  6733 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 10:04:16.011   295   295 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-24 10:04:16.031  3704  3704 V ActivityThread: updateVisibility : ActivityRecord{e4cab2e token=android.os.BinderProxy@cf0df18 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-24 10:04:16.031  3704  3704 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 10:04:16.121   749   764 V WindowStateAnimator: Finishing drawing window Window{8021fa7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 10:04:16.121  3704  3704 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 10:04:16.121   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
,08-24 10:04:16.121   749  2142 V WindowStateAnimator: Finishing drawing window Window{97387fd u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 10:04:16.131  3704  3704 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-24 10:04:16.131  3704  3704 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-24 10:04:16.131   749   860 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 10:04:16.131   749   860 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +367ms (total +388ms)
08-24 10:04:16.131   749   749 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 10:04:16.131   749   749 I KnoxTimeoutHandler: SD activityfalse
,08-24 10:04:16.141   749   860 D ActivityManager: mDVFSHelper.release()
,08-24 10:04:16.141   749   860 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8e44989 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108071
,08-24 10:04:16.141   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
,08-24 10:04:16.151   749   762 V WindowStateAnimator: Finishing drawing window Window{8021fa7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 10:04:16.151   749  1590 V WindowStateAnimator: Finishing drawing window Window{97387fd u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 10:04:16.151  3704  3704 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cf0df18 time:108086
,08-24 10:04:16.151   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbed7e364
,08-24 10:04:16.781   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 10:04:16.901   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:04:16.911  1457  1457 D Recents : onTaskStackChanged
,08-24 10:04:16.931   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{c270f43: PendingIntentRecord{4cd3add com.google.android.gms broadcastIntent}}
,08-24 10:04:16.941   749  1325 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-24 10:04:16.941   749  1325 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-24 10:04:16.951  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 10:04:16.961   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:04:16.961   749   764 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 10:04:16.961   749   764 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-24 10:04:16.961   749   764 D BatteryService: stay LED for charging
,08-24 10:04:16.961   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:04:16.961  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:04:16.961  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:04:16.961  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:04:16.961   749   749 I MotionRecognitionService: Plugged
,08-24 10:04:16.971  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 10:04:16.971  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:04:16.971   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:04:16.971   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 10:04:16.971   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:04:16.981  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:16.991  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 10:04:16.991  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:17.051   749  3460 D SSRM:n  : SIOP:: AP = 480, PST = 455, CUR = 350, LCD = 0
,08-24 10:04:17.411   749   892 D PackageManager: [MSG] MCS_UNBIND
,08-24 10:04:17.421   749  1322 I ActivityManager: Killing 5727:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-24 10:04:17.441   749  1593 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-24 10:04:17.781   749   892 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 10:04:17.811   749   892 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 10:04:18.841   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:04:20.301  6452  6567 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 10:04:20.301  6452  6567 I jxcore-log: 
,08-24 10:04:20.301  6452  6567 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 10:04:20.301  6452  6567 I jxcore-log: 
,08-24 10:04:20.311  6452  6567 D BluetoothAdapter: STATE_ON
,08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:04:20.311  6452  6567 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 10:04:20.311  6452  6567 D BluetoothAdapter: STATE_ON
,08-24 10:04:20.321  6452  6567 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 10:04:20.321  6452  6567 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 10:04:20.321  6452  6567 I jxcore-log: 
,08-24 10:04:20.321  6452  6567 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 10:04:20.321  6452  6567 I jxcore-log: 
,08-24 10:04:20.851  6452  6567 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 10:04:20.851  6452  6567 I jxcore-log: Failed to execute UT.
08-24 10:04:20.851  6452  6567 I jxcore-log: 
08-24 10:04:20.851  6452  6567 I jxcore-log: Unit Test app is loaded
08-24 10:04:20.851  6452  6567 I jxcore-log: 
,08-24 10:04:20.861  6452  6567 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 10:04:20.861  6452  6567 I jxcore-log: 
,08-24 10:04:20.861  6452  6567 I jxcore-log: My device name is: samsung-SM-G900F
08-24 10:04:20.861  6452  6567 I jxcore-log: 
,08-24 10:04:20.861  6452  6567 I jxcore-log: WARN testUtils: myNameCallback not set!
08-24 10:04:20.861  6452  6567 I jxcore-log: 
,08-24 10:04:20.881  6452  6452 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 10:04:21.811   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 10:04:22.171   749   806 I ActivityManager: Waited long enough for: ServiceRecord{1d3847b u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-24 10:04:22.991   749  1322 I ActivityManager: Killing 5406:com.policydm/1000 (adj 15): DHA:empty #37
,08-24 10:04:23.041  6431  6431 D AASAservice: onDestroy()
,08-24 10:04:23.041  6431  6431 I art     : System.exit called, status: 80
,08-24 10:04:23.051  6431  6431 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-24 10:04:23.051   749  2126 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-24 10:04:23.061   749  2201 I ActivityManager: Process com.samsung.aasaservice (pid 6431)(adj 0) has died(58,718)
,08-24 10:04:23.061   749  2201 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-24 10:04:23.081   359   359 I Zygote  : Process 6431 exited cleanly (80)
,08-24 10:04:25.051  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 10:04:25.051  6452  6567 I jxcore-log: 
,08-24 10:04:26.021  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 10:04:26.021  6452  6567 I jxcore-log: 
,08-24 10:04:26.051  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 10:04:26.051  6452  6567 I jxcore-log: 
,08-24 10:04:26.051  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 10:04:26.051  6452  6567 I jxcore-log: 
,08-24 10:04:26.071  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 10:04:26.071  6452  6567 I jxcore-log: 
,08-24 10:04:26.081  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 10:04:26.081  6452  6567 I jxcore-log: 
,08-24 10:04:26.961   749  1325 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-24 10:04:26.961   749  1325 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 10:04:27.101   749  3460 D SSRM:n  : SIOP:: AP = 450, PST = 454, CUR = 350, LCD = 0
,08-24 10:04:28.091   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:04:28.121  2796  2796 I art     : Waiting for a blocking GC DisableMovingGc
,08-24 10:04:28.121  2796  2796 I art     : Starting a blocking GC DisableMovingGc
,08-24 10:04:28.121  5779  5832 I Finsky  : [817] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-24 10:04:28.141   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:04:28.141   749  1591 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 10:04:28.141   749  1591 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-24 10:04:28.141   749  1591 D BatteryService: stay LED for charging
,08-24 10:04:28.141   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:04:28.141   749   749 I MotionRecognitionService: Plugged
08-24 10:04:28.141   749   749 D MotionRecognitionService:   cableConnection= 1
08-24 10:04:28.141   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 10:04:28.141   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:04:28.141  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:04:28.141  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:04:28.141  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:04:28.151  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:04:28.151  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:04:28.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:28.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 10:04:28.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:28.361  5779  5832 I Finsky  : [817] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-24 10:04:28.371  5779  5779 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-24 10:04:28.871   749  1594 E Watchdog: !@Sync 3 [08-24 10:04:28.886]
,08-24 10:04:29.411  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 10:04:29.411  6452  6567 I jxcore-log: 
,08-24 10:04:29.431  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 10:04:29.431  6452  6567 I jxcore-log: 
,08-24 10:04:29.441  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 10:04:29.441  6452  6567 I jxcore-log: 
,08-24 10:04:29.601  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
08-24 10:04:29.601  6452  6567 I jxcore-log: 
,08-24 10:04:30.451  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 10:04:30.451  6452  6567 I jxcore-log: 
,08-24 10:04:30.711  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 10:04:30.711  6452  6567 I jxcore-log: 
,08-24 10:04:30.711  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 10:04:30.711  6452  6567 I jxcore-log: 
,08-24 10:04:30.911  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 10:04:30.911  6452  6567 I jxcore-log: 
,08-24 10:04:30.941  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 10:04:30.941  6452  6567 I jxcore-log: 
,08-24 10:04:30.941  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 10:04:30.941  6452  6567 I jxcore-log: 
,08-24 10:04:30.951  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 10:04:30.951  6452  6567 I jxcore-log: 
,08-24 10:04:30.961  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 10:04:30.961  6452  6567 I jxcore-log: 
,08-24 10:04:30.981  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-24 10:04:30.981  6452  6567 I jxcore-log: 
,08-24 10:04:31.071  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-24 10:04:31.071  6452  6567 I jxcore-log: 
,08-24 10:04:31.071  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-24 10:04:31.071  6452  6567 I jxcore-log: 
,08-24 10:04:31.101  6452  6567 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
08-24 10:04:31.101  6452  6567 I jxcore-log: 
,08-24 10:04:31.111  6452  6567 D BluetoothAdapter: STATE_ON
,08-24 10:04:31.111  6452  6567 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 10:04:31.121  6452  6567 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 10:04:31.121  6452  6567 I jxcore-log: 
,08-24 10:04:32.071   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:04:32.071   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:04:32.071   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:04:37.161   749  3460 D SSRM:n  : SIOP:: AP = 420, PST = 450, CUR = 350, LCD = 0
,08-24 10:04:38.841   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:04:40.791   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:04:40.851   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f42684a u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
,08-24 10:04:40.871   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:04:40.871   749  2126 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:04:40.871   749  2126 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-24 10:04:40.871   749  2126 D BatteryService: stay LED for charging
,08-24 10:04:40.871   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:04:40.871   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{e4923bb: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:40.881   749   749 I MotionRecognitionService: Plugged
,08-24 10:04:40.881   749   749 D MotionRecognitionService:   cableConnection= 1
08-24 10:04:40.881   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:04:40.881   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:04:40.891  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:04:40.891  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:04:40.891  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:04:40.901  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:04:40.901  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:04:40.911  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:40.911  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:40.911  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:41.011   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{1b03c31: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:41.091  2796  6801 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-24 10:04:41.091  2796  6801 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-24 10:04:41.111  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:41.121   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{bc772f0: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:41.151   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e914069 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45e389d 1959:com.google.android.gms.persistent/u0a11}
,08-24 10:04:41.181   749  1592 V AlarmManager:  remove PendingIntent] PendingIntent{fae9aee: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:41.321   749   764 V AlarmManager:  remove PendingIntent] PendingIntent{d747a25: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:41.451  6812  6812 E Zygote  : v2
08-24 10:04:41.451  6812  6812 I libpersona: KNOX_SDCARD checking this for 10011
08-24 10:04:41.451  6812  6812 I libpersona: KNOX_SDCARD not a persona
,08-24 10:04:41.451  6812  6812 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:04:41.451  6812  6812 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 10:04:41.451   749  2201 I ActivityManager: Start proc 6812:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-24 10:04:41.451  6812  6812 E Zygote  : accessInfo : 0
,08-24 10:04:41.451  6812  6812 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-24 10:04:41.481  6812  6812 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:04:41.481  6812  6812 D ActivityThread: Added TimaKeyStore provider
,08-24 10:04:41.491  6812  6812 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 10:04:41.531  6812  6812 I MultiDex: VM with version 2.1.0 has multidex support
08-24 10:04:41.531  6812  6812 I MultiDex: install
08-24 10:04:41.531  6812  6812 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 10:04:41.551  6812  6812 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-24 10:04:41.571  6812  6812 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 10:04:41.571  6812  6812 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-24 10:04:41.571  6812  6812 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 10:04:41.601  6812  6812 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 10:04:41.611  6812  6812 D ChimeraCfgMgr: Reading stored module config
,08-24 10:04:41.751  6812  6826 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-24 10:04:41.751  1959  1959 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=12e8e9a8-dfc3-4eae-86f4-97c0984c4553
,08-24 10:04:41.761  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:41.761  1959  1959 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 10:04:41.791   328   972 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6812)
,08-24 10:04:41.831   328   972 D WVCdm   : Instantiating CDM.
,08-24 10:04:41.831   328   328 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6812)
08-24 10:04:41.831   328   328 I WVCdm   : CdmEngine::OpenSession
08-24 10:04:41.831   328   328 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-24 10:04:41.841   328   328 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-24 10:04:41.841   328   328 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-24 10:04:41.841   328   328 D DrmWidevineDash: Service_Initialize: starts!
08-24 10:04:41.841   328   328 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-24 10:04:41.851   328   328 D QSEECOMAPI: : App is not loaded in QSEE
08-24 10:04:41.851   328   328 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-24 10:04:41.851   328   328 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-24 10:04:41.851   328   328 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-24 10:04:41.851   328   328 D QSEECOMAPI: : App is not loaded in QSEE
08-24 10:04:41.851   328   328 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-24 10:04:41.851   328   328 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-24 10:04:41.851   328   328 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-24 10:04:41.851   328   328 D QSEECOMAPI: : App is not loaded in QSEE
,08-24 10:04:41.871   328   328 D QSEECOMAPI: : Loaded image: APP id = 3
,08-24 10:04:41.871   328   328 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-24 10:04:41.871   328   328 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaed17000
08-24 10:04:41.871   328   328 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaed17000
,08-24 10:04:41.881   328   328 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-24 10:04:41.881   328   328 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-24 10:04:41.891   328   328 D DrmWidevineDash: hlos api version =  10
,08-24 10:04:41.891   328   328 D DrmWidevineDash: tz api version =  10
08-24 10:04:41.891   328   328 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-24 10:04:41.891   328   328 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-24 10:04:41.901   328   328 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbeaf96b4
,08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1ddda68, dataLength=8
,08-24 10:04:41.901   328   328 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-24 10:04:41.901  6812  6822 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:41.901  6812  6822 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:41.911   316  1188 D EnterpriseController: netId is 0
08-24 10:04:41.911   316  1188 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 10:04:41.911  6812  6822 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6812, getuid(): 10011
,08-24 10:04:41.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:04:41.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:04:41.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:04:41.921   328   328 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xaf527800, wrapped_rsa_key_length=1280
,08-24 10:04:41.921   328   328 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-24 10:04:41.921   328   328 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-24 10:04:41.921   328   972 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-24 10:04:41.921   328   972 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-24 10:04:41.921   328   972 I WVCdm   : CdmEngine::GenerateKeyRequest
08-24 10:04:41.921   328   972 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaf2376c0, idLength=0xaefb5f2c
,08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-24 10:04:41.931   328   972 D DrmWidevineDash: hlos api version =  10
08-24 10:04:41.931   328   972 D DrmWidevineDash: tz api version =  10
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-24 10:04:41.931   328   972 D WVCdm   : PrepareKeyRequest: nonce=176477884
08-24 10:04:41.931   328   972 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d43c00
,08-24 10:04:41.931   328   972 D DrmWidevineDash: message_length=1630, signature=0xad41c780, signature_length=2935709700
,08-24 10:04:41.951  1959  2387 W GCoreFlp: No location to return for getLastLocation()
,08-24 10:04:42.011  2796  6802 D UdcContextInitService: registered all accounts: true
,08-24 10:04:42.011  1959  2435 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 10:04:42.021   328   972 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-24 10:04:42.031   328   961 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6812)
08-24 10:04:42.031   328   961 I WVCdm   : CdmEngine::CloseSession
08-24 10:04:42.031   328   961 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-24 10:04:42.031   328   961 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-24 10:04:42.031   328   961 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-24 10:04:42.031   328   961 D DrmWidevineDash: Service_Uninitialize: starts!
08-24 10:04:42.031   328   961 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-24 10:04:42.031   328   961 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-24 10:04:42.031   328   961 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-24 10:04:42.031   328   961 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-24 10:04:42.031  1959  2667 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-24 10:04:42.071  6812  6822 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6812, getuid(): 10011
,08-24 10:04:42.121   749  1500 V AlarmManager:  remove PendingIntent] PendingIntent{a2d8344: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:42.221  6812  6822 I qtaguid : Untagging socket 21
,08-24 10:04:42.261  6812  6822 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 10:04:42.261  6812  6822 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 10:04:42.321  1959  6841 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 10:04:42.321  1959  6838 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 10:04:42.331  1959  6841 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 10:04:42.331  1959  6838 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 10:04:42.351  1959  6841 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 10:04:42.351  1959  6838 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-24 10:04:42.351  1959  6838 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-24 10:04:42.361  1959  6838 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 10:04:42.431   749  1500 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:42.461  1959  6838 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-24 10:04:42.501  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:42.501  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:42.501   316  1188 D EnterpriseController: netId is 0
08-24 10:04:42.501   316  1188 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 10:04:42.511  1959  6838 I qtaguid : Tagging socket 59 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:42.551  1959  6838 I qtaguid : Tagging socket 62 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:42.721   749  1220 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:42.731  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:42.731  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:42.731  1959  6838 I qtaguid : Tagging socket 59 with tag 11065c0800000000{285629448,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:42.811  6849  6849 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-24 10:04:42.821   749  2142 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:42.831  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:42.831  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:42.831  1959  6838 I qtaguid : Tagging socket 59 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:42.931   749  1590 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:42.951  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:42.951  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:42.951  1959  6838 I qtaguid : Tagging socket 59 with tag 11065fff00000000{285630463,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:42.951  6849  6849 I dex2oat : ----------------------------------------------------
08-24 10:04:42.951  6849  6849 I dex2oat : <SS>: S T A R T I N G . . .
08-24 10:04:42.951  6849  6849 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-24 10:04:42.951  6849  6849 I dex2oat : dex2oat took 144.445ms (threads: 4) arena alloc=209KB java alloc=63KB native alloc=1800KB free=1783KB
,08-24 10:04:42.961  6812  6822 W System  : ClassLoader referenced unknown path: 
,08-24 10:04:42.961  6812  6822 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-24 10:04:42.971  6812  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 10:04:42.971  6812  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 10:04:42.971  6812  6822 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 10:04:42.971  6812  6822 I Adreno-EGL: Local Branch: ss
08-24 10:04:42.971  6812  6822 I Adreno-EGL: Remote Branch: 
08-24 10:04:42.971  6812  6822 I Adreno-EGL: Local Patches: 
08-24 10:04:42.971  6812  6822 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:04:42.971  6812  6822 D libEGL  : eglInitialize EGLDisplay = 0xb300d264
,08-24 10:04:43.031  6812  6822 D libEGL  : eglTerminate EGLDisplay = 0xb300d2bc
,08-24 10:04:43.031  6812  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 10:04:43.031  6812  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 10:04:43.031  6812  6822 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 10:04:43.031  6812  6822 I Adreno-EGL: Local Branch: ss
08-24 10:04:43.031  6812  6822 I Adreno-EGL: Remote Branch: 
08-24 10:04:43.031  6812  6822 I Adreno-EGL: Local Patches: 
08-24 10:04:43.031  6812  6822 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:04:43.031  6812  6822 D libEGL  : eglInitialize EGLDisplay = 0xb300d264
,08-24 10:04:43.051   749  2218 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:43.071  6812  6822 D libEGL  : eglTerminate EGLDisplay = 0xb300d2bc
,08-24 10:04:43.091  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.091  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.091   316  1188 D EnterpriseController: netId is 0
08-24 10:04:43.091   316  1188 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 10:04:43.091  1959  6838 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.111  6812  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 10:04:43.111  6812  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 10:04:43.111  6812  6822 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 10:04:43.111  6812  6822 I Adreno-EGL: Local Branch: ss
08-24 10:04:43.111  6812  6822 I Adreno-EGL: Remote Branch: 
08-24 10:04:43.111  6812  6822 I Adreno-EGL: Local Patches: 
08-24 10:04:43.111  6812  6822 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:04:43.111  6812  6822 D libEGL  : eglInitialize EGLDisplay = 0xb300d264
,08-24 10:04:43.121  1959  6838 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.151  6812  6822 D libEGL  : eglTerminate EGLDisplay = 0xb300d2bc
,08-24 10:04:43.171  1959  6808 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.171  1959  6808 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.171  1959  6808 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.211  1959  6808 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.311  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.321  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.321  1959  6838 I qtaguid : Tagging socket 59 with tag 1106525900000000{285626969,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:43.341  1959  2667 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 10:04:43.351  1959  2667 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-24 10:04:43.351   749   764 V AlarmManager:  remove PendingIntent] PendingIntent{f5b416b: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:43.361  1959  6858 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.361  1959  2667 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-24 10:04:42.103+0200, stopTime=2016-08-24 10:04:43.368+0200, duration=1265ms
,08-24 10:04:43.361  1959  6858 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.361   316  1188 D EnterpriseController: netId is 0
08-24 10:04:43.361   316  1188 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 10:04:43.361  1959  6858 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.391  1959  6858 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:43.421   749  2143 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:43.441  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.441  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.441  1959  6838 I qtaguid : Tagging socket 59 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:43.541   749   764 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:43.551  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.551  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.551  1959  6838 I qtaguid : Tagging socket 59 with tag 11065b5800000000{285629272,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:43.611  1959  6858 I qtaguid : Untagging socket 71
,08-24 10:04:43.611  1959  2667 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-24 10:04:43.651   749  1591 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 10:04:43.651  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:43.651  1959  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 10:04:43.651  1959  6838 I qtaguid : Tagging socket 59 with tag 11065c9100000000{285629585,0} uid -1, pid: 1959, getuid(): 10011
,08-24 10:04:43.751   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{15a4961: PendingIntentRecord{812ba80 com.google.android.gms broadcastIntent}}
,08-24 10:04:45.571  1959  6859 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:45.571  1959  6859 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 10:04:45.571  1959  6859 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} uid 10011, pid: 1959, getuid(): 10011
,08-24 10:04:45.811  1959  6859 I qtaguid : Untagging socket 71
,08-24 10:04:45.861  1959  2667 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-24 10:04:47.231   749  3460 D SSRM:n  : SIOP:: AP = 410, PST = 442, CUR = 300, LCD = 0
,08-24 10:04:47.271   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 10:04:50.961   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 10:04:50.971   749  1500 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:04:50.971   749  1500 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:04:50.981   749  1500 D BatteryService: stay LED for charging
,08-24 10:04:50.981   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:04:51.001   749   749 I MotionRecognitionService: Plugged
,08-24 10:04:51.001   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:04:51.001   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:04:51.011   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:04:51.021  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:04:51.021  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:04:51.021  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:04:51.041  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:04:51.041  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:04:51.051  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:51.051  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:51.051  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:04:57.331   749  3460 D SSRM:n  : SIOP:: AP = 380, PST = 433, CUR = 300, LCD = 0
,08-24 10:04:58.851   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:04:58.881   749  1594 E Watchdog: !@Sync 4 [08-24 10:04:58.891]
,08-24 10:04:59.681  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:04:59.981   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:05:01.041   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:01.041   749  2209 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:05:01.051   749  2209 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:05:01.051   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:01.061   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:01.061   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:01.071   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:01.081   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:01.081  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:01.081  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:01.081  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:01.081   749  2209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 42ms
,08-24 10:05:01.081   749  2209 D BatteryService: stay LED for charging
,08-24 10:05:01.101  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:01.101  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:01.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:01.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:01.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:07.391   749  3460 D SSRM:n  : SIOP:: AP = 350, PST = 425, CUR = 300, LCD = 0
,08-24 10:05:07.401   749  3460 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-24 10:05:07.491  6881  6881 E Zygote  : v2
,08-24 10:05:07.491  6881  6881 I libpersona: KNOX_SDCARD checking this for 10053
08-24 10:05:07.491  6881  6881 I libpersona: KNOX_SDCARD not a persona
,08-24 10:05:07.501  6881  6881 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:05:07.501  6881  6881 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:05:07.501  6881  6881 E Zygote  : accessInfo : 0
,08-24 10:05:07.511   749   806 I ActivityManager: Start proc 6881:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-24 10:05:07.511   749  1325 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-24 10:05:07.521   749  3460 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 10:05:07.521  6881  6881 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-24 10:05:07.521  2782  2782 D ContentApp:  LEVEL : 0
,08-24 10:05:07.591  6881  6881 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:05:07.591  6881  6881 D ActivityThread: Added TimaKeyStore provider
,08-24 10:05:07.621   749  1500 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{36a8947 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1a4574 6881:com.sec.android.app.videoplayer/u0a53}
,08-24 10:05:07.621   749  1325 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-24 10:05:07.631  6881  6881 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-24 10:05:07.671  6881  6881 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-24 10:05:07.701  6881  6881 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-24 10:05:07.731  6881  6881 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-24 10:05:07.731  6881  6881 D videowall-Global: core_num = 4
,08-24 10:05:07.761  6881  6881 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,08-24 10:05:07.761  6881  6881 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-24 10:05:07.801  6881  6881 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-24 10:05:07.801   749  2142 I ActivityManager: Killing 5970:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-24 10:05:07.841   749  1322 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-24 10:05:11.131   749  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:11.141   749  1592 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:05:11.141   749  1592 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:05:11.151   749  1592 D BatteryService: stay LED for charging
,08-24 10:05:11.151   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:11.161   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:11.161   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:11.171   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:11.171   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:11.181  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:11.181  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:11.181  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:11.211  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:11.211  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:11.211  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:11.221  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:11.221  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:17.581   749  3460 D SSRM:n  : SIOP:: AP = 340, PST = 417, CUR = 300, LCD = 0,
,08-24 10:05:18.851   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:05:21.201   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:21.211   749  2209 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:05:21.211   749  2209 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:05:21.221   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:21.231   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:21.231   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:21.231   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:21.241   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:21.241   749  2209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-24 10:05:21.251   749  2209 D BatteryService: stay LED for charging
,08-24 10:05:21.251  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:21.251  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:21.251  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:21.261  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:21.271  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:21.271  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:21.281  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:21.281  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:22.871   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:05:22.871   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:05:22.871   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:05:26.911  1959  3334 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 10:05:27.651   749  3460 D SSRM:n  : SIOP:: AP = 340, PST = 409, CUR = 300, LCD = 0
,08-24 10:05:27.651   749  3460 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-24 10:05:27.701   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e111a9d u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1a4574 6881:com.sec.android.app.videoplayer/u0a53}
,08-24 10:05:27.711  6881  6881 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-24 10:05:27.711  2782  2782 D ContentApp:  LEVEL : -1
,08-24 10:05:27.711  6881  6881 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-24 10:05:28.221  2796  5074 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 10:05:28.891   749  1594 E Watchdog: !@Sync 5 [08-24 10:05:28.899]
,08-24 10:05:29.201   749  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-24 10:05:29.211   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c999336 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e66ce5 6257:com.samsung.android.sm.provider/1000}
,08-24 10:05:29.271   749  3461 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.271   749  3461 W ResourcesManager: getTopLevelResources: /system/app/bootagent/bootagent.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.281   749  3461 W ResourcesManager: getTopLevelResources: /system/app/BluetoothTest/BluetoothTest.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.291   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.361   749  3461 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.371   749  3461 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.381   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.391   749  3461 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.411   749  3461 W ResourcesManager: getTopLevelResources: /system/app/EdmSimPinService/EdmSimPinService.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.411   749  3461 W ResourcesManager: getTopLevelResources: /system/app/AntHalService/AntHalService.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.421   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/CSC/CSC.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.421   749  3461 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.421   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.431   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/Telecom/Telecom.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.441   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartcardManager/SmartcardManager.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.451   749  3461 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.461   749  3461 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.461   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMediaProvider/SecMediaProvider.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.471   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/ContextProvider/ContextProvider.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.481   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in null rsrc of package null
,08-24 10:05:29.501   749  3461 W ResourcesManager: getTopLevelResources: /system/priv-app/UcsPinpad/UcsPinpad.apk / 1.0 running in null rsrc of package null
,08-24 10:05:31.291   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:31.291   749  1500 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4348, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 10:05:31.291   749  1500 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-24 10:05:31.291   749  1500 D BatteryService: stay LED for charging
08-24 10:05:31.291   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:31.291   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:31.301  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:31.301  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:05:31.301  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:31.301   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:31.301   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:31.301   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:31.301  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:31.311  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:31.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:31.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:31.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:32.611  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.631  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.631  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.651  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings/SecSettings.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.661  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.671  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera3/SamsungCamera3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.681  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.691  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.691  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.721  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.751  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.761  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.761  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.771  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Flipboard/Flipboard.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.801  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.821  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.831  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.841  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.851  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.861  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.891  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M_OS_UPG/SPlanner_M_OS_UPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.901  6257  6913 W ResourcesManager: getTopLevelResources: /data/app/com.android.vending-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.931  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.931  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.941  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.941  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideo/SecVideo.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.951  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.951  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.951  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote/VoiceNote.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:32.961  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.011  6257  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator2_LMUPG/SecCalculator2_LMUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.021  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.031  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.041  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.051  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.061  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/app-production-release-3.3.3-newSDK_23/app-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.071  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/SecMemoDL/SecMemoDL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.081  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.141  6257  6913 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_MUPG/ClockPackage_MUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.161  6257  6913 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.181  6257  6913 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:33.191  6257  6913 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,08-24 10:05:37.761   749  3460 D SSRM:n  : SIOP:: AP = 360, PST = 401, CUR = 300, LCD = 0
,08-24 10:05:38.861   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:05:41.381   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:41.381   749  2209 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:05:41.381   749  2209 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:05:41.391   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:41.401   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:41.401   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:41.411   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:41.411   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:41.411   749  2209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:05:41.421   749  2209 D BatteryService: stay LED for charging
,08-24 10:05:41.431  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:05:41.441  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:41.441  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:41.451  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:41.451  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:41.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:41.471  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:41.471  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:47.821   749  3460 D SSRM:n  : SIOP:: AP = 340, PST = 387, CUR = 300, LCD = 0
,08-24 10:05:51.451   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:05:51.461   749   764 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:05:51.461   749   764 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:05:51.461   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:05:51.481   749   749 I MotionRecognitionService: Plugged
,08-24 10:05:51.481   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:05:51.481   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:05:51.491   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:05:51.491   749   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:05:51.491   749   764 D BatteryService: stay LED for charging
,08-24 10:05:51.491  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:51.491  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:05:51.491  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:05:51.511  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:05:51.511  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:05:51.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:51.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:51.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 10:05:57.881   749  3460 D SSRM:n  : SIOP:: AP = 330, PST = 372, CUR = 300, LCD = 0
,08-24 10:05:58.861   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:05:58.891   749  1594 E Watchdog: !@Sync 6 [08-24 10:05:58.907]
,08-24 10:05:59.691  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:06:01.561   749  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:01.561   749  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:06:01.561   749  1220 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:06:01.571   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:06:01.581   749   749 I MotionRecognitionService: Plugged
,08-24 10:06:01.581   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:06:01.581   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:06:01.591   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:06:01.591   749  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:06:01.591   749  1220 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 749) 
,08-24 10:06:01.601   749  1220 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-24 10:06:01.611  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:01.611  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:01.611  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:06:01.611  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:06:01.631   749  1220 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-24 10:06:01.641   749  1220 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-24 10:06:01.651  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:06:01.651  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:06:01.661  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:01.661  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:01.661  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:01.671   749  1220 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-24 10:06:01.671   749  1220 D BatteryService: turn on LED for fully charged
,08-24 10:06:02.041   749  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-24 10:06:02.041   749   875 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-24 10:06:02.041   749   875 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-24 10:06:02.061   749   875 D SensorManager: unregisterListener ::   
,08-24 10:06:02.061   749   875 D lights  : led_pattern : 5 +
,08-24 10:06:02.081   749   875 D lights  : led_pattern : 5 -
,08-24 10:06:02.081   749   875 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-24 10:06:02.081   749   875 V AlarmManager:  remove PendingIntent] PendingIntent{2a71f87: PendingIntentRecord{62dbeb4 android broadcastIntent}}
,08-24 10:06:07.941   749  3460 D SSRM:n  : SIOP:: AP = 320, PST = 359, CUR = 300, LCD = 0
,08-24 10:06:11.621   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:11.631   749  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:06:11.631   749  1591 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:06:11.641   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:06:11.651   749   749 I MotionRecognitionService: Plugged
,08-24 10:06:11.651   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:06:11.661   749  1591 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-24 10:06:11.661   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:06:11.661   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:06:11.661   749  1591 D BatteryService: stay LED for fully charged
,08-24 10:06:11.681  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:11.681  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:11.691  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:06:11.701  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:06:11.701  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:06:11.711  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:11.711  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:11.711  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:18.001   749  3460 D SSRM:n  : SIOP:: AP = 320, PST = 349, CUR = 300, LCD = 0
,08-24 10:06:18.861   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:06:21.701   749  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:21.711   749  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:06:21.711   749  1322 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:06:21.711   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:06:21.731   749   749 I MotionRecognitionService: Plugged
,08-24 10:06:21.731   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:06:21.731   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:06:21.731   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:06:21.741   749  1322 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:06:21.741   749  1322 D BatteryService: stay LED for fully charged
,08-24 10:06:21.741  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:21.741  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:06:21.741  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:06:21.761  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:06:21.761  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:06:21.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:21.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:06:21.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:28.061   749  3460 D SSRM:n  : SIOP:: AP = 320, PST = 340, CUR = 300, LCD = 0
,08-24 10:06:28.901   749  1594 E Watchdog: !@Sync 7 [08-24 10:06:28.913]
,08-24 10:06:31.791   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:31.791   749  2218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0,
08-24 10:06:31.801   749  2218 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:06:31.801   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:06:31.811   749   749 I MotionRecognitionService: Plugged
,08-24 10:06:31.821   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:06:31.821   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:06:31.821   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:06:31.831   749  2218 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 10:06:31.831   749  2218 D BatteryService: stay LED for fully charged
,08-24 10:06:31.841  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:31.841  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:06:31.841  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:06:31.851  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:06:31.851  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:06:31.861  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:31.861  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:31.871  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:38.121   749  3460 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 300, LCD = 0
,08-24 10:06:38.871   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:06:41.871   749  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:48.181   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 330, CUR = 300, LCD = 0
,08-24 10:06:51.951   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:06:51.961   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:06:51.961   749  2126 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:06:51.961   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:06:51.981   749   749 I MotionRecognitionService: Plugged
,08-24 10:06:51.981   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:06:51.981   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:06:51.981   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:06:51.991   749  2126 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:06:51.991   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:06:51.991  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:06:51.991  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:06:51.991  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:06:52.011  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:06:52.011  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:06:52.021  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:52.021  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:06:52.021  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:06:58.251   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 327, CUR = 300, LCD = 0
,08-24 10:06:58.871   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:06:58.901   749  1594 E Watchdog: !@Sync 8 [08-24 10:06:58.917]
,08-24 10:06:59.711  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:07:00.001  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 8 size : 2Kb duration : 285ms lastUpdatedAfter : 172315ms
,08-24 10:07:02.041   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:02.041   749   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:07:02.041   749   764 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:07:02.051   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:07:02.061   749   749 I MotionRecognitionService: Plugged
,08-24 10:07:02.061   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:07:02.061   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:07:02.071   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:07:02.071   749   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:07:02.071   749   764 D BatteryService: stay LED for fully charged
,08-24 10:07:02.091  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:07:02.091  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:07:02.091  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:07:02.101  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:07:02.101  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:07:02.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:02.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:02.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:08.311   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 300, LCD = 0
,08-24 10:07:12.131   749  2201 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:18.361   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300, LCD = 0
,08-24 10:07:18.871   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:07:22.211   749  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:22.221   749  1593 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:07:22.221   749  1593 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:07:22.221   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:07:22.241   749   749 I MotionRecognitionService: Plugged
,08-24 10:07:22.241   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:07:22.241   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:07:22.241   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:07:22.251   749  1593 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:07:22.251   749  1593 D BatteryService: stay LED for fully charged
,08-24 10:07:22.261  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:07:22.261  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:07:22.261  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:07:22.291  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:07:22.291  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:07:22.291  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:22.291  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:07:22.291  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:27.521   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:07:27.521   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:07:27.521   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:07:28.421   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300, LCD = 0
,08-24 10:07:28.911   749  1594 E Watchdog: !@Sync 9 [08-24 10:07:28.920]
,08-24 10:07:32.301   749  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:38.481   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300, LCD = 0
,08-24 10:07:38.881   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:07:42.381   749  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:42.391   749  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:07:42.391   749  1590 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:07:42.391   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:07:42.411   749   749 I MotionRecognitionService: Plugged
,08-24 10:07:42.411   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:07:42.411   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:07:42.411   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:07:42.421   749  1590 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:07:42.421   749  1590 D BatteryService: stay LED for fully charged
,08-24 10:07:42.441  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:07:42.441  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:07:42.441  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:07:42.451  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:07:42.451  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:07:42.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-24 10:07:42.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:42.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:43.611   749  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 10:07:43.621   749  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 10:07:43.621   749  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 10:07:43.641   749  1231 I TLC_TIMA_PKM_initialize: initializing...
,08-24 10:07:43.641   749  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-24 10:07:43.641   749  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-24 10:07:43.641   749  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-24 10:07:43.651   749  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-24 10:07:43.651   749  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-24 10:07:43.651   749  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-24 10:07:43.651   749  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-24 10:07:43.661   749  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-24 10:07:43.661   749  1231 D QSEECOMAPI: : App is not loaded in QSEE
,08-24 10:07:43.671   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:07:43.671   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:07:43.671   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:07:43.721   749  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,08-24 10:07:43.721   749  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-24 10:07:43.731   749  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-24 10:07:46.981   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 10:07:46.991   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 10:07:47.001   749  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:07:47.001   749  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:07:48.541   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300, LCD = 0
,08-24 10:07:58.591   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300, LCD = 0
,08-24 10:07:58.881   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:07:58.911   749  1594 E Watchdog: !@Sync 10 [08-24 10:07:58.924]
,08-24 10:07:59.681   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:07:59.751   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:07:59.761   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:07:59.761   749  2126 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-24 10:07:59.761   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:07:59.771   749  1238 I ActivityManager: Start proc 6945:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-24 10:07:59.781  6945  6945 E Zygote  : v2
,08-24 10:07:59.781  6945  6945 I libpersona: KNOX_SDCARD checking this for 1000
,08-24 10:07:59.781  6945  6945 I libpersona: KNOX_SDCARD not a persona
,08-24 10:07:59.781  6945  6945 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:07:59.781  6945  6945 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:07:59.791  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 10:07:59.791  1384  1384 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 10:07:59.791  1384  1384 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:07:59.791  6945  6945 E Zygote  : accessInfo : 0
,08-24 10:07:59.821  1384  1384 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 10:07:59.831  1555  1555 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-24 10:07:59.831  1555  1555 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-24 10:07:59.841  1555  1555 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 10:07:59.851  1384  1384 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 10:07:59.861   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:07:59.861  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.881   749   749 I MotionRecognitionService: Plugged
08-24 10:07:59.881   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:07:59.881   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 10:07:59.881   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:07:59.881  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.881  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 10:07:59.881  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:07:59.891  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.891  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.891  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.891  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-24 10:07:59.891  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.901  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:07:59.901  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:07:59.901  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:07:59.901  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:07:59.901  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:07:59.901  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:07:59.911  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:07:59.911  6945  6945 D ActivityThread: Added TimaKeyStore provider
,08-24 10:07:59.931  6945  6945 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-24 10:07:59.951  6945  6945 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-24 10:07:59.961  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:07:59.981   749   764 I ActivityManager: Killing 5993:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-24 10:08:00.021   749  1592 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-24 10:08:00.101  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:08:00.701   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:08:02.861   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:08:02.861   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:08:02.861   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:08:03.591  1555  1555 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
,08-24 10:08:03.601   316  1185 D Netd    : Iface wlan0 link up
,08-24 10:08:03.611  1555  1555 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-24 10:08:03.621   749   810 D Tethering: interfaceLinkStateChanged wlan0, true
,08-24 10:08:03.621   749   810 D Tethering: interfaceStatusChanged wlan0, true
,08-24 10:08:03.641   749  1326 D WifiP2pService: InactiveState{ what=147461 }
,08-24 10:08:03.641   749  1326 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-24 10:08:03.651   749  1326 D WifiP2pService: DefaultState{ what=147461 }
,08-24 10:08:03.701   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8eea610 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4e77895 1384:com.android.systemui/u0a58}
,08-24 10:08:08.651   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300, LCD = 0
,08-24 10:08:09.851   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:08:18.711   749  3460 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-24 10:08:18.891   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:08:19.941   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:08:28.771   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300, LCD = 0
,08-24 10:08:28.911   749  1594 E Watchdog: !@Sync 11 [08-24 10:08:28.929]
,08-24 10:08:30.021   749  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:08:30.031   749  1593 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:08:30.031   749  1593 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:08:30.031   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:08:30.051   749   749 I MotionRecognitionService: Plugged
,08-24 10:08:30.051   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:08:30.051   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:08:30.051   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:08:30.061   749  1593 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:08:30.061   749  1593 D BatteryService: stay LED for fully charged
,08-24 10:08:30.081  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:08:30.081  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:08:30.081  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:08:30.101  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:08:30.101  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:08:30.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:08:30.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:08:30.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:08:35.611  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 10:08:35.611  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(732): No file ready to send
,08-24 10:08:38.831   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,08-24 10:08:38.891   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:08:40.111   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:08:48.891   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300, LCD = 0
,08-24 10:08:50.201   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:08:58.891   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:08:58.921   749  1594 E Watchdog: !@Sync 12 [08-24 10:08:58.934]
,08-24 10:08:58.951   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,08-24 10:09:00.121  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:09:00.281   749  2142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:01.311   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:09:01.311   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:09:01.311   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:09:09.011   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,08-24 10:09:10.371   749  2143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:10.371   749  2143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:09:10.371   749  2143 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:09:10.381   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:09:10.391   749   749 I MotionRecognitionService: Plugged
,08-24 10:09:10.391   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:09:10.391   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:09:10.401   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:09:10.401   749  2143 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:09:10.401   749  2143 D BatteryService: stay LED for fully charged
,08-24 10:09:10.421  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:10.421  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:10.421  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:09:10.441  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:09:10.441  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:09:10.451  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:10.451  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:09:10.451  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:11.231   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:09:11.231   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:09:11.231   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:09:18.901   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:09:19.071   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,08-24 10:09:20.451   749  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:20.461   749  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:09:20.461   749  1322 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:09:20.461   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:09:20.481   749   749 I MotionRecognitionService: Plugged
,08-24 10:09:20.481   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:09:20.481   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:09:20.481   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:09:20.491   749  1322 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:09:20.491   749  1322 D BatteryService: stay LED for fully charged
,08-24 10:09:20.491  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:20.491  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:09:20.491  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:09:20.511  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:09:20.511  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:09:20.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:20.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:20.521  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:26.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:09:26.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:09:26.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:09:28.921   749  1594 E Watchdog: !@Sync 13 [08-24 10:09:28.938]
,08-24 10:09:29.131   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,08-24 10:09:30.541   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:30.541   749   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:09:30.541   749   764 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:09:30.551   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:09:30.561   749   749 I MotionRecognitionService: Plugged
,08-24 10:09:30.561   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:09:30.561   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:09:30.571   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:09:30.571   749   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:09:30.571   749   764 D BatteryService: stay LED for fully charged
,08-24 10:09:30.591  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:30.591  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:09:30.591  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:09:30.601  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:09:30.601  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:09:30.611  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:30.611  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:09:30.611  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:38.901   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:09:39.191   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,08-24 10:09:40.621   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:40.621   749  2218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:09:40.621   749  2218 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:09:40.631   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:09:40.641   749   749 I MotionRecognitionService: Plugged
,08-24 10:09:40.641   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:09:40.641   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:09:40.651   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:09:40.651   749  2218 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:09:40.651   749  2218 D BatteryService: stay LED for fully charged
,08-24 10:09:40.661  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:40.661  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:40.661  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:09:40.691  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:09:40.691  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:09:40.691  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:40.701  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:09:40.701  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:42.221   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:09:42.221   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:09:42.221   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:09:49.251   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-24 10:09:50.701   749  2201 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:09:50.711   749  2201 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:09:50.711   749  2201 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:09:50.711   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:09:50.731   749   749 I MotionRecognitionService: Plugged
,08-24 10:09:50.731   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:09:50.731   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:09:50.731   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:09:50.741   749  2201 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:09:50.741   749  2201 D BatteryService: stay LED for fully charged
,08-24 10:09:50.741  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:09:50.741  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:09:50.741  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:09:50.761  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:09:50.761  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:09:50.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:50.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:50.771  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:09:58.911   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:09:58.931   749  1594 E Watchdog: !@Sync 14 [08-24 10:09:58.944]
,08-24 10:09:59.311   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:00.211  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:10:00.451  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 216ms lastUpdatedAfter : 180450ms
,08-24 10:10:00.781   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:10:00.791   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:10:00.791   749  2126 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:10:00.791   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:10:00.811   749   749 I MotionRecognitionService: Plugged
,08-24 10:10:00.811   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:10:00.811   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:10:00.821   749  2126 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 10:10:00.821   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:10:00.821   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:10:00.841  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:10:00.841  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:10:00.841  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:10:00.851  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:10:00.851  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:10:00.861  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:00.861  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:00.861  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:00.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:10:00.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:10:00.911   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:10:09.361   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:10.891   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:10:10.901   749   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:10:10.901   749   764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:10:10.901   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:10:10.911   749   749 I MotionRecognitionService: Plugged
,08-24 10:10:10.921   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:10:10.921   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:10:10.921   749   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 10:10:10.921   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:10:10.931   749   764 D BatteryService: stay LED for fully charged
,08-24 10:10:10.941  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:10:10.941  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:10:10.941  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:10:10.951  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:10:10.951  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:10:10.961  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:10.961  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:10:10.961  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:18.911   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:10:19.421   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:28.931   749  1594 E Watchdog: !@Sync 15 [08-24 10:10:28.948]
,08-24 10:10:29.471   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:33.551   369   369 I bootchecker: bootchecker wake up!!
,08-24 10:10:38.911   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:10:39.531   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:40.961   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:10:40.971   749  2209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:10:40.971   749  2209 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:10:40.971   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:10:40.981   749   749 I MotionRecognitionService: Plugged
,08-24 10:10:40.991   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:10:40.991   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:10:40.991   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:10:40.991   749  2209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:10:41.001   749  2209 D BatteryService: stay LED for fully charged
,08-24 10:10:41.011  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:10:41.011  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:10:41.011  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:10:41.041  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:10:41.041  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:10:41.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:41.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:10:41.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:10:49.581   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:10:58.921   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:10:58.941   749  1594 E Watchdog: !@Sync 16 [08-24 10:10:58.954]
,08-24 10:10:59.631   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:00.451  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:11:00.701   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:11:00.701   749  1238 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=512622 batch.start=514800
,08-24 10:11:00.721  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 10:11:00.721  1384  1384 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 10:11:00.721  1384  1384 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:11:00.751  1384  1384 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 10:11:00.761  1384  1384 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 10:11:00.791  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.811  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:00.881  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:11:02.881   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:11:02.941   749   803 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-24 10:11:02.941   749   803 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-24 10:11:03.371   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{8142b7d: PendingIntentRecord{ab38b1 com.google.android.apps.plus broadcastIntent}}
,08-24 10:11:03.381   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{584ca72: PendingIntentRecord{5651ec3 com.google.android.apps.plus broadcastIntent}}
,08-24 10:11:09.701   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:11.031   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:11:11.041   749  1500 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:11:11.041   749  1500 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:11:11.041   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:11:11.051   749   749 I MotionRecognitionService: Plugged
,08-24 10:11:11.061   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:11:11.061   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:11:11.061   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:11:11.071   749  1500 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:11:11.071   749  1500 D BatteryService: stay LED for fully charged
,08-24 10:11:11.081  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:11:11.081  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:11:11.081  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:11:11.111  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:11:11.111  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:11:11.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:11.111  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:11.121  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:18.921   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:11:19.751   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:28.941   749  1594 E Watchdog: !@Sync 17 [08-24 10:11:28.958]
,08-24 10:11:29.811   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:38.931   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:11:39.861   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:41.101   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:11:41.111   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:11:41.111   749  2126 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:11:41.111   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:11:41.131   749   749 I MotionRecognitionService: Plugged
,08-24 10:11:41.131   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:11:41.131   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:11:41.131   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:11:41.141   749  2126 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:11:41.141   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:11:41.161  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:11:41.161  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:11:41.161  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:11:41.171  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:11:41.171  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:11:41.181  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:41.181  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:41.181  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:11:49.921   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:58.931   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:11:58.951   749  1594 E Watchdog: !@Sync 18 [08-24 10:11:58.965]
,08-24 10:11:59.981   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:11:59.981   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:12:00.491  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:12:10.031   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:12:11.171   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:12:11.181   749  2209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:12:11.181   749  2209 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:12:11.191   749  2209 D BatteryService: stay LED for fully charged
,08-24 10:12:11.191   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:12:11.211  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:12:11.211  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:12:11.211  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:12:11.211   749   749 I MotionRecognitionService: Plugged
,08-24 10:12:11.221   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:12:11.221   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 10:12:11.221   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:12:11.231  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:12:11.231  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:12:11.241  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:11.241  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:11.241  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:18.931   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:12:20.091   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:12:22.321   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:12:22.321   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:12:22.321   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:12:28.961   749  1594 E Watchdog: !@Sync 19 [08-24 10:12:28.972]
,08-24 10:12:30.141   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:12:37.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:12:37.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:12:37.351   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:12:38.941   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:12:40.201   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:12:41.241   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:12:41.241   749  1500 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:12:41.251   749  1500 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:12:41.251   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:12:41.261   749   749 I MotionRecognitionService: Plugged
,08-24 10:12:41.271   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:12:41.271   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:12:41.271   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:12:41.281   749  1500 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-24 10:12:41.281   749  1500 D BatteryService: stay LED for fully charged
,08-24 10:12:41.301  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:12:41.301  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:12:41.301  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:12:41.321  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:12:41.321  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:12:41.331  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:41.331  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:41.331  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:12:43.601   749  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 10:12:43.611   749  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 10:12:43.611   749  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 10:12:45.071   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 10:12:45.071   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 10:12:45.081   749  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:12:45.091   749  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:12:50.251   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:12:58.941   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:12:58.961   749  1594 E Watchdog: !@Sync 20 [08-24 10:12:58.977]
,08-24 10:13:00.361   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:00.511   749   759 I art     : Background sticky concurrent mark sweep GC freed 117257(9MB) AllocSpace objects, 282(5MB) LOS objects, 26% free, 42MB/58MB, paused 2.921ms total 207.550ms
,08-24 10:13:00.621  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:13:00.801  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 164ms lastUpdatedAfter : 180350ms
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.111   749   803 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.121   749   803 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.131   749   803 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 10:13:02.141   749   803 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 10:13:02.381   749   860 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,08-24 10:13:02.391   749   860 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,08-24 10:13:10.431   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:11.311   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:13:11.321   749  2218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:13:11.321   749  2218 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:13:11.321   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:13:11.331   749   749 I MotionRecognitionService: Plugged
,08-24 10:13:11.341   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:13:11.341   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:13:11.351   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:13:11.351   749  2218 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 10:13:11.351   749  2218 D BatteryService: stay LED for fully charged
,08-24 10:13:11.361  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:13:11.361  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:13:11.361  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:13:11.371  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:13:11.381  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:13:11.381  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:11.391  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:11.391  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:18.951   749  3490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 10:13:20.531   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:28.971   749  1594 E Watchdog: !@Sync 21 [08-24 10:13:28.981]
,08-24 10:13:30.591   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:40.671   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:41.381   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:13:41.381   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:13:41.381   749  2126 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:13:41.391   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:13:41.401   749   749 I MotionRecognitionService: Plugged
,08-24 10:13:41.401   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:13:41.401   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:13:41.411   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:13:41.411   749  2126 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:13:41.411   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:13:41.421  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:13:41.431  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:13:41.431  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:13:41.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:41.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:41.461  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:13:41.471  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:13:41.471  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:13:46.851   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:13:50.721   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:13:58.971   749  1594 E Watchdog: !@Sync 22 [08-24 10:13:58.986]
,08-24 10:14:00.781   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:14:00.881  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:14:10.831   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-24 10:14:11.451   749  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:14:20.891   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,08-24 10:14:28.981   749  1594 E Watchdog: !@Sync 23 [08-24 10:14:28.990]
,08-24 10:14:30.951   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,08-24 10:14:41.011   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,08-24 10:14:41.521   749  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:14:41.521   749  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:14:41.531   749  1322 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:14:41.531   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:14:41.541   749   749 I MotionRecognitionService: Plugged
,08-24 10:14:41.541   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:14:41.551   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:14:41.551   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:14:41.551   749  1322 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 10:14:41.561   749  1322 D BatteryService: stay LED for fully charged
,08-24 10:14:41.561  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:14:41.561  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:14:41.561  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:14:41.571  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:14:41.581  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:14:41.591  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:14:41.591  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:14:41.591  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:14:51.071   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,08-24 10:14:58.981   749  1594 E Watchdog: !@Sync 24 [08-24 10:14:58.997]
,08-24 10:15:00.981  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:15:01.131   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,08-24 10:15:11.191   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,08-24 10:15:11.591   749  2143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:15:11.591   749  2143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:15:11.601   749  2143 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:15:11.601   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:15:11.611   749   749 I MotionRecognitionService: Plugged
,08-24 10:15:11.611   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:15:11.621   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:15:11.621   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:15:11.631   749  2143 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-24 10:15:11.631   749  2143 D BatteryService: stay LED for fully charged
,08-24 10:15:11.641  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:15:11.651  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:15:11.651  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:15:11.671  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:15:11.671  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:15:11.681  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:15:11.681  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:15:11.681  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:15:21.251   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:15:28.991   749  1594 E Watchdog: !@Sync 25 [08-24 10:15:29.003]
,08-24 10:15:31.311   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-24 10:15:41.371   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:15:41.661   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:15:51.431   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:15:58.991   749  1594 E Watchdog: !@Sync 26 [08-24 10:15:59.008]
,08-24 10:16:01.071  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:16:01.271  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 181ms lastUpdatedAfter : 180472ms
,08-24 10:16:01.521   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:16:02.091   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:16:02.461   749  2213 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-24 10:16:02.461   749  2213 V MARsPolicyManager: updateSMDBValues
,08-24 10:16:02.471   749   857 E MARsDBManager: updateDBAll : begin --size 1
,08-24 10:16:02.501   749   857 I ActivityManager: Killing 2035:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 780s, lastActivityTime 711s
,08-24 10:16:02.511   749   857 I ActivityManager: Killing 6367:com.samsung.android.sdk.samsunglink/u0a41 (adj 5): SSR - service for lastStateTime 715s, lastActivityTime 715s
,08-24 10:16:02.511   749   857 I ActivityManager: Killing 3822:com.sec.spp.push/u0a37 (adj 5): SSR - service for lastStateTime 766s, lastActivityTime 732s
,08-24 10:16:02.521   749   857 I ActivityManager: Killing 1517:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 733s, lastActivityTime 733s
,08-24 10:16:02.521   749   857 I ActivityManager: Killing 4662:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 761s, lastActivityTime 761s
,08-24 10:16:02.531   749   857 I ActivityManager: Killing 3893:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 766s, lastActivityTime 766s
,08-24 10:16:02.571   749   857 E MARsDBManager: updateDBAll : end
,08-24 10:16:02.571   749   857 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-24 10:16:02.621   294   294 I ServiceManager: service 'AtCmdFwd' died
,08-24 10:16:02.621   378  4855 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-24 10:16:02.621   378  4855 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 10:16:02.631   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-24 10:16:02.631   749  1500 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
,08-24 10:16:02.631   749  1500 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-24 10:16:02.671   749  1590 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
08-24 10:16:02.671   749  1590 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,08-24 10:16:02.681   749  2218 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-24 10:16:02.681   749  2218 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-24 10:16:02.681   749  2218 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10945ms
,08-24 10:16:02.691  5839  5839 D HealthConsole: Service for HealthDataStore is disconnected
,08-24 10:16:02.691   749  1220 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,08-24 10:16:02.691   749  1220 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-24 10:16:02.691   749  1220 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20934ms
,08-24 10:16:02.701   749  2126 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-24 10:16:02.701   749  2126 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-24 10:16:02.701   749  2126 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 30927ms
08-24 10:16:02.701   749  2126 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-24 10:16:02.701   749  2126 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 40927ms
,08-24 10:16:02.711   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
08-24 10:16:02.711   749  1500 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,08-24 10:16:02.741   749  1322 I ActivityManager: Start proc 7062:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,08-24 10:16:02.751  7062  7062 E Zygote  : v2
,08-24 10:16:02.751  7062  7062 I libpersona: KNOX_SDCARD checking this for 10034
08-24 10:16:02.751  7062  7062 I libpersona: KNOX_SDCARD not a persona
,08-24 10:16:02.751  7062  7062 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:16:02.751  7062  7062 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:16:02.761  7062  7062 E Zygote  : accessInfo : 0
,08-24 10:16:02.761  7062  7062 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,08-24 10:16:02.821  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:16:02.821  7062  7062 D ActivityThread: Added TimaKeyStore provider
,08-24 10:16:02.841  7062  7062 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-24 10:16:02.861  7062  7062 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-24 10:16:02.871  7062  7062 I MultiDex: VM with version 2.1.0 has multidex support
,08-24 10:16:02.871  7062  7062 I MultiDex: install
08-24 10:16:02.871  7062  7062 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 10:16:02.871  7062  7062 I MultiDex: install
08-24 10:16:02.871  7062  7062 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 10:16:03.061   749   764 I ActivityManager: Start proc 7083:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,08-24 10:16:03.071  7083  7083 E Zygote  : v2
,08-24 10:16:03.071  7083  7083 I libpersona: KNOX_SDCARD checking this for 10016
08-24 10:16:03.071  7083  7083 I libpersona: KNOX_SDCARD not a persona
,08-24 10:16:03.081  7083  7083 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:16:03.081  7083  7083 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:16:03.091  7083  7083 E Zygote  : accessInfo : 0
,08-24 10:16:03.091  7083  7083 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,08-24 10:16:03.181  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:16:03.181  7083  7083 D ActivityThread: Added TimaKeyStore provider
,08-24 10:16:03.211  7083  7083 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,08-24 10:16:03.261  7062  7062 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-24 10:16:03.261  7062  7062 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-24 10:16:03.291  1384  1384 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,08-24 10:16:03.301  1384  1384 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{e26f24c VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,08-24 10:16:03.301  1384  1384 D AdaptiveEventManager: M updateContainers()
08-24 10:16:03.301  1384  1384 D AdaptiveEventContainerSmall: C updatePedoContainer()
08-24 10:16:03.301  1384  1384 D AdaptiveEventContainerSmall: handlePedoUpdate()
,08-24 10:16:03.301   749  1591 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,08-24 10:16:03.301  1384  1384 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,08-24 10:16:03.311   749  2218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,08-24 10:16:03.311   749   764 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,08-24 10:16:03.321   749  1220 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,08-24 10:16:03.351  7062  7062 I Health.HealthService: HealthService: onCreate() start (7062)
,08-24 10:16:03.441  5839  5839 D HealthDataStore: Service for HealthDataStore is connected
,08-24 10:16:03.441  5839  5839 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-24 10:16:03.461   749  1591 I ActivityManager: Killing 6044:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-24 10:16:03.491  5839  5839 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-24 10:16:03.491  5839  5839 E HealthDataStore: disconnectService: Context instance is invalid
,08-24 10:16:03.561  7062  7062 D HealthDataStore: Service for HealthDataStore is connected
,08-24 10:16:03.561  7062  7062 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-24 10:16:03.561  7062  7062 D HealthConsole: Service for HealthDataConsole is connected
,08-24 10:16:03.571  7062  7062 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-24 10:16:03.571  7062  7062 E HealthDataStore: disconnectService: Context instance is invalid
,08-24 10:16:03.571   749  1500 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-24 10:16:03.621   378  4855 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 10:16:03.661  7115  7115 E Zygote  : v2
,08-24 10:16:03.661  7115  7115 I libpersona: KNOX_SDCARD checking this for 1000
08-24 10:16:03.661  7115  7115 I libpersona: KNOX_SDCARD not a persona
,08-24 10:16:03.671  7115  7115 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:16:03.671  7115  7115 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:16:03.671  7115  7115 E Zygote  : accessInfo : 0
,08-24 10:16:03.671   749   806 I ActivityManager: Start proc 7115:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-24 10:16:03.701  7115  7115 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 10:16:03.701  7115  7115 D ActivityThread: Added TimaKeyStore provider
,08-24 10:16:03.721  7115  7115 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-24 10:16:03.741  7115  7115 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-24 10:16:03.741  7115  7115 D AtFwdService: onCreate method
08-24 10:16:03.741  7115  7115 I AtFwdService: Instantiate AtCmdFwd Service
,08-24 10:16:03.751  7062  7100 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,08-24 10:16:03.751  7115  7127 D AtCkpdCmdHandler: De-queing command
,08-24 10:16:03.801  7062  7129 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,08-24 10:16:03.811  7083  7097 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-24 10:16:03.821   393   393 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7083
08-24 10:16:03.821   393   393 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,08-24 10:16:03.961  7083  7097 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,08-24 10:16:04.061  7062  7129 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,08-24 10:16:04.251  7062  7129 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-24 10:16:04.251  7062  7129 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-24 10:16:04.281   393   393 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,08-24 10:16:04.331  7083  7097 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,08-24 10:16:04.331  7083  7097 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,08-24 10:16:04.331  7083  7097 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,08-24 10:16:11.581   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 300, LCD = 0
,08-24 10:16:11.741   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:16:11.741   749   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:16:11.741   749   762 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:16:11.751   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:16:11.761   749   749 I MotionRecognitionService: Plugged
,08-24 10:16:11.761   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:16:11.771   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:16:11.771   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:16:11.771   749   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:16:11.781   749   762 D BatteryService: stay LED for fully charged
,08-24 10:16:11.791  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:16:11.791  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:16:11.801  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:16:11.811  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:16:11.811  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:16:11.821  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:16:11.821  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:16:11.821  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:16:13.701   749   806 I ActivityManager: Start proc 7151:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-24 10:16:13.711  7151  7151 E Zygote  : v2
,08-24 10:16:13.711  7151  7151 I libpersona: KNOX_SDCARD checking this for 10026
08-24 10:16:13.711  7151  7151 I libpersona: KNOX_SDCARD not a persona
,08-24 10:16:13.711  7151  7151 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 10:16:13.711  7151  7151 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:16:13.721  7151  7151 E Zygote  : accessInfo : 0
,08-24 10:16:13.721  7151  7151 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-24 10:16:13.761  7151  7151 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:16:13.761  7151  7151 D ActivityThread: Added TimaKeyStore provider
,08-24 10:16:13.791  7151  7151 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-24 10:16:13.801  7151  7151 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-24 10:16:13.821  7151  7151 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-24 10:16:13.821  7151  7151 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-24 10:16:21.661   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 292, CUR = 300, LCD = 0
,08-24 10:16:23.701   749   806 I ActivityManager: Start proc 7164:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
08-24 10:16:23.701   749  1325 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-24 10:16:23.701  7164  7164 E Zygote  : v2
,08-24 10:16:23.711  7164  7164 I libpersona: KNOX_SDCARD checking this for 10181
,08-24 10:16:23.711  7164  7164 I libpersona: KNOX_SDCARD not a persona
,08-24 10:16:23.711  7164  7164 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 10:16:23.711  7164  7164 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 10:16:23.721  7164  7164 E Zygote  : accessInfo : 0
,08-24 10:16:23.721  7164  7164 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,08-24 10:16:23.761  7164  7164 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 10:16:23.761  7164  7164 D ActivityThread: Added TimaKeyStore provider
,08-24 10:16:23.781   749  1325 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-24 10:16:23.801  7164  7164 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,08-24 10:16:23.821  7164  7164 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,08-24 10:16:23.841  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,08-24 10:16:23.851  7164  7164 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 10:16:23.861   749   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4667cc u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1628a15 7164:com.sec.android.daemonapp/u0a181}
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,08-24 10:16:23.861  7164  7164 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-24 10:16:23.881  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,08-24 10:16:23.891  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-24 10:16:23.901  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,08-24 10:16:23.911  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.911  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-24 10:16:23.911  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,08-24 10:16:23.911  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-24 10:16:23.911  7164  7164 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 10:16:23.921  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 10:16:23.921  7164  7164 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-24 10:16:23.921  7164  7164 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-24 10:16:23.921  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.921  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 10:16:23.931   749  2218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eeb291 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1628a15 7164:com.sec.android.daemonapp/u0a181}
,08-24 10:16:23.931  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.931  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-24 10:16:23.931  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 10:16:23.931  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 10:16:23.941  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 10:16:23.941  7164  7164 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-24 10:16:23.941  7164  7164 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 10:16:23.941  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.941  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 10:16:23.951   749  1322 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{73065f6 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1628a15 7164:com.sec.android.daemonapp/u0a181}
,08-24 10:16:23.951  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.951  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-24 10:16:23.951  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 10:16:23.961  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 10:16:23.961  7164  7164 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 10:16:23.961  7164  7164 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 10:16:23.961  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 10:16:23.961  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.971  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 10:16:23.971   749  1500 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f08df7 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1628a15 7164:com.sec.android.daemonapp/u0a181}
,08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 10:16:23.981  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 10:16:23.981  7164  7164 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 10:16:23.981  7164  7164 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 10:16:23.981  7164  7164 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-24 10:16:23.981  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 10:16:23.991  7164  7164 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 10:16:23.991  7164  7164 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 10:16:29.001   749  1594 E Watchdog: !@Sync 27 [08-24 10:16:29.013]
,08-24 10:16:31.721   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 293, CUR = 300, LCD = 0
,08-24 10:16:41.811   749  2143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:16:41.861   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:16:51.911   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:16:59.001   749  1594 E Watchdog: !@Sync 28 [08-24 10:16:59.018]
,08-24 10:17:01.361  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:17:01.971   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:11.881   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:17:12.031   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:22.081   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:29.011   749  1594 E Watchdog: !@Sync 29 [08-24 10:17:29.024]
,08-24 10:17:32.131   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:41.951   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:17:41.951   749  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:17:41.951   749  1591 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:17:41.961   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:17:41.971   749   749 I MotionRecognitionService: Plugged
,08-24 10:17:41.971   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:17:41.971   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:17:41.981   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:17:41.981   749  1591 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 10:17:41.981   749  1591 D BatteryService: stay LED for fully charged
,08-24 10:17:42.001  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:17:42.011  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:17:42.011  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:17:42.021  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:17:42.021  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:17:42.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:17:42.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:17:42.041  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:17:42.191   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:43.601   749  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 10:17:43.611   749  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 10:17:43.611   749  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 10:17:46.961   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 10:17:46.961   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 10:17:46.971   749  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:17:46.971   749  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:17:52.241   749  3460 D SSRM:n  : SIOP:: AP = 300, PST = 293, CUR = 300, LCD = 0
,08-24 10:17:59.011   749  1594 E Watchdog: !@Sync 30 [08-24 10:17:59.028]
,08-24 10:18:01.481  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:18:02.301   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-24 10:18:04.871   749  1238 V AlarmManager: Expired Alarm result :4
,08-24 10:18:04.941  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 10:18:04.941  1384  1384 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 10:18:04.941  1384  1384 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:18:04.961  1384  1384 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 10:18:04.971  1384  1384 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 10:18:04.981  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:04.981   749   806 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,08-24 10:18:04.981  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:04.991  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:04.991  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:04.991  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:04.991  1384  1384 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:05.001  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:05.011   749   749 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,08-24 10:18:05.021   749   749 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-24 10:18:05.021   749   749 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-24 10:18:05.041   749   749 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-24 10:18:05.051  2078  2299 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-24 10:18:05.051  2078  2299 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-24 10:18:05.051  2078  2299 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
08-24 10:18:05.051  2078  2299 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
08-24 10:18:05.051  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.061  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.061  2078  2398 D bt_upio : upio_start_stop_timer : timer_settime success
,08-24 10:18:05.061  2078  2398 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.071  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.071  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.071  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.071  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.071  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.071  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.071  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.071  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.071  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.071  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.071  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.081  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.081  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.081  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.081  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.081  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.081  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.081  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.091  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.091  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.091  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.101  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.101  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.101  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.101  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.101  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.101  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.101  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.101  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.101  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.101  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.101  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.101  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.101  2078  2398 D bt_vendor: op for 7
,08-24 10:18:05.101  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.101  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.111  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.111  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 10:18:05.111  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.111  2078  2398 D bt_vendor: op for 7
08-24 10:18:05.111  2078  2398 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 10:18:05.111  2078  2398 D bt_upio : BT_WAKE is asserted already
,08-24 10:18:05.121   749  1592 V AlarmManager:  remove PendingIntent] PendingIntent{28a3dce: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.131  1384  1384 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 10:18:05.131   749  1500 V AlarmManager:  remove PendingIntent] PendingIntent{f0544ef: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.141   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{195bfc: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.171   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{5bb2285: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.171   749  1592 V AlarmManager:  remove PendingIntent] PendingIntent{d1068da: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.181   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{28b410b: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.181   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{c9e3be8: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.191   749  1500 V AlarmManager:  remove PendingIntent] PendingIntent{3106201: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.191   749   764 V AlarmManager:  remove PendingIntent] PendingIntent{99c38a6: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.191   749  2126 V AlarmManager:  remove PendingIntent] PendingIntent{72ae2e7: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.201   749  1322 V AlarmManager:  remove PendingIntent] PendingIntent{40f2e94: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.201   749  2143 V AlarmManager:  remove PendingIntent] PendingIntent{5201d3d: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.211   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{1c33932: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.211   749  1591 V AlarmManager:  remove PendingIntent] PendingIntent{a38c683: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.221   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{2faa000: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.221   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{1765039: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.221   749  1220 V AlarmManager:  remove PendingIntent] PendingIntent{e7b67e: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.231   749  2218 V AlarmManager:  remove PendingIntent] PendingIntent{fb747df: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.231   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{e69bc2c: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.241   749  1592 V AlarmManager:  remove PendingIntent] PendingIntent{62b6f5: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.241   749  1593 V AlarmManager:  remove PendingIntent] PendingIntent{444bc8a: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.251   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{f7282fb: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.251   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{cc6f18: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.261   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{574cd71: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.261   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{fba1756: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.261   749  2126 V AlarmManager:  remove PendingIntent] PendingIntent{7dc53d7: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.261   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{9a564c4: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.271   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{3b7cfad: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.271   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{35852e2: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.271   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{2a85673: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.281   749  2126 V AlarmManager:  remove PendingIntent] PendingIntent{bf60930: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.281   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{9aeb9a9: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.281   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{dacbb2e: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.291   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{727e6cf: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.291   749  2209 V AlarmManager:  remove PendingIntent] PendingIntent{76a885c: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.291   749  2126 V AlarmManager:  remove PendingIntent] PendingIntent{1104765: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.301   749  2201 V AlarmManager:  remove PendingIntent] PendingIntent{6cd5c3a: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.301   749  2142 V AlarmManager:  remove PendingIntent] PendingIntent{66620eb: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.301   749  1590 V AlarmManager:  remove PendingIntent] PendingIntent{845ce48: PendingIntentRecord{19c22c9 com.android.bluetooth broadcastIntent}}
,08-24 10:18:05.391   749  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
08-24 10:18:05.391   749   875 D LightsService: [SvcLED]  onSensorChanged::light value = 0
08-24 10:18:05.391   749   875 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-24 10:18:05.401   749   875 D SensorManager: unregisterListener ::   
,08-24 10:18:05.401   749   875 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-24 10:18:05.401   749   875 V AlarmManager:  remove PendingIntent] PendingIntent{2a71f87: PendingIntentRecord{62dbeb4 android broadcastIntent}}
,08-24 10:18:05.861  2078  2676 D bt_upio : ..proc_btwrite_timeout..
,08-24 10:18:05.861  2078  2676 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-24 10:18:12.021   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:18:12.021   749  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:18:12.031   749  1591 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:18:12.031   749  1591 D BatteryService: stay LED for fully charged
,08-24 10:18:12.031   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:18:12.051  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:18:12.051  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:18:12.051  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:18:12.061   749   749 I MotionRecognitionService: Plugged
,08-24 10:18:12.061   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:18:12.061   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:18:12.061   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:18:12.071  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:18:12.071  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:18:12.071  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:18:12.071  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:18:12.081  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:18:12.351   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:18:22.411   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:18:29.021   749  1594 E Watchdog: !@Sync 31 [08-24 10:18:29.033]
,08-24 10:18:32.461   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:18:42.081   749  2142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:18:42.511   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:18:52.571   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:18:59.021   749  1594 E Watchdog: !@Sync 32 [08-24 10:18:59.038]
,08-24 10:18:59.981   749  1238 V AlarmManager: Expired Alarm result :8
,08-24 10:19:01.501  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:19:01.651  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 130ms lastUpdatedAfter : 180377ms
,08-24 10:19:02.631   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:19:11.331  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 10:19:11.331  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(732): No file ready to send
,08-24 10:19:12.151   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:19:12.681   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:19:22.731   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-24 10:19:29.031   749  1594 E Watchdog: !@Sync 33 [08-24 10:19:29.044]
,08-24 10:19:32.791   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:19:42.251   749  2201 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:19:42.251   749  2201 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:19:42.251   749  2201 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:19:42.251   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:19:42.261   749   749 I MotionRecognitionService: Plugged
,08-24 10:19:42.261   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:19:42.261   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:19:42.261   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:19:42.271   749  2201 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 20ms
,08-24 10:19:42.271   749  2201 D BatteryService: stay LED for fully charged
,08-24 10:19:42.281  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:19:42.281  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:19:42.291  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:19:42.311  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:19:42.311  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:19:42.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:19:42.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 10:19:42.321  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:19:42.851   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:19:52.901   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:19:59.031   749  1594 E Watchdog: !@Sync 34 [08-24 10:19:59.048]
,08-24 10:20:01.661  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:20:02.951   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:12.281   749  2142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:20:13.021   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:23.071   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:29.041   749  1594 E Watchdog: !@Sync 35 [08-24 10:20:29.054]
,08-24 10:20:33.121   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:42.251   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:20:42.251   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:20:42.251   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:20:42.351   749  2218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:20:42.351   749  2218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:20:42.351   749  2218 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-24 10:20:42.351   749  2218 D BatteryService: stay LED for fully charged
08-24 10:20:42.351   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:20:42.351   749   749 I MotionRecognitionService: Plugged
,08-24 10:20:42.351   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:20:42.351   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 10:20:42.351   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:20:42.361  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:20:42.361  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:20:42.361  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:20:42.371  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:20:42.371  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:20:42.381  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:20:42.381  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:20:42.381  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:20:43.171   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:53.231   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:20:57.271   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 10:20:57.271   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 10:20:57.271   316  1184 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 10:20:59.041   749  1594 E Watchdog: !@Sync 36 [08-24 10:20:59.059]
,08-24 10:21:01.761  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:21:03.281   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:12.421   749  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:21:13.331   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:23.381   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:29.051   749  1594 E Watchdog: !@Sync 37 [08-24 10:21:29.065]
,08-24 10:21:33.441   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:42.491   749  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:21:42.501   749  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:21:42.501   749  1322 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:21:42.501   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:21:42.511   749   749 I MotionRecognitionService: Plugged
,08-24 10:21:42.521   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:21:42.521   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:21:42.521   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:21:42.531   749  1322 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 10:21:42.531   749  1322 D BatteryService: stay LED for fully charged
,08-24 10:21:42.531  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:21:42.531  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:21:42.531  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:21:42.551  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:21:42.551  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:21:42.561  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:21:42.561  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:21:42.561  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:21:43.501   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:53.551   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:21:59.061   749  1594 E Watchdog: !@Sync 38 [08-24 10:21:59.069]
,08-24 10:22:01.791  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:22:01.991  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 181ms lastUpdatedAfter : 180335ms
,08-24 10:22:03.601   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:12.561   749  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:22:13.661   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:23.741   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:29.061   749  1594 E Watchdog: !@Sync 39 [08-24 10:22:29.074]
,08-24 10:22:33.791   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:42.621   749  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:22:42.631   749  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:22:42.631   749  1590 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:22:42.631   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:22:42.641   749   749 I MotionRecognitionService: Plugged
,08-24 10:22:42.651   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:22:42.651   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:22:42.651   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:22:42.661   749  1590 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:22:42.661   749  1590 D BatteryService: stay LED for fully charged
,08-24 10:22:42.681  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:22:42.681  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:22:42.681  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:22:42.691  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:22:42.691  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:22:42.701  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,08-24 10:22:42.701  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:22:42.701  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:22:43.601   749  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 10:22:43.611   749  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 10:22:43.611   749  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 10:22:43.861   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:45.071   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 10:22:45.071   749  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 10:22:45.081   749  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:22:45.091   749  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 10:22:53.911   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:22:55.641   749   803 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 10:22:59.071   749  1594 E Watchdog: !@Sync 40 [08-24 10:22:59.079]
,08-24 10:23:01.991  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:23:03.961   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:12.691   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:23:14.021   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:24.071   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:29.071   749  1594 E Watchdog: !@Sync 41 [08-24 10:23:29.086]
,08-24 10:23:34.131   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:42.761   749  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:23:42.761   749  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:23:42.761   749  1592 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:23:42.771   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:23:42.781   749   749 I MotionRecognitionService: Plugged
,08-24 10:23:42.781   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:23:42.791   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:23:42.791   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:23:42.791   749  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 10:23:42.801   749  1592 D BatteryService: stay LED for fully charged
,08-24 10:23:42.811  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:23:42.811  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:23:42.821  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:23:42.841  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:23:42.841  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:23:42.851  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:23:42.851  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:23:42.851  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:23:44.181   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:54.241   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:23:59.081   749  1594 E Watchdog: !@Sync 42 [08-24 10:23:59.093]
,08-24 10:24:02.031  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:24:04.291   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:11.381  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 10:24:11.381  5779  5815 I PlayCommon: [801] com.google.android.play.a.al.e(732): No file ready to send
,08-24 10:24:12.831   749  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:24:12.831   749  2209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:24:12.831   749  2209 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:24:12.841   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:24:12.851   749   749 I MotionRecognitionService: Plugged
,08-24 10:24:12.851   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:24:12.861   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:24:12.861   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:24:12.861   749  2209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:24:12.871   749  2209 D BatteryService: stay LED for fully charged
,08-24 10:24:12.881  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:24:12.881  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:24:12.881  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:24:12.891  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:24:12.891  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:24:12.901  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:24:12.901  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:24:12.911  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:24:14.341   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:24.401   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:29.081   749  1594 E Watchdog: !@Sync 43 [08-24 10:24:29.098]
,08-24 10:24:34.451   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:42.891   749  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:24:44.511   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:54.571   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:24:59.091   749  1594 E Watchdog: !@Sync 44 [08-24 10:24:59.105]
,08-24 10:25:02.071  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:25:02.281  1654  1713 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 190ms lastUpdatedAfter : 180293ms
,08-24 10:25:04.621   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:12.961   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:25:14.681   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:24.741   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:29.101   749  1594 E Watchdog: !@Sync 45 [08-24 10:25:29.110]
,08-24 10:25:34.801   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:34.911   749   759 I art     : Background sticky concurrent mark sweep GC freed 54922(7MB) AllocSpace objects, 378(7MB) LOS objects, 26% free, 42MB/58MB, paused 2.568ms total 111.921ms
,08-24 10:25:43.021   749  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:25:44.861   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:54.921   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:25:59.101   749  1594 E Watchdog: !@Sync 46 [08-24 10:25:59.115]
,08-24 10:26:02.371  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:26:04.971   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:13.091   749   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:26:13.101   749   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:26:13.101   749   764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:26:13.101   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:26:13.121   749   749 I MotionRecognitionService: Plugged
,08-24 10:26:13.121   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:26:13.121   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:26:13.131   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:26:13.131   749   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 10:26:13.131   749   764 D BatteryService: stay LED for fully charged
,08-24 10:26:13.131  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:26:13.131  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:26:13.131  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:26:13.151  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 10:26:13.151  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:26:13.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:13.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:13.161  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:15.031   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:25.121   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:29.111   749  1594 E Watchdog: !@Sync 47 [08-24 10:26:29.122]
,08-24 10:26:35.171   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:43.161   749  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:26:43.161   749  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:26:43.171   749  1591 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:26:43.171   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:26:43.181   749   749 I MotionRecognitionService: Plugged
,08-24 10:26:43.181   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:26:43.191   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:26:43.191   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:26:43.201   749  1591 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 10:26:43.201   749  1591 D BatteryService: stay LED for fully charged
,08-24 10:26:43.211  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:26:43.221  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:26:43.221  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:26:43.241  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:26:43.241  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:26:43.251  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:43.251  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:43.251  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:26:45.231   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:55.281   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:26:59.111   749  1594 E Watchdog: !@Sync 48 [08-24 10:26:59.126]
,08-24 10:27:02.401  1654  1713 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 10:27:05.341   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:27:13.221   749  2126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 10:27:13.231   749  2126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 10:27:13.231   749  2126 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-24 10:27:13.241   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 10:27:13.251   749   749 I MotionRecognitionService: Plugged
,08-24 10:27:13.251   749   749 D MotionRecognitionService:   cableConnection= 1
,08-24 10:27:13.251   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 10:27:13.261   749   749 D MotionRecognitionService: skip setTransmitPower. 
,08-24 10:27:13.261   749  2126 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 10:27:13.261   749  2126 D BatteryService: stay LED for fully charged
,08-24 10:27:13.281  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 10:27:13.281  1384  1384 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 10:27:13.281  1384  1384 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 10:27:13.291  2078  2078 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 10:27:13.291  2078  2682 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 10:27:13.301  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:27:13.301  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:27:13.301  1384  1384 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 10:27:15.401   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:27:25.491   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-24 10:27:29.121   749  1594 E Watchdog: !@Sync 49 [08-24 10:27:29.132]
,08-24 10:27:35.551   749  3460 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms)
```
