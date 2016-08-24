#### Test 79763830cb90817_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-24 16:35:44.405  5413  5413 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-24 16:35:44.405  5413  5413 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-24 16:35:44.405  5413  5413 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-24 16:35:44.405  5413  5413 I art     : System.exit called, status: 0
08-24 16:35:44.405  5413  5413 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-24 16:35:44.445   761  1738 I ActivityManager: Process com.samsung.aasaservice (pid 5413)(adj 0) has died(117,717)
08-24 16:35:44.445   761  1738 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-24 16:35:44.445   761  1738 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-24 16:35:44.445   761  1738 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-24 16:35:44.455  5372  5372 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-24 16:35:44.475   761   853 I ActivityManager: Start proc 6275:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-24 16:35:44.475   761  1318 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 16:35:44.475  6275  6275 E Zygote  : v2
08-24 16:35:44.475  6275  6275 I libpersona: KNOX_SDCARD checking this for 10014
08-24 16:35:44.475  6275  6275 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:44.475  6275  6275 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:44.475  6275  6275 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:44.485  6275  6275 E Zygote  : accessInfo : 0
08-24 16:35:44.485  6275  6275 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-24 16:35:44.505  6275  6275 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:44.505  6275  6275 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:44.515   761  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bd2950 6275:com.google.android.partnersetup/u0a14}
08-24 16:35:44.515   761  1318 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-24 16:35:44.525  6275  6275 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-24 16:35:44.535  6275  6275 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-24 16:35:44.565   761  1422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bd2950 6275:com.google.android.partnersetup/u0a14}
08-24 16:35:44.575  6300  6300 E Zygote  : v2
08-24 16:35:44.575   761  2296 I ActivityManager: Start proc 6300:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-24 16:35:44.575  6300  6300 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:44.575  6300  6300 I libpersona: KNOX_SDCARD checking this for 10015
08-24 16:35:44.575  6300  6300 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:44.585  6300  6300 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:44.585  6300  6300 E Zygote  : accessInfo : 0
08-24 16:35:44.585  6300  6300 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-24 16:35:44.585   761  2268 I ActivityManager: Killing 5449:com.sec.esdk.elm/u0a103 (adj 15): DHA:empty #37
08-24 16:35:44.605   761  1738 D ActivityManager: isAutoRunBlockedApp:: com.sec.esdk.elm, Auto Run ON
08-24 16:35:44.625  6300  6300 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:44.625  6300  6300 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:44.635   761  1614 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c291d6f 6300:com.samsung.groupcast/u0a15}
08-24 16:35:44.635  6300  6300 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-24 16:35:44.655  6300  6300 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-24 16:35:44.675  6300  6300 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-24 16:35:44.685  6300  6300 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-24 16:35:44.685  6300  6300 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-24 16:35:44.685  6300  6300 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:35:44.685  6300  6300 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 16:35:44.685  6300  6300 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:35:44.685  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 16:35:44.685  6300  6300 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 16:35:44.685   761  1614 I ActivityManager: Killing 5465:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-24 16:35:44.695   761  1614 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dca88a3 1882:com.sec.android.app.shealth:remote/u0a34}
08-24 16:35:44.705   761  1732 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-24 16:35:44.715  6312  6312 E Zygote  : v2
08-24 16:35:44.715   761  2268 I ActivityManager: Start proc 6312:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-24 16:35:44.715  6312  6312 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:44.715  6312  6312 I libpersona: KNOX_SDCARD checking this for 10041
08-24 16:35:44.715  6312  6312 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:44.715  6312  6312 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:44.715  6312  6312 E Zygote  : accessInfo : 0
08-24 16:35:44.715  6312  6312 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-24 16:35:44.735  6312  6312 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:44.735  6312  6312 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:44.745   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7538a7c 6312:com.samsung.android.sdk.samsunglink/u0a41}
08-24 16:35:44.755  6312  6312 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-24 16:35:44.835  6312  6312 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 16:35:44.835  6312  6312 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 16:35:44.895  6312  6312 I SL_DEBUG: isLoggable:: isProductShip = 1
08-24 16:35:44.895  6312  6312 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-24 16:35:44.905   761   775 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.905   761  1738 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-24 16:35:44.905   761  1482 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.915   761  1801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.915   761  1614 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.915   761  1723 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.915   761   774 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.925   761  2296 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.925   761  1315 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-24 16:35:44.925   761  1732 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-24 16:35:45.025  6312  6312 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-24 16:35:45.025  6312  6312 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-24 16:35:45.025  6312  6312 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-24 16:35:45.025  6312  6312 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-24 16:35:45.025  6312  6312 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-24 16:35:45.025  6312  6312 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-24 16:35:45.025  6312  6312 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 16:35:45.025  6312  6312 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 16:35:45.035  6312  6312 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 16:35:45.035  6312  6312 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 16:35:45.035  6312  6312 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:35:45.035  6312  6312 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:35:45.035  6312  6312 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 16:35:45.035  6312  6312 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:35:45.035  6312  6312 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 16:35:45.035  6312  6312 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 16:35:45.035   761   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9beb92e 1663:android.process.acore/u0a19}
08-24 16:35:45.045   761  1482 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{83f66fa 5118:com.sec.android.gallery3d/u0a47}
08-24 16:35:45.045  5118  5118 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-24 16:35:45.055   761  1315 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 16:35:45.075  6335  6335 E Zygote  : v2
08-24 16:35:45.075  6335  6335 I libpersona: KNOX_SDCARD checking this for 10050
08-24 16:35:45.075  6335  6335 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.075  6335  6335 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.075  6335  6335 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.075  6335  6335 E Zygote  : accessInfo : 0
08-24 16:35:45.075  6335  6335 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-24 16:35:45.075   761  1732 I ActivityManager: Start proc 6335:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-24 16:35:45.105  6335  6335 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.105  6335  6335 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.105   761  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cc8aac 6335:com.sec.android.app.myfiles/u0a50}
08-24 16:35:45.115  6335  6335 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-24 16:35:45.135  6335  6335 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-24 16:35:45.165  6335  6335 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 16:35:45.185   332   332 E installd: system dir 0 : /system/app/
08-24 16:35:45.185   761   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4e77f6 2837:com.android.settings/1000}
08-24 16:35:45.185   332   332 E installd: system dir 1 : /system/priv-app/
08-24 16:35:45.185   332   332 E installd: system dir 2 : /vendor/app/
08-24 16:35:45.185   332   332 E installd: system dir 3 : /oem/app/
08-24 16:35:45.195   761   936 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 16:35:45.225   761  3422 D SSRM:n  : SIOP:: AP = 480, PST = 455, CUR = 350, LCD = 0
08-24 16:35:45.225   761  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4e77f6 2837:com.android.settings/1000}
08-24 16:35:45.235  6350  6350 E Zygote  : v2
08-24 16:35:45.235   761  1422 I ActivityManager: Start proc 6350:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-24 16:35:45.235  6350  6350 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.235  6350  6350 I libpersona: KNOX_SDCARD checking this for 10169
08-24 16:35:45.235  6350  6350 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.235  6350  6350 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.235  6350  6350 E Zygote  : accessInfo : 0
08-24 16:35:45.235  6350  6350 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-24 16:35:45.265  6350  6350 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.265  6350  6350 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.275   761   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5cda598 6350:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-24 16:35:45.275  6350  6350 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-24 16:35:45.285  6350  6350 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: onUnbind
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: CSB onClientsDisconnected
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDown
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDownCarState
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: Skip, car not connected.
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDownClientState
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: requestStop
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: onDestroy
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDown
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDownCarState
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: Skip, car not connected.
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: tearDownClientState
08-24 16:35:45.285  6190  6190 D CAR.SERVICE: requestStop
08-24 16:35:45.295  6190  6190 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@530c549 that was originally bound here
08-24 16:35:45.295  6190  6190 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@530c549 that was originally bound here
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 16:35:45.295  6190  6190 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 16:35:45.295   761  1723 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@c9401f1
08-24 16:35:45.305   761  1315 I ActivityManager: Killing 5477:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-24 16:35:45.315   761  1315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e37af37 1707:com.android.phone/1001}
08-24 16:35:45.325   761  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a88cf88 1819:com.google.android.googlequicksearchbox:search/u0a61}
08-24 16:35:45.325  2231  2231 E audit   : type=1400 msg=audit(1472049345.325:285): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 16:35:45.325  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.325  2231  2231 E audit   : type=1300 msg=audit(1472049345.325:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 16:35:45.325  2231  2231 E audit   : type=1327 msg=audit(1472049345.325:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 16:35:45.325  2231  2231 E audit   : type=1320 msg=audit(1472049345.325:285): 
08-24 16:35:45.325   761  1422 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-24 16:35:45.345   761  1614 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a88cf88 1819:com.google.android.googlequicksearchbox:search/u0a61}
08-24 16:35:45.355   761  1315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23ddc57 6229:com.samsung.android.sm.provider/1000}
08-24 16:35:45.365  6364  6364 E Zygote  : v2
08-24 16:35:45.365  6364  6364 I libpersona: KNOX_SDCARD checking this for 5012
08-24 16:35:45.365  6364  6364 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.365   761  1622 I ActivityManager: Start proc 6364:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-24 16:35:45.365  6364  6364 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.365  6364  6364 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.375  6364  6364 E Zygote  : accessInfo : 0
08-24 16:35:45.375  6364  6364 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-24 16:35:45.375  1819  6362 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 16:35:45.375  2231  2231 E audit   : type=1400 msg=audit(1472049345.375:286): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 16:35:45.375  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.375  2231  2231 E audit   : type=1300 msg=audit(1472049345.375:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 16:35:45.375  2231  2231 E audit   : type=1327 msg=audit(1472049345.375:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 16:35:45.375  2231  2231 E audit   : type=1320 msg=audit(1472049345.375:286): 
08-24 16:35:45.415  6364  6364 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.415  6364  6364 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.425  2231  2231 E audit   : type=1400 msg=audit(1472049345.425:287): avc:  denied  { execmod } for  pid=6273 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 16:35:45.425  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.425  2231  2231 E audit   : type=1300 msg=audit(1472049345.425:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6273 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 16:35:45.425  2231  2231 E audit   : type=1327 msg=audit(1472049345.425:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 16:35:45.425  2231  2231 E audit   : type=1320 msg=audit(1472049345.425:287): 
08-24 16:35:45.425  6273  6273 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 16:35:45.425  1819  6362 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 16:35:45.435  6273  6273 D AndroidRuntime: CheckJNI is OFF
08-24 16:35:45.435   761  1315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc38344 6364:com.samsung.android.sm.devicesecurity/5012}
08-24 16:35:45.435  6273  6273 D AndroidRuntime: readGMSProperty: start
08-24 16:35:45.435  6273  6273 D AndroidRuntime: readGMSProperty: already setted!!
08-24 16:35:45.435  6273  6273 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 16:35:45.435  6273  6273 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 16:35:45.435  6273  6273 D AndroidRuntime: readGMSProperty: end
08-24 16:35:45.435  6273  6273 D AndroidRuntime: addProductProperty: start
08-24 16:35:45.435  6273  6273 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 16:35:45.435  6364  6364 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-24 16:35:45.435  6273  6273 W art     : af0a5000-b1fcb000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:45.435  6273  6273 W art     : b1fcb000-b423a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:45.435  6273  6273 W art     : b423a000-b423b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:45.435  6273  6273 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 16:35:45.435  6273  6273 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 16:35:45.435  6273  6273 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 16:35:45.435  6273  6273 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 16:35:45.435  6273  6273 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 16:35:45.435  6273  6273 W art     : b47e0000-b47e3000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 16:35:45.435  6273  6273 W art     : b47e3000-b47e4000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 16:35:45.435  6273  6273 W art     : b47e4000-b47e5000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 16:35:45.435  6273  6273 W art     : b47e5000-b47e6000 r--p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b47e6000-b4806000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 16:35:45.435  6273  6273 W art     : b4806000-b5217000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 16:35:45.435  6273  6273 W art     : b5217000-b5218000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5218000-b5261000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 16:35:45.435  6273  6273 W art     : b5261000-b5262000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 16:35:45.435  6273  6273 W art     : b5262000-b526a000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b526a000-b526b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.435  6273  6273 W art     : b526b000-b52a0000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:45.435  6273  6273 W art     : b52a0000-b52a1000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b52a1000-b52a2000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:45.435  6273  6273 W art     : b52a2000-b52a3000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:45.435  6273  6273 W art     : b52a3000-b52fb000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 16:35:45.435  6273  6273 W art     : b52fb000-b52fc000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b52fc000-b52fd000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 16:35:45.435  6273  6273 W art     : b52fd000-b52fe000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 16:35:45.435  6273  6273 W art     : b52ff000-b5305000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 16:35:45.435  6273  6273 W art     : b5305000-b5306000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 16:35:45.435  6273  6273 W art     : b5306000-b5307000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 16:35:45.435  6273  6273 W art     : b5307000-b5309000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b530a000-b5314000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:45.435  6273  6273 W art     : b5314000-b5317000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:45.435  6273  6273 W art     : b5317000-b5318000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:45.435  6273  6273 W art     : b5319000-b5330000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 16:35:45.435  6273  6273 W art     : b5330000-b5331000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5331000-b5332000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 16:35:45.435  6273  6273 W art     : b5332000-b5333000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 16:35:45.435  6273  6273 W art     : b5334000-b533e000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:45.435  6273  6273 W art     : b533e000-b533f000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:45.435  6273  6273 W art     : b533f000-b5340000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:45.435  6273  6273 W art     : b5340000-b5344000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 16:35:45.435  6273  6273 W art     : b5344000-b5345000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 16:35:45.435  6273  6273 W art     : b5345000-b5346000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 16:35:45.435  6273  6273 W art     : b5346000-b535c000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 16:35:45.435  6273  6273 W art     : b535c000-b535d000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 16:35:45.435  6273  6273 W art     : b535d000-b535e000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 16:35:45.435  6273  6273 W art     : b535e000-b536b000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:45.435  6273  6273 W art     : b536b000-b536c000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:45.435  6273  6273 W art     : b536c000-b536d000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:45.435  6273  6273 W art     : b536d000-b53cd000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 16:35:45.435  6273  6273 W art     : b53cd000-b53d0000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 16:35:45.435  6273  6273 W art     : b53d0000-b53d4000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b53d4000-b5435000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 16:35:45.435  6273  6273 W art     : b5435000-b5436000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 16:35:45.435  6273  6273 W art     : b5436000-b5485000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 16:35:45.435  6273  6273 W art     : b5485000-b5487000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 16:35:45.435  6273  6273 W art     : b5487000-b5488000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 16:35:45.435  6273  6273 W art     : b5488000-b5489000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5489000-b5490000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5490000-b5491000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5491000-b5492000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5493000-b5496000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5496000-b5497000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5497000-b5498000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 16:35:45.435  6273  6273 W art     : b5499000-b549d000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 16:35:45.435  6273  6273 W art     : b549d000-b549e000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b549e000-b549f000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 16:35:45.435  6273  6273 W art     : b549f000-b54a0000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-24 16:35:45.435  6273  6273 W art     : b54a1000-b54be000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 16:35:45.435  6273  6273 W art     : b54be000-b54bf000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 16:35:45.435  6273  6273 W art     : b54bf000-b54c0000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 16:35:45.435  6273  6273 W art     : b54c1000-b54c6000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:45.435  6273  6273 W art     : b54c6000-b54c7000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:45.435  6273  6273 W art     : b54c7000-b54c8000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:45.435  6273  6273 W art     : b54c9000-b54fa000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:45.435  6273  6273 W art     : b54fa000-b54fd000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:45.435  6273  6273 W art     : b54fd000-b54fe000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:45.435  6273  6273 W art     : b54ff000-b553a000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 16:35:45.435  6273  6273 W art     : b553a000-b553b000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 16:35:45.435  6273  6273 W art     : b553b000-b553c000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 16:35:45.435  6273  6273 W art     : b553d000-b5544000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:45.435  6273  6273 W art     : b5544000-b5545000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5545000-b5546000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:45.435  6273  6273 W art     : b5546000-b5547000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:45.435  6273  6273 W art     : b5547000-b5548000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.435  6273  6273 W art     : b5548000-b555f000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 16:35:45.435  6273  6273 W art     : b555f000-b5560000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5560000-b5563000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 16:35:45.435  6273  6273 W art     : b5563000-b5564000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 16:35:45.435  6273  6273 W art     : b5564000-b5583000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:45.435  6273  6273 W art     : b5583000-b5584000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:45.435  6273  6273 W art     : b5584000-b5585000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:45.435  6273  6273 W art     : b5585000-b55c3000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:45.435  6273  6273 W art     : b55c3000-b55c4000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b55c4000-b55c6000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:45.435  6273  6273 W art     : b55c6000-b55c7000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:45.435  6273  6273 W art     : b55c8000-b55cf000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 16:35:45.435  6273  6273 W art     : b55cf000-b55d0000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 16:35:45.435  6273  6273 W art     : b55d0000-b55d1000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 16:35:45.435  6273  6273 W art     : b55d2000-b55d5000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:45.435  6273  6273 W art     : b55d5000-b55d6000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:45.435  6273  6273 W art     : b55d6000-b55d7000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:45.435  6273  6273 W art     : b55d7000-b55dd000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 16:35:45.435  6273  6273 W art     : b55dd000-b55de000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b55de000-b55df000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 16:35:45.445  1819  6362 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 16:35:45.435  6273  6273 W art     : b55df000-b55e0000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 16:35:45.435  6273  6273 W art     : b55e0000-b55e9000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:45.435  6273  6273 W art     : b55e9000-b55ea000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:45.435  6273  6273 W art     : b55ea000-b55eb000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:45.435  6273  6273 W art     : b55eb000-b567c000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:45.435  6273  6273 W art     : b567c000-b567d000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b567d000-b5688000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:45.435  6273  6273 W art     : b5688000-b5689000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:45.435  6273  6273 W art     : b568a000-b569c000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 16:35:45.435  6273  6273 W art     : b569c000-b569d000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 16:35:45.435  6273  6273 W art     : b569d000-b569e000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 16:35:45.435  6273  6273 W art     : b569f000-b56a4000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:45.435  6273  6273 W art     : b56a4000-b56a5000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:45.435  6273  6273 W art     : b56a5000-b56a6000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:45.435  6273  6273 W art     : b56a7000-b5714000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 16:35:45.435  6273  6273 W art     : b5714000-b5715000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5715000-b5717000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 16:35:45.435  6273  6273 W art     : b5717000-b5718000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 16:35:45.435  6273  6273 W art     : b5718000-b5719000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.435  6273  6273 W art     : b5719000-b5720000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:45.435  6273  6273 W art     : b5720000-b5721000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:45.435  6273  6273 W art     : b5721000-b5722000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:45.435  6273  6273 W art     : b5723000-b57a3000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 16:35:45.435  6273  6273 W art     : b57a3000-b57a4000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b57a4000-b57a5000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 16:35:45.435  6273  6273 W art     : b57a5000-b57a6000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 16:35:45.435  6273  6273 W art     : b57a6000-b57bd000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b57bd000-b57f4000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 16:35:45.435  6273  6273 W art     : ib/libqc-opt.so
08-24 16:35:45.435  6273  6273 W art     : b57f4000-b57f5000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 16:35:45.435  6273  6273 W art     : b57f5000-b57f6000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 16:35:45.435  6273  6273 W art     : b57f6000-b5812000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 16:35:45.435  6273  6273 W art     : b5812000-b5813000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 16:35:45.435  6273  6273 W art     : b5813000-b5814000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 16:35:45.435  6273  6273 W art     : b5815000-b5876000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:45.435  6273  6273 W art     : b5876000-b5878000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:45.435  6273  6273 W art     : b5878000-b5879000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:45.435  6273  6273 W art     : b587a000-b58a1000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:45.435  6273  6273 W art     : b58a1000-b58a2000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b58a2000-b58a3000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:45.435  6273  6273 W art     : b58a3000-b58a4000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:45.435  6273  6273 W art     : b58a5000-b58ad000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 16:35:45.435  6273  6273 W art     : b58ad000-b58af000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 16:35:45.435  6273  6273 W art     : b58af000-b58b0000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 16:35:45.435  6273  6273 W art     : b58b1000-b58b4000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:45.435  6273  6273 W art     : b58b4000-b58b5000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:45.435  6273  6273 W art     : b58b5000-b58b6000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:45.435  6273  6273 W art     : b58b6000-b58ba000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:45.435  6273  6273 W art     : b58ba000-b58bb000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b58bb000-b58bc000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:45.435  6273  6273 W art     : b58bc000-b58bd000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:45.435  6273  6273 W art     : b58bd000-b58cd000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 16:35:45.435  6273  6273 W art     : b58cd000-b58ce000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 16:35:45.435  6273  6273 W art     : b58ce000-b58cf000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 16:35:45.435  6273  6273 W art     : b58cf000-b5915000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5915000-b591e000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:45.435  6273  6273 W art     : b591e000-b591f000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:45.435  6273  6273 W art     : b591f000-b5920000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:45.435  6273  6273 W art     : b5921000-b5926000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 16:35:45.435  6273  6273 W art     : b5926000-b5927000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 16:35:45.435  6273  6273 W art     : b5927000-b5928000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 16:35:45.435  6273  6273 W art     : b5928000-b592b000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:45.435  6273  6273 W art     : b592b000-b592c000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b592c000-b592d000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:45.435  6273  6273 W art     : b592d000-b592e000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:45.435  6273  6273 W art     : b592f000-b5947000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 16:35:45.435  6273  6273 W art     : b5947000-b5948000 ---p 00000000 00:00 0 
08-24 16:35:45.465  6376  6376 I libpersona: KNOX_SDCARD checking this for 10210
08-24 16:35:45.435  6273  6273 W art     : b5948000-b5949000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 16:35:45.465  6376  6376 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.435  6273  6273 W art     : b5949000-b594a000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 16:35:45.435  6273  6273 W art     : b594a000-b594b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:45.435  6273  6273 W art     : b594b000-b5ae5000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:45.435  6273  6273 W art     : b5ae5000-b5ae6000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5ae6000-b5af3000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:45.435  6273  6273 W art     : b5af3000-b5af4000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:45.435  6273  6273 W art     : b5af4000-b5af8000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 16:35:45.435  6273  6273 W art     : b5af8000-b5af9000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5af9000-b5afa000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 16:35:45.435  6273  6273 W art     : b5afa000-b5afb000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 16:35:45.435  6273  6273 W art     : b5afb000-b5b0e000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:45.435  6273  6273 W art     : b5b0e000-b5b0f000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:45.435  6273  6273 W art     : b5b0f000-b5b10000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:45.435  6273  6273 W art     : b5b11000-b5b5c000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:45.465   761   853 I ActivityManager: Start proc 6376:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-24 16:35:45.435  6273  6273 W art     : b5b5c000-b5b5d000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:45.435  6273  6273 W art     : b5b5d000-b5b5e000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:45.435  6273  6273 W art     : b5b5e000-b5b60000 rw-p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5b61000-b5b72000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:45.435  6273  6273 W art     : b5b72000-b5b73000 ---p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5b73000-b5b74000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:45.435  6273  6273 W art     : b5b74000-b5b75000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:45.435  6273  6273 W art     : b5b75000-b5b76000 r--p 00000000 00:00 0 
08-24 16:35:45.435  6273  6273 W art     : b5b76000-b5b80000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:45.445  6273  6273 W art     : b5b80000-b5b82000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:45.445  6273  6273 W art     : b5b82000-b5b83000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:45.445  6273  6273 W art     : b5b83000-b5b9c000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 16:35:45.445  6273  6273 W art     : b5b9c000-b5b9d000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 16:35:45.445  6273  6273 W art     : b5b9d000-b5ba0000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 16:35:45.445  6273  6273 W art     : b5ba0000-b5ba4000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b5ba4000-b5c18000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:45.445  6273  6273 W art     : b5c18000-b5c19000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b5c19000-b5c1c000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:45.445  6273  6273 W art     : b5c1c000-b5c1d000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:45.445  6273  6273 W art     : b5c1d000-b5c1e000 r--p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b5c1e000-b5c21000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 16:35:45.445  6273  6273 W art     : b5c21000-b5c22000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 16:35:45.445  6273  6273 W art     : b5c22000-b5c23000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 16:35:45.445  6273  6273 W art     : b5c23000-b5c24000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c24000-b5c29000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:45.445  6273  6273 W art     : b5c29000-b5c2a000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:45.445  6273  6273 W art     : b5c2a000-b5c2b000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:45.445  6273  6273 W art     : b5c2b000-b5c2c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c2c000-b5c2f000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b5c2f000-b5c30000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b5c30000-b5c31000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b5c31000-b5c32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c32000-b5c36000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:45.445  6273  6273 W art     : b5c36000-b5c37000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:45.445  6273  6273 W art     : b5c37000-b5c38000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:45.445  6273  6273 W art     : b5c38000-b5c39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:45.445  6273  6273 W art     : b5c39000-b5c3d000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 16:35:45.445  6273  6273 W art     : b5c3d000-b5c3e000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 16:35:45.445  6273  6273 W art     : b5c3e000-b5c3f000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 16:35:45.445  6273  6273 W art     : b5c3f000-b5c40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c40000-b5c4e000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:45.445  6273  6273 W art     : b5c4e000-b5c4f000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b5c4f000-b5c50000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:45.445  6273  6273 W art     : b5c50000-b5c51000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:45.445  6273  6273 W art     : b5c51000-b5c5b000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 16:35:45.445  6273  6273 W art     : b5c5b000-b5c5e000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 16:35:45.445  6273  6273 W art     : b5c5e000-b5c5f000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 16:35:45.445  6273  6273 W art     : b5c5f000-b5c60000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c60000-b5c6a000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:45.445  6273  6273 W art     : b5c6a000-b5c6d000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:45.445  6273  6273 W art     : b5c6d000-b5c6e000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:45.445  6273  6273 W art     : b5c6e000-b5c72000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:45.445  6273  6273 W art     : b5c72000-b5c73000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:45.445  6273  6273 W art     : b5c73000-b5c74000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:45.445  6273  6273 W art     : b5c74000-b5c75000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b5c75000-b5c82000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 16:35:45.445  6273  6273 W art     : b5c82000-b5c84000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 16:35:45.445  6273  6273 W art     : b5c84000-b5c85000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 16:35:45.445  6273  6273 W art     : b5c85000-b6097000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:45.445  6273  6273 W art     : b6097000-b6098000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6098000-b60a1000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:45.445  6273  6273 W art     : b60a1000-b60a5000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:45.445  6273  6273 W art     : b60a5000-b60a6000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b60a6000-b60ad000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:45.445  6273  6273 W art     : b60ad000-b60ae000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:45.445  6273  6273 W art     : b60ae000-b60af000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:45.445  6273  6273 W art     : b60af000-b60b0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b60b0000-b60cb000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 16:35:45.445  6273  6273 W art     : b60cb000-b60cc000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 16:35:45.445  6273  6273 W art     : b60cc000-b60cd000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 16:35:45.445  6273  6273 W art     : b60cd000-b60ce000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b60ce000-b611a000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:45.445  6273  6273 W art     : b611a000-b611b000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b611b000-b611c000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:45.445  6273  6273 W art     : b611c000-b611d000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:45.445  6273  6273 W art     : b611d000-b611e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b611e000-b6122000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:45.445  6273  6273 W art     : b6122000-b6123000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6123000-b6124000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:45.445  6273  6273 W art     : b6124000-b6125000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:45.445  6273  6273 W art     : b6125000-b615d000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:45.445  6273  6273 W art     : b615d000-b615e000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:45.445  6273  6273 W art     : b615e000-b615f000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:45.445  6273  6273 W art     : b615f000-b6160000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6160000-b61fe000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:45.445  6273  6273 W art     : b61fe000-b61ff000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b61ff000-b621d000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:45.445  6273  6273 W art     : b621d000-b621e000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:45.445  6273  6273 W art     : b621e000-b6391000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:45.445  6273  6273 W art     : b6391000-b639c000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:45.445  6273  6273 W art     : b639c000-b639d000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:45.445  6273  6273 W art     : b639d000-b64b4000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:45.445  6273  6273 W art     : b64b4000-b64bf000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:45.445  6273  6273 W art     : b64bf000-b64c0000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:45.445  6273  6273 W art     : b64c0000-b64c4000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b64c4000-b64e8000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 16:35:45.445  6273  6273 W art     : b64e8000-b64ea000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 16:35:45.445  6273  6273 W art     : b64ea000-b64eb000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 16:35:45.445  6273  6273 W art     : b64eb000-b6591000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:45.445  6273  6273 W art     : b6591000-b659e000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:45.445  6273  6273 W art     : b659e000-b659f000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:45.445  6273  6273 W art     : b659f000-b65a0000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b65a0000-b65f3000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:45.445  6273  6273 W art     : b65f3000-b65f4000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b65f4000-b65f5000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:45.445  6273  6273 W art     : b65f5000-b65f6000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:45.445  6273  6273 W art     : b65f6000-b65fb000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b65fb000-b660d000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 16:35:45.445  6273  6273 W art     : b660d000-b660e000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b660e000-b660f000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 16:35:45.445  6273  6273 W art     : b660f000-b6610000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 16:35:45.445  6273  6273 W art     : b6610000-b6617000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 16:35:45.445  6273  6273 W art     : b6617000-b6618000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 16:35:45.445  6273  6273 W art     : b6618000-b6619000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 16:35:45.445  6273  6273 W art     : b6619000-b661a000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b661a,000-b661d000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:45.445  6273  6273 W art     : b661d000-b661e000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:45.445  6273  6273 W art     : b661e000-b661f000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:45.445  6273  6273 W art     : b661f000-b6623000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 16:35:45.445  6273  6273 W art     : b6623000-b6624000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 16:35:45.445  6273  6273 W art     : b6624000-b6625000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 16:35:45.445  6273  6273 W art     : b6625000-b6633000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:45.445  6273  6273 W art     : b6633000-b6634000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6634000-b6635000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:45.445  6273  6273 W art     : b6635000-b6636000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:45.445  6273  6273 W art     : b6636000-b663f000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 16:35:45.445  6273  6273 W art     : b663f000-b6640000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 16:35:45.445  6273  6273 W art     : b6640000-b6641000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 16:35:45.445  6273  6273 W art     : b6641000-b66a7000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:45.445  6273  6273 W art     : b66a7000-b66a8000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b66a8000-b66aa000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:45.445  6273  6273 W art     : b66aa000-b66b3000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:45.445  6273  6273 W art     : b66b3000-b66b6000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b66b6000-b674d000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 16:35:45.445  6273  6273 W art     : b674d000-b674f000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 16:35:45.445  6273  6273 W art     : b674f000-b6750000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 16:35:45.445  6273  6273 W art     : b6750000-b6751000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6751000-b6a72000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 16:35:45.445  6273  6273 W art     : b6a72000-b6a73000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6a73000-b6a8e000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 16:35:45.445  6273  6273 W art     : b6a8e000-b6a92000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 16:35:45.445  6273  6273 W art     : b6a92000-b6a97000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6a97000-b6a9f000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b6a9f000-b6aa0000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b6aa0000-b6aa1000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 16:35:45.445  6273  6273 W art     : b6aa1000-b6acf000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:45.445  6273  6273 W art     : b6acf000-b6ad0000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6ad0000-b6ad7000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:45.445  6273  6273 W art     : b6ad7000-b6ad8000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:45.445  6273  6273 W art     : b6ad8000-b6b1e000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 16:35:45.445  6273  6273 W art     : b6b1e000-b6b1f000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6b1f000-b6b22000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 16:35:45.445  6273  6273 W art     : b6b22000-b6b23000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 16:35:45.445  6273  6273 W art     : b6b23000-b6b3e000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:45.445  6273  6273 W art     : b6b3e000-b6b42000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:45.445  6273  6273 W art     : b6b42000-b6b43000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:45.445  6273  6273 W art     : b6b43000-b6b90000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:45.445  6273  6273 W art     : b6b90000-b6b91000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6b91000-b6b9d000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:45.445  6273  6273 W art     : b6b9d000-b6b9e000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:45.445  6273  6273 W art     : b6b9e000-b6bab000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 16:35:45.445  6273  6273 W art     : b6bab000-b6bac000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6bac000-b6bad000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 16:35:45.445  6273  6273 W art     : b6bad000-b6bae000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 16:35:45.445  6273  6273 W art     : b6bae000-b6bb6000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:45.445  6273  6273 W art     : b6bb6000-b6bb7000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6bb7000-b6bb8000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:45.445  6273  6273 W art     : b6bb8000-b6bb9000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:45.445  6273  6273 W art     : b6bb9000-b6bc0000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:45.445  6273  6273 W art     : b6bc0000-b6bc1000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:45.445  6273  6273 W art     : b6bc1000-b6bc2000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:45.445  6273  6273 W art     : b6bc2000-b6bd6000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:45.445  6273  6273 W art     : b6bd6000-b6bd8000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:45.445  6273  6273 W art     : b6bd8000-b6bd9000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:45.445  6273  6273 W art     : b6bd9000-b6c01000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:45.445  6273  6273 W art     : b6c01000-b6c03000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:45.445  6273  6273 W art     : b6c03000-b6c04000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:45.445  6273  6273 W art     : b6c04000-b6c07000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 16:35:45.445  6273  6273 W art     : b6c07000-b6c08000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 16:35:45.445  6273  6273 W art     : b6c08000-b6c09000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 16:35:45.445  6273  6273 W art     : b6c09000-b6c12000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:45.445  6273  6273 W art     : b6c12000-b6c13000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:45.445  6273  6273 W art     : b6c13000-b6c14000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:45.445  6273  6273 W art     : b6c14000-b6c34000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 16:35:45.445  6273  6273 W art     : b6c34000-b6c35000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 16:35:45.445  6273  6273 W art     : b6c35000-b6c36000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 16:35:45.445  6273  6273 W art     : b6c36000-b6ca9000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 16:35:45.445  6273  6273 W art     : b6ca9000-b6cad000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 16:35:45.445  6273  6273 W art     : b6cad000-b6cb0000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 16:35:45.445  6273  6273 W art     : b6cb0000-b6cba000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6cba000-b6d42000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:45.445  6273  6273 W art     : b6d42000-b6d43000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6d43000-b6d47000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:45.445  6273  6273 W art     : b6d47000-b6d48000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:45.445  6273  6273 W art     : b6d48000-b6d49000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6d49000-b6d72000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:45.445  6273  6273 W art     : b6d72000-b6d73000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6d73000-b6d76000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:45.445  6273  6273 W art     : b6d76000-b6d77000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:45.445  6273  6273 W art     : b6d77000-b6e51000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:45.445  6273  6273 W art     : b6e51000-b6e58000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:45.445  6273  6273 W art     : b6e58000-b6e60000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:45.445  6273  6273 W art     : b6e60000-b6e61000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6e61000-b6e62000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:45.445  6273  6273 W art     : b6e62000-b6e63000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 16:35:45.445  6273  6273 W art     : b6e63000-b6e64000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6e64000-b6e67000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6e67000-b6e8c000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:45.445  6273  6273 W art     : b6e8c000-b6e8d000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6e8d000-b6e94000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:45.445  6273  6273 W art     : b6e94000-b6e95000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:45.445  6273  6273 W art     : b6e95000-b6e9c000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 16:35:45.445  6273  6273 W art     : b6e9c000-b6e9d000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 16:35:45.445  6273  6273 W art     : b6e9d000-b6e9e000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 16:35:45.445  6273  6273 W art     : b6e9e000-b6e9f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6e9f000-b6eb7000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 16:35:45.445  6273  6273 W art     : b6eb7000-b6eb8000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6eb8000-b6eb9000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 16:35:45.445  6273  6273 W art     : b6eb9000-b6eba000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 16:35:45.445  6273  6273 W art     : b6eba000-b6ec8000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:45.445  6273  6273 W art     : b6ec8000-b6ec9000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6ec9000-b6eca000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:45.445  6273  6273 W art     : b6eca000-b6ecb000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:45.445  6273  6273 W art     : b6ecb000-b6ecc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:45.445  6273  6273 W art     : b6ecc000-b6ece000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:45.445  6273  6273 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 16:35:45.445  6273  6273 W art     : b6ed1000-b6ed2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:45.445  6273  6273 W art     : b6ed2000-b6ef2000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 16:35:45.445  6273  6273 W art     : b6ef2000-b6ef3000 r--p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6ef3000-b6ef4000 ---p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6ef4000-b6ef6000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 16:35:45.445  6273  6273 W art     : b6ef6000-b6ef7000 r-xp 00000000 00:00 0          [sigpage]
08-24 16:35:45.445  6273  6273 W art     : b6ef7000-b6f12000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 16:35:45.445  6273  6273 W art     : b6f12000-b6f13000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 16:35:45.445  6273  6273 W art     : b6f13000-b6f15000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 16:35:45.445  6273  6273 W art     : b6f15000-b6f17000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : b6f17000-b6f1c000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 16:35:45.445  6273  6273 W art     : b6f1c000-b6f1d000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 16:35:45.445  6273  6273 W art     : b6f1d000-b6f1e000 rw-p 00000000 00:00 0 
08-24 16:35:45.445  6273  6273 W art     : be8d2000-be8f3000 rw-p 00000000 00:00 0          [stack]
08-24 16:35:45.445  6273  6273 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-24 16:35:45.465  6376  6376 E Zygote  : v2
08-24 16:35:45.465  6376  6376 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.465  6376  6376 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.465  6376  6376 E Zygote  : accessInfo : 0
08-24 16:35:45.465  6376  6376 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-24 16:35:45.465  6364  6364 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-24 16:35:45.485  6273  6273 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 16:35:45.495   761  1723 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-24 16:35:45.525  6273  6273 I Radio-JNI: register_android_hardware_Radio DONE
08-24 16:35:45.535  6273  6273 E AffinityControl: AffinityControl: registerfunction enter
08-24 16:35:45.545  6376  6376 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.545  6376  6376 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.555  6273  6273 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 16:35:45.565  6376  6376 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-24 16:35:45.575   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4a14746 3179:com.android.contacts/u0a19}
08-24 16:35:45.585  6376  6376 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-24 16:35:45.595   761  1482 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-24 16:35:45.595  6376  6376 D AASAservice: onCreate()
08-24 16:35:45.605   761  1482 D ActivityManager: mDVFSHelper.acquire()
08-24 16:35:45.605   761  1482 V WindowManager: addAppToken: AppWindowToken{d6153e5 token=Token{25df6dc ActivityRecord{a21ff4f u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-24 16:35:45.615   761   903 D SecWifiDisplayUtil: Metadata value : none
08-24 16:35:45.615   761   903 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{66f1a9d V.E...... R.....ID 0,0-0,0}
08-24 16:35:45.615   761   903 D ISSUE_DEBUG: InputChannelName : eca72e3 Starting com.test.thalitest
08-24 16:35:45.615  6396  6396 E Zygote  : v2
08-24 16:35:45.615   761  1482 I ActivityManager: Start proc 6396:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-24 16:35:45.615  6396  6396 I libpersona: KNOX_SDCARD checking this for 10004
08-24 16:35:45.615  6396  6396 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.615  6396  6396 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.615  6396  6396 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.615  6396  6396 E Zygote  : accessInfo : 0
08-24 16:35:45.615  6396  6396 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-24 16:35:45.625   761  1482 D InputDispatcher: Focused application set to: xxxx
08-24 16:35:45.625   761  1482 D InputDispatcher: Focus left window: 4434
08-24 16:35:45.625  6273  6273 D AndroidRuntime: Shutting down VM
08-24 16:35:45.635   292   292 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-24 16:35:45.655  6408  6408 E Zygote  : v2
08-24 16:35:45.655  6408  6408 I libpersona: KNOX_SDCARD checking this for 10049
08-24 16:35:45.655  6408  6408 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:45.655  6408  6408 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:45.655  6408  6408 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:45.655   761  2296 I ActivityManager: Start proc 6408:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-24 16:35:45.655  6408  6408 E Zygote  : accessInfo : 0
08-24 16:35:45.655  6396  6396 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.655  6396  6396 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.655  6408  6408 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-24 16:35:45.665  5372  5372 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-24 16:35:45.665   761   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:761 uid:1000
08-24 16:35:45.665   761   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 16:35:45.665   761   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:761 uid:1000
08-24 16:35:45.665   761   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 16:35:45.665   761   903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-24 16:35:45.665   761   855 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d6dbeab u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-24 16:35:45.675  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-24 16:35:45.675  4145  6393 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-24 16:35:45.675   761  1422 V WindowOrientationListener: setCurrentAppOrientation :-1
08-24 16:35:45.675   761  1422 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-24 16:35:45.685  6408  6408 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:45.685  6408  6408 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:45.695   761   903 V WindowStateAnimator: Finishing drawing window Window{eca72e3 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-24 16:35:45.695   761  1422 D ActivityManager:  Launching com.test.thalitest, updated priority
08-24 16:35:45.705   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe9cd364
08-24 16:35:45.715  1724  1933 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-24 16:35:45.715  1724  1724 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-24 16:35:45.725   292   363 D libEGL  : eglTerminate EGLDisplay = 0xb694164c
08-24 16:35:45.725   292   363 D libEGL  : eglTerminate EGLDisplay = 0xb694164c
08-24 16:35:45.735   292   372 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-24 16:35:45.735   292  1498 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-24 16:35:45.755   761   853 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-24 16:35:45.765   292  1497 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-24 16:35:45.765  6396  6396 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 16:35:45.765   292   363 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-24 16:35:45.765   761   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c275a3f 6408:com.android.mms/u0a49}
08-24 16:35:45.775   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd3a4
08-24 16:35:45.775   761  1622 I ActivityManager: Killing 5490:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-24 16:35:45.775   761  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 16:35:45.775   761   855 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{eca72e3 u0 d0 Starting com.test.thalitest}
08-24 16:35:45.775  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-24 16:35:45.785  2319  2330 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-24 16:35:45.785  1724  1724 D Launcher: onTrimMemory. Level: 20
08-24 16:35:45.785  1724  1724 V ActivityThread: updateVisibility : ActivityRecord{76dcdf2 token=android.os.BinderProxy@594286d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 16:35:45.795  4434  4434 V ActivityThread: updateVisibility : ActivityRecord{8724619 token=android.os.BinderProxy@21d3de2 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-24 16:35:45.795  6396  6396 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 16:35:45.795  6396  6396 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 16:35:45.805  6408  6408 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-24 16:35:45.815   761  1422 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
08-24 16:35:45.815  6396  6396 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-24 16:35:45.855  6408  6408 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-24 16:35:45.855  6396  6396 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 16:35:45.865  6408  6408 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-24 16:35:45.865  6396  6396 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 16:35:45.875  6396  6396 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 96-99)
,08-24 16:35:45.875  6396  6396 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 16:35:45.875  1819  6362 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 503 ms] updated apps [took 503 ms] 
,08-24 16:35:45.895  6396  6396 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3942014}
08-24 16:35:45.895  6396  6396 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 16:35:45.895  6396  6396 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 16:35:45.895  6396  6423 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-24 16:35:45.905   761   771 I art     : Background partial concurrent mark sweep GC freed 147892(9MB) AllocSpace objects, 11(2MB) LOS objects, 27% free, 42MB/58MB, paused 2.585ms total 163.737ms
,08-24 16:35:45.905  6396  6396 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 16:35:45.925  6408  6408 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-24 16:35:45.925  6396  6396 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 16:35:45.925  6396  6396 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 16:35:45.925  6396  6396 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 16:35:45.925  6396  6396 I Adreno-EGL: Local Branch: ss
08-24 16:35:45.925  6396  6396 I Adreno-EGL: Remote Branch: 
08-24 16:35:45.925  6396  6396 I Adreno-EGL: Local Patches: 
08-24 16:35:45.925  6396  6396 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:35:45.935  6408  6430 D Mms/ArtClassLoader: init before art third
,08-24 16:35:45.935  6396  6396 D libEGL  : eglInitialize EGLDisplay = 0xbe9dddac
,08-24 16:35:45.935  6408  6429 D Mms/ArtClassLoader: init before art second
,08-24 16:35:45.935  6408  6428 D Mms/ArtClassLoader: init before art first
,08-24 16:35:45.945  6408  6408 D Mms/TelephonyPermission: start operation mode monitor
08-24 16:35:45.945  6408  6408 D Mms/TelephonyPermission: User ID is null set current User Id
,08-24 16:35:45.955  6408  6408 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 16:35:45.965  6408  6430 D Mms/ArtClassLoader: init [DONE] art
,08-24 16:35:45.965  6408  6408 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 16:35:45.965   761  1614 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-24 16:35:45.965   761  1614 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-24 16:35:46.005  6408  6408 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-24 16:35:46.005  6408  6408 D Mms/TelephonyPermission: isDefault true
,08-24 16:35:46.005  6408  6408 D Mms/MmsApp: onCreate() com.android.mms
,08-24 16:35:46.015  6396  6396 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-24 16:35:46.025  6396  6396 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 16:35:46.025  6396  6396 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-24 16:35:46.025  6396  6396 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-24 16:35:46.025  6396  6396 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-24 16:35:46.045  6408  6408 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-24 16:35:46.055  6408  6408 D Mms/MmsApp: [start]    initCountryIso consume time = 123.612241
,08-24 16:35:46.055  6396  6396 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-24 16:35:46.055  6396  6396 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 16:35:46.055   761  1622 D CountryDetector: The first listener is added
,08-24 16:35:46.075  6408  6428 D Mms/ArtClassLoader: init [DONE] art
,08-24 16:35:46.075  6408  6408 D Mms/MmsApp: [end]    initCountryIso consume time = 22.380833
08-24 16:35:46.075  6408  6408 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.250781
,08-24 16:35:46.085  6408  6408 D Mms/MmsConfig: before partial update
,08-24 16:35:46.115  6408  6429 D Mms/ArtClassLoader: init [DONE] art
,08-24 16:35:46.135  6396  6396 D SecWifiDisplayUtil: Metadata value : none
,08-24 16:35:46.145  6396  6396 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{be20612 I.E...... R.....ID 0,0-0,0}
,08-24 16:35:46.145  6408  6408 D Mms/MmsConfig: Load Resize quality : 80
,08-24 16:35:46.145  6396  6453 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 16:35:46.155   761  1732 D ISSUE_DEBUG: InputChannelName : 7eeaa58 com.test.thalitest/com.test.thalitest.MainActivity
,08-24 16:35:46.155   761  1315 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-24 16:35:46.155   761  1315 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 16:35:46.155   761   761 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 16:35:46.155   761   761 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 16:35:46.165  6408  6408 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 16:35:46.165  6408  6408 D EasySignUpManager_1.0.5: isAuth is false
08-24 16:35:46.165  6408  6408 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-24 16:35:46.165  6408  6408 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-24 16:35:46.165  6408  6408 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-24 16:35:46.175  6408  6408 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 16:35:46.175  6408  6408 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-24 16:35:46.175  6408  6408 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 16:35:46.175  6408  6408 D EasySignUpManager_1.0.5: isAuth is false
08-24 16:35:46.175  6408  6408 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-24 16:35:46.175  6408  6408 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-24 16:35:46.175  6396  6396 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6396
,08-24 16:35:46.175   761   774 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6396 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:35:46.175   761  1327 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-24 16:35:46.175   761  1327 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 16:35:46.175   761  1327 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-24 16:35:46.175   761  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-24 16:35:46.175   761  1327 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:35:46.195  1707  1722 D TP/MmsSmsProvider: query, match:2117, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.195  1707  1722 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.031 ms
08-24 16:35:46.195  6396  6423 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-24 16:35:46.195  6396  6396 D SecWifiDisplayUtil: Metadata value : none
,08-24 16:35:46.205  6408  6408 E CscParser: mps_code.dat does not exist
08-24 16:35:46.205  6408  6408 E CscParser: customer_path =/system/csc/customer.xml
08-24 16:35:46.205   292   292 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
08-24 16:35:46.205  6408  6408 E CscParser: fileName + /system/csc/customer.xml
,08-24 16:35:46.205   761   774 D InputDispatcher: Focus entered window: 6396
,08-24 16:35:46.205   761   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:761 uid:1000
08-24 16:35:46.205   761   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 16:35:46.205   761   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:761 uid:1000
08-24 16:35:46.205   761   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 16:35:46.215  6396  6453 D libEGL  : eglInitialize EGLDisplay = 0x9ca7f7c4
08-24 16:35:46.215  6396  6453 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 16:35:46.215  6408  6408 E CscParser: mps_code.dat does not exist
08-24 16:35:46.215  6408  6408 E CscParser: customer_path =/system/csc/customer.xml
08-24 16:35:46.215  6408  6408 E CscParser: fileName + /system/csc/customer.xml
,08-24 16:35:46.225  6408  6408 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-24 16:35:46.225  6408  6408 D Mms/MmsConfig:  enable multiwindow = true
,08-24 16:35:46.225  6408  6408 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-24 16:35:46.225  6408  6408 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-24 16:35:46.225  6408  6408 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-24 16:35:46.225  6408  6408 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-24 16:35:46.225  6408  6408 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-24 16:35:46.225  6408  6408 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-24 16:35:46.225  6408  6408 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 16:35:46.225  6408  6408 D Mms/MmsConfig: [end]    init() consume time = 154.424583
,08-24 16:35:46.235  6408  6408 D Mms/Contact: [start]    init() consume time = 4.298334
,08-24 16:35:46.245  1707  5261 D TP/MmsSmsProvider: query, match:13, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.245  1707  5261 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.197 ms
08-24 16:35:46.255  6408  6408 D Mms/Contact: [end]    init consume time = 18.25224
,08-24 16:35:46.255  6408  6461 D Mms/DraftCache: [start]    rebuildCache consume time = 3.354843
,08-24 16:35:46.265  1707  2511 D TP/MmsSmsProvider: query, match:12, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.265  1707  2511 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.927 ms
,08-24 16:35:46.265  6408  6408 D Mms:transaction: roaming -> false (slotId = 0)
08-24 16:35:46.265  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 16:35:46.265  6408  6408 D Mms:transaction: auto download without roaming -> true
,08-24 16:35:46.265  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 16:35:46.265  6408  6408 D Mms:transaction: roaming -> false (slotId = 1)
,08-24 16:35:46.265  6408  6461 D Mms/DraftCache: [end]    rebuildCache consume time = 15.959114
08-24 16:35:46.275  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 16:35:46.275  6408  6408 D Mms:transaction: auto download without roaming -> true
08-24 16:35:46.275  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 16:35:46.275  6408  6408 D Mms:transaction: auto download during roaming secondary -> false
08-24 16:35:46.275  6408  6408 D Mms:transaction: mAutoDownload ------> true
,08-24 16:35:46.275  6396  6396 V ActivityThread: updateVisibility : ActivityRecord{9c95755 token=android.os.BinderProxy@738919d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 16:35:46.275  6396  6396 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-24 16:35:46.285  6396  6396 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 16:35:46.285   761  2296 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 16:35:46.295  6396  6396 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 16:35:46.315   761  1315 V WindowStateAnimator: Finishing drawing window Window{7eeaa58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-24 16:35:46.315  6396  6396 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 16:35:46.315  6396  6396 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@738919d time:100548
,08-24 16:35:46.325   761   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 16:35:46.325   761   761 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 16:35:46.325   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe9cd364
,08-24 16:35:46.325   761   761 I KnoxTimeoutHandler: SD activityfalse
,08-24 16:35:46.325   761   903 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +574ms (total +720ms)
,08-24 16:35:46.325   761   903 D ActivityManager: mDVFSHelper.release()
08-24 16:35:46.325   761   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a21ff4f u0 com.test.thalitest/.MainActivity t168} time:100558
,08-24 16:35:46.335   761   903 D ViewRootImpl: #3 mView = null
,08-24 16:35:46.335   292   363 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-24 16:35:46.335   292  1498 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-24 16:35:46.335   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd3a4
,08-24 16:35:46.345  6408  6408 D ComposerPerformance: 1472049346354 ms / [DONE] Composer constructor
,08-24 16:35:46.355  6408  6408 D CII     : Log Level [5]
,08-24 16:35:46.355  6408  6465 D Mms/Conversation: [start]    init() consume time = 82.176407
08-24 16:35:46.355  6408  6408 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-24 16:35:46.355  1707  1720 D TP/MmsSmsProvider: delete, match:1, calling pid = 6408
,08-24 16:35:46.355  1707  1720 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-24 16:35:46.355  1707  1720 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-24 16:35:46.355  6408  6408 I Mms/ReservationManager: ReservationManager()
,08-24 16:35:46.355  6408  6408 I Mms/ReservationManager: resetAfterConnected()
,08-24 16:35:46.365  1707  1720 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-24 16:35:46.365  1707  1720 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-24 16:35:46.365  1707  1720 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-24 16:35:46.365  1707  1945 D TP/MmsSmsProvider: query, match:7, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.365  1707  1945 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.607 ms
,08-24 16:35:46.365  1707  1720 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-24 16:35:46.375  6396  6466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 16:35:46.375  1707  1720 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-24 16:35:46.375  1707  1720 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-24 16:35:46.375  1707  1720 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 16:35:46.375  1707  1720 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 11.877 ms
08-24 16:35:46.375  1707  1720 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 16:35:46.375  6396  6466 D libEGL  : eglInitialize EGLDisplay = 0x9b52f3ec
,08-24 16:35:46.375  6408  6465 D Mms/Conversation: [end]    init consume time = 27.896926
,08-24 16:35:46.385  6408  6465 D Mms/MessagingNotification: [start]    init() consume time = 2.975157
,08-24 16:35:46.385  6408  6408 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 16:35:46.385  6408  6465 D Mms/MessagingNotification: [end]    init consume time = 3.659844
,08-24 16:35:46.385  6408  6408 D Mms/MmsApp: [end]    onCreate() consume time = 0.883854
08-24 16:35:46.385  6408  6408 D Mms/MmsApp: [end]    onCreate() consume time = 0.08151
,08-24 16:35:46.385  6408  6469 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.269323
08-24 16:35:46.385  6408  6408 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-24 16:35:46.395  6408  6408 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-24 16:35:46.405   761  1732 I ActivityManager: Start proc 6471:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-24 16:35:46.405  6471  6471 E Zygote  : v2
08-24 16:35:46.405  6471  6471 I libpersona: KNOX_SDCARD checking this for 1000
08-24 16:35:46.405  6471  6471 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:46.405  6471  6471 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 16:35:46.405  6471  6471 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:46.405  6471  6471 E Zygote  : accessInfo : 0
,08-24 16:35:46.405   761  1732 I ActivityManager: Killing 3987:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-24 16:35:46.415  1707  2511 D TP/MmsSmsProvider: query, match:400, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.425  1707  1722 D TP/MmsSmsProvider: query, match:0, calling pid = 6408, accessRestricted = false
08-24 16:35:46.425  1707  1722 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 16:35:46.425  1707  1722 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.042 ms
,08-24 16:35:46.425  6408  6469 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 38.527969
,08-24 16:35:46.435  6085  6095 D BadgeProvider: query, [selection] : package=?
,08-24 16:35:46.435  6408  6465 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-24 16:35:46.435  6396  6396 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6396
,08-24 16:35:46.445  6408  6408 D Mms:transaction: roaming -> false (slotId = 0)
08-24 16:35:46.445  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 16:35:46.445  6408  6408 D Mms:transaction: auto download without roaming -> true
08-24 16:35:46.445  6408  6408 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 16:35:46.445  6408  6408 D Mms:transaction: mAutoDownload ------> true
08-24 16:35:46.445  6408  6470 D Mms/Synchronizer: [start]    doSync consume time = 16.455209
,08-24 16:35:46.445  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 16:35:46.445  6471  6471 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:46.455  1707  1722 D TP/MmsSmsProvider: update, match:300, calling pid = 6408
,08-24 16:35:46.455  1707  1722 V TP/MmsSmsProvider: syncDBData start
08-24 16:35:46.455  1707  2511 D TP/SmsProvider: query,matched:26, calling pid = 6408
,08-24 16:35:46.455  1707  1722 V TP/MmsSmsProvider: syncDBData sms end
,08-24 16:35:46.455  1707  1722 V TP/MmsSmsProvider: syncDBData mms end
,08-24 16:35:46.455  1707  2511 D TP/SmsProvider: query, match 26:Elapsed time : 1.714 ms
,08-24 16:35:46.455  1707  1722 V TP/MmsSmsProvider: syncDBData end
,08-24 16:35:46.455  1707  1722 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.347 ms
,08-24 16:35:46.465   761   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{526bf21 6471:com.samsung.android.bbc.bbcagent/1000}
,08-24 16:35:46.465  6408  6470 D Mms/Synchronizer: [end]    doSync consume time = 21.638385
,08-24 16:35:46.465   761  1614 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-24 16:35:46.495  6471  6471 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-24 16:35:46.495  1707  5261 D TP/MmsSmsProvider: query, match:6, calling pid = 6408, accessRestricted = false
,08-24 16:35:46.495  1707  5261 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.323 ms
,08-24 16:35:46.515  6471  6471 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-24 16:35:46.525  6485  6485 E Zygote  : v2
08-24 16:35:46.525   761   774 I ActivityManager: Start proc 6485:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-24 16:35:46.525  6485  6485 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:46.525  6485  6485 I libpersona: KNOX_SDCARD checking this for 10024
08-24 16:35:46.525  6485  6485 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:46.525  6485  6485 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:46.525  6485  6485 E Zygote  : accessInfo : 0
08-24 16:35:46.525  6485  6485 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-24 16:35:46.545  6485  6485 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:46.545  6485  6485 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:46.555   761  1732 I ActivityManager: Killing 5533:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-24 16:35:46.555  6396  6396 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 16:35:46.565   761  1315 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-24 16:35:46.575  6485  6485 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-24 16:35:46.585   761  1622 I ActivityManager: Start proc 6498:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-24 16:35:46.585  6498  6498 E Zygote  : v2
08-24 16:35:46.585  6498  6498 I libpersona: KNOX_SDCARD checking this for 10097
08-24 16:35:46.585  6498  6498 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:46.585  6498  6498 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:46.585  6498  6498 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:46.585  6498  6498 E Zygote  : accessInfo : 0
,08-24 16:35:46.585  6498  6498 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-24 16:35:46.585   761  1622 I ActivityManager: Killing 5143:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-24 16:35:46.615  6485  6485 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-24 16:35:46.615  6498  6498 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:46.615  6498  6498 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:46.635   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4419f46 6498:com.google.android.apps.docs/u0a97}
,08-24 16:35:46.635   761  1723 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-24 16:35:46.665  6498  6498 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 16:35:46.685  6485  6485 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-24 16:35:46.705  6408  6465 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-24 16:35:46.715  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-24 16:35:46.725  6485  6485 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-24 16:35:46.735  6498  6498 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-24 16:35:46.745  6396  6510 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1695499984
,08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 16:35:46.755  6396  6510 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f769d3 added. We now have 1 listener(s)
,08-24 16:35:46.755  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-24 16:35:46.755  6396  6510 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-24 16:35:46.755  6396  6510 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:35:46.755  6396  6510 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 16:35:46.765  6396  6510 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2afee0e added. We now have 1 listener(s)
08-24 16:35:46.765  6396  6510 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:35:46.765  6396  6510 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-24 16:35:46.775   761  3425 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-24 16:35:46.775  6396  6510 D BluetoothAdapter: STATE_ON
,08-24 16:35:46.775  6396  6510 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:35:46.775  6396  6510 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:35:46.775  6396  6510 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 16:35:46.775  6396  6510 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:35:46.785  6396  6510 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 16:35:46.785   761  3463 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 16:35:46.785  6396  6396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:35:46.785  6396  6396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:35:46.805  6396  6396 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 16:35:46.875  4145  5083 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-24 16:35:46.935  4145  5083 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-24 16:35:47.015  4145  5083 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-24 16:35:47.035   761  6202 I HarmonyEASService: Updating for all 1
,08-24 16:35:47.085  6498  6514 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-24 16:35:47.085  6498  6514 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 16:35:47.085  6498  6514 I GAv4    :   adb logcat -s GAv4
,08-24 16:35:47.105  6498  6514 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 16:35:47.105   761  2268 V AlarmManager:  remove PendingIntent] PendingIntent{61c67cc: PendingIntentRecord{5808a15 com.google.android.apps.docs broadcastIntent}}
,08-24 16:35:47.105  6498  6514 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:35:47.115  6498  6514 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:35:47.115  6498  6521 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:35:47.155  1449  1449 D Recents : onTaskStackChanged
,08-24 16:35:47.165  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 16:35:47.205  6498  6498 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-24 16:35:47.205  6498  6498 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-24 16:35:47.225  6498  6514 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-24 16:35:47.225  6498  6514 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-24 16:35:47.225  6498  6514 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-24 16:35:47.225  6498  6514 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-24 16:35:47.275  6527  6527 E Zygote  : v2
08-24 16:35:47.275  6527  6527 I libpersona: KNOX_SDCARD checking this for 10098
08-24 16:35:47.275  6527  6527 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:47.275  6527  6527 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:47.275  6527  6527 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:47.275  6527  6527 E Zygote  : accessInfo : 0
,08-24 16:35:47.275  6527  6527 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-24 16:35:47.275   761  1614 I ActivityManager: Start proc 6527:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-24 16:35:47.285   761  1614 I ActivityManager: Killing 5153:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-24 16:35:47.305   761  1738 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-24 16:35:47.305  6527  6527 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:47.305  6527  6527 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:47.315   761  2296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aecb291 6527:com.sec.android.automotive.drivelink/u0a98}
,08-24 16:35:47.325  6527  6527 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 16:35:47.335  2050  2050 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 16:35:47.335  2050  2050 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 16:35:47.345  6527  6527 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-24 16:35:47.355  2050  2050 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 16:35:47.385  6527  6527 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-24 16:35:47.395   761  1622 V AlarmManager:  remove PendingIntent] PendingIntent{b5a22c9: PendingIntentRecord{c703dce com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 16:35:47.405  6527  6543 I GMPM    : App measurement is starting up
,08-24 16:35:47.415  6527  6527 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-24 16:35:47.415  6498  6515 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 16:35:47.415  6527  6543 E GMPM    : getGoogleAppId failed with status: 10
,08-24 16:35:47.415  6527  6543 E GMPM    : Uploading is not possible. App measurement disabled
,08-24 16:35:47.415   761  1801 V AlarmManager:  remove PendingIntent] PendingIntent{9f344ef: PendingIntentRecord{c703dce com.sec.android.automotive.drivelink broadcastIntent}}
,08-24 16:35:47.445  6527  6527 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-24 16:35:47.445  6527  6527 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-24 16:35:47.465  6498  6515 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-24 16:35:47.495  6549  6549 E Zygote  : v2
,08-24 16:35:47.495  6549  6549 I libpersona: KNOX_SDCARD checking this for 10032
08-24 16:35:47.495  6549  6549 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:47.495   761   774 I ActivityManager: Start proc 6549:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-24 16:35:47.495  6549  6549 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:47.495  6549  6549 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:47.495   761  1318 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 16:35:47.495  6549  6549 E Zygote  : accessInfo : 0
,08-24 16:35:47.495  6549  6549 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-24 16:35:47.505  6498  6515 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 16:35:47.505  6498  6515 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-24 16:35:47.505  6498  6515 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 16:35:47.525  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 16:35:47.525  6549  6549 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:47.535   761  1318 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-24 16:35:47.535  6549  6549 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-24 16:35:47.555  6549  6549 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-24 16:35:47.555  6498  6515 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 16:35:47.635  6527  6527 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-24 16:35:47.635  6527  6527 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-24 16:35:47.645  6396  6511 W jxcore-log: Initializing JXcore engine
08-24 16:35:47.645  6527  6527 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-24 16:35:47.645  6396  6511 W jxcore-log: JXcore engine is ready
,08-24 16:35:47.665  6527  6527 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 24 16:35:47 GMT+02:00 2016
,08-24 16:35:47.675   761  1622 I ActivityManager: Start proc 6563:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-24 16:35:47.675  6563  6563 E Zygote  : v2
08-24 16:35:47.675  6563  6563 I libpersona: KNOX_SDCARD checking this for 1000
08-24 16:35:47.675  6563  6563 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:47.675  6563  6563 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:47.675   761  1622 I ActivityManager: Killing 4654:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-24 16:35:47.675  6563  6563 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:47.675   761  1622 I ActivityManager: Killing 5192:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
08-24 16:35:47.675  6563  6563 E Zygote  : accessInfo : 0
,08-24 16:35:47.675  6527  6527 D DialogFlow: initQueue()
,08-24 16:35:47.695  2231  2231 E audit   : type=1400 msg=audit(1472049347.695:288): avc:  denied  { ioctl } for  pid=6511 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 16:35:47.695  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:47.695  2231  2231 E audit   : type=1300 msg=audit(1472049347.695:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9add03c8 items=0 ppid=350 ppcomm=main pid=6511 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 16:35:47.695  2231  2231 E audit   : type=1327 msg=audit(1472049347.695:288): proctitle="com.test.thalitest"
08-24 16:35:47.695  2231  2231 E audit   : type=1320 msg=audit(1472049347.695:288): 
08-24 16:35:47.695  2231  2231 E audit   : type=1400 msg=audit(1472049347.695:289): avc:  denied  { ioctl } for  pid=6511 comm="Thread-899" path="socket:[38777]" dev="sockfs" ino=38777 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 16:35:47.695  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:47.695  2231  2231 E audit   : type=1300 msg=audit(1472049347.695:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9add03c8 items=0 ppid=350 ppcomm=main pid=6511 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 16:35:47.695  2231  2231 E audit   : type=1327 msg=audit(1472049347.695:289): proctitle="com.test.thalitest"
08-24 16:35:47.695  2231  2231 E audit   : type=1320 msg=audit(1472049347.695:289): 
,08-24 16:35:47.695   761  1614 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-24 16:35:47.705  6563  6563 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:47.705  6563  6563 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:47.705  6396  6511 W jxcore-log: Starting JXcore engine
,08-24 16:35:47.715   761  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e59410b 6563:com.samsung.android.app.filterinstaller/1000}
,08-24 16:35:47.715  6549  6549 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-24 16:35:47.715   761  1738 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-24 16:35:47.725  6563  6563 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-24 16:35:47.735  6563  6563 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-24 16:35:47.735  6549  6549 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-24 16:35:47.745  6563  6563 E FilterPackageIntentReceiver: This package is not a effect filter
,08-24 16:35:47.755  6576  6576 E Zygote  : v2
,08-24 16:35:47.755  6576  6576 I libpersona: KNOX_SDCARD checking this for 1000
08-24 16:35:47.755  6576  6576 I libpersona: KNOX_SDCARD not a persona
08-24 16:35:47.755   761  1738 I ActivityManager: Start proc 6576:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-24 16:35:47.755  6576  6576 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:47.755  6576  6576 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:47.755  6576  6576 E Zygote  : accessInfo : 0
,08-24 16:35:47.755   761  1738 I ActivityManager: Killing 5084:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-24 16:35:47.775  6576  6576 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:47.775  6576  6576 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:47.785   761  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d8e2e7 6576:com.samsung.helphub/1000}
,08-24 16:35:47.795   761  1614 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-24 16:35:47.795  6576  6576 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-24 16:35:47.795  6396  6511 W jxcore-log: Platform android
08-24 16:35:47.795  6396  6511 W jxcore-log: 
08-24 16:35:47.795  6396  6511 W jxcore-log: Process ARCH arm
08-24 16:35:47.795  6396  6511 W jxcore-log: 
,08-24 16:35:47.805   761   775 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-24 16:35:47.805  6576  6576 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-24 16:35:47.825  6549  6549 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-24 16:35:47.825  6549  6549 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-24 16:35:47.835  6549  6549 D DialogFlow: initQueue()
,08-24 16:35:47.855  6591  6591 E Zygote  : v2
08-24 16:35:47.855  6591  6591 I libpersona: KNOX_SDCARD checking this for 1000
08-24 16:35:47.855  6591  6591 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:47.855   761   775 I ActivityManager: Start proc 6591:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-24 16:35:47.855  6591  6591 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:47.855  6591  6591 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:47.855  6591  6591 E Zygote  : accessInfo : 0
,08-24 16:35:47.855   761   775 I ActivityManager: Killing 5360:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-24 16:35:47.875  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:47.875  6591  6591 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:47.875   761  1315 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-24 16:35:47.885   761  2296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4db67e 6591:com.samsung.android.app.mirrorlink/1000}
,08-24 16:35:47.895  6591  6591 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-24 16:35:47.905  6591  6591 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-24 16:35:47.935  6591  6591 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-24 16:35:47.935  6591  6591 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-24 16:35:47.945   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{943ffca 5756:com.google.android.apps.plus/u0a134}
,08-24 16:35:47.955   761  2296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{943ffca 5756:com.google.android.apps.plus/u0a134}
,08-24 16:35:47.965   761  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{943ffca 5756:com.google.android.apps.plus/u0a134}
,08-24 16:35:47.995   761  1614 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-24 16:35:47.995  6396  6511 I jxcore-log: JXcore Cordova bridge is ready!
08-24 16:35:47.995  6396  6511 I jxcore-log: 
,08-24 16:35:47.995  6396  6511 W jxcore-log: JXcore engine is started
08-24 16:35:47.995   761  1738 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-24 16:35:47.995   761  1801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-24 16:35:47.995   761  2268 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-24 16:35:48.005   761  1315 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-24 16:35:48.005  6396  6510 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 16:35:48.005   761  1732 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-24 16:35:48.005  6396  6396 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 16:35:48.005   761   774 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-24 16:35:48.005   761  1614 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-24 16:35:48.045   761  1315 I ActivityManager: Start proc 6605:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-24 16:35:48.045  6605  6605 E Zygote  : v2
08-24 16:35:48.045  6605  6605 I libpersona: KNOX_SDCARD checking this for 10165
08-24 16:35:48.045  6605  6605 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:48.045  6605  6605 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:48.045  6605  6605 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:48.045  6605  6605 E Zygote  : accessInfo : 0
,08-24 16:35:48.045  6605  6605 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-24 16:35:48.045   761  1732 I ActivityManager: Killing 5612:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-24 16:35:48.065   761   774 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-24 16:35:48.075  6605  6605 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:48.075  6605  6605 D ActivityThread: Added TimaKeyStore provider
,08-24 16:35:48.085   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b80b6f5 6605:com.sec.kidsplat.installer/u0a165}
,08-24 16:35:48.085  6605  6605 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-24 16:35:48.095  6605  6605 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-24 16:35:48.105   761  2296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b80b6f5 6605:com.sec.kidsplat.installer/u0a165}
,08-24 16:35:48.105  6605  6605 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-24 16:35:48.125   761  1801 I ActivityManager: Start proc 6617:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-24 16:35:48.125   761  1801 I ActivityManager: Killing 5583:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-24 16:35:48.125  6617  6617 E Zygote  : v2
08-24 16:35:48.125  6617  6617 I libpersona: KNOX_SDCARD checking this for 10142
08-24 16:35:48.125  6617  6617 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:48.125  6617  6617 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 16:35:48.125  6617  6617 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:48.125  6617  6617 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:48.125  6617  6617 E Zygote  : accessInfo : 64
08-24 16:35:48.125  6617  6617 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 16:35:48.125  6617  6617 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-24 16:35:48.125  6617  6617 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-24 16:35:48.145   761  2268 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
08-24 16:35:48.155  6617  6617 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:35:48.155  6617  6617 D ActivityThread: Added TimaKeyStore provider
08-24 16:35:48.165   761  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40abc8a 6617:com.sec.android.app.sbrowser/u0a142}
,08-24 16:35:48.165  6617  6617 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 16:35:48.195  6617  6617 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-24 16:35:48.255  6617  6617 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 16:35:48.255  6617  6617 D ManifestProvider: onCreate()
,08-24 16:35:48.265  6617  6617 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-24 16:35:48.275  6617  6617 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-24 16:35:48.275  6617  6617 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 16:35:48.275  6617  6617 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-24 16:35:48.275  6617  6617 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-24 16:35:48.275  6617  6617 D [MM]MHDataBaseProvider: onCreate()
,08-24 16:35:48.295  6617  6617 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@98fdbb9)
,08-24 16:35:48.315   761   774 I ActivityManager: Killing 5741:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-24 16:35:48.315   761   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf10bd0 2050:com.google.android.gms.persistent/u0a11}
,08-24 16:35:48.325   761  1801 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-24 16:35:48.335  4145  6632 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 16:35:48.335  4145  6631 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-24 16:35:48.335   761  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f967aa 4145:com.google.android.gms/u0a11}
,08-24 16:35:48.345  4145  6632 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 16:35:48.355  4145  6632 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 16:35:48.365  4145  4145 D AsyncTaskServiceImpl: Submit a task: nzm
,08-24 16:35:48.365  4145  6632 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 16:35:48.375   761  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf10bd0 2050:com.google.android.gms.persistent/u0a11}
,08-24 16:35:48.385   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f967aa 4145:com.google.android.gms/u0a11}
,08-24 16:35:48.395  4145  4145 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 16:35:48.395  4145  5026 D nzm     : Processing package: com.test.thalitest
,08-24 16:35:48.425  6408  6408 I Mms/MmsApp:  start initViewCache mms
,08-24 16:35:48.435  4145  5026 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-24 16:35:48.435  4145  5026 D nzm     : Found info for package com.test.thalitest in db.
,08-24 16:35:48.505   761  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{263868a 5780:com.android.vending/u0a29}
,08-24 16:35:48.545   761  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d3d655d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4e38729 6128:com.sec.android.app.samsungapps/u0a39}
,08-24 16:35:48.555   761   771 I art     : Background partial concurrent mark sweep GC freed 26037(1653KB) AllocSpace objects, 1(20KB) LOS objects, 27% free, 42MB/58MB, paused 1.699ms total 110.561ms
,08-24 16:35:48.555   761  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fae4765 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf10bd0 2050:com.google.android.gms.persistent/u0a11}
,08-24 16:35:48.555  5780  5780 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-24 16:35:48.565  2050  2050 D WearableService: callingUid 10011, callindPid: 2050
,08-24 16:35:48.565  5780  5780 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-24 16:35:48.575   761  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c0f4e1 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{263868a 5780:com.android.vending/u0a29}
,08-24 16:35:48.595   761   774 V AlarmManager:  remove PendingIntent] PendingIntent{d2386f4: PendingIntentRecord{779ed80 com.google.android.gms broadcastIntent}}
,08-24 16:35:48.605   761  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff6fe1d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf682c7 5828:com.sec.android.app.shealth/u0a34}
,08-24 16:35:48.605  5780  5780 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 16:35:48.605  5780  5780 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-24 16:35:48.615  5780  6639 I Finsky  : [827] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-24 16:35:48.615  5780  5804 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 16:35:48.615   761  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff6fe1d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dca88a3 1882:com.sec.android.app.shealth:remote/u0a34}
,08-24 16:35:48.645  5780  6640 I PlayCommon: [828] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-24 16:35:48.645  5780  6640 I PlayCommon: [828] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-24 16:35:48.645   761  1738 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff6fe1d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dca88a3 1882:com.sec.android.app.shealth:remote/u0a34}
,08-24 16:35:48.665   761  1362 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-24 16:35:48.675   761   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{23a4bde u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf10bd0 2050:com.google.android.gms.persistent/u0a11}
,08-24 16:35:48.705  2050  2050 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 16:35:48.735  5780  5804 I PlayCommon: [797] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-24 16:35:48.735  5780  5804 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 16:35:48.735  5780  5804 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 16:35:48.755   305  1187 D EnterpriseController: netId is 0
08-24 16:35:48.755   305  1187 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-24 16:35:48.765  6549  6590 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 16:35:48.765  6549  6590 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 16:35:48.805  6549  6590 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 16:35:48.805  6549  6590 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 16:35:48.805  6549  6590 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-24 16:35:48.815  6549  6590 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 16:35:48.815  6549  6590 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 16:35:48.855  6408  6408 D Mms/BubbleViewCache: fillCache bubble = 4
,08-24 16:35:49.095  5780  5804 I PlayCommon: [797] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-24 16:35:49.105  5780  5804 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 16:35:49.105  5780  5804 I PlayCommon: [797] com.google.android.play.a.al.e(732): No file ready to send
,08-24 16:35:49.735  4145  5038 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-24 16:35:49.815  4145  5038 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 16:35:49.835  4145  5038 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 16:35:49.835  4145  5038 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-24 16:35:51.785   761  3463 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 16:35:51.785   761  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 16:35:53.395  3500  3500 D FactoryTest: User mode
08-24 16:35:53.395  3500  3500 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-24 16:35:53.395  3500  3500 D MTPRx   : still no open session command from host, so toast
08-24 16:35:53.405   761   774 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-24 16:35:53.415   761   774 D ActivityManager: mDVFSHelper.acquire()
08-24 16:35:53.415   761   774 V WindowManager: addAppToken: AppWindowToken{f5df8b6 token=Token{f5fd851 ActivityRecord{9635978 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
08-24 16:35:53.415   761   774 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
08-24 16:35:53.425   761   853 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-24 16:35:53.435   761   774 D InputDispatcher: Focused application set to: xxxx
08-24 16:35:53.445   761   774 D InputDispatcher: Focus left window: 6396
08-24 16:35:53.445   761   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:761 uid:1000
08-24 16:35:53.445   761   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 16:35:53.445   761   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:761 uid:1000
08-24 16:35:53.445   761   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 16:35:53.455   761  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 16:35:53.455  3500  3500 E MTPRx   : started activity for popup
08-24 16:35:53.455  3500  3500 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-24 16:35:53.465  3500  3500 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-24 16:35:53.475  3500  3500 D MTPUSBConnection: onCreate in USBConnection
08-24 16:35:53.475  3500  3500 V MTPUSBConnection: Registering broadcast receiver.
08-24 16:35:53.475  3500  3500 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
08-24 16:35:53.475   761  2296 D SecContentProvider2: query(), uri = 14 selection = getSealedState
08-24 16:35:53.525  3500  3500 D TAG     : dev.kiessupport is : TRUE
08-24 16:35:53.545  3500  3500 D SecWifiDisplayUtil: Metadata value : none
08-24 16:35:53.555  3500  3500 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b3d1dcd V.E...... R.....I. 0,0-0,0}
08-24 16:35:53.555  3500  6682 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-24 16:35:53.555   761  1422 D ISSUE_DEBUG: InputChannelName : 2ff688e com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-24 16:35:53.555   761  1422 D InputDispatcher: Focus entered window: 3500
08-24 16:35:53.555   761   855 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2ff688e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-24 16:35:53.555  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-24 16:35:53.555   761   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:761 uid:1000
08-24 16:35:53.555   761   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 16:35:53.555   761   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:761 uid:1000
08-24 16:35:53.555   761   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 16:35:53.565  3500  3500 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9ed3985 I.E...... R.....I. 0,0-0,0}
08-24 16:35:53.565   761  1422 D ISSUE_DEBUG: InputChannelName : 95f64bc com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-24 16:35:53.575   761  2296 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-24 16:35:53.575   761  2296 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 16:35:53.575   761   761 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 16:35:53.575   761   761 I KnoxTimeoutHandler: Shared devices show user statefalse
08-24 16:35:53.575   761   761 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-24 16:35:53.605   292   292 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-24 16:35:53.625  3500  6682 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 16:35:53.625  3500  6682 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 16:35:53.625  3500  6682 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 16:35:53.625  3500  6682 I Adreno-EGL: Local Branch: ss
08-24 16:35:53.625  3500  6682 I Adreno-EGL: Remote Branch: 
08-24 16:35:53.625  3500  6682 I Adreno-EGL: Local Patches: 
08-24 16:35:53.625  3500  6682 I Adreno-EGL: Reconstruct Branch: 
,08-24 16:35:53.625  3500  6682 D libEGL  : eglInitialize EGLDisplay = 0x9efb57c4
08-24 16:35:53.625  3500  6682 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 16:35:53.655   292   292 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-24 16:35:53.675  3500  3500 V ActivityThread: updateVisibility : ActivityRecord{7ec7ee8 token=android.os.BinderProxy@1a85682 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-24 16:35:53.675  3500  3500 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 16:35:53.765   761  1622 V WindowStateAnimator: Finishing drawing window Window{2ff688e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 16:35:53.765  3500  3500 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 16:35:53.765   761  2268 V WindowStateAnimator: Finishing drawing window Window{95f64bc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 16:35:53.765  3500  3500 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-24 16:35:53.765  3500  3500 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-24 16:35:53.765   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe9cd364
,08-24 16:35:53.765   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe9cd364
,08-24 16:35:53.775   761  1732 V WindowStateAnimator: Finishing drawing window Window{2ff688e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 16:35:53.775   761   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 16:35:53.775   761   761 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 16:35:53.775   761   761 I KnoxTimeoutHandler: SD activityfalse
,08-24 16:35:53.775   761   903 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +340ms (total +363ms)
,08-24 16:35:53.775   761   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9635978 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108005
08-24 16:35:53.775   761   903 D ActivityManager: mDVFSHelper.release()
,08-24 16:35:53.775   761  1801 V WindowStateAnimator: Finishing drawing window Window{95f64bc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 16:35:53.775  3500  3500 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a85682 time:108007
,08-24 16:35:53.785   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe9cd364
,08-24 16:35:54.445   761  3425 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 16:35:54.585  1449  1449 D Recents : onTaskStackChanged
,08-24 16:35:54.595  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 16:35:55.085   761  1231 V AlarmManager: Expired Alarm result :4
,08-24 16:35:55.095   761  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-24 16:35:55.105   761  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 16:35:55.105   761   775 V AlarmManager:  remove PendingIntent] PendingIntent{58d7f9a: PendingIntentRecord{4407ff0 com.google.android.gms broadcastIntent}}
,08-24 16:35:55.155   761  1801 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 16:35:55.155   761  1801 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 16:35:55.155   761  1801 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-24 16:35:55.155   761  1801 D BatteryService: stay LED for charging
08-24 16:35:55.155   761   761 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 16:35:55.155   761   761 I MotionRecognitionService: Plugged
08-24 16:35:55.155   761   761 D MotionRecognitionService:   cableConnection= 1
08-24 16:35:55.155   761   761 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 16:35:55.155   761   761 D MotionRecognitionService: skip setTransmitPower. 
,08-24 16:35:55.155  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 16:35:55.155  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 16:35:55.165  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 16:35:55.175  2225  2225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 16:35:55.175  2225  2718 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 16:35:55.195  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 16:35:55.195  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 16:35:55.195  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 16:35:55.245   761   936 D PackageManager: [MSG] MCS_UNBIND
,08-24 16:35:55.245   761  1622 I ActivityManager: Killing 4770:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-24 16:35:55.265   761  3422 D SSRM:n  : SIOP:: AP = 480, PST = 457, CUR = 350, LCD = 0
,08-24 16:35:55.275   761  1732 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-24 16:35:55.645   761   936 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 16:35:55.675   761   936 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 16:35:56.785   761  3463 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 16:35:58.125  6396  6511 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 16:35:58.125  6396  6511 I jxcore-log: 
,08-24 16:35:58.125  6396  6511 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 16:35:58.125  6396  6511 I jxcore-log: 
,08-24 16:35:58.135  6396  6511 D BluetoothAdapter: STATE_ON
,08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:35:58.135  6396  6511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:35:58.135  6396  6511 D BluetoothAdapter: STATE_ON
,08-24 16:35:58.145  6396  6511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:35:58.145  6396  6511 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 16:35:58.145  6396  6511 I jxcore-log: 
,08-24 16:35:58.145  6396  6511 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 16:35:58.145  6396  6511 I jxcore-log: 
,08-24 16:35:58.675  6396  6511 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 16:35:58.675  6396  6511 I jxcore-log: Failed to execute UT.
08-24 16:35:58.675  6396  6511 I jxcore-log: 
08-24 16:35:58.675  6396  6511 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 16:35:58.675  6396  6511 I jxcore-log: 
,08-24 16:35:58.675  6396  6511 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:35:58.675  6396  6511 I jxcore-log: 
,08-24 16:35:58.695  6396  6396 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 16:35:59.495   761  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 16:35:59.645  2231  2231 E audit   : type=1400 msg=audit(1472049359.645:290): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 16:35:59.645  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:59.645  2231  2231 E audit   : type=1300 msg=audit(1472049359.645:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4016000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 16:35:59.645  2231  2231 E audit   : type=1327 msg=audit(1472049359.645:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 16:35:59.645  2231  2231 E audit   : type=1320 msg=audit(1472049359.645:290): 
,08-24 16:35:59.705  2231  2231 E audit   : type=1400 msg=audit(1472049359.705:291): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 16:35:59.705  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:59.705  2231  2231 E audit   : type=1300 msg=audit(1472049359.705:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd6000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 16:35:59.705  2231  2231 E audit   : type=1327 msg=audit(1472049359.705:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 16:35:59.705  2231  2231 E audit   : type=1320 msg=audit(1472049359.705:291): 
,08-24 16:35:59.745  2231  2231 E audit   : type=1400 msg=audit(1472049359.745:292): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-24 16:35:59.745  6699  6699 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 16:35:59.755  2231  2231 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 16:35:59.755  2231  2231 E audit   : type=1300 msg=audit(1472049359.745:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd6000 a1=51000 a2=5 a3=4 items=0 ppid=3574 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-24 16:35:59.755  2231  2231 E audit   : type=1327 msg=audit(1472049359.745:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-24 16:35:59.755  2231  2231 E audit   : type=1320 msg=audit(1472049359.745:292): 
,08-24 16:35:59.755  6699  6699 D AndroidRuntime: CheckJNI is OFF
,08-24 16:35:59.755  6699  6699 D AndroidRuntime: readGMSProperty: start
08-24 16:35:59.755  6699  6699 D AndroidRuntime: readGMSProperty: already setted!!
,08-24 16:35:59.755  6699  6699 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 16:35:59.765  6699  6699 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 16:35:59.765  6699  6699 D AndroidRuntime: readGMSProperty: end
08-24 16:35:59.765  6699  6699 D AndroidRuntime: addProductProperty: start
,08-24 16:35:59.765  6699  6699 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-24 16:35:59.765  6699  6699 W art     : aee3d000-b1d63000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:59.765  6699  6699 W art     : b1d63000-b3fd2000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:59.765  6699  6699 W art     : b3fd2000-b3fd3000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 16:35:59.765  6699  6699 W art     : b3fd3000-b3fd4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.765  6699  6699 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 16:35:59.765  6699  6699 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 16:35:59.765  6699  6699 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
,08-24 16:35:59.765  6699  6699 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 16:35:59.765  6699  6699 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 16:35:59.765  6699  6699 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-24 16:35:59.765  6699  6699 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 16:35:59.765  6699  6699 W art     : b48a5000-b48a8000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 16:35:59.765  6699  6699 W art     : b48a8000-b48a9000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-24 16:35:59.765  6699  6699 W art     : b48a9000-b48aa000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 16:35:59.765  6699  6699 W art     : b48aa000-b48ab000 r--p 00000000 00:00 0 
08-24 16:35:59.765  6699  6699 W art     : b48ab000-b48cb000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 16:35:59.765  6699  6699 W art     : b48cb000-b52dc000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 16:35:59.765  6699  6699 W art     : b52dc000-b52dd000 ---p 00000000 00:00 0 
08-24 16:35:59.765  6699  6699 W art     : b52dd000-b5326000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 16:35:59.765  6699  6699 W art     : b5326000-b5327000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-24 16:35:59.765  6699  6699 W art     : b5327000-b532f000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b532f000-b5330000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5330000-b5365000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:59.775  6699  6699 W art     : b5365000-b5366000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5366000-b5367000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:59.775  6699  6699 W art     : b5367000-b5368000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 16:35:59.775  6699  6699 W art     : b5368000-b53c0000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-24 16:35:59.775  6699  6699 W art     : b53c0000-b53c1000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b53c1000-b53c2000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 16:35:59.775  6699  6699 W art     : b53c2000-b53c3000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 16:35:59.775  6699  6699 W art     : b53c4000-b53ca000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 16:35:59.775  6699  6699 W art     : b53ca000-b53cb000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 16:35:59.775  6699  6699 W art     : b53cb000-b53cc000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-24 16:35:59.775  6699  6699 W art     : b53cc000-b53ce000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b53cf000-b53d9000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:59.775  6699  6699 W art     : b53d9000-b53dc000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:59.775  6699  6699 W art     : b53dc000-b53dd000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 16:35:59.775  6699  6699 W art     : b53de000-b53f5000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 16:35:59.775  6699  6699 W art     : b53f5000-b53f6000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b53f6000-b53f7000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-24 16:35:59.775  6699  6699 W art     : b53f7000-b53f8000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 16:35:59.775  6699  6699 W art     : b53f9000-b5403000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:59.775  6699  6699 W art     : b5403000-b5404000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:59.775  6699  6699 W art     : b5404000-b5405000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 16:35:59.775  6699  6699 W art     : b5405000-b5409000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-24 16:35:59.775  6699  6699 W art     : b5409000-b540a000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 16:35:59.775  6699  6699 W art     : b540a000-b540b000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 16:35:59.775  6699  6699 W art     : b540b000-b5421000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 16:35:59.775  6699  6699 W art     : b5421000-b5422000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 16:35:59.775  6699  6699 W art     : b5422000-b5423000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-24 16:35:59.775  6699  6699 W art     : b5423000-b5430000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:59.775  6699  6699 W art     : b5430000-b5431000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:59.775  6699  6699 W art     : b5431000-b5432000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 16:35:59.775  6699  6699 W art     : b5432000-b5492000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 16:35:59.775  6699  6699 W art     : b5492000-b5495000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 16:35:59.775  6699  6699 W art     : b5495000-b5499000 rw-p 00000000 00:00 0 
,08-24 16:35:59.775  6699  6699 W art     : b5499000-b54fa000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 16:35:59.775  6699  6699 W art     : b54fa000-b54fb000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 16:35:59.775  6699  6699 W art     : b54fb000-b554a000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-24 16:35:59.775  6699  6699 W art     : b554a000-b554c000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-24 16:35:59.775  6699  6699 W art     : b554c000-b554d000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 16:35:59.775  6699  6699 W art     : b554d000-b554e000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b554e000-b5555000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 16:35:59.775  6699  6699 W art     : b5555000-b5556000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 16:35:59.775  6699  6699 W art     : b5556000-b5557000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-24 16:35:59.775  6699  6699 W art     : avc_common.so
08-24 16:35:59.775  6699  6699 W art     : b5558000-b555b000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 16:35:59.775  6699  6699 W art     : b555b000-b555c000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-24 16:35:59.775  6699  6699 W art     : b555c000-b555d000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-24 16:35:59.775  6699  6699 W art     : enc_common.so
08-24 16:35:59.775  6699  6699 W art     : b555e000-b5562000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 16:35:59.775  6699  6699 W art     : b5562000-b5563000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5563000-b5564000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 16:35:59.775  6699  6699 W art     : b5564000-b5565000 rw-p 00005000 b3:17 2510       /syste
08-24 16:35:59.775  6699  6699 W art     : m/lib/libpowermanager.so
08-24 16:35:59.775  6699  6699 W art     : b5566000-b5583000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 16:35:59.775  6699  6699 W art     : b5583000-b5584000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
,08-24 16:35:59.775  6699  6699 W art     : b5584000-b5585000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 16:35:59.775  6699  6699 W art     : b5586000-b558b000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:59.775  6699  6699 W art     : b558b000-b558c000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:59.775  6699  6699 W art     : b558c000-b558d000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 16:35:59.775  6699  6699 W art     : b558e000-b55bf000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:59.775  6699  6699 W art     : b55bf000-b55c2000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:59.775  6699  6699 W art     : b55c2000-b55c3000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 16:35:59.775  6699  6699 W art     : b55c4000-b55ff000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 16:35:59.775  6699  6699 W art     : b55ff000-b5600000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-24 16:35:59.775  6699  6699 W art     : b5600000-b5601000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 16:35:59.775  6699  6699 W art     : b5602000-b5609000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:59.775  6699  6699 W art     : b5609000-b560a000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b560a000-b560b000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:59.775  6699  6699 W art     : b560b000-b560c000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 16:35:59.775  6699  6699 W art     : b560c000-b560d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b560d000-b5624000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 16:35:59.775  6699  6699 W art     : b5624000-b5625000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5625000-b5628000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
,08-24 16:35:59.775  6699  6699 W art     : b5628000-b5629000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 16:35:59.775  6699  6699 W art     : b5629000-b5648000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:59.775  6699  6699 W art     : b5648000-b5649000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:59.775  6699  6699 W art     : b5649000-b564a000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 16:35:59.775  6699  6699 W art     : b564a000-b5688000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:59.775  6699  6699 W art     : b5688000-b5689000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5689000-b568b000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:59.775  6699  6699 W art     : b568b000-b568c000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 16:35:59.775  6699  6699 W art     : b568d000-b5694000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-24 16:35:59.775  6699  6699 W art     : b5694000-b5695000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 16:35:59.775  6699  6699 W art     : b5695000-b5696000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 16:35:59.775  6699  6699 W art     : b5697000-b569a000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:59.775  6699  6699 W art     : b569a000-b569b000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:59.775  6699  6699 W art     : b569b000-b569c000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 16:35:59.775  6699  6699 W art     : b569c000-b56a2000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 16:35:59.775  6699  6699 W art     : b56a2000-b56a3000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b56a3000-b56a4000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 16:35:59.775  6699  6699 W art     : b56a4000-b56a5000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-24 16:35:59.775  6699  6699 W art     : b56a5000-b56ae000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:59.775  6699  6699 W art     : b56ae000-b56af000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:59.775  6699  6699 W art     : b56af000-b56b0000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 16:35:59.775  6699  6699 W art     : b56b0000-b5741000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:59.775  6699  6699 W art     : b5741000-b5742000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5742000-b574d000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:59.775  6699  6699 W art     : b574d000-b574e000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 16:35:59.775  6699  6699 W art     : b574f000-b5761000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-24 16:35:59.775  6699  6699 W art     : b5761000-b5762000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 16:35:59.775  6699  6699 W art     : b5762000-b5763000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 16:35:59.775  6699  6699 W art     : b5764000-b5769000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:59.775  6699  6699 W art     : b5769000-b576a000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:59.775  6699  6699 W art     : b576a000-b576b000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 16:35:59.775  6699  6699 W art     : b576c000-b57d9000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 16:35:59.775  6699  6699 W art     : b57d9000-b57da000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b57da000-b57dc000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 16:35:59.775  6699  6699 W art     : b57dc000-b57dd000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
,08-24 16:35:59.775  6699  6699 W art     : b57dd000-b57de000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b57de000-b57e5000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:59.775  6699  6699 W art     : b57e5000-b57e6000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:59.775  6699  6699 W art     : b57e6000-b57e7000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 16:35:59.775  6699  6699 W art     : b57e8000-b5868000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 16:35:59.775  6699  6699 W art     : b5868000-b5869000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5869000-b586a000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 16:35:59.775  6699  6699 W art     : b586a000-b586b000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-24 16:35:59.775  6699  6699 W art     : b586b000-b5882000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5882000-b58b9000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 16:35:59.775  6699  6699 W art     : ib/libqc-opt.so
08-24 16:35:59.775  6699  6699 W art     : b58b9000-b58ba000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 16:35:59.775  6699  6699 W art     : b58ba000-b58bb000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 16:35:59.775  6699  6699 W art     : b58bb000-b58d7000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 16:35:59.775  6699  6699 W art     : b58d7000-b58d8000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 16:35:59.775  6699  6699 W art     : b58d8000-b58d9000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
,08-24 16:35:59.775  6699  6699 W art     : b58da000-b593b000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:59.775  6699  6699 W art     : b593b000-b593d000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:59.775  6699  6699 W art     : b593d000-b593e000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 16:35:59.775  6699  6699 W art     : b593f000-b5966000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:59.775  6699  6699 W art     : b5966000-b5967000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5967000-b5968000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:59.775  6699  6699 W art     : b5968000-b5969000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 16:35:59.775  6699  6699 W art     : b596a000-b5972000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 16:35:59.775  6699  6699 W art     : b5972000-b5974000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 16:35:59.775  6699  6699 W art     : b5974000-b5975000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-24 16:35:59.775  6699  6699 W art     : b5976000-b5979000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:59.775  6699  6699 W art     : b5979000-b597a000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:59.775  6699  6699 W art     : b597a000-b597b000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 16:35:59.775  6699  6699 W art     : b597b000-b597f000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:59.775  6699  6699 W art     : b597f000-b5980000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5980000-b5981000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:59.775  6699  6699 W art     : b5981000-b5982000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 16:35:59.775  6699  6699 W art     : b5982000-b5992000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 16:35:59.775  6699  6699 W art     : b5992000-b5993000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
,08-24 16:35:59.775  6699  6699 W art     : b5993000-b5994000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 16:35:59.775  6699  6699 W art     : b5994000-b59da000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b59da000-b59e3000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:59.775  6699  6699 W art     : b59e3000-b59e4000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:59.775  6699  6699 W art     : b59e4000-b59e5000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 16:35:59.775  6699  6699 W art     : b59e6000-b59eb000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 16:35:59.775  6699  6699 W art     : b59eb000-b59ec000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 16:35:59.775  6699  6699 W art     : b59ec000-b59ed000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,08-24 16:35:59.775  6699  6699 W art     : b59ed000-b59f0000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:59.775  6699  6699 W art     : b59f0000-b59f1000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b59f1000-b59f2000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:59.775  6699  6699 W art     : b59f2000-b59f3000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 16:35:59.775  6699  6699 W art     : b59f4000-b5a0c000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 16:35:59.775  6699  6699 W art     : b5a0c000-b5a0d000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5a0d000-b5a0e000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 16:35:59.775  6699  6699 W art     : b5a0e000-b5a0f000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-24 16:35:59.775  6699  6699 W art     : b5a10000-b5baa000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:59.775  6699  6699 W art     : b5baa000-b5bab000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5bab000-b5bb8000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:59.775  6699  6699 W art     : b5bb8000-b5bb9000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 16:35:59.775  6699  6699 W art     : b5bb9000-b5bbd000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 16:35:59.775  6699  6699 W art     : b5bbd000-b5bbe000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5bbe000-b5bbf000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 16:35:59.775  6699  6699 W art     : b5bbf000-b5bc0000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-24 16:35:59.775  6699  6699 W art     : b5bc0000-b5bd3000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:59.775  6699  6699 W art     : b5bd3000-b5bd4000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:59.775  6699  6699 W art     : b5bd4000-b5bd5000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 16:35:59.775  6699  6699 W art     : b5bd5000-b5bd6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:59.775  6699  6699 W art     : b5bd6000-b5c21000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:59.775  6699  6699 W art     : b5c21000-b5c22000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:59.775  6699  6699 W art     : b5c22000-b5c23000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 16:35:59.775  6699  6699 W art     : b5c23000-b5c25000 rw-p 00000000 00:00 0 
,08-24 16:35:59.775  6699  6699 W art     : b5c26000-b5c37000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:59.775  6699  6699 W art     : b5c37000-b5c38000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5c38000-b5c39000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:59.775  6699  6699 W art     : b5c39000-b5c3a000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 16:35:59.775  6699  6699 W art     : b5c3b000-b5c45000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:59.775  6699  6699 W art     : b5c45000-b5c47000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:59.775  6699  6699 W art     : b5c47000-b5c48000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 16:35:59.775  6699  6699 W art     : b5c48000-b5c61000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 16:35:59.775  6699  6699 W art     : b5c61000-b5c62000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 16:35:59.775  6699  6699 W art     : b5c62000-b5c65000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,08-24 16:35:59.775  6699  6699 W art     : b5c65000-b5c69000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5c69000-b5cdd000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:59.775  6699  6699 W art     : b5cdd000-b5cde000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5cde000-b5ce1000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:59.775  6699  6699 W art     : b5ce1000-b5ce2000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 16:35:59.775  6699  6699 W art     : b5ce2000-b5ce3000 r--p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5ce3000-b5ce6000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 16:35:59.775  6699  6699 W art     : b5ce6000-b5ce7000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
,08-24 16:35:59.775  6699  6699 W art     : b5ce7000-b5ce8000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 16:35:59.775  6699  6699 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5ce9000-b5cee000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:59.775  6699  6699 W art     : b5cee000-b5cef000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:59.775  6699  6699 W art     : b5cef000-b5cf0000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 16:35:59.775  6699  6699 W art     : b5cf0000-b5cf1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5cf1000-b5cf4000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
,08-24 16:35:59.775  6699  6699 W art     : b5cf4000-b5cf5000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 16:35:59.775  6699  6699 W art     : b5cf5000-b5cf6000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 16:35:59.775  6699  6699 W art     : b5cf6000-b5cf7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5cf7000-b5cfb000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:59.775  6699  6699 W art     : b5cfb000-b5cfc000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:59.775  6699  6699 W art     : b5cfc000-b5cfd000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 16:35:59.775  6699  6699 W art     : b5cfd000-b5cfe000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:59.775  6699  6699 W art     : b5cfe000-b5d02000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 16:35:59.775  6699  6699 W art     : b5d02000-b5d03000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
,08-24 16:35:59.775  6699  6699 W art     : b5d03000-b5d04000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 16:35:59.775  6699  6699 W art     : b5d04000-b5d05000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5d05000-b5d13000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:59.775  6699  6699 W art     : b5d13000-b5d14000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b5d14000-b5d15000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:59.775  6699  6699 W art     : b5d15000-b5d16000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 16:35:59.775  6699  6699 W art     : b5d16000-b5d20000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 16:35:59.775  6699  6699 W art     : b5d20000-b5d23000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-24 16:35:59.775  6699  6699 W art     : b5d23000-b5d24000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 16:35:59.775  6699  6699 W art     : b5d24000-b5d25000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5d25000-b5d2f000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:59.775  6699  6699 W art     : b5d2f000-b5d32000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:59.775  6699  6699 W art     : b5d32000-b5d33000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 16:35:59.775  6699  6699 W art     : b5d33000-b5d37000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:59.775  6699  6699 W art     : b5d37000-b5d38000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:59.775  6699  6699 W art     : b5d38000-b5d39000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 16:35:59.775  6699  6699 W art     : b5d39000-b5d3a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b5d3a000-b5d47000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
,08-24 16:35:59.775  6699  6699 W art     : b5d47000-b5d49000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 16:35:59.775  6699  6699 W art     : b5d49000-b5d4a000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 16:35:59.775  6699  6699 W art     : b5d4a000-b615c000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:59.775  6699  6699 W art     : b615c000-b615d000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b615d000-b6166000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:59.775  6699  6699 W art     : b6166000-b616a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 16:35:59.775  6699  6699 W art     : b616a000-b616b000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b616b000-b6172000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:59.775  6699  6699 W art     : b6172000-b6173000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:59.775  6699  6699 W art     : b6173000-b6174000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 16:35:59.775  6699  6699 W art     : b6174000-b6175000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-24 16:35:59.775  6699  6699 W art     : b6175000-b6190000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 16:35:59.775  6699  6699 W art     : b6190000-b6191000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 16:35:59.775  6699  6699 W art     : b6191000-b6192000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 16:35:59.775  6699  6699 W art     : b6192000-b6193000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b6193000-b61df000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:59.775  6699  6699 W art     : b61df000-b61e0000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b61e0000-b61e1000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:59.775  6699  6699 W art     : b61e1000-b61e2000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 16:35:59.775  6699  6699 W art     : b61e2000-b61e3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b61e3000-b61e7000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:59.775  6699  6699 W art     : b61e7000-b61e8000 ---p 00000000 00:00 0 
,08-24 16:35:59.775  6699  6699 W art     : b61e8000-b61e9000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:59.775  6699  6699 W art     : b61e9000-b61ea000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 16:35:59.775  6699  6699 W art     : b61ea000-b6222000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:59.775  6699  6699 W art     : b6222000-b6223000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:59.775  6699  6699 W art     : b6223000-b6224000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 16:35:59.775  6699  6699 W art     : b6224000-b6225000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.775  6699  6699 W art     : b6225000-b62c3000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:59.775  6699  6699 W art     : b62c3000-b62c4000 ---p 00000000 00:00 0 
,08-24 16:35:59.775  6699  6699 W art     : b62c4000-b62e2000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:59.775  6699  6699 W art     : b62e2000-b62e3000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 16:35:59.775  6699  6699 W art     : b62e3000-b6456000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:59.775  6699  6699 W art     : b6456000-b6461000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:59.775  6699  6699 W art     : b6461000-b6462000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 16:35:59.775  6699  6699 W art     : b6462000-b6579000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:59.775  6699  6699 W art     : b6579000-b6584000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:59.775  6699  6699 W art     : b6584000-b6585000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 16:35:59.775  6699  6699 W art     : b6585000-b6589000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b6589000-b65ad000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 16:35:59.775  6699  6699 W art     : b65ad000-b65af000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 16:35:59.775  6699  6699 W art     : b65af000-b65b0000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 16:35:59.775  6699  6699 W art     : b65b0000-b6656000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:59.775  6699  6699 W art     : b6656000-b6663000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:59.775  6699  6699 W art     : b6663000-b6664000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 16:35:59.775  6699  6699 W art     : b6664000-b6665000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b6665000-b66b8000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:59.775  6699  6699 W art     : b66b8000-b66b9000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b66b9000-b66ba000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:59.775  6699  6699 W art     : b66ba000-b66bb000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 16:35:59.775  6699  6699 W art     : b66bb000-b66c0000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b66c0000-b66d2000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 16:35:59.775  6699  6699 W art     : b66d2000-b66d3000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b66d3000-b66d4000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-24 16:35:59.775  6699  6699 W art     : b66d4000-b66d5000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 16:35:59.775  6699  6699 W art     : b66d5000-b66dc000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 16:35:59.775  6699  6699 W art     : b66dc000-b66dd000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 16:35:59.775  6699  6699 W art     : b66dd000-b66de000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-24 16:35:59.775  6699  6699 W art     : b66de000-b66df000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b66df000-b66e2000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:59.775  6699  6699 W art     : b66e2000-b66e3000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:59.775  6699  6699 W art     : b66e3000-b66e4000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 16:35:59.775  6699  6699 W art     : b66e4000-b66e8000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
,08-24 16:35:59.775  6699  6699 W art     : b66e8000-b66e9000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 16:35:59.775  6699  6699 W art     : b66e9000-b66ea000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 16:35:59.775  6699  6699 W art     : b66ea000-b66f8000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:59.775  6699  6699 W art     : b66f8000-b66f9000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b66f9000-b66fa000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:59.775  6699  6699 W art     : b66fa000-b66fb000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 16:35:59.775  6699  6699 W art     : b66fb000-b6704000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 16:35:59.775  6699  6699 W art     : b6704000-b6705000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
,08-24 16:35:59.775  6699  6699 W art     : b6705000-b6706000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 16:35:59.775  6699  6699 W art     : b6706000-b676c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:59.775  6699  6699 W art     : b676c000-b676d000 ---p 00000000 00:00 0 
,08-24 16:35:59.775  6699  6699 W art     : b676d000-b676f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:59.775  6699  6699 W art     : b676f000-b6778000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 16:35:59.775  6699  6699 W art     : b6778000-b677b000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b677b000-b6812000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 16:35:59.775  6699  6699 W art     : b6812000-b6814000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 16:35:59.775  6699  6699 W art     : b6814000-b6815000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
,08-24 16:35:59.775  6699  6699 W art     : b6815000-b6816000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b6816000-b6b37000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 16:35:59.775  6699  6699 W art     : b6b37000-b6b38000 ---p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b6b38000-b6b53000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 16:35:59.775  6699  6699 W art     : b6b53000-b6b57000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 16:35:59.775  6699  6699 W art     : b6b57000-b6b5c000 rw-p 00000000 00:00 0 
08-24 16:35:59.775  6699  6699 W art     : b6b5c000-b6b64000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 16:35:59.775  6699  6699 W art     : b6b64000-b6b65000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
,08-24 16:35:59.775  6699  6699 W art     : b6b65000-b6b66000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 16:35:59.785  6699  6699 W art     : b6b66000-b6b94000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:59.785  6699  6699 W art     : b6b94000-b6b95000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6b95000-b6b9c000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:59.785  6699  6699 W art     : b6b9c000-b6b9d000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 16:35:59.785  6699  6699 W art     : b6b9d000-b6be3000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 16:35:59.785  6699  6699 W art     : b6be3000-b6be4000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6be4000-b6be7000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
,08-24 16:35:59.785  6699  6699 W art     : b6be7000-b6be8000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 16:35:59.785  6699  6699 W art     : b6be8000-b6c03000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:59.785  6699  6699 W art     : b6c03000-b6c07000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:59.785  6699  6699 W art     : b6c07000-b6c08000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 16:35:59.785  6699  6699 W art     : b6c08000-b6c55000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:59.785  6699  6699 W art     : b6c55000-b6c56000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6c56000-b6c62000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:59.785  6699  6699 W art     : b6c62000-b6c63000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 16:35:59.785  6699  6699 W art     : b6c63000-b6c70000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
,08-24 16:35:59.785  6699  6699 W art     : b6c70000-b6c71000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6c71000-b6c72000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 16:35:59.785  6699  6699 W art     : b6c72000-b6c73000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 16:35:59.785  6699  6699 W art     : b6c73000-b6c7b000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:59.785  6699  6699 W art     : b6c7b000-b6c7c000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6c7c000-b6c7d000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:59.785  6699  6699 W art     : b6c7d000-b6c7e000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 16:35:59.785  6699  6699 W art     : b6c7e000-b6c85000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:59.785  6699  6699 W art     : b6c85000-b6c86000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:59.785  6699  6699 W art     : b6c86000-b6c87000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 16:35:59.785  6699  6699 W art     : b6c87000-b6c9b000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:59.785  6699  6699 W art     : b6c9b000-b6c9d000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:59.785  6699  6699 W art     : b6c9d000-b6c9e000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 16:35:59.785  6699  6699 W art     : b6c9e000-b6cc6000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:59.785  6699  6699 W art     : b6cc6000-b6cc8000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:59.785  6699  6699 W art     : b6cc8000-b6cc9000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 16:35:59.785  6699  6699 W art     : b6cc9000-b6ccc000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
,08-24 16:35:59.785  6699  6699 W art     : b6ccc000-b6ccd000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 16:35:59.785  6699  6699 W art     : b6ccd000-b6cce000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 16:35:59.785  6699  6699 W art     : b6cce000-b6cd7000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:59.785  6699  6699 W art     : b6cd7000-b6cd8000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:59.785  6699  6699 W art     : b6cd8000-b6cd9000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 16:35:59.785  6699  6699 W art     : b6cd9000-b6cf9000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 16:35:59.785  6699  6699 W art     : b6cf9000-b6cfa000 r--p 0001f000 b3:17 2560       /system/lib/libm.so,
08-24 16:35:59.785  6699  6699 W art     : b6cfa000-b6cfb000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 16:35:59.785  6699  6699 W art     : b6cfb000-b6d6e000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 16:35:59.785  6699  6699 W art     : b6d6e000-b6d72000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 16:35:59.785  6699  6699 W art     : b6d72000-b6d75000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 16:35:59.785  6699  6699 W art     : b6d75000-b6d7f000 rw-p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6d7f000-b6e07000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:59.785  6699  6699 W art     : b6e07000-b6e08000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6e08000-b6e0c000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:59.785  6699  6699 W art     : b6e0c000-b6e0d000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 16:35:59.785  6699  6699 W art     : b6e0d000-b6e0e000 rw-p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6e0e000-b6e37000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:59.785  6699  6699 W art     : b6e37000-b6e38000 ---p 00000000 00:00 0 
,08-24 16:35:59.785  6699  6699 W art     : b6e38000-b6e3b000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:59.785  6699  6699 W art     : b6e3b000-b6e3c000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 16:35:59.785  6699  6699 W art     : b6e3c000-b6f16000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:59.785  6699  6699 W art     : b6f16000-b6f1d000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:59.785  6699  6699 W art     : b6f1d000-b6f25000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 16:35:59.785  6699  6699 W art     : b6f25000-b6f26000 rw-p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6f26000-b6f27000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-24 16:35:59.785  6699  6699 W art     : b6f27000-b6f28000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 16:35:59.785  6699  6699 W art     : b6f28000-b6f29000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f29000-b6f2c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f2c000-b6f51000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:59.785  6699  6699 W art     : b6f51000-b6f52000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6f52000-b6f59000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:59.785  6699  6699 W art     : b6f59000-b6f5a000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 16:35:59.785  6699  6699 W art     : b6f5a000-b6f61000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,08-24 16:35:59.785  6699  6699 W art     : b6f61000-b6f62000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 16:35:59.785  6699  6699 W art     : b6f62000-b6f63000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 16:35:59.785  6699  6699 W art     : b6f63000-b6f64000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f64000-b6f7c000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f7c000-b6f7d000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6f7d000-b6f7e000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f7e000-b6f7f000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f7f000-b6f8d000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f8d000-b6f8e000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6f8e000-b6f8f000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f8f000-b6f90000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 16:35:59.785  6699  6699 W art     : b6f90000-b6f91000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:59.785  6699  6699 W art     : b6f91000-b6f93000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f93000-b6f94000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f94000-b6f95000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 16:35:59.785  6699  6699 W art     : b6f95000-b6f96000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
,08-24 16:35:59.785  6699  6699 W art     : b6f96000-b6f97000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 16:35:59.785  6699  6699 W art     : b6f97000-b6fb7000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 16:35:59.785  6699  6699 W art     : b6fb7000-b6fb8000 r--p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6fb8000-b6fb9000 ---p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6fb9000-b6fbb000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 16:35:59.785  6699  6699 W art     : b6fbb000-b6fbc000 r-xp 00000000 00:00 0          [sigpage]
08-24 16:35:59.785  6699  6699 W art     : b6fbc000-b6fd7000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 16:35:59.785  6699  6699 W art     : b6fd7000-b6fd8000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 16:35:59.785  6699  6699 W art     : b6fd8000-b6fda000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 16:35:59.785  6699  6699 W art     : b6fda000-b6fdc000 rw-p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : b6fdc000-b6fe1000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 16:35:59.785  6699  6699 W art     : b6fe1000-b6fe2000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 16:35:59.785  6699  6699 W art     : b6fe2000-b6fe3000 rw-p 00000000 00:00 0 
08-24 16:35:59.785  6699  6699 W art     : beec0000-beee1000 rw-p 00000000 00:00 0          [stack]
08-24 16:35:59.785  6699  6699 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-24 16:35:59.865  6699  6699 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 16:35:59.915  6699  6699 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 16:35:59.925  6699  6699 E AffinityControl: AffinityControl: registerfunction enter
,08-24 16:35:59.945  6699  6699 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 16:35:59.955   761  1422 D PackageManager: START PACKAGE DELETE: observer{87847115}
08-24 16:35:59.955   761  1422 D PackageManager: pkg{<packageName>}
08-24 16:35:59.955   761  1422 D PackageManager: user{0}
08-24 16:35:59.955   761  1422 D PackageManager: caller{2000}
08-24 16:35:59.955   761  1422 D PackageManager: flags{2}
,08-24 16:35:59.955   761  1422 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 16:35:59.955   761  1422 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 16:35:59.955   761  1422 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 16:35:59.955   761  1422 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 16:35:59.955   761  1422 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-24 16:35:59.955   761   936 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 16:35:59.955   761   936 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 16:35:59.955   761   936 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 16:35:59.955   761   936 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 16:35:59.955   761   936 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 16:35:59.965   761   936 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-24 16:35:59.965   761   936 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-24 16:35:59.965   761   936 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-24 16:35:59.965   761   853 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-24 16:35:59.965   761   853 I ActivityManager: Killing 6396:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-24 16:35:59.965   761   853 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-24 16:35:59.975   761   936 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-24 16:35:59.975   761   936 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-24 16:35:59.985   761   853 I ActivityManager: Start proc 6708:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-24 16:35:59.985  6708  6708 E Zygote  : v2
08-24 16:35:59.985  6708  6708 I libpersona: KNOX_SDCARD checking this for 10004
08-24 16:35:59.985  6708  6708 I libpersona: KNOX_SDCARD not a persona
,08-24 16:35:59.985   761   853 I ActivityManager: Killing 5372:com.policydm/1000 (adj 15): DHA:empty #37
,08-24 16:35:59.985   761   853 I ActivityManager:   Force finishing activity ActivityRecord{a21ff4f u0 com.test.thalitest/.MainActivity t168}
,08-24 16:35:59.995  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:35:59.995  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 16:35:59.995  6708  6708 E Zygote  : accessInfo : 0
,08-24 16:35:59.995  6708  6708 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-24 16:35:59.995   761  1231 V AlarmManager: Expired Alarm result :8
,08-24 16:35:59.995   292  1497 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
,08-24 16:35:59.995   292  1243 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
,08-24 16:36:00.015   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
,08-24 16:36:00.015   761   853 I ActivityManager: Waited long enough for: ServiceRecord{590ad14 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-24 16:36:00.025   761  1732 D GraphicsStats: Buffer count: 5
,08-24 16:36:00.025   761  1732 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d1c10a8)
,08-24 16:36:00.025   761  1327 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:36:00.025   761  1327 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:36:00.025   761  1327 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 16:36:00.045  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:36:00.045  6708  6708 D ActivityThread: Added TimaKeyStore provider
,08-24 16:36:00.055   761  1422 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-24 16:36:00.055  6376  6376 D AASAservice: onDestroy()
,08-24 16:36:00.055  6376  6376 I art     : System.exit called, status: 80
,08-24 16:36:00.055  6376  6376 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-24 16:36:00.065   761   936 D AASAinstall: there is not AASApackages.xml file
,08-24 16:36:00.075   761  1482 I ActivityManager: Process com.samsung.aasaservice (pid 6376)(adj 0) has died(153,710)
,08-24 16:36:00.085   350   350 I Zygote  : Process 6376 exited cleanly (80)
,08-24 16:36:00.335   761   936 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-24 16:36:00.425   761   936 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 16:36:00.425   761  1482 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-24 16:36:00.435   334   334 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-24 16:36:00.435  6708  6708 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 16:36:00.445   761   936 I art     : Starting a blocking GC Explicit
,08-24 16:36:00.445  6708  6708 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-24 16:36:00.445  6708  6708 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-24 16:36:00.445  6708  6708 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-24 16:36:00.445  6708  6708 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-24 16:36:00.465  6708  6708 D AndroidRuntime: Shutting down VM
,08-24 16:36:00.465  6708  6708 E AndroidRuntime: FATAL EXCEPTION: main
08-24 16:36:00.465  6708  6708 E AndroidRuntime: Process: com.test.thalitest, PID: 6708
08-24 16:36:00.465  6708  6708 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-24 16:36:00.465  6708  6708 E AndroidRuntime: 	... 9 more
,08-24 16:36:00.495  6736  6736 E Zygote  : v2
08-24 16:36:00.495   761   853 I ActivityManager: Start proc 6736:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
08-24 16:36:00.495  6736  6736 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 16:36:00.495  6736  6736 I libpersona: KNOX_SDCARD checking this for 1000
08-24 16:36:00.495  6736  6736 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 16:36:00.495  6736  6736 I libpersona: KNOX_SDCARD not a persona
08-24 16:36:00.495  6708  6708 I Process : Sending signal. PID: 6708 SIG: 9
08-24 16:36:00.495  6736  6736 E Zygote  : accessInfo : 0
,08-24 16:36:00.515   761  1801 I ActivityManager: Process com.test.thalitest (pid 6708)(adj 9) has died(156,709)
,08-24 16:36:00.515   761  1801 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 16:36:00.515   761  1801 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-24 16:36:00.525   761  1801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-24 16:36:00.525  6736  6736 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 16:36:00.525  6736  6736 D ActivityThread: Added TimaKeyStore provider
,08-24 16:36:00.525   761   853 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-24 16:36:00.525   761   853 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-24 16:36:00.535   761  1422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fb66 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1f4ea7 6736:com.samsung.android.sm/1000}
,08-24 16:36:00.535  6736  6736 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-24 16:36:00.575  6736  6736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-24 16:36:00.585   761  1614 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fb66 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f967aa 4145:com.google.android.gms/u0a11}
,08-24 16:36:00.595   761   936 I art     : Explicit concurrent mark sweep GC freed 90681(4MB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.703ms total 158.667ms
,08-24 16:36:00.625   761   936 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 16:36:00.625   761   936 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-24 16:36:00.625   761   936 D AASAinstall: there is not AASApackages.xml file
08-24 16:36:00.625   761   936 D PackageManager: result of delete: 1{87847115}
,08-24 16:36:00.635  6699  6699 I art     : System.exit called, status: 0
08-24 16:36:00.635  6699  6699 I AndroidRuntime: VM exiting with result code 0.
08-24 16:36:00.635   761   936 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 16:36:00.635   761   936 D PackageManager: userId{-1}
08-24 16:36:00.635   761   936 D PackageManager: andCode{true}
,08-24 16:36:00.645   761   936 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-24 16:36:00.655  5980  6757 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-24 16:36:00.655  5980  6757 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-24 16:36:00.655  5980  6757 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-24 16:36:00.705   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.715   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.715   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.715  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-24 16:36:00.715  1379  1379 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-24 16:36:00.715   761   903 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.725   761   903 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.725   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.725   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.725  2028  2028 E SamsungIME: mOCRHelper is null
,08-24 16:36:00.725   761  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 16:36:00.735  2050  2499 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.735   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.745   761   853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ebd331 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8328bb 4294:com.samsung.klmsagent/u0a18}
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.745  1707  1707 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.745   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.755  4294  4294 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 24 16:36:00 GMT+02:00 2016
,08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.755   761   761 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.755  3179  3197 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 16:36:00.755  3179  3197 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 16:36:00.765  3179  3197 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 16:36:00.765   761   761 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.765  3179  3197 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-24 16:36:00.765  4294  4294 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-24 16:36:00.765   761  1723 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-24 16:36:00.765   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.765  4294  4294 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-24 16:36:00.765  4294  4294 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.775  4294  4294 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 16:36:00.775  4294  6769 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-24 16:36:00.775  4294  6769 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-24 16:36:00.775   761  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ebd331 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54772f7 761:system/1000}
,08-24 16:36:00.775  4294  6769 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-24 16:36:00.775  4294  6769 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-24 16:36:00.775  4294  6769 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-24 16:36:00.775  4294  6769 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.775   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785  4294  6769 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785  4294  6769 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.785   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.795   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.795  4294  6769 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-24 16:36:00.795  4294  6769 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-24 16:36:00.795   761  1317 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-24 16:36:00.795   761  1317 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 16:36:00.795   761  1317 V NetworkStats: performPollLocked(flags=0x3)
,08-24 16:36:00.795   761  1318 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,08-24 16:36:00.795   761  1318 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-24 16:36:00.805   761   761 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.805  4294  6769 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 16:36:00.805  1698  6770 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 16:36:00.805   761  1317 V NetworkStats: performPollLocked() took 6ms
08-24 16:36:00.805   761  1317 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 16:36:00.805  1698  6770 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-24 16:36:00.805  1698  6770 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 16:36:00.805  1698  6770 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-24 16:36:00.805   761   761 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.805  1698  6770 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 16:36:00.805   761  1318 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 16:36:00.805   761  1318 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 16:36:00.815   761   761 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.815   761   761 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.815   761  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-24 16:36:00.815   761  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/168_task_thumbnail.png
,08-24 16:36:00.815   761   761 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.825   761   761 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.825  4294  6769 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: #################################################################
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: #################################################################
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:36:00.825  4294  6769 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: #################################################################
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: #################################################################
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-24 16:36:00.825  4294  6769 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:36:00.825  4294  6769 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-24 16:36:00.825  4294  6769 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.845   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.855   761  1293 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-24 16:36:00.855   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.855   761   761 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.855   761   761 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.865   761  1622 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
,08-24 16:36:00.865   761  1622 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 16:36:00.865   761  1622 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 16:36:00.865   761  1622 D SettingsProvider: selectionArgs: false
08-24 16:36:00.865   761  1622 D SettingsProvider: selectionArgs: 10018
08-24 16:36:00.865   761  1622 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-24 16:36:00.865   761   761 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.865   761   761 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.865   761  1622 D SettingsProvider: ret = -1
,08-24 16:36:00.865  4294  6769 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-24 16:36:00.865  4294  6769 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-24 16:36:00.865   761   761 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.865   761   761 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.875   761   761 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.875   761   761 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.875  2050  6641 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d7e1374 in tid 6641 (Binder_4)
,08-24 16:36:00.875  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:00.875  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:00.875   761   761 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.875   761   761 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.885   761   761 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.895   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-24 16:36:00.905   761   761 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-24 16:36:00.905   761   761 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9c4e7f48 in tid 761 (system_server)
08-24 16:36:00.905   761   761 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 16:36:00.905  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:00.935  4145  4145 E GmsClient: service descriptor mismatch: com.google.android.gms.phenotype.internal.IPhenotypeService vs. 
,08-24 16:36:00.935  4145  4145 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9a8334d9 in tid 4145 (gle.android.gms)
,08-24 16:36:00.945  4145  4145 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 16:36:00.945  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:00.975   350   350 I Zygote  : Process 2050 exited due to signal (7)
,08-24 16:36:00.985   291   291 I ServiceManager: service 'sec_analytics' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'telecom' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'edmnativehelper' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'context_aware' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'scontext' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'barbeam' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'multiwindow_facade' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'window' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'input' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'midi' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'bluetooth_manager' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'rcp' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'input_method' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'knox_ccm_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'enterprise_license_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'application_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wifi_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'phone_restriction_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'remoteinjection' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'knox_ucsm_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'edm_proxy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'mum_container_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'enterprise_billing_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'otp_service' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'persona_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'package' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'user' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'procstats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'meminfo' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'gfxinfo' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'dbinfo' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'cpuinfo' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'permission' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'processinfo' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'sensorservice' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'mdm.remotedesktop' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'battery' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'usagestats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'webviewupdate' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'scheduling_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'telephony.registry' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'persona' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'enterprise_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'statusbar' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'clipboard' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'clipboardEx' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'network_management' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'ABTPersistenceService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'te,xtservices' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'network_score' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'netstats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'netpolicy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wifip2p' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wifi' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wifihs20' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wifiscanner' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'rttmanager' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'ethernet' died
08-24 16:36:00.985  2837  2847 W Sensors : sensorservice died [0xad5bbc40]
08-24 16:36:00.985   291   291 I ServiceManager: service 'connectivity' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'sb_service' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'servicediscovery' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'updatelock' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'audio' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'DockObserver' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'notification' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'devicestoragemonitor' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'location' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'country_detector' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'sec_location' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'search' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'execute' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'dropbox' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'wallpaper' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'usb' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'serial' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'kiesusb' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'jobscheduler' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'backup' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'appwidget' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'voiceinteraction' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'SecExternalDisplayService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'diskstats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'mDNIe' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'AAS' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'MSCS' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'spengestureservice' died,
,08-24 16:36:00.985   291   291 I ServiceManager: service 'quickconnect' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'samplingprofiler' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'commontime_management' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'dreams' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'graphicsstats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'print' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'restrictions' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'media_session' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'media_router' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'trust' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'fingerprint' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'launcherapps' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'voip' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'media_projection' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'lpnet' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'imms' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'accessibility' died
08-24 16:36:00.985   292  1498 D libEGL  : eglTerminate EGLDisplay = 0xb46706fc
08-24 16:36:00.985   291   291 I ServiceManager: service 'cover' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'mount' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'lock_settings' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'uimode' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'deviceidle' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'device_policy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'harmony_eas_service' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'sdp' died
08-24 16:36:01.005  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
08-24 16:36:00.985   291   291 I ServiceManager: service 'sdp_log' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'dlp' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'log_manager_service' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'batterystats' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'appops' died
08-24 16:36:00.985   292  1498 D libEGL  : eglTerminate EGLDisplay = 0xb46706fc
08-24 16:36:00.985   291   291 I ServiceManager: service 'power' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'display' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'activity' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'SEAMService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'media.camera.proxy' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'account' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'content' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'DirEncryptService' died
08-24 16:36:01.005  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
08-24 16:36:00.985   291   291 I ServiceManager: service 'LSManager' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'ReactiveService' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'DeviceRootKeyService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'EngineeringModeService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'SatsService' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'sedenial' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'vibrator' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'tw_toolbox' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'tima' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'iccc' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'cepproxyks' died
,08-24 16:36:00.985   291   291 I ServiceManager: service 'emailksproxy' died
08-24 16:36:00.985   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
08-24 16:36:00.985   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
08-24 16:36:00.985   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-24 16:36:00.985   291   291 I ServiceManager: service 'consumer_ir' died
08-24 16:36:00.985   291   291 I ServiceManager: service 'alarm' died
08-24 16:36:00.985  2288  2316 W Sensors : sensorservice died [0xaa5fad40]
08-24 16:36:00.995   292  1498 I SurfaceFlinger: restart the boot-animation @ binderDied,
08-24 16:36:00.995   325   963 W AudioFlinger: power manager service died !!!
08-24 16:36:00.995   325   963 W AudioFlinger: power manager service died !!!
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=15 Removed EimLayer(An (2/9)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=2 Removed GocusedStac (3/8)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/7)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=4 Removed EimLayer(An (0/6)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=14 Removed EimLayer(Di (2/5)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
,08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-24 16:36:00.995  1724  1960 W Sensors : sensorservice died [0xad9b9380]
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
,08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=23 Removed VSBConnecti (1/2)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=24 Removed VSBConnecti (0/1)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/1)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=24 Removed VSBConnecti (-2/1)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=20 Removed DolorFade (0/0)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=20 Removed DolorFade (-2/0)
08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
,08-24 16:36:00.995   292  1243 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
08-24 16:36:00.995  1379  1872 W Sensors : sensorservice died [0xad593d80]
08-24 16:36:00.995  1819  1970 E WifiManager: Channel connection lost
08-24 16:36:00.995  1707  2187 E WifiManager: Channel connection lost
08-24 16:36:01.005  5780  5780 D AndroidRuntime: Shutting down VM
08-24 16:36:01.005  5780  5780 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9dfdb134 in tid 5780 (android.vending)
08-24 16:36:01.005  5780  5780 F libc    : Unable to open connection to debuggerd: Connection refused
08-24 16:36:01.005  1707  1707 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-24 16:36:01.005  2225  2225 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ec9c894 in tid 2225 (droid.bluetooth)
08-24 16:36:01.005  2225  2225 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 16:36:01.005  1882  1955 W Sensors : sensorservice died [0xaa6bbe80]
08-24 16:36:01.005  1379  1631 E WifiManager: Channel connection lost
08-24 16:36:01.015   350   350 I Zygote  : Process 4145 exited due to signal (7)
,08-24 16:36:01.015  5639  5694 E WifiManager: Channel connection lost
,08-24 16:36:01.035  2837  3166 E WifiManager: Channel connection lost
,08-24 16:36:01.035  4294  6769 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x710b601e in tid 6769 (IntentService[K)
,08-24 16:36:01.035  4294  6769 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 16:36:01.035  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:01.045  2277  2277 D BluetoothA2dp: Proxy object disconnected
,08-24 16:36:01.045  2837  2837 D BluetoothA2dp: Proxy object disconnected
08-24 16:36:01.045  2837  2837 D A2dpProfile: Bluetooth service disconnected
08-24 16:36:01.045  2837  2837 D BluetoothMap: Proxy object disconnected
08-24 16:36:01.045  2837  2837 D MapProfile: Bluetooth service disconnected
,08-24 16:36:01.045  2837  2837 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b8bd2bd in tid 2837 (ndroid.settings)
08-24 16:36:01.045  2837  2837 F libc    : Unable to open connection to debuggerd: Connection refused
,08-24 16:36:01.045  2231  2231 E audit_log: File locking failed. error= Bad file descriptor
,08-24 16:36:01.085   350   350 I Zygote  : Process 5780 exited due to signal (7)
,08-24 16:36:01.085   350   350 I Zygote  : Process 4294 exited due to signal (7)
,08-24 16:36:01.095   350   350 I Zygote  : Process 2225 exited due to signal (7)
,08-24 16:36:01.105   350   350 I Zygote  : Process 2837 exited due to signal (7)
,08-24 16:36:01.235   292   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-24 16:36:01.235   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-24 16:36:01.245   332   332 E installd: eof
08-24 16:36:01.245   332   332 E installd: failed to read size
08-24 16:36:01.245   332   332 I installd: closing connection
08-24 16:36:01.245   290   290 I lowmemorykiller: ActivityManager disconnected
08-24 16:36:01.245   290   290 I lowmemorykiller: Closing Activity Manager data connection
,08-24 16:36:01.485   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd3a4
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
08-24 16:36:01.485   292   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd3a4
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
08-24 16:36:01.485   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd38c
,08-24 16:36:01.495   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe9cd3a4

```
