#### Test 832729920321fb3_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-30 17:24:28.245  5461  5461 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-30 17:24:28.245  5461  5461 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-30 17:24:28.245  5461  5461 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-30 17:24:28.245  5461  5461 I art     : System.exit called, status: 0
08-30 17:24:28.245  5461  5461 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-30 17:24:28.285   772   791 I ActivityManager: Process com.samsung.aasaservice (pid 5461)(adj 0) has died(128,737)
08-30 17:24:28.285   772   791 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-30 17:24:28.285   772   791 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-30 17:24:28.285   772   791 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-30 17:24:28.285  5417  5417 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-30 17:24:28.305   772   872 I ActivityManager: Start proc 6413:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-30 17:24:28.305  6413  6413 E Zygote  : v2
08-30 17:24:28.305   772  1319 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 17:24:28.305  6413  6413 I libpersona: KNOX_SDCARD checking this for 10014
08-30 17:24:28.305  6413  6413 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:28.315  6413  6413 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:28.315  6413  6413 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:28.315  6413  6413 E Zygote  : accessInfo : 0
08-30 17:24:28.315  6413  6413 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-30 17:24:28.355  6413  6413 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:28.355  6413  6413 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:28.375   772  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ad5753 6413:com.google.android.partnersetup/u0a14}
08-30 17:24:28.375   772  1319 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-30 17:24:28.385  6413  6413 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-30 17:24:28.395  6413  6413 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-30 17:24:28.425   772  1418 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ad5753 6413:com.google.android.partnersetup/u0a14}
08-30 17:24:28.445  6432  6432 E Zygote  : v2
08-30 17:24:28.445   772  1718 I ActivityManager: Start proc 6432:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-30 17:24:28.445  6432  6432 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:28.445  6432  6432 I libpersona: KNOX_SDCARD checking this for 10015
08-30 17:24:28.445  6432  6432 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:28.445  6432  6432 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:28.455  6432  6432 E Zygote  : accessInfo : 0
08-30 17:24:28.455  6432  6432 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-30 17:24:28.465   772  2575 I ActivityManager: Killing 5599:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-30 17:24:28.485  6432  6432 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:28.485  6432  6432 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:28.485   772  2564 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53ad98e 6432:com.samsung.groupcast/u0a15}
08-30 17:24:28.495   772  1703 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-30 17:24:28.505  6432  6432 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-30 17:24:28.525  6432  6432 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-30 17:24:28.535  6432  6432 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-30 17:24:28.545  6432  6432 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 17:24:28.545  6432  6432 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-30 17:24:28.545  6432  6432 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 17:24:28.545  6432  6432 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 17:24:28.545  6432  6432 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:24:28.545  6432  6432 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 17:24:28.545  6432  6432 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 17:24:28.555   772  1703 I ActivityManager: Killing 5261:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-30 17:24:28.555   772  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3eb077a 1986:com.sec.android.app.shealth:remote/u0a34}
08-30 17:24:28.575   772  1709 I ActivityManager: Start proc 6447:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-30 17:24:28.575  6447  6447 E Zygote  : v2
08-30 17:24:28.575  6447  6447 I libpersona: KNOX_SDCARD checking this for 10041
08-30 17:24:28.575  6447  6447 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:28.575  6447  6447 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:28.575  6447  6447 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:28.575  6447  6447 E Zygote  : accessInfo : 0
08-30 17:24:28.575  6447  6447 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-30 17:24:28.585   772  2578 D CountryDetector: No listener is left
08-30 17:24:28.585   772  1718 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-30 17:24:28.605  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:28.605  6447  6447 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:28.615   772  2564 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2c15af 6447:com.samsung.android.sdk.samsunglink/u0a41}
08-30 17:24:28.625  6447  6447 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-30 17:24:28.705  6447  6447 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 17:24:28.705  6447  6447 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-30 17:24:28.755  6447  6447 I SL_DEBUG: isLoggable:: isProductShip = 1
08-30 17:24:28.755  6447  6447 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-30 17:24:28.765   772  1703 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.765   772  2564 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-30 17:24:28.775   772   792 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.775   772  1709 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.775   772  2575 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.775   772  2578 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.785   772  1217 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.785   772   791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.785   772  1418 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.785   772  1802 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-30 17:24:28.895  6447  6447 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-30 17:24:28.895  6447  6447 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-30 17:24:28.895  6447  6447 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-30 17:24:28.895  6447  6447 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-30 17:24:28.895  6447  6447 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-30 17:24:28.895  6447  6447 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 17:24:28.895  6447  6447 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 17:24:28.895  6447  6447 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:24:28.895  6447  6447 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 17:24:28.895  6447  6447 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 17:24:28.905   772  1604 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21c4a10 1625:android.process.acore/u0a19}
08-30 17:24:28.925   772  1604 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8126727 5137:com.sec.android.gallery3d/u0a47}
08-30 17:24:28.925  5137  5137 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-30 17:24:28.935   772  1217 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 17:24:28.955  6471  6471 E Zygote  : v2
08-30 17:24:28.955   772   791 I ActivityManager: Start proc 6471:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-30 17:24:28.955  6471  6471 I libpersona: KNOX_SDCARD checking this for 10050
08-30 17:24:28.955  6471  6471 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:28.955  6471  6471 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:28.955  6471  6471 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:28.955  6471  6471 E Zygote  : accessInfo : 0
08-30 17:24:28.955  6471  6471 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-30 17:24:28.995  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:28.995  6471  6471 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.005   772  2527 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{193c89f 6471:com.sec.android.app.myfiles/u0a50}
08-30 17:24:29.015  6471  6471 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-30 17:24:29.035  6471  6471 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-30 17:24:29.085  6471  6471 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-30 17:24:29.115   772  1709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422db6d 2205:com.android.settings/1000}
08-30 17:24:29.115   332   332 E installd: system dir 0 : /system/app/
08-30 17:24:29.115   332   332 E installd: system dir 1 : /system/priv-app/
08-30 17:24:29.115   332   332 E installd: system dir 2 : /vendor/app/
08-30 17:24:29.115   332   332 E installd: system dir 3 : /oem/app/
08-30 17:24:29.135   772  1217 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422db6d 2205:com.android.settings/1000}
08-30 17:24:29.135   772   945 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-30 17:24:29.145   772  1217 I ActivityManager: Start proc 6486:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-30 17:24:29.155  6486  6486 E Zygote  : v2
08-30 17:24:29.155  6486  6486 I libpersona: KNOX_SDCARD checking this for 10169
08-30 17:24:29.155  6486  6486 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:29.155  6486  6486 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:29.155  6486  6486 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.155  6486  6486 E Zygote  : accessInfo : 0
08-30 17:24:29.155  6486  6486 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-30 17:24:29.185  6486  6486 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:29.185  6486  6486 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.195   772   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7764fbb 6486:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-30 17:24:29.205  6486  6486 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-30 17:24:29.215  6486  6486 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-30 17:24:29.235   772  1718 I ActivityManager: Killing 5614:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-30 17:24:29.235   772  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b167526 1683:com.android.phone/1001}
08-30 17:24:29.245   772  2564 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3174a4f 1812:com.google.android.googlequicksearchbox:search/u0a61}
08-30 17:24:29.255   772  2527 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-30 17:24:29.285   772  1709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3174a4f 1812:com.google.android.googlequicksearchbox:search/u0a61}
08-30 17:24:29.305   772   872 I ActivityManager: Start proc 6499:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-30 17:24:29.305  6499  6499 E Zygote  : v2
08-30 17:24:29.305  6499  6499 I libpersona: KNOX_SDCARD checking this for 10210
08-30 17:24:29.305  6499  6499 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:29.305  6499  6499 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:29.305  6499  6499 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.305  6499  6499 E Zygote  : accessInfo : 0
08-30 17:24:29.305  6499  6499 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-30 17:24:29.315   772   791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9af4831 6345:com.samsung.android.sm.provider/1000}
08-30 17:24:29.335   772  1718 I ActivityManager: Start proc 6511:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-30 17:24:29.335  6511  6511 E Zygote  : v2
08-30 17:24:29.335  6511  6511 I libpersona: KNOX_SDCARD checking this for 5012
08-30 17:24:29.335  6511  6511 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:29.335  6511  6511 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:29.335  6511  6511 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.335  6511  6511 E Zygote  : accessInfo : 0
08-30 17:24:29.335  6511  6511 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-30 17:24:29.345  1812  6498 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 17:24:29.375  6499  6499 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:29.375  6499  6499 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.395  2511  2511 E audit   : type=1400 msg=audit(1472570669.395:284): avc:  denied  { execmod } for  pid=6412 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 17:24:29.395  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.395  2511  2511 E audit   : type=1300 msg=audit(1472570669.395:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f49000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6412 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 17:24:29.395  2511  2511 E audit   : type=1327 msg=audit(1472570669.395:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 17:24:29.395  2511  2511 E audit   : type=1320 msg=audit(1472570669.395:284): 
08-30 17:24:29.415  6511  6511 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:29.415  6511  6511 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.425  1812  1823 I art     : Background sticky concurrent mark sweep GC freed 42761(3MB) AllocSpace objects, 17(1628KB) LOS objects, 23% free, 19MB/25MB, paused 739us total 141.988ms
08-30 17:24:29.425   772  2578 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e86db16 6511:com.samsung.android.sm.devicesecurity/5012}
08-30 17:24:29.435  6511  6511 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-30 17:24:29.445  6499  6499 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-30 17:24:29.445  6511  6511 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-30 17:24:29.445  1812  6498 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-30 17:24:29.455  6499  6499 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-30 17:24:29.465  1812  6498 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-30 17:24:29.465  6499  6499 D AASAservice: onCreate()
08-30 17:24:29.475   772   792 I ActivityManager: Killing 5633:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
08-30 17:24:29.475  2511  2511 E audit   : type=1400 msg=audit(1472570669.475:285): avc:  denied  { execmod } for  pid=6412 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 17:24:29.475  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.475  2511  2511 E audit   : type=1300 msg=audit(1472570669.475:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f09000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6412 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 17:24:29.475  2511  2511 E audit   : type=1327 msg=audit(1472570669.475:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 17:24:29.475  2511  2511 E audit   : type=1320 msg=audit(1472570669.475:285): 
08-30 17:24:29.475  5417  5417 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-30 17:24:29.505   772   792 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-30 17:24:29.505   772  2578 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1811713 3247:com.android.contacts/u0a19}
08-30 17:24:29.515   772  2527 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
08-30 17:24:29.535   772  1604 I ActivityManager: Start proc 6524:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-30 17:24:29.535  6524  6524 E Zygote  : v2
08-30 17:24:29.535  6524  6524 I libpersona: KNOX_SDCARD checking this for 10049
08-30 17:24:29.535  6524  6524 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:29.535  2511  2511 E audit   : type=1400 msg=audit(1472570669.535:286): avc:  denied  { execmod } for  pid=6412 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 17:24:29.535  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.535  2511  2511 E audit   : type=1300 msg=audit(1472570669.535:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f09000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6412 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 17:24:29.535  6524  6524 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:29.535  2511  2511 E audit   : type=1327 msg=audit(1472570669.535:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 17:24:29.535  6524  6524 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.535  2511  2511 E audit   : type=1320 msg=audit(1472570669.535:286): 
08-30 17:24:29.535  6412  6412 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 17:24:29.535  6524  6524 E Zygote  : accessInfo : 0
08-30 17:24:29.535  6524  6524 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-30 17:24:29.545  6412  6412 D AndroidRuntime: CheckJNI is OFF
08-30 17:24:29.545  6412  6412 D AndroidRuntime: readGMSProperty: start
08-30 17:24:29.545  6412  6412 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:24:29.545  6412  6412 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:24:29.545  6412  6412 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:24:29.545  6412  6412 D AndroidRuntime: readGMSProperty: end
08-30 17:24:29.545  6412  6412 D AndroidRuntime: addProductProperty: start
08-30 17:24:29.555  6412  6412 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 17:24:29.555  6412  6412 W art     : af0a5000-b1fcb000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-30 17:24:29.555  6412  6412 W art     : b1fcb000-b423a000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 17:24:29.555  6412  6412 W art     : b423a000-b423b000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-30 17:24:29.555  6412  6412 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 17:24:29.555  6412  6412 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-30 17:24:29.555  6412  6412 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-30 17:24:29.555  6412  6412 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-30 17:24:29.555  6412  6412 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-30 17:24:29.555  6412  6412 W art     : b47d6000-b47d9000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:29.555  6412  6412 W art     : b47d9000-b47da000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:29.555  6412  6412 W art     : b47da000-b47db000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:29.555  6412  6412 W art     : b47db000-b47dc000 r--p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b47dc000-b47fc000 r--s 00000000 00:0b 9236       /dev/__properties__
08-30 17:24:29.555  6412  6412 W art     : b47fc000-b520d000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:29.555  6412  6412 W art     : b520d000-b520e000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b520e000-b5257000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:29.555  6412  6412 W art     : b5257000-b5258000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:29.555  6412  6412 W art     : b5258000-b5260000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5260000-b5295000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:29.555  6412  6412 W art     : b5295000-b5296000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5296000-b5297000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:29.555  6412  6412 W art     : b5297000-b5298000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:29.555  6412  6412 W art     : b5298000-b52f0000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:29.555  6412  6412 W art     : b52f0000-b52f1000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b52f1000-b52f2000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:29.555  6412  6412 W art     : b52f2000-b52f3000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:29.555  6412  6412 W art     : b52f4000-b52fa000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:29.555  6412  6412 W art     : b52fa000-b52fb000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:29.555  6412  6412 W art     : b52fb000-b52fc000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:29.555  6412  6412 W art     : b52fc000-b52fe000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b52ff000-b5309000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:29.555  6412  6412 W art     : b5309000-b530c000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:29.555  6412  6412 W art     : b530c000-b530d000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:29.555  6412  6412 W art     : b530e000-b5325000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:29.555  6412  6412 W art     : b5325000-b5326000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5326000-b5327000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:29.555  6412  6412 W art     : b5327000-b5328000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:29.555  6412  6412 W art     : b5329000-b5333000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:29.555  6412  6412 W art     : b5333000-b5334000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:29.555  6412  6412 W art     : b5334000-b5335000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:29.555  6412  6412 W art     : b5335000-b5339000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:29.555  6412  6412 W art     : b5339000-b533a000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:29.555  6412  6412 W art     : b533a000-b533b000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:29.555  6412  6412 W art     : b533b000-b5351000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:29.555  6412  6412 W art     : b5351000-b5352000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:29.555  6412  6412 W art     : b5352000-b5353000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:29.555  6412  6412 W art     : b5353000-b5360000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:29.555  6412  6412 W art     : b5360000-b5361000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:29.555  6412  6412 W art     : b5361000-b5362000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:29.555  6412  6412 W art     : b5362000-b53c2000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-30 17:24:29.555  6412  6412 W art     : b53c2000-b53c5000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-30 17:24:29.555  6412  6412 W art     : b53c5000-b53c9000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b53c9000-b542a000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-30 17:24:29.555  6412  6412 W art     : b542a000-b542b000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 17:24:29.555  6412  6412 W art     : b542b000-b547a000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:29.555  6412  6412 W art     : b547a000-b547c000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:29.555  6412  6412 W art     : b547c000-b547d000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:29.555  6412  6412 W art     : b547d000-b547e000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b547e000-b5485000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 17:24:29.555  6412  6412 W art     : b5485000-b5486000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 17:24:29.555  6412  6412 W art     : b5486000-b5487000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-30 17:24:29.555  6412  6412 W art     : avc_common.so
08-30 17:24:29.555  6412  6412 W art     : b5488000-b548b000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 17:24:29.555  6412  6412 W art     : b548b000-b548c000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 17:24:29.555  6412  6412 W art     : b548c000-b548d000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-30 17:24:29.555  6412  6412 W art     : enc_common.so
08-30 17:24:29.555  6412  6412 W art     : b548e000-b5492000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-30 17:24:29.555  6412  6412 W art     : b5492000-b5493000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5493000-b5494000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-30 17:24:29.555  6412  6412 W art     : b5494000-b5495000 rw-p 00005000 b3:17 2510       /syste
08-30 17:24:29.555  6412  6412 W art     : m/lib/libpowermanager.so
08-30 17:24:29.555  6412  6412 W art     : b5496000-b54b3000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 17:24:29.555  6412  6412 W art     : b54b3000-b54b4000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 17:24:29.555  6412  6412 W art     : b54b4000-b54b5000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 17:24:29.555  6412  6412 W art     : b54b6000-b54bb000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:29.555  6412  6412 W art     : b54bb000-b54bc000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:29.555  6412  6412 W art     : b54bc000-b54bd000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:29.555  6412  6412 W art     : b54be000-b54ef000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:29.555  6412  6412 W art     : b54ef000-b54f0000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b54f0000-b54f3000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:29.555  6412  6412 W art     : b54f3000-b54f4000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:29.555  6412  6412 W art     : b54f5000-b5530000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-30 17:24:29.555  6412  6412 W art     : b5530000-b5531000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-30 17:24:29.555  6412  6412 W art     : b5531000-b5532000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-30 17:24:29.555  6412  6412 W art     : b5533000-b553a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:29.555  6412  6412 W art     : b553a000-b553b000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b553b000-b553c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:29.555  6412  6412 W art     : b553c000-b553d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:29.555  6412  6412 W art     : b553d000-b553e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b553e000-b5555000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:29.555  6412  6412 W art     : b5555000-b5556000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5556000-b5559000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:29.555  6412  6412 W art     : b5559000-b555a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:29.555  6412  6412 W art     : b555a000-b5579000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:29.555  6412  6412 W art     : b5579000-b557a000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:29.555  6412  6412 W art     : b557a000-b557b000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:29.555  6412  6412 W art     : b557b000-b55b9000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:29.555  6412  6412 W art     : b55b9000-b55ba000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b55ba000-b55bc000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:29.555  6412  6412 W art     : b55bc000-b55bd000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:29.555  6412  6412 W art     : b55be000-b55c5000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:29.555  6412  6412 W art     : b55c5000-b55c6000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:29.555  6412  6412 W art     : b55c6000-b55c7000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:29.555  6412  6412 W art     : b55c8000-b55cb000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:29.555  6412  6412 W art     : b55cb000-b55cc000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:29.555  6412  6412 W art     : b55cc000-b55cd000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:29.555  6412  6412 W art     : b55cd000-b55d3000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:29.555  6412  6412 W art     : b55d3000-b55d4000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b55d4000-b55d5000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:29.555  6412  6412 W art     : b55d5000-b55d6000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:29.555  6412  6412 W art     : b55d6000-b55df000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:29.555  6412  6412 W art     : b55df000-b55e0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:29.555  6412  6412 W art     : b55e0000-b55e1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:29.555  6412  6412 W art     : b55e1000-b5672000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:29.555  6412  6412 W art     : b5672000-b5673000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5673000-b567e000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:29.555  6412  6412 W art     : b567e000-b567f000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:29.555  6412  6412 W art     : b5680000-b5692000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:29.555  6412  6412 W art     : b5692000-b5693000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:29.555  6412  6412 W art     : b5693000-b5694000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:29.555  6412  6412 W art     : b5695000-b569a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:29.555  6412  6412 W art     : b569a000-b569b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:29.555  6412  6412 W art     : b569b000-b569c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:29.555  6412  6412 W art     : b569d000-b570a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:29.555  6412  6412 W art     : b570a000-b570b000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b570b000-b570d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:29.555  6412  6412 W art     : b570d000-b570e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:29.555  6412  6412 W art     : b570e000-b570f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b570f000-b5716000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:29.555  6412  6412 W art     : b5716000-b5717000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:29.555  6412  6412 W art     : b5717000-b5718000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:29.555  6412  6412 W art     : b5719000-b5799000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:29.555  6412  6412 W art     : b5799000-b579a000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b579a000-b579b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:29.555  6412  6412 W art     : b579b000-b579c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:29.555  6412  6412 W art     : b579c000-b57b3000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b57b3000-b57ea000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:29.555  6412  6412 W art     : b57ea000-b57eb000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:29.555  6412  6412 W art     : b57eb000-b57ec000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:29.555  6412  6412 W art     : b57ec000-b5808000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:29.555  6412  6412 W art     : b5808000-b5809000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:29.555  6412  6412 W art     : b5809000-b580a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:29.555  6412  6412 W art     : b580b000-b586c000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:29.555  6412  6412 W art     : b586c000-b586e000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:29.555  6412  6412 W art     : b586e000-b586f000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:29.555  6412  6412 W art     : b5870000-b5895000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 17:24:29.555  6412  6412 W art     : b5895000-b5896000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 17:24:29.555  6412  6412 W art     : b5896000-b5897000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 17:24:29.555  6412  6412 W art     : b5898000-b58a0000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:29.555  6412  6412 W art     : b58a0000-b58a2000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:29.555  6412  6412 W art     : b58a2000-b58a3000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:29.555  6412  6412 W art     : b58a4000-b58a7000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:29.555  6412  6412 W art     : b58a7000-b58a8000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:29.555  6412  6412 W art     : b58a8000-b58a9000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:29.555  6412  6412 W art     : b58a9000-b58ad000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:29.555  6412  6412 W art     : b58ad000-b58ae000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b58ae000-b58af000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:29.555  6412  6412 W art     : b58af000-b58b0000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:29.555  6412  6412 W art     : b58b0000-b58c0000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:29.555  6412  6412 W art     : b58c0000-b58c1000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:29.555  6412  6412 W art     : b58c1000-b58c2000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:29.555  6412  6412 W art     : b58c2000-b5908000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5908000-b5911000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 17:24:29.555  6412  6412 W art     : b5911000-b5912000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-30 17:24:29.555  6412  6412 W art     : b5912000-b5913000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-30 17:24:29.555  6412  6412 W art     : b5914000-b5919000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:29.555  6412  6412 W art     : b5919000-b591a000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:29.555  6412  6412 W art     : b591a000-b591b000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:29.555  6412  6412 W art     : b591b000-b591e000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:29.555  6412  6412 W art     : b591e000-b591f000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b591f000-b5920000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:29.555  6412  6412 W art     : b5920000-b5921000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:29.555  6412  6412 W art     : b5921000-b5922000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-30 17:24:29.555  6412  6412 W art     : or]
08-30 17:24:29.555  6412  6412 W art     : b5922000-b593a000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:29.555  6412  6412 W art     : b593a000-b593b000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b593b000-b593c000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:29.555  6412  6412 W art     : b593c000-b593d000 rw-p 00019000 b3:
08-30 17:24:29.555  6412  6412 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:29.555  6412  6412 W art     : b593e000-b5ad8000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 17:24:29.555  6412  6412 W art     : b5ad8000-b5ad9000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5ad9000-b5ae6000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 17:24:29.555  6412  6412 W art     : b5ae6000-b5ae7000 rw-p 001a7000 b3:17 604        /system/
08-30 17:24:29.555  6412  6412 W art     : lib/libstagefright.so
08-30 17:24:29.555  6412  6412 W art     : b5ae7000-b5aeb000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 17:24:29.555  6412  6412 W art     : b5aeb000-b5aec000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5aec000-b5aed000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 17:24:29.555  6412  6412 W art     : b5aed000-b5aee000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 17:24:29.555  6412  6412 W art     : ersona.so
08-30 17:24:29.555  6412  6412 W art     : b5aee000-b5b01000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:29.555  6412  6412 W art     : b5b01000-b5b02000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:29.555  6412  6412 W art     : b5b02000-b5b03000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:29.555  6412  6412 W art     : b5b04000-b5b4f000 r
08-30 17:24:29.555  6412  6412 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:29.555  6412  6412 W art     : b5b4f000-b5b50000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:29.555  6412  6412 W art     : b5b50000-b5b51000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:29.555  6412  6412 W art     : b5b51000-b5b53000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5b53000-b5b54000 r--p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5b54000-b5b65000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:29.555  6412  6412 W art     : b5b65000-b5b66000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5b66000-b5b67000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:29.555  6412  6412 W art     : b5b67000-b5b68000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:29.555  6412  6412 W art     : b5b68000-b5b69000 r--p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5b69000-b5b73000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:29.555  6412  6412 W art     : b5b73000-b5b75000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:29.555  6412  6412 W art     : b5b75000-b5b76000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:29.555  6412  6412 W art     : b5b76000-b5b8f000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:29.555  6412  6412 W art     : b5b8f000-b5b90000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:29.555  6412  6412 W art     : b5b90000-b5b93000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:29.555  6412  6412 W art     : b5b93000-b5b97000 rw-p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5b97000-b5c0b000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:29.555  6412  6412 W art     : b5c0b000-b5c0c000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5c0c000-b5c0f000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:29.555  6412  6412 W art     : b5c0f000-b5c10000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:29.555  6412  6412 W art     : b5c10000-b5c11000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c11000-b5c14000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:29.555  6412  6412 W art     : b5c14000-b5c15000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:29.555  6412  6412 W art     : b5c15000-b5c16000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:29.555  6412  6412 W art     : b5c16000-b5c17000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c17000-b5c1c000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:29.555  6412  6412 W art     : b5c1c000-b5c1d000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:29.555  6412  6412 W art     : b5c1d000-b5c1e000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:29.555  6412  6412 W art     : b5c1e000-b5c1f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c1f000-b5c22000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:29.555  6412  6412 W art     : b5c22000-b5c23000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:29.555  6412  6412 W art     : b5c23000-b5c24000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:29.555  6412  6412 W art     : b5c24000-b5c25000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:29.555  6412  6412 W art     : b5c25000-b5c29000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:29.555  6412  6412 W art     : b5c29000-b5c2a000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:29.555  6412  6412 W art     : b5c2a000-b5c2b000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:29.555  6412  6412 W art     : b5c2b000-b5c2c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c2c000-b5c30000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:29.555  6412  6412 W art     : b5c30000-b5c31000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:29.555  6412  6412 W art     : b5c31000-b5c32000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:29.555  6412  6412 W art     : b5c32000-b5c33000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c33000-b5c41000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:29.555  6412  6412 W art     : b5c41000-b5c42000 ---p 00000000 00:00 0 
08-30 17:24:29.555  6412  6412 W art     : b5c42000-b5c43000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:29.555  6412  6412 W art     : b5c43000-b5c44000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:29.555  6412  6412 W art     : b5c44000-b5c4e000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:29.555  6412  6412 W art     : b5c4e000-b5c51000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:29.555  6412  6412 W art     : b5c51000-b5c52000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:29.555  6412  6412 W art     : b5c52000-b5c53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.555  6412  6412 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:29.555  6412  6412 W art     : b5c5d000-b5c60000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:29.565  6412  6412 W art     : b5c60000-b5c61000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:29.565  6412  6412 W art     : b5c61000-b5c65000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:29.565  6412  6412 W art     : b5c65000-b5c66000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:29.565  6412  6412 W art     : b5c66000-b5c67000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:29.565  6412  6412 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b5c68000-b5c75000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:29.565  6412  6412 W art     : b5c75000-b5c77000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:29.565  6412  6412 W art     : b5c77000-b5c78000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:29.565  6412  6412 W art     : b5c78000-b608a000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:29.565  6412  6412 W art     : b608a000-b608b000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b608b000-b6094000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:29.565  6412  6412 W art     : b6094000-b6098000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:29.565  6412  6412 W art     : b6098000-b6099000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6099000-b60a0000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:29.565  6412  6412 W art     : b60a0000-b60a1000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:29.565  6412  6412 W art     : b60a1000-b60a2000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:29.565  6412  6412 W art     : b60a2000-b60a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b60a3000-b60be000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-30 17:24:29.565  6412  6412 W art     : b60be000-b60bf000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 17:24:29.565  6412  6412 W art     : b60bf000-b60c0000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 17:24:29.565  6412  6412 W art     : b60c0000-b60c1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b60c1000-b610d000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:29.565  6412  6412 W art     : b610d000-b610e000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b610e000-b610f000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:29.565  6412  6412 W art     : b610f000-b6110000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:29.565  6412  6412 W art     : b6110000-b6111000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6111000-b6115000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:29.565  6412  6412 W art     : b6115000-b6116000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6116000-b6117000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:29.565  6412  6412 W art     : b6117000-b6118000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:29.565  6412  6412 W art     : b6118000-b6150000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:29.565  6412  6412 W art     : b6150000-b6151000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:29.565  6412  6412 W art     : b6151000-b6152000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:29.565  6412  6412 W art     : b6152000-b6153000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6153000-b61f2000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:29.565  6412  6412 W art     : b61f2000-b6210000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:29.565  6412  6412 W art     : b6210000-b6211000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:29.565  6412  6412 W art     : b6211000-b6384000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:29.565  6412  6412 W art     : b6384000-b638f000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:29.565  6412  6412 W art     : b638f000-b6390000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:29.565  6412  6412 W art     : b6390000-b64a7000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:29.565  6412  6412 W art     : b64a7000-b64b2000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:29.565  6412  6412 W art     : b64b2000-b64b3000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:29.565  6412  6412 W art     : b64b3000-b64b7000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b64b7000-b64db000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 17:24:29.565  6412  6412 W art     : b64db000-b64dd000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-30 17:24:29.565  6412  6412 W art     : b64dd000-b64de000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-30 17:24:29.565  6412  6412 W art     : b64de000-b6584000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:29.565  6412  6412 W art     : b6584000-b6591000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:29.565  6412  6412 W art     : b6591000-b6592000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:29.565  6412  6412 W art     : b6592000-b6593000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6593000-b65e6000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:29.565  6412  6412 W art     : b65e6000-b65e7000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b65e7000-b65e8000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:29.565  6412  6412 W art     : b65e8000-b65e9000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:29.565  6412  6412 W art     : b65e9000-b65ee000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b65ee000-b6600000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:29.565  6412  6412 W art     : b6600000-b6601000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6601000-b6602000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:29.565  6412  6412 W art     : b6602000-b6603000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:29.565  6412  6412 W art     : b6603000-b660a000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:29.565  6412  6412 W art     : b660a000-b660b000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:29.565  6412  6412 W art     : b660b000-b660c000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:29.565  6412  6412 W art     : b660c000-b660d000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b660d000-b6610000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:29.565  6412  6412 W art     : b6610000-b6611000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:29.565  6412  6412 W art     : b6611000-b6612000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:29.565  6412  6412 W art     : b6612000-b6616000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 17:24:29.565  6412  6412 W art     : b6616000-b6617000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 17:24:29.565  6412  6412 W art     : b6617000-b6618000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-30 17,:24:29.565  6412  6412 W art     : b6618000-b6626000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:29.565  6412  6412 W art     : b6626000-b6627000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6627000-b6628000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:29.565  6412  6412 W art     : b6628000-b6629000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:29.565  6412  6412 W art     : b6629000-b6632000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:29.565  6412  6412 W art     : b6632000-b6633000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:29.565  6412  6412 W art     : b6633000-b6634000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:29.565  6412  6412 W art     : b6634000-b669a000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:29.565  6412  6412 W art     : b669a000-b669b000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b669b000-b669d000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:29.565  6412  6412 W art     : b669d000-b66a6000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:29.565  6412  6412 W art     : b66a6000-b66a9000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b66a9000-b6740000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:29.565  6412  6412 W art     : b6740000-b6742000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:29.565  6412  6412 W art     : b6742000-b6743000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:29.565  6412  6412 W art     : b6743000-b6744000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6744000-b6a62000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 17:24:29.565  6412  6412 W art     : b6a62000-b6a63000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6a63000-b6a7e000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 17:24:29.565  6412  6412 W art     : b6a7e000-b6a82000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-30 17:24:29.565  6412  6412 W art     : b6a82000-b6a87000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6a87000-b6a8f000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:29.565  6412  6412 W art     : b6a8f000-b6a90000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:29.565  6412  6412 W art     : b6a90000-b6a91000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:29.565  6412  6412 W art     : b6a91000-b6abf000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:29.565  6412  6412 W art     : b6abf000-b6ac0000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6ac0000-b6ac7000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:29.565  6412  6412 W art     : b6ac7000-b6ac8000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:29.565  6412  6412 W art     : b6ac8000-b6b0e000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:29.565  6412  6412 W art     : b6b0e000-b6b0f000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6b0f000-b6b12000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:29.595   772  3521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 17:24:29.565  6412  6412 W art     : b6b12000-b6b13000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:29.565  6412  6412 W art     : b6b13000-b6b2e000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:29.565  6412  6412 W art     : b6b2e000-b6b32000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:29.565  6412  6412 W art     : b6b32000-b6b33000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:29.565  6412  6412 W art     : b6b33000-b6b80000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:29.565  6412  6412 W art     : b6b80000-b6b81000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6b81000-b6b8d000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:29.565  6412  6412 W art     : b6b8d000-b6b8e000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:29.565  6412  6412 W art     : b6b8e000-b6b9b000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-30 17:24:29.565  6412  6412 W art     : b6b9b000-b6b9c000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6b9c000-b6b9d000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 17:24:29.565  6412  6412 W art     : b6b9d000-b6b9e000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-30 17:24:29.565  6412  6412 W art     : b6b9e000-b6ba6000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ba6000-b6ba7000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6ba7000-b6ba8000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ba8000-b6ba9000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ba9000-b6bb0000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:29.565  6412  6412 W art     : b6bb0000-b6bb1000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:29.565  6412  6412 W art     : b6bb1000-b6bb2000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:29.565  6412  6412 W art     : b6bb2000-b6bc6000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:29.565  6412  6412 W art     : b6bc6000-b6bc8000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:29.565  6412  6412 W art     : b6bc8000-b6bc9000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:29.565  6412  6412 W art     : b6bc9000-b6bf1000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:29.565  6412  6412 W art     : b6bf1000-b6bf3000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:29.565  6412  6412 W art     : b6bf3000-b6bf4000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:29.565  6412  6412 W art     : b6bf4000-b6bf7000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:29.565  6412  6412 W art     : b6bf7000-b6bf8000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:29.565  6412  6412 W art     : b6bf8000-b6bf9000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:29.565  6412  6412 W art     : b6bf9000-b6c02000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:29.565  6412  6412 W art     : b6c02000-b6c03000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:29.565  6412  6412 W art     : b6c03000-b6c04000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:29.565  6412  6412 W art     : b6c04000-b6c24000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 17:24:29.565  6412  6412 W art     : b6c24000-b6c25000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-30 17:24:29.565  6412  6412 W art     : b6c25000-b6c26000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 17:24:29.565  6412  6412 W art     : b6c26000-b6c99000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 17:24:29.565  6412  6412 W art     : b6c99000-b6c9d000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-30 17:24:29.565  6412  6412 W art     : b6c9d000-b6ca0000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-30 17:24:29.565  6412  6412 W art     : b6ca0000-b6caa000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6caa000-b6d32000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:29.565  6412  6412 W art     : b6d32000-b6d33000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6d33000-b6d37000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:29.565  6412  6412 W art     : b6d37000-b6d38000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:29.565  6412  6412 W art     : b6d38000-b6d39000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6d39000-b6d62000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:29.565  6412  6412 W art     : b6d62000-b6d63000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6d63000-b6d66000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:29.565  6412  6412 W art     : b6d66000-b6d67000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:29.565  6412  6412 W art     : b6d67000-b6e41000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:29.565  6412  6412 W art     : b6e41000-b6e48000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:29.565  6412  6412 W art     : b6e48000-b6e50000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:29.565  6412  6412 W art     : b6e50000-b6e51000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6e51000-b6e52000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:29.565  6412  6412 W art     : b6e52000-b6e53000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-30 17:24:29.565  6412  6412 W art     : b6e53000-b6e54000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6e54000-b6e57000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6e57000-b6e7c000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:29.565  6412  6412 W art     : b6e7c000-b6e7d000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6e7d000-b6e84000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:29.565  6412  6412 W art     : b6e84000-b6e85000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:29.565  6412  6412 W art     : b6e85000-b6e8c000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:29.565  6412  6412 W art     : b6e8c000-b6e8d000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:29.565  6412  6412 W art     : b6e8d000-b6e8e000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:29.565  6412  6412 W art     : b6e8e000-b6e8f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6e8f000-b6ea7000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ea7000-b6ea8000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6ea8000-b6ea9000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ea9000-b6eaa000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 17:24:29.565  6412  6412 W art     : b6eaa000-b6eb8000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:29.565  6412  6412 W art     : b6eb8000-b6eb9000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6eb9000-b6eba000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:29.565  6412  6412 W art     : b6eba000-b6ebb000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:29.565  6412  6412 W art     : b6ebb000-b6ebc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:29.565  6412  6412 W art     : b6ebc000-b6ebe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6ebe000-b6ebf000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6ebf000-b6ec0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:29.565  6412  6412 W art     : b6ec0000-b6ec1000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 17:24:29.565  6412  6412 W art     : b6ec1000-b6ec2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:29.565  6412  6412 W art     : b6ec2000-b6ee2000 r--s 00000000 00:0b 9236       /dev/__properties__
08-30 17:24:29.565  6412  6412 W art     : b6ee2000-b6ee3000 r--p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6ee3000-b6ee4000 ---p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6ee4000-b6ee6000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-30 17:24:29.565  6412  6412 W art     : b6ee6000-b6ee7000 r-xp 00000000 00:00 0          [sigpage]
08-30 17:24:29.565  6412  6412 W art     : b6ee7000-b6f02000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 17:24:29.565  6412  6412 W art     : b6f02000-b6f03000 r--p 0001a000 b3:17 341        /system/bin/linker
08-30 17:24:29.565  6412  6412 W art     : b6f03000-b6f05000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 17:24:29.565  6412  6412 W art     : b6f05000-b6f07000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : b6f07000-b6f0c000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 17:24:29.565  6412  6412 W art     : b6f0c000-b6f0d000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-30 17:24:29.565  6412  6412 W art     : b6f0d000-b6f0e000 rw-p 00000000 00:00 0 
08-30 17:24:29.565  6412  6412 W art     : bed4c000-bed6d000 rw-p 00000000 00:00 0          [stack]
08-30 17:24:29.565  6412  6412 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-30 17:24:29.635  6412  6412 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 17:24:29.635  6524  6524 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:29.635  6524  6524 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.655   772   791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de5cc69 6524:com.android.mms/u0a49}
08-30 17:24:29.665  4255  6536 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-30 17:24:29.685  6524  6524 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-30 17:24:29.685  6412  6412 I Radio-JNI: register_android_hardware_Radio DONE
08-30 17:24:29.695  6412  6412 E AffinityControl: AffinityControl: registerfunction enter
08-30 17:24:29.715  6412  6412 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:24:29.725  1812  6498 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 381 ms] updated apps [took 381 ms] 
08-30 17:24:29.735  6524  6524 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-30 17:24:29.735   772  1217 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-30 17:24:29.735  6524  6524 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-30 17:24:29.745   772  1217 D ActivityManager: mDVFSHelper.acquire()
08-30 17:24:29.745   772  1217 D FocusedStackFrame: Set to : 0
08-30 17:24:29.745   772  1217 V WindowManager: addAppToken: AppWindowToken{45f6987 token=Token{8a35c6 ActivityRecord{2719fa1 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-30 17:24:29.755   772   904 D SecWifiDisplayUtil: Metadata value : none
08-30 17:24:29.755   772   904 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ce2027f V.E...... R.....ID 0,0-0,0}
08-30 17:24:29.755   772   904 D ISSUE_DEBUG: InputChannelName : 46d8295 Starting com.test.thalitest
08-30 17:24:29.765  6544  6544 E Zygote  : v2
08-30 17:24:29.765  6544  6544 I libpersona: KNOX_SDCARD checking this for 10004
08-30 17:24:29.765  6544  6544 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:29.775  6544  6544 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:29.775  6544  6544 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:29.775   772  1217 D InputDispatcher: Focused application set to: xxxx
08-30 17:24:29.775   772  1217 I ActivityManager: Start proc 6544:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-30 17:24:29.775  6544  6544 E Zygote  : accessInfo : 0
08-30 17:24:29.775  6544  6544 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 17:24:29.775   772  1217 D InputDispatcher: Focus left window: 1697
08-30 17:24:29.775   292   292 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-30 17:24:29.775   772  1319 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 17:24:29.775  6412  6412 D AndroidRuntime: Shutting down VM
08-30 17:24:29.775  6524  6524 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-30 17:24:29.795   772   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:772 uid:1000
08-30 17:24:29.795   772   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:24:29.795   772   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:772 uid:1000
08-30 17:24:29.795   772   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-30 17:24:29.795   772   904 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-30 17:24:29.795  6524  6524 D Mms/TelephonyPermission: start operation mode monitor
08-30 17:24:29.795  6524  6524 D Mms/TelephonyPermission: User ID is null set current User Id
08-30 17:24:29.795  6524  6558 D Mms/ArtClassLoader: init before art third
08-30 17:24:29.795  6524  6556 D Mms/ArtClassLoader: init before art first
08-30 17:24:29.805  6544  6544 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:29.805  6544  6544 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:29.805   772  2575 V WindowOrientationListener: setCurrentAppOrientation :-1
08-30 17:24:29.805   772  2575 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-30 17:24:29.815  6524  6557 D Mms/ArtClassLoader: init before art second
08-30 17:24:29.815  6524  6524 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-30 17:24:29.815   772   875 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{46d8295 u0 d0 Starting com.test.thalitest}
08-30 17:24:29.825  6524  6524 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-30 17:24:29.825  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-30 17:24:29.835   772  2575 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 17:24:29.835  1697  1883 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-30 17:24:29.835  1697  1697 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-30 17:24:29.845  6524  6558 D Mms/ArtClassLoader: init [DONE] art
08-30 17:24:29.855   772   904 V WindowStateAnimator: Finishing drawing window Window{46d8295 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 17:24:29.855   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeebb364
08-30 17:24:29.855   292  5235 D libEGL  : eglTerminate EGLDisplay = 0xb471864c
08-30 17:24:29.855   292  5235 D libEGL  : eglTerminate EGLDisplay = 0xb471864c
08-30 17:24:29.865   292  1500 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-30 17:24:29.865   292  5235 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-30 17:24:29.865  2252  2270 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-30 17:24:29.865  1697  1697 V ActivityThread: updateVisibility : ActivityRecord{2857cee token=android.os.BinderProxy@61b5205 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 17:24:29.875   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb3a4
08-30 17:24:29.875  1697  1697 D Launcher: onTrimMemory. Level: 20
08-30 17:24:29.945  6524  6556 D Mms/ArtClassLoader: init [DONE] art
08-30 17:24:29.955  6524  6557 D Mms/ArtClassLoader: init [DONE] art
,08-30 17:24:30.165   772  2575 I WindowManager: Screenshot max retries 4 of Token{8a35c6 ActivityRecord{2719fa1 u0 com.test.thalitest/.MainActivity t167}} appWin=Window{46d8295 u0 d0 Starting com.test.thalitest} drawState=4
,08-30 17:24:30.165   772   872 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-30 17:24:30.175   772  1319 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 17:24:30.185   772  3482 D M       : limitCPUFreq:: freq = -1
08-30 17:24:30.185   772  3482 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 772  tag : SIOP_ARM_MAX@25
,08-30 17:24:30.185   772  3482 D M       : limitGPUFreq:: freq = -1
,08-30 17:24:30.185  6544  6544 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 17:24:30.185  6524  6524 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-30 17:24:30.185  6524  6524 D Mms/TelephonyPermission: isDefault true
,08-30 17:24:30.195   772  3482 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 17:24:30.195  6524  6524 D Mms/MmsApp: onCreate() com.android.mms
,08-30 17:24:30.205  6524  6524 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-30 17:24:30.205  6524  6524 D Mms/MmsApp: [start]    initCountryIso consume time = 429.567708
,08-30 17:24:30.215   772  1718 D CountryDetector: The first listener is added
,08-30 17:24:30.215  6544  6544 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 17:24:30.215  6544  6544 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 17:24:30.215  6524  6524 D Mms/MmsApp: [end]    initCountryIso consume time = 8.119271
08-30 17:24:30.215  6524  6524 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.23349
,08-30 17:24:30.235  6544  6544 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-30 17:24:30.235  6524  6524 D Mms/MmsConfig: before partial update
,08-30 17:24:30.255  6544  6544 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 17:24:30.265  6544  6544 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 17:24:30.265  6524  6524 D Mms/MmsConfig: Load Resize quality : 80
,08-30 17:24:30.265  6524  6524 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-30 17:24:30.265  6524  6524 D EasySignUpManager_1.0.5: isAuth is false
08-30 17:24:30.265  6524  6524 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-30 17:24:30.265  6524  6524 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
08-30 17:24:30.265  6544  6544 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7145-7149)
08-30 17:24:30.265  6544  6544 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-30 17:24:30.275  6524  6524 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-30 17:24:30.275  6524  6524 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-30 17:24:30.275  6524  6524 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-30 17:24:30.275  6524  6524 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-30 17:24:30.275  6524  6524 D EasySignUpManager_1.0.5: isAuth is false
08-30 17:24:30.275  6524  6524 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-30 17:24:30.275  6524  6524 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-30 17:24:30.285  1683  1694 D TP/MmsSmsProvider: query, match:2117, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.285  1683  1694 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.797 ms
,08-30 17:24:30.285  6544  6544 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d5866a}
,08-30 17:24:30.285  6544  6544 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-30 17:24:30.285  6544  6544 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:24:30.285  6544  6572 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-30 17:24:30.295  6524  6524 E CscParser: mps_code.dat does not exist
08-30 17:24:30.295  6524  6524 E CscParser: customer_path =/system/csc/customer.xml
08-30 17:24:30.295  6524  6524 E CscParser: fileName + /system/csc/customer.xml
,08-30 17:24:30.295  6544  6544 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 17:24:30.305  6524  6524 E CscParser: mps_code.dat does not exist
08-30 17:24:30.305  6524  6524 E CscParser: customer_path =/system/csc/customer.xml
,08-30 17:24:30.305  6524  6524 E CscParser: fileName + /system/csc/customer.xml
,08-30 17:24:30.305  6524  6524 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-30 17:24:30.305  6524  6524 D Mms/MmsConfig:  enable multiwindow = true
,08-30 17:24:30.315  6524  6524 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-30 17:24:30.315  6524  6524 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-30 17:24:30.315  6524  6524 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-30 17:24:30.315  6524  6524 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-30 17:24:30.315  6524  6524 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-30 17:24:30.315  6524  6524 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-30 17:24:30.315  6524  6524 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-30 17:24:30.315  6524  6524 D Mms/MmsConfig: [end]    init() consume time = 101.411094
,08-30 17:24:30.325  6524  6524 D Mms/Contact: [start]    init() consume time = 4.338021
,08-30 17:24:30.325  6544  6544 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 17:24:30.325  6544  6544 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 17:24:30.325  6544  6544 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 17:24:30.325  6544  6544 I Adreno-EGL: Local Branch: ss
08-30 17:24:30.325  6544  6544 I Adreno-EGL: Remote Branch: 
08-30 17:24:30.325  6544  6544 I Adreno-EGL: Local Patches: 
08-30 17:24:30.325  6544  6544 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:24:30.335  1683  1696 D TP/MmsSmsProvider: query, match:13, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.335  6544  6544 D libEGL  : eglInitialize EGLDisplay = 0xbe980dac
,08-30 17:24:30.335  1683  1696 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.326 ms
,08-30 17:24:30.335  6524  6524 D Mms/Contact: [end]    init consume time = 11.910468
,08-30 17:24:30.335  6524  6579 D Mms/DraftCache: [start]    rebuildCache consume time = 3.114792
,08-30 17:24:30.345  6524  6524 D Mms:transaction: roaming -> false (slotId = 0)
08-30 17:24:30.345  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 17:24:30.345  6524  6524 D Mms:transaction: auto download without roaming -> true
08-30 17:24:30.345  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-30 17:24:30.345  6524  6524 D Mms:transaction: roaming -> false (slotId = 1)
08-30 17:24:30.345  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-30 17:24:30.345  6524  6524 D Mms:transaction: auto download without roaming -> true
08-30 17:24:30.345  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-30 17:24:30.345  6524  6524 D Mms:transaction: auto download during roaming secondary -> false
08-30 17:24:30.345  6524  6524 D Mms:transaction: mAutoDownload ------> true
,08-30 17:24:30.355  1683  1868 D TP/MmsSmsProvider: query, match:12, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.355  1683  1868 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.411 ms
,08-30 17:24:30.355  6524  6579 D Mms/DraftCache: [end]    rebuildCache consume time = 18.582344
,08-30 17:24:30.365  6524  6524 D ComposerPerformance: 1472570670373 ms / [DONE] Composer constructor
,08-30 17:24:30.365  6524  6581 D Mms/Conversation: [start]    init() consume time = 9.016094
,08-30 17:24:30.365  6524  6524 D CII     : Log Level [5]
08-30 17:24:30.365  6524  6524 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-30 17:24:30.365  1683  1696 D TP/MmsSmsProvider: delete, match:1, calling pid = 6524
08-30 17:24:30.365  1683  1696 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 17:24:30.365  1683  1696 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-30 17:24:30.365  6524  6524 I Mms/ReservationManager: ReservationManager()
,08-30 17:24:30.365  6524  6524 I Mms/ReservationManager: resetAfterConnected()
,08-30 17:24:30.375  1683  1696 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-30 17:24:30.375  1683  1696 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-30 17:24:30.375  1683  1696 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-30 17:24:30.375   772  1418 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-30 17:24:30.375   772  1418 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-30 17:24:30.385  1683  1867 D TP/MmsSmsProvider: query, match:7, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.385  1683  1867 D TP/MmsSmsProvider: query, match 7:Elapsed time : 6.824 ms
,08-30 17:24:30.385  1683  1696 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-30 17:24:30.395  6524  6524 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-30 17:24:30.405  6524  6524 D Mms/MmsApp: [end]    onCreate() consume time = 37.506146
,08-30 17:24:30.405  6524  6524 D Mms/MmsApp: [end]    onCreate() consume time = 0.230104
,08-30 17:24:30.415  1683  1696 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-30 17:24:30.415  1683  1696 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-30 17:24:30.415  1683  1696 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-30 17:24:30.415  1683  1696 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 34.741 ms
08-30 17:24:30.415  1683  1696 D TP/MmsSmsProvider: need read changed broadcast:false
,08-30 17:24:30.415  6524  6524 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-30 17:24:30.415  6524  6524 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-30 17:24:30.415  6524  6524 D Mms:transaction: roaming -> false (slotId = 0)
08-30 17:24:30.415  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 17:24:30.415  6524  6524 D Mms:transaction: auto download without roaming -> true
08-30 17:24:30.415  6524  6524 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-30 17:24:30.415  6524  6524 D Mms:transaction: mAutoDownload ------> true
,08-30 17:24:30.425  6598  6598 E Zygote  : v2
08-30 17:24:30.425  6598  6598 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:24:30.425  6598  6598 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:30.435   772  2564 I ActivityManager: Start proc 6598:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-30 17:24:30.435  6598  6598 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:30.435  6598  6598 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:30.435  6598  6598 E Zygote  : accessInfo : 0
,08-30 17:24:30.435  6524  6581 D Mms/Conversation: [end]    init consume time = 34.639999
,08-30 17:24:30.445  6524  6581 D Mms/MessagingNotification: [start]    init() consume time = 6.79573
,08-30 17:24:30.445  6544  6544 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-30 17:24:30.445  6524  6581 D Mms/MessagingNotification: [end]    init consume time = 1.583645
,08-30 17:24:30.445  6524  6611 D Mms/Synchronizer: [start]    doSync consume time = 2.1975
,08-30 17:24:30.455  1683  1868 D TP/MmsSmsProvider: update, match:300, calling pid = 6524
08-30 17:24:30.455  1683  1868 V TP/MmsSmsProvider: syncDBData start
,08-30 17:24:30.455  1683  1868 V TP/MmsSmsProvider: syncDBData sms end
,08-30 17:24:30.455  1683  1868 V TP/MmsSmsProvider: syncDBData mms end
,08-30 17:24:30.455  1683  1868 V TP/MmsSmsProvider: syncDBData end
,08-30 17:24:30.455  1683  1868 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.006 ms
,08-30 17:24:30.455  6544  6544 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:24:30.455  6524  6611 D Mms/Synchronizer: [end]    doSync consume time = 10.799688
,08-30 17:24:30.455  6544  6544 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-30 17:24:30.465  6544  6544 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-30 17:24:30.465  6544  6544 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-30 17:24:30.465  6524  6610 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 6.203854
,08-30 17:24:30.475  6598  6598 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:24:30.475  6598  6598 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:30.475  1683  1696 D TP/MmsSmsProvider: query, match:0, calling pid = 6524, accessRestricted = false
08-30 17:24:30.475  1683  1696 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-30 17:24:30.475  1683  1696 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.351 ms
,08-30 17:24:30.485  6544  6544 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-30 17:24:30.485  1683  1694 D TP/MmsSmsProvider: query, match:400, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.485   772  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d810df1 6598:com.samsung.android.bbc.bbcagent/1000}
,08-30 17:24:30.485  6524  6610 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 20.488438
,08-30 17:24:30.485  6544  6544 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 17:24:30.495  6083  6099 D BadgeProvider: query, [selection] : package=?
,08-30 17:24:30.495  6598  6598 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-30 17:24:30.505  6524  6581 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-30 17:24:30.515  1683  1696 D TP/SmsProvider: query,matched:26, calling pid = 6524
,08-30 17:24:30.515  1683  1696 D TP/SmsProvider: query, match 26:Elapsed time : 1.087 ms
,08-30 17:24:30.525  1683  1694 D TP/MmsSmsProvider: query, match:6, calling pid = 6524, accessRestricted = false
,08-30 17:24:30.525  1683  1694 D TP/MmsSmsProvider: query, match 6:Elapsed time : 0.954 ms
,08-30 17:24:30.545  6598  6598 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-30 17:24:30.565  6616  6616 E Zygote  : v2
08-30 17:24:30.565  6616  6616 I libpersona: KNOX_SDCARD checking this for 10024
08-30 17:24:30.565  6616  6616 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:30.565  6616  6616 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:30.565  6616  6616 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:30.565  6616  6616 E Zygote  : accessInfo : 0
,08-30 17:24:30.565  6616  6616 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-30 17:24:30.565   772  1604 I ActivityManager: Start proc 6616:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-30 17:24:30.575  6626  6626 E Zygote  : v2
08-30 17:24:30.575  6626  6626 I libpersona: KNOX_SDCARD checking this for 10097
08-30 17:24:30.575  6626  6626 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:30.575  6626  6626 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:30.575  6626  6626 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:30.585  6626  6626 E Zygote  : accessInfo : 0
08-30 17:24:30.585  6626  6626 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-30 17:24:30.585   772  1709 I ActivityManager: Start proc 6626:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-30 17:24:30.585   772  1709 I ActivityManager: Killing 5159:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-30 17:24:30.605  6544  6544 D SecWifiDisplayUtil: Metadata value : none
,08-30 17:24:30.605  6544  6544 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{40eff3b I.E...... R.....ID 0,0-0,0}
,08-30 17:24:30.605  6616  6616 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:30.605  6616  6616 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:30.605  6544  6641 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:24:30.615   772  2578 D ISSUE_DEBUG: InputChannelName : 79ccbb0 com.test.thalitest/com.test.thalitest.MainActivity
,08-30 17:24:30.615  6626  6626 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:30.615  6626  6626 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:30.615   772  2527 I ActivityManager: Killing 5175:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-30 17:24:30.625   772  1709 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-30 17:24:30.625   772  2564 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 17:24:30.625   772  2564 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 17:24:30.625   772   772 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 17:24:30.625   772   772 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 17:24:30.635   772  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df28a29 6626:com.google.android.apps.docs/u0a97}
,08-30 17:24:30.645   772   792 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-30 17:24:30.655  6626  6626 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 17:24:30.665  6616  6616 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-30 17:24:30.665  6544  6544 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6544
,08-30 17:24:30.675   772  1718 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6544 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:30.675   772  1328 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-30 17:24:30.675   772  1328 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 17:24:30.675   772  1328 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 17:24:30.675   772  1328 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-30 17:24:30.675   772  1328 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:30.675   772  1802 I ActivityManager: Killing 5204:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-30 17:24:30.685  6544  6572 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-30 17:24:30.685  6544  6544 D SecWifiDisplayUtil: Metadata value : none
,08-30 17:24:30.695   292   292 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-30 17:24:30.695  6616  6616 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-30 17:24:30.705   772  1418 D InputDispatcher: Focus entered window: 6544
,08-30 17:24:30.705   772  1709 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-30 17:24:30.705  6626  6626 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-30 17:24:30.705   772   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:772 uid:1000
08-30 17:24:30.705   772   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:24:30.705   772   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:772 uid:1000
08-30 17:24:30.705   772   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 17:24:30.705  6544  6641 D libEGL  : eglInitialize EGLDisplay = 0x9cabf7c4
08-30 17:24:30.705  6544  6641 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:24:30.725  4255  5099 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-30 17:24:30.755  6544  6544 V ActivityThread: updateVisibility : ActivityRecord{fef8022 token=android.os.BinderProxy@65081ca {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 17:24:30.765  6544  6544 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-30 17:24:30.765  6616  6616 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-30 17:24:30.765  6544  6544 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-30 17:24:30.765   772  2575 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:24:30.775  6524  6581 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-30 17:24:30.775  6544  6544 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 17:24:30.795   772  1217 V WindowStateAnimator: Finishing drawing window Window{79ccbb0 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-30 17:24:30.805   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeebb364
,08-30 17:24:30.805  6544  6544 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-30 17:24:30.805  6544  6544 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@65081ca time:107682
,08-30 17:24:30.815   772   904 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 17:24:30.815   772   772 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 17:24:30.815   772   772 I KnoxTimeoutHandler: SD activityfalse
,08-30 17:24:30.815   772   904 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +647ms (total +1s63ms)
,08-30 17:24:30.815   772   904 D ActivityManager: mDVFSHelper.release()
08-30 17:24:30.815   772   904 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2719fa1 u0 com.test.thalitest/.MainActivity t167} time:107693
,08-30 17:24:30.815   772   904 D ViewRootImpl: #3 mView = null
,08-30 17:24:30.815   292   352 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-30 17:24:30.815   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
,08-30 17:24:30.825   772   785 I art     : Background partial concurrent mark sweep GC freed 151778(9MB) AllocSpace objects, 10(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.951ms total 170.827ms
,08-30 17:24:30.835  6544  6649 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:24:30.835  6544  6649 D libEGL  : eglInitialize EGLDisplay = 0x9a22c3ec
,08-30 17:24:30.845  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-30 17:24:30.845  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-30 17:24:30.845  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-30 17:24:30.855  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-30 17:24:30.865  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-30 17:24:30.865  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-30 17:24:30.865  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-30 17:24:30.865  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-30 17:24:30.875  4255  5099 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-30 17:24:30.875  6544  6544 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6544
,08-30 17:24:30.915  4255  5099 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-30 17:24:31.025  6544  6544 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:24:31.135  6626  6658 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-30 17:24:31.135  6626  6658 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:24:31.135  6626  6658 I GAv4    :   adb logcat -s GAv4
,08-30 17:24:31.135  6544  6655 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1716004560
,08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:24:31.135  6544  6655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aca8588 added. We now have 1 listener(s)
,08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-30 17:24:31.145  6544  6655 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-30 17:24:31.145  6544  6655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:24:31.145  6544  6655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:24:31.145  6544  6655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ac7107 added. We now have 1 listener(s)
08-30 17:24:31.145  6544  6655 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:24:31.145  6544  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 17:24:31.155  6544  6655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:24:31.155  6626  6658 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-30 17:24:31.155  6544  6655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-30 17:24:31.155   772  1802 V AlarmManager:  remove PendingIntent] PendingIntent{1b9b25e: PendingIntentRecord{31dc63f com.google.android.apps.docs broadcastIntent}}
,08-30 17:24:31.155  6626  6658 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:24:31.155  6544  6655 D BluetoothAdapter: STATE_ON
,08-30 17:24:31.155  6544  6655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:24:31.155  6544  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:24:31.155  6626  6658 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-30 17:24:31.155  6544  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 17:24:31.155  6544  6655 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:24:31.155  6544  6655 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:24:31.165  6544  6544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:24:31.165  6544  6544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:24:31.165  6626  6663 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:24:31.165   772  3483 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-30 17:24:31.185  6544  6544 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:24:31.305  6626  6626 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-30 17:24:31.305  6626  6626 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-30 17:24:31.335  3740  3740 D FactoryTest: User mode
,08-30 17:24:31.335  3740  3740 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 17:24:31.335  3740  3740 D MTPRx   : still no open session command from host, so toast
,08-30 17:24:31.335   772  1217 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-30 17:24:31.345   772  1217 D ActivityManager: mDVFSHelper.acquire()
,08-30 17:24:31.355   772  1217 V WindowManager: addAppToken: AppWindowToken{56a966a token=Token{6324c55 ActivityRecord{9cecb0c u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-30 17:24:31.355   772  1217 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-30 17:24:31.355   772   872 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-30 17:24:31.365   772  1217 D InputDispatcher: Focused application set to: xxxx
,08-30 17:24:31.365   772  1217 D InputDispatcher: Focus left window: 6544
,08-30 17:24:31.375   772   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:772 uid:1000
08-30 17:24:31.375   772   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:24:31.375   772   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:772 uid:1000
08-30 17:24:31.375   772   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 17:24:31.375  3740  3740 E MTPRx   : started activity for popup
,08-30 17:24:31.375  3740  3740 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 17:24:31.385  3740  3740 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 17:24:31.385  6626  6658 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-30 17:24:31.385  6626  6658 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-30 17:24:31.385  6626  6658 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-30 17:24:31.385  6626  6658 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-30 17:24:31.415  6671  6671 E Zygote  : v2
08-30 17:24:31.415  6671  6671 I libpersona: KNOX_SDCARD checking this for 10098
08-30 17:24:31.415  6671  6671 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:31.415  6671  6671 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:31.415  6671  6671 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:31.415   772  2578 I ActivityManager: Start proc 6671:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-30 17:24:31.415  6671  6671 E Zygote  : accessInfo : 0
08-30 17:24:31.415  6671  6671 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
08-30 17:24:31.415   772  1418 I ActivityManager: Killing 5100:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-30 17:24:31.415  3740  3740 D MTPUSBConnection: onCreate in USBConnection
,08-30 17:24:31.415  3740  3740 V MTPUSBConnection: Registering broadcast receiver.
,08-30 17:24:31.435  3740  3740 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-30 17:24:31.435   772  1604 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-30 17:24:31.455  6671  6671 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:24:31.455  6671  6671 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:31.465   772   791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86388c2 6671:com.sec.android.automotive.drivelink/u0a98}
,08-30 17:24:31.495   772  2564 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-30 17:24:31.505  3740  3740 D TAG     : dev.kiessupport is : TRUE
,08-30 17:24:31.525  6671  6671 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 17:24:31.535  3740  3740 D SecWifiDisplayUtil: Metadata value : none
,08-30 17:24:31.535  3740  3740 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{df67ceb V.E...... R.....I. 0,0-0,0}
,08-30 17:24:31.545  3740  6687 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:24:31.545  6671  6671 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-30 17:24:31.545   772  1703 D ISSUE_DEBUG: InputChannelName : 6656f0e com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 17:24:31.545   772  1703 D InputDispatcher: Focus entered window: 3740
,08-30 17:24:31.545   772   875 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6656f0e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-30 17:24:31.545  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-30 17:24:31.545   772   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:772 uid:1000
08-30 17:24:31.545   772   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:24:31.545   772   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:772 uid:1000
08-30 17:24:31.545   772   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 17:24:31.555  3740  3740 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c939e63 I.E...... R.....I. 0,0-0,0}
,08-30 17:24:31.555   772  1718 D ISSUE_DEBUG: InputChannelName : b210f3c com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 17:24:31.555   772  1604 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-30 17:24:31.555   772  1604 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 17:24:31.555   772   772 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 17:24:31.555   772   772 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 17:24:31.555   772   772 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 17:24:31.595   292   292 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-30 17:24:31.595  6671  6671 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 17:24:31.605  3740  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 17:24:31.605  3740  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 17:24:31.605  3740  6687 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 17:24:31.605  3740  6687 I Adreno-EGL: Local Branch: ss
08-30 17:24:31.605  3740  6687 I Adreno-EGL: Remote Branch: 
08-30 17:24:31.605  3740  6687 I Adreno-EGL: Local Patches: 
08-30 17:24:31.605  3740  6687 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:24:31.605  3740  6687 D libEGL  : eglInitialize EGLDisplay = 0x9ef937c4
08-30 17:24:31.605  3740  6687 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:24:31.615  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:31.615  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:31.635   772  1802 V AlarmManager:  remove PendingIntent] PendingIntent{d8de328: PendingIntentRecord{9901841 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 17:24:31.645  6671  6671 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-30 17:24:31.645  6671  6690 I GMPM    : App measurement is starting up
,08-30 17:24:31.655  6671  6690 E GMPM    : getGoogleAppId failed with status: 10
,08-30 17:24:31.655   292   292 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,08-30 17:24:31.675  3740  3740 V ActivityThread: updateVisibility : ActivityRecord{a0ad7de token=android.os.BinderProxy@4c4fa48 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-30 17:24:31.675  6671  6690 E GMPM    : Uploading is not possible. App measurement disabled
,08-30 17:24:31.675   772  2527 V AlarmManager:  remove PendingIntent] PendingIntent{d0451e6: PendingIntentRecord{9901841 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 17:24:31.675  3740  3740 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 17:24:31.735   772  6322 I HarmonyEASService: Updating for all 1
,08-30 17:24:31.755  6671  6671 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-30 17:24:31.765  6671  6671 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-30 17:24:31.765  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:31.775   772  1802 V WindowStateAnimator: Finishing drawing window Window{6656f0e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 17:24:31.775  3740  3740 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 17:24:31.775   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeebb364
,08-30 17:24:31.785   772   791 V WindowStateAnimator: Finishing drawing window Window{b210f3c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 17:24:31.785  3740  3740 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 17:24:31.785  3740  3740 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-30 17:24:31.795   772   904 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 17:24:31.795   772   904 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +427ms (total +442ms)
08-30 17:24:31.795   772  1217 V WindowStateAnimator: Finishing drawing window Window{6656f0e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-30 17:24:31.795   772  1703 V WindowStateAnimator: Finishing drawing window Window{b210f3c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 17:24:31.795   772   772 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 17:24:31.795  3740  3740 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4c4fa48 time:108673
,08-30 17:24:31.795   772   904 D ActivityManager: mDVFSHelper.release()
08-30 17:24:31.795   772   904 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9cecb0c u0 com.samsung.android.MtpApplication/.USBConnection t168} time:108674
,08-30 17:24:31.795   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeebb364
,08-30 17:24:31.795   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeebb364
,08-30 17:24:31.805   772   772 I KnoxTimeoutHandler: SD activityfalse
,08-30 17:24:31.845  6699  6699 E Zygote  : v2
08-30 17:24:31.845  6699  6699 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:24:31.845  6699  6699 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:31.845   772  2578 I ActivityManager: Start proc 6699:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-30 17:24:31.845   772  1319 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 17:24:31.845  6699  6699 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:31.845  6699  6699 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:31.845  6699  6699 E Zygote  : accessInfo : 0
08-30 17:24:31.845  6699  6699 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-30 17:24:31.845  6626  6659 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 17:24:31.865  6699  6699 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:31.875  6699  6699 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:31.875   772  1319 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 17:24:31.885  6699  6699 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-30 17:24:31.915  6626  6659 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-30 17:24:31.935  6699  6699 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-30 17:24:31.935  6626  6659 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-30 17:24:31.935  6626  6659 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-30 17:24:31.945  6626  6659 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 17:24:31.975  6626  6659 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:24:32.065  6671  6671 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-30 17:24:32.065  6671  6671 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-30 17:24:32.065  6671  6671 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-30 17:24:32.085  6671  6671 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 30 17:24:32 GMT+02:00 2016
,08-30 17:24:32.095  6671  6671 D DialogFlow: initQueue()
,08-30 17:24:32.095  6714  6714 E Zygote  : v2
08-30 17:24:32.095  6714  6714 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:24:32.095  6714  6714 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:32.095   772  1604 I ActivityManager: Start proc 6714:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-30 17:24:32.105  6714  6714 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:32.105  6714  6714 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:32.105  6714  6714 E Zygote  : accessInfo : 0
08-30 17:24:32.105   772  1604 I ActivityManager: Killing 5731:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
08-30 17:24:32.105  6699  6699 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
08-30 17:24:32.105   772  1604 I ActivityManager: Killing 5505:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-30 17:24:32.125   772   792 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
08-30 17:24:32.125  6714  6714 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:32.125  6714  6714 D ActivityThread: Added TimaKeyStore provider
08-30 17:24:32.135  6544  6664 W jxcore-log: Initializing JXcore engine
08-30 17:24:32.135  6544  6664 W jxcore-log: JXcore engine is ready
08-30 17:24:32.135   772   791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc09935 6714:com.samsung.android.app.filterinstaller/1000}
08-30 17:24:32.135  6699  6699 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-30 17:24:32.145   772  1709 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-30 17:24:32.155  6714  6714 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-30 17:24:32.165  6714  6714 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-30 17:24:32.175  6714  6714 E FilterPackageIntentReceiver: This package is not a effect filter
,08-30 17:24:32.185  2511  2511 E audit   : type=1400 msg=audit(1472570672.185:287): avc:  denied  { ioctl } for  pid=6664 comm="Thread-922" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:24:32.185  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:32.185  2511  2511 E audit   : type=1300 msg=audit(1472570672.185:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=999ff3c8 items=0 ppid=350 ppcomm=main pid=6664 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-922" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 17:24:32.185  2511  2511 E audit   : type=1327 msg=audit(1472570672.185:287): proctitle="com.test.thalitest"
08-30 17:24:32.185  2511  2511 E audit   : type=1320 msg=audit(1472570672.185:287): 
08-30 17:24:32.185  2511  2511 E audit   : type=1400 msg=audit(1472570672.185:288): avc:  denied  { ioctl } for  pid=6664 comm="Thread-922" path="socket:[40135]" dev="sockfs" ino=40135 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 17:24:32.185  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:32.185  2511  2511 E audit   : type=1300 msg=audit(1472570672.185:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=999ff3c8 items=0 ppid=350 ppcomm=main pid=6664 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-922" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 17:24:32.185  2511  2511 E audit   : type=1327 msg=audit(1472570672.185:288): proctitle="com.test.thalitest"
08-30 17:24:32.185  2511  2511 E audit   : type=1320 msg=audit(1472570672.185:288): 
,08-30 17:24:32.195  6731  6731 E Zygote  : v2
08-30 17:24:32.195   772  1418 I ActivityManager: Start proc 6731:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-30 17:24:32.195  6731  6731 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:24:32.195  6731  6731 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:32.195  6731  6731 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:32.195  6731  6731 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:32.195  6731  6731 E Zygote  : accessInfo : 0
08-30 17:24:32.195   772  1418 I ActivityManager: Killing 5743:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-30 17:24:32.195  6544  6664 W jxcore-log: Starting JXcore engine
,08-30 17:24:32.215   772  2578 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-30 17:24:32.225  6731  6731 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:24:32.225  6731  6731 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:32.235   772  1709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ad91ca 6731:com.samsung.helphub/1000}
,08-30 17:24:32.245   772  1709 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-30 17:24:32.245  6731  6731 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-30 17:24:32.255  6731  6731 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-30 17:24:32.275  6699  6699 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-30 17:24:32.275  6699  6699 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-30 17:24:32.285  6699  6699 D DialogFlow: initQueue()
,08-30 17:24:32.295  6544  6664 W jxcore-log: Platform android
08-30 17:24:32.295  6544  6664 W jxcore-log: 
08-30 17:24:32.295  6544  6664 W jxcore-log: Process ARCH arm
08-30 17:24:32.295  6544  6664 W jxcore-log: 
,08-30 17:24:32.305  6743  6743 E Zygote  : v2
08-30 17:24:32.305  6743  6743 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:24:32.305  6743  6743 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:32.305  6743  6743 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:32.305  6743  6743 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:32.305   772  1802 I ActivityManager: Start proc 6743:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-30 17:24:32.305  6743  6743 E Zygote  : accessInfo : 0
,08-30 17:24:32.315   772  1802 I ActivityManager: Killing 5833:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-30 17:24:32.325   772  1703 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-30 17:24:32.335  6743  6743 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:32.335  6743  6743 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:32.345   772  1604 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{827b9ed 6743:com.samsung.android.app.mirrorlink/1000}
,08-30 17:24:32.345  6743  6743 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-30 17:24:32.365  6743  6743 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-30 17:24:32.375   772  3483 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-30 17:24:32.395  6743  6743 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-30 17:24:32.395  6743  6743 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-30 17:24:32.395   772  1418 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fd4824 5756:com.google.android.apps.plus/u0a134}
,08-30 17:24:32.415   772  1604 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fd4824 5756:com.google.android.apps.plus/u0a134}
,08-30 17:24:32.425   772  2564 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fd4824 5756:com.google.android.apps.plus/u0a134}
,08-30 17:24:32.445  6524  6524 I Mms/MmsApp:  start initViewCache mms
,08-30 17:24:32.465   772   792 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-30 17:24:32.465   772  2578 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-30 17:24:32.475   772  1703 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-30 17:24:32.475   772  1418 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-30 17:24:32.475   772  2564 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-30 17:24:32.485   772  1217 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-30 17:24:32.485   772   791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-30 17:24:32.495   772  2575 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-30 17:24:32.515  6758  6758 E Zygote  : v2
08-30 17:24:32.515  6758  6758 I libpersona: KNOX_SDCARD checking this for 10165
08-30 17:24:32.515  6758  6758 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:32.515  6758  6758 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:32.515  6758  6758 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:32.515  6758  6758 E Zygote  : accessInfo : 0
,08-30 17:24:32.515  6758  6758 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-30 17:24:32.525   772  1418 I ActivityManager: Start proc 6758:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-30 17:24:32.525  6544  6664 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:24:32.525  6544  6664 I jxcore-log: 
,08-30 17:24:32.535  6544  6664 W jxcore-log: JXcore engine is started
,08-30 17:24:32.535  6544  6655 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:24:32.535  6544  6544 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:24:32.545  6758  6758 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:32.545  6758  6758 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:32.555   772  1234 V AlarmManager: Expired Alarm result :4
,08-30 17:24:32.565   772   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8798c6e 6758:com.sec.kidsplat.installer/u0a165}
,08-30 17:24:32.565   772  1802 I ActivityManager: Killing 4767:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-30 17:24:32.565  1448  1448 D Recents : onTaskStackChanged
,08-30 17:24:32.575  6758  6758 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-30 17:24:32.575  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 17:24:32.585   772  1418 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-30 17:24:32.595  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 17:24:32.595  6758  6758 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-30 17:24:32.605   772  2527 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8798c6e 6758:com.sec.kidsplat.installer/u0a165}
,08-30 17:24:32.605  6758  6758 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-30 17:24:32.625   772  2575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:24:32.625   772  2575 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-30 17:24:32.625   772  2575 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-30 17:24:32.625   772  2575 D BatteryService: stay LED for charging
08-30 17:24:32.625   772   772 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:24:32.635   772  1217 I ActivityManager: Start proc 6771:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-30 17:24:32.635  6771  6771 E Zygote  : v2
08-30 17:24:32.635  6771  6771 I libpersona: KNOX_SDCARD checking this for 10142
08-30 17:24:32.635  6771  6771 I libpersona: KNOX_SDCARD not a persona
08-30 17:24:32.635  6771  6771 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-30 17:24:32.635   772  1217 I ActivityManager: Killing 5567:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-30 17:24:32.635  6771  6771 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:32.635  6771  6771 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:32.635  6771  6771 E Zygote  : accessInfo : 64
08-30 17:24:32.635  6771  6771 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 17:24:32.635  6771  6771 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-30 17:24:32.635  6771  6771 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-30 17:24:32.645   772   772 I MotionRecognitionService: Plugged
08-30 17:24:32.645   772   772 D MotionRecognitionService:   cableConnection= 1
08-30 17:24:32.645   772   772 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 17:24:32.645   772   772 D MotionRecognitionService: skip setTransmitPower. 
,08-30 17:24:32.645  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:24:32.645  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:24:32.645  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:24:32.645  2506  2506 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:24:32.645  2506  2919 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 17:24:32.665  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 17:24:32.665  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 17:24:32.665  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 17:24:32.665  6771  6771 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:32.665  6771  6771 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:32.675   772   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f9e7f0f 6771:com.sec.android.app.sbrowser/u0a142}
,08-30 17:24:32.685  6771  6771 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 17:24:32.685   772  1718 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-30 17:24:32.705  6771  6771 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-30 17:24:32.715  6771  6771 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 17:24:32.715  6771  6771 D ManifestProvider: onCreate()
,08-30 17:24:32.725  6771  6771 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-30 17:24:32.725  6771  6771 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 17:24:32.725  6771  6771 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 17:24:32.725  6771  6771 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-30 17:24:32.735  6771  6771 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-30 17:24:32.735  6771  6771 D [MM]MHDataBaseProvider: onCreate()
,08-30 17:24:32.755  6771  6771 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@c036e37)
,08-30 17:24:32.785   772  3482 D SSRM:n  : SIOP:: AP = 470, PST = 469, CUR = 300, LCD = 0
,08-30 17:24:32.795   772  3482 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 17:24:32.835  6524  6524 D Mms/BubbleViewCache: fillCache bubble = 4
,08-30 17:24:32.835   772  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-30 17:24:32.845   772  1418 I ActivityManager: Killing 5399:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-30 17:24:32.855   772  1418 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91f9771 2049:com.google.android.gms.persistent/u0a11}
,08-30 17:24:32.865  4255  6788 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-30 17:24:32.865   772  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5c7155d 4255:com.google.android.gms/u0a11}
,08-30 17:24:32.865  4255  6787 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-30 17:24:32.875   772  2578 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-30 17:24:32.875  4255  6788 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 17:24:32.885  4255  4255 D AsyncTaskServiceImpl: Submit a task: nzm
,08-30 17:24:32.895  4255  6788 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 17:24:32.905  4255  6788 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 17:24:32.905   772  1418 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91f9771 2049:com.google.android.gms.persistent/u0a11}
,08-30 17:24:32.915   772   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5c7155d 4255:com.google.android.gms/u0a11}
,08-30 17:24:32.925  4255  5056 D nzm     : Processing package: com.test.thalitest
,08-30 17:24:32.955  4255  4255 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 17:24:33.005  4255  5056 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-30 17:24:33.005  4255  5056 D nzm     : Found info for package com.test.thalitest in db.
,08-30 17:24:33.065   772  1217 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c627eb6 6185:com.sec.android.app.samsungapps/u0a39}
,08-30 17:24:33.085   772  2527 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62a6f10 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{15dc138 5780:com.android.vending/u0a29}
,08-30 17:24:33.145  5780  5780 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-30 17:24:33.145  6794  6794 E Zygote  : v2
08-30 17:24:33.145  6794  6794 I libpersona: KNOX_SDCARD checking this for 10034
08-30 17:24:33.145  6794  6794 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:33.145  6794  6794 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 17:24:33.145  6794  6794 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:33.145   772   792 I ActivityManager: Start proc 6794:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-30 17:24:33.145  6794  6794 E Zygote  : accessInfo : 0
,08-30 17:24:33.145  6794  6794 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-30 17:24:33.165  5780  5780 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,08-30 17:24:33.165  2049  2049 D WearableService: callingUid 10011, callindPid: 2049
,08-30 17:24:33.185  6794  6794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:33.185  6794  6794 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:33.185  5780  5780 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-30 17:24:33.185  5780  5780 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-30 17:24:33.195   772  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb6d615 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{251bd2a 6794:com.sec.android.app.shealth/u0a34}
,08-30 17:24:33.215  6794  6794 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-30 17:24:33.215  6699  6728 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 17:24:33.215  6699  6728 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 17:24:33.225  6794  6794 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-30 17:24:33.235  6794  6794 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:24:33.235  6794  6794 I MultiDex: install
08-30 17:24:33.235  6794  6794 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 17:24:33.235  6794  6794 I MultiDex: install
08-30 17:24:33.235  6794  6794 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:24:33.255  6699  6728 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 17:24:33.255  6699  6728 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-30 17:24:33.255  6699  6728 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-30 17:24:33.275  6699  6728 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 17:24:33.275  6699  6728 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 17:24:33.305   772  1604 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb6d615 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3eb077a 1986:com.sec.android.app.shealth:remote/u0a34}
,08-30 17:24:33.305   772  1802 I ActivityManager: Killing 5896:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-30 17:24:33.315  6794  6794 D HealthDataStore: Service for HealthDataStore is connected
,08-30 17:24:33.355  6794  6794 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-30 17:24:33.355   772  1217 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb6d615 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3eb077a 1986:com.sec.android.app.shealth:remote/u0a34}
,08-30 17:24:33.365  6794  6794 D HealthConsole: Service for HealthDataConsole is connected
,08-30 17:24:33.365   772  1418 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-30 17:24:33.375   772  1604 V AlarmManager:  remove PendingIntent] PendingIntent{24cb2cd: PendingIntentRecord{9db8940 com.google.android.gms broadcastIntent}}
,08-30 17:24:33.375  6794  6794 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-30 17:24:33.385   772  2575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0c782 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91f9771 2049:com.google.android.gms.persistent/u0a11}
08-30 17:24:33.385  6794  6794 E HealthDataStore: disconnectService: Context instance is invalid
,08-30 17:24:33.395   772  1319 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 17:24:33.395   772  1319 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 17:24:34.155  4255  5050 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-30 17:24:34.265  4255  5050 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 17:24:34.285  4255  5050 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 17:24:34.295  4255  5050 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-30 17:24:34.595   772  3521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:24:37.395   772  3482 D M       : limitCPUFreq:: freq = 1728000
08-30 17:24:37.395   772  3482 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 772  pkgName : SIOP_ARM_MAX@25
,08-30 17:24:37.395   772  3482 D M       : limitGPUFreq:: freq = 389000000
,08-30 17:24:37.405   772  3482 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 17:24:39.195   772   945 D PackageManager: [MSG] MCS_UNBIND
,08-30 17:24:39.215   772  1709 I ActivityManager: Killing 5417:com.policydm/1000 (adj 15): DHA:empty #37
,08-30 17:24:39.275   772  1418 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-30 17:24:39.275  6499  6499 D AASAservice: onDestroy()
,08-30 17:24:39.285  6499  6499 I art     : System.exit called, status: 80
08-30 17:24:39.285  6499  6499 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-30 17:24:39.305   772  2575 I ActivityManager: Process com.samsung.aasaservice (pid 6499)(adj 0) has died(72,735)
,08-30 17:24:39.305   772  2575 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-30 17:24:39.335   350   350 I Zygote  : Process 6499 exited cleanly (80)
,08-30 17:24:39.795   772   945 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 17:24:39.815   772   945 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 17:24:42.845   772  3482 D SSRM:n  : SIOP:: AP = 460, PST = 467, CUR = 300, LCD = 0
,08-30 17:24:42.865   772  3482 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 17:24:43.395   772  1319 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 17:24:43.405   772  1319 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 17:24:43.885   772   872 I ActivityManager: Waited long enough for: ServiceRecord{cc30ba7 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-30 17:24:44.085   772  1554 E Watchdog: !@Sync 3 [08-30 17:24:44.094]
,08-30 17:24:48.485   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-30 17:24:48.485   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-30 17:24:48.485   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-30 17:24:50.305  6544  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:24:50.305  6544  6664 I jxcore-log: 
,08-30 17:24:50.305  6544  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:24:50.305  6544  6664 I jxcore-log: 
,08-30 17:24:50.325  6544  6664 D BluetoothAdapter: STATE_ON
,08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:24:50.325  6544  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:24:50.325  6544  6664 D BluetoothAdapter: STATE_ON
,08-30 17:24:50.325  6544  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:24:50.325  6544  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:24:50.325  6544  6664 I jxcore-log: 
,08-30 17:24:50.335  6544  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:24:50.335  6544  6664 I jxcore-log: 
,08-30 17:24:50.395   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-30 17:24:50.395   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-30 17:24:50.395   309  1179 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-30 17:24:50.485   772  1234 V AlarmManager: Expired Alarm result :4
,08-30 17:24:50.535  5780  5820 I Finsky  : [824] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,08-30 17:24:50.555   772   872 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8eef7e8 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91f9771 2049:com.google.android.gms.persistent/u0a11}
,08-30 17:24:50.555   772   792 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:24:50.565   772   792 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4341, temperature: 330, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-30 17:24:50.565   772   792 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-30 17:24:50.565   772   792 D BatteryService: stay LED for charging
,08-30 17:24:50.565   772   772 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:24:50.565   772  1217 V AlarmManager:  remove PendingIntent] PendingIntent{2b86e01: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:50.575   772   772 I MotionRecognitionService: Plugged
,08-30 17:24:50.575   772   772 D MotionRecognitionService:   cableConnection= 1
08-30 17:24:50.575   772   772 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 17:24:50.575   772   772 D MotionRecognitionService: skip setTransmitPower. 
,08-30 17:24:50.575  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:24:50.575  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:24:50.575  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:24:50.595  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 17:24:50.595  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 17:24:50.605  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 17:24:50.605  2506  2506 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:24:50.605  2506  2919 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 17:24:50.705   772  2527 V AlarmManager:  remove PendingIntent] PendingIntent{24fcee7: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:50.805  4255  6860 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 17:24:50.805  4255  6860 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 17:24:50.835  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:50.845   772  1802 V AlarmManager:  remove PendingIntent] PendingIntent{d24527e: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:50.865  6544  6664 I jxcore-log: Running unit tests
08-30 17:24:50.865  6544  6664 I jxcore-log: 
,08-30 17:24:50.865  6544  6664 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 17:24:50.865  6544  6664 I jxcore-log: Failed to execute UT.
08-30 17:24:50.865  6544  6664 I jxcore-log: 
,08-30 17:24:50.865  6544  6664 I jxcore-log: Unit Test app is loaded
08-30 17:24:50.865  6544  6664 I jxcore-log: 
,08-30 17:24:50.865   772   872 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{50db3df u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91f9771 2049:com.google.android.gms.persistent/u0a11}
,08-30 17:24:50.875  6544  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:24:50.875  6544  6664 I jxcore-log: 
,08-30 17:24:50.875  6544  6544 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 17:24:50.875  6544  6664 I jxcore-log: My device name is: samsung-SM-G900F
08-30 17:24:50.875  6544  6664 I jxcore-log: 
,08-30 17:24:50.905   772  1217 V AlarmManager:  remove PendingIntent] PendingIntent{11db82c: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:51.045   772  1802 V AlarmManager:  remove PendingIntent] PendingIntent{1c3aefb: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:51.065  5780  5820 I Finsky  : [824] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,08-30 17:24:51.065  5780  5780 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-30 17:24:51.175   772   785 I art     : Background partial concurrent mark sweep GC freed 43602(2MB) AllocSpace objects, 18(360KB) LOS objects, 27% free, 42MB/58MB, paused 2.081ms total 172.810ms
,08-30 17:24:51.215  6866  6866 E Zygote  : v2
08-30 17:24:51.215  6866  6866 I libpersona: KNOX_SDCARD checking this for 10011
08-30 17:24:51.215  6866  6866 I libpersona: KNOX_SDCARD not a persona
,08-30 17:24:51.215  6866  6866 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-30 17:24:51.215  6866  6866 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:51.225   772  2578 I ActivityManager: Start proc 6866:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-30 17:24:51.225  6866  6866 E Zygote  : accessInfo : 0
,08-30 17:24:51.225  6866  6866 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-30 17:24:51.255  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:24:51.255  6866  6866 D ActivityThread: Added TimaKeyStore provider
,08-30 17:24:51.275  6866  6866 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 17:24:51.305  6866  6866 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:24:51.305  6866  6866 I MultiDex: install
08-30 17:24:51.305  6866  6866 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:24:51.335  6866  6866 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-30 17:24:51.355  6866  6866 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-30 17:24:51.355  6866  6866 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-30 17:24:51.355  6866  6866 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 17:24:51.405  6866  6866 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:24:51.425  6866  6866 D ChimeraCfgMgr: Reading stored module config
,08-30 17:24:51.495  2049  2049 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=3ec84f89-d15d-4854-b00a-98490f6242a1
,08-30 17:24:51.545  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:51.545  2049  2049 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:24:51.545  6866  6881 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 17:24:51.555   328   923 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6866)
,08-30 17:24:51.605   328   923 D WVCdm   : Instantiating CDM.
,08-30 17:24:51.605   328   939 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6866)
08-30 17:24:51.605   328   939 I WVCdm   : CdmEngine::OpenSession
08-30 17:24:51.605   328   939 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-30 17:24:51.615   328   939 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 17:24:51.625   328   939 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-30 17:24:51.625   328   939 D DrmWidevineDash: Service_Initialize: starts!
08-30 17:24:51.625   328   939 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-30 17:24:51.625   328   939 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:24:51.625   328   939 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-30 17:24:51.625   328   939 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 17:24:51.625   328   939 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 17:24:51.625   328   939 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:24:51.625   328   939 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-30 17:24:51.625   328   939 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 17:24:51.625   328   939 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 17:24:51.625   328   939 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:24:51.655   328   939 D QSEECOMAPI: : Loaded image: APP id = 2
,08-30 17:24:51.655   328   939 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-30 17:24:51.655   328   939 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaf052000
08-30 17:24:51.655   328   939 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaf052000
,08-30 17:24:51.665   328   939 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-30 17:24:51.665   328   939 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-30 17:24:51.675   328   939 D DrmWidevineDash: hlos api version =  10
,08-30 17:24:51.675   328   939 D DrmWidevineDash: tz api version =  10
,08-30 17:24:51.675  6866  6877 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:51.675  6866  6877 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:51.675   309  1183 D EnterpriseController: netId is 0
08-30 17:24:51.675   309  1183 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:24:51.675   328   939 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-30 17:24:51.675   328   939 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-30 17:24:51.695   328   939 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf17a924
,08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1edd7c8, dataLength=8
,08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-30 17:24:51.695   328   939 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1e4d800, wrapped_rsa_key_length=1280
,08-30 17:24:51.705   328   939 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-30 17:24:51.705   328   939 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 17:24:51.705   328   923 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 17:24:51.705   328   923 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-30 17:24:51.705   328   923 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaec3d440, idLength=0xaf279f2c
,08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-30 17:24:51.705   328   923 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-30 17:24:51.715   328   923 D DrmWidevineDash: hlos api version =  10
08-30 17:24:51.715   328   923 D DrmWidevineDash: tz api version =  10
08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-30 17:24:51.715   328   923 D WVCdm   : PrepareKeyRequest: nonce=3116271202
08-30 17:24:51.715   328   923 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xae44e400
08-30 17:24:51.715   328   923 D DrmWidevineDash: message_length=1631, signature=0xae2b4c80, signature_length=2938609668
,08-30 17:24:51.725  6866  6877 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6866, getuid(): 10011
,08-30 17:24:51.815   328   923 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-30 17:24:51.825   328   328 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6866)
,08-30 17:24:51.825   328   328 I WVCdm   : CdmEngine::CloseSession
08-30 17:24:51.825   328   328 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-30 17:24:51.825   328   328 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-30 17:24:51.825   328   328 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-30 17:24:51.825   328   328 D DrmWidevineDash: Service_Uninitialize: starts!
,08-30 17:24:51.825   328   328 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-30 17:24:51.825   328   328 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,08-30 17:24:51.825   328   328 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-30 17:24:51.825   328   328 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-30 17:24:51.825  2049  2293 W GCoreFlp: No location to return for getLastLocation()
,08-30 17:24:51.905  4255  6861 D UdcContextInitService: registered all accounts: true
,08-30 17:24:51.905  2049  2333 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:24:51.915  2049  2374 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 17:24:51.925  6866  6877 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6866, getuid(): 10011
,08-30 17:24:52.035   772   792 V AlarmManager:  remove PendingIntent] PendingIntent{81543f2: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:52.095  6866  6877 I qtaguid : Untagging socket 21
,08-30 17:24:52.145  6866  6877 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-30 17:24:52.145  6866  6877 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 17:24:52.335  2049  6896 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:24:52.335  2049  6894 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:24:52.355  2049  6896 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:24:52.355  2049  6894 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:24:52.365  2049  6896 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:24:52.365  2049  6894 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:24:52.365  2049  6894 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 17:24:52.375  2049  6894 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 17:24:52.455   772  2578 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:52.475  2049  6894 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-30 17:24:52.525  6897  6897 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-30 17:24:52.545  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:52.545  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:52.545   309  1183 D EnterpriseController: netId is 0
08-30 17:24:52.545   309  1183 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:24:52.545  2049  6894 I qtaguid : Tagging socket 55 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:52.605  2049  6894 I qtaguid : Tagging socket 58 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:52.625  6897  6897 I dex2oat : ----------------------------------------------------
08-30 17:24:52.625  6897  6897 I dex2oat : <SS>: S T A R T I N G . . .
08-30 17:24:52.625  6897  6897 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-30 17:24:52.625  6897  6897 I dex2oat : dex2oat took 98.329ms (threads: 4) arena alloc=211KB java alloc=63KB native alloc=1796KB free=1787KB
,08-30 17:24:52.635  6866  6877 W System  : ClassLoader referenced unknown path: 
,08-30 17:24:52.635  6866  6877 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-30 17:24:52.645  6866  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 17:24:52.645  6866  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 17:24:52.645  6866  6877 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 17:24:52.645  6866  6877 I Adreno-EGL: Local Branch: ss
08-30 17:24:52.645  6866  6877 I Adreno-EGL: Remote Branch: 
08-30 17:24:52.645  6866  6877 I Adreno-EGL: Local Patches: 
08-30 17:24:52.645  6866  6877 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:24:52.645  6866  6877 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-30 17:24:52.725  6866  6877 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-30 17:24:52.845   772  1703 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:52.845  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:52.845  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:52.845  2049  6894 I qtaguid : Tagging socket 55 with tag 11065c9100000000{285629585,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:52.915   772  3482 D SSRM:n  : SIOP:: AP = 440, PST = 463, CUR = 300, LCD = 0
,08-30 17:24:52.955   772  1703 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:52.955  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:52.955  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:52.965  2049  6894 I qtaguid : Tagging socket 55 with tag 11065c0800000000{285629448,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:53.065   772   791 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:53.065  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.065  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:53.065  2049  6894 I qtaguid : Tagging socket 55 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:53.085  6866  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 17:24:53.085  6866  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 17:24:53.085  6866  6877 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 17:24:53.085  6866  6877 I Adreno-EGL: Local Branch: ss
08-30 17:24:53.085  6866  6877 I Adreno-EGL: Remote Branch: 
08-30 17:24:53.085  6866  6877 I Adreno-EGL: Local Patches: 
08-30 17:24:53.085  6866  6877 I Adreno-EGL: Reconstruct Branch: 
08-30 17:24:53.085  6866  6877 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-30 17:24:53.145  6866  6877 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-30 17:24:53.145  6866  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 17:24:53.145  6866  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 17:24:53.145  6866  6877 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 17:24:53.145  6866  6877 I Adreno-EGL: Local Branch: ss
08-30 17:24:53.145  6866  6877 I Adreno-EGL: Remote Branch: 
08-30 17:24:53.145  6866  6877 I Adreno-EGL: Local Patches: 
08-30 17:24:53.145  6866  6877 I Adreno-EGL: Reconstruct Branch: 
08-30 17:24:53.145  6866  6877 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-30 17:24:53.165   772  1604 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:53.175  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.175  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.175  2049  6894 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:53.195  6866  6877 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-30 17:24:53.285   772  2578 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:53.295  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.295  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:53.295  2049  6894 I qtaguid : Tagging socket 55 with tag 11065b5800000000{285629272,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:53.395  2049  6864 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.395  2049  6864 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.395   309  1183 D EnterpriseController: netId is 0
08-30 17:24:53.395   309  1183 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:24:53.415  2049  6864 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} uid 10011, pid: 2049, getuid(): 10011
,08-30 17:24:53.415   772  1703 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:24:53.435  2049  6864 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} uid 10011, pid: 2049, getuid(): 10011
,08-30 17:24:53.445  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.445  2049  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:53.445  2049  6894 I qtaguid : Tagging socket 55 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2049, getuid(): 10011
,08-30 17:24:53.595   772  1802 V AlarmManager:  remove PendingIntent] PendingIntent{c9cdf31: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:53.595  2049  2374 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 17:24:53.595  2049  2374 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 17:24:53.605  2049  2374 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 17:24:51.992+0200, stopTime=2016-08-30 17:24:53.611+0200, duration=1619ms
,08-30 17:24:53.625  2049  6916 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:53.625  2049  6916 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:53.625   309  1183 D EnterpriseController: netId is 0
08-30 17:24:53.625   309  1183 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:24:53.625  2049  6916 I qtaguid : Tagging socket 53 with tag 1000310500000000{268448005,0} uid 10011, pid: 2049, getuid(): 10011
,08-30 17:24:53.665   772  2578 V AlarmManager:  remove PendingIntent] PendingIntent{d791b97: PendingIntentRecord{52e96cd com.google.android.gms broadcastIntent}}
,08-30 17:24:53.685  2049  6916 I qtaguid : Tagging socket 46 with tag 1000310500000000{268448005,0} uid 10011, pid: 2049, getuid(): 10011
,08-30 17:24:53.895  2049  6916 I qtaguid : Untagging socket 53
,08-30 17:24:53.905  2049  2374 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 17:24:54.415  6544  6664 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 17:24:54.415  6544  6664 I jxcore-log: 
,08-30 17:24:54.595   772  3521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:24:55.025  6544  6664 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 17:24:55.025  6544  6664 I jxcore-log: 
,08-30 17:24:55.055  6544  6664 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 17:24:55.055  6544  6664 I jxcore-log: 
,08-30 17:24:55.715  2049  6915 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:24:55.715  2049  6915 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:24:55.715  2049  6915 I qtaguid : Tagging socket 53 with tag 1000310200000000{268448002,0} uid 10011, pid: 2049, getuid(): 10011
,08-30 17:24:55.935  2049  6915 I qtaguid : Untagging socket 53
,08-30 17:24:55.945  2049  2374 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 17:24:56.905  6544  6664 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 17:24:56.905  6544  6664 I jxcore-log: 
,08-30 17:24:57.215  6544  6664 I jxcore-log: ERROR runTests: 
08-30 17:24:57.215  6544  6664 I jxcore-log: 
,08-30 17:24:57.225  6544  6664 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:24:57.225  6544  6664 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 17:24:57.245  6544  6664 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _functionName: 'loadFile',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _lineNumber: '26',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _columnNumber: '11',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 17:24:57.245  6544  6664 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _functionName: '',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _lineNumber: '38',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _columnNumber: '7',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 17:24:57.245  6544  6664 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _functionName: '',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _lineNumber: '35',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _columnNumber: '3',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 17:24:57.245  6544  6664 I jxcore-log:   { _fileName: 'module.js',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _lineNumber: '621',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _columnNumber: '8',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 17:24:57.245  6544  6664 I jxcore-log:   { _fileName: 'module.js',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _lineNumber: '651',
08-30 17:24:57.245  6544  6664 I jxcore-log:     _columnNumber: '1',
08-30 17:24:57.245  6544  6664 I jxcore-log:    
,08-30 17:24:57.245  6544  6664 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 17:24:57.245  6544  6664 I jxcore-log: 
08-30 17:24:57.245  6544  6664 E jxcore-log: Error: 
08-30 17:24:57.245  6544  6664 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:24:57.245  6544  6664 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 17:24:57.245  6544  6664 E jxcore-log: 
,08-30 17:24:58.385   772   792 I ActivityManager: Killing 5920:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-30 17:24:58.425   772  1718 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-30 17:24:58.425  2511  2511 E audit   : type=1400 msg=audit(1472570698.425:289): avc:  denied  { execmod } for  pid=6930 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-30 17:24:58.435  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 17:24:58.435  2511  2511 E audit   : type=1300 msg=audit(1472570698.425:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc9000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6930 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 17:24:58.435  2511  2511 E audit   : type=1327 msg=audit(1472570698.425:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-30 17:24:58.435  2511  2511 E audit   : type=1320 msg=audit(1472570698.425:289): 
,08-30 17:24:58.495  2511  2511 E audit   : type=1400 msg=audit(1472570698.495:290): avc:  denied  { execmod } for  pid=6930 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 17:24:58.495  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:58.505  2511  2511 E audit   : type=1300 msg=audit(1472570698.495:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f89000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6930 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 17:24:58.505  2511  2511 E audit   : type=1327 msg=audit(1472570698.495:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-30 17:24:58.505  2511  2511 E audit   : type=1320 msg=audit(1472570698.495:290): 
,08-30 17:24:58.555  2511  2511 E audit   : type=1400 msg=audit(1472570698.555:291): avc:  denied  { execmod } for  pid=6930 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-30 17:24:58.555  6930  6930 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 17:24:58.555  2511  2511 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-30 17:24:58.555  2511  2511 E audit   : type=1300 msg=audit(1472570698.555:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f89000 a1=51000 a2=5 a3=4 items=0 ppid=3621 ppcomm=adbd pid=6930 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-30 17:24:58.555  2511  2511 E audit   : type=1327 msg=audit(1472570698.555:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-30 17:24:58.565  2511  2511 E audit   : type=1320 msg=audit(1472570698.555:291): 
,08-30 17:24:58.565  6930  6930 D AndroidRuntime: CheckJNI is OFF
,08-30 17:24:58.565  6930  6930 D AndroidRuntime: readGMSProperty: start
08-30 17:24:58.565  6930  6930 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:24:58.565  6930  6930 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:24:58.565  6930  6930 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:24:58.565  6930  6930 D AndroidRuntime: readGMSProperty: end
08-30 17:24:58.565  6930  6930 D AndroidRuntime: addProductProperty: start
,08-30 17:24:58.575  6930  6930 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 17:24:58.575  6930  6930 W art     : af125000-b204b000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
,08-30 17:24:58.575  6930  6930 W art     : b204b000-b42ba000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 17:24:58.575  6930  6930 W art     : b42ba000-b42bb000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-30 17:24:58.575  6930  6930 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 17:24:58.575  6930  6930 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-30 17:24:58.575  6930  6930 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b4733000-b473d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-30 17:24:58.575  6930  6930 W art     : b473d000-b473e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-30 17:24:58.575  6930  6930 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-30 17:24:58.575  6930  6930 W art     : b4858000-b485b000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:58.575  6930  6930 W art     : b485b000-b485c000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:58.575  6930  6930 W art     : b485c000-b485d000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-30 17:24:58.575  6930  6930 W art     : b485d000-b485e000 r--p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b485e000-b487e000 r--s 00000000 00:0b 9236       /dev/__properties__
08-30 17:24:58.575  6930  6930 W art     : b487e000-b528f000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:58.575  6930  6930 W art     : b528f000-b5290000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5290000-b52d9000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:58.575  6930  6930 W art     : b52d9000-b52da000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-30 17:24:58.575  6930  6930 W art     : b52da000-b52e2000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b52e2000-b5317000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:58.575  6930  6930 W art     : b5317000-b5318000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5318000-b5319000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:58.575  6930  6930 W art     : b5319000-b531a000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-30 17:24:58.575  6930  6930 W art     : b531a000-b5372000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:58.575  6930  6930 W art     : b5372000-b5373000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5373000-b5374000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:58.575  6930  6930 W art     : b5374000-b5375000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-30 17:24:58.575  6930  6930 W art     : b5376000-b537c000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:58.575  6930  6930 W art     : b537c000-b537d000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:58.575  6930  6930 W art     : b537d000-b537e000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 17:24:58.575  6930  6930 W art     : b537e000-b5380000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5381000-b538b000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:58.575  6930  6930 W art     : b538b000-b538e000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:58.575  6930  6930 W art     : b538e000-b538f000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 17:24:58.575  6930  6930 W art     : b5390000-b53a7000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:58.575  6930  6930 W art     : b53a7000-b53a8000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b53a8000-b53,a9000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:58.575  6930  6930 W art     : b53a9000-b53aa000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 17:24:58.575  6930  6930 W art     : b53ab000-b53b5000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:58.575  6930  6930 W art     : b53b5000-b53b6000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:58.575  6930  6930 W art     : b53b6000-b53b7000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-30 17:24:58.575  6930  6930 W art     : b53b7000-b53bb000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:58.575  6930  6930 W art     : b53bb000-b53bc000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:58.575  6930  6930 W art     : b53bc000-b53bd000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 17:24:58.575  6930  6930 W art     : b53bd000-b53d3000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:58.575  6930  6930 W art     : b53d3000-b53d4000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:58.575  6930  6930 W art     : b53d4000-b53d5000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-30 17:24:58.575  6930  6930 W art     : b53d5000-b53e2000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:58.575  6930  6930 W art     : b53e2000-b53e3000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:58.575  6930  6930 W art     : b53e3000-b53e4000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-30 17:24:58.575  6930  6930 W art     : b53e4000-b5444000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-30 17:24:58.575  6930  6930 W art     : b5444000-b5447000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-30 17:24:58.575  6930  6930 W art     : b5447000-b544b000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b544b000-b54ac000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-30 17:24:58.575  6930  6930 W art     : b54ac000-b54ad000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 17:24:58.575  6930  6930 W art     : b54ad000-b54fc000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:58.575  6930  6930 W art     : b54fc000-b54fe000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:58.575  6930  6930 W art     : b54fe000-b54ff000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-30 17:24:58.575  6930  6930 W art     : b54ff000-b5500000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5500000-b5507000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 17:24:58.575  6930  6930 W art     : b5507000-b5508000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 17:24:58.575  6930  6930 W art     : b5508000-b5509000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-30 17:24:58.575  6930  6930 W art     : avc_common.so
08-30 17:24:58.575  6930  6930 W art     : b550a000-b550d000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 17:24:58.575  6930  6930 W art     : b550d000-b550e000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 17:24:58.575  6930  6930 W art     : b550e000-b550f000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-30 17:24:58.575  6930  6930 W art     : enc_common.so
08-30 17:24:58.575  6930  6930 W art     : b5510000-b5514000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-30 17:24:58.575  6930  6930 W art     : b5514000-b5515000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5515000-b5516000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-30 17:24:58.575  6930  6930 W art     : b5516000-b5517000 rw-p 00005000 b3:17 2510       /syste
08-30 17:24:58.575  6930  6930 W art     : m/lib/libpowermanager.so
08-30 17:24:58.575  6930  6930 W art     : b5518000-b5535000 r-xp 00000000 b3:17, 2795       /system/lib/libvorbisidec.so
08-30 17:24:58.575  6930  6930 W art     : b5535000-b5536000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 17:24:58.575  6930  6930 W art     : b5536000-b5537000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 17:24:58.575  6930  6930 W art     : b5538000-b553d000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:58.575  6930  6930 W art     : b553d000-b553e000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:58.575  6930  6930 W art     : b553e000-b553f000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 17:24:58.575  6930  6930 W art     : b5540000-b5571000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:58.575  6930  6930 W art     : b5571000-b5572000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5572000-b5575000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:58.575  6930  6930 W art     : b5575000-b5576000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 17:24:58.575  6930  6930 W art     : b5577000-b55b2000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-30 17:24:58.575  6930  6930 W art     : b55b2000-b55b3000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-30 17:24:58.575  6930  6930 W art     : b55b3000-b55b4000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-30 17:24:58.575  6930  6930 W art     : b55b5000-b55bc000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:58.575  6930  6930 W art     : b55bc000-b55bd000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b55bd000-b55be000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:58.575  6930  6930 W art     : b55be000-b55bf000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-30 17:24:58.575  6930  6930 W art     : b55bf000-b55c0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b55c0000-b55d7000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:58.575  6930  6930 W art     : b55d7000-b55d8000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b55d8000-b55db000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:58.575  6930  6930 W art     : b55db000-b55dc000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-30 17:24:58.575  6930  6930 W art     : b55dc000-b55fb000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:58.575  6930  6930 W art     : b55fb000-b55fc000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:58.575  6930  6930 W art     : b55fc000-b55fd000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-30 17:24:58.575  6930  6930 W art     : b55fd000-b563b000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:58.575  6930  6930 W art     : b563b000-b563c000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b563c000-b563e000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:58.575  6930  6930 W art     : b563e000-b563f000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-30 17:24:58.575  6930  6930 W art     : b5640000-b5647000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:58.575  6930  6930 W art     : b5647000-b5648000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:58.575  6930  6930 W art     : b5648000-b5649000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 17:24:58.575  6930  6930 W art     : b564a000-b564d000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:58.575  6930  6930 W art     : b564d000-b564e000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:58.575  6930  6930 W art     : b564e000-b564f000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 17:24:58.575  6930  6930 W art     : b564f000-b5655000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:58.575  6930  6930 W art     : b5655000-b5656000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5656000-b5657000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:58.575  6930  6930 W art     : b5657000-b5658000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 17:24:58.575  6930  6930 W art     : b5658000-b5661000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:58.575  6930  6930 W art     : b5661000-b5662000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:58.575  6930  6930 W art     : b5662000-b5663000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 17:24:58.575  6930  6930 W art     : b5663000-b56f4000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:58.575  6930  6930 W art     : b56f4000-b56f5000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b56f5000-b5700000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:58.575  6930  6930 W art     : b5700000-b5701000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 17:24:58.575  6930  6930 W art     : b5702000-b5714000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:58.575  6930  6930 W art     : b5714000-b5715000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:58.575  6930  6930 W art     : b5715000-b5716000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 17:24:58.575  6930  6930 W art     : b5717000-b571c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:58.575  6930  6930 W art     : b571c000-b571d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:58.575  6930  6930 W art     : b571d000-b571e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 17:24:58.575  6930  6930 W art     : b571f000-b578c000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:58.575  6930  6930 W art     : b578c000-b578d000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b578d000-b578f000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:58.575  6930  6930 W art     : b578f000-b5790000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 17:24:58.575  6930  6930 W art     : b5790000-b5791000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5791000-b5798000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:58.575  6930  6930 W art     : b5798000-b5799000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:58.575  6930  6930 W art     : b5799000-b579a000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 17:24:58.575  6930  6930 W art     : b579b000-b581b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:58.575  6930  6930 W art     : b581b000-b581c000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b581c000-b581d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:58.575  6930  6930 W art     : b581d000-b581e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 17:24:58.575  6930  6930 W art     : b581e000-b5835000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5835000-b586c000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:58.575  6930  6930 W art     : b586c000-b586d000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:58.575  6930  6930 W art     : b586d000-b586e000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 17:24:58.575  6930  6930 W art     : b586e000-b588a000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:58.575  6930  6930 W art     : b588a000-b588b000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:58.575  6930  6930 W art     : b588b000-b588c000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 17:24:58.575  6930  6930 W art     : b588d000-b58ee000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:58.575  6930  6930 W art     : b58ee000-b58f0000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:58.575  6930  6930 W art     : b58f0000-b58f1000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 17:24:58.575  6930  6930 W art     : b58f2000-b5917000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 17:24:58.575  6930  6930 W art     : b5917000-b5918000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 17:24:58.575  6930  6930 W art     : b5918000-b5919000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 17:24:58.575  6930  6930 W art     : b591a000-b5922000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:58.575  6930  6930 W art     : b5922000-b5924000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:58.575  6930  6930 W art     : b5924000-b5925000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 17:24:58.575  6930  6930 W art     : b5926000-b5929000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:58.575  6930  6930 W art     : b5929000-b592a000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:58.575  6930  6930 W art     : b592a000-b592b000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-30 17:24:58.575  6930  6930 W art     : b592b000-b592f000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:58.575  6930  6930 W art     : b592f000-b5930000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5930000-b5931000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:58.575  6930  6930 W art     : b5931000-b5932000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 17:24:58.575  6930  6930 W art     : b5932000-b5942000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:58.575  6930  6930 W art     : b5942000-b5943000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:58.575  6930  6930 W art     : b5943000-b5944000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 17:24:58.575  6930  6930 W art     : b5944000-b598a000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b598a000-b5993000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 17:24:58.575  6930  6930 W art     : b5993000-b5994000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-30 17:24:58.575  6930  6930 W art     : b5994000-b5995000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-30 17:24:58.575  6930  6930 W art     : b5996000-b599b000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:58.575  6930  6930 W art     : b599b000-b599c000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:58.575  6930  6930 W art     : b599c000-b599d000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 17:24:58.575  6930  6930 W art     : b599d000-b59a0000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:58.575  6930  6930 W art     : b59a0000-b59a1000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b59a1000-b59a2000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:58.575  6930  6930 W art     : b59a2000-b59a3000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 17:24:58.575  6930  6930 W art     : b59a3000-b59a4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-30 17:24:58.575  6930  6930 W art     : or]
08-30 17:24:58.575  6930  6930 W art     : b59a4000-b59bc000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:58.575  6930  6930 W art     : b59bc000-b59bd000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b59bd000-b59be000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:58.575  6930  6930 W art     : b59be000-b59bf000 rw-p 00019000 b3:
08-30 17:24:58.575  6930  6930 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-30 17:24:58.575  6930  6930 W art     : b59c0000-b5b5a000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 17:24:58.575  6930  6930 W art     : b5b5a000-b5b5b000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5b5b000-b5b68000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 17:24:58.575  6930  6930 W art     : b5b68000-b5b69000 rw-p 001a7000 b3:17 604        /system/
08-30 17:24:58.575  6930  6930 W art     : lib/libstagefright.so
08-30 17:24:58.575  6930  6930 W art     : b5b69000-b5b6d000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 17:24:58.575  6930  6930 W art     : b5b6d000-b5b6e000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5b6e000-b5b6f000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 17:24:58.575  6930  6930 W art     : b5b6f000-b5b70000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 17:24:58.575  6930  6930 W art     : ersona.so
08-30 17:24:58.575  6930  6930 W art     : b5b70000-b5b83000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:58.575  6930  6930 W art     : b5b83000-b5b84000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:58.575  6930  6930 W art     : b5b84000-b5b85000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 17:24:58.575  6930  6930 W art     : b5b86000-b5bd1000 r
08-30 17:24:58.575  6930  6930 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:58.575  6930  6930 W art     : b5bd1000-b5bd2000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:58.575  6930  6930 W art     : b5bd2000-b5bd3000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 17:24:58.575  6930  6930 W art     : b5bd3000-b5bd5000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5bd5000-b5bd6000 r--p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5bd6000-b5be7000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:58.575  6930  6930 W art     : b5be7000-b5be8000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5be8000-b5be9000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:58.575  6930  6930 W art     : b5be9000-b5bea000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 17:24:58.575  6930  6930 W art     : b5bea000-b5beb000 r--p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5beb000-b5bf5000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:58.575  6930  6930 W art     : b5bf5000-b5bf7000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:58.575  6930  6930 W art     : b5bf7000-b5bf8000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 17:24:58.575  6930  6930 W art     : b5bf8000-b5c11000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:58.575  6930  6930 W art     : b5c11000-b5c12000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:58.575  6930  6930 W art     : b5c12000-b5c15000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-30 17:24:58.575  6930  6930 W art     : b5c15000-b5c19000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5c19000-b5c8d000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:58.575  6930  6930 W art     : b5c8d000-b5c8e000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5c8e000-b5c91000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:58.575  6930  6930 W art     : b5c91000-b5c92000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 17:24:58.575  6930  6930 W art     : b5c92000-b5c93000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5c93000-b5c96000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:58.575  6930  6930 W art     : b5c96000-b5c97000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:58.575  6930  6930 W art     : b5c97000-b5c98000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-30 17:24:58.575  6930  6930 W art     : b5c98000-b5c99000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5c99000-b5c9e000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:58.575  6930  6930 W art     : b5c9e000-b5c9f000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:58.575  6930  6930 W art     : b5c9f000-b5ca0000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 17:24:58.575  6930  6930 W art     : b5ca0000-b5ca1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5ca1000-b5ca4000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:58.575  6930  6930 W art     : b5ca4000-b5ca5000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:58.575  6930  6930 W art     : b5ca5000-b5ca6000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 17:24:58.575  6930  6930 W art     : b5ca6000-b5ca7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:58.575  6930  6930 W art     : b5ca7000-b5cab000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:58.575  6930  6930 W art     : b5cab000-b5cac000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:58.575  6930  6930 W art     : b5cac000-b5cad000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-30 17:24:58.575  6930  6930 W art     : b5cad000-b5cae000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5cae000-b5cb2000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:58.575  6930  6930 W art     : b5cb2000-b5cb3000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:58.575  6930  6930 W art     : b5cb3000-b5cb4000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 17:24:58.575  6930  6930 W art     : b5cb4000-b5cb5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5cb5000-b5cc3000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:58.575  6930  6930 W art     : b5cc3000-b5cc4000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b5cc4000-b5cc5000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:58.575  6930  6930 W art     : b5cc5000-b5cc6000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-30 17:24:58.575  6930  6930 W art     : b5cc6000-b5cd0000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:58.575  6930  6930 W art     : b5cd0000-b5cd3000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:58.575  6930  6930 W art     : b5cd3000-b5cd4000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 17:24:58.575  6930  6930 W art     : b5cd4000-b5cd5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5cd5000-b5cdf000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:58.575  6930  6930 W art     : b5cdf000-b5ce2000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:58.575  6930  6930 W art     : b5ce2000-b5ce3000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 17:24:58.575  6930  6930 W art     : b5ce3000-b5ce7000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:58.575  6930  6930 W art     : b5ce7000-b5ce8000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:58.575  6930  6930 W art     : b5ce8000-b5ce9000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-30 17:24:58.575  6930  6930 W art     : b5ce9000-b5cea000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b5cea000-b5cf7000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:58.575  6930  6930 W art     : b5cf7000-b5cf9000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:58.575  6930  6930 W art     : b5cf9000-b5cfa000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-30 17:24:58.575  6930  6930 W art     : b5cfa000-b610c000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:58.575  6930  6930 W art     : b610c000-b610d000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b610d000-b6116000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:58.575  6930  6930 W art     : b6116000-b611a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 17:24:58.575  6930  6930 W art     : b611a000-b611b000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b611b000-b6122000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:58.575  6930  6930 W art     : b6122000-b6123000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:58.575  6930  6930 W art     : b6123000-b6124000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 17:24:58.575  6930  6930 W art     : b6124000-b6125000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b6125000-b6140000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-30 17:24:58.575  6930  6930 W art     : b6140000-b6141000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 17:24:58.575  6930  6930 W art     : b6141000-b6142000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 17:24:58.575  6930  6930 W art     : b6142000-b6143000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b6143000-b618f000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:58.575  6930  6930 W art     : b618f000-b6190000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b6190000-b6191000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:58.575  6930  6930 W art     : b6191000-b6192000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 17:24:58.575  6930  6930 W art     : b6192000-b6193000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b6193000-b6197000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:58.575  6930  6930 W art     : b6197000-b6198000 ---p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b6198000-b6199000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:58.575  6930  6930 W art     : b6199000-b619a000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 17:24:58.575  6930  6930 W art     : b619a000-b61d2000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:58.575  6930  6930 W art     : b61d2000-b61d3000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:58.575  6930  6930 W art     : b61d3000-b61d4000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 17:24:58.575  6930  6930 W art     : b61d4000-b61d5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.575  6930  6930 W art     : b61d5000-b6274000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:58.575  6930  6930 W art     : b6274000-b6292000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:58.575  6930  6930 W art     : b6292000-b6293000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-30 17:24:58.575  6930  6930 W art     : b6293000-b6406000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:58.575  6930  6930 W art     : b6406000-b6411000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:58.575  6930  6930 W art     : b6411000-b6412000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 17:24:58.575  6930  6930 W art     : b6412000-b6529000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:58.575  6930  6930 W art     : b6529000-b6534000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:58.575  6930  6930 W art     : b6534000-b6535000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-30 17:24:58.575  6930  6930 W art     : b6535000-b6539000 rw-p 00000000 00:00 0 
08-30 17:24:58.575  6930  6930 W art     : b6539000-b655d000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 17:24:58.575  6930  6930 W art     : b655d000-b655f000 r--p 00023000 b3:17 400        /system/lib/libssl.so
,08-30 17:24:58.585  6930  6930 W art     : b655f000-b6560000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-30 17:24:58.585  6930  6930 W art     : b6560000-b6606000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:58.585  6930  6930 W art     : b6606000-b6613000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:58.585  6930  6930 W art     : b6613000-b6614000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 17:24:58.585  6930  6930 W art     : b6614000-b6615000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6615000-b6668000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:58.585  6930  6930 W art     : b6668000-b6669000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6669000-b666a000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:58.585  6930  6930 W art     : b666a000-b666b000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-30 17:24:58.585  6930  6930 W art     : b666b000-b6670000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6670000-b6682000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:58.585  6930  6930 W art     : b6682000-b6683000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6683000-b6684000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:58.585  6930  6930 W art     : b6684000-b6685000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 17:24:58.585  6930  6930 W art     : b6685000-b668c000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:58.585  6930  6930 W art     : b668c000-b668d000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:58.585  6930  6930 W art     : b668d000-b668e000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 17:24:58.585  6930  6930 W art     : b668e000-b668f000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b668f000-b6692000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:58.585  6930  6930 W art     : b6692000-b6693000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:58.585  6930  6930 W art     : b6693000-b6694000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-30 17:24:58.585  6930  6930 W art     : b6694000-b6698000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 17:24:58.585  6930  6930 W art     : b6698000-b6699000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 17:24:58.585  6930  6930 W art     : b6699000-b669a000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-30 17:24:58.585  6930  6930 W art     : b669a000-b66a8000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:58.585  6930  6930 W art     : b66a8000-b66a9000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b66a9000-b66aa000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:58.585  6930  6930 W art     : b66aa000-b66ab000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-30 17:24:58.585  6930  6930 W art     : b66ab000-b66b4000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:58.585  6930  6930 W art     : b66b4000-b66b5000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:58.585  6930  6930 W art     : b66b5000-b66b6000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 17:24:58.585  6930  6930 W art     : b66b6000-b671c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:58.585  6930  6930 W art     : b671c000-b671d000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b671d000-b671f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:58.585  6930  6930 W art     : b671f000-b6728000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 17:24:58.585  6930  6930 W art     : b6728000-b672b000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b672b000-b67c2000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:58.585  6930  6930 W art     : b67c2000-b67c4000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:58.585  6930  6930 W art     : b67c4000-b67c5000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 17:24:58.585  6930  6930 W art     : b67c5000-b67c6000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b67c6000-b6ae4000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 17:24:58.585  6930  6930 W art     : b6ae4000-b6ae5000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6ae5000-b6b00000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 17:24:58.585  6930  6930 W art     : b6b00000-b6b04000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-30 17:24:58.585  6930  6930 W art     : b6b04000-b6b09000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6b09000-b6b11000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:58.585  6930  6930 W art     : b6b11000-b6b12000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:58.585  6930  6930 W art     : b6b12000-b6b13000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 17:24:58.585  6930  6930 W art     : b6b13000-b6b41000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:58.585  6930  6930 W art     : b6b41000-b6b42000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6b42000-b6b49000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:58.585  6930  6930 W art     : b6b49000-b6b4a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 17:24:58.585  6930  6930 W art     : b6b4a000-b6b90000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:58.585  6930  6930 W art     : b6b90000-b6b91000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6b91000-b6b94000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:58.585  6930  6930 W art     : b6b94000-b6b95000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-30 17:24:58.585  6930  6930 W art     : b6b95000-b6bb0000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:58.585  6930  6930 W art     : b6bb0000-b6bb4000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:58.585  6930  6930 W art     : b6bb4000-b6bb5000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-30 17:24:58.585  6930  6930 W art     : b6bb5000-b6c02000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:58.585  6930  6930 W art     : b6c02000-b6c03000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6c03000-b6c0f000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:58.585  6930  6930 W art     : b6c0f000-b6c10000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-30 17:24:58.585  6930  6930 W art     : b6c10000-b6c1d000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-30 17:24:58.585  6930  6930 W art     : b6c1d000-b6c1e000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6c1e000-b6c1f000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 17:24:58.585  6930  6930 W art     : b6c1f000-b6c20000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-30 17:24:58.585  6930  6930 W art     : b6c20000-b6c28000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:58.585  6930  6930 W art     : b6c28000-b6c29000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6c29000-b6c2a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:58.585  6930  6930 W art     : b6c2a000-b6c2b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-30 17:24:58.585  6930  6930 W art     : b6c2b000-b6c32000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:58.585  6930  6930 W art     : b6c32000-b6c33000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:58.585  6930  6930 W art     : b6c33000-b6c34000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 17:24:58.585  6930  6930 W art     : b6c34000-b6c48000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:58.585  6930  6930 W art     : b6c48000-b6c4a000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:58.585  6930  6930 W art     : b6c4a000-b6c4b000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 17:24:58.585  6930  6930 W art     : b6c4b000-b6c73000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:58.585  6930  6930 W art     : b6c73000-b6c75000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:58.585  6930  6930 W art     : b6c75000-b6c76000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-30 17:24:58.585  6930  6930 W art     : b6c76000-b6c79000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:58.585  6930  6930 W art     : b6c79000-b6c7a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:58.585  6930  6930 W art     : b6c7a000-b6c7b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-30 17:24:58.585  6930  6930 W art     : b6c7b000-b6c84000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:58.585  6930  6930 W art     : b6c84000-b6c85000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:58.585  6930  6930 W art     : b6c85000-b6c86000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 17:24:58.585  6930  6930 W art     : b6c86000-b6ca6000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 17:24:58.585  6930  6930 W art     : b6ca6000-b6ca7000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-30 17:24:58.585  6930  6930 W art     : b6ca7000-b6ca8000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 17:24:58.585  6930  6930 W art     : b6ca8000-b6d1b000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 17:24:58.585  6930  6930 W art     : b6d1b000-b6d1f000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-30 17:24:58.585  6930  6930 W art     : b6d1f000-b6d22000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-30 17:24:58.585  6930  6930 W art     : b6d22000-b6d2c000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6d2c000-b6db4000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:58.585  6930  6930 W art     : b6db4000-b6db5000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6db5000-b6db9000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:58.585  6930  6930 W art     : b6db9000-b6dba000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 17:24:58.585  6930  6930 W art     : b6dba000-b6dbb000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6dbb000-b6de4000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:58.585  6930  6930 W art     : b6de4000-b6de5000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6de5000-b6de8000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:58.585  6930  6930 W art     : b6de8000-b6de9000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 17:24:58.585  6930  6930 W art     : b6de9000-b6ec3000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:58.585  6930  6930 W art     : b6ec3000-b6eca000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:58.585  6930  6930 W art     : b6eca000-b6ed2000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 17:24:58.585  6930  6930 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6ed3000-b6ed4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:58.585  6930  6930 W art     : b6ed4000-b6ed5000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-30 17:24:58.585  6930  6930 W art     : b6ed5000-b6ed6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6ed6000-b6ed9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6ed9000-b6efe000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:58.585  6930  6930 W art     : b6efe000-b6eff000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6eff000-b6f06000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:58.585  6930  6930 W art     : b6f06000-b6f07000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 17:24:58.585  6930  6930 W art     : b6f07000-b6f0e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:58.585  6930  6930 W art     : b6f0e000-b6f0f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:58.585  6930  6930 W art     : b6f0f000-b6f10000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 17:24:58.585  6930  6930 W art     : b6f10000-b6f11000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6f11000-b6f29000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f29000-b6f2a000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6f2a000-b6f2b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f2b000-b6f2c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f2c000-b6f3a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f3a000-b6f3b000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6f3b000-b6f3c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f3c000-b6f3d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-30 17:24:58.585  6930  6930 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:58.585  6930  6930 W art     : b6f3e000-b6f40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6f41000-b6f42000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 17:24:58.585  6930  6930 W art     : b6f42000-b6f43000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 17:24:58.585  6930  6930 W art     : b6f43000-b6f44000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 17:24:58.585  6930  6930 W art     : b6f44000-b6f64000 r--s 00000000 00:0b 9236       /dev/__properties__
08-30 17:24:58.585  6930  6930 W art     : b6f64000-b6f65000 r--p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6f65000-b6f66000 ---p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6f66000-b6f68000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-30 17:24:58.585  6930  6930 W art     : b6f68000-b6f69000 r-xp 00000000 00:00 0          [sigpage]
08-30 17:24:58.585  6930  6930 W art     : b6f69000-b6f84000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 17:24:58.585  6930  6930 W art     : b6f84000-b6f85000 r--p 0001a000 b3:17 341        /system/bin/linker
08-30 17:24:58.585  6930  6930 W art     : b6f85000-b6f87000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 17:24:58.585  6930  6930 W art     : b6f87000-b6f89000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : b6f89000-b6f8e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 17:24:58.585  6930  6930 W art     : b6f8e000-b6f8f000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-30 17:24:58.585  6930  6930 W art     : b6f8f000-b6f90000 rw-p 00000000 00:00 0 
08-30 17:24:58.585  6930  6930 W art     : bedd7000-bedf8000 rw-p 00000000 00:00 0          [stack]
08-30 17:24:58.585  6930  6930 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-30 17:24:58.635  6930  6930 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 17:24:58.705  6930  6930 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 17:24:58.715  6930  6930 E AffinityControl: AffinityControl: registerfunction enter
,08-30 17:24:58.735  6930  6930 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:24:58.755   772  1217 D PackageManager: START PACKAGE DELETE: observer{145702253}
08-30 17:24:58.755   772  1217 D PackageManager: pkg{<packageName>}
08-30 17:24:58.755   772  1217 D PackageManager: user{0}
08-30 17:24:58.755   772  1217 D PackageManager: caller{2000}
08-30 17:24:58.755   772  1217 D PackageManager: flags{2}
08-30 17:24:58.755   772  1217 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-30 17:24:58.755   772  1217 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 17:24:58.755   772  1217 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 17:24:58.755   772  1217 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 17:24:58.755   772  1217 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 17:24:58.755   772   945 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 17:24:58.765   772   945 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-30 17:24:58.765   772   945 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 17:24:58.765   772   945 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 17:24:58.765   772   945 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 17:24:58.765   772   945 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 17:24:58.765   772   945 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 17:24:58.765   772   945 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-30 17:24:58.765   772   872 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-30 17:24:58.765   772   945 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 17:24:58.765   772   945 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 17:24:58.765   772   872 I ActivityManager: Killing 6544:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-30 17:24:58.775   772   872 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 17:24:58.775   772   872 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 17:24:58.785   772   945 D AASAinstall: there is not AASApackages.xml file
,08-30 17:24:58.855   772  1604 D GraphicsStats: Buffer count: 4
,08-30 17:24:58.855   772  1217 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@6a28da2)
,08-30 17:24:58.855   772  1328 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:24:58.855   772  1802 I WindowState: WIN DEATH: Window{79ccbb0 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:24:58.865   292  5235 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
08-30 17:24:58.865   772  1328 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:58.865   292   352 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-30 17:24:58.865   772  1328 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:58.865   292   357 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-30 17:24:58.865   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb3a4
,08-30 17:24:59.215   772   945 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 17:24:59.335   772   945 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 17:24:59.335   772   872 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 17:24:59.345   334   334 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-30 17:24:59.345   772   945 I art     : Starting a blocking GC Explicit
,08-30 17:24:59.355   772   872 E ActivityManager: Failure starting process com.test.thalitest
08-30 17:24:59.355   772   872 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5275)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5192)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5030)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6685)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7383)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9144)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8767)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8922)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2599)
08-30 17:24:59.355   772   872 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:59.355   772   872 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 17:24:59.355   772   872 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:59.355   772   872 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 17:24:59.355   772   872 I ActivityManager:   Force finishing activity ActivityRecord{2719fa1 u0 com.test.thalitest/.MainActivity t167}
,08-30 17:24:59.535   772   945 I art     : Explicit concurrent mark sweep GC freed 90872(4MB) AllocSpace objects, 9(180KB) LOS objects, 27% free, 42MB/58MB, paused 2.143ms total 179.485ms
,08-30 17:24:59.565   772   945 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 17:24:59.575   772   945 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-30 17:24:59.575   772   945 D AASAinstall: there is not AASApackages.xml file
,08-30 17:24:59.575   772   945 D PackageManager: result of delete: 1{145702253}
,08-30 17:24:59.575   772   945 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 17:24:59.575   772   945 D PackageManager: userId{-1}
08-30 17:24:59.575   772   945 D PackageManager: andCode{true}
,08-30 17:24:59.585  6930  6930 I art     : System.exit called, status: 0
08-30 17:24:59.585  6930  6930 I AndroidRuntime: VM exiting with result code 0.
,08-30 17:24:59.605   772   945 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-30 17:24:59.615  5965  6957 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 17:24:59.615  5965  6957 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 17:24:59.615  5965  6957 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 17:24:59.705   772   872 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 17:24:59.705   772   872 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 17:24:59.715   772   872 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 17:24:59.715   772   772 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.725  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-30 17:24:59.725  1378  1378 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-30 17:24:59.725   772   772 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.725   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.735   772   904 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.735   772   904 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.745   772  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:24:59.745  2049  2333 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:24:59.745   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.745   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.755  2083  2083 E SamsungIME: mOCRHelper is null
,08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.755   772   772 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.765   772   772 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.765   772   772 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.765   772   872 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9e40c6 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2d0fe6 4352:com.samsung.klmsagent/u0a18}
,08-30 17:24:59.775  1683  1683 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 17:24:59.775   772   772 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.775   772   772 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.785   772   945 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x71c24efc in tid 945 (PackageManager)
,08-30 17:24:59.785   772  1295 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-30 17:24:59.785   772   772 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.785   772   772 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 17:24:59.785  3247  3263 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 17:24:59.785  4352  4352 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d08644 in tid 4352 (msung.klmsagent)
,08-30 17:24:59.785  3247  3263 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 17:24:59.785  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
08-30 17:24:59.785  3247  3263 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 17:24:59.795   772   772 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.795   772   772 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 17:24:59.795  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
,08-30 17:24:59.795  4352  4352 F libc    : Unable to open connection to debuggerd: Connection refused
,08-30 17:24:59.795  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
,08-30 17:24:59.835   350   350 I Zygote  : Process 4352 exited due to signal (7)
,08-30 17:24:59.875   291   291 I ServiceManager: service 'sec_analytics' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'telecom' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'alarm' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'context_aware' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'scontext' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'barbeam' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'multiwindow_facade' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'window' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'input' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'audio' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'display' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'persona_policy' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'package' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'user' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'procstats' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'meminfo' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'gfxinfo' died
08-30 17:24:59.875   291   291 I ServiceManager: service 'dbinfo' died
08-30 17:24:59.885   328   328 W AudioFlinger: power manager service died !!!
08-30 17:24:59.885   328   328 W AudioFlinger: power manager service died !!!
08-30 17:24:59.885   291   291 I ServiceManager: service 'cpuinfo' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'permission' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'processinfo' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'sensorservice' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'activity' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'mdm.remotedesktop' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'battery' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'usagestats' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'webviewupdate' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'scheduling_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'telephony.registry' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'persona' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'SEAMService' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'media.camera.proxy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'account' died
08-30 17:24:59.895  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
08-30 17:24:59.885   291   291 I ServiceManager: service 'content' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'DirEncryptService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'LSManager' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'ReactiveService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'DeviceRootKeyService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'EngineeringModeService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'SatsService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'sedenial' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'vibrator' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'tw_toolbox' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'tima' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'iccc' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'cepproxyks' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'emailksproxy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'bluetooth_manager' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'consumer_ir' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'rcp' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'media_projection' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'lpnet' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'imms' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'edmnativehelper' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'input_method' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'accessibility' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'cover' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'mount' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'uimode' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'lock_settings' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'deviceidle' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'device_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'harmony_eas_service' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'sdp' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'sdp_log' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'dlp' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'log_manager_service' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'mum_container_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'enterprise_billing_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'otp_service' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'enterprise_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'statusbar' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'clipboard' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'clipboardEx' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'network_management' died
08-30 17:24:59.885  1986  2000 W Sensors : sensorservice died [0xb3ab2d00]
08-30 17:24:59.885   291   291 I ServiceManager: service 'DockObserver' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'ABTPersis,tenceService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'textservices' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'network_score' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'netstats' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'netpolicy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wifip2p' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wifi' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wifihs20' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wifiscanner' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'rttmanager' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'ethernet' died
08-30 17:24:59.895  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
08-30 17:24:59.885   291   291 I ServiceManager: service 'midi' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'connectivity' died
08-30 17:24:59.885  2205  2220 W Sensors : sensorservice died [0xad850dc0]
08-30 17:24:59.885   291   291 I ServiceManager: service 'sb_service' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'servicediscovery' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'updatelock' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'notification' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'devicestoragemonitor' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'location' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'country_detector' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'sec_location' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'search' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'execute' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'dropbox' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wallpaper' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'usb' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'serial' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'kiesusb' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'jobscheduler' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'backup' died
08-30 17:24:59.905  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
08-30 17:24:59.885   291   291 I ServiceManager: service 'appwidget' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'voiceinteraction' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'SecExternalDisplayService' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'diskstats' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'mDNIe' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'AAS' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'MSCS' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'spengestureservice' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'quickconnect' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'samplingprofiler' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'commontime_management' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'dreams' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'graphicsstats' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'print' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'restrictions' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'media_session' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'media_router' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'trust' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'fingerprint' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'launcherapps' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'voip' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'knox_ccm_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'enterprise_license_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'application_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'wifi_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'phone_restriction_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'remoteinjection' died
,08-30 17:24:59.885   291   291 I ServiceManager: service 'knox_ucsm_policy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'edm_proxy' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'batterystats' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'appops' died
08-30 17:24:59.885   291   291 I ServiceManager: service 'power' died
08-30 17:24:59.885  2567  2589 W Sensors : sensorservice died [0xb3abfdc0]
,08-30 17:24:59.885  1378  1397 W Sensors : sensorservice died [0xacee2c80]
08-30 17:24:59.885   292  1500 D libEGL  : eglTerminate EGLDisplay = 0xb4abf6fc
08-30 17:24:59.885   292  1500 D libEGL  : eglTerminate EGLDisplay = 0xb4abf6fc
08-30 17:24:59.885   292  1500 I SurfaceFlinger: restart the boot-animation @ binderDied
08-30 17:24:59.885  1378  1599 E WifiManager: Channel connection lost
08-30 17:24:59.895   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-30 17:24:59.895   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-30 17:24:59.895  3247  3263 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e31b026 in tid 3263 (AccountChangeLi)
08-30 17:24:59.895  3247  3263 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 17:24:59.895  2506  2506 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ee5a39a in tid 2506 (droid.bluetooth)
08-30 17:24:59.895  1683  1683 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-30 17:24:59.895  2205  3218 E WifiManager: Channel connection lost
08-30 17:24:59.895  2506  2506 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 17:24:59.895  1671  1671 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2ca7c02 in tid 1671 (com.android.nfc)
,08-30 17:24:59.905  1671  1671 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 17:24:59.905  2049  2391 W Sensors : sensorservice died [0xb292c980]
08-30 17:24:59.905  1683  2172 E WifiManager: Channel connection lost
08-30 17:24:59.905  2049  2332 E WifiManager: Channel connection lost
,08-30 17:24:59.915  1812  1923 E WifiManager: Channel connection lost
,08-30 17:24:59.915   292   357 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
,08-30 17:24:59.915  1697  2069 W Sensors : sensorservice died [0xad80e480]
,08-30 17:24:59.915  6109  6163 E WifiManager: Channel connection lost
,08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=18 Removed DolorFade (8/8)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=18 Removed DolorFade (-2/8)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=21 Removed VSBConnecti (6/7)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=22 Removed VSBConnecti (4/6)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/6)
08-30 17:24:59.925   292  6973 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/6)
08-30 17:24:59.925   292   352 I SurfaceFlinger: id=5 Removed TtatusBar (5/5)
08-30 17:24:59.925   332   332 E installd: eof
08-30 17:24:59.925   332   332 E installd: failed to read size
08-30 17:24:59.925   332   332 I installd: closing connection
08-30 17:24:59.925   292   352 I SurfaceFlinger: id=5 Removed TtatusBar (-2/5)
,08-30 17:24:59.925   292   352 I SurfaceFlinger: id=7 Removed JmageWallpa (3/4)
08-30 17:24:59.925   292   352 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/4)
08-30 17:24:59.925   292   357 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/3)
08-30 17:24:59.925   292   357 I SurfaceFlinger: id=4 Removed EimLayer(An (0/2)
08-30 17:24:59.925   292   357 I SurfaceFlinger: id=15 Removed EimLayer(An (0/1)
,08-30 17:24:59.925   292   357 I SurfaceFlinger: id=14 Removed EimLayer(Di (0/0)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
08-30 17:24:59.925   292  5235 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
08-30 17:24:59.925   292   357 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-30 17:24:59.925   292   357 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
,08-30 17:24:59.925   292   357 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-30 17:24:59.945   291   291 I ServiceManager: service 'nfc' died
08-30 17:24:59.945   291   291 I ServiceManager: service 'secontroller' died
08-30 17:24:59.945   291   291 I ServiceManager: service 'nfccontroller' died
,08-30 17:24:59.945  2205  2205 D BluetoothA2dp: Proxy object disconnected
,08-30 17:24:59.945  2205  2205 D A2dpProfile: Bluetooth service disconnected
08-30 17:24:59.945  2205  2205 D BluetoothMap: Proxy object disconnected
08-30 17:24:59.945  2205  2205 D MapProfile: Bluetooth service disconnected
08-30 17:24:59.945  2551  2551 D BluetoothA2dp: Proxy object disconnected
,08-30 17:24:59.945  2205  2205 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b98d2bd in tid 2205 (ndroid.settings)
,08-30 17:24:59.945  2205  2205 F libc    : Unable to open connection to debuggerd: Connection refused
,08-30 17:24:59.945  2511  2511 E audit_log: File locking failed. error= Bad file descriptor
,08-30 17:24:59.965   350   350 I Zygote  : Process 1671 exited due to signal (7)
,08-30 17:24:59.975   350   350 I Zygote  : Process 3247 exited due to signal (7)
,08-30 17:25:00.035   350   350 I Zygote  : Process 2205 exited due to signal (7)
,08-30 17:25:00.035   350   350 I Zygote  : Process 2506 exited due to signal (7)
,08-30 17:25:00.135   292   547 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-30 17:25:00.135   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-30 17:25:00.145   290   290 I lowmemorykiller: ActivityManager disconnected
08-30 17:25:00.145   290   290 I lowmemorykiller: Closing Activity Manager data connection
,08-30 17:25:00.385   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-30 17:25:00.395   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb3a4
,08-30 17:25:00.405   292   547 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 17:25:00.405   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb3a4
,08-30 17:25:00.405   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
,08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
,08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
,08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c
08-30 17:25:00.415   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeebb38c

```
