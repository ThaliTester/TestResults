#### Test 80912877c1aacde_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-12 11:11:04.786  5407  5407 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-12 11:11:04.786  5407  5407 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 11:11:04.786  5407  5407 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-12 11:11:04.786  5407  5407 I art     : System.exit called, status: 0
08-12 11:11:04.786  5407  5407 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-12 11:11:04.816  5355  5355 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
--------- beginning of system
08-12 11:11:04.816   764  2321 I ActivityManager: Process com.samsung.aasaservice (pid 5407)(adj 0) has died(107,767)
08-12 11:11:04.816   764  2321 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 11:11:04.816   764  2321 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 11:11:04.816   764  2321 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-12 11:11:04.846   764   861 I ActivityManager: Start proc 6315:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-12 11:11:04.846   764  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 11:11:04.856  6315  6315 E Zygote  : v2
08-12 11:11:04.856  6315  6315 I libpersona: KNOX_SDCARD checking this for 10014
08-12 11:11:04.856  6315  6315 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:04.856  6315  6315 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:04.856  6315  6315 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:04.856  6315  6315 E Zygote  : accessInfo : 0
08-12 11:11:04.856  6315  6315 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-12 11:11:04.886  6315  6315 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:04.886  6315  6315 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:04.896   764  1467 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2dfa3fb 6315:com.google.android.partnersetup/u0a14}
08-12 11:11:04.896   764  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-12 11:11:04.906  6315  6315 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-12 11:11:04.916  6315  6315 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-12 11:11:04.936   764  1275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2dfa3fb 6315:com.google.android.partnersetup/u0a14}
08-12 11:11:04.956   764  1467 I ActivityManager: Start proc 6337:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-12 11:11:04.956  6337  6337 E Zygote  : v2
08-12 11:11:04.956  6337  6337 I libpersona: KNOX_SDCARD checking this for 10015
08-12 11:11:04.956  6337  6337 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:04.956  6337  6337 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:04.956  6337  6337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:04.956  6337  6337 E Zygote  : accessInfo : 0
08-12 11:11:04.966  6337  6337 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 11:11:04.986  6337  6337 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:04.986  6337  6337 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:04.986   764   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1e6c56 6337:com.samsung.groupcast/u0a15}
08-12 11:11:04.996  6337  6337 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-12 11:11:05.006   764  2149 I ActivityManager: Killing 4140:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-12 11:11:05.016  6337  6337 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-12 11:11:05.026   764  1551 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-12 11:11:05.046  6337  6337 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-12 11:11:05.046  6337  6337 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 11:11:05.046  6337  6337 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 11:11:05.046  6337  6337 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 11:11:05.046  6337  6337 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 11:11:05.046  6337  6337 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:05.046  6337  6337 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 11:11:05.046  6337  6337 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 11:11:05.046   764  1234 V AlarmManager: Expired Alarm result :8
08-12 11:11:05.046   764  1705 I ActivityManager: Killing 5526:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-12 11:11:05.056   764  1705 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bac7f4b 1855:com.sec.android.app.shealth:remote/u0a34}
08-12 11:11:05.066   764  1723 I ActivityManager: Start proc 6350:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-12 11:11:05.066  6350  6350 E Zygote  : v2
08-12 11:11:05.066  6350  6350 I libpersona: KNOX_SDCARD checking this for 10041
08-12 11:11:05.066  6350  6350 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.066  6350  6350 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.066  6350  6350 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.076  6350  6350 E Zygote  : accessInfo : 0
08-12 11:11:05.076  6350  6350 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-12 11:11:05.076   764  2223 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-12 11:11:05.096  6350  6350 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.096  6350  6350 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.106   764  1467 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7a84d7 6350:com.samsung.android.sdk.samsunglink/u0a41}
08-12 11:11:05.106  6350  6350 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-12 11:11:05.186  6350  6350 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 11:11:05.186  6350  6350 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 11:11:05.246  6350  6350 I SL_DEBUG: isLoggable:: isProductShip = 1
08-12 11:11:05.246  6350  6350 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-12 11:11:05.256   764  2223 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.256   764   778 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-12 11:11:05.266   764  1727 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.266   764  2154 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.266   764  1467 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.266   764  1551 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.266   764  2321 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.276   764  2220 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.276   764  1726 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.276   764  2149 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-12 11:11:05.386  6350  6350 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-12 11:11:05.386  6350  6350 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 11:11:05.386  6350  6350 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 11:11:05.386  6350  6350 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 11:11:05.386  6350  6350 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 11:11:05.386  6350  6350 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 11:11:05.386  6350  6350 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 11:11:05.386  6350  6350 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:05.386  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 11:11:05.386  6350  6350 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 11:11:05.396   764  1687 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8c6257 1757:android.process.acore/u0a19}
08-12 11:11:05.406   764  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a517f1b 5049:com.sec.android.gallery3d/u0a47}
08-12 11:11:05.406  5049  5049 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-12 11:11:05.406   764  1727 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 11:11:05.426  6373  6373 E Zygote  : v2
08-12 11:11:05.426  6373  6373 I libpersona: KNOX_SDCARD checking this for 10050
08-12 11:11:05.426  6373  6373 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.426   764  1551 I ActivityManager: Start proc 6373:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-12 11:11:05.426  6373  6373 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.426  6373  6373 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.426  6373  6373 E Zygote  : accessInfo : 0
08-12 11:11:05.426  6373  6373 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-12 11:11:05.456  6373  6373 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.456  6373  6373 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.466   764  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11051c7 6373:com.sec.android.app.myfiles/u0a50}
08-12 11:11:05.466   764  1467 I ActivityManager: Killing 5237:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-12 11:11:05.486   764  1726 D CountryDetector: No listener is left
08-12 11:11:05.486   764  1465 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-12 11:11:05.486  6373  6373 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-12 11:11:05.516  6373  6373 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-12 11:11:05.556  6373  6373 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-12 11:11:05.566   764  2154 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ec9d41 2872:com.android.settings/1000}
08-12 11:11:05.566   320   320 E installd: system dir 0 : /system/app/
08-12 11:11:05.566   320   320 E installd: system dir 1 : /system/priv-app/
08-12 11:11:05.566   320   320 E installd: system dir 2 : /vendor/app/
08-12 11:11:05.566   320   320 E installd: system dir 3 : /oem/app/
08-12 11:11:05.576   764   943 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-12 11:11:05.586   764  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ec9d41 2872:com.android.settings/1000}
08-12 11:11:05.596   764  2321 I ActivityManager: Start proc 6388:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-12 11:11:05.596  6388  6388 E Zygote  : v2
08-12 11:11:05.596  6388  6388 I libpersona: KNOX_SDCARD checking this for 10169
08-12 11:11:05.596  6388  6388 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.596  6388  6388 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.596  6388  6388 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.596  6388  6388 E Zygote  : accessInfo : 0
08-12 11:11:05.596  6388  6388 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-12 11:11:05.626  6388  6388 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.626  6388  6388 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.636   764  1705 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db64363 6388:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-12 11:11:05.646  6388  6388 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-12 11:11:05.646  6388  6388 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-12 11:11:05.676   764  1465 I ActivityManager: Killing 5541:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-12 11:11:05.686   764  1465 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d6e2f 1698:com.android.phone/1001}
08-12 11:11:05.696   764  2321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe6f88 1824:com.google.android.googlequicksearchbox:search/u0a61}
08-12 11:11:05.706   764  2220 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-12 11:11:05.716   764  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe6f88 1824:com.google.android.googlequicksearchbox:search/u0a61}
08-12 11:11:05.716   764  1275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2cd4819 6253:com.samsung.android.sm.provider/1000}
08-12 11:11:05.726  2111  2111 E audit   : type=1400 msg=audit(1470993065.726:285): avc:  denied  { execmod } for  pid=6313 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 11:11:05.726  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.726  2111  2111 E audit   : type=1300 msg=audit(1470993065.726:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb2000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6313 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 11:11:05.726  2111  2111 E audit   : type=1327 msg=audit(1470993065.726:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 11:11:05.736  2111  2111 E audit   : type=1320 msg=audit(1470993065.726:285): 
08-12 11:11:05.736  6402  6402 E Zygote  : v2
08-12 11:11:05.736  6402  6402 I libpersona: KNOX_SDCARD checking this for 5012
08-12 11:11:05.736  6402  6402 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.736  6402  6402 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.736  6402  6402 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.736   764  2154 I ActivityManager: Start proc 6402:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-12 11:11:05.736  6402  6402 E Zygote  : accessInfo : 0
08-12 11:11:05.736  6402  6402 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-12 11:11:05.756  1824  6400 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 11:11:05.776  6402  6402 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.776  6402  6402 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.786   764  1551 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b580de 6402:com.samsung.android.sm.devicesecurity/5012}
08-12 11:11:05.786  6402  6402 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-12 11:11:05.796  2111  2111 E audit   : type=1400 msg=audit(1470993065.796:286): avc:  denied  { execmod } for  pid=6313 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 11:11:05.796  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.796  2111  2111 E audit   : type=1300 msg=audit(1470993065.796:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f75000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6313 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 11:11:05.796  2111  2111 E audit   : type=1327 msg=audit(1470993065.796:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 11:11:05.796  2111  2111 E audit   : type=1320 msg=audit(1470993065.796:286): 
08-12 11:11:05.796  6402  6402 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-12 11:11:05.806  1824  6400 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-12 11:11:05.826   764  1705 I ActivityManager: Killing 5153:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-12 11:11:05.826   764  1705 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77d1e95 3207:com.android.contacts/u0a19}
08-12 11:11:05.826  1824  6400 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-12 11:11:05.836   764   861 I ActivityManager: Start proc 6414:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-12 11:11:05.836  6414  6414 E Zygote  : v2
08-12 11:11:05.836  6414  6414 I libpersona: KNOX_SDCARD checking this for 10210
08-12 11:11:05.836  6414  6414 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.836  6414  6414 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.836  6414  6414 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.836  6414  6414 E Zygote  : accessInfo : 0
08-12 11:11:05.836  6414  6414 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-12 11:11:05.846  2111  2111 E audit   : type=1400 msg=audit(1470993065.846:287): avc:  denied  { execmod } for  pid=6313 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 11:11:05.846  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.846  2111  2111 E audit   : type=1300 msg=audit(1470993065.846:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f75000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6313 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 11:11:05.846  2111  2111 E audit   : type=1327 msg=audit(1470993065.846:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 11:11:05.846  2111  2111 E audit   : type=1320 msg=audit(1470993065.846:287): 
08-12 11:11:05.846  6313  6313 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 11:11:05.846   764  2220 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-12 11:11:05.856  6313  6313 D AndroidRuntime: CheckJNI is OFF
08-12 11:11:05.856  6313  6313 D AndroidRuntime: readGMSProperty: start
08-12 11:11:05.856  6313  6313 D AndroidRuntime: readGMSProperty: already setted!!
08-12 11:11:05.856  6313  6313 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 11:11:05.856  6313  6313 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 11:11:05.856  6313  6313 D AndroidRuntime: readGMSProperty: end
08-12 11:11:05.856  6313  6313 D AndroidRuntime: addProductProperty: start
08-12 11:11:05.856  6313  6313 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 11:11:05.856  6313  6313 W art     : aedd9000-b1cff000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:05.856  6313  6313 W art     : b1cff000-b3f6e000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:05.856  6313  6313 W art     : b3f6e000-b3f6f000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:05.856  6313  6313 W art     : b3f6f000-b3f70000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.856  6313  6313 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 11:11:05.856  6313  6313 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 11:11:05.856  6313  6313 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 11:11:05.856  6313  6313 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 11:11:05.856  6313  6313 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 11:11:05.856  6313  6313 W art     : b4842000-b4845000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:05.856  6313  6313 W art     : b4845000-b4846000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:05.856  6313  6313 W art     : b4846000-b4847000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:05.856  6313  6313 W art     : b4847000-b4848000 r--p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b4848000-b4868000 r--s 00000000 00:0b 8200       /dev/__properties__
08-12 11:11:05.856  6313  6313 W art     : b4868000-b5279000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 11:11:05.856  6313  6313 W art     : b5279000-b527a000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b527a000-b52c3000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 11:11:05.856  6313  6313 W art     : b52c3000-b52c4000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 11:11:05.856  6313  6313 W art     : b52c4000-b52cc000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b52cc000-b52cd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.856  6313  6313 W art     : b52cd000-b5302000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:05.856  6313  6313 W art     : b5302000-b5303000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5303000-b5304000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:05.856  6313  6313 W art     : b5304000-b5305000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:05.856  6313  6313 W art     : b5305000-b535d000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 11:11:05.856  6313  6313 W art     : b535d000-b535e000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b535e000-b535f000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 11:11:05.856  6313  6313 W art     : b535f000-b5360000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 11:11:05.856  6313  6313 W art     : b5361000-b5367000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:05.856  6313  6313 W art     : b5367000-b5368000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:05.856  6313  6313 W art     : b5368000-b5369000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:05.856  6313  6313 W art     : b5369000-b536b000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b536c000-b5376000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:05.856  6313  6313 W art     : b5376000-b5379000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:05.856  6313  6313 W art     : b5379000-b537a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:05.856  6313  6313 W art     : b537b000-b5392000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 11:11:05.856  6313  6313 W art     : b5392000-b5393000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5393000-b5394000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 11:11:05.856  6313  6313 W art     : b5394000-b5395000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 11:11:05.856  6313  6313 W art     : b5396000-b53a0000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:05.856  6313  6313 W art     : b53a0000-b53a1000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:05.856  6313  6313 W art     : b53a1000-b53a2000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:05.856  6313  6313 W art     : b53a2000-b53a6000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 11:11:05.856  6313  6313 W art     : b53a6000-b53a7000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 11:11:05.856  6313  6313 W art     : b53a7000-b53a8000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 11:11:05.856  6313  6313 W art     : b53a8000-b53be000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:05.856  6313  6313 W art     : b53be000-b53bf000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:05.856  6313  6313 W art     : b53bf000-b53c0000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:05.856  6313  6313 W art     : b53c0000-b53cd000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 11:11:05.856  6313  6313 W art     : b53cd000-b53ce000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 11:11:05.856  6313  6313 W art     : b53ce000-b53cf000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 11:11:05.856  6313  6313 W art     : b53cf000-b542f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 11:11:05.866   764  1275 I ActivityManager: Start proc 6425:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-12 11:11:05.856  6313  6313 W art     : b542f000-b5432000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 11:11:05.856  6313  6313 W art     : b5432000-b5436000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5436000-b5497000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 11:11:05.856  6313  6313 W art     : b5497000-b5498000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 11:11:05.856  6313  6313 W art     : b5498000-b54e7000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 11:11:05.856  6313  6313 W art     : b54e7000-b54e9000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 11:11:05.856  6313  6313 W art     : b54e9000-b54ea000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 11:11:05.856  6313  6313 W art     : b54ea000-b54eb000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b54eb000-b54f2000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54f2000-b54f3000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54f3000-b54f4000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54f5000-b54f8000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54f8000-b54f9000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54f9000-b54fa000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 11:11:05.856  6313  6313 W art     : b54fb000-b54ff000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:05.856  6313  6313 W art     : b54ff000-b5500000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5500000-b5501000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:05.856  6313  6313 W art     : b5501000-b5502000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:05.856  6313  6313 W art     : b5503000-b5520000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:05.856  6313  6313 W art     : b5520000-b5521000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:05.856  6313  6313 W art     : b5521000-b5522000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:05.856  6313  6313 W art     : b5523000-b5528000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 11:11:05.856  6313  6313 W art     : b5528000-b5529000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 11:11:05.856  6313  6313 W art     : b5529000-b552a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 11:11:05.856  6313  6313 W art     : b552b000-b555c000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:05.856  6313  6313 W art     : b555c000-b555f000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:05.856  6313  6313 W art     : b555f000-b5560000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:05.856  6313  6313 W art     : b5561000-b559c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 11:11:05.856  6313  6313 W art     : b559c000-b559d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 11:11:05.856  6313  6313 W art     : b559d000-b559e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 11:11:05.856  6313  6313 W art     : b559f000-b55a6000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 11:11:05.856  6313  6313 W art     : b55a6000-b55a7000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b55a7000-b55a8000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 11:11:05.856  6313  6313 W art     : b55a8000-b55a9000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 11:11:05.856  6313  6313 W art     : b55a9000-b55aa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.856  6313  6313 W art     : b55aa000-b55c1000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:05.856  6313  6313 W art     : b55c1000-b55c2000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b55c2000-b55c5000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:05.856  6313  6313 W art     : b55c5000-b55c6000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:05.856  6313  6313 W art     : b55c6000-b55e5000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 11:11:05.856  6313  6313 W art     : b55e5000-b55e6000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 11:11:05.856  6313  6313 W art     : b55e6000-b55e7000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 11:11:05.856  6313  6313 W art     : b55e7000-b5625000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:05.856  6313  6313 W art     : b5625000-b5626000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5626000-b5628000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:05.856  6313  6313 W art     : b5628000-b5629000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:05.856  6313  6313 W art     : b562a000-b5631000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:05.856  6313  6313 W art     : b5631000-b5632000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:05.856  6313  6313 W art     : b5632000-b5633000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:05.856  6313  6313 W art     : b5634000-b5637000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 11:11:05.876  6425  6425 I libpersona: KNOX_SDCARD checking this for 10049
08-12 11:11:05.856  6313  6313 W art     : b5637000-b5638000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 11:11:05.876  6425  6425 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:05.856  6313  6313 W art     : b5638000-b5639000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 11:11:05.856  6313  6313 W art     : b5639000-b563f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:05.856  6313  6313 W art     : b563f000-b5640000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5640000-b5641000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:05.856  6313  6313 W art     : b5641000-b5642000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:05.856  6313  6313 W art     : b5642000-b564b000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:05.856  6313  6313 W art     : b564b000-b564c000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:05.856  6313  6313 W art     : b564c000-b564d000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:05.856  6313  6313 W art     : b564d000-b56de000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:05.856  6313  6313 W art     : b56de000-b56df000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b56df000-b56ea000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:05.856  6313  6313 W art     : b56ea000-b56eb000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:05.856  6313  6313 W art     : b56ec000-b56fe000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:05.856  6313  6313 W art     : b56fe000-b56ff000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:05.856  6313  6313 W art     : b56ff000-b5700000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:05.856  6313  6313 W art     : b5701000-b5706000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:05.856  6313  6313 W art     : b5706000-b5707000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:05.856  6313  6313 W art     : b5707000-b5708000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:05.856  6313  6313 W art     : b5709000-b5776000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 11:11:05.856  6313  6313 W art     : b5776000-b5777000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5777000-b5779000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 11:11:05.856  6313  6313 W art     : b5779000-b577a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 11:11:05.856  6313  6313 W art     : b577a000-b577b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.856  6313  6313 W art     : b577b000-b5782000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:05.856  6313  6313 W art     : b5782000-b5783000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:05.856  6313  6313 W art     : b5783000-b5784000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:05.856  6313  6313 W art     : b5785000-b5805000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 11:11:05.856  6313  6313 W art     : b5805000-b5806000 ---p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b5806000-b5807000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 11:11:05.856  6313  6313 W art     : b5807000-b5808000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 11:11:05.856  6313  6313 W art     : b5808000-b581f000 rw-p 00000000 00:00 0 
08-12 11:11:05.856  6313  6313 W art     : b581f000-b5856000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 11:11:05.856  6313  6313 W art     : ib/libqc-opt.so
08-12 11:11:05.856  6313  6313 W art     : b5856000-b5857000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 11:11:05.856  6313  6313 W art     : b5857000-b5858000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 11:11:05.856  6313  6313 W art     : b5858000-b5874000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 11:11:05.856  6313  6313 W art     : b5874000-b5875000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 11:11:05.856  6313  6313 W art     : b5875000-b5876000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 11:11:05.856  6313  6313 W art     : b5877000-b58d8000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:05.856  6313  6313 W art     : b58d8000-b58da000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:05.866  6313  6313 W art     : b58da000-b58db000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:05.866  6313  6313 W art     : b58dc000-b5903000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:05.866  6313  6313 W art     : b5903000-b5904000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5904000-b5905000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:05.866  6313  6313 W art     : b5905000-b5906000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:05.866  6313  6313 W art     : b5907000-b590f000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:05.866  6313  6313 W art     : b590f000-b5911000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:05.866  6313  6313 W art     : b5911000-b5912000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:05.866  6313  6313 W art     : b5913000-b5916000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:05.866  6313  6313 W art     : b5916000-b5917000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:05.866  6313  6313 W art     : b5917000-b5918000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:05.866  6313  6313 W art     : b5918000-b591c000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:05.866  6313  6313 W art     : b591c000-b591d000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b591d000-b591e000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:05.866  6313  6313 W art     : b591e000-b591f000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:05.866  6313  6313 W art     : b591f000-b592f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:05.866  6313  6313 W art     : b592f000-b5930000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:05.866  6313  6313 W art     : b5930000-b5931000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:05.866  6313  6313 W art     : b5931000-b5977000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5977000-b5980000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:05.866  6313  6313 W art     : b5980000-b5981000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:05.866  6313  6313 W art     : b5981000-b5982000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:05.866  6313  6313 W art     : b5983000-b5988000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:05.866  6313  6313 W art     : b5988000-b5989000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:05.866  6313  6313 W art     : b5989000-b598a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:05.866  6313  6313 W art     : b598a000-b598d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 11:11:05.866  6313  6313 W art     : b598d000-b598e000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b598e000-b598f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 11:11:05.866  6313  6313 W art     : b598f000-b5990000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 11:11:05.866  6313  6313 W art     : b5991000-b59a9000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:05.866  6313  6313 W art     : b59a9000-b59aa000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b59aa000-b59ab000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:05.866  6313  6313 W art     : b59ab000-b59ac000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:05.866  6313  6313 W art     : b59ad000-b5b47000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:05.866  6313  6313 W art     : b5b47000-b5b48000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5b48000-b5b55000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:05.866  6313  6313 W art     : b5b55000-b5b56000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:05.866  6313  6313 W art     : b5b56000-b5b5a000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 11:11:05.866  6313  6313 W art     : b5b5a000-b5b5b000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5b5b000-b5b5c000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 11:11:05.866  6313  6313 W art     : b5b5c000-b5b5d000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 11:11:05.866  6313  6313 W art     : b5b5d000-b5b70000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:05.866  6313  6313 W art     : b5b70000-b5b71000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:05.866  6313  6313 W art     : b5b71000-b5b72000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:05.866  6313  6313 W art     : b5b73000-b5bbe000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:05.866  6313  6313 W art     : b5bbe000-b5bbf000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:05.866  6313  6313 W art     : b5bbf000-b5bc0000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:05.866  6313  6313 W art     : b5bc0000-b5bc2000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5bc2000-b5bc3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:05.866  6313  6313 W art     : b5bc3000-b5bd4000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:05.866  6313  6313 W art     : b5bd4000-b5bd5000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5bd5000-b5bd6000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:05.866  6313  6313 W art     : b5bd6000-b5bd7000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:05.866  6313  6313 W art     : b5bd8000-b5be2000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:05.866  6313  6313 W art     : b5be2000-b5be4000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:05.866  6313  6313 W art     : b5be4000-b5be5000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:05.866  6313  6313 W art     : b5be5000-b5bfe000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 11:11:05.866  6313  6313 W art     : b5bfe000-b5bff000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 11:11:05.866  6313  6313 W art     : b5bff000-b5c02000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 11:11:05.866  6313  6313 W art     : b5c02000-b5c06000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5c06000-b5c7a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:05.866  6313  6313 W art     : b5c7a000-b5c7b000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5c7b000-b5c7e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:05.866  6313  6313 W art     : b5c7e000-b5c7f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:05.866  6313  6313 W art     : b5c80000-b5c83000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 11:11:05.866  6313  6313 W art     : b5c83000-b5c84000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 11:11:05.866  6313  6313 W art     : b5c84000-b5c85000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 11:11:05.866  6313  6313 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b5c86000-b5c8b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:05.866  6313  6313 W art     : b5c8b000-b5c8c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:05.866  6313  6313 W art     : b5c8c000-b5c8d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:05.866  6313  6313 W art     : b5c8d000-b5c8e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b5c8e000-b5c91000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b5c91000-b5c92000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b5c92000-b5c93000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b5c94000-b5c98000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:05.866  6313  6313 W art     : b5c98000-b5c99000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:05.866  6313  6313 W art     : b5c99000-b5c9a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:05.866  6313  6313 W art     : b5c9a000-b5c9b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:05.866  6313  6313 W art     : b5c9b000-b5c9f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 11:11:05.866  6313  6313 W art     : b5c9f000-b5ca0000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 11:11:05.866  6313  6313 W art     : b5ca0000-b5ca1000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
,08-12 11:11:05.866  6313  6313 W art     : b5ca1000-b5ca2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b5ca2000-b5cb0000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 11:11:05.866  6313  6313 W art     : b5cb0000-b5cb1000 ---p 00000000 00:00 0 
08-12 11:11:05.896   764  3468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-12 11:11:05.866  6313  6313 W art     : b5cb1000-b5cb2000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
,08-12 11:11:05.866  6313  6313 W art     : b5cb2000-b5cb3000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 11:11:05.866  6313  6313 W art     : b5cb3000-b5cbd000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:05.866  6313  6313 W art     : b5cbd000-b5cc0000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:05.866  6313  6313 W art     : b5cc0000-b5cc1000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:05.866  6313  6313 W art     : b5cc1000-b5cc2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b5cc2000-b5ccc000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 11:11:05.866  6313  6313 W art     : b5ccc000-b5ccf000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 11:11:05.866  6313  6313 W art     : b5ccf000-b5cd0000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 11:11:05.866  6313  6313 W art     : b5cd0000-b5cd4000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:05.866  6313  6313 W art     : b5cd4000-b5cd5000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:05.866  6313  6313 W art     : b5cd5000-b5cd6000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:05.866  6313  6313 W art     : b5cd6000-b5cd7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b5cd7000-b5ce4000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:05.866  6313  6313 W art     : b5ce4000-b5ce6000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:05.866  6313  6313 W art     : b5ce6000-b5ce7000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:05.866  6313  6313 W art     : b5ce7000-b60f9000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 11:11:05.866  6313  6313 W art     : b60f9000-b60fa000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b60fa000-b6103000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 11:11:05.866  6313  6313 W art     : b6103000-b6107000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 11:11:05.866  6313  6313 W art     : b6107000-b6108000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6108000-b610f000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-12 11:11:05.866  6313  6313 W art     : ioutils.so
08-12 11:11:05.866  6313  6313 W art     : b610f000-b6110000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 11:11:05.866  6313  6313 W art     : b6110000-b6111000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 11:11:05.866  6313  6313 W art     : b6111000-b6112000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6112000-b612d000 r-xp 00000000
08-12 11:11:05.866  6313  6313 W art     :  b3:17 1184       /system/lib/libz.so
08-12 11:11:05.866  6313  6313 W art     : b612d000-b612e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 11:11:05.866  6313  6313 W art     : b612e000-b612f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 11:11:05.866  6313  6313 W art     : b612f000-b6130000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6130000-b617c000 r-xp 00000000 b3:17 994        
08-12 11:11:05.866  6313  6313 W art     : /system/lib/libharfbuzz_ng.so
08-12 11:11:05.866  6313  6313 W art     : b617c000-b617d000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b617d000-b617e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 11:11:05.866  6313  6313 W art     : b617e000-b617f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 11:11:05.866  6313  6313 W art     : b617f000-b6180000 r--p 00000000 00:00 0          [anon:li
08-12 11:11:05.866  6313  6313 W art     : nker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6180000-b6184000 r-xp 00000000 b3:17 2681       /s,ystem/lib/libusbhost.so
08-12 11:11:05.866  6313  6313 W art     : b6184000-b6185000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6185000-b6186000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 11:11:05.866  6313  6313 W art     : b6186000-b6187000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-12 11:11:05.866  6313  6313 W art     : sbhost.so
08-12 11:11:05.866  6313  6313 W art     : b6187000-b61bf000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 11:11:05.866  6313  6313 W art     : b61bf000-b61c0000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 11:11:05.866  6313  6313 W art     : b61c0000-b61c1000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 11:11:05.866  6313  6313 W art     : b61c1000-b61c2000 r--p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     :          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b61c2000-b6260000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 11:11:05.866  6313  6313 W art     : b6260000-b6261000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6261000-b627f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 11:11:05.866  6313  6313 W art     : b627f000-b6280000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-12 11:11:05.866  6313  6313 W art     : .so
08-12 11:11:05.866  6313  6313 W art     : b6280000-b63f3000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:05.866  6313  6313 W art     : b63f3000-b63fe000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:05.866  6313  6313 W art     : b63fe000-b63ff000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:05.866  6313  6313 W art     : b63ff000-b6516000 r-xp 00000000
08-12 11:11:05.866  6313  6313 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:05.866  6313  6313 W art     : b6516000-b6521000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:05.866  6313  6313 W art     : b6521000-b6522000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:05.866  6313  6313 W art     : b6522000-b6526000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6526000-b654a000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-12 11:11:05.866  6313  6313 W art     : o
08-12 11:11:05.866  6313  6313 W art     : b654a000-b654c000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 11:11:05.866  6313  6313 W art     : b654c000-b654d000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 11:11:05.866  6313  6313 W art     : b654d000-b65f3000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 11:11:05.866  6313  6313 W art     : b65f3000-b6600000 r--p 000a5000 b3:17 13
08-12 11:11:05.866  6313  6313 W art     : 2        /system/lib/libcrypto.so
08-12 11:11:05.866  6313  6313 W art     : b6600000-b6601000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 11:11:05.866  6313  6313 W art     : b6601000-b6602000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6602000-b6655000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:05.866  6313  6313 W art     : b6655000-b6656000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6656000-b6657000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:05.866  6313  6313 W art     : b6657000-b6658000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:05.866  6313  6313 W art     : b6658000-b665d000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b665d000-b666f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 11:11:05.866  6313  6313 W art     : b666f000-b6670000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6670000-b6671000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 11:11:05.866  6313  6313 W art     : b6671000-b6672000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 11:11:05.866  6313  6313 W ar,t     : b6672000-b6679000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:05.866  6313  6313 W art     : b6679000-b667a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:05.866  6313  6313 W art     : b667a000-b667b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:05.866  6313  6313 W art     : b667b000-b667c000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b667c000-b667f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 11:11:05.866  6313  6313 W art     : b667f000-b6680000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 11:11:05.866  6313  6313 W art     : b6680000-b6681000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 11:11:05.866  6313  6313 W art     : b6681000-b6685000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:05.866  6313  6313 W art     : b6685000-b6686000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:05.866  6313  6313 W art     : b6686000-b6687000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:05.866  6313  6313 W art     : b6687000-b6695000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:05.866  6313  6313 W art     : b6695000-b6696000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6696000-b6697000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:05.866  6313  6313 W art     : b6697000-b6698000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:05.866  6313  6313 W art     : b6698000-b66a1000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 11:11:05.866  6313  6313 W art     : b66a1000-b66a2000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 11:11:05.866  6313  6313 W art     : b66a2000-b66a3000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 11:11:05.866  6313  6313 W art     : b66a3000-b6709000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:05.866  6313  6313 W art     : b6709000-b670a000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b670a000-b670c000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:05.866  6313  6313 W art     : b670c000-b6715000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:05.866  6313  6313 W art     : b6715000-b6718000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6718000-b67af000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 11:11:05.866  6313  6313 W art     : b67af000-b67b1000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 11:11:05.866  6313  6313 W art     : b67b1000-b67b2000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 11:11:05.866  6313  6313 W art     : b67b2000-b67b3000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b67b3000-b6ad4000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 11:11:05.866  6313  6313 W art     : b6ad4000-b6ad5000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6ad5000-b6af0000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 11:11:05.866  6313  6313 W art     : b6af0000-b6af4000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 11:11:05.866  6313  6313 W art     : b6af4000-b6af9000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6af9000-b6b01000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b6b01000-b6b02000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b6b02000-b6b03000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 11:11:05.866  6313  6313 W art     : b6b03000-b6b31000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 11:11:05.866  6313  6313 W art     : b6b31000-b6b32000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6b32000-b6b39000 r--p 0002e000 b3:17 564        ,/system/lib/libcamera_client.so
08-12 11:11:05.866  6313  6313 W art     : b6b39000-b6b3a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 11:11:05.866  6313  6313 W art     : b6b3a000-b6b80000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 11:11:05.866  6313  6313 W art     : b6b80000-b6b81000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6b81000-b6b84000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 11:11:05.866  6313  6313 W art     : b6b84000-b6b85000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 11:11:05.866  6313  6313 W art     : b6b85000-b6ba0000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:05.866  6313  6313 W art     : b6ba0000-b6ba4000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:05.866  6313  6313 W art     : b6ba4000-b6ba5000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:05.866  6313  6313 W art     : b6ba5000-b6bf2000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 11:11:05.866  6313  6313 W art     : b6bf2000-b6bf3000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6bf3000-b6bff000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 11:11:05.866  6313  6313 W art     : b6bff000-b6c00000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 11:11:05.866  6313  6313 W art     : b6c00000-b6c0d000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 11:11:05.866  6313  6313 W art     : b6c0d000-b6c0e000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6c0e000-b6c0f000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 11:11:05.866  6313  6313 W art     : b6c0f000-b6c10000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 11:11:05.866  6313  6313 W art     : b6c10000-b6c18000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 11:11:05.866  6313  6313 W art     : b6c18000-b6c19000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6c19000-b6c1a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 11:11:05.866  6313  6313 W art     : b6c1a000-b6c1b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 11:11:05.866  6313  6313 W art     : b6c1b000-b6c22000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:05.866  6313  6313 W art     : b6c22000-b6c23000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:05.866  6313  6313 W art     : b6c23000-b6c24000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:05.866  6313  6313 W art     : b6c24000-b6c38000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:05.866  6313  6313 W art     : b6c38000-b6c3a000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:05.866  6313  6313 W art     : b6c3a000-b6c3b000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:05.866  6313  6313 W art     : b6c3b000-b6c63000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 11:11:05.866  6313  6313 W art     : b6c63000-b6c65000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 11:11:05.866  6313  6313 W art     : b6c65000-b6c66000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 11:11:05.866  6313  6313 W art     : b6c66000-b6c69000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:05.866  6313  6313 W art     : b6c69000-b6c6a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:05.866  6313  6313 W art     : b6c6a000-b6c6b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:05.866  6313  6313 W art     : b6c6b000-b6c74000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 11:11:05.866  6313  6313 W art     : b6c74000-b6c75000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 11:11:05.866  6313  6313 W art     : b6c75000-b6c76000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 11:11:05.866 , 6313  6313 W art     : b6c76000-b6c96000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 11:11:05.866  6313  6313 W art     : b6c96000-b6c97000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 11:11:05.866  6313  6313 W art     : b6c97000-b6c98000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 11:11:05.866  6313  6313 W art     : b6c98000-b6d0b000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 11:11:05.866  6313  6313 W art     : b6d0b000-b6d0f000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 11:11:05.866  6313  6313 W art     : b6d0f000-b6d12000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 11:11:05.866  6313  6313 W art     : b6d12000-b6d1c000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6d1c000-b6da4000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 11:11:05.866  6313  6313 W art     : b6da4000-b6da5000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6da5000-b6da9000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 11:11:05.866  6313  6313 W art     : b6da9000-b6daa000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 11:11:05.866  6313  6313 W art     : b6daa000-b6dab000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6dab000-b6dd4000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:05.866  6313  6313 W art     : b6dd4000-b6dd5000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6dd5000-b6dd8000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:05.866  6313  6313 W art     : b6dd8000-b6dd9000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:05.866  6313  6313 W art     : b6dd9000-b6eb3000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 11:11:05.866  6313  6313 W art     : b6eb3000-b6eba000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 11:11:05.866  6313  6313 W art     : b6eba000-b6ec2000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 11:11:05.866  6313  6313 W art     : b6ec2000-b6ec3000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6ec3000-b6ec4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:05.866  6313  6313 W art     : b6ec4000-b6ec5000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 11:11:05.866  6313  6313 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6ec6000-b6ec9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6ec9000-b6eee000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 11:11:05.866  6313  6313 W art     : b6eee000-b6eef000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6eef000-b6ef6000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 11:11:05.866  6313  6313 W art     : b6ef6000-b6ef7000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 11:11:05.866  6313  6313 W art     : b6ef7000-b6efe000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:05.866  6313  6313 W art     : b6efe000-b6eff000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:05.866  6313  6313 W art     : b6eff000-b6f00000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:05.866  6313  6313 W art     : b6f00000-b6f01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6f01000-b6f19000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f19000-b6f1a000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6f1a000-b6f1b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f1b000-b6f1c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f1c000-b6f2a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f2a000-b6f2b000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6f2b000-b6f2c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f2c000-b6f2d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:05.866  6313  6313 W art     : b6f2d000-b6f2e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:05.866  6313  6313 W art     : b6f2e000-b6f30000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6f30000-b6f31000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6f31000-b6f32000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:05.866  6313  6313 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 11:11:05.866  6313  6313 W art     : b6f33000-b6f34000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:05.866  6313  6313 W art     : b6f34000-b6f54000 r--s 00000000 00:0b 8200       /dev/__properties__
08-12 11:11:05.866  6313  6313 W art     : b6f54000-b6f55000 r--p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6f55000-b6f56000 ---p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6f56000-b6f58000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 11:11:05.866  6313  6313 W art     : b6f58000-b6f59000 r-xp 00000000 00:00 0          [sigpage]
08-12 11:11:05.866  6313  6313 W art     : b6f59000-b6f74000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 11:11:05.866  6313  6313 W art     : b6f74000-b6f75000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 11:11:05.866  6313  6313 W art     : b6f75000-b6f77000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 11:11:05.866  6313  6313 W art     : b6f77000-b6f79000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : b6f79000-b6f7e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 11:11:05.866  6313  6313 W art     : b6f7e000-b6f7f000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 11:11:05.866  6313  6313 W art     : b6f7f000-b6f80000 rw-p 00000000 00:00 0 
08-12 11:11:05.866  6313  6313 W art     : bea08000-bea29000 rw-p 00000000 00:00 0          [stack]
08-12 11:11:05.866  6313  6313 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 11:11:05.876  6425  6425 E Zygote  : v2
08-12 11:11:05.876  6425  6425 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:05.876  6425  6425 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:05.876  6425  6425 E Zygote  : accessInfo : 0
08-12 11:11:05.876  6425  6425 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-12 11:11:05.886  6414  6414 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.886  6414  6414 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.916   764   777 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-12 11:11:05.926  6313  6313 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 11:11:05.926  6425  6425 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:05.926  6425  6425 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:05.936   764  2154 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc6bbdb 6425:com.android.mms/u0a49}
08-12 11:11:05.946  6414  6414 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-12 11:11:05.976  6313  6313 I Radio-JNI: register_android_hardware_Radio DONE
08-12 11:11:05.976  6313  6313 E AffinityControl: AffinityControl: registerfunction enter
08-12 11:11:05.986  6425  6425 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-12 11:11:05.996  6414  6414 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-12 11:11:05.996  2811  6439 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-12 11:11:06.006  6313  6313 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 11:11:06.016  6414  6414 D AASAservice: onCreate()
08-12 11:11:06.016   764  2223 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 11:11:06.026  6425  6425 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-12 11:11:06.036   764  2223 D ActivityManager: mDVFSHelper.acquire()
08-12 11:11:06.036   764  2223 D FocusedStackFrame: Set to : 0
08-12 11:11:06.036   764  2223 V WindowManager: addAppToken: AppWindowToken{9ce0f42 token=Token{577418d ActivityRecord{295f224 u0 com.test.thalitest/.MainActivity t163}}} to stack=1 task=163 at 0
08-12 11:11:06.046  6425  6425 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-12 11:11:06.046   764   906 D SecWifiDisplayUtil: Metadata value : none
08-12 11:11:06.046   764   906 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9f2449a V.E...... R.....ID 0,0-0,0}
08-12 11:11:06.046   764   906 D ISSUE_DEBUG: InputChannelName : 2f2dda8 Starting com.test.thalitest
08-12 11:11:06.046   764  2223 I ActivityManager: Start proc 6449:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 11:11:06.046   764  2223 D InputDispatcher: Focused application set to: xxxx
08-12 11:11:06.056   764  2223 D InputDispatcher: Focus left window: 1713
08-12 11:11:06.056  6449  6449 E Zygote  : v2
08-12 11:11:06.056  6449  6449 I libpersona: KNOX_SDCARD checking this for 10004
08-12 11:11:06.056  6449  6449 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:06.056  6449  6449 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:06.056  6449  6449 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:06.056  6449  6449 E Zygote  : accessInfo : 0
08-12 11:11:06.056  6449  6449 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 11:11:06.056  6313  6313 D AndroidRuntime: Shutting down VM
08-12 11:11:06.076   293   293 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
08-12 11:11:06.076   764  1726 I ActivityManager: Killing 5096:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-12 11:11:06.086  6425  6425 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-12 11:11:06.086  5355  5355 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-12 11:11:06.086   764   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-12 11:11:06.086   764   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 11:11:06.086   764   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-12 11:11:06.086   764   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 11:11:06.086   764   906 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 11:11:06.096  6425  6463 D Mms/ArtClassLoader: init before art third
08-12 11:11:06.096  6425  6425 D Mms/TelephonyPermission: start operation mode monitor
08-12 11:11:06.096  6425  6425 D Mms/TelephonyPermission: User ID is null set current User Id
08-12 11:11:06.096  6425  6462 D Mms/ArtClassLoader: init before art second
08-12 11:11:06.106  1824  6400 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 344 ms] updated apps [took 344 ms] 
08-12 11:11:06.106  6449  6449 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:06.106  6449  6449 D ActivityThread: Added TimaKeyStore provider
08-12 11:11:06.106   764  1275 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-12 11:11:06.106  6425  6461 D Mms/ArtClassLoader: init before art first
08-12 11:11:06.106  6425  6463 D Mms/ArtClassLoader: init [DONE] art
08-12 11:11:06.106  6425  6425 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-12 11:11:06.116  6425  6425 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-12 11:11:06.126   764   906 V WindowStateAnimator: Finishing drawing window Window{2f2dda8 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 11:11:06.126   764  1465 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 11:11:06.126   764  1465 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 11:11:06.126   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
08-12 11:11:06.146   764   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2f2dda8 u0 d0 Starting com.test.thalitest}
08-12 11:11:06.146  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 11:11:06.146  1713  1870 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 11:11:06.146  1713  1713 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 11:11:06.146   764  1465 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 11:11:06.156   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-12 11:11:06.166   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-12 11:11:06.166   764  3428 D SSRM:n  : SIOP:: AP = 480, PST = 452, CUR = 450, LCD = 0
08-12 11:11:06.176   293  1295 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-12 11:11:06.176   293  1939 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-12 11:11:06.176   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
08-12 11:11:06.176  1713  1713 V ActivityThread: updateVisibility : ActivityRecord{5c64e8e token=android.os.BinderProxy@92c60ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 11:11:06.176  1713  1713 D Launcher: onTrimMemory. Level: 20
08-12 11:11:06.186  2325  2336 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 11:11:06.206   764   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-12 11:11:06.206   764  3428 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 11:11:06.216  6449  6449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 11:11:06.216  6425  6425 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-12 11:11:06.216  6425  6425 D Mms/TelephonyPermission: isDefault true
08-12 11:11:06.216  6425  6425 D Mms/MmsApp: onCreate() com.android.mms
08-12 11:11:06.226   764  3428 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 11:11:06.236  6449  6449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 11:11:06.266  6449  6449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 11:11:06.286  6449  6449 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 11:11:06.306  6425  6425 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 11:11:06.306  6449  6449 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 11:11:06.306  6425  6461 D Mms/ArtClassLoader: init [DONE] art
,08-12 11:11:06.326  6449  6449 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 11:11:06.336  6449  6449 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 618-622)
,08-12 11:11:06.336  6449  6449 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 11:11:06.346  6425  6425 D Mms/MmsApp: [start]    initCountryIso consume time = 257.532708
,08-12 11:11:06.346   764  1705 D CountryDetector: The first listener is added
,08-12 11:11:06.356  6449  6469 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 11:11:06.366  6425  6462 D Mms/ArtClassLoader: init [DONE] art
,08-12 11:11:06.366   764   774 I art     : Background partial concurrent mark sweep GC freed 56035(3MB) AllocSpace objects, 10(340KB) LOS objects, 27% free, 42MB/58MB, paused 2.031ms total 172.783ms
,08-12 11:11:06.366  6425  6425 D Mms/MmsApp: [end]    initCountryIso consume time = 25.960781
08-12 11:11:06.366  6425  6425 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.100885
,08-12 11:11:06.366  6449  6449 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a0c63c}
,08-12 11:11:06.366  6449  6449 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-12 11:11:06.366  6449  6449 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 11:11:06.376  6449  6449 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 11:11:06.406  6449  6449 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 11:11:06.406  6449  6449 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 11:11:06.406  6449  6449 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 11:11:06.406  6449  6449 I Adreno-EGL: Local Branch: ss
08-12 11:11:06.406  6449  6449 I Adreno-EGL: Remote Branch: 
08-12 11:11:06.406  6449  6449 I Adreno-EGL: Local Patches: 
08-12 11:11:06.406  6449  6449 I Adreno-EGL: Reconstruct Branch: 
,08-12 11:11:06.416  6449  6449 D libEGL  : eglInitialize EGLDisplay = 0xbeaccdac
,08-12 11:11:06.426  6425  6425 D Mms/MmsConfig: before partial update
,08-12 11:11:06.446   764  1687 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 11:11:06.446   764  1687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 11:11:06.446  6425  6425 D Mms/MmsConfig: Load Resize quality : 80
,08-12 11:11:06.456  6425  6425 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-12 11:11:06.456  6425  6425 D EasySignUpManager_1.0.5: isAuth is false
08-12 11:11:06.456  6425  6425 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 11:11:06.456  6425  6425 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 11:11:06.466  6425  6425 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 11:11:06.476  6425  6425 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 11:11:06.476  6425  6425 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 11:11:06.476  6425  6425 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 11:11:06.476  6425  6425 D EasySignUpManager_1.0.5: isAuth is false
08-12 11:11:06.476  6425  6425 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-12 11:11:06.476  6425  6425 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 11:11:06.486  1698  1712 D TP/MmsSmsProvider: query, match:2117, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.486  1698  1712 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.959 ms
,08-12 11:11:06.496  6425  6425 E CscParser: mps_code.dat does not exist
08-12 11:11:06.496  6425  6425 E CscParser: customer_path =/system/csc/customer.xml
08-12 11:11:06.496  6425  6425 E CscParser: fileName + /system/csc/customer.xml
,08-12 11:11:06.496  6449  6449 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 11:11:06.506  6425  6425 E CscParser: mps_code.dat does not exist
08-12 11:11:06.506  6425  6425 E CscParser: customer_path =/system/csc/customer.xml
08-12 11:11:06.506  6425  6425 E CscParser: fileName + /system/csc/customer.xml
,08-12 11:11:06.506  6449  6449 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 11:11:06.506  6449  6449 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 11:11:06.516  6449  6449 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 11:11:06.516  6449  6449 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 11:11:06.516  6425  6425 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 11:11:06.516  6425  6425 D Mms/MmsConfig:  enable multiwindow = true
,08-12 11:11:06.516  6425  6425 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 11:11:06.516  6425  6425 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-12 11:11:06.516  6425  6425 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-12 11:11:06.516  6425  6425 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-12 11:11:06.516  6425  6425 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-12 11:11:06.516  6425  6425 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-12 11:11:06.516  6425  6425 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 11:11:06.526  6425  6425 D Mms/MmsConfig: [end]    init() consume time = 154.833699
,08-12 11:11:06.526  6425  6425 D Mms/Contact: [start]    init() consume time = 4.759947
,08-12 11:11:06.526  6449  6449 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 11:11:06.536  6449  6449 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 11:11:06.546  6425  6425 D Mms/Contact: [end]    init consume time = 15.910469
,08-12 11:11:06.546  1698  2027 D TP/MmsSmsProvider: query, match:13, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.546  1698  2027 D TP/MmsSmsProvider: query, match 13:Elapsed time : 0.814 ms
,08-12 11:11:06.546  6425  6495 D Mms/DraftCache: [start]    rebuildCache consume time = 3.126354
,08-12 11:11:06.546  6425  6425 D Mms:transaction: roaming -> false (slotId = 0)
08-12 11:11:06.546  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 11:11:06.546  6425  6425 D Mms:transaction: auto download without roaming -> true
08-12 11:11:06.546  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-12 11:11:06.546  6425  6425 D Mms:transaction: roaming -> false (slotId = 1)
08-12 11:11:06.546  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-12 11:11:06.546  6425  6425 D Mms:transaction: auto download without roaming -> true
08-12 11:11:06.546  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 11:11:06.546  6425  6425 D Mms:transaction: auto download during roaming secondary -> false
08-12 11:11:06.546  6425  6425 D Mms:transaction: mAutoDownload ------> true
,08-12 11:11:06.556  1698  1710 D TP/MmsSmsProvider: query, match:12, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.556  1698  1710 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.039 ms
,08-12 11:11:06.566  6425  6425 D ComposerPerformance: 1470993066573 ms / [DONE] Composer constructor
,08-12 11:11:06.566  6425  6497 D Mms/Conversation: [start]    init() consume time = 19.70125
,08-12 11:11:06.566  6425  6425 D CII     : Log Level [5]
08-12 11:11:06.566  6425  6425 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-12 11:11:06.566  6425  6425 I Mms/ReservationManager: ReservationManager()
08-12 11:11:06.566  6425  6425 I Mms/ReservationManager: resetAfterConnected()
,08-12 11:11:06.596  1698  2441 D TP/MmsSmsProvider: delete, match:1, calling pid = 6425
08-12 11:11:06.596  1698  2441 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 11:11:06.596  1698  2441 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-12 11:11:06.596  1698  2441 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 11:11:06.596  1698  2441 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-12 11:11:06.596  1698  2441 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-12 11:11:06.596  6425  6495 D Mms/DraftCache: [end]    rebuildCache consume time = 30.818073
,08-12 11:11:06.596  1698  2441 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 11:11:06.606  1698  2027 D TP/MmsSmsProvider: query, match:7, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.606  1698  2027 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.214 ms
,08-12 11:11:06.606  1698  2441 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-12 11:11:06.606  1698  2441 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-12 11:11:06.606  1698  2441 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,08-12 11:11:06.606  1698  2441 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 4.532 ms
08-12 11:11:06.606  1698  2441 D TP/MmsSmsProvider: need read changed broadcast:false
08-12 11:11:06.606  6425  6497 D Mms/Conversation: [end]    init consume time = 12.300052
,08-12 11:11:06.616  6425  6425 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-12 11:11:06.616  6449  6449 D SecWifiDisplayUtil: Metadata value : none
,08-12 11:11:06.616  6449  6449 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{161907a I.E...... R.....ID 0,0-0,0}
,08-12 11:11:06.616  6425  6497 D Mms/MessagingNotification: [start]    init() consume time = 5.910052
,08-12 11:11:06.616  6425  6497 D Mms/MessagingNotification: [end]    init consume time = 2.064271
08-12 11:11:06.616  6425  6425 D Mms/MmsApp: [end]    onCreate() consume time = 0.018437
08-12 11:11:06.616  6425  6425 D Mms/MmsApp: [end]    onCreate() consume time = 0.148855
,08-12 11:11:06.616  6449  6501 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 11:11:06.626   764  2154 D ISSUE_DEBUG: InputChannelName : cc5b67f com.test.thalitest/com.test.thalitest.MainActivity
08-12 11:11:06.626  6425  6502 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.239896
08-12 11:11:06.626  6425  6503 D Mms/Synchronizer: [start]    doSync consume time = 1.279427
,08-12 11:11:06.626  6425  6425 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 11:11:06.626  6425  6425 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-12 11:11:06.636  6425  6425 D Mms:transaction: roaming -> false (slotId = 0)
,08-12 11:11:06.636  1698  2441 D TP/MmsSmsProvider: update, match:300, calling pid = 6425
08-12 11:11:06.636  1698  2441 V TP/MmsSmsProvider: syncDBData start
08-12 11:11:06.636  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 11:11:06.636  6425  6425 D Mms:transaction: auto download without roaming -> true
,08-12 11:11:06.636  1698  2441 V TP/MmsSmsProvider: syncDBData sms end
08-12 11:11:06.636  6425  6425 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 11:11:06.636  6425  6425 D Mms:transaction: mAutoDownload ------> true
08-12 11:11:06.636  1698  2441 V TP/MmsSmsProvider: syncDBData mms end
,08-12 11:11:06.636  1698  2441 V TP/MmsSmsProvider: syncDBData end
08-12 11:11:06.636  1698  2441 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.684 ms
,08-12 11:11:06.636  6504  6504 E Zygote  : v2
,08-12 11:11:06.636  1698  1712 D TP/MmsSmsProvider: query, match:0, calling pid = 6425, accessRestricted = false
08-12 11:11:06.636  1698  1712 V TP/MmsSmsProvider: getSimpleConversations entered.
08-12 11:11:06.646  6504  6504 I libpersona: KNOX_SDCARD checking this for 1000
,08-12 11:11:06.646  6504  6504 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:06.646  1698  2027 D TP/MmsSmsProvider: query, match:400, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.646  1698  1712 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.245 ms
08-12 11:11:06.646  6504  6504 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 11:11:06.646  6504  6504 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:06.646  6504  6504 E Zygote  : accessInfo : 0
,08-12 11:11:06.646   764  1551 I ActivityManager: Start proc 6504:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-12 11:11:06.656   764  2321 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-12 11:11:06.656   764  2321 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 11:11:06.656   764   764 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 11:11:06.656   764   764 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 11:11:06.656  6425  6503 D Mms/Synchronizer: [end]    doSync consume time = 27.862812
,08-12 11:11:06.656  6425  6502 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 3.486354
,08-12 11:11:06.656  6189  6211 D BadgeProvider: query, [selection] : package=?
,08-12 11:11:06.666  6425  6497 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 11:11:06.676  6449  6449 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6449
,08-12 11:11:06.686   764   778 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6449 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 11:11:06.686  1698  1712 D TP/SmsProvider: query,matched:26, calling pid = 6425
,08-12 11:11:06.686   764  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 11:11:06.686   764  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 11:11:06.686   764  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 11:11:06.686  1698  1712 D TP/SmsProvider: query, match 26:Elapsed time : 5.243 ms
,08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 11:11:06.686   764  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-12 11:11:06.686   764  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 11:11:06.696   764  1705 I ActivityManager: Killing 5179:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 11:11:06.696  6504  6504 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 11:11:06.696  6504  6504 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:06.696  6449  6469 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 11:11:06.696  6449  6449 D SecWifiDisplayUtil: Metadata value : none
,08-12 11:11:06.706   764  2149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6002076 6504:com.samsung.android.bbc.bbcagent/1000}
,08-12 11:11:06.706   293   293 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,08-12 11:11:06.716  6504  6504 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 11:11:06.726   764  1727 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 11:11:06.726   764  2220 D InputDispatcher: Focus entered window: 6449
,08-12 11:11:06.726   764   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-12 11:11:06.726   764   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 11:11:06.726   764   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-12 11:11:06.726   764   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 11:11:06.736  6449  6501 D libEGL  : eglInitialize EGLDisplay = 0x9ca3c7c4
08-12 11:11:06.736  6449  6501 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 11:11:06.736  1698  2441 D TP/MmsSmsProvider: query, match:6, calling pid = 6425, accessRestricted = false
,08-12 11:11:06.736  1698  2441 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.187 ms
,08-12 11:11:06.736  6504  6504 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 11:11:06.756  6520  6520 E Zygote  : v2
08-12 11:11:06.756  6520  6520 I libpersona: KNOX_SDCARD checking this for 10024
08-12 11:11:06.756  6520  6520 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:06.756   764  1465 I ActivityManager: Start proc 6520:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-12 11:11:06.756  6520  6520 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:06.756  6520  6520 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:06.756  6520  6520 E Zygote  : accessInfo : 0
08-12 11:11:06.756  6520  6520 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-12 11:11:06.786  6449  6449 V ActivityThread: updateVisibility : ActivityRecord{eaec35d token=android.os.BinderProxy@bbfa4a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 11:11:06.786   764  1467 I ActivityManager: Start proc 6532:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-12 11:11:06.786  6532  6532 E Zygote  : v2
08-12 11:11:06.786  6532  6532 I libpersona: KNOX_SDCARD checking this for 10097
08-12 11:11:06.786  6532  6532 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:06.786  6532  6532 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:06.786  6532  6532 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:06.796  6532  6532 E Zygote  : accessInfo : 0
,08-12 11:11:06.796  6532  6532 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 11:11:06.796   764  1467 I ActivityManager: Killing 4729:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-12 11:11:06.796  6520  6520 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:06.796  6520  6520 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:06.806   764  1275 I ActivityManager: Killing 5116:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 11:11:06.816  6449  6449 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 11:11:06.826  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 11:11:06.826  6532  6532 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:06.826  6520  6520 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 11:11:06.836   764  1726 V WindowStateAnimator: Finishing drawing window Window{cc5b67f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 11:11:06.836  6449  6449 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 11:11:06.836  6449  6449 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 11:11:06.836   764  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{935f677 6532:com.google.android.apps.docs/u0a97}
08-12 11:11:06.836   764  1275 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 11:11:06.846   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
,08-12 11:11:06.846   764   777 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 11:11:06.846  6449  6449 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 11:11:06.856  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 11:11:06.856   764   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 11:11:06.856   764   764 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 11:11:06.856   764   906 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +653ms (total +815ms)
,08-12 11:11:06.856   764   906 D ActivityManager: mDVFSHelper.release()
08-12 11:11:06.856   764   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{295f224 u0 com.test.thalitest/.MainActivity t163} time:101145
,08-12 11:11:06.856   764   764 I KnoxTimeoutHandler: SD activityfalse
,08-12 11:11:06.856   764   906 D ViewRootImpl: #3 mView = null
,08-12 11:11:06.866   293   362 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,08-12 11:11:06.866   293  1295 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,08-12 11:11:06.866   764  1275 V WindowStateAnimator: Finishing drawing window Window{cc5b67f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-12 11:11:06.876  6449  6449 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bbfa4a5 time:101163
,08-12 11:11:06.876   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
,08-12 11:11:06.876   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
,08-12 11:11:06.886  6449  6547 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:11:06.886  6449  6547 D libEGL  : eglInitialize EGLDisplay = 0x9a7ea3ec
,08-12 11:11:06.896  6532  6532 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 11:11:06.896  6520  6520 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 11:11:06.906   764  1687 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 11:11:06.926  6449  6449 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6449
,08-12 11:11:06.946  6520  6520 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 11:11:06.956  6425  6497 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 11:11:06.986  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 11:11:06.996  6520  6520 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 11:11:07.006   764  6147 I HarmonyEASService: Updating for all 1
,08-12 11:11:07.036  6449  6449 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 11:11:07.086  2811  4933 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 11:11:07.116  2811  4933 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 11:11:07.196  2811  4933 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 11:11:07.196  6449  6552 D jxcore_app_log: JniHelper::setJavaVM(0xb483c000), pthread_self() = -1711015632
,08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 11:11:07.206  6449  6552 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9492a1b added. We now have 1 listener(s)
,08-12 11:11:07.206  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 11:11:07.206   764  3429 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 11:11:07.206  6449  6552 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 11:11:07.206  6449  6552 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 11:11:07.206  6449  6552 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 11:11:07.216  6449  6552 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9c0f6 added. We now have 1 listener(s)
08-12 11:11:07.216  6449  6552 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:11:07.216  6449  6552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 11:11:07.226  6449  6552 D BluetoothAdapter: STATE_ON
,08-12 11:11:07.226  6449  6552 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:11:07.226  6449  6552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:11:07.226  6449  6552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 11:11:07.226  6449  6552 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 11:11:07.226  6449  6552 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 11:11:07.226  6449  6449 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:11:07.226  6449  6449 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:11:07.256  6449  6449 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 11:11:07.276  6532  6556 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 11:11:07.276  6532  6556 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 11:11:07.276  6532  6556 I GAv4    :   adb logcat -s GAv4
,08-12 11:11:07.296  6532  6556 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 11:11:07.296   764   778 V AlarmManager:  remove PendingIntent] PendingIntent{d4b1b5a: PendingIntentRecord{cec418b com.google.android.apps.docs broadcastIntent}}
,08-12 11:11:07.296  6532  6556 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 11:11:07.306  6532  6556 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 11:11:07.326  6532  6562 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 11:11:07.406  6532  6532 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 11:11:07.406  6532  6532 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 11:11:07.426  6532  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-12 11:11:07.426  6532  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-12 11:11:07.426  6532  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-12 11:11:07.426  6532  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 11:11:07.476  6568  6568 E Zygote  : v2
08-12 11:11:07.476  6568  6568 I libpersona: KNOX_SDCARD checking this for 10098
08-12 11:11:07.476  6568  6568 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:07.476  6568  6568 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:07.476   764  1726 I ActivityManager: Start proc 6568:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-12 11:11:07.476  6568  6568 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 11:11:07.476  6568  6568 E Zygote  : accessInfo : 0
08-12 11:11:07.476  6568  6568 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-12 11:11:07.476   764  1726 I ActivityManager: Killing 5639:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-12 11:11:07.496   764  2223 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-12 11:11:07.506  6568  6568 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:07.506  6568  6568 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:07.506   764  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9db6b67 6568:com.sec.android.automotive.drivelink/u0a98}
,08-12 11:11:07.516  6568  6568 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 11:11:07.536  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 11:11:07.536  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 11:11:07.536  6568  6568 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 11:11:07.556  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 11:11:07.576  6568  6568 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 11:11:07.586   764  1705 V AlarmManager:  remove PendingIntent] PendingIntent{5e0605f: PendingIntentRecord{6602aac com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 11:11:07.586  6568  6584 I GMPM    : App measurement is starting up
,08-12 11:11:07.586  6568  6568 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-12 11:11:07.596  6568  6584 E GMPM    : getGoogleAppId failed with status: 10
,08-12 11:11:07.596  6568  6584 E GMPM    : Uploading is not possible. App measurement disabled
,08-12 11:11:07.596   764  1705 V AlarmManager:  remove PendingIntent] PendingIntent{fac375: PendingIntentRecord{6602aac com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 11:11:07.606  6532  6557 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 11:11:07.616  6568  6568 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 11:11:07.616  6568  6568 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 11:11:07.666  6590  6590 E Zygote  : v2
08-12 11:11:07.666  6590  6590 I libpersona: KNOX_SDCARD checking this for 10032
08-12 11:11:07.666  6590  6590 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:07.666  6590  6590 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:07.666  6590  6590 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:07.666  6590  6590 E Zygote  : accessInfo : 0
,08-12 11:11:07.666  6590  6590 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 11:11:07.676   764  1726 I ActivityManager: Start proc 6590:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-12 11:11:07.676   764  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 11:11:07.676  1446  1446 D Recents : onTaskStackChanged
,08-12 11:11:07.676  1446  1446 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 11:11:07.696  6532  6557 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 11:11:07.696  6590  6590 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:07.696  6590  6590 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:07.706   764  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 11:11:07.706  6590  6590 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 11:11:07.716  6532  6557 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-12 11:11:07.716  6532  6557 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 11:11:07.726  6590  6590 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-12 11:11:07.726  6532  6557 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 11:11:07.756  6532  6557 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 11:11:07.796  6568  6568 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 11:11:07.806  6568  6568 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 11:11:07.806  6568  6568 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-12 11:11:07.826  6568  6568 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 11:11:07 GMT+02:00 2016
,08-12 11:11:07.826  6568  6568 D DialogFlow: initQueue()
,08-12 11:11:07.836  6590  6590 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
08-12 11:11:07.836   764  2149 I ActivityManager: Start proc 6604:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-12 11:11:07.836  6604  6604 E Zygote  : v2
08-12 11:11:07.836  6604  6604 I libpersona: KNOX_SDCARD checking this for 1000
08-12 11:11:07.836  6604  6604 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:07.836  6604  6604 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:07.836  6604  6604 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:07.836   764  2149 I ActivityManager: Killing 5685:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-12 11:11:07.836   764  2149 I ActivityManager: Killing 5562:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 11:11:07.836  6604  6604 E Zygote  : accessInfo : 0
,08-12 11:11:07.866   764   777 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 11:11:07.876  6604  6604 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:07.876  6604  6604 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:07.876   764  1726 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 11:11:07.886   764  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2b2344 6604:com.samsung.android.app.filterinstaller/1000}
,08-12 11:11:07.886  6590  6590 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 11:11:07.896  6604  6604 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 11:11:07.906  6604  6604 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 11:11:07.916  6604  6604 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 11:11:07.926  6620  6620 E Zygote  : v2
08-12 11:11:07.926  6620  6620 I libpersona: KNOX_SDCARD checking this for 1000
08-12 11:11:07.926  6620  6620 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:07.936  6620  6620 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:07.936  6620  6620 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:07.936  6620  6620 E Zygote  : accessInfo : 0
08-12 11:11:07.936   764  1726 I ActivityManager: Start proc 6620:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-12 11:11:07.936   764  1726 I ActivityManager: Killing 5670:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 11:11:07.956   764  1727 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 11:11:07.956  6620  6620 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:07.956  6620  6620 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:07.966   764  2220 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 11:11:07.966   764  1275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b4ec2d 6620:com.samsung.helphub/1000}
,08-12 11:11:07.976  6620  6620 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 11:11:07.986  6590  6590 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 11:11:07.986  6590  6590 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 11:11:07.996  6620  6620 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 11:11:08.016  6590  6590 D DialogFlow: initQueue()
,08-12 11:11:08.016  6449  6553 W jxcore-log: Initializing JXcore engine
08-12 11:11:08.016  6449  6553 W jxcore-log: JXcore engine is ready
,08-12 11:11:08.086  2111  2111 E audit   : type=1400 msg=audit(1470993068.086:288): avc:  denied  { ioctl } for  pid=6553 comm="Thread-915" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 11:11:08.086  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.086  2111  2111 E audit   : type=1300 msg=audit(1470993068.086:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=984643c8 items=0 ppid=342 ppcomm=main pid=6553 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 11:11:08.086  2111  2111 E audit   : type=1327 msg=audit(1470993068.086:288): proctitle="com.test.thalitest"
08-12 11:11:08.086  2111  2111 E audit   : type=1320 msg=audit(1470993068.086:288): 
08-12 11:11:08.086  2111  2111 E audit   : type=1400 msg=audit(1470993068.086:289): avc:  denied  { ioctl } for  pid=6553 comm="Thread-915" path="socket:[41079]" dev="sockfs" ino=41079 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 11:11:08.086  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.086  2111  2111 E audit   : type=1300 msg=audit(1470993068.086:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=984643c8 items=0 ppid=342 ppcomm=main pid=6553 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 11:11:08.086  2111  2111 E audit   : type=1327 msg=audit(1470993068.086:289): proctitle="com.test.thalitest"
08-12 11:11:08.086  2111  2111 E audit   : type=1320 msg=audit(1470993068.086:289): 
,08-12 11:11:08.096  6633  6633 E Zygote  : v2
08-12 11:11:08.096  6633  6633 I libpersona: KNOX_SDCARD checking this for 1000
08-12 11:11:08.096  6633  6633 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:08.096   764  1467 I ActivityManager: Start proc 6633:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-12 11:11:08.096  6633  6633 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:08.096  6633  6633 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.096  6449  6553 W jxcore-log: Starting JXcore engine
08-12 11:11:08.096   764  1467 I ActivityManager: Killing 4219:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 11:11:08.096  6633  6633 E Zygote  : accessInfo : 0
,08-12 11:11:08.116  6633  6633 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:08.116  6633  6633 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:08.126   764  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31996dc 6633:com.samsung.android.app.mirrorlink/1000}
,08-12 11:11:08.136   764   778 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 11:11:08.136  6633  6633 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 11:11:08.156  6633  6633 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 11:11:08.186  6633  6633 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-12 11:11:08.186  6633  6633 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 11:11:08.186  6449  6553 W jxcore-log: Platform android
08-12 11:11:08.186  6449  6553 W jxcore-log: 
,08-12 11:11:08.186  6449  6553 W jxcore-log: Process ARCH arm
08-12 11:11:08.186  6449  6553 W jxcore-log: 
,08-12 11:11:08.186   764  2149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9b37b6 5698:com.google.android.apps.plus/u0a134}
,08-12 11:11:08.216   764  1275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9b37b6 5698:com.google.android.apps.plus/u0a134}
,08-12 11:11:08.226   764  2321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9b37b6 5698:com.google.android.apps.plus/u0a134}
,08-12 11:11:08.256   764  1705 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 11:11:08.256   764  1687 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 11:11:08.266   764  1465 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 11:11:08.266   764  2321 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 11:11:08.266   764  2149 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 11:11:08.266   764   777 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 11:11:08.276   764  2220 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 11:11:08.276   764  2223 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 11:11:08.306   764  1465 I ActivityManager: Start proc 6647:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-12 11:11:08.306  6647  6647 E Zygote  : v2
08-12 11:11:08.306  6647  6647 I libpersona: KNOX_SDCARD checking this for 10165
08-12 11:11:08.306  6647  6647 I libpersona: KNOX_SDCARD not a persona
,08-12 11:11:08.306  6647  6647 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 11:11:08.306  6647  6647 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.306  6647  6647 E Zygote  : accessInfo : 0
,08-12 11:11:08.306  6647  6647 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 11:11:08.316   764  1465 I ActivityManager: Killing 5718:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-12 11:11:08.326   764  1727 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-12 11:11:08.336  6647  6647 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 11:11:08.336  6647  6647 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:08.346   764  1551 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c51616b 6647:com.sec.kidsplat.installer/u0a165}
,08-12 11:11:08.356  6647  6647 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 11:11:08.366  6449  6553 I jxcore-log: JXcore Cordova bridge is ready!
08-12 11:11:08.366  6449  6553 I jxcore-log: 
,08-12 11:11:08.366  6449  6553 W jxcore-log: JXcore engine is started
,08-12 11:11:08.366  6647  6647 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
08-12 11:11:08.366  6449  6552 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 11:11:08.366  6449  6449 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 11:11:08.376   764  2149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c51616b 6647:com.sec.kidsplat.installer/u0a165}
,08-12 11:11:08.376  6647  6647 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 11:11:08.396  6659  6659 E Zygote  : v2
08-12 11:11:08.396  6659  6659 I libpersona: KNOX_SDCARD checking this for 10142
08-12 11:11:08.396  6659  6659 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 11:11:08.396  6659  6659 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:08.396   764  1723 I ActivityManager: Start proc 6659:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 11:11:08.396   764  1321 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 11:11:08.396  6659  6659 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:08.396  6659  6659 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.396   764  1723 I ActivityManager: Killing 5788:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 11:11:08.396  6659  6659 E Zygote  : accessInfo : 64
08-12 11:11:08.396  6659  6659 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 11:11:08.396  6659  6659 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-12 11:11:08.396  6659  6659 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 11:11:08.396   764  1321 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-12 11:11:08.416  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 11:11:08.416  6659  6659 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:08.426   764  2154 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1744c8 6659:com.sec.android.app.sbrowser/u0a142}
,08-12 11:11:08.426   764  1705 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 11:11:08.436  6659  6659 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 11:11:08.446  6659  6659 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 11:11:08.496  6659  6659 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 11:11:08.506  6659  6659 D ManifestProvider: onCreate()
,08-12 11:11:08.516  6659  6659 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-12 11:11:08.516  6659  6659 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 11:11:08.516  6659  6659 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 11:11:08.526  6659  6659 I SBrowserUtils: getSystemProperty of countryiso_code : PL
08-12 11:11:08.526  6659  6659 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 11:11:08.526  6659  6659 D [MM]MHDataBaseProvider: onCreate()
,08-12 11:11:08.546  6659  6659 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@c76b341)
,08-12 11:11:08.566   764  2154 I ActivityManager: Killing 5925:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
,08-12 11:11:08.566   764  2154 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfa78f8 2045:com.google.android.gms.persistent/u0a11}
,08-12 11:11:08.576   764  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19e99ab 2811:com.google.android.gms/u0a11}
,08-12 11:11:08.576  2811  6674 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 11:11:08.586  2811  6673 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 11:11:08.586  2811  6674 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 11:11:08.606  2811  2811 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 11:11:08.606   764  2149 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,08-12 11:11:08.616  2811  6674 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 11:11:08.616  2811  6674 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 11:11:08.626   764  2321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfa78f8 2045:com.google.android.gms.persistent/u0a11}
,08-12 11:11:08.646   764  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19e99ab 2811:com.google.android.gms/u0a11}
,08-12 11:11:08.656  2811  5043 D nzm     : Processing package: com.test.thalitest
,08-12 11:11:08.656  6425  6425 I Mms/MmsApp:  start initViewCache mms
,08-12 11:11:08.656  2811  2811 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 11:11:08.716  2811  5043 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-12 11:11:08.716  2811  5043 D nzm     : Found info for package com.test.thalitest in db.
,08-12 11:11:08.816   764   774 I art     : Background partial concurrent mark sweep GC freed 24746(1589KB) AllocSpace objects, 2(40KB) LOS objects, 27% free, 41MB/57MB, paused 1.640ms total 147.993ms
,08-12 11:11:08.816   764  2220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{801b220 5737:com.android.vending/u0a29}
,08-12 11:11:08.836  6590  6618 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 11:11:08.836  6590  6618 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 11:11:08.866   764  2321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8a1d2bd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{918877c 6228:com.sec.android.app.samsungapps/u0a39}
,08-12 11:11:08.886  6680  6680 E Zygote  : v2
08-12 11:11:08.886  6680  6680 I libpersona: KNOX_SDCARD checking this for 10034
08-12 11:11:08.886  6680  6680 I libpersona: KNOX_SDCARD not a persona
08-12 11:11:08.886   764  1234 V AlarmManager: Expired Alarm result :8
,08-12 11:11:08.896   764  2149 I ActivityManager: Start proc 6680:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 11:11:08.896  6680  6680 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 11:11:08.896  6680  6680 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:08.896  6680  6680 E Zygote  : accessInfo : 0
,08-12 11:11:08.896  6680  6680 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-12 11:11:08.906   764  1465 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 11:11:08.906   764  1465 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4226, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 11:11:08.906   764  1465 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 11:11:08.906   764  1465 D BatteryService: stay LED for charging
08-12 11:11:08.906   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 11:11:08.916  5737  5737 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-12 11:11:08.916   764   764 I MotionRecognitionService: Plugged
08-12 11:11:08.916   764   764 D MotionRecognitionService:   cableConnection= 1
08-12 11:11:08.916   764   764 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 11:11:08.916   764   764 D MotionRecognitionService: skip setTransmitPower. 
,08-12 11:11:08.916  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 11:11:08.916  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 11:11:08.916  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 11:11:08.926  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 11:11:08.926  2105  2105 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 11:11:08.926  2105  2657 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 11:11:08.926  6590  6618 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 11:11:08.926  6590  6618 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 11:11:08.926  6590  6618 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-12 11:11:08.936  6680  6680 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 11:11:08.936  6680  6680 D ActivityThread: Added TimaKeyStore provider
,08-12 11:11:08.936  6590  6618 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 11:11:08.936  6590  6618 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 11:11:08.936  2045  2045 D WearableService: callingUid 10011, callindPid: 2045
,08-12 11:11:08.936  5737  5737 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-12 11:11:08.946  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 11:11:08.946  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 11:11:08.946   764  1705 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e827237 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9e193a4 6680:com.sec.android.app.shealth/u0a34}
,08-12 11:11:08.946  6680  6680 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-12 11:11:08.966  5737  5737 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-12 11:11:08.966  5737  5737 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-12 11:11:08.976  6680  6680 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-12 11:11:08.986  6680  6680 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 11:11:08.986  6680  6680 I MultiDex: install
,08-12 11:11:08.986  6680  6680 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 11:11:08.986  6680  6680 I MultiDex: install
08-12 11:11:08.986  6680  6680 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 11:11:09.106   764  1726 I ActivityManager: Killing 5470:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 11:11:09.106   764  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/163_task.xml.bak
,08-12 11:11:09.116   764  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e827237 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bac7f4b 1855:com.sec.android.app.shealth:remote/u0a34}
,08-12 11:11:09.116  6680  6680 D HealthDataStore: Service for HealthDataStore is connected
,08-12 11:11:09.126  6680  6680 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-12 11:11:09.126   764  2220 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 11:11:09.136  6680  6680 D HealthConsole: Service for HealthDataConsole is connected
,08-12 11:11:09.136   764  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e827237 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bac7f4b 1855:com.sec.android.app.shealth:remote/u0a34}
,08-12 11:11:09.146  6680  6680 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-12 11:11:09.146  6680  6680 E HealthDataStore: disconnectService: Context instance is invalid
,08-12 11:11:09.156   764  1275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fe7712f u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfa78f8 2045:com.google.android.gms.persistent/u0a11}
,08-12 11:11:09.176  6425  6425 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 11:11:09.386  2811  6679 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 11:11:09.976  2811  4954 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-12 11:11:10.066  2811  4954 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 11:11:10.076  2811  4954 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 11:11:10.076  2811  4954 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 11:11:10.896   764  3468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 11:11:11.206  6228  6228 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,08-12 11:11:11.206  6228  6228 D PreloadUpdateManagerStateMachine: exit::IDLE
,08-12 11:11:11.206  6228  6228 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-12 11:11:11.216  6228  6228 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,08-12 11:11:11.216  6228  6228 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,08-12 11:11:11.226  6228  6228 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,08-12 11:11:11.226  6228  6228 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,08-12 11:11:11.226  6228  6228 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-12 11:11:12.236   764  3428 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 11:11:12.626  3505  3505 D FactoryTest: User mode
08-12 11:11:12.626  3505  3505 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-12 11:11:12.626  3505  3505 D MTPRx   : still no open session command from host, so toast
08-12 11:11:12.626   764   778 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-12 11:11:12.636   764   778 D ActivityManager: mDVFSHelper.acquire()
08-12 11:11:12.636   764   778 V WindowManager: addAppToken: AppWindowToken{c1e5727 token=Token{b9fd5e6 ActivityRecord{3172c41 u0 com.samsung.android.MtpApplication/.USBConnection t164}}} to stack=1 task=164 at 0
08-12 11:11:12.636   764   778 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
08-12 11:11:12.646   764   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-12 11:11:12.666   764   778 D InputDispatcher: Focused application set to: xxxx
08-12 11:11:12.666   764   778 D InputDispatcher: Focus left window: 6449
08-12 11:11:12.666   764   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-12 11:11:12.666   764   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 11:11:12.666   764   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-12 11:11:12.666   764   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 11:11:12.676  3505  3505 E MTPRx   : started activity for popup
08-12 11:11:12.676  3505  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 11:11:12.676  3505  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 11:11:12.686  3505  3505 D MTPUSBConnection: onCreate in USBConnection
08-12 11:11:12.696  3505  3505 V MTPUSBConnection: Registering broadcast receiver.
08-12 11:11:12.696  3505  3505 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
08-12 11:11:12.696   764  1705 D SecContentProvider2: query(), uri = 14 selection = getSealedState
08-12 11:11:12.706   764  3428 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 11:11:12.746  3505  3505 D TAG     : dev.kiessupport is : TRUE
08-12 11:11:12.776  3505  3505 D SecWifiDisplayUtil: Metadata value : none
08-12 11:11:12.776  3505  3505 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bc34ad5 V.E...... R.....I. 0,0-0,0}
08-12 11:11:12.776  3505  6720 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 11:11:12.776   764  1465 D ISSUE_DEBUG: InputChannelName : 9d041f com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 11:11:12.786   764   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9d041f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-12 11:11:12.786   764  1465 D InputDispatcher: Focus entered window: 3505
08-12 11:11:12.786  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-12 11:11:12.786   764   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-12 11:11:12.786   764   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 11:11:12.786   764   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-12 11:11:12.786   764   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 11:11:12.786  3505  3505 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{45aff8d I.E...... R.....I. 0,0-0,0}
08-12 11:11:12.796   764  2149 D ISSUE_DEBUG: InputChannelName : 25b6d35 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 11:11:12.796   764  2154 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 11:11:12.796   764  2154 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 11:11:12.796   764   764 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 11:11:12.796   764   764 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 11:11:12.796   764   764 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 11:11:12.826   293   293 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,08-12 11:11:12.836  3505  6720 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 11:11:12.836  3505  6720 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 11:11:12.836  3505  6720 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 11:11:12.836  3505  6720 I Adreno-EGL: Local Branch: ss
08-12 11:11:12.836  3505  6720 I Adreno-EGL: Remote Branch: 
08-12 11:11:12.836  3505  6720 I Adreno-EGL: Local Patches: 
08-12 11:11:12.836  3505  6720 I Adreno-EGL: Reconstruct Branch: 
,08-12 11:11:12.846  3505  6720 D libEGL  : eglInitialize EGLDisplay = 0x9efac7c4
08-12 11:11:12.846  3505  6720 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 11:11:12.886   293   293 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,08-12 11:11:12.906  3505  3505 V ActivityThread: updateVisibility : ActivityRecord{6df6290 token=android.os.BinderProxy@8b1f2ea {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 11:11:12.916  3505  3505 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 11:11:13.006   764  2223 V WindowStateAnimator: Finishing drawing window Window{9d041f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 11:11:13.006  3505  3505 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 11:11:13.006   764  1465 V WindowStateAnimator: Finishing drawing window Window{25b6d35 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 11:11:13.006  3505  3505 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 11:11:13.006  3505  3505 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-12 11:11:13.016   764   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 11:11:13.016   764   764 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 11:11:13.016   764   906 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +355ms (total +378ms)
,08-12 11:11:13.016   764   764 I KnoxTimeoutHandler: SD activityfalse
,08-12 11:11:13.016   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
,08-12 11:11:13.016   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
,08-12 11:11:13.016   764  1467 V WindowStateAnimator: Finishing drawing window Window{9d041f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-12 11:11:13.016   764   906 D ActivityManager: mDVFSHelper.release()
08-12 11:11:13.016   764   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3172c41 u0 com.samsung.android.MtpApplication/.USBConnection t164} time:107307
08-12 11:11:13.016   764  1275 V WindowStateAnimator: Finishing drawing window Window{25b6d35 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-12 11:11:13.016  3505  3505 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8b1f2ea time:107308
,08-12 11:11:13.036   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbea1e364
,08-12 11:11:13.676   764  3429 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 11:11:13.796  1446  1446 D Recents : onTaskStackChanged
,08-12 11:11:13.806  1446  1446 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 11:11:15.626   764   943 D PackageManager: [MSG] MCS_UNBIND
,08-12 11:11:15.636   764  1727 I ActivityManager: Killing 5355:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 11:11:15.666   764  1726 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 11:11:15.666  6414  6414 D AASAservice: onDestroy()
,08-12 11:11:15.666  6414  6414 I art     : System.exit called, status: 80
,08-12 11:11:15.666  6414  6414 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 11:11:15.686   764  2220 I ActivityManager: Process com.samsung.aasaservice (pid 6414)(adj 0) has died(75,747)
,08-12 11:11:15.686   764  2220 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 11:11:15.706   342   342 I Zygote  : Process 6414 exited cleanly (80)
,08-12 11:11:15.896   764  3468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 11:11:16.076   764   943 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 11:11:16.106   764   943 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 11:11:16.276   764  3428 D SSRM:n  : SIOP:: AP = 470, PST = 454, CUR = 450, LCD = 0
,08-12 11:11:17.676   304  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 11:11:17.676   304  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 11:11:17.676   304  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 11:11:18.716   764  3428 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 11:11:18.886  6449  6553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:11:18.886  6449  6553 I jxcore-log: 
,08-12 11:11:18.896  6449  6553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:11:18.896  6449  6553 I jxcore-log: 
,08-12 11:11:18.896  6449  6553 D BluetoothAdapter: STATE_ON
,08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:11:18.896  6449  6553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:11:18.906  6449  6553 D BluetoothAdapter: STATE_ON
,08-12 11:11:18.906  6449  6553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:11:18.906  6449  6553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:11:18.906  6449  6553 I jxcore-log: 
,08-12 11:11:18.906  6449  6553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:11:18.906  6449  6553 I jxcore-log: 
,08-12 11:11:19.256  6449  6553 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 11:11:19.256  6449  6553 I jxcore-log: Failed to execute UT.
08-12 11:11:19.256  6449  6553 I jxcore-log: 
08-12 11:11:19.256  6449  6553 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 11:11:19.256  6449  6553 I jxcore-log: 
,08-12 11:11:19.266  6449  6553 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:11:19.266  6449  6553 I jxcore-log: 
08-12 11:11:19.266  6449  6449 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 11:11:20.236  2111  2111 E audit   : type=1400 msg=audit(1470993080.236:290): avc:  denied  { execmod } for  pid=6731 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-12 11:11:20.246  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:20.246  2111  2111 E audit   : type=1300 msg=audit(1470993080.236:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f35000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6731 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 11:11:20.246  2111  2111 E audit   : type=1327 msg=audit(1470993080.236:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 11:11:20.246  2111  2111 E audit   : type=1320 msg=audit(1470993080.236:290): 
,08-12 11:11:20.296  2111  2111 E audit   : type=1400 msg=audit(1470993080.296:291): avc:  denied  { execmod } for  pid=6731 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 11:11:20.296  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:20.296  2111  2111 E audit   : type=1300 msg=audit(1470993080.296:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3efa000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6731 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 11:11:20.296  2111  2111 E audit   : type=1327 msg=audit(1470993080.296:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 11:11:20.296  2111  2111 E audit   : type=1320 msg=audit(1470993080.296:291): 
,08-12 11:11:20.336  2111  2111 E audit   : type=1400 msg=audit(1470993080.336:292): avc:  denied  { execmod } for  pid=6731 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 11:11:20.336  2111  2111 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 11:11:20.336  6731  6731 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 11:11:20.336  2111  2111 E audit   : type=1300 msg=audit(1470993080.336:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ef8000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6731 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 11:11:20.336  2111  2111 E audit   : type=1327 msg=audit(1470993080.336:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 11:11:20.336  2111  2111 E audit   : type=1320 msg=audit(1470993080.336:292): 
,08-12 11:11:20.346  6731  6731 D AndroidRuntime: CheckJNI is OFF
,08-12 11:11:20.346  6731  6731 D AndroidRuntime: readGMSProperty: start
08-12 11:11:20.346  6731  6731 D AndroidRuntime: readGMSProperty: already setted!!
08-12 11:11:20.346  6731  6731 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 11:11:20.346  6731  6731 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 11:11:20.346  6731  6731 D AndroidRuntime: readGMSProperty: end
08-12 11:11:20.346  6731  6731 D AndroidRuntime: addProductProperty: start
08-12 11:11:20.356  6731  6731 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 11:11:20.356  6731  6731 W art     : aed5c000-b1c82000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:20.356  6731  6731 W art     : b1c82000-b3ef1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:20.356  6731  6731 W art     : b3ef1000-b3ef2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 11:11:20.356  6731  6731 W art     : b3ef2000-b3ef3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.356  6731  6731 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 11:11:20.356  6731  6731 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 11:11:20.356  6731  6731 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 11:11:20.356  6731  6731 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 11:11:20.356  6731  6731 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-12 11:11:20.356  6731  6731 W art     : b47c7000-b47ca000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:20.356  6731  6731 W art     : b47ca000-b47cb000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:20.356  6731  6731 W art     : b47cb000-b47cc000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 11:11:20.356  6731  6731 W art     : b47cc000-b47cd000 r--p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b47cd000-b47ed000 r--s 00000000 00:0b 8200       /dev/__properties__
08-12 11:11:20.356  6731  6731 W art     : b47ed000-b51fe000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 11:11:20.356  6731  6731 W art     : b51fe000-b51ff000 ---p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b51ff000-b5248000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 11:11:20.356  6731  6731 W art     : b5248000-b5249000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-12 11:11:20.356  6731  6731 W art     : b5249000-b5251000 rw-p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b5251000-b5252000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.356  6731  6731 W art     : b5252000-b5287000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:20.356  6731  6731 W art     : b5287000-b5288000 ---p 00000000 00:00 0 
08-12 11:11:20.356  6731  6731 W art     : b5288000-b5289000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:20.366  6731  6731 W art     : b5289000-b528a000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 11:11:20.366  6731  6731 W art     : b528a000-b52e2000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-12 11:11:20.366  6731  6731 W art     : b52e2000-b52e3000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b52e3000-b52e4000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 11:11:20.366  6731  6731 W art     : b52e4000-b52e5000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 11:11:20.366  6731  6731 W art     : b52e6000-b52ec000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:20.366  6731  6731 W art     : b52ec000-b52ed000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:20.366  6731  6731 W art     : b52ed000-b52ee000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 11:11:20.366  6731  6731 W art     : b52ee000-b52f0000 rw-p 00000000 00:00 0 
,08-12 11:11:20.366  6731  6731 W art     : b52f1000-b52fb000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:20.366  6731  6731 W art     : b52fb000-b52fe000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:20.366  6731  6731 W art     : b52fe000-b52ff000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 11:11:20.366  6731  6731 W art     : b5300000-b5317000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 11:11:20.366  6731  6731 W art     : b5317000-b5318000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5318000-b5319000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 11:11:20.366  6731  6731 W art     : b5319000-b531a000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-12 11:11:20.366  6731  6731 W art     : b531b000-b5325000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:20.366  6731  6731 W art     : b5325000-b5326000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:20.366  6731  6731 W art     : b5326000-b5327000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 11:11:20.366  6731  6731 W art     : b5327000-b532b000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 11:11:20.366  6731  6731 W art     : b532b000-b532c000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 11:11:20.366  6731  6731 W art     : b532c000-b532d000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-12 11:11:20.366  6731  6731 W art     : b532d000-b5343000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:20.366  6731  6731 W art     : b5343000-b5344000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:20.366  6731  6731 W art     : b5344000-b5345000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 11:11:20.366  6731  6731 W art     : b5345000-b5352000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 11:11:20.366  6731  6731 W art     : b5352000-b5353000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 11:11:20.366  6731  6731 W art     : b5353000-b5354000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
,08-12 11:11:20.366  6731  6731 W art     : b5354000-b53b4000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 11:11:20.366  6731  6731 W art     : b53b4000-b53b7000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 11:11:20.366  6731  6731 W art     : b53b7000-b53bb000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b53bb000-b541c000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 11:11:20.366  6731  6731 W art     : b541c000-b541d000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
,08-12 11:11:20.366  6731  6731 W art     : b541d000-b546c000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 11:11:20.366  6731  6731 W art     : b546c000-b546e000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 11:11:20.366  6731  6731 W art     : b546e000-b546f000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 11:11:20.366  6731  6731 W art     : b546f000-b5470000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5470000-b5477000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:20.366  6731  6731 W art     : b5477000-b5478000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:20.366  6731  6731 W art     : b5478000-b5479000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 11:11:20.366  6731  6731 W art     : b547a000-b547d000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 11:11:20.366  6731  6731 W art     : b547d000-b547e000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 11:11:20.366  6731  6731 W art     : b547e000-b547f000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-12 11:11:20.366  6731  6731 W art     : b5480000-b5484000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:20.366  6731  6731 W art     : b5484000-b5485000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5485000-b5486000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:20.366  6731  6731 W art     : b5486000-b5487000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 11:11:20.366  6731  6731 W art     : b5488000-b54a5000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:20.366  6731  6731 W art     : b54a5000-b54a6000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:20.366  6731  6731 W art     : b54a6000-b54a7000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 11:11:20.366  6731  6731 W art     : b54a8000-b54ad000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 11:11:20.366  6731  6731 W art     : b54ad000-b54ae000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-12 11:11:20.366  6731  6731 W art     : b54ae000-b54af000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 11:11:20.366  6731  6731 W art     : b54b0000-b54e1000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:20.366  6731  6731 W art     : b54e1000-b54e4000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:20.366  6731  6731 W art     : b54e4000-b54e5000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 11:11:20.366  6731  6731 W art     : b54e6000-b5521000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 11:11:20.366  6731  6731 W art     : b5521000-b5522000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 11:11:20.366  6731  6731 W art     : b5522000-b5523000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 11:11:20.366  6731  6731 W art     : b5524000-b552b000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 11:11:20.366  6731  6731 W art     : b552b000-b552c000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b552c000-b552d000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
,08-12 11:11:20.366  6731  6731 W art     : b552d000-b552e000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 11:11:20.366  6731  6731 W art     : b552e000-b552f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b552f000-b5546000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:20.366  6731  6731 W art     : b5546000-b5547000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5547000-b554a000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:20.366  6731  6731 W art     : b554a000-b554b000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 11:11:20.366  6731  6731 W art     : b554b000-b556a000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 11:11:20.366  6731  6731 W art     : b556a000-b556b000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 11:11:20.366  6731  6731 W art     : b556b000-b556c000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
,08-12 11:11:20.366  6731  6731 W art     : b556c000-b55aa000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:20.366  6731  6731 W art     : b55aa000-b55ab000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b55ab000-b55ad000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:20.366  6731  6731 W art     : b55ad000-b55ae000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 11:11:20.366  6731  6731 W art     : b55af000-b55b6000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:20.366  6731  6731 W art     : b55b6000-b55b7000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:20.366  6731  6731 W art     : b55b7000-b55b8000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 11:11:20.366  6731  6731 W art     : b55b9000-b55bc000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 11:11:20.366  6731  6731 W art     : b55bc000-b55bd000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-12 11:11:20.366  6731  6731 W art     : b55bd000-b55be000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 11:11:20.366  6731  6731 W art     : b55be000-b55c4000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b55c4000-b55c5000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b55c5000-b55c6000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b55c6000-b55c7000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b55c7000-b55d0000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:20.366  6731  6731 W art     : b55d0000-b55d1000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:20.366  6731  6731 W art     : b55d1000-b55d2000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 11:11:20.366  6731  6731 W art     : b55d2000-b5663000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:20.366  6731  6731 W art     : b5663000-b5664000 ---p 00000000 00:00 0 
,08-12 11:11:20.366  6731  6731 W art     : b5664000-b566f000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:20.366  6731  6731 W art     : b566f000-b5670000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 11:11:20.366  6731  6731 W art     : b5671000-b5683000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:20.366  6731  6731 W art     : b5683000-b5684000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:20.366  6731  6731 W art     : b5684000-b5685000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 11:11:20.366  6731  6731 W art     : b5686000-b568b000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:20.366  6731  6731 W art     : b568b000-b568c000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:20.366  6731  6731 W art     : b568c000-b568d000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 11:11:20.366  6731  6731 W art     : b568e000-b56fb000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
,08-12 11:11:20.366  6731  6731 W art     : b56fb000-b56fc000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b56fc000-b56fe000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 11:11:20.366  6731  6731 W art     : b56fe000-b56ff000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 11:11:20.366  6731  6731 W art     : b56ff000-b5700000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b5700000-b5707000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:20.366  6731  6731 W art     : b5707000-b5708000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:20.366  6731  6731 W art     : b5708000-b5709000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 11:11:20.366  6731  6731 W art     : b570a000-b578a000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 11:11:20.366  6731  6731 W art     : b578a000-b578b000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b578b000-b578c000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
,08-12 11:11:20.366  6731  6731 W art     : b578c000-b578d000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 11:11:20.366  6731  6731 W art     : b578d000-b57a4000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b57a4000-b57db000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 11:11:20.366  6731  6731 W art     : ib/libqc-opt.so
08-12 11:11:20.366  6731  6731 W art     : b57db000-b57dc000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 11:11:20.366  6731  6731 W art     : b57dc000-b57dd000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 11:11:20.366  6731  6731 W art     : b57dd000-b57f9000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 11:11:20.366  6731  6731 W art     : b57f9000-b57fa000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 11:11:20.366  6731  6731 W art     : b57fa000-b57fb000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
,08-12 11:11:20.366  6731  6731 W art     : b57fc000-b585d000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:20.366  6731  6731 W art     : b585d000-b585f000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:20.366  6731  6731 W art     : b585f000-b5860000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 11:11:20.366  6731  6731 W art     : b5861000-b5888000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:20.366  6731  6731 W art     : b5888000-b5889000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5889000-b588a000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:20.366  6731  6731 W art     : b588a000-b588b000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 11:11:20.366  6731  6731 W art     : b588c000-b5894000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:20.366  6731  6731 W art     : b5894000-b5896000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:20.366  6731  6731 W art     : b5896000-b5897000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 11:11:20.366  6731  6731 W art     : b5898000-b589b000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:20.366  6731  6731 W art     : b589b000-b589c000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:20.366  6731  6731 W art     : b589c000-b589d000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 11:11:20.366  6731  6731 W art     : b589d000-b58a1000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:20.366  6731  6731 W art     : b58a1000-b58a2000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b58a2000-b58a3000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:20.366  6731  6731 W art     : b58a3000-b58a4000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 11:11:20.366  6731  6731 W art     : b58a4000-b58b4000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:20.366  6731  6731 W art     : b58b4000-b58b5000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:20.366  6731  6731 W art     : b58b5000-b58b6000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 11:11:20.366  6731  6731 W art     : b58b6000-b58fc000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b58fc000-b5905000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:20.366  6731  6731 W art     : b5905000-b5906000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:20.366  6731  6731 W art     : b5906000-b5907000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 11:11:20.366  6731  6731 W art     : b5908000-b590d000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:20.366  6731  6731 W art     : b590d000-b590e000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:20.366  6731  6731 W art     : b590e000-b590f000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 11:11:20.366  6731  6731 W art     : b590f000-b5912000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 11:11:20.366  6731  6731 W art     : b5912000-b5913000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5913000-b5914000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 11:11:20.366  6731  6731 W art     : b5914000-b5915000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-12 11:11:20.366  6731  6731 W art     : b5916000-b592e000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:20.366  6731  6731 W art     : b592e000-b592f000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b592f000-b5930000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:20.366  6731  6731 W art     : b5930000-b5931000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 11:11:20.366  6731  6731 W art     : b5932000-b5acc000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:20.366  6731  6731 W art     : b5acc000-b5acd000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5acd000-b5ada000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:20.366  6731  6731 W art     : b5ada000-b5adb000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 11:11:20.366  6731  6731 W art     : b5adb000-b5adf000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 11:11:20.366  6731  6731 W art     : b5adf000-b5ae0000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5ae0000-b5ae1000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 11:11:20.366  6731  6731 W art     : b5ae1000-b5ae2000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-12 11:11:20.366  6731  6731 W art     : b5ae2000-b5af5000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:20.366  6731  6731 W art     : b5af5000-b5af6000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:20.366  6731  6731 W art     : b5af6000-b5af7000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 11:11:20.366  6731  6731 W art     : b5af8000-b5b43000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:20.366  6731  6731 W art     : b5b43000-b5b44000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:20.366  6731  6731 W art     : b5b44000-b5b45000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 11:11:20.366  6731  6731 W art     : b5b45000-b5b47000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5b47000-b5b48000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:20.366  6731  6731 W art     : b5b48000-b5b59000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:20.366  6731  6731 W art     : b5b59000-b5b5a000 ---p 00000000 00:00 0 
,08-12 11:11:20.366  6731  6731 W art     : b5b5a000-b5b5b000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:20.366  6731  6731 W art     : b5b5b000-b5b5c000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 11:11:20.366  6731  6731 W art     : b5b5d000-b5b67000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:20.366  6731  6731 W art     : b5b67000-b5b69000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:20.366  6731  6731 W art     : b5b69000-b5b6a000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 11:11:20.366  6731  6731 W art     : b5b6a000-b5b83000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 11:11:20.366  6731  6731 W art     : b5b83000-b5b84000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
,08-12 11:11:20.366  6731  6731 W art     : b5b84000-b5b87000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 11:11:20.366  6731  6731 W art     : b5b87000-b5b8b000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5b8b000-b5bff000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:20.366  6731  6731 W art     : b5bff000-b5c00000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5c00000-b5c03000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:20.366  6731  6731 W art     : b5c03000-b5c04000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 11:11:20.366  6731  6731 W art     : b5c05000-b5c08000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 11:11:20.366  6731  6731 W art     : b5c08000-b5c09000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 11:11:20.366  6731  6731 W art     : b5c09000-b5c0a000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
,08-12 11:11:20.366  6731  6731 W art     : b5c0a000-b5c0b000 r--p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5c0b000-b5c10000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:20.366  6731  6731 W art     : b5c10000-b5c11000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:20.366  6731  6731 W art     : b5c11000-b5c12000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 11:11:20.366  6731  6731 W art     : b5c12000-b5c13000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b5c13000-b5c16000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:20.366  6731  6731 W art     : b5c16000-b5c17000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:20.366  6731  6731 W art     : b5c17000-b5c18000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 11:11:20.366  6731  6731 W art     : b5c18000-b5c19000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 11:11:20.366  6731  6731 W art     : b5c19000-b5c1d000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:20.366  6731  6731 W art     : b5c1d000-b5c1e000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:20.366  6731  6731 W art     : b5c1e000-b5c1f000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 11:11:20.366  6731  6731 W art     : b5c1f000-b5c20000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:20.366  6731  6731 W art     : b5c20000-b5c24000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 11:11:20.366  6731  6731 W art     : b5c24000-b5c25000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 11:11:20.366  6731  6731 W art     : b5c25000-b5c26000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 11:11:20.366  6731  6731 W art     : b5c26000-b5c27000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b5c27000-b5c35000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
,08-12 11:11:20.366  6731  6731 W art     : b5c35000-b5c36000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b5c36000-b5c37000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 11:11:20.366  6731  6731 W art     : b5c37000-b5c38000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 11:11:20.366  6731  6731 W art     : b5c38000-b5c42000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:20.366  6731  6731 W art     : b5c42000-b5c45000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:20.366  6731  6731 W art     : b5c45000-b5c46000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 11:11:20.366  6731  6731 W art     : b5c46000-b5c47000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b5c47000-b5c51000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 11:11:20.366  6731  6731 W art     : b5c51000-b5c54000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
,08-12 11:11:20.366  6731  6731 W art     : b5c54000-b5c55000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 11:11:20.366  6731  6731 W art     : b5c55000-b5c59000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:20.366  6731  6731 W art     : b5c59000-b5c5a000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:20.366  6731  6731 W art     : b5c5a000-b5c5b000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 11:11:20.366  6731  6731 W art     : b5c5b000-b5c5c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b5c5c000-b5c69000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:20.366  6731  6731 W art     : b5c69000-b5c6b000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:20.366  6731  6731 W art     : b5c6b000-b5c6c000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 11:11:20.366  6731  6731 W art     : b5c6c000-b607e000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
,08-12 11:11:20.366  6731  6731 W art     : b607e000-b607f000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b607f000-b6088000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 11:11:20.366  6731  6731 W art     : b6088000-b608c000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 11:11:20.366  6731  6731 W art     : b608c000-b608d000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b608d000-b6094000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-12 11:11:20.366  6731  6731 W art     : ioutils.so
08-12 11:11:20.366  6731  6731 W art     : b6094000-b6095000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 11:11:20.366  6731  6731 W art     : b6095000-b6096000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 11:11:20.366  6731  6731 W art     : b6096000-b6097000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 11:11:20.366  6731  6731 W art     : b6097000-b60b2000 r-xp 00000000
08-12 11:11:20.366  6731  6731 W art     :  b3:17 1184       /system/lib/libz.so
08-12 11:11:20.366  6731  6731 W art     : b60b2000-b60b3000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 11:11:20.366  6731  6731 W art     : b60b3000-b60b4000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 11:11:20.366  6731  6731 W art     : b60b4000-b60b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b60b5000-b6101000 r-xp 00000000 b3:17 994        
08-12 11:11:20.366  6731  6731 W art     : /system/lib/libharfbuzz_ng.so
08-12 11:11:20.366  6731  6731 W art     : b6101000-b6102000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6102000-b6103000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
,08-12 11:11:20.366  6731  6731 W art     : b6103000-b6104000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 11:11:20.366  6731  6731 W art     : b6104000-b6105000 r--p 00000000 00:00 0          [anon:li
08-12 11:11:20.366  6731  6731 W art     : nker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b6105000-b6109000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 11:11:20.366  6731  6731 W art     : b6109000-b610a000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b610a000-b610b000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 11:11:20.366  6731  6731 W art     : b610b000-b610c000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-12 11:11:20.366  6731  6731 W art     : sbhost.so
08-12 11:11:20.366  6731  6731 W art     : b610c000-b6144000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
,08-12 11:11:20.366  6731  6731 W art     : b6144000-b6145000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 11:11:20.366  6731  6731 W art     : b6145000-b6146000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 11:11:20.366  6731  6731 W art     : b6146000-b6147000 r--p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     :          [anon:linker_alloc]
08-12 11:11:20.366  6731  6731 W art     : b6147000-b61e5000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 11:11:20.366  6731  6731 W art     : b61e5000-b61e6000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b61e6000-b6204000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 11:11:20.366  6731  6731 W art     : b6204000-b6205000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-12 11:11:20.366  6731  6731 W art     : .so
,08-12 11:11:20.366  6731  6731 W art     : b6205000-b6378000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:20.366  6731  6731 W art     : b6378000-b6383000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:20.366  6731  6731 W art     : b6383000-b6384000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 11:11:20.366  6731  6731 W art     : b6384000-b649b000 r-xp 00000000
08-12 11:11:20.366  6731  6731 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:20.366  6731  6731 W art     : b649b000-b64a6000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:20.366  6731  6731 W art     : b64a6000-b64a7000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 11:11:20.366  6731  6731 W art     : b64a7000-b64ab000 rw-p 00000000 00:00 0 
,08-12 11:11:20.366  6731  6731 W art     : b64ab000-b64cf000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-12 11:11:20.366  6731  6731 W art     : o
08-12 11:11:20.366  6731  6731 W art     : b64cf000-b64d1000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 11:11:20.366  6731  6731 W art     : b64d1000-b64d2000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 11:11:20.366  6731  6731 W art     : b64d2000-b6578000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 11:11:20.366  6731  6731 W art     : b6578000-b6585000 r--p 000a5000 b3:17 13
08-12 11:11:20.366  6731  6731 W art     : 2        /system/lib/libcrypto.so
08-12 11:11:20.366  6731  6731 W art     : b6585000-b6586000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
,08-12 11:11:20.366  6731  6731 W art     : b6586000-b6587000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6587000-b65da000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:20.366  6731  6731 W art     : b65da000-b65db000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b65db000-b65dc000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:20.366  6731  6731 W art     : b65dc000-b65dd000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 11:11:20.366  6731  6731 W art     : b65dd000-b65e2000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b65e2000-b65f4000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 11:11:20.366  6731  6731 W art     : b65f4000-b65f5000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b65f5000-b65f6000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-12 11:11:20.366  6731  6731 W art     : b65f6000-b65f7000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 11:11:20.366  6731  6731 W art     : b65f7000-b65fe000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:20.366  6731  6731 W art     : b65fe000-b65ff000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:20.366  6731  6731 W art     : b65ff000-b6600000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 11:11:20.366  6731  6731 W art     : b6600000-b6601000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6601000-b6604000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 11:11:20.366  6731  6731 W art     : b6604000-b6605000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 11:11:20.366  6731  6731 W art     : b6605000-b6606000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
,08-12 11:11:20.366  6731  6731 W art     : b6606000-b660a000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:20.366  6731  6731 W art     : b660a000-b660b000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:20.366  6731  6731 W art     : b660b000-b660c000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 11:11:20.366  6731  6731 W art     : b660c000-b661a000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:20.366  6731  6731 W art     : b661a000-b661b000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b661b000-b661c000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:20.366  6731  6731 W art     : b661c000-b661d000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 11:11:20.366  6731  6731 W art     : b661d000-b6626000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
,08-12 11:11:20.366  6731  6731 W art     : b6626000-b6627000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 11:11:20.366  6731  6731 W art     : b6627000-b6628000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 11:11:20.366  6731  6731 W art     : b6628000-b668e000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:20.366  6731  6731 W art     : b668e000-b668f000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b668f000-b6691000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:20.366  6731  6731 W art     : b6691000-b669a000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 11:11:20.366  6731  6731 W art     : b669a000-b669d000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b669d000-b6734000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 11:11:20.366  6731  6731 W art     : b6734000-b6736000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
,08-12 11:11:20.366  6731  6731 W art     : b6736000-b6737000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 11:11:20.366  6731  6731 W art     : b6737000-b6738000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6738000-b6a59000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 11:11:20.366  6731  6731 W art     : b6a59000-b6a5a000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6a5a000-b6a75000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 11:11:20.366  6731  6731 W art     : b6a75000-b6a79000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 11:11:20.366  6731  6731 W art     : b6a79000-b6a7e000 rw-p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6a7e000-b6a86000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 11:11:20.366  6731  6731 W art     : b6a86000-b6a87000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 11:11:20.366  6731  6731 W art     : b6a87000-b6a88000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
,08-12 11:11:20.366  6731  6731 W art     : b6a88000-b6ab6000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 11:11:20.366  6731  6731 W art     : b6ab6000-b6ab7000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6ab7000-b6abe000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 11:11:20.366  6731  6731 W art     : b6abe000-b6abf000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 11:11:20.366  6731  6731 W art     : b6abf000-b6b05000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 11:11:20.366  6731  6731 W art     : b6b05000-b6b06000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6b06000-b6b09000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
,08-12 11:11:20.366  6731  6731 W art     : b6b09000-b6b0a000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 11:11:20.366  6731  6731 W art     : b6b0a000-b6b25000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:20.366  6731  6731 W art     : b6b25000-b6b29000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:20.366  6731  6731 W art     : b6b29000-b6b2a000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 11:11:20.366  6731  6731 W art     : b6b2a000-b6b77000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
,08-12 11:11:20.366  6731  6731 W art     : b6b77000-b6b78000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6b78000-b6b84000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 11:11:20.366  6731  6731 W art     : b6b84000-b6b85000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 11:11:20.366  6731  6731 W art     : b6b85000-b6b92000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 11:11:20.366  6731  6731 W art     : b6b92000-b6b93000 ---p 00000000 00:00 0 
,08-12 11:11:20.366  6731  6731 W art     : b6b93000-b6b94000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 11:11:20.366  6731  6731 W art     : b6b94000-b6b95000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 11:11:20.366  6731  6731 W art     : b6b95000-b6b9d000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 11:11:20.366  6731  6731 W art     : b6b9d000-b6b9e000 ---p 00000000 00:00 0 
08-12 11:11:20.366  6731  6731 W art     : b6b9e000-b6b9f000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 11:11:20.366  6731  6731 W art     : b6b9f000-b6ba0000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
,08-12 11:11:20.366  6731  6731 W art     : b6ba0000-b6ba7000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b6ba7000-b6ba8000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b6ba8000-b6ba9000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 11:11:20.366  6731  6731 W art     : b6ba9000-b6bbd000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:20.366  6731  6731 W art     : b6bbd000-b6bbf000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:20.366  6731  6731 W art     : b6bbf000-b6bc0000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 11:11:20.366  6731  6731 W art     : b6bc0000-b6be8000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
,08-12 11:11:20.366  6731  6731 W art     : b6be8000-b6bea000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 11:11:20.366  6731  6731 W art     : b6bea000-b6beb000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 11:11:20.376  6731  6731 W art     : b6beb000-b6bee000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:20.376  6731  6731 W art     : b6bee000-b6bef000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:20.376  6731  6731 W art     : b6bef000-b6bf0000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 11:11:20.376  6731  6731 W art     : b6bf0000-b6bf9000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
,08-12 11:11:20.376  6731  6731 W art     : b6bf9000-b6bfa000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 11:11:20.376  6731  6731 W art     : b6bfa000-b6bfb000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 11:11:20.376  6731  6731 W art     : b6bfb000-b6c1b000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 11:11:20.376  6731  6731 W art     : b6c1b000-b6c1c000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 11:11:20.376  6731  6731 W art     : b6c1c000-b6c1d000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
,08-12 11:11:20.376  6731  6731 W art     : b6c1d000-b6c90000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 11:11:20.376  6731  6731 W art     : b6c90000-b6c94000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 11:11:20.376  6731  6731 W art     : b6c94000-b6c97000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 11:11:20.376  6731  6731 W art     : b6c97000-b6ca1000 rw-p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6ca1000-b6d29000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 11:11:20.376  6731  6731 W art     : b6d29000-b6d2a000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6d2a000-b6d2e000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 11:11:20.376  6731  6731 W art     : b6d2e000-b6d2f000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
,08-12 11:11:20.376  6731  6731 W art     : b6d2f000-b6d30000 rw-p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6d30000-b6d59000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:20.376  6731  6731 W art     : b6d59000-b6d5a000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6d5a000-b6d5d000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:20.376  6731  6731 W art     : b6d5d000-b6d5e000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 11:11:20.376  6731  6731 W art     : b6d5e000-b6e38000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 11:11:20.376  6731  6731 W art     : b6e38000-b6e3f000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 11:11:20.376  6731  6731 W art     : b6e3f000-b6e47000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
,08-12 11:11:20.376  6731  6731 W art     : b6e47000-b6e48000 rw-p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6e48000-b6e49000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:20.376  6731  6731 W art     : b6e49000-b6e4a000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 11:11:20.376  6731  6731 W art     : b6e4a000-b6e4b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.376  6731  6731 W art     : b6e4b000-b6e4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.376  6731  6731 W art     : b6e4e000-b6e73000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 11:11:20.376  6731  6731 W art     : b6e73000-b6e74000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6e74000-b6e7b000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
,08-12 11:11:20.376  6731  6731 W art     : b6e7b000-b6e7c000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 11:11:20.376  6731  6731 W art     : b6e7c000-b6e83000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:20.376  6731  6731 W art     : b6e83000-b6e84000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:20.376  6731  6731 W art     : b6e84000-b6e85000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 11:11:20.376  6731  6731 W art     : b6e85000-b6e86000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.376  6731  6731 W art     : b6e86000-b6e9e000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 11:11:20.376  6731  6731 W art     : b6e9e000-b6e9f000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6e9f000-b6ea0000 r--p 00018000 b3:17 918        /system/lib/libutils.so
,08-12 11:11:20.376  6731  6731 W art     : b6ea0000-b6ea1000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 11:11:20.376  6731  6731 W art     : b6ea1000-b6eaf000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:20.376  6731  6731 W art     : b6eaf000-b6eb0000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6eb0000-b6eb1000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:20.376  6731  6731 W art     : b6eb1000-b6eb2000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 11:11:20.376  6731  6731 W art     : b6eb2000-b6eb3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:20.376  6731  6731 W art     : b6eb3000-b6eb5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.376  6731  6731 W art     : b6eb5000-b6eb6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
,08-12 11:11:20.376  6731  6731 W art     : b6eb6000-b6eb7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 11:11:20.376  6731  6731 W art     : b6eb7000-b6eb8000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 11:11:20.376  6731  6731 W art     : b6eb8000-b6eb9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 11:11:20.376  6731  6731 W art     : b6eb9000-b6ed9000 r--s 00000000 00:0b 8200       /dev/__properties__
08-12 11:11:20.376  6731  6731 W art     : b6ed9000-b6eda000 r--p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6eda000-b6edb000 ---p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6edb000-b6edd000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 11:11:20.376  6731  6731 W art     : b6edd000-b6ede000 r-xp 00000000 00:00 0          [sigpage]
,08-12 11:11:20.376  6731  6731 W art     : b6ede000-b6ef9000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 11:11:20.376  6731  6731 W art     : b6ef9000-b6efa000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 11:11:20.376  6731  6731 W art     : b6efa000-b6efc000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 11:11:20.376  6731  6731 W art     : b6efc000-b6efe000 rw-p 00000000 00:00 0 
08-12 11:11:20.376  6731  6731 W art     : b6efe000-b6f03000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 11:11:20.376  6731  6731 W art     : b6f03000-b6f04000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 11:11:20.376  6731  6731 W art     : b6f04000-b6f05000 rw-p 00000000 00:00 0 
,08-12 11:11:20.376  6731  6731 W art     : beb61000-beb82000 rw-p 00000000 00:00 0          [stack]
08-12 11:11:20.376  6731  6731 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-12 11:11:20.456  6731  6731 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat,
,08-12 11:11:20.516  6731  6731 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 11:11:20.526  6731  6731 E AffinityControl: AffinityControl: registerfunction enter
,08-12 11:11:20.546  6731  6731 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 11:11:20.556   764  2321 D PackageManager: START PACKAGE DELETE: observer{9945915}
08-12 11:11:20.556   764  2321 D PackageManager: pkg{<packageName>}
08-12 11:11:20.556   764  2321 D PackageManager: user{0}
08-12 11:11:20.556   764  2321 D PackageManager: caller{2000}
08-12 11:11:20.556   764  2321 D PackageManager: flags{2}
,08-12 11:11:20.556   764  2321 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 11:11:20.556   764  2321 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-12 11:11:20.556   764  2321 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-12 11:11:20.556   764  2321 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 11:11:20.556   764  2321 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 11:11:20.556   764   943 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-12 11:11:20.556   764   943 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-12 11:11:20.556   764   943 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-12 11:11:20.556   764   943 D ApplicationPolicy: getApplicationUninstallationEnabled
08-12 11:11:20.556   764   943 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 11:11:20.556   764   943 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 11:11:20.556   764   943 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 11:11:20.556   764   943 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-12 11:11:20.556   764   943 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-12 11:11:20.556   764   861 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-12 11:11:20.556   764   943 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 11:11:20.566   764   861 I ActivityManager: Killing 6449:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-12 11:11:20.576   764   861 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 11:11:20.576   764   861 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 11:11:20.586   764   943 D AASAinstall: there is not AASApackages.xml file
,08-12 11:11:20.626   764  1467 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8bc4a58)
,08-12 11:11:20.626   764  2154 D GraphicsStats: Buffer count: 4
,08-12 11:11:20.626   293  1939 D libEGL  : eglTerminate EGLDisplay = 0xaeffb6fc
08-12 11:11:20.626   764   777 I WindowState: WIN DEATH: Window{cc5b67f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 11:11:20.626   764  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 11:11:20.626   764  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 11:11:20.626   764  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 11:11:20.626   293   357 I SurfaceFlinger: id=15 Removed NainActivit (4/10)
,08-12 11:11:20.626   293  1295 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
,08-12 11:11:20.626   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
,08-12 11:11:20.876   764   943 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 11:11:20.896   764   943 W PackageSettings: Skipping PackageSetting{76b1b50 com.example.hello/10192} due to missing metadata
,08-12 11:11:20.966   764   943 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 11:11:20.966   764   861 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 11:11:20.966   764   861 E ActivityManager: Failure starting process com.test.thalitest
08-12 11:11:20.966   764   861 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6684)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7381)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 11:11:20.966   764   861 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:20.966   764   861 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 11:11:20.966   764   861 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:11:20.966   764   861 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 11:11:20.966   324   324 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 11:11:20.976   764   943 I art     : Starting a blocking GC Explicit
,08-12 11:11:20.976   764   861 I ActivityManager:   Force finishing activity ActivityRecord{295f224 u0 com.test.thalitest/.MainActivity t163}
,08-12 11:11:21.086   764   943 I art     : Explicit concurrent mark sweep GC freed 90778(4MB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 41MB/57MB, paused 1.454ms total 115.855ms
,08-12 11:11:21.116   764   943 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 11:11:21.116   764   943 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-12 11:11:21.116   764   943 D AASAinstall: there is not AASApackages.xml file
,08-12 11:11:21.116   764   943 D PackageManager: result of delete: 1{9945915}
,08-12 11:11:21.116  6731  6731 I art     : System.exit called, status: 0
08-12 11:11:21.116  6731  6731 I AndroidRuntime: VM exiting with result code 0.
,08-12 11:11:21.126   764   943 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 11:11:21.126   764   943 D PackageManager: userId{-1}
08-12 11:11:21.126   764   943 D PackageManager: andCode{true}
,08-12 11:11:21.126   764   943 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 11:11:21.146  5891  6741 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 11:11:21.146  5891  6741 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 11:11:21.146  5891  6741 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 11:11:21.196   764   861 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-12 11:11:21.196   764   861 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 11:11:21.196   764   861 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 11:11:21.196   764   764 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.206   764   764 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.206   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.216   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.216   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.216   764   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.226  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-12 11:11:21.226  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 11:11:21.226   764   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.226   764  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.236  1963  1963 E SamsungIME: mOCRHelper is null
,08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.236   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.246  2045  2544 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.246   764   764 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.256   764   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fbdf21 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f75f61 4328:com.samsung.klmsagent/u0a18}
,08-12 11:11:21.256   764   764 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.256   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.266  4328  4328 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 11:11:21 GMT+02:00 2016
,08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.266   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.266   764   849 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
,08-12 11:11:21.276   764   849 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 11:11:21.276  1698  1698 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 11:11:21.276  3207  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 11:11:21.276  3207  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276  3207  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.276   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  3207  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  4328  4328 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
08-12 11:11:21.286   764  1465 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  4328  4328 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  4328  4328 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  4328  4328 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286  4328  6757 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-12 11:11:21.286  4328  6757 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-12 11:11:21.286  4328  6757 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-12 11:11:21.286  4328  6757 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-12 11:11:21.286  4328  6757 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-12 11:11:21.286  4328  6757 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-12 11:11:21.286   764   849 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.286   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.296   764   764 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.296  4328  6757 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-12 11:11:21.296  4328  6757 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-12 11:11:21.296   764  2220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fbdf21 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{575c18c 764:system/1000}
08-12 11:11:21.296   764   764 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.296   764   764 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.296  4328  6757 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-12 11:11:21.306  4328  6757 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
08-12 11:11:21.306   764   764 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.306  4328  6757 W System.err: mkdir failed: ENOENT (No such file or directory) : /data/user/0/com.samsung.klmsagent/databases
08-12 11:11:21.306   764   764 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.306  4328  6757 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (2)
08-12 11:11:21.306  4328  6757 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131072) and mode_t (0) due to error (2)
08-12 11:11:21.306  4328  6757 E SQLiteLog: (14) cannot open file at line 31517 of [2ef4f3a5b1]
08-12 11:11:21.306  4328  6757 E SQLiteLog: (14) os_unix.c:31517: (2) open(/data/user/0/com.samsung.klmsagent/databases/klms.db) - 
08-12 11:11:21.306   764  1321 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9c9f0b3e in tid 1321 (NetworkPolicy)
08-12 11:11:21.306   764  1320 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9c9f2ee4 in tid 1320 (NetworkStats)
08-12 11:11:21.306   764  1320 I libc    : Another thread contacted debuggerd first; not contacting debuggerd.
08-12 11:11:21.306  4328  6757 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x733093a8 in tid 6757 (IntentService[K)
08-12 11:11:21.306  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
08-12 11:11:21.306  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
08-12 11:11:21.316   764   764 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-12 11:11:21.316  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
,08-12 11:11:21.346   342   342 I Zygote  : Process 4328 exited due to signal (7)
,08-12 11:11:21.386   320   320 E installd: eof
08-12 11:11:21.386   320   320 E installd: failed to read size
08-12 11:11:21.386   320   320 I installd: closing connection
,08-12 11:11:21.386   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'application_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wifi_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'remoteinjection' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'edm_proxy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'mum_container_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'otp_service' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'enterprise_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'statusbar' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'clipboard' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'clipboardEx' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'network_management' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'midi' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'textservices' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'network_score' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'netstats' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'netpolicy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wifip2p' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wifi' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wifihs20' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wifiscanner' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'rttmanager' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'ethernet' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'connectivity' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sb_service' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'input_method' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'accessibility' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'cover' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'mount' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'lock_settings' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'deviceidle' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'device_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'harmony_eas_service' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sdp' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sdp_log' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'dlp' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'log_manager_service' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'servicediscovery' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'updatelock' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'notification' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'location' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'country_detector' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sec_location' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'search' die,d
08-12 11:11:21.386   292   292 I ServiceManager: service 'execute' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'dropbox' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'wallpaper' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'audio' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'DockObserver' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'usb' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'serial' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'kiesusb' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'jobscheduler' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'backup' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'appwidget' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'voiceinteraction' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'diskstats' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'mDNIe' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'AAS' died
08-12 11:11:21.396  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
08-12 11:11:21.386   292   292 I ServiceManager: service 'MSCS' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'spengestureservice' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'quickconnect' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'samplingprofiler' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'commontime_management' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'dreams' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'graphicsstats' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'print' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'restrictions' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'media_session' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'media_router' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'trust' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'fingerprint' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'launcherapps' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'voip' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'media_projection' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'lpnet' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sec_analytics' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'telecom' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'user' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'procstats' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'meminfo' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'gfxinfo' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'dbinfo' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'cpuinfo' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'permission' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'processinfo' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'sensorservice' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'battery' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'usagestats' died
,08-12 11:11:21.386   292   292 I ServiceManager: service 'webviewupdate' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'scheduling_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'telephony.registry' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'persona' died
08-12 11:11:21.386  1688  1688 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x732d397e in tid 1688 (com.android.nfc)
08-12 11:11:21.386   292   292 I ServiceManager: service 'context_aware' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'scontext' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'barbeam' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'multiwindow_facade' died
,08-12 11:11:21.386   292   292 I ServiceManager: service 'window' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'input' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'bluetooth_manager' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'rcp' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'SEAMService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'media.camera.proxy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'account' died
,08-12 11:11:21.386   292   292 I ServiceManager: service 'content' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'DirEncryptService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'LSManager' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'ReactiveService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'EngineeringModeService' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'SatsService' died
,08-12 11:11:21.386   292   292 I ServiceManager: service 'sedenial' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'vibrator' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'tw_toolbox' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'tima' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'iccc' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'cepproxyks' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'emailksproxy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
,08-12 11:11:21.386   292   292 I ServiceManager: service 'consumer_ir' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'alarm' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'package' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'persona_policy' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'activity' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'imms' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'batterystats' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'appops' died
08-12 11:11:21.386   292   292 I ServiceManager: service 'power' died
,08-12 11:11:21.396   292   292 I ServiceManager: service 'display' died
08-12 11:11:21.396   292   292 I ServiceManager: service 'uimode' died
08-12 11:11:21.396   292   292 I ServiceManager: service 'edmnativehelper' died
08-12 11:11:21.396  3207  3225 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e63ab55 in tid 3225 (AccountChangeLi)
08-12 11:11:21.396  3207  3225 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 11:11:21.396  1855  1865 W Sensors : sensorservice died [0xad83cec0]
08-12 11:11:21.396  1698  1698 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-12 11:11:21.396  1698  2576 E WifiManager: Channel connection lost
08-12 11:11:21.396   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb69c16fc
08-12 11:11:21.396   293   357 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 11:11:21.396   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-12 11:11:21.396   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 11:11:21.396  2872  2882 W Sensors : sensorservice died [0xb483bc40]
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=8 Removed EimLayer(Di (6/9)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=2 Removed GocusedStac (4/8)
,08-12 11:11:21.396   293   362 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/7)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=4 Removed EimLayer(An (0/6)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=9 Removed EimLayer(An (0/5)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
,08-12 11:11:21.396   293   362 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=13 Removed DolorFade (2/2)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=13 Removed DolorFade (-2/2)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=16 Removed VSBConnecti (1/1)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=17 Removed VSBConnecti (0/0)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/0)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/0)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=8 Removed EimLayer(Di (-2/0)
08-12 11:11:21.396   293   362 I SurfaceFlinger: id=9 Removed EimLayer(An (-2/0)
08-12 11:11:21.396  1382  2250 W Sensors : sensorservice died [0xb483bdc0]
,08-12 11:11:21.396  1382  1656 E WifiManager: Channel connection lost
08-12 11:11:21.406  2105  2105 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ee3f30a in tid 2105 (droid.bluetooth)
08-12 11:11:21.406  2105  2105 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 11:11:21.406  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
,08-12 11:11:21.406  5990  6039 E WifiManager: Channel connection lost
08-12 11:11:21.406  1688  1688 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 11:11:21.406  1824  2011 E WifiManager: Channel connection lost
08-12 11:11:21.406  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
,08-12 11:11:21.406  2045  2056 W Sensors : sensorservice died [0xad44fec0]
,08-12 11:11:21.406  2872  3194 E WifiManager: Channel connection lost
,08-12 11:11:21.416   317   317 W AudioFlinger: power manager service died !!!
,08-12 11:11:21.416   317   317 W AudioFlinger: power manager service died !!!
,08-12 11:11:21.416  1713  1881 W Sensors : sensorservice died [0xb3ac8380]
,08-12 11:11:21.416  2045  2543 E WifiManager: Channel connection lost
08-12 11:11:21.416  2161  2190 W Sensors : sensorservice died [0xad83cd80]
,08-12 11:11:21.426   292   292 I ServiceManager: service 'nfc' died
08-12 11:11:21.426   292   292 I ServiceManager: service 'nfccontroller' died
08-12 11:11:21.426   292   292 I ServiceManager: service 'secontroller' died
,08-12 11:11:21.446  2153  2153 D BluetoothA2dp: Proxy object disconnected
,08-12 11:11:21.446  2872  2872 D BluetoothMap: Proxy object disconnected
08-12 11:11:21.446  2872  2872 D MapProfile: Bluetooth service disconnected
,08-12 11:11:21.446   342   342 I Zygote  : Process 1688 exited due to signal (7)
,08-12 11:11:21.446  2872  2872 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9722bd in tid 2872 (ndroid.settings)
,08-12 11:11:21.446  2872  2872 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 11:11:21.446  2111  2111 E audit_log: File locking failed. error= Bad file descriptor
,08-12 11:11:21.456   342   342 I Zygote  : Process 3207 exited due to signal (7)
,08-12 11:11:21.496   342   342 I Zygote  : Process 2105 exited due to signal (7)
08-12 11:11:21.496   342  6681 I Zygote  : Process 2872 exited due to signal (7)
,08-12 11:11:21.576   291   291 I lowmemorykiller: ActivityManager disconnected
08-12 11:11:21.576   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-12 11:11:21.646   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-12 11:11:21.646   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 11:11:21.906   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 11:11:21.916   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c
08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e3a4
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c
,08-12 11:11:21.916   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbea1e38c

```
