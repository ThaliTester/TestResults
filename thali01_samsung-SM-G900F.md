#### Test 82203060198550b_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-24 14:03:41.366  5383  5383 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-24 14:03:41.366  5383  5383 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-24 14:03:41.366  5383  5383 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-24 14:03:41.366  5383  5383 I art     : System.exit called, status: 0
08-24 14:03:41.366  5383  5383 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-24 14:03:41.406   776  1660 I ActivityManager: Process com.samsung.aasaservice (pid 5383)(adj 0) has died(123,715)
08-24 14:03:41.406   776  1660 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-24 14:03:41.406   776  1660 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-24 14:03:41.406   776  1660 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-24 14:03:41.406  5355  5355 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-24 14:03:41.426   776   861 I ActivityManager: Start proc 6275:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-24 14:03:41.426  6275  6275 E Zygote  : v2
08-24 14:03:41.426  6275  6275 I libpersona: KNOX_SDCARD checking this for 10014
08-24 14:03:41.426  6275  6275 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:41.426   776  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 14:03:41.426  6275  6275 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:41.426  6275  6275 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:41.426  6275  6275 E Zygote  : accessInfo : 0
08-24 14:03:41.436  6275  6275 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-24 14:03:41.486  6275  6275 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:41.486  6275  6275 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:41.496   776  1580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d417f15 6275:com.google.android.partnersetup/u0a14}
08-24 14:03:41.496   776  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-24 14:03:41.506  6275  6275 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-24 14:03:41.516  6275  6275 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-24 14:03:41.536   776  1660 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d417f15 6275:com.google.android.partnersetup/u0a14}
08-24 14:03:41.556   776  1728 I ActivityManager: Start proc 6294:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-24 14:03:41.556  6294  6294 E Zygote  : v2
08-24 14:03:41.556  6294  6294 I libpersona: KNOX_SDCARD checking this for 10015
08-24 14:03:41.556  6294  6294 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:41.556  6294  6294 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:41.556  6294  6294 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:41.556  6294  6294 E Zygote  : accessInfo : 0
08-24 14:03:41.556  6294  6294 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-24 14:03:41.576  6294  6294 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:41.576  6294  6294 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:41.586   776  1740 I ActivityManager: Killing 5453:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): DHA:empty #37
08-24 14:03:41.596   776  1660 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ce76db8 6294:com.samsung.groupcast/u0a15}
08-24 14:03:41.596  6294  6294 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-24 14:03:41.606   776  1739 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.SPlannerAppWidget, Auto Run ON
08-24 14:03:41.616  6294  6294 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-24 14:03:41.636  6294  6294 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-24 14:03:41.646  6294  6294 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-24 14:03:41.646  6294  6294 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-24 14:03:41.646  6294  6294 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 14:03:41.646  6294  6294 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 14:03:41.646  6294  6294 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:41.646  6294  6294 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 14:03:41.646  6294  6294 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 14:03:41.646   776  1728 I ActivityManager: Killing 4755:com.android.calendar/u0a149 (adj 15): DHA:empty #37
08-24 14:03:41.656   776  1728 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{50e6002 1904:com.sec.android.app.shealth:remote/u0a34}
08-24 14:03:41.666  6309  6309 E Zygote  : v2
08-24 14:03:41.666  6309  6309 I libpersona: KNOX_SDCARD checking this for 10041
08-24 14:03:41.666   776   789 I ActivityManager: Start proc 6309:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-24 14:03:41.666  6309  6309 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:41.666  6309  6309 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:41.666  6309  6309 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:41.666  6309  6309 E Zygote  : accessInfo : 0
08-24 14:03:41.666  6309  6309 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-24 14:03:41.676   776   790 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
08-24 14:03:41.696  6309  6309 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:41.696  6309  6309 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:41.706   776  1294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{647f791 6309:com.samsung.android.sdk.samsunglink/u0a41}
08-24 14:03:41.706  6309  6309 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-24 14:03:41.786  6309  6309 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 14:03:41.786  6309  6309 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 14:03:41.796   776  3496 D SSRM:n  : SIOP:: AP = 480, PST = 459, CUR = 350, LCD = 0
08-24 14:03:41.846  6309  6309 I SL_DEBUG: isLoggable:: isProductShip = 1
08-24 14:03:41.856  6309  6309 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-24 14:03:41.866   776  1581 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.866   776  1728 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-24 14:03:41.866   776  1294 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.866   776  2572 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.876   776  1739 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.876   776  1624 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.886   776  1411 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.886   776  1740 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.886   776  1660 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.886   776  2569 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: onUnbind
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: CSB onClientsDisconnected
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDown
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDownCarState
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: Skip, car not connected.
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDownClientState
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: requestStop
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: onDestroy
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDown
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDownCarState
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: Skip, car not connected.
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: tearDownClientState
08-24 14:03:41.916  6171  6171 D CAR.SERVICE: requestStop
08-24 14:03:41.926  6171  6171 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@4557d15 that was originally bound here
08-24 14:03:41.926  6171  6171 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@4557d15 that was originally bound here
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 14:03:41.926  6171  6171 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 14:03:41.926   776  1294 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@f5e3bd0
08-24 14:03:41.996  6309  6309 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-24 14:03:41.996  6309  6309 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-24 14:03:41.996  6309  6309 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-24 14:03:41.996  6309  6309 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-24 14:03:41.996  6309  6309 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-24 14:03:41.996  6309  6309 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 14:03:41.996  6309  6309 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 14:03:41.996  6309  6309 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:41.996  6309  6309 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 14:03:41.996  6309  6309 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 14:03:42.006   776  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3ea070 1742:android.process.acore/u0a19}
08-24 14:03:42.016  5095  5095 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-24 14:03:42.016   776  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a9d14b 5095:com.sec.android.gallery3d/u0a47}
08-24 14:03:42.026   776  1581 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 14:03:42.046  6332  6332 E Zygote  : v2
08-24 14:03:42.046   776   790 I ActivityManager: Start proc 6332:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-24 14:03:42.046  6332  6332 I libpersona: KNOX_SDCARD checking this for 10050
08-24 14:03:42.046  6332  6332 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.046  6332  6332 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.056  6332  6332 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.056  6332  6332 E Zygote  : accessInfo : 0
08-24 14:03:42.056  6332  6332 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-24 14:03:42.076  6332  6332 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.076  6332  6332 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.086   776  1660 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efed9a6 6332:com.sec.android.app.myfiles/u0a50}
08-24 14:03:42.096  6332  6332 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-24 14:03:42.106  6332  6332 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-24 14:03:42.146  6332  6332 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 14:03:42.156   329   329 E installd: system dir 0 : /system/app/
08-24 14:03:42.156   329   329 E installd: system dir 1 : /system/priv-app/
08-24 14:03:42.156   329   329 E installd: system dir 2 : /vendor/app/
08-24 14:03:42.156   329   329 E installd: system dir 3 : /oem/app/
08-24 14:03:42.166   776  1660 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3e861 2853:com.android.settings/1000}
08-24 14:03:42.166   776   934 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 14:03:42.186   776  1581 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3e861 2853:com.android.settings/1000}
08-24 14:03:42.196  6347  6347 E Zygote  : v2
08-24 14:03:42.196   776  1728 I ActivityManager: Start proc 6347:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-24 14:03:42.196  6347  6347 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.196  6347  6347 I libpersona: KNOX_SDCARD checking this for 10169
08-24 14:03:42.196  6347  6347 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.196  6347  6347 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.196  6347  6347 E Zygote  : accessInfo : 0
08-24 14:03:42.196  6347  6347 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-24 14:03:42.216  6347  6347 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.216  6347  6347 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.226   776  2572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12eea32 6347:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-24 14:03:42.236  6347  6347 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-24 14:03:42.246  6347  6347 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-24 14:03:42.256   776  1728 I ActivityManager: Killing 5468:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-24 14:03:42.266   776  1728 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd48bbf 1704:com.android.phone/1001}
08-24 14:03:42.276   776   790 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-24 14:03:42.276   776  2572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1fa007f 1843:com.google.android.googlequicksearchbox:search/u0a61}
08-24 14:03:42.286   776  2569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1fa007f 1843:com.google.android.googlequicksearchbox:search/u0a61}
08-24 14:03:42.296   776  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a03900 6219:com.samsung.android.sm.provider/1000}
08-24 14:03:42.316  2460  2460 E audit   : type=1400 msg=audit(1472040222.316:284): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:42.316  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.316  2460  2460 E audit   : type=1300 msg=audit(1472040222.316:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4f000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:42.316  2460  2460 E audit   : type=1327 msg=audit(1472040222.316:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 14:03:42.316  2460  2460 E audit   : type=1320 msg=audit(1472040222.316:284): 
08-24 14:03:42.316  6361  6361 E Zygote  : v2
08-24 14:03:42.316  6361  6361 I libpersona: KNOX_SDCARD checking this for 5012
08-24 14:03:42.316  6361  6361 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.316  6361  6361 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.316  6361  6361 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.316  6361  6361 E Zygote  : accessInfo : 0
08-24 14:03:42.316  6361  6361 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-24 14:03:42.316   776  1580 I ActivityManager: Start proc 6361:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-24 14:03:42.336  1843  6359 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 14:03:42.356  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.356  6361  6361 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.356   776  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b967539 6361:com.samsung.android.sm.devicesecurity/5012}
08-24 14:03:42.366  6361  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-24 14:03:42.376  2460  2460 E audit   : type=1400 msg=audit(1472040222.376:285): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:42.376  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.376  2460  2460 E audit   : type=1300 msg=audit(1472040222.376:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f0f000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:42.376  2460  2460 E audit   : type=1327 msg=audit(1472040222.376:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 14:03:42.376  2460  2460 E audit   : type=1320 msg=audit(1472040222.376:285): 
08-24 14:03:42.376  6361  6361 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-24 14:03:42.396  1843  6359 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 14:03:42.406  1843  6359 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 14:03:42.406   776  1727 I ActivityManager: Killing 5486:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-24 14:03:42.416   776  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f1139ae 3255:com.android.contacts/u0a19}
08-24 14:03:42.426   776   861 I ActivityManager: Start proc 6374:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-24 14:03:42.426  6374  6374 E Zygote  : v2
08-24 14:03:42.426  6374  6374 I libpersona: KNOX_SDCARD checking this for 10210
08-24 14:03:42.426  6374  6374 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.426  6374  6374 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.426  6374  6374 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.426  2460  2460 E audit   : type=1400 msg=audit(1472040222.426:286): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:42.426  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.426  2460  2460 E audit   : type=1300 msg=audit(1472040222.426:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f0f000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:42.426  2460  2460 E audit   : type=1327 msg=audit(1472040222.426:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 14:03:42.426  6374  6374 E Zygote  : accessInfo : 0
08-24 14:03:42.426  2460  2460 E audit   : type=1320 msg=audit(1472040222.426:286): 
08-24 14:03:42.426  6374  6374 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-24 14:03:42.426  6273  6273 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 14:03:42.436  6273  6273 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:42.436  6273  6273 D AndroidRuntime: readGMSProperty: start
08-24 14:03:42.436  6273  6273 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:03:42.436  6273  6273 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:42.436  6273  6273 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:42.436  6273  6273 D AndroidRuntime: readGMSProperty: end
08-24 14:03:42.436  6273  6273 D AndroidRuntime: addProductProperty: start
08-24 14:03:42.436   776  1294 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
08-24 14:03:42.446  6273  6273 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 14:03:42.446  6273  6273 W art     : af0a5000-b1fcb000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:42.446  6273  6273 W art     : b1fcb000-b423a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:42.446  6273  6273 W art     : b423a000-b423b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:42.446  6273  6273 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 14:03:42.446  6273  6273 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 14:03:42.446  6273  6273 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 14:03:42.446  6273  6273 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 14:03:42.446  6273  6273 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 14:03:42.446  6273  6273 W art     : b47dd000-b47e0000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:42.446  6273  6273 W art     : b47e0000-b47e1000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:42.446  6273  6273 W art     : b47e1000-b47e2000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:42.446  6273  6273 W art     : b47e2000-b47e3000 r--p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b47e3000-b4803000 r--s 00000000 00:0b 7184       /dev/__properties__
08-24 14:03:42.446  6273  6273 W art     : b4803000-b5214000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:42.446  6273  6273 W art     : b5214000-b5215000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5215000-b525e000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:42.446  6273  6273 W art     : b525e000-b525f000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:42.446  6273  6273 W art     : b525f000-b5267000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5267000-b5268000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5268000-b529d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:42.446  6273  6273 W art     : b529d000-b529e000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b529e000-b529f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:42.446  6273  6273 W art     : b529f000-b52a0000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:42.446  6273  6273 W art     : b52a0000-b52f8000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:42.446  6273  6273 W art     : b52f8000-b52f9000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b52f9000-b52fa000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:42.446  6273  6273 W art     : b52fa000-b52fb000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:42.446  6273  6273 W art     : b52fc000-b5302000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:42.446  6273  6273 W art     : b5302000-b5303000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:42.446  6273  6273 W art     : b5303000-b5304000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:42.446  6273  6273 W art     : b5304000-b5306000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5307000-b5311000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:42.446  6273  6273 W art     : b5311000-b5314000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:42.446  6273  6273 W art     : b5314000-b5315000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:42.446  6273  6273 W art     : b5316000-b532d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:42.446  6273  6273 W art     : b532d000-b532e000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b532e000-b532f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:42.446  6273  6273 W art     : b532f000-b5330000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:42.446  6273  6273 W art     : b5331000-b533b000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:42.446  6273  6273 W art     : b533b000-b533c000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:42.446  6273  6273 W art     : b533c000-b533d000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:42.446  6273  6273 W art     : b533d000-b5341000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:42.446  6273  6273 W art     : b5341000-b5342000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:42.446  6273  6273 W art     : b5342000-b5343000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:42.446  6273  6273 W art     : b5343000-b5359000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:42.446  6273  6273 W art     : b5359000-b535a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:42.446  6273  6273 W art     : b535a000-b535b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:42.446  6273  6273 W art     : b535b000-b5368000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:42.446  6273  6273 W art     : b5368000-b5369000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:42.446  6273  6273 W art     : b5369000-b536a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:42.446  6273  6273 W art     : b536a000-b53ca000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 14:03:42.446  6273  6273 W art     : b53ca000-b53cd000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 14:03:42.446  6273  6273 W art     : b53cd000-b53d1000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b53d1000-b5432000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 14:03:42.446  6273  6273 W art     : b5432000-b5433000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 14:03:42.446  6273  6273 W art     : b5433000-b5482000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:42.446  6273  6273 W art     : b5482000-b5484000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:42.446  6273  6273 W art     : b5484000-b5485000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:42.446  6273  6273 W art     : b5485000-b5486000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5486000-b548d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 14:03:42.446  6273  6273 W art     : b548d000-b548e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 14:03:42.446  6273  6273 W art     : b548e000-b548f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 14:03:42.446  6273  6273 W art     : b5490000-b5493000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 14:03:42.446  6273  6273 W art     : b5493000-b5494000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 14:03:42.446  6273  6273 W art     : b5494000-b5495000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 14:03:42.446  6273  6273 W art     : b5496000-b549a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 14:03:42.446  6273  6273 W art     : b549a000-b549b000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b549b000-b549c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 14:03:42.446  6273  6273 W art     : b549c000-b549d000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-24 14:03:42.446  6273  6273 W art     : b549e000-b54bb000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:42.446  6273  6273 W art     : b54bb000-b54bc000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:42.446  6273  6273 W art     : b54bc000-b54bd000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:42.446  6273  6273 W art     : b54be000-b54c3000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:42.446  6273  6273 W art     : b54c3000-b54c4000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:42.446  6273  6273 W art     : b54c4000-b54c5000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:42.446  6273  6273 W art     : b54c6000-b54f7000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:42.446  6273  6273 W art     : b54f7000-b54fa000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:42.446  6273  6273 W art     : b54fa000-b54fb000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:42.446  6273  6273 W art     : b54fc000-b5537000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 14:03:42.446  6273  6273 W art     : b5537000-b5538000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 14:03:42.446  6273  6273 W art     : b5538000-b5539000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 14:03:42.446  6273  6273 W art     : b553a000-b5541000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:42.446  6273  6273 W art     : b5541000-b5542000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5542000-b5543000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:42.446  6273  6273 W art     : b5543000-b5544000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:42.446  6273  6273 W art     : b5544000-b5545000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5545000-b555c000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:42.446  6273  6273 W art     : b555c000-b555d000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b555d000-b5560000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:42.446  6273  6273 W art     : b5560000-b5561000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:42.446  6273  6273 W art     : b5561000-b5580000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:42.446  6273  6273 W art     : b5580000-b5581000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:42.446  6273  6273 W art     : b5581000-b5582000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:42.446  6273  6273 W art     : b5582000-b55c0000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:42.446  6273  6273 W art     : b55c0000-b55c1000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b55c1000-b55c3000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:42.446  6273  6273 W art     : b55c3000-b55c4000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:42.446  6273  6273 W art     : b55c5000-b55cc000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:42.446  6273  6273 W art     : b55cc000-b55cd000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:42.446  6273  6273 W art     : b55cd000-b55ce000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:42.446  6273  6273 W art     : b55cf000-b55d2000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:42.446  6273  6273 W art     : b55d2000-b55d3000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:42.446  6273  6273 W art     : b55d3000-b55d4000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:42.446  6273  6273 W art     : b55d4000-b55da000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:42.446  6273  6273 W art     : b55da000-b55db000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b55db000-b55dc000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:42.446  6273  6273 W art     : b55dc000-b55dd000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:42.446  6273  6273 W art     : b55dd000-b55e6000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:42.446  6273  6273 W art     : b55e6000-b55e7000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:42.446  6273  6273 W art     : b55e7000-b55e8000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:42.446  6273  6273 W art     : b55e8000-b5679000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:42.446  6273  6273 W art     : b5679000-b567a000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b567a000-b5685000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:42.446  6273  6273 W art     : b5685000-b5686000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:42.446  6273  6273 W art     : b5687000-b5699000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:42.446  6273  6273 W art     : b5699000-b569a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:42.446  6273  6273 W art     : b569a000-b569b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:42.446  6273  6273 W art     : b569c000-b56a1000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:42.446  6273  6273 W art     : b56a1000-b56a2000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:42.446  6273  6273 W art     : b56a2000-b56a3000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:42.446  6273  6273 W art     : b56a4000-b5711000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:42.446  6273  6273 W art     : b5711000-b5712000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5712000-b5714000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:42.446  6273  6273 W art     : b5714000-b5715000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:42.446  6273  6273 W art     : b5715000-b5716000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5716000-b571d000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:42.446  6273  6273 W art     : b571d000-b571e000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:42.446  6273  6273 W art     : b571e000-b571f000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:42.446  6273  6273 W art     : b5720000-b57a0000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:42.446  6273  6273 W art     : b57a0000-b57a1000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b57a1000-b57a2000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:42.446  6273  6273 W art     : b57a2000-b57a3000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:42.446  6273  6273 W art     : b57a3000-b57ba000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b57ba000-b57f1000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 14:03:42.446  6273  6273 W art     : ib/libqc-opt.so
08-24 14:03:42.446  6273  6273 W art     : b57f1000-b57f2000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 14:03:42.446  6273  6273 W art     : b57f2000-b57f3000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 14:03:42.446  6273  6273 W art     : b57f3000-b580f000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:42.446  6273  6273 W art     : b580f000-b5810000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:42.446  6273  6273 W art     : b5810000-b5811000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:42.446  6273  6273 W art     : b5812000-b5873000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:42.446  6273  6273 W art     : b5873000-b5875000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:42.446  6273  6273 W art     : b5875000-b5876000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:42.446  6273  6273 W art     : b5877000-b589e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:42.446  6273  6273 W art     : b589e000-b589f000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b589f000-b58a0000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:42.446  6273  6273 W art     : b58a0000-b58a1000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:42.446  6273  6273 W art     : b58a2000-b58aa000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:42.446  6273  6273 W art     : b58aa000-b58ac000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:42.446  6273  6273 W art     : b58ac000-b58ad000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:42.446  6273  6273 W art     : b58ae000-b58b1000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:42.446  6273  6273 W art     : b58b1000-b58b2000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:42.446  6273  6273 W art     : b58b2000-b58b3000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:42.446  6273  6273 W art     : b58b3000-b58b7000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:42.446  6273  6273 W art     : b58b7000-b58b8000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b58b8000-b58b9000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:42.446  6273  6273 W art     : b58b9000-b58ba000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:42.446  6273  6273 W art     : b58ba000-b58ca000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:42.446  6273  6273 W art     : b58ca000-b58cb000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:42.446  6273  6273 W art     : b58cb000-b58cc000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:42.446  6273  6273 W art     : b58cc000-b5912000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5912000-b591b000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:42.446  6273  6273 W art     : b591b000-b591c000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:42.446  6273  6273 W art     : b591c000-b591d000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:42.446  6273  6273 W art     : b591e000-b5923000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:42.446  6273  6273 W art     : b5923000-b5924000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:42.446  6273  6273 W art     : b5924000-b5925000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:42.446  6273  6273 W art     : b5925000-b5928000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 14:03:42.446  6273  6273 W art     : b5928000-b5929000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5929000-b592a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 14:03:42.446  6273  6273 W art     : b592a000-b592b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 14:03:42.446  6273  6273 W art     : b592c000-b5944000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:42.446  6273  6273 W art     : b5944000-b5945000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5945000-b5946000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:42.446  6273  6273 W art     : b5946000-b5947000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:42.446  6273  6273 W art     : b5947000-b5948000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:42.446  6273  6273 W art     : b5948000-b5ae2000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:42.446  6273  6273 W art     : b5ae2000-b5ae3000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5ae3000-b5af0000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:42.446  6273  6273 W art     : b5af0000-b5af1000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:42.446  6273  6273 W art     : b5af1000-b5af5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:42.446  6273  6273 W art     : b5af5000-b5af6000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5af6000-b5af7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:42.446  6273  6273 W art     : b5af7000-b5af8000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:42.446  6273  6273 W art     : b5af8000-b5b0b000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:42.446  6273  6273 W art     : b5b0b000-b5b0c000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:42.446  6273  6273 W art     : b5b0c000-b5b0d000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:42.446  6273  6273 W art     : b5b0e000-b5b59000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:42.446  6273  6273 W art     : b5b59000-b5b5a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:42.446  6273  6273 W art     : b5b5a000-b5b5b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:42.446  6273  6273 W art     : b5b5b000-b5b5d000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5b5e000-b5b6f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:42.446  6273  6273 W art     : b5b6f000-b5b70000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5b70000-b5b71000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:42.446  6273  6273 W art     : b5b71000-b5b72000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:42.446  6273  6273 W art     : b5b72000-b5b73000 r--p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5b73000-b5b7d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:42.446  6273  6273 W art     : b5b7d000-b5b7f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:42.446  6273  6273 W art     : b5b7f000-b5b80000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:42.446  6273  6273 W art     : b5b80000-b5b99000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:42.446  6273  6273 W art     : b5b99000-b5b9a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:42.446  6273  6273 W art     : b5b9a000-b5b9d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:42.446  6273  6273 W art     : b5b9d000-b5ba1000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5ba1000-b5c15000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:42.446  6273  6273 W art     : b5c15000-b5c16000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5c16000-b5c19000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:42.446  6273  6273 W art     : b5c19000-b5c1a000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:42.446  6273  6273 W art     : b5c1a000-b5c1b000 r--p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5c1b000-b5c1e000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:42.446  6273  6273 W art     : b5c1e000-b5c1f000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:42.446  6273  6273 W art     : b5c1f000-b5c20000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:42.446  6273  6273 W art     : b5c20000-b5c21000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c21000-b5c26000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:42.446  6273  6273 W art     : b5c26000-b5c27000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:42.446  6273  6273 W art     : b5c27000-b5c28000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:42.446  6273  6273 W art     : b5c28000-b5c29000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c29000-b5c2c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b5c2c000-b5c2d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b5c2d000-b5c2e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b5c2e000-b5c2f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c2f000-b5c33000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:42.446  6273  6273 W art     : b5c33000-b5c34000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:42.446  6273  6273 W art     : b5c34000-b5c35000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:42.446  6273  6273 W art     : b5c35000-b5c36000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:42.446  6273  6273 W art     : b5c36000-b5c3a000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:42.446  6273  6273 W art     : b5c3a000-b5c3b000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:42.446  6273  6273 W art     : b5c3b000-b5c3c000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:42.446  6273  6273 W art     : b5c3c000-b5c3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c3d000-b5c4b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:42.446  6273  6273 W art     : b5c4b000-b5c4c000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b5c4c000-b5c4d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:42.446  6273  6273 W art     : b5c4d000-b5c4e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:42.446  6273  6273 W art     : b5c4e000-b5c58000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:42.446  6273  6273 W art     : b5c58000-b5c5b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:42.446  6273  6273 W art     : b5c5b000-b5c5c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:42.446  6273  6273 W art     : b5c5c000-b5c5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c5d000-b5c67000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:42.446  6273  6273 W art     : b5c67000-b5c6a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:42.446  6273  6273 W art     : b5c6a000-b5c6b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:42.446  6273  6273 W art     : b5c6b000-b5c6f000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:42.446  6273  6273 W art     : b5c6f000-b5c70000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:42.446  6273  6273 W art     : b5c70000-b5c71000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:42.446  6273  6273 W art     : b5c71000-b5c72000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b5c72000-b5c7f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:42.446  6273  6273 W art     : b5c7f000-b5c81000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:42.446  6273  6273 W art     : b5c81000-b5c82000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:42.446  6273  6273 W art     : b5c82000-b6094000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:42.446  6273  6273 W art     : b6094000-b6095000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6095000-b609e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:42.446  6273  6273 W art     : b609e000-b60a2000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:42.446  6273  6273 W art     : b60a2000-b60a3000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b60a3000-b60aa000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:42.446  6273  6273 W art     : b60aa000-b60ab000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:42.446  6273  6273 W art     : b60ab000-b60ac000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:42.446  6273  6273 W art     : b60ac000-b60ad000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b60ad000-b60c8000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 14:03:42.446  6273  6273 W art     : b60c8000-b60c9000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 14:03:42.446  6273  6273 W art     : b60c9000-b60ca000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 14:03:42.446  6273  6273 W art     : b60ca000-b60cb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b60cb000-b6117000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:42.446  6273  6273 W art     : b6117000-b6118000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6118000-b6119000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:42.446  6273  6273 W art     : b6119000-b611a000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:42.446  6273  6273 W art     : b611a000-b611b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b611b000-b611f000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:42.446  6273  6273 W art     : b611f000-b6120000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6120000-b6121000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:42.446  6273  6273 W art     : b6121000-b6122000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:42.446  6273  6273 W art     : b6122000-b615a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:42.446  6273  6273 W art     : b615a000-b615b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:42.446  6273  6273 W art     : b615b000-b615c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:42.446  6273  6273 W art     : b615c000-b615d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.446  6273  6273 W art     : b615d000-b61fb000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:42.446  6273  6273 W art     : b61fb000-b61fc000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b61fc000-b621a000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:42.446  6273  6273 W art     : b621a000-b621b000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:42.446  6273  6273 W art     : b621b000-b638e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:42.446  6273  6273 W art     : b638e000-b6399000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:42.446  6273  6273 W art     : b6399000-b639a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:42.446  6273  6273 W art     : b639a000-b64b1000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:42.446  6273  6273 W art     : b64b1000-b64bc000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:42.446  6273  6273 W art     : b64bc000-b64bd000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:42.446  6273  6273 W art     : b64bd000-b64c1000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b64c1000-b64e5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 14:03:42.446  6273  6273 W art     : b64e5000-b64e7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 14:03:42.446  6273  6273 W art     : b64e7000-b64e8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 14:03:42.446  6273  6273 W art     : b64e8000-b658e000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:42.446  6273  6273 W art     : b658e000-b659b000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:42.446  6273  6273 W art     : b659b000-b659c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:42.446  6273  6273 W art     : b659c000-b659d000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b659d000-b65f0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:42.446  6273  6273 W art     : b65f0000-b65f1000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     ,: b65f1000-b65f2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:42.446  6273  6273 W art     : b65f2000-b65f3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:42.446  6273  6273 W art     : b65f3000-b65f8000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b65f8000-b660a000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:42.446  6273  6273 W art     : b660a000-b660b000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b660b000-b660c000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:42.446  6273  6273 W art     : b660c000-b660d000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:42.446  6273  6273 W art     : b660d000-b6614000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:42.446  6273  6273 W art     : b6614000-b6615000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:42.446  6273  6273 W art     : b6615000-b6616000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:42.446  6273  6273 W art     : b6616000-b6617000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6617000-b661a000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:42.446  6273  6273 W art     : b661a000-b661b000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:42.446  6273  6273 W art     : b661b000-b661c000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:42.446  6273  6273 W art     : b661c000-b6620000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:42.446  6273  6273 W art     : b6620000-b6621000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:42.446  6273  6273 W art     : b6621000-b6622000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:42.446  6273  6273 W art     : b6622000-b6630000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:42.446  6273  6273 W art     : b6630000-b6631000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6631000-b6632000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:42.446  6273  6273 W art     : b6632000-b6633000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:42.446  6273  6273 W art     : b6633000-b663c000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:42.446  6273  6273 W art     : b663c000-b663d000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:42.446  6273  6273 W art     : b663d000-b663e000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:42.446  6273  6273 W art     : b663e000-b66a4000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:42.446  6273  6273 W art     : b66a4000-b66a5000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b66a5000-b66a7000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:42.446  6273  6273 W art     : b66a7000-b66b0000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:42.446  6273  6273 W art     : b66b0000-b66b3000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b66b3000-b674a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:42.446  6273  6273 W art     : b674a000-b674c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:42.446  6273  6273 W art     : b674c000-b674d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:42.446  6273  6273 W art     : b674d000-b674e000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b674e000-b6a6f000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 14:03:42.446  6273  6273 W art     : b6a6f000-b6a70000 ---p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6a70000-b6a8b000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 14:03:42.446  6273  6273 W art     : b6a8b000-b6a8f000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 14:03:42.446  6273  6273 W art     : b6a8f000-b6a94000 rw-p 00000000 00:00 0 
08-24 14:03:42.446  6273  6273 W art     : b6a94000-b6a9c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b6a9c000-b6a9d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b6a9d000-b6a9e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:42.446  6273  6273 W art     : b6a9e000-b6acc000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:42.446  6273  6273 W art     : b6acc000-b6acd000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6acd000-b6ad4000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:42.456  6273  6273 W art     : b6ad4000-b6ad5000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:42.456  6273  6273 W art     : b6ad5000-b6b1b000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:42.456  6273  6273 W art     : b6b1b000-b6b1c000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6b1c000-b6b1f000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:42.456  6273  6273 W art     : b6b1f000-b6b20000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:42.456  6273  6273 W art     : b6b20000-b6b3b000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:42.456  6273  6273 W art     : b6b3b000-b6b3f000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:42.456  6273  6273 W art     : b6b3f000-b6b40000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:42.456  6273  6273 W art     : b6b40000-b6b8d000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:42.456  6273  6273 W art     : b6b8d000-b6b8e000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6b8e000-b6b9a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:42.456  6273  6273 W art     : b6b9a000-b6b9b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:42.456  6273  6273 W art     : b6b9b000-b6ba8000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 14:03:42.456  6273  6273 W art     : b6ba8000-b6ba9000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6ba9000-b6baa000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 14:03:42.456  6273  6273 W art     : b6baa000-b6bab000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 14:03:42.456  6273  6273 W art     : b6bab000-b6bb3000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:42.456  6273  6273 W art     : b6bb3000-b6bb4000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6bb4000-b6bb5000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:42.456  6273  6273 W art     : b6bb5000-b6bb6000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:42.456  6273  6273 W art     : b6bb6000-b6bbd000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:42.456  6273  6273 W art     : b6bbd000-b6bbe000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:42.456  6273  6273 W art     : b6bbe000-b6bbf000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:42.456  6273  6273 W art     : b6bbf000-b6bd3000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:42.456  6273  6273 W art     : b6bd3000-b6bd5000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:42.456  6273  6273 W art     : b6bd5000-b6bd6000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:42.456  6273  6273 W art     : b6bd6000-b6bfe000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:42.456  6273  6273 W art     : b6bfe000-b6c00000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:42.456  6273  6273 W art     : b6c00000-b6c01000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:42.456  6273  6273 W art     : b6c01000-b6c04000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:42.456  6273  6273 W art     : b6c04000-b6c05000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:42.456  6273  6273 W art     : b6c05000-b6c06000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:42.456  6273  6273 W art     : b6c06000-b6c0f000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:42.456  6273  6273 W art     : b6c0f000-b6c10000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:42.456  6273  6273 W art     : b6c10000-b6c11000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:42.456  6273  6273 W art     : b6c11000-b6c31000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 14:03:42.456  6273  6273 W art     : b6c31000-b6c32000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 14:03:42.456  6273  6273 W art     : b6c32000-b6c33000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 14:03:42.456  6273  6273 W art     : b6c33000-b6ca6000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 14:03:42.456  6273  6273 W art     : b6ca6000-b6caa000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 14:03:42.456  6273  6273 W art     : b6caa000-b6cad000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 14:03:42.456  6273  6273 W art     : b6cad000-b6cb7000 rw-p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6cb7000-b6d3f000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:42.456  6273  6273 W art     : b6d3f000-b6d40000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6d40000-b6d44000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:42.456  6273  6273 W art     : b6d44000-b6d45000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:42.456  6273  6273 W art     : b6d45000-b6d46000 rw-p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6d46000-b6d6f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:42.456  6273  6273 W art     : b6d6f000-b6d70000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6d70000-b6d73000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:42.456  6273  6273 W art     : b6d73000-b6d74000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:42.456  6273  6273 W art     : b6d74000-b6e4e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:42.456  6273  6273 W art     : b6e4e000-b6e55000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:42.456  6273  6273 W art     : b6e55000-b6e5d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:42.456  6273  6273 W art     : b6e5d000-b6e5e000 rw-p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6e5e000-b6e5f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:42.456  6273  6273 W art     : b6e5f000-b6e60000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 14:03:42.456  6273  6273 W art     : b6e60000-b6e61000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6e61000-b6e64000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6e64000-b6e89000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:42.456  6273  6273 W art     : b6e89000-b6e8a000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6e8a000-b6e91000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:42.456  6273  6273 W art     : b6e91000-b6e92000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:42.456  6273  6273 W art     : b6e92000-b6e99000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:42.456  6273  6273 W art     : b6e99000-b6e9a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:42.456  6273  6273 W art     : b6e9a000-b6e9b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:42.456  6273  6273 W art     : b6e9b000-b6e9c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6e9c000-b6eb4000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 14:03:42.456  6273  6273 W art     : b6eb4000-b6eb5000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6eb5000-b6eb6000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 14:03:42.456  6273  6273 W art     : b6eb6000-b6eb7000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 14:03:42.456  6273  6273 W art     : b6eb7000-b6ec5000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:42.456  6273  6273 W art     : b6ec5000-b6ec6000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6ec6000-b6ec7000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:42.456  6273  6273 W art     : b6ec7000-b6ec8000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:42.456  6273  6273 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:42.456  6273  6273 W art     : b6ec9000-b6ecb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6ecb000-b6ecc000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6ecc000-b6ecd000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:42.456  6273  6273 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 14:03:42.456  6273  6273 W art     : b6ece000-b6ecf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:42.456  6273  6273 W art     : b6ecf000-b6eef000 r--s 00000000 00:0b 7184       /dev/__properties__
08-24 14:03:42.456  6273  6273 W art     : b6eef000-b6ef0000 r--p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6ef0000-b6ef1000 ---p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6ef1000-b6ef3000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 14:03:42.456  6273  6273 W art     : b6ef3000-b6ef4000 r-xp 00000000 00:00 0          [sigpage]
08-24 14:03:42.456  6273  6273 W art     : b6ef4000-b6f0f000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 14:03:42.456  6273  6273 W art     : b6f0f000-b6f10000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 14:03:42.456  6273  6273 W art     : b6f10000-b6f12000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 14:03:42.456  6273  6273 W art     : b6f12000-b6f14000 rw-p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : b6f14000-b6f19000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 14:03:42.456  6273  6273 W art     : b6f19000-b6f1a000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 14:03:42.456  6273  6273 W art     : b6f1a000-b6f1b000 rw-p 00000000 00:00 0 
08-24 14:03:42.456  6273  6273 W art     : bee5c000-bee7d000 rw-p 00000000 00:00 0          [stack]
08-24 14:03:42.456  6273  6273 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-24 14:03:42.456   776  2569 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-24 14:03:42.486  6374  6374 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.486  6374  6374 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.496   776  1727 I ActivityManager: Start proc 6387:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-24 14:03:42.496  6387  6387 E Zygote  : v2
08-24 14:03:42.496  6387  6387 I libpersona: KNOX_SDCARD checking this for 10049
08-24 14:03:42.496  6387  6387 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.496  6387  6387 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.496  6387  6387 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.496  6387  6387 E Zygote  : accessInfo : 0
08-24 14:03:42.496  6387  6387 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-24 14:03:42.516  6273  6273 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 14:03:42.526  6387  6387 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.526  6387  6387 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.536   776  1581 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1497ffb 6387:com.android.mms/u0a49}
08-24 14:03:42.556  4426  6386 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-24 14:03:42.556  6387  6387 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-24 14:03:42.566  6273  6273 I Radio-JNI: register_android_hardware_Radio DONE
08-24 14:03:42.576  6273  6273 E AffinityControl: AffinityControl: registerfunction enter
08-24 14:03:42.586  6387  6387 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-24 14:03:42.586  6374  6374 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-24 14:03:42.596  6273  6273 D AndroidRuntime: Calling main entry com.android.commands.am.Am
,08-24 14:03:42.596  6374  6374 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-24 14:03:42.606  6387  6387 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-24 14:03:42.606  6374  6374 D AASAservice: onCreate()
08-24 14:03:42.606   776  1739 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-24 14:03:42.616   776  1739 D ActivityManager: mDVFSHelper.acquire()
08-24 14:03:42.626   776  1739 V WindowManager: addAppToken: AppWindowToken{9cee4ad token=Token{e07adc4 ActivityRecord{ca620d7 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-24 14:03:42.636   776   907 D SecWifiDisplayUtil: Metadata value : none
08-24 14:03:42.636   776   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{654fc65 V.E...... R.....ID 0,0-0,0}
08-24 14:03:42.636   776  1739 I ActivityManager: Start proc 6407:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-24 14:03:42.636  6407  6407 E Zygote  : v2
08-24 14:03:42.636  6407  6407 I libpersona: KNOX_SDCARD checking this for 10004
08-24 14:03:42.636   776  1739 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:42.636  6407  6407 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:42.636  6407  6407 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:42.636  6407  6407 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:42.636  6407  6407 E Zygote  : accessInfo : 0
08-24 14:03:42.636  6407  6407 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-24 14:03:42.636   776  1739 D InputDispatcher: Focus left window: 4374
08-24 14:03:42.636   776   907 D ISSUE_DEBUG: InputChannelName : e765deb Starting com.test.thalitest
08-24 14:03:42.646  6273  6273 D AndroidRuntime: Shutting down VM
08-24 14:03:42.656   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-24 14:03:42.656  5355  5355 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-24 14:03:42.666   776   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{218acac u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-24 14:03:42.666  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-24 14:03:42.666   776   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:776 uid:1000
08-24 14:03:42.666   776   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:42.666   776   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:776 uid:1000
08-24 14:03:42.666   776   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 14:03:42.666   776   907 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-24 14:03:42.676  6407  6407 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:42.676  6407  6407 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:42.676  1843  6359 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 339 ms] updated apps [took 339 ms] 
08-24 14:03:42.686   776  1624 V WindowOrientationListener: setCurrentAppOrientation :-1
08-24 14:03:42.686   776  1624 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-24 14:03:42.696   776  1624 D ActivityManager:  Launching com.test.thalitest, updated priority
08-24 14:03:42.716  1725  1896 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-24 14:03:42.716  1725  1725 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-24 14:03:42.726   776   907 V WindowStateAnimator: Finishing drawing window Window{e765deb u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-24 14:03:42.726   294   835 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-24 14:03:42.726   294   354 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-24 14:03:42.726   294   354 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
08-24 14:03:42.726   294   354 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
08-24 14:03:42.726  4374  4374 V ActivityThread: updateVisibility : ActivityRecord{9fcb3c8 token=android.os.BinderProxy@29ff580 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-24 14:03:42.736   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8e6364
08-24 14:03:42.736   294   835 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-24 14:03:42.736   294   354 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-24 14:03:42.736  2233  2246 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-24 14:03:42.736  1725  1725 V ActivityThread: updateVisibility : ActivityRecord{560c50e token=android.os.BinderProxy@e023e7d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 14:03:42.736  1725  1725 D Launcher: onTrimMemory. Level: 20
08-24 14:03:42.746   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e63a4
,08-24 14:03:43.026   776  1624 I WindowManager: Screenshot max retries 4 of Token{e07adc4 ActivityRecord{ca620d7 u0 com.test.thalitest/.MainActivity t168}} appWin=Window{e765deb u0 d0 Starting com.test.thalitest} drawState=4
,08-24 14:03:43.036   776   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-24 14:03:43.036   776   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e765deb u0 d0 Starting com.test.thalitest}
08-24 14:03:43.036  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
,08-24 14:03:43.046  6407  6407 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 14:03:43.046  6387  6387 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-24 14:03:43.056  6387  6387 D Mms/TelephonyPermission: start operation mode monitor
,08-24 14:03:43.056  6387  6387 D Mms/TelephonyPermission: User ID is null set current User Id
,08-24 14:03:43.056  6387  6424 D Mms/ArtClassLoader: init before art third
,08-24 14:03:43.066   776  3496 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 14:03:43.066  6387  6423 D Mms/ArtClassLoader: init before art second
,08-24 14:03:43.066  6387  6422 D Mms/ArtClassLoader: init before art first
,08-24 14:03:43.076  6387  6387 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 14:03:43.076  6387  6387 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 14:03:43.086  6387  6387 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-24 14:03:43.086  6387  6387 D Mms/TelephonyPermission: isDefault true
,08-24 14:03:43.086  6387  6387 D Mms/MmsApp: onCreate() com.android.mms
,08-24 14:03:43.086  6407  6407 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 14:03:43.086  6407  6407 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 14:03:43.116  6407  6407 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-24 14:03:43.116  6387  6387 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-24 14:03:43.126  6387  6424 D Mms/ArtClassLoader: init [DONE] art
,08-24 14:03:43.126  6387  6387 D Mms/MmsApp: [start]    initCountryIso consume time = 77.927187
,08-24 14:03:43.126   776  1727 D CountryDetector: The first listener is added
,08-24 14:03:43.136  6387  6387 D Mms/MmsApp: [end]    initCountryIso consume time = 6.618907
08-24 14:03:43.136  6387  6387 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.101979
,08-24 14:03:43.136  6407  6407 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 14:03:43.136  6407  6407 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 14:03:43.146  6387  6387 D Mms/MmsConfig: before partial update
,08-24 14:03:43.146  6407  6407 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1573-1576)
,08-24 14:03:43.146  6407  6407 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 14:03:43.166   776  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:43.166  6407  6435 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-24 14:03:43.166  6407  6407 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4a11ed0}
08-24 14:03:43.166  6407  6407 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 14:03:43.166  6407  6407 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:03:43.176  6387  6387 D Mms/MmsConfig: Load Resize quality : 80
,08-24 14:03:43.176  6407  6407 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 14:03:43.196  6387  6387 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-24 14:03:43.196  6387  6387 D EasySignUpManager_1.0.5: isAuth is false
08-24 14:03:43.196  6387  6387 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-24 14:03:43.196  6387  6387 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-24 14:03:43.196  6387  6387 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-24 14:03:43.196  6387  6387 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 14:03:43.196  6387  6387 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-24 14:03:43.196  6387  6387 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 14:03:43.196  6387  6387 D EasySignUpManager_1.0.5: isAuth is false
08-24 14:03:43.206  6387  6387 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-24 14:03:43.206  6387  6387 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-24 14:03:43.206  6407  6407 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 14:03:43.206  6407  6407 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 14:03:43.206  6407  6407 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 14:03:43.206  6407  6407 I Adreno-EGL: Local Branch: ss
08-24 14:03:43.206  6407  6407 I Adreno-EGL: Remote Branch: 
08-24 14:03:43.206  6407  6407 I Adreno-EGL: Local Patches: 
08-24 14:03:43.206  6407  6407 I Adreno-EGL: Reconstruct Branch: 
,08-24 14:03:43.216  6407  6407 D libEGL  : eglInitialize EGLDisplay = 0xbece2dac
,08-24 14:03:43.216  1704  1722 D TP/MmsSmsProvider: query, match:2117, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.216  1704  1722 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.992 ms
,08-24 14:03:43.226  6387  6387 E CscParser: mps_code.dat does not exist
,08-24 14:03:43.226  6387  6387 E CscParser: customer_path =/system/csc/customer.xml
08-24 14:03:43.226  6387  6387 E CscParser: fileName + /system/csc/customer.xml
,08-24 14:03:43.236  6387  6387 E CscParser: mps_code.dat does not exist
08-24 14:03:43.236  6387  6387 E CscParser: customer_path =/system/csc/customer.xml
08-24 14:03:43.236  6387  6387 E CscParser: fileName + /system/csc/customer.xml
,08-24 14:03:43.246  6387  6422 D Mms/ArtClassLoader: init [DONE] art
,08-24 14:03:43.246   776  1581 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-24 14:03:43.246   776  1581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-24 14:03:43.256  6387  6387 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-24 14:03:43.256  6387  6423 D Mms/ArtClassLoader: init [DONE] art
,08-24 14:03:43.276  6387  6387 D Mms/MmsConfig:  enable multiwindow = true
,08-24 14:03:43.276  6387  6387 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-24 14:03:43.286  6387  6387 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-24 14:03:43.286  6387  6387 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-24 14:03:43.286  6387  6387 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-24 14:03:43.286  6387  6387 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-24 14:03:43.286  6387  6387 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-24 14:03:43.286  6387  6387 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 14:03:43.286  6407  6407 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-24 14:03:43.286  6387  6387 D Mms/MmsConfig: [end]    init() consume time = 153.567396
,08-24 14:03:43.296  6387  6387 D Mms/Contact: [start]    init() consume time = 5.571719
,08-24 14:03:43.296  6407  6407 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:03:43.296  6407  6407 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-24 14:03:43.296  6407  6407 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-24 14:03:43.296  6407  6407 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-24 14:03:43.306  1704  2066 D TP/MmsSmsProvider: query, match:13, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.306  1704  2066 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.025 ms
,08-24 14:03:43.316  6387  6387 D Mms/Contact: [end]    init consume time = 24.605104
,08-24 14:03:43.316  6407  6407 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-24 14:03:43.316  6387  6460 D Mms/DraftCache: [start]    rebuildCache consume time = 3.20552
,08-24 14:03:43.326  6407  6407 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 14:03:43.326  6387  6387 D Mms:transaction: roaming -> false (slotId = 0)
,08-24 14:03:43.326  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:03:43.326  6387  6387 D Mms:transaction: auto download without roaming -> true
08-24 14:03:43.326  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 14:03:43.326  6387  6387 D Mms:transaction: roaming -> false (slotId = 1)
,08-24 14:03:43.326  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 14:03:43.326  6387  6387 D Mms:transaction: auto download without roaming -> true
08-24 14:03:43.326  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 14:03:43.326  6387  6387 D Mms:transaction: auto download during roaming secondary -> false
08-24 14:03:43.326  6387  6387 D Mms:transaction: mAutoDownload ------> true
,08-24 14:03:43.336  1704  1942 D TP/MmsSmsProvider: query, match:12, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.336  1704  1942 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.121 ms
,08-24 14:03:43.336  6387  6460 D Mms/DraftCache: [end]    rebuildCache consume time = 15.311303
,08-24 14:03:43.366  6387  6387 D ComposerPerformance: 1472040223370 ms / [DONE] Composer constructor
,08-24 14:03:43.366  6387  6387 D CII     : Log Level [5]
08-24 14:03:43.366  6387  6387 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-24 14:03:43.366  6387  6387 I Mms/ReservationManager: ReservationManager()
08-24 14:03:43.366  6387  6462 D Mms/Conversation: [start]    init() consume time = 28.833854
08-24 14:03:43.366  6387  6387 I Mms/ReservationManager: resetAfterConnected()
,08-24 14:03:43.366  1704  2066 D TP/MmsSmsProvider: delete, match:1, calling pid = 6387
08-24 14:03:43.366  1704  2066 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-24 14:03:43.366  1704  2066 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-24 14:03:43.366  1704  2066 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-24 14:03:43.366  1704  2066 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-24 14:03:43.366  1704  2066 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-24 14:03:43.376  1704  1722 D TP/MmsSmsProvider: query, match:7, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.386  1704  2066 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-24 14:03:43.386  1704  1722 D TP/MmsSmsProvider: query, match 7:Elapsed time : 9.229 ms
,08-24 14:03:43.386  6387  6387 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 14:03:43.386  6387  6387 D Mms/MmsApp: [end]    onCreate() consume time = 25.352864
,08-24 14:03:43.386  6387  6387 D Mms/MmsApp: [end]    onCreate() consume time = 0.369896
,08-24 14:03:43.396  1704  2066 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-24 14:03:43.396  1704  2066 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-24 14:03:43.396  1704  2066 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 14:03:43.396  1704  2066 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 21.778 ms
08-24 14:03:43.396  1704  2066 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 14:03:43.396  6387  6387 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-24 14:03:43.396  6387  6387 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-24 14:03:43.396  6387  6387 D Mms:transaction: roaming -> false (slotId = 0)
08-24 14:03:43.396  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:03:43.396  6387  6387 D Mms:transaction: auto download without roaming -> true
08-24 14:03:43.396  6387  6387 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-24 14:03:43.396  6387  6387 D Mms:transaction: mAutoDownload ------> true
,08-24 14:03:43.406   776  1411 I ActivityManager: Start proc 6464:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-24 14:03:43.406  6464  6464 E Zygote  : v2
08-24 14:03:43.406  6464  6464 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:43.406  6464  6464 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:43.406  6464  6464 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:43.406  6464  6464 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:43.406  6464  6464 E Zygote  : accessInfo : 0
,08-24 14:03:43.416  6387  6462 D Mms/Conversation: [end]    init consume time = 22.82099
,08-24 14:03:43.426  6407  6407 D SecWifiDisplayUtil: Metadata value : none
,08-24 14:03:43.426  6387  6462 D Mms/MessagingNotification: [start]    init() consume time = 14.207187
,08-24 14:03:43.426  6407  6407 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{dbb572e I.E...... R.....ID 0,0-0,0}
,08-24 14:03:43.436  6387  6462 D Mms/MessagingNotification: [end]    init consume time = 4.774011
,08-24 14:03:43.436  6407  6477 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-24 14:03:43.436  6387  6478 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.293593
,08-24 14:03:43.436   776  1581 D ISSUE_DEBUG: InputChannelName : 61d55b5 com.test.thalitest/com.test.thalitest.MainActivity
,08-24 14:03:43.436  6387  6479 D Mms/Synchronizer: [start]    doSync consume time = 4.369583
,08-24 14:03:43.446   776  1581 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-24 14:03:43.446   776  1581 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 14:03:43.446   776   776 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 14:03:43.446   776   776 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 14:03:43.446  1704  2066 D TP/MmsSmsProvider: update, match:300, calling pid = 6387
,08-24 14:03:43.446  1704  2066 V TP/MmsSmsProvider: syncDBData start
,08-24 14:03:43.446  1704  2066 V TP/MmsSmsProvider: syncDBData sms end
,08-24 14:03:43.446  1704  2066 V TP/MmsSmsProvider: syncDBData mms end
,08-24 14:03:43.446  1704  2066 V TP/MmsSmsProvider: syncDBData end
,08-24 14:03:43.456  1704  1942 D TP/MmsSmsProvider: query, match:0, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.456  1704  1942 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 14:03:43.456  1704  1942 D TP/MmsSmsProvider: query, match 0:Elapsed time : 2.233 ms
,08-24 14:03:43.456  1704  2066 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.896 ms
,08-24 14:03:43.456  6387  6479 D Mms/Synchronizer: [end]    doSync consume time = 18.074271
,08-24 14:03:43.456  1704  1723 D TP/MmsSmsProvider: query, match:400, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.466  6464  6464 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:43.466  6464  6464 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:43.476   776  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41a9831 6464:com.samsung.android.bbc.bbcagent/1000}
,08-24 14:03:43.486  6407  6407 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6407
,08-24 14:03:43.486   776  1727 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6407 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:03:43.486   776  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-24 14:03:43.486   776  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 14:03:43.486   776  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 14:03:43.486   776  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-24 14:03:43.486   776  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:03:43.496   776  1294 I ActivityManager: Killing 5499:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
,08-24 14:03:43.506  6003  6016 D BadgeProvider: query, [selection] : package=?
,08-24 14:03:43.506  6407  6435 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-24 14:03:43.506  6407  6407 D SecWifiDisplayUtil: Metadata value : none
,08-24 14:03:43.516   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-24 14:03:43.516  6464  6464 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-24 14:03:43.526   776  2572 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-24 14:03:43.526  6387  6478 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 71.980886
08-24 14:03:43.536   776  1728 D InputDispatcher: Focus entered window: 6407
,08-24 14:03:43.536   776   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:776 uid:1000
,08-24 14:03:43.536   776   907 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:43.536  6407  6477 D libEGL  : eglInitialize EGLDisplay = 0x9cab87c4
08-24 14:03:43.536  6407  6477 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:03:43.536   776   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:776 uid:1000
08-24 14:03:43.536   776   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 14:03:43.546  6387  6462 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-24 14:03:43.556  1704  1942 D TP/SmsProvider: query,matched:26, calling pid = 6387
,08-24 14:03:43.556  1704  1942 D TP/SmsProvider: query, match 26:Elapsed time : 1.158 ms
,08-24 14:03:43.566  1704  1722 D TP/MmsSmsProvider: query, match:6, calling pid = 6387, accessRestricted = false
,08-24 14:03:43.566  1704  1722 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.159 ms
,08-24 14:03:43.596  6407  6407 V ActivityThread: updateVisibility : ActivityRecord{72000e1 token=android.os.BinderProxy@4a645a9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 14:03:43.606  6484  6484 E Zygote  : v2
08-24 14:03:43.606  6484  6484 I libpersona: KNOX_SDCARD checking this for 10024
08-24 14:03:43.606  6484  6484 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:43.606   776  1411 I ActivityManager: Start proc 6484:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-24 14:03:43.606  6464  6464 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-24 14:03:43.606  6484  6484 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:43.606  6484  6484 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:43.606   776   786 I art     : Background partial concurrent mark sweep GC freed 60955(3MB) AllocSpace objects, 9(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.815ms total 133.438ms
,08-24 14:03:43.606  6484  6484 E Zygote  : accessInfo : 0
,08-24 14:03:43.606  6484  6484 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-24 14:03:43.616  6407  6407 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-24 14:03:43.616  6407  6407 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 14:03:43.616   776  1660 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:03:43.646  6407  6407 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 14:03:43.656  6484  6484 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:43.656  6484  6484 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:43.666   776   789 I ActivityManager: Killing 5343:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-24 14:03:43.676   776  1740 V WindowStateAnimator: Finishing drawing window Window{61d55b5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-24 14:03:43.676  6407  6407 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 14:03:43.676   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8e6364
,08-24 14:03:43.686   776   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 14:03:43.686  6484  6484 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-24 14:03:43.686   776   907 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +657ms (total +1s61ms)
,08-24 14:03:43.686   776   776 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 14:03:43.686   776   776 I KnoxTimeoutHandler: SD activityfalse
,08-24 14:03:43.686  6407  6407 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4a645a9 time:102115
,08-24 14:03:43.686   776   907 D ActivityManager: mDVFSHelper.release()
08-24 14:03:43.686   776   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ca620d7 u0 com.test.thalitest/.MainActivity t168} time:102116
,08-24 14:03:43.686   776   907 D ViewRootImpl: #3 mView = null
,08-24 14:03:43.686   294   354 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
08-24 14:03:43.686   294   351 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-24 14:03:43.696  4426  5069 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-24 14:03:43.696  6407  6499 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:03:43.696  6407  6499 D libEGL  : eglInitialize EGLDisplay = 0x9a2503ec
,08-24 14:03:43.696   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e63a4
,08-24 14:03:43.706  6484  6484 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-24 14:03:43.706   776  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-24 14:03:43.726  6502  6502 E Zygote  : v2
08-24 14:03:43.726  6502  6502 I libpersona: KNOX_SDCARD checking this for 10097
08-24 14:03:43.726  6502  6502 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:43.726  6502  6502 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:43.726  6502  6502 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:43.726   776   790 I ActivityManager: Start proc 6502:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-24 14:03:43.726   776   790 I ActivityManager: Killing 4217:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-24 14:03:43.726  6502  6502 E Zygote  : accessInfo : 0
08-24 14:03:43.726  6502  6502 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-24 14:03:43.756  6407  6407 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6407
,08-24 14:03:43.776  6502  6502 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:43.776  6502  6502 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:43.786   776   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{49fa2a2 6502:com.google.android.apps.docs/u0a97}
,08-24 14:03:43.786  6387  6462 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 14:03:43.796  6484  6484 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-24 14:03:43.806   776  1727 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-24 14:03:43.816  6502  6502 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 14:03:43.836  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-24 14:03:43.836  6502  6502 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-24 14:03:43.836  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-24 14:03:43.836  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-24 14:03:43.836  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-24 14:03:43.836  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-24 14:03:43.846  6484  6484 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-24 14:03:43.856  4426  5069 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-24 14:03:43.956   776  6192 I HarmonyEASService: Updating for all 1
,08-24 14:03:43.956  6407  6407 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:03:43.986  4426  5069 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-24 14:03:44.036   776  3498 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-24 14:03:44.086  6407  6517 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1736050384
,08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:03:44.096  6407  6517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e98dbf added. We now have 1 listener(s)
,08-24 14:03:44.096  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-24 14:03:44.096  6407  6517 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-24 14:03:44.096  6407  6517 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:03:44.096  6407  6517 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:03:44.106  6407  6517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e80a3ea added. We now have 1 listener(s)
08-24 14:03:44.106  6407  6517 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:03:44.106  6407  6517 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-24 14:03:44.116  6407  6517 D BluetoothAdapter: STATE_ON
,08-24 14:03:44.116  6407  6517 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:03:44.116  6407  6517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:03:44.116  6407  6517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:03:44.116  6407  6517 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:03:44.116  6407  6517 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:03:44.116  6407  6407 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:03:44.116  6407  6407 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:03:44.136  6407  6407 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:03:44.226  6502  6521 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-24 14:03:44.226  6502  6521 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:03:44.226  6502  6521 I GAv4    :   adb logcat -s GAv4
,08-24 14:03:44.246  6502  6521 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 14:03:44.256   776  1728 V AlarmManager:  remove PendingIntent] PendingIntent{fb7fc08: PendingIntentRecord{650efa1 com.google.android.apps.docs broadcastIntent}}
,08-24 14:03:44.256  6502  6521 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:03:44.256  6502  6521 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:03:44.266  6502  6527 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:03:44.336  6502  6502 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-24 14:03:44.336  6502  6502 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-24 14:03:44.356  6502  6521 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-24 14:03:44.356  6502  6521 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-24 14:03:44.356  6502  6521 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-24 14:03:44.356  6502  6521 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-24 14:03:44.396  6533  6533 E Zygote  : v2
08-24 14:03:44.396  6533  6533 I libpersona: KNOX_SDCARD checking this for 10098
08-24 14:03:44.396  6533  6533 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.396   776  1580 I ActivityManager: Start proc 6533:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-24 14:03:44.396  6533  6533 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 14:03:44.396  6533  6533 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:44.406   776  1580 I ActivityManager: Killing 5517:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-24 14:03:44.406  6533  6533 E Zygote  : accessInfo : 0
,08-24 14:03:44.406  6533  6533 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-24 14:03:44.426  6533  6533 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.426  6533  6533 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.436   776  2569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46be4dd 6533:com.sec.android.automotive.drivelink/u0a98}
,08-24 14:03:44.446   776  1739 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-24 14:03:44.446  6533  6533 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 14:03:44.446  1454  1454 D Recents : onTaskStackChanged
,08-24 14:03:44.456  1454  1454 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 14:03:44.466  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 14:03:44.466  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 14:03:44.476  6533  6533 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-24 14:03:44.506  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 14:03:44.516  6533  6533 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 14:03:44.526   776  1660 V AlarmManager:  remove PendingIntent] PendingIntent{12bd295: PendingIntentRecord{e103faa com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 14:03:44.536  6533  6533 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-24 14:03:44.536  6533  6549 I GMPM    : App measurement is starting up
,08-24 14:03:44.546  6533  6549 E GMPM    : getGoogleAppId failed with status: 10
,08-24 14:03:44.546  6533  6549 E GMPM    : Uploading is not possible. App measurement disabled
,08-24 14:03:44.546   776  1581 V AlarmManager:  remove PendingIntent] PendingIntent{7cd179b: PendingIntentRecord{e103faa com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 14:03:44.556  6533  6533 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-24 14:03:44.566  6533  6533 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-24 14:03:44.566  6502  6522 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 14:03:44.616   776  1581 I ActivityManager: Start proc 6555:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-24 14:03:44.616   776  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-24 14:03:44.616  6555  6555 E Zygote  : v2
08-24 14:03:44.616  6555  6555 I libpersona: KNOX_SDCARD checking this for 10032
08-24 14:03:44.616  6555  6555 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.616  6555  6555 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:44.616  6555  6555 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:44.616  6555  6555 E Zygote  : accessInfo : 0
,08-24 14:03:44.616  6555  6555 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-24 14:03:44.636  6502  6522 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-24 14:03:44.636  6555  6555 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.636  6555  6555 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.646   776  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-24 14:03:44.646  6555  6555 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-24 14:03:44.656  6502  6522 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 14:03:44.656  6502  6522 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-24 14:03:44.666  6502  6522 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 14:03:44.666  6555  6555 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-24 14:03:44.696  6502  6522 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:03:44.756  6533  6533 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-24 14:03:44.756  6533  6533 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-24 14:03:44.766  6533  6533 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-24 14:03:44.766  6555  6555 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-24 14:03:44.786  6533  6533 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 24 14:03:44 GMT+02:00 2016
,08-24 14:03:44.786  6555  6555 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-24 14:03:44.786  6533  6533 D DialogFlow: initQueue()
,08-24 14:03:44.796  6569  6569 E Zygote  : v2
08-24 14:03:44.796  6569  6569 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:44.796  6569  6569 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:44.796   776  1728 I ActivityManager: Start proc 6569:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-24 14:03:44.796  6569  6569 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:44.796  6569  6569 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:44.796  6569  6569 E Zygote  : accessInfo : 0
,08-24 14:03:44.796   776  1728 I ActivityManager: Killing 5118:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-24 14:03:44.796   776  1728 I ActivityManager: Killing 5145:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-24 14:03:44.826   776  1294 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-24 14:03:44.826  6569  6569 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.826  6569  6569 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.836   776  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d1a02 6569:com.samsung.android.app.filterinstaller/1000}
,08-24 14:03:44.836   776  1728 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-24 14:03:44.846  6569  6569 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-24 14:03:44.856  6569  6569 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-24 14:03:44.856  6569  6569 E FilterPackageIntentReceiver: This package is not a effect filter
,08-24 14:03:44.866   776  1739 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-24 14:03:44.876  6585  6585 E Zygote  : v2
,08-24 14:03:44.876  6585  6585 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:44.876  6585  6585 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:44.876   776   789 I ActivityManager: Start proc 6585:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-24 14:03:44.876  6585  6585 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 14:03:44.876  6585  6585 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:44.876   776   789 I ActivityManager: Killing 5167:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-24 14:03:44.876  6585  6585 E Zygote  : accessInfo : 0
,08-24 14:03:44.896   776   790 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-24 14:03:44.896  6585  6585 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.906  6585  6585 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.906   776  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a78b05 6585:com.samsung.helphub/1000}
,08-24 14:03:44.906  6555  6555 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-24 14:03:44.916  6555  6555 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-24 14:03:44.916  6585  6585 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-24 14:03:44.916  6555  6555 D DialogFlow: initQueue()
,08-24 14:03:44.936  6585  6585 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-24 14:03:44.986  6597  6597 E Zygote  : v2
,08-24 14:03:44.986  6597  6597 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:44.986  6597  6597 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.986  6597  6597 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 14:03:44.986   776  1740 I ActivityManager: Start proc 6597:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-24 14:03:44.986  6597  6597 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:44.986   776  1740 I ActivityManager: Killing 4720:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-24 14:03:44.986  6597  6597 E Zygote  : accessInfo : 0
,08-24 14:03:45.006   776  1581 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-24 14:03:45.006  6597  6597 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.006  6597  6597 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.016   776   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68fe75a 6597:com.samsung.android.app.mirrorlink/1000}
,08-24 14:03:45.026  6597  6597 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-24 14:03:45.046  6597  6597 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-24 14:03:45.106  6597  6597 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-24 14:03:45.106  6597  6597 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-24 14:03:45.106   776  1581 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3103789 5716:com.google.android.apps.plus/u0a134}
,08-24 14:03:45.126   776   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3103789 5716:com.google.android.apps.plus/u0a134}
,08-24 14:03:45.136   776  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3103789 5716:com.google.android.apps.plus/u0a134}
,08-24 14:03:45.176   776  1739 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-24 14:03:45.176   776  1580 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-24 14:03:45.176  6407  6518 W jxcore-log: Initializing JXcore engine
,08-24 14:03:45.176  6407  6518 W jxcore-log: JXcore engine is ready
,08-24 14:03:45.186   776  1624 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-24 14:03:45.186   776  1294 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-24 14:03:45.186   776  1660 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-24 14:03:45.196   776  1727 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-24 14:03:45.196   776  2569 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-24 14:03:45.196   776  1411 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-24 14:03:45.226  6611  6611 E Zygote  : v2
08-24 14:03:45.226  6611  6611 I libpersona: KNOX_SDCARD checking this for 10165
08-24 14:03:45.226  6611  6611 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:45.226  6611  6611 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:45.226  6611  6611 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:45.226   776  1728 I ActivityManager: Start proc 6611:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-24 14:03:45.226   776  1321 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 14:03:45.226  6611  6611 E Zygote  : accessInfo : 0
,08-24 14:03:45.226  6611  6611 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-24 14:03:45.226  2460  2460 E audit   : type=1400 msg=audit(1472040225.226:287): avc:  denied  { ioctl } for  pid=6518 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 14:03:45.226  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:45.226  2460  2460 E audit   : type=1300 msg=audit(1472040225.226:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=97c5f3c8 items=0 ppid=350 ppcomm=main pid=6518 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 14:03:45.226  2460  2460 E audit   : type=1327 msg=audit(1472040225.226:287): proctitle="com.test.thalitest"
08-24 14:03:45.226  2460  2460 E audit   : type=1320 msg=audit(1472040225.226:287): 
08-24 14:03:45.226  2460  2460 E audit   : type=1400 msg=audit(1472040225.226:288): avc:  denied  { ioctl } for  pid=6518 comm="Thread-899" path="socket:[39417]" dev="sockfs" ino=39417 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 14:03:45.226  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:45.226  2460  2460 E audit   : type=1300 msg=audit(1472040225.226:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=97c5f3c8 items=0 ppid=350 ppcomm=main pid=6518 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 14:03:45.226  2460  2460 E audit   : type=1327 msg=audit(1472040225.226:288): proctitle="com.test.thalitest"
08-24 14:03:45.226  2460  2460 E audit   : type=1320 msg=audit(1472040225.226:288): 
,08-24 14:03:45.226   776  1321 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 14:03:45.236   776  1660 I ActivityManager: Killing 5070:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-24 14:03:45.236  6407  6518 W jxcore-log: Starting JXcore engine
,08-24 14:03:45.246  6611  6611 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:45.246  6611  6611 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.256   776  2569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f9ad281 6611:com.sec.kidsplat.installer/u0a165}
,08-24 14:03:45.266  6611  6611 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-24 14:03:45.266   776  1728 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-24 14:03:45.276  6611  6611 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-24 14:03:45.286   776  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f9ad281 6611:com.sec.kidsplat.installer/u0a165}
,08-24 14:03:45.296  6611  6611 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
08-24 14:03:45.306   776   790 I ActivityManager: Start proc 6623:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-24 14:03:45.306  6623  6623 E Zygote  : v2
08-24 14:03:45.306  6623  6623 I libpersona: KNOX_SDCARD checking this for 10142
08-24 14:03:45.306  6623  6623 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.306  6623  6623 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 14:03:45.306  6623  6623 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 14:03:45.306  6623  6623 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:45.306  6623  6623 E Zygote  : accessInfo : 64
08-24 14:03:45.306  6623  6623 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 14:03:45.306  6623  6623 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-24 14:03:45.306  6623  6623 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-24 14:03:45.306   776   790 I ActivityManager: Killing 5355:com.policydm/1000 (adj 15): DHA:empty #37
,08-24 14:03:45.326  6407  6518 W jxcore-log: Platform android
08-24 14:03:45.326  6407  6518 W jxcore-log: 
08-24 14:03:45.326  6407  6518 W jxcore-log: Process ARCH arm
08-24 14:03:45.326  6407  6518 W jxcore-log: 
,08-24 14:03:45.336   776  1581 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-24 14:03:45.336  6623  6623 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:45.336  6623  6623 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.346  6374  6374 D AASAservice: onDestroy()
,08-24 14:03:45.356   776  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4a00767 6623:com.sec.android.app.sbrowser/u0a142}
,08-24 14:03:45.356  6374  6374 I art     : System.exit called, status: 80
08-24 14:03:45.356  6374  6374 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-24 14:03:45.356  6623  6623 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 14:03:45.376   776  1294 I ActivityManager: Process com.samsung.aasaservice (pid 6374)(adj 0) has died(72,752)
,08-24 14:03:45.376   776  1294 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-24 14:03:45.376  6623  6623 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-24 14:03:45.396  6623  6623 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 14:03:45.396  6623  6623 D ManifestProvider: onCreate()
,08-24 14:03:45.406  6623  6623 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-24 14:03:45.406  6623  6623 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 14:03:45.406  6623  6623 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-24 14:03:45.406  6623  6623 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-24 14:03:45.416   350   350 I Zygote  : Process 6374 exited cleanly (80)
,08-24 14:03:45.416  6623  6623 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-24 14:03:45.416  6623  6623 D [MM]MHDataBaseProvider: onCreate()
,08-24 14:03:45.426  6387  6387 I Mms/MmsApp:  start initViewCache mms
,08-24 14:03:45.436  6623  6623 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@9896e85)
,08-24 14:03:45.486   776  2572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03c508 2043:com.google.android.gms.persistent/u0a11}
,08-24 14:03:45.496   776  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ba43b 4426:com.google.android.gms/u0a11}
,08-24 14:03:45.506  4426  6641 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 14:03:45.516  4426  6640 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-24 14:03:45.516  4426  4426 D AsyncTaskServiceImpl: Submit a task: nzm
,08-24 14:03:45.526  4426  6641 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 14:03:45.526  4426  5069 D nzm     : Processing package: com.test.thalitest
,08-24 14:03:45.526  6407  6518 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:03:45.526  6407  6518 I jxcore-log: 
,08-24 14:03:45.526  6407  6518 W jxcore-log: JXcore engine is started
,08-24 14:03:45.536   776  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03c508 2043:com.google.android.gms.persistent/u0a11}
,08-24 14:03:45.536  6407  6517 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:03:45.536  6407  6407 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:03:45.556   776  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ba43b 4426:com.google.android.gms/u0a11}
,08-24 14:03:45.556  4426  4426 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 14:03:45.556  4426  6641 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 14:03:45.566  4426  5069 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-24 14:03:45.566  4426  5069 D nzm     : Found info for package com.test.thalitest in db.
,08-24 14:03:45.576  4426  6641 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 14:03:45.656   776  2572 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfaa923 5750:com.android.vending/u0a29}
,08-24 14:03:45.686   776  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-24 14:03:45.706  5750  5750 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-24 14:03:45.706   776  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a90131 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43565df 6116:com.sec.android.app.samsungapps/u0a39}
,08-24 14:03:45.716  6387  6387 D Mms/BubbleViewCache: fillCache bubble = 4
,08-24 14:03:45.726  2043  2043 D WearableService: callingUid 10011, callindPid: 2043
,08-24 14:03:45.726  5750  5750 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-24 14:03:45.736   776  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{389c162 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03c508 2043:com.google.android.gms.persistent/u0a11}
,08-24 14:03:45.746   776  1660 V AlarmManager:  remove PendingIntent] PendingIntent{e5f62f3: PendingIntentRecord{4263dce com.google.android.gms broadcastIntent}}
,08-24 14:03:45.756   776  1580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9b55bb0 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfaa923 5750:com.android.vending/u0a29}
,08-24 14:03:45.766   776  1294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc691ae u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b88bd05 5802:com.sec.android.app.shealth/u0a34}
,08-24 14:03:45.776   776  1294 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc691ae u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{50e6002 1904:com.sec.android.app.shealth:remote/u0a34}
,08-24 14:03:45.786  5750  5750 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:03:45.786  5750  5750 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-24 14:03:45.806  5750  6647 I Finsky  : [831] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-24 14:03:45.816  5750  5781 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 14:03:45.836   776  1728 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc691ae u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{50e6002 1904:com.sec.android.app.shealth:remote/u0a34}
,08-24 14:03:45.846  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 14:03:45.856   776  2569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7623d6b u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e03c508 2043:com.google.android.gms.persistent/u0a11}
,08-24 14:03:45.856  5750  6648 I PlayCommon: [832] com.google.android.play.a.w.a(27553): Starting to flush logs
08-24 14:03:45.856  5750  6648 I PlayCommon: [832] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-24 14:03:45.896  5750  5781 I PlayCommon: [801] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-24 14:03:45.896  5750  5781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 14:03:45.896  5750  5781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 14:03:45.896   306  1191 D EnterpriseController: netId is 0
08-24 14:03:45.896   306  1191 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-24 14:03:45.936  6555  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 14:03:45.936  6555  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 14:03:45.956  6555  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 14:03:45.956  6555  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 14:03:45.956  6555  6583 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-24 14:03:45.966  6555  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 14:03:45.966  6555  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 14:03:46.146  5750  5781 I PlayCommon: [801] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-24 14:03:46.146  5750  5781 I PlayCommon: [801] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-24 14:03:46.146  5750  5781 I PlayCommon: [801] com.google.android.play.a.al.e(732): No file ready to send
,08-24 14:03:46.716  4426  4983 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-24 14:03:46.816  4426  4983 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 14:03:46.816  4426  4983 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 14:03:46.826  4426  4983 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-24 14:03:48.166   776  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:49.076   776  3496 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 14:03:49.576  3564  3564 D FactoryTest: User mode
,08-24 14:03:49.586  3564  3564 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 14:03:49.586  3564  3564 D MTPRx   : still no open session command from host, so toast
,08-24 14:03:49.586   776  1739 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 14:03:49.596   776  1739 D ActivityManager: mDVFSHelper.acquire()
,08-24 14:03:49.596   776  1739 V WindowManager: addAppToken: AppWindowToken{ea6eee3 token=Token{da94712 ActivityRecord{c80369d u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,08-24 14:03:49.596   776  1739 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-24 14:03:49.606   776   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-24 14:03:49.626   776  1739 D InputDispatcher: Focused application set to: xxxx
,08-24 14:03:49.626   776  1739 D InputDispatcher: Focus left window: 6407
,08-24 14:03:49.626   776   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:776 uid:1000
,08-24 14:03:49.626   776   907 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:49.626   776   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:776 uid:1000
08-24 14:03:49.626   776   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 14:03:49.636   776  3496 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 14:03:49.646  3564  3564 E MTPRx   : started activity for popup
,08-24 14:03:49.646  3564  3564 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 14:03:49.646  3564  3564 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 14:03:49.666  3564  3564 D MTPUSBConnection: onCreate in USBConnection
,08-24 14:03:49.666  3564  3564 V MTPUSBConnection: Registering broadcast receiver.
,08-24 14:03:49.666  3564  3564 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-24 14:03:49.666   776  1740 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-24 14:03:49.716  3564  3564 D TAG     : dev.kiessupport is : TRUE
,08-24 14:03:49.746  3564  3564 D SecWifiDisplayUtil: Metadata value : none
,08-24 14:03:49.746  3564  3564 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7e1d8d9 V.E...... R.....I. 0,0-0,0}
,08-24 14:03:49.766  3564  6679 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 14:03:49.766   776  1294 D ISSUE_DEBUG: InputChannelName : 1b1575b com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 14:03:49.766   776  1294 D InputDispatcher: Focus entered window: 3564
,08-24 14:03:49.766   776   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1b1575b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-24 14:03:49.766  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-24 14:03:49.766   776   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:776 uid:1000
,08-24 14:03:49.766   776   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:49.766   776   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:776 uid:1000
08-24 14:03:49.766   776   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 14:03:49.776  3564  3564 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{774ca11 I.E...... R.....I. 0,0-0,0}
,08-24 14:03:49.776   776  1727 D ISSUE_DEBUG: InputChannelName : 1bba8d1 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 14:03:49.776   776   789 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-24 14:03:49.776   776   789 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 14:03:49.776   776   776 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 14:03:49.786   776   776 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 14:03:49.786   776   776 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-24 14:03:49.806   294   294 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-24 14:03:49.826  3564  6679 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 14:03:49.826  3564  6679 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 14:03:49.826  3564  6679 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 14:03:49.826  3564  6679 I Adreno-EGL: Local Branch: ss
08-24 14:03:49.826  3564  6679 I Adreno-EGL: Remote Branch: 
08-24 14:03:49.826  3564  6679 I Adreno-EGL: Local Patches: 
08-24 14:03:49.826  3564  6679 I Adreno-EGL: Reconstruct Branch: 
,08-24 14:03:49.836  3564  6679 D libEGL  : eglInitialize EGLDisplay = 0x9f0737c4
08-24 14:03:49.836  3564  6679 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 14:03:49.866   294   294 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-24 14:03:49.886  3564  3564 V ActivityThread: updateVisibility : ActivityRecord{b4881e4 token=android.os.BinderProxy@c11a29e {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-24 14:03:49.886  3564  3564 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 14:03:49.976   776  1728 V WindowStateAnimator: Finishing drawing window Window{1b1575b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 14:03:49.976  3564  3564 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 14:03:49.976   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8e6364
,08-24 14:03:49.976   776  1581 V WindowStateAnimator: Finishing drawing window Window{1bba8d1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 14:03:49.976  3564  3564 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-24 14:03:49.976  3564  3564 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-24 14:03:49.986   776   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 14:03:49.986   776   776 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 14:03:49.986   776   776 I KnoxTimeoutHandler: SD activityfalse
,08-24 14:03:49.986   776   907 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +366ms (total +389ms)
,08-24 14:03:49.986   776   907 D ActivityManager: mDVFSHelper.release()
08-24 14:03:49.986   776   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c80369d u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108417
,08-24 14:03:49.996   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8e6364
,08-24 14:03:49.996   776   790 V WindowStateAnimator: Finishing drawing window Window{1b1575b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 14:03:49.996   776  1411 V WindowStateAnimator: Finishing drawing window Window{1bba8d1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-24 14:03:49.996  3564  3564 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c11a29e time:108422
,08-24 14:03:50.006   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8e6364
,08-24 14:03:50.636   776  3498 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 14:03:50.786  1454  1454 D Recents : onTaskStackChanged
08-24 14:03:50.796  1454  1454 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-24 14:03:51.676   776  1236 V AlarmManager: Expired Alarm result :4
08-24 14:03:51.696   776  1321 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-24 14:03:51.696   776  1321 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-24 14:03:51.696   776  1581 V AlarmManager:  remove PendingIntent] PendingIntent{3a40e37: PendingIntentRecord{67c7079 com.google.android.gms broadcastIntent}}
08-24 14:03:51.746   776  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 14:03:51.746   776  1739 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 14:03:51.746   776  1739 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-24 14:03:51.746   776  1739 D BatteryService: stay LED for charging
08-24 14:03:51.746   776   776 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 14:03:51.746   776   776 I MotionRecognitionService: Plugged
08-24 14:03:51.746   776   776 D MotionRecognitionService:   cableConnection= 1
08-24 14:03:51.746   776   776 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 14:03:51.746   776   776 D MotionRecognitionService: skip setTransmitPower. 
08-24 14:03:51.746  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 14:03:51.756  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 14:03:51.756  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 14:03:51.756  2451  2451 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 14:03:51.756  2451  2905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 14:03:51.776  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:03:51.776  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:03:51.776  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:51.826   776  3496 D SSRM:n  : SIOP:: AP = 480, PST = 461, CUR = 350, LCD = 0
,08-24 14:03:52.216   776   934 D PackageManager: [MSG] MCS_UNBIND
,08-24 14:03:52.236   776  1294 I ActivityManager: Killing 5594:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-24 14:03:52.256  6407  6518 E jxcore  : Error!: syntax error
08-24 14:03:52.256  6407  6518 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:03:52.266  6407  6407 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-24 14:03:52.266  6407  6407 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:03:52.266   776  1728 I ActivityManager: Killing 4832:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
08-24 14:03:52.276  6407  6407 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 14:03:52.276  6407  6407 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-24 14:03:52.276  6407  6407 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:03:52.276  6407  6407 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:03:52.276  6407  6407 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:03:52.276  6407  6407 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:03:52.276  6407  6407 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e98dbf removed from the list
08-24 14:03:52.276  6407  6407 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:03:52.286   776  1660 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
08-24 14:03:52.286  6407  6517 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,08-24 14:03:52.286  6407  6407 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e80a3ea removed from the list
,08-24 14:03:52.286  6407  6407 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:03:52.286  6407  6407 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-24 14:03:52.286  6407  6407 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 14:03:52.286  6407  6407 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-24 14:03:52.296  6407  6407 D ViewRootImpl: #3 mView = null
,08-24 14:03:52.296   294   351 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
,08-24 14:03:52.296   294   354 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
,08-24 14:03:52.306   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e63a4
,08-24 14:03:52.306  6407  6407 D cr_Ime  : [ImeAdapter.java:587] detach
,08-24 14:03:52.326   776  1624 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-24 14:03:52.666   776   934 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 14:03:52.686   776   934 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 14:03:53.166   776  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:53.196  2460  2460 E audit   : type=1400 msg=audit(1472040233.196:289): avc:  denied  { execmod } for  pid=6707 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:53.196  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-24 14:03:53.196  2460  2460 E audit   : type=1300 msg=audit(1472040233.196:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbb000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6707 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:53.196  2460  2460 E audit   : type=1327 msg=audit(1472040233.196:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 14:03:53.196  2460  2460 E audit   : type=1320 msg=audit(1472040233.196:289): 
,08-24 14:03:53.256  2460  2460 E audit   : type=1400 msg=audit(1472040233.256:290): avc:  denied  { execmod } for  pid=6707 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:53.256  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:53.256  2460  2460 E audit   : type=1300 msg=audit(1472040233.256:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7a000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6707 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:53.256  2460  2460 E audit   : type=1327 msg=audit(1472040233.256:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 14:03:53.256  2460  2460 E audit   : type=1320 msg=audit(1472040233.256:290): 
,08-24 14:03:53.306  2460  2460 E audit   : type=1400 msg=audit(1472040233.306:291): avc:  denied  { execmod } for  pid=6707 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 14:03:53.306  2460  2460 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 14:03:53.306  2460  2460 E audit   : type=1300 msg=audit(1472040233.306:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3650 ppcomm=adbd pid=6707 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 14:03:53.306  2460  2460 E audit   : type=1327 msg=audit(1472040233.306:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 14:03:53.306  2460  2460 E audit   : type=1320 msg=audit(1472040233.306:291): 
,08-24 14:03:53.306  6707  6707 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 14:03:53.316  6707  6707 D AndroidRuntime: CheckJNI is OFF
,08-24 14:03:53.316  6707  6707 D AndroidRuntime: readGMSProperty: start
08-24 14:03:53.316  6707  6707 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:03:53.316  6707  6707 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:53.316  6707  6707 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:53.316  6707  6707 D AndroidRuntime: readGMSProperty: end
08-24 14:03:53.316  6707  6707 D AndroidRuntime: addProductProperty: start
,08-24 14:03:53.326  6707  6707 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 14:03:53.326  6707  6707 W art     : af124000-b204a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:53.326  6707  6707 W art     : b204a000-b42b9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:53.326  6707  6707 W art     : b42b9000-b42ba000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 14:03:53.326  6707  6707 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 14:03:53.326  6707  6707 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 14:03:53.326  6707  6707 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 14:03:53.326  6707  6707 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 14:03:53.326  6707  6707 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 14:03:53.326  6707  6707 W art     : b4848000-b484b000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:53.326  6707  6707 W art     : b484b000-b484c000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:53.326  6707  6707 W art     : b484c000-b484d000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 14:03:53.326  6707  6707 W art     : b484d000-b484e000 r--p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b484e000-b486e000 r--s 00000000 00:0b 7184       /dev/__properties__
,08-24 14:03:53.326  6707  6707 W art     : b486e000-b527f000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:53.326  6707  6707 W art     : b527f000-b5280000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5280000-b52c9000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:53.326  6707  6707 W art     : b52c9000-b52ca000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 14:03:53.326  6707  6707 W art     : b52ca000-b52d2000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b52d2000-b52d3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b52d3000-b5308000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:53.326  6707  6707 W art     : b5308000-b5309000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5309000-b530a000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:53.326  6707  6707 W art     : b530a000-b530b000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 14:03:53.326  6707  6707 W art     : b530b000-b5363000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:53.326  6707  6707 W art     : b5363000-b5364000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5364000-b5365000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:53.326  6707  6707 W art     : b5365000-b5366000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 14:03:53.326  6707  6707 W art     : b5367000-b536d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:53.326  6707  6707 W art     : b536d000-b536e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:53.326  6707  6707 W art     : b536e000-b536f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 14:03:53.326  6707  6707 W art     : b536f000-b5371000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5372000-b537c000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:53.326  6707  6707 W art     : b537c000-b537f000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:53.326  6707  6707 W art     : b537f000-b5380000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 14:03:53.326  6707  6707 W art     : b5381000-b5398000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:53.326  6707  6707 W art     : b5398000-b5399000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5399000-b539a000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:53.326  6707  6707 W art     : b539a000-b539b000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 14:03:53.326  6707  6707 W art     : b539c000-b53a6000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:53.326  6707  6707 W art     : b53a6000-b53a7000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:53.326  6707  6707 W art     : b53a7000-b53a8000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 14:03:53.326  6707  6707 W art     : b53a8000-b53ac000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:53.326  6707  6707 W art     : b53ac000-b53ad000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:53.326  6707  6707 W art     : b53ad000-b53ae000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 14:03:53.326  6707  6707 W art     : b53ae000-b53c4000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:53.326  6707  6707 W art     : b53c4000-b53c5000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:53.326  6707  6707 W art     : b53c5000-b53c6000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 14:03:53.326  6707  6707 W art     : b53c6000-b53d3000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:53.326  6707  6707 W art     : b53d3000-b53d4000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:53.326  6707  6707 W art     : b53d4000-b53d5000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 14:03:53.326  6707  6707 W art     : b53d5000-b5435000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 14:03:53.326  6707  6707 W art     : b5435000-b5438000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 14:03:53.326  6707  6707 W art     : b5438000-b543c000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b543c000-b549d000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 14:03:53.326  6707  6707 W art     : b549d000-b549e000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 14:03:53.326  6707  6707 W art     : b549e000-b54ed000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:53.326  6707  6707 W art     : b54ed000-b54ef000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:53.326  6707  6707 W art     : b54ef000-b54f0000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 14:03:53.326  6707  6707 W art     : b54f0000-b54f1000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b54f1000-b54f8000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 14:03:53.326  6707  6707 W art     : b54f8000-b54f9000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 14:03:53.326  6707  6707 W art     : b54f9000-b54fa000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-24 14:03:53.326  6707  6707 W art     : avc_common.so
08-24 14:03:53.326  6707  6707 W art     : b54fb000-b54fe000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 14:03:53.326  6707  6707 W art     : b54fe000-b54ff000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 14:03:53.326  6707  6707 W art     : b54ff000-b5500000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-24 14:03:53.326  6707  6707 W art     : enc_common.so
08-24 14:03:53.326  6707  6707 W art     : b5501000-b5505000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 14:03:53.326  6707  6707 W art     : b5505000-b5506000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5506000-b5507000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 14:03:53.326  6707  6707 W art     : b5507000-b5508000 rw-p 00005000 b3:17 2510       /syste
08-24 14:03:53.326  6707  6707 W art     : m/lib/libpowermanager.so
08-24 14:03:53.326  6707  6707 W art     : b5509000-b5526000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:53.326  6707  6707 W art     : b5526000-b5527000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:53.326  6707  6707 W art     : b5527000-b5528000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 14:03:53.326  6707  6707 W art     : b5529000-b552e000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:53.326  6707  6707 W art     : b552e000-b552f000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:53.326  6707  6707 W art     : b552f000-b5530000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 14:03:53.326  6707  6707 W art     : b5531000-b5562000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:53.326  6707  6707 W art     : b5562000-b5565000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:53.326  6707  6707 W art     : b5565000-b5566000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 14:03:53.326  6707  6707 W art     : b5567000-b55a2000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 14:03:53.326  6707  6707 W art     : b55a2000-b55a3000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 14:03:53.326  6707  6707 W art     : b55a3000-b55a4000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 14:03:53.326  6707  6707 W art     : b55a5000-b55ac000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:53.326  6707  6707 W art     : b55ac000-b55ad000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b55ad000-b55ae000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:53.326  6707  6707 W art     : b55ae000-b55af000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 14:03:53.326  6707  6707 W art     : b55af000-b55b0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b55b0000-b55c7000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:53.326  6707  6707 W art     : b55c7000-b55c8000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b55c8000-b55cb000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:53.326  6707  6707 W art     : b55cb000-b55cc000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 14:03:53.326  6707  6707 W art     : b55cc000-b55eb000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:53.326  6707  6707 W art     : b55eb000-b55ec000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:53.326  6707  6707 W art     : b55ec000-b55ed000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 14:03:53.326  6707  6707 W art     : b55ed000-b562b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:53.326  6707  6707 W art     : b562b000-b562c000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b562c000-b562e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:53.326  6707  6707 W art     : b562e000-b562f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 14:03:53.326  6707  6707 W art     : b5630000-b5637000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:53.326  6707  6707 W art     : b5637000-b5638000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:53.326  6707  6707 W art     : b5638000-b5639000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 14:03:53.326  6707  6707 W art     : b563a000-b563d000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:53.326  6707  6707 W art     : b563d000-b563e000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:53.326  6707  6707 W art     : b563e000-b563f000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 14:03:53.326  6707  6707 W art     : b563f000-b5645000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:53.326  6707  6707 W art     : b5645000-b5646000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5646000-b5647000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:53.326  6707  6707 W art     : b5647000-b5648000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 14:03:53.326  6707  6707 W art     : b5648000-b5651000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:53.326  6707  6707 W art     : b5651000-b5652000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:53.326  6707  6707 W art     : b5652000-b5653000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 14:03:53.326  6707  6707 W art     : b5653000-b56e4000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:53.326  6707  6707 W art     : b56e4000-b56e5000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b56e5000-b56f0000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:53.326  6707  6707 W art     : b56f0000-b56f1000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 14:03:53.326  6707  6707 W art     : b56f2000-b5704000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:53.326  6707  6707 W art     : b5704000-b5705000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:53.326  6707  6707 W art     : b5705000-b5706000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 14:03:53.326  6707  6707 W art     : b5707000-b570c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:53.326  6707  6707 W art     : b570c000-b570d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:53.326  6707  6707 W art     : b570d000-b570e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 14:03:53.326  6707  6707 W art     : b570f000-b577c000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:53.326  6707  6707 W art     : b577c000-b577d000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b577d000-b577f000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:53.326  6707  6707 W art     : b577f000-b5780000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 14:03:53.326  6707  6707 W art     : b5780000-b5781000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5781000-b5788000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:53.326  6707  6707 W art     : b5788000-b5789000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:53.326  6707  6707 W art     : b5789000-b578a000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 14:03:53.326  6707  6707 W art     : b578b000-b580b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:53.326  6707  6707 W art     : b580b000-b580c000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b580c000-b580d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:53.326  6707  6707 W art     : b580d000-b580e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 14:03:53.326  6707  6707 W art     : b580e000-b5825000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5825000-b585c000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 14:03:53.326  6707  6707 W art     : ib/libqc-opt.so
08-24 14:03:53.326  6707  6707 W art     : b585c000-b585d000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 14:03:53.326  6707  6707 W art     : b585d000-b585e000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 14:03:53.326  6707  6707 W art     : b585e000-b587a000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:53.326  6707  6707 W art     : b587a000-b587b000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:53.326  6707  6707 W art     : b587b000-b587c000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 14:03:53.326  6707  6707 W art     : b587d000-b58de000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:53.326  6707  6707 W art     : b58de000-b58e0000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:53.326  6707  6707 W art     : b58e0000-b58e1000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 14:03:53.326  6707  6707 W art     : b58e2000-b5909000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:53.326  6707  6707 W art     : b5909000-b590a000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b590a000-b590b000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:53.326  6707  6707 W art     : b590b000-b590c000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 14:03:53.326  6707  6707 W art     : b590d000-b5915000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:53.326  6707  6707 W art     : b5915000-b5917000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:53.326  6707  6707 W art     : b5917000-b5918000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 14:03:53.326  6707  6707 W art     : b5919000-b591c000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:53.326  6707  6707 W art     : b591c000-b591d000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:53.326  6707  6707 W art     : b591d000-b591e000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 14:03:53.326  6707  6707 W art     : b591e000-b5922000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:53.326  6707  6707 W art     : b5922000-b5923000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5923000-b5924000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:53.326  6707  6707 W art     : b5924000-b5925000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 14:03:53.326  6707  6707 W art     : b5925000-b5935000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:53.326  6707  6707 W art     : b5935000-b5936000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:53.326  6707  6707 W art     : b5936000-b5937000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 14:03:53.326  6707  6707 W art     : b5937000-b597d000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b597d000-b5986000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:53.326  6707  6707 W art     : b5986000-b5987000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:53.326  6707  6707 W art     : b5987000-b5988000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 14:03:53.326  6707  6707 W art     : b5989000-b598e000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:53.326  6707  6707 W art     : b598e000-b598f000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:53.326  6707  6707 W art     : b598f000-b5990000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 14:03:53.326  6707  6707 W art     : b5990000-b5993000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 14:03:53.326  6707  6707 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5994000-b5995000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-24 14:03:53.326  6707  6707 W art     : b5995000-b5996000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 14:03:53.326  6707  6707 W art     : b5997000-b59af000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:53.326  6707  6707 W art     : b59af000-b59b0000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b59b0000-b59b1000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:53.326  6707  6707 W art     : b59b1000-b59b2000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 14:03:53.326  6707  6707 W art     : b59b3000-b5b4d000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:53.326  6707  6707 W art     : b5b4d000-b5b4e000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5b4e000-b5b5b000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:53.326  6707  6707 W art     : b5b5b000-b5b5c000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 14:03:53.326  6707  6707 W art     : b5b5c000-b5b60000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:53.326  6707  6707 W art     : b5b60000-b5b61000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5b61000-b5b62000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:53.326  6707  6707 W art     : b5b62000-b5b63000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 14:03:53.326  6707  6707 W art     : b5b63000-b5b76000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:53.326  6707  6707 W art     : b5b76000-b5b77000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:53.326  6707  6707 W art     : b5b77000-b5b78000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 14:03:53.326  6707  6707 W art     : b5b78000-b5b79000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:53.326  6707  6707 W art     : b5b79000-b5bc4000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:53.326  6707  6707 W art     : b5bc4000-b5bc5000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:53.326  6707  6707 W art     : b5bc5000-b5bc6000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 14:03:53.326  6707  6707 W art     : b5bc6000-b5bc8000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5bc9000-b5bda000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:53.326  6707  6707 W art     : b5bda000-b5bdb000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5bdb000-b5bdc000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:53.326  6707  6707 W art     : b5bdc000-b5bdd000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 14:03:53.326  6707  6707 W art     : b5bde000-b5be8000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:53.326  6707  6707 W art     : b5be8000-b5bea000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:53.326  6707  6707 W art     : b5bea000-b5beb000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 14:03:53.326  6707  6707 W art     : b5beb000-b5c04000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:53.326  6707  6707 W art     : b5c04000-b5c05000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:53.326  6707  6707 W art     : b5c05000-b5c08000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 14:03:53.326  6707  6707 W art     : b5c08000-b5c0c000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5c0c000-b5c80000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:53.326  6707  6707 W art     : b5c80000-b5c81000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5c81000-b5c84000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:53.326  6707  6707 W art     : b5c84000-b5c85000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 14:03:53.326  6707  6707 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5c86000-b5c89000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:53.326  6707  6707 W art     : b5c89000-b5c8a000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:53.326  6707  6707 W art     : b5c8a000-b5c8b000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 14:03:53.326  6707  6707 W art     : b5c8b000-b5c8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5c8c000-b5c91000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:53.326  6707  6707 W art     : b5c91000-b5c92000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:53.326  6707  6707 W art     : b5c92000-b5c93000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 14:03:53.326  6707  6707 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5c94000-b5c97000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:53.326  6707  6707 W art     : b5c97000-b5c98000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:53.326  6707  6707 W art     : b5c98000-b5c99000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 14:03:53.326  6707  6707 W art     : b5c99000-b5c9a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5c9a000-b5c9e000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:53.326  6707  6707 W art     : b5c9e000-b5c9f000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:53.326  6707  6707 W art     : b5c9f000-b5ca0000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 14:03:53.326  6707  6707 W art     : b5ca0000-b5ca1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:53.326  6707  6707 W art     : b5ca1000-b5ca5000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:53.326  6707  6707 W art     : b5ca5000-b5ca6000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:53.326  6707  6707 W art     : b5ca6000-b5ca7000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 14:03:53.326  6707  6707 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5ca8000-b5cb6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:53.326  6707  6707 W art     : b5cb6000-b5cb7000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b5cb7000-b5cb8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:53.326  6707  6707 W art     : b5cb8000-b5cb9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 14:03:53.326  6707  6707 W art     : b5cb9000-b5cc3000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:53.326  6707  6707 W art     : b5cc3000-b5cc6000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:53.326  6707  6707 W art     : b5cc6000-b5cc7000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 14:03:53.326  6707  6707 W art     : b5cc7000-b5cc8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5cc8000-b5cd2000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:53.326  6707  6707 W art     : b5cd2000-b5cd5000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:53.326  6707  6707 W art     : b5cd5000-b5cd6000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 14:03:53.326  6707  6707 W art     : b5cd6000-b5cda000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:53.326  6707  6707 W art     : b5cda000-b5cdb000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:53.326  6707  6707 W art     : b5cdb000-b5cdc000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 14:03:53.326  6707  6707 W art     : b5cdc000-b5cdd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b5cdd000-b5cea000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:53.326  6707  6707 W art     : b5cea000-b5cec000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:53.326  6707  6707 W art     : b5cec000-b5ced000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 14:03:53.326  6707  6707 W art     : b5ced000-b60ff000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:53.326  6707  6707 W art     : b60ff000-b6100000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b6100000-b6109000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:53.326  6707  6707 W art     : b6109000-b610d000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 14:03:53.326  6707  6707 W art     : b610d000-b610e000 rw-p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b610e000-b6115000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:53.326  6707  6707 W art     : b6115000-b6116000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:53.326  6707  6707 W art     : b6116000-b6117000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 14:03:53.326  6707  6707 W art     : b6117000-b6118000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b6118000-b6133000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 14:03:53.326  6707  6707 W art     : b6133000-b6134000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 14:03:53.326  6707  6707 W art     : b6134000-b6135000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 14:03:53.326  6707  6707 W art     : b6135000-b6136000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b6136000-b6182000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:53.326  6707  6707 W art     : b6182000-b6183000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b6183000-b6184000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:53.326  6707  6707 W art     : b6184000-b6185000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 14:03:53.326  6707  6707 W art     : b6185000-b6186000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b6186000-b618a000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:53.326  6707  6707 W art     : b618a000-b618b000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b618b000-b618c000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:53.326  6707  6707 W art     : b618c000-b618d000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 14:03:53.326  6707  6707 W art     : b618d000-b61c5000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:53.326  6707  6707 W art     : b61c5000-b61c6000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:53.326  6707  6707 W art     : b61c6000-b61c7000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 14:03:53.326  6707  6707 W art     : b61c7000-b61c8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.326  6707  6707 W art     : b61c8000-b6266000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:53.326  6707  6707 W art     : b6266000-b6267000 ---p 00000000 00:00 0 
08-24 14:03:53.326  6707  6707 W art     : b6267000-b6285000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:53.326  6707  6707 W art     : b6285000-b6286000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 14:03:53.326  6707  6707 W art     : b6286000-b63f9000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:53.326  6707  6707 W art     : b63f9000-b6404000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:53.326  6707  6707 W art     : b6404000-b6405000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 14:03:53.326  6707  6707 W art     : b6405000-b651c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:53.326  6707  6707 W art     : b651c000-b6527000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:53.336  6707  6707 W art     : b6527000-b6528000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 14:03:53.336  6707  6707 W art     : b6528000-b652c000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b652c000-b6550000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 14:03:53.336  6707  6707 W art     : b6550000-b6552000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 14:03:53.336  6707  6707 W art     : b6552000-b6553000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 14:03:53.336  6707  6707 W art     : b6553000-b65f9000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:53.336  6707  6707 W art     : b65f9000-b6606000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:53.336  6707  6707 W art     : b6606000-b6607000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 14:03:53.336  6707  6707 W art     : b6607000-b6608000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6608000-b665b000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:53.336  6707  6707 W art     : b665b000-b665c000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b665c000-b665d000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:53.336  6707  6707 W art     : b665d000-b665e000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 14:03:53.336  6707  6707 W art     : b665e000-b6663000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6663000-b6675000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:53.336  6707  6707 W art     : b6675000-b6676000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6676000-b6677000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:53.336  6707  6707 W art     : b6677000-b6678000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 14:03:53.336  6707  6707 W art     : b6678000-b667f000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:53.336  6707  6707 W art     : b667f000-b6680000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:53.336  6707  6707 W art     : b6680000-b6681000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 14:03:53.336  6707  6707 W art     : b6681000-b6682000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6682000-b6685000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:53.336  6707  6707 W art     : b6685000-b6686000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:53.336  6707  6707 W art     : b6686000-b6687000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 14:03:53.336  6707  6707 W art     : b6687000-b668b000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:53.336  6707  6707 W art     : b668b000-b668c000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:53.336  6707  6707 W art     : b668c000-b668d000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 14:03:53.336  6707  6707 W art     : b668d000-b669b000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:53.336  6707  6707 W art     : b669b000-b669c000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b669c000-b669d000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:53.336  6707  6707 W art     : b669d000-b669e000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 14:03:53.336  6707  6707 W art     : b669e000-b66a7000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:53.336  6707  6707 W art     : b66a7000-b66a8000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:53.336  6707  6707 W art     : b66a8000-b66a9000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 14:03:53.336  6707  6707 W art     : b66a9000-b670f000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:53.336  6707  6707 W art     : b670f000-b6710000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6710000-b6712000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:53.336  6707  6707 W art     : b6712000-b671b000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 14:03:53.336  6707  6707 W art     : b671b000-b671e000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b671e000-b67b5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:53.336  6707  6707 W art     : b67b5000-b67b7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:53.336  6707  6707 W art     : b67b7000-b67b8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 14:03:53.336  6707  6707 W art     : b67b8000-b67b9000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b67b9000-b6ada000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 14:03:53.336  6707  6707 W art     : b6ada000-b6adb000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6adb000-b6af6000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 14:03:53.336  6707  6707 W art     : b6af6000-b6afa000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 14:03:53.336  6707  6707 W art     : b6afa000-b6aff000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6aff000-b6b07000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:53.336  6707  6707 W art     : b6b07000-b6b08000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:53.336  6707  6707 W art     : b6b08000-b6b09000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 14:03:53.336  6707  6707 W art     : b6b09000-b6b37000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:53.336  6707  6707 W art     : b6b37000-b6b38000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6b38000-b6b3f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:53.336  6707  6707 W art     : b6b3f000-b6b40000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 14:03:53.336  6707  6707 W art     : b6b40000-b6b86000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:53.336  6707  6707 W art     : b6b86000-b6b87000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6b87000-b6b8a000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:53.336  6707  6707 W art     : b6b8a000-b6b8b000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 14:03:53.336  6707  6707 W art     : b6b8b000-b6ba6000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:53.336  6707  6707 W art     : b6ba6000-b6baa000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:53.336  6707  6707 W art     : b6baa000-b6bab000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 14:03:53.336  6707  6707 W art     : b6bab000-b6bf8000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:53.336  6707  6707 W art     : b6bf8000-b6bf9000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6bf9000-b6c05000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:53.336  6707  6707 W art     : b6c05000-b6c06000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 14:03:53.336  6707  6707 W art     : b6c06000-b6c13000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 14:03:53.336  6707  6707 W art     : b6c13000-b6c14000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6c14000-b6c15000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 14:03:53.336  6707  6707 W art     : b6c15000-b6c16000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 14:03:53.336  6707  6707 W art     : b6c16000-b6c1e000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:53.336  6707  6707 W art     : b6c1e000-b6c1f000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6c1f000-b6c20000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:53.336  6707  6707 W art     : b6c20000-b6c21000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 14:03:53.336  6707  6707 W art     : b6c21000-b6c28000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:53.336  6707  6707 W art     : b6c28000-b6c29000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:53.336  6707  6707 W art     : b6c29000-b6c2a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 14:03:53.336  6707  6707 W art     : b6c2a000-b6c3e000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:53.336  6707  6707 W art     : b6c3e000-b6c40000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:53.336  6707  6707 W art     : b6c40000-b6c41000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 14:03:53.336  6707  6707 W art     : b6c41000-b6c69000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:53.336  6707  6707 W art     : b6c69000-b6c6b000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:53.336  6707  6707 W art     : b6c6b000-b6c6c000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 14:03:53.336  6707  6707 W art     : b6c6c000-b6c6f000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:53.336  6707  6707 W art     : b6c6f000-b6c70000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:53.336  6707  6707 W art     : b6c70000-b6c71000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 14:03:53.336  6707  6707 W art     : b6c71000-b6c7a000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:53.336  6707  6707 W art     : b6c7a000-b6c7b000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:53.336  6707  6707 W art     : b6c7b000-b6c7c000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 14:03:53.336  6707  6707 W art     : b6c7c000-b6c9c000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 14:03:53.336  6707  6707 W art     : b6c9c000-b6c9d000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 14:03:53.336  6707  6707 W art     : b6c9d000-b6c9e000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 14:03:53.336  6707  6707 W art     : b6c9e000-b6d11000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 14:03:53.336  6707  6707 W art     : b6d11000-b6d15000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 14:03:53.336  6707  6707 W art     : b6d15000-b6d18000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 14:03:53.336  6707  6707 W art     : b6d18000-b6d22000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6d22000-b6daa000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:53.336  6707  6707 W art     : b6daa000-b6dab000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6dab000-b6daf000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:53.336  6707  6707 W art     : b6daf000-b6db0000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 14:03:53.336  6707  6707 W art     : b6db0000-b6db1000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6db1000-b6dda000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:53.336  6707  6707 W art     : b6dda000-b6ddb000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6ddb000-b6dde000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:53.336  6707  6707 W art     : b6dde000-b6ddf000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 14:03:53.336  6707  6707 W art     : b6ddf000-b6eb9000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:53.336  6707  6707 W art     : b6eb9000-b6ec0000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:53.336  6707  6707 W art     : b6ec0000-b6ec8000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 14:03:53.336  6707  6707 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6ec9000-b6eca000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:53.336  6707  6707 W art     : b6eca000-b6ecb000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 14:03:53.336  6707  6707 W art     : b6ecb000-b6ecc000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6ecc000-b6ecf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6ecf000-b6ef4000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:53.336  6707  6707 W art     : b6ef4000-b6ef5000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6ef5000-b6efc000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:53.336  6707  6707 W art     : b6efc000-b6efd000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 14:03:53.336  6707  6707 W art     : b6efd000-b6f04000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:53.336  6707  6707 W art     : b6f04000-b6f05000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:53.336  6707  6707 W art     : b6f05000-b6f06000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 14:03:53.336  6707  6707 W art     : b6f06000-b6f07000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6f07000-b6f1f000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f1f000-b6f20000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6f20000-b6f21000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f21000-b6f22000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f22000-b6f30000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f30000-b6f31000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6f31000-b6f32000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f32000-b6f33000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 14:03:53.336  6707  6707 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:53.336  6707  6707 W art     : b6f34000-b6f36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6f36000-b6f37000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6f37000-b6f38000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 14:03:53.336  6707  6707 W art     : b6f38000-b6f39000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 14:03:53.336  6707  6707 W art     : b6f39000-b6f3a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 14:03:53.336  6707  6707 W art     : b6f3a000-b6f5a000 r--s 00000000 00:0b 7184       /dev/__properties__
08-24 14:03:53.336  6707  6707 W art     : b6f5a000-b6f5b000 r--p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6f5b000-b6f5c000 ---p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6f5c000-b6f5e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 14:03:53.336  6707  6707 W art     : b6f5e000-b6f5f000 r-xp 00000000 00:00 0          [sigpage]
08-24 14:03:53.336  6707  6707 W art     : b6f5f000-b6f7a000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 14:03:53.336  6707  6707 W art     : b6f7a000-b6f7b000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 14:03:53.336  6707  6707 W art     : b6f7b000-b6f7d000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 14:03:53.336  6707  6707 W art     : b6f7d000-b6f7f000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : b6f7f000-b6f84000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 14:03:53.336  6707  6707 W art     : b6f84000-b6f85000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 14:03:53.336  6707  6707 W art     : b6f85000-b6f86000 rw-p 00000000 00:00 0 
08-24 14:03:53.336  6707  6707 W art     : becc1000-bece2000 rw-p 00000000 00:00 0          [stack]
08-24 14:03:53.336  6707  6707 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-24 14:03:53.416  6707  6707 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 14:03:53.476  6707  6707 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 14:03:53.486  6707  6707 E AffinityControl: AffinityControl: registerfunction enter
,08-24 14:03:53.496  6707  6707 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:03:53.516   776  1660 D PackageManager: START PACKAGE DELETE: observer{247005092}
08-24 14:03:53.516   776  1660 D PackageManager: pkg{<packageName>}
08-24 14:03:53.516   776  1660 D PackageManager: user{0}
08-24 14:03:53.516   776  1660 D PackageManager: caller{2000}
08-24 14:03:53.516   776  1660 D PackageManager: flags{2}
08-24 14:03:53.516   776  1660 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 14:03:53.516   776  1660 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 14:03:53.516   776  1660 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 14:03:53.516   776  1660 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 14:03:53.516   776  1660 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-24 14:03:53.516   776   934 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 14:03:53.516   776   934 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 14:03:53.516   776   934 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 14:03:53.516   776   934 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 14:03:53.516   776   934 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 14:03:53.526   776   934 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-24 14:03:53.526   776   934 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-24 14:03:53.526   776   934 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-24 14:03:53.526   776   861 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-24 14:03:53.526   776   861 I ActivityManager: Killing 6407:com.test.thalitest/u0a4 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-24 14:03:53.526   776   861 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-24 14:03:53.536   776   934 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-24 14:03:53.536   776   934 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-24 14:03:53.556   776   934 D AASAinstall: there is not AASApackages.xml file
,08-24 14:03:53.576   776   789 D GraphicsStats: Buffer count: 5
,08-24 14:03:53.576   776   789 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f81010d)
08-24 14:03:53.586   776  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:03:53.586   776  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:03:53.586   776  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:03:53.826   776   934 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-24 14:03:53.916   776   934 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 14:03:53.916   331   331 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-24 14:03:53.916   776   934 I art     : Starting a blocking GC Explicit
,08-24 14:03:54.036   776   934 I art     : Explicit concurrent mark sweep GC freed 109152(5MB) AllocSpace objects, 15(300KB) LOS objects, 27% free, 42MB/58MB, paused 1.309ms total 111.047ms
,08-24 14:03:54.056   776   934 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 14:03:54.066   776   934 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-24 14:03:54.066   776   934 D AASAinstall: there is not AASApackages.xml file
08-24 14:03:54.066   776   934 D PackageManager: result of delete: 1{247005092}
,08-24 14:03:54.066  6707  6707 I art     : System.exit called, status: 0
08-24 14:03:54.066  6707  6707 I AndroidRuntime: VM exiting with result code 0.
,08-24 14:03:54.066   776   934 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 14:03:54.066   776   934 D PackageManager: userId{-1}
08-24 14:03:54.066   776   934 D PackageManager: andCode{true}
,08-24 14:03:54.086   776   934 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-24 14:03:54.096  6050  6726 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-24 14:03:54.096  6050  6726 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-24 14:03:54.116  6050  6726 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-24 14:03:54.156   776   776 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.156   776   776 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.166  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-24 14:03:54.166  1379  1379 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
08-24 14:03:54.166   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.166   776   907 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.166   776   907 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.166   776  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:03:54.176   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.186   776   776 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.196   776   776 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.196   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.196  2015  2015 E SamsungIME: mOCRHelper is null
,08-24 14:03:54.206  1704  1704 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-24 14:03:54.206  2043  2343 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.216   776   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{adef327 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ed9ef7a 4301:com.samsung.klmsagent/u0a18}
,08-24 14:03:54.216  4301  4301 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 24 14:03:54 GMT+02:00 2016
,08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.216   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.226   776   776 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.226   776   776 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.226   776   776 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.226   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.226  4301  4301 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-24 14:03:54.236  3255  3271 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 14:03:54.236  3255  3271 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 14:03:54.236   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.236  4301  4301 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-24 14:03:54.236   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.236  4301  4301 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 14:03:54.236   776   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{adef327 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4dc23 776:system/1000}
,08-24 14:03:54.236  4301  4301 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 14:03:54.236  4301  6742 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-24 14:03:54.236  4301  6742 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-24 14:03:54.236  4301  6742 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-24 14:03:54.236  4301  6742 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,08-24 14:03:54.246  4301  6742 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-24 14:03:54.246  4301  6742 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-24 14:03:54.246  3255  3271 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.246   776  1363 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.246   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.256   776   776 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.256   776   776 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.256  3255  3271 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 14:03:54.256   776  1581 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-24 14:03:54.256   776   776 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.256   776   776 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.256  4301  6742 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 14:03:54.266  4301  6742 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.266   776  1297 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-24 14:03:54.266  4301  6742 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x727febe6 in tid 6742 (IntentService[K)
,08-24 14:03:54.266   776   852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
,08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.266   776   776 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.266   776   852 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-24 14:03:54.266  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
08-24 14:03:54.266  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
,08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.276   776   776 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.276  1699  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-24 14:03:54.286   776   776 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
08-24 14:03:54.286  1699  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 14:03:54.286  1699  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 14:03:54.286   776  2569 I ActivityManager: Process com.samsung.klmsagent (pid 4301)(adj 5) has died(211,703)
08-24 14:03:54.286  1699  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 14:03:54.286  1699  6744 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 14:03:54.286   776  2569 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
,08-24 14:03:54.286   776  2569 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
,08-24 14:03:54.286   776   852 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ca941ae in tid 852 (android.bg)
08-24 14:03:54.286   776   852 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 14:03:54.286   776   776 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.286   776   776 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 14:03:54.286  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
,08-24 14:03:54.316   350   350 I Zygote  : Process 4301 exited due to signal (7)
,08-24 14:03:54.366  1904  1914 W Sensors : sensorservice died [0xad83fe00]
08-24 14:03:54.366  2853  2863 W Sensors : sensorservice died [0xacea2c00]
,08-24 14:03:54.366  1725  1737 W Sensors : sensorservice died [0xb3a46240]
,08-24 14:03:54.366  1379  1407 W Sensors : sensorservice died [0xad67bc00]
,08-24 14:03:54.366   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
,08-24 14:03:54.366   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-24 14:03:54.366   294  4736 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-24 14:03:54.366   294   354 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
,08-24 14:03:54.376  2043  2060 W Sensors : sensorservice died [0xa988bc40]
,08-24 14:03:54.376   294   354 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
08-24 14:03:54.376   293   293 I ServiceManager: service 'telecom' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'notification' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'location' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'country_detector' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sec_location' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'search' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'execute' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'dropbox' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'wallpaper' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'audio' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'DockObserver' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'midi' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'usb' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'serial' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'kiesusb' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'jobscheduler' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'backup' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'appwidget' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'voiceinteraction' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'diskstats' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'mDNIe' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'AAS' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'MSCS' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'spengestureservice' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'quickconnect' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'samplingprofiler' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'commontime_management' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'dreams' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'graphicsstats' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'print' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'restrictions' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'media_session' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'media_router' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'trust' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'fingerprint' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'launcherapps' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'voip' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'media_projection' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'lpnet' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'imms' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sec_analytics' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'clipboard' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'clipboardEx' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'network_management' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'textservices' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'network_score' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'netstats' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'netpolicy' died
08-24 14:03:54.376   293   2,93 I ServiceManager: service 'wifip2p' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'wifi' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'wifihs20' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'wifiscanner' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'rttmanager' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'ethernet' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'connectivity' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sb_service' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'servicediscovery' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'updatelock' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'knox_ccm_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'application_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'wifi_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'remoteinjection' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'edm_proxy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'mum_container_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'otp_service' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'enterprise_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'statusbar' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'activity' died
08-24 14:03:54.376  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
08-24 14:03:54.376   293   293 I ServiceManager: service 'context_aware' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'scontext' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'barbeam' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'multiwindow_facade' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'window' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'input' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'bluetooth_manager' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'rcp' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'input_method' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'accessibility' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'display' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'package' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'persona_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'user' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'procstats' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'meminfo' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'gfxinfo' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'dbinfo' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'cpuinfo' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'permission' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'processinfo' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sensorservice' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'battery' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'usagestats' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'webviewupdate' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'scheduling_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'telephony.registry' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'persona' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'edmnativehelper' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'cover' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'mount' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'uimode' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'lock_settings' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'deviceidle' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'device_policy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'harmony_eas_service' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sdp' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sdp_log' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'dlp' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'log_manager_service' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'SEAMService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'media.camera.proxy' died
08-24 14:03:54.386  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
08-24 14:03:54.376   293   293 I ServiceManager: service 'account' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'content' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'DirEncryptService' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'LSManager' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'ReactiveService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'EngineeringModeService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'SatsService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'sedenial' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'vibrator' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'tw_toolbox' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'tima' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'iccc' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'cepproxyks' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'emailksproxy' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'consumer_ir' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'alarm' died
,08-24 14:03:54.376   293   293 I ServiceManager: service 'batterystats' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'appops' died
08-24 14:03:54.376   293   293 I ServiceManager: service 'power' died
08-24 14:03:54.376  1699  1699 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7168ab05 in tid 1699 (com.android.nfc)
08-24 14:03:54.376  1699  1699 F libc    : Unable to open connection to debuggerd: Connection refused
08-24 14:03:54.376  1704  1704 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-24 14:03:54.376  1379  1638 E WifiManager: Channel connection lost
,08-24 14:03:54.376   318   318 W AudioFlinger: power manager service died !!!
08-24 14:03:54.376   318   318 W AudioFlinger: power manager service died !!!
08-24 14:03:54.376  1704  2211 E WifiManager: Channel connection lost
08-24 14:03:54.376  2043  2342 E WifiManager: Channel connection lost
08-24 14:03:54.376  2451  2451 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ed54894 in tid 2451 (droid.bluetooth)
08-24 14:03:54.376  2451  2451 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 14:03:54.386  6017  6093 E WifiManager: Channel connection lost
,08-24 14:03:54.396  2853  3225 E WifiManager: Channel connection lost
,08-24 14:03:54.396  2512  2523 W Sensors : sensorservice died [0xad3ffcc0]
,08-24 14:03:54.396   294   351 I SurfaceFlinger: id=5 Removed TtatusBar (8/9)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=5 Removed TtatusBar (-2/9)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=7 Removed JmageWallpa (3/8)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=23 Removed VSBConnecti (6/7)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=24 Removed VSBConnecti (4/6)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/6)
08-24 14:03:54.396   294   351 I SurfaceFlinger: id=24 Removed VSBConnecti (-2/6)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=2 Removed GocusedStac (3/5)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=14 Removed EimLayer(Di (3/4)
08-24 14:03:54.396   294   354 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/4)
08-24 14:03:54.396   294   354 I SurfaceFlinger: id=20 Removed DolorFade (3/3)
08-24 14:03:54.396   294   354 I SurfaceFlinger: id=20 Removed DolorFade (-2/3)
08-24 14:03:54.396   294   354 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/3)
08-24 14:03:54.396   294   354 I SurfaceFlinger: id=15 Removed EimLayer(An (2/2)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-24 14:03:54.396   294   835 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-24 14:03:54.406   329   329 E installd: eof
08-24 14:03:54.406   329   329 E installd: failed to read size
08-24 14:03:54.406   329   329 I installd: closing connection
08-24 14:03:54.406  1843  1986 E WifiManager: Channel connection lost
,08-24 14:03:54.416   293   293 I ServiceManager: service 'nfc' died
08-24 14:03:54.416   293   293 I ServiceManager: service 'secontroller' died
08-24 14:03:54.416   293   293 I ServiceManager: service 'nfccontroller' died
,08-24 14:03:54.416  2853  2853 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 14:03:54.416  2853  2853 D PanProfile: Bluetooth service disconnected
08-24 14:03:54.416  2500  2500 D BluetoothA2dp: Proxy object disconnected
08-24 14:03:54.416  2853  2853 D BluetoothMap: Proxy object disconnected
08-24 14:03:54.416  2853  2853 D MapProfile: Bluetooth service disconnected
,08-24 14:03:54.416  2853  2853 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9752bd in tid 2853 (ndroid.settings)
,08-24 14:03:54.416  2853  2853 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 14:03:54.416  2460  2460 E audit_log: File locking failed. error= Bad file descriptor
,08-24 14:03:54.456   350   350 I Zygote  : Process 1699 exited due to signal (7)
08-24 14:03:54.456   350   350 I Zygote  : Process 2853 exited due to signal (7)
,08-24 14:03:54.476   350   350 I Zygote  : Process 2451 exited due to signal (7)
,08-24 14:03:54.626   292   292 I lowmemorykiller: ActivityManager disconnected
08-24 14:03:54.626   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-24 14:03:54.626   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-24 14:03:54.626   294   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-24 14:03:54.876   294   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 14:03:54.876   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
,08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
,08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
08-24 14:03:54.886   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
,08-24 14:03:54.896   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e638c
,08-24 14:03:54.896   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e63a4
,08-24 14:03:54.896   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8e63a4

```
