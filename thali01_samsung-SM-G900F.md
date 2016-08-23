#### Test 8233723530fac5a_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-23 12:25:23.582  5359  5359 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-23 12:25:23.582  5359  5359 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-23 12:25:23.582  5359  5359 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-23 12:25:23.592  5359  5359 I art     : System.exit called, status: 0
08-23 12:25:23.592  5359  5359 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 12:25:23.632  5319  5319 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
--------- beginning of system
08-23 12:25:23.632   765  2043 I ActivityManager: Process com.samsung.aasaservice (pid 5359)(adj 0) has died(122,723)
08-23 12:25:23.632   765  2043 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 12:25:23.632   765  2043 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-23 12:25:23.632   765  2043 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-23 12:25:23.652   765   834 I ActivityManager: Start proc 6250:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-23 12:25:23.652  6250  6250 E Zygote  : v2
08-23 12:25:23.652  6250  6250 I libpersona: KNOX_SDCARD checking this for 10014
08-23 12:25:23.652  6250  6250 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:23.652  6250  6250 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:23.652  6250  6250 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:23.652  6250  6250 E Zygote  : accessInfo : 0
08-23 12:25:23.652   765  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 12:25:23.652  6250  6250 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-23 12:25:23.672  6250  6250 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:23.672  6250  6250 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:23.712   765  2127 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbcb6b0 6250:com.google.android.partnersetup/u0a14}
08-23 12:25:23.712   765  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-23 12:25:23.722  6250  6250 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-23 12:25:23.732  6250  6250 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-23 12:25:23.752   765  2140 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbcb6b0 6250:com.google.android.partnersetup/u0a14}
08-23 12:25:23.772  6274  6274 E Zygote  : v2
08-23 12:25:23.772  6274  6274 I libpersona: KNOX_SDCARD checking this for 10015
08-23 12:25:23.772  6274  6274 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:23.772  6274  6274 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:23.772  6274  6274 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:23.782  6274  6274 E Zygote  : accessInfo : 0
08-23 12:25:23.782  6274  6274 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-23 12:25:23.782   765  1416 I ActivityManager: Start proc 6274:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-23 12:25:23.782   765  2102 I ActivityManager: Killing 5277:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
08-23 12:25:23.812  6274  6274 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:23.812  6274  6274 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:23.812   765  2050 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
08-23 12:25:23.822   765  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 12:25:23.822   765   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{28a924f 6274:com.samsung.groupcast/u0a15}
08-23 12:25:23.832  6274  6274 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-23 12:25:23.842  6274  6274 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-23 12:25:23.862  6274  6274 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-23 12:25:23.872  6274  6274 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 12:25:23.872  6274  6274 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-23 12:25:23.872  6274  6274 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 12:25:23.872  6274  6274 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 12:25:23.872  6274  6274 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:23.872  6274  6274 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 12:25:23.872  6274  6274 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 12:25:23.872   765  1497 I ActivityManager: Killing 5471:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-23 12:25:23.882   765  1497 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{959ee60 1923:com.sec.android.app.shealth:remote/u0a34}
08-23 12:25:23.892   765  1680 I ActivityManager: Start proc 6286:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-23 12:25:23.892   765  1321 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 12:25:23.892  6286  6286 E Zygote  : v2
08-23 12:25:23.892  6286  6286 I libpersona: KNOX_SDCARD checking this for 10041
08-23 12:25:23.892  6286  6286 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:23.892  6286  6286 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:23.902   765   777 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-23 12:25:23.902  6286  6286 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:23.902  6286  6286 E Zygote  : accessInfo : 0
08-23 12:25:23.902  6286  6286 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-23 12:25:23.902   765  1321 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 12:25:23.922  6286  6286 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:23.922  6286  6286 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:23.932   765  2043 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ae8ddc 6286:com.samsung.android.sdk.samsunglink/u0a41}
08-23 12:25:23.932  6286  6286 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-23 12:25:23.942   765  3411 D SSRM:n  : SIOP:: AP = 470, PST = 445, CUR = 450, LCD = 0
08-23 12:25:24.012  6286  6286 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 12:25:24.012  6286  6286 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 12:25:24.072  6286  6286 I SL_DEBUG: isLoggable:: isProductShip = 1
08-23 12:25:24.072  6286  6286 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-23 12:25:24.092   765  2102 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.092   765  2103 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-23 12:25:24.092   765  2043 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.092   765  2000 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.092   765  1487 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.102   765  2044 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.102   765  2127 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.102   765  1318 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.102   765   779 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.102   765  1497 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-23 12:25:24.202  6286  6286 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-23 12:25:24.202  6286  6286 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-23 12:25:24.202  6286  6286 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-23 12:25:24.202  6286  6286 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-23 12:25:24.202  6286  6286 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-23 12:25:24.202  6286  6286 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 12:25:24.202  6286  6286 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 12:25:24.202  6286  6286 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:24.202  6286  6286 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 12:25:24.202  6286  6286 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 12:25:24.212   765  2044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96c69eb 1682:android.process.acore/u0a19}
08-23 12:25:24.222   765  2044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cab2891 5076:com.sec.android.gallery3d/u0a47}
08-23 12:25:24.222  5076  5076 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 12:25:24.222   765   777 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 12:25:24.252  6309  6309 E Zygote  : v2
08-23 12:25:24.252  6309  6309 I libpersona: KNOX_SDCARD checking this for 10050
08-23 12:25:24.252  6309  6309 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.252   765  1668 I ActivityManager: Start proc 6309:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-23 12:25:24.252  6309  6309 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.252  6309  6309 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.252   765  1321 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 12:25:24.252  6309  6309 E Zygote  : accessInfo : 0
08-23 12:25:24.252  6309  6309 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-23 12:25:24.252   765  1321 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 12:25:24.272  6309  6309 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.272  6309  6309 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.282   765  2000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{61f260c 6309:com.sec.android.app.myfiles/u0a50}
08-23 12:25:24.292  6309  6309 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-23 12:25:24.302  6309  6309 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-23 12:25:24.342  6309  6309 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 12:25:24.362   765  2127 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5569ee4 2842:com.android.settings/1000}
08-23 12:25:24.362   332   332 E installd: system dir 0 : /system/app/
08-23 12:25:24.362   332   332 E installd: system dir 1 : /system/priv-app/
08-23 12:25:24.362   332   332 E installd: system dir 2 : /vendor/app/
08-23 12:25:24.362   332   332 E installd: system dir 3 : /oem/app/
08-23 12:25:24.372   765  2050 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5569ee4 2842:com.android.settings/1000}
08-23 12:25:24.382   765   925 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 12:25:24.392   765  2050 I ActivityManager: Start proc 6324:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-23 12:25:24.392  6324  6324 E Zygote  : v2
08-23 12:25:24.392  6324  6324 I libpersona: KNOX_SDCARD checking this for 10169
08-23 12:25:24.392  6324  6324 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.392  6324  6324 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.392  6324  6324 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.392  6324  6324 E Zygote  : accessInfo : 0
08-23 12:25:24.392  6324  6324 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-23 12:25:24.412  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.412  6324  6324 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.422   765   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9e96f8 6324:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-23 12:25:24.422  6324  6324 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-23 12:25:24.432  6324  6324 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-23 12:25:24.452   765  2044 I ActivityManager: Killing 5508:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-23 12:25:24.462   765  2044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{82b464 1655:com.android.phone/1001}
08-23 12:25:24.462   765  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81fc671 1788:com.google.android.googlequicksearchbox:search/u0a61}
08-23 12:25:24.472   765  2050 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-23 12:25:24.482   765  2043 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81fc671 1788:com.google.android.googlequicksearchbox:search/u0a61}
08-23 12:25:24.492   765  1487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a93236 6182:com.samsung.android.sm.provider/1000}
08-23 12:25:24.512  6338  6338 E Zygote  : v2
08-23 12:25:24.512  6338  6338 I libpersona: KNOX_SDCARD checking this for 5012
08-23 12:25:24.512   765  2127 I ActivityManager: Start proc 6338:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-23 12:25:24.522  6338  6338 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.522  6338  6338 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.522  6338  6338 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.522  6338  6338 E Zygote  : accessInfo : 0
08-23 12:25:24.522  6338  6338 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-23 12:25:24.522  1788  6336 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 12:25:24.532  2023  2023 E audit   : type=1400 msg=audit(1471947924.532:285): avc:  denied  { execmod } for  pid=6260 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 12:25:24.532  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.532  2023  2023 E audit   : type=1300 msg=audit(1471947924.532:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4030000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6260 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:24.532  2023  2023 E audit   : type=1327 msg=audit(1471947924.532:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 12:25:24.532  2023  2023 E audit   : type=1320 msg=audit(1471947924.532:285): 
08-23 12:25:24.542  6338  6338 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.542  6338  6338 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.552   765  1668 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1b0537 6338:com.samsung.android.sm.devicesecurity/5012}
08-23 12:25:24.552  6338  6338 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-23 12:25:24.572  6338  6338 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-23 12:25:24.582  1788  6336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 12:25:24.582  2023  2023 E audit   : type=1400 msg=audit(1471947924.582:286): avc:  denied  { execmod } for  pid=6260 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 12:25:24.582  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.592  2023  2023 E audit   : type=1300 msg=audit(1471947924.582:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fef000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6260 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:24.592  2023  2023 E audit   : type=1327 msg=audit(1471947924.582:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 12:25:24.592  2023  2023 E audit   : type=1320 msg=audit(1471947924.582:286): 
08-23 12:25:24.592   765  1416 I ActivityManager: Killing 3984:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-23 12:25:24.592  1788  6336 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 12:25:24.592   765  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c72579 3176:com.android.contacts/u0a19}
08-23 12:25:24.612   765   779 I ActivityManager: Start proc 6350:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-23 12:25:24.612  6350  6350 E Zygote  : v2
08-23 12:25:24.612  6350  6350 I libpersona: KNOX_SDCARD checking this for 10049
08-23 12:25:24.612  6350  6350 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.612  6350  6350 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.612  6350  6350 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.612  6350  6350 E Zygote  : accessInfo : 0
08-23 12:25:24.612  6350  6350 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-23 12:25:24.632   765  2000 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-23 12:25:24.642  2023  2023 E audit   : type=1400 msg=audit(1471947924.642:287): avc:  denied  { execmod } for  pid=6260 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 12:25:24.642  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.642  2023  2023 E audit   : type=1300 msg=audit(1471947924.642:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff0000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6260 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:24.642  2023  2023 E audit   : type=1327 msg=audit(1471947924.642:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 12:25:24.642  2023  2023 E audit   : type=1320 msg=audit(1471947924.642:287): 
08-23 12:25:24.642  6260  6260 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 12:25:24.642  6350  6350 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.642  6350  6350 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.642  6260  6260 D AndroidRuntime: CheckJNI is OFF
08-23 12:25:24.642  6260  6260 D AndroidRuntime: readGMSProperty: start
08-23 12:25:24.642  6260  6260 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:25:24.642  6260  6260 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:25:24.642  6260  6260 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:25:24.642  6260  6260 D AndroidRuntime: readGMSProperty: end
08-23 12:25:24.642  6260  6260 D AndroidRuntime: addProductProperty: start
08-23 12:25:24.652  6260  6260 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 12:25:24.652  6260  6260 W art     : af19f000-b20c5000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:24.652  6260  6260 W art     : b20c5000-b4334000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:24.652  6260  6260 W art     : b4334000-b4335000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:24.652  6362  6362 I libpersona: KNOX_SDCARD checking this for 10210
08-23 12:25:24.652  6260  6260 W art     : b4335000-b435e000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 12:25:24.652  6362  6362 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.652  6260  6260 W art     : b435e000-b4361000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:24.652  6260  6260 W art     : b4361000-b4362000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:24.652  6260  6260 W art     : b4362000-b4363000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:24.652  6260  6260 W art     : b4363000-b47b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 12:25:24.652  6362  6362 E Zygote  : v2
08-23 12:25:24.652  6260  6260 W art     : b47b1000-b47b2000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b47b2000-b47bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 12:25:24.652  6260  6260 W art     : b47bc000-b47bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 12:25:24.652  6260  6260 W art     : b47bd000-b47bf000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b47bf000-b47c0000 r--p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 12:25:24.652  6260  6260 W art     : b48c3000-b48c4000 r--p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b48c4000-b48e4000 r--s 00000000 00:0b 6572       /dev/__properties__
08-23 12:25:24.652  6260  6260 W art     : b48e4000-b52f5000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:24.652  6260  6260 W art     : b52f5000-b52f6000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b52f6000-b533f000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:24.652  6260  6260 W art     : b533f000-b5340000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:24.652  6260  6260 W art     : b5340000-b5348000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5348000-b5349000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5349000-b537e000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:24.652  6260  6260 W art     : b537e000-b537f000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b537f000-b5380000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:24.652  6260  6260 W art     : b5380000-b5381000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:24.652  6260  6260 W art     : b5381000-b53d9000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:24.652  6260  6260 W art     : b53d9000-b53da000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b53da000-b53db000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:24.652  6260  6260 W art     : b53db000-b53dc000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:24.652  6260  6260 W art     : b53dd000-b53e3000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:24.652  6260  6260 W art     : b53e3000-b53e4000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:24.652  6260  6260 W art     : b53e4000-b53e5000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:24.652  6260  6260 W art     : b53e5000-b53e7000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b53e8000-b53f2000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:24.652  6260  6260 W art     : b53f2000-b53f5000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:24.652   765   834 I ActivityManager: Start proc 6362:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-23 12:25:24.652  6260  6260 W art     : b53f5000-b53f6000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:24.652  6260  6260 W art     : b53f7000-b540e000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:24.652  6362  6362 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.652  6260  6260 W art     : b540e000-b540f000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b540f000-b5410000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:24.652  6260  6260 W art     : b5410000-b5411000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:24.652  6362  6362 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.652  6260  6260 W art     : b5412000-b541c000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:24.652  6260  6260 W art     : b541c000-b541d000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:24.652  6260  6260 W art     : b541d000-b541e000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:24.652  6260  6260 W art     : b541e000-b5422000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:24.652  6260  6260 W art     : b5422000-b5423000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:24.652  6260  6260 W art     : b5423000-b5424000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:24.652  6260  6260 W art     : b5424000-b543a000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:24.652  6260  6260 W art     : b543a000-b543b000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:24.652  6260  6260 W art     : b543b000-b543c000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:24.652  6260  6260 W art     : b543c000-b5449000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:24.652  6260  6260 W art     : b5449000-b544a000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:24.652  6260  6260 W art     : b544a000-b544b000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:24.652  6260  6260 W art     : b544b000-b54ab000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 12:25:24.652  6260  6260 W art     : b54ab000-b54ae000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 12:25:24.652  6260  6260 W art     : b54ae000-b54b2000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b54b2000-b5513000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 12:25:24.652  6260  6260 W art     : b5513000-b5514000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 12:25:24.652  6260  6260 W art     : b5514000-b5563000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:24.652  6260  6260 W art     : b5563000-b5565000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:24.652  6260  6260 W art     : b5565000-b5566000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:24.652  6260  6260 W art     : b5566000-b5567000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5567000-b556e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 12:25:24.652  6260  6260 W art     : b556e000-b556f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 12:25:24.652  6260  6260 W art     : b556f000-b5570000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 12:25:24.652  6260  6260 W art     : avc_common.so
08-23 12:25:24.652  6260  6260 W art     : b5571000-b5574000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 12:25:24.652  6260  6260 W art     : b5574000-b5575000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 12:25:24.652  6260  6260 W art     : b5575000-b5576000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 12:25:24.652  6260  6260 W art     : enc_common.so
08-23 12:25:24.652  6260  6260 W art     : b5577000-b557b000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 12:25:24.652  6260  6260 W art     : b557b000-b557c000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b557c000-b557d000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 12:25:24.652  6260  6260 W art     : b557d000-b557e000 rw-p 00005000 b3:17 2510       /syste
08-23 12:25:24.652  6260  6260 W art     : m/lib/libpowermanager.so
08-23 12:25:24.652  6260  6260 W art     : b557f000-b559c000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:24.652  6260  6260 W art     : b559c000-b559d000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:24.652  6260  6260 W art     : b559d000-b559e000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:24.652  6260  6260 W art     : b559f000-b55a4000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:24.652  6260  6260 W art     : b55a4000-b55a5000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:24.652  6260  6260 W art     : b55a5000-b55a6000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:24.652  6260  6260 W art     : b55a7000-b55d8000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:24.652  6260  6260 W art     : b55d8000-b55db000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:24.652  6260  6260 W art     : b55db000-b55dc000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:24.652  6260  6260 W art     : b55dd000-b5618000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 12:25:24.652  6260  6260 W art     : b5618000-b5619000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 12:25:24.652  6260  6260 W art     : b5619000-b561a000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 12:25:24.652  6260  6260 W art     : b561b000-b5622000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:24.652  6260  6260 W art     : b5622000-b5623000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5623000-b5624000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:24.652  6260  6260 W art     : b5624000-b5625000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:24.652  6260  6260 W art     : b5625000-b5626000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5626000-b563d000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:24.652  6260  6260 W art     : b563d000-b563e000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b563e000-b5641000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:24.652  6260  6260 W art     : b5641000-b5642000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:24.652  6260  6260 W art     : b5642000-b5661000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:24.652  6260  6260 W art     : b5661000-b5662000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:24.652  6362  6362 E Zygote  : accessInfo : 0
08-23 12:25:24.652  6260  6260 W art     : b5662000-b5663000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:24.652  6260  6260 W art     : b5663000-b56a1000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:24.652  6260  6260 W art     : b56a1000-b56a2000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b56a2000-b56a4000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:24.652  6260  6260 W art     : b56a4000-b56a5000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:24.652  6260  6260 W art     : b56a6000-b56ad000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:24.652  6260  6260 W art     : b56ad000-b56ae000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:24.652  6260  6260 W art     : b56ae000-b56af000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:24.652  6260  6260 W art     : b56b0000-b56b3000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:24.652  6260  6260 W art     : b56b3000-b56b4000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:24.652  6260  6260 W art     : b56b4000-b56b5000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:24.652  6260  6260 W art     : b56b5000-b56bb000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:24.652  6260  6260 W art     : b56bb000-b56bc000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b56bc000-b56bd000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:24.652  6260  6260 W art     : b56bd000-b56be000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:24.652  6260  6260 W art     : b56be000-b56c7000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:24.652  6260  6260 W art     : b56c7000-b56c8000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:24.652  6362  6362 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-23 12:25:24.652  6260  6260 W art     : b56c8000-b56c9000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:24.652  6260  6260 W art     : b56c9000-b575a000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:24.652  6260  6260 W art     : b575a000-b575b000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b575b000-b5766000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:24.652  6260  6260 W art     : b5766000-b5767000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:24.652  6260  6260 W art     : b5768000-b577a000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:24.652  6260  6260 W art     : b577a000-b577b000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:24.652  6260  6260 W art     : b577b000-b577c000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:24.652  6260  6260 W art     : b577d000-b5782000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:24.652  6260  6260 W art     : b5782000-b5783000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:24.652  6260  6260 W art     : b5783000-b5784000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:24.652  6260  6260 W art     : b5785000-b57f2000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:24.652  6260  6260 W art     : b57f2000-b57f3000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b57f3000-b57f5000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:24.652  6260  6260 W art     : b57f5000-b57f6000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:24.652  6260  6260 W art     : b57f6000-b57f7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b57f7000-b57fe000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:24.652  6260  6260 W art     : b57fe000-b57ff000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:24.652  6260  6260 W art     : b57ff000-b5800000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:24.652  6260  6260 W art     : b5801000-b5881000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:24.652  6260  6260 W art     : b5881000-b5882000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5882000-b5883000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:24.652  6260  6260 W art     : b5883000-b5884000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:24.652  6260  6260 W art     : b5884000-b589b000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b589b000-b58d2000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 12:25:24.652  6260  6260 W art     : ib/libqc-opt.so
08-23 12:25:24.652  6260  6260 W art     : b58d2000-b58d3000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 12:25:24.652  6260  6260 W art     : b58d3000-b58d4000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 12:25:24.652  6260  6260 W art     : b58d4000-b58f0000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:24.652  6260  6260 W art     : b58f0000-b58f1000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:24.652  6260  6260 W art     : b58f1000-b58f2000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:24.652  6260  6260 W art     : b58f3000-b5954000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:24.652  6260  6260 W art     : b5954000-b5956000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:24.652  6260  6260 W art     : b5956000-b5957000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:24.652  6260  6260 W art     : b5958000-b597f000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:24.652  6260  6260 W art     : b597f000-b5980000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5980000-b5981000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:24.652  6260  6260 W art     : b5981000-b5982000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:24.652  6260  6260 W art     : b5983000-b598b000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:24.652  6260  6260 W art     : b598b000-b598d000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:24.652  6260  6260 W art     : b598d000-b598e000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:24.652  6260  6260 W art     : b598f000-b5992000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:24.652  6260  6260 W art     : b5992000-b5993000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:24.652  6260  6260 W art     : b5993000-b5994000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:24.652  6260  6260 W art     : b5994000-b5998000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:24.652  6260  6260 W art     : b5998000-b5999000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5999000-b599a000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:24.652  6260  6260 W art     : b599a000-b599b000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:24.652  6260  6260 W art     : b599b000-b59ab000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:24.652  6260  6260 W art     : b59ab000-b59ac000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:24.652  6260  6260 W art     : b59ac000-b59ad000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:24.652  6260  6260 W art     : b59ad000-b59f3000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b59f3000-b59fc000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:24.652  6260  6260 W art     : b59fc000-b59fd000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:24.652  6260  6260 W art     : b59fd000-b59fe000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:24.652  6260  6260 W art     : b59ff000-b5a04000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:24.652  6260  6260 W art     : b5a04000-b5a05000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:24.652  6260  6260 W art     : b5a05000-b5a06000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:24.652  6260  6260 W art     : b5a06000-b5a09000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:24.652  6260  6260 W art     : b5a09000-b5a0a000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5a0a000-b5a0b000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:24.652  6260  6260 W art     : b5a0b000-b5a0c000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:24.652  6260  6260 W art     : b5a0d000-b5a25000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:24.652  6260  6260 W art     : b5a25000-b5a26000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5a26000-b5a27000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:24.652  6260  6260 W art     : b5a27000-b5a28000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:24.652  6260  6260 W art     : b5a29000-b5bc3000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:24.652  6260  6260 W art     : b5bc3000-b5bc4000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5bc4000-b5bd1000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:24.652  6260  6260 W art     : b5bd1000-b5bd2000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:24.652  6260  6260 W art     : b5bd2000-b5bd6000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:24.652  6260  6260 W art     : b5bd6000-b5bd7000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5bd7000-b5bd8000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:24.652  6260  6260 W art     : b5bd8000-b5bd9000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:24.652  6260  6260 W art     : b5bd9000-b5bec000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:24.652  6260  6260 W art     : b5bec000-b5bed000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:24.652  6260  6260 W art     : b5bed000-b5bee000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:24.652  6260  6260 W art     : b5bee000-b5bef000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:24.652  6260  6260 W art     : b5bef000-b5c3a000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:24.652  6260  6260 W art     : b5c3a000-b5c3b000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:24.652  6260  6260 W art     : b5c3b000-b5c3c000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:24.652  6260  6260 W art     : b5c3c000-b5c3e000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5c3f000-b5c50000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:24.652  6260  6260 W art     : b5c50000-b5c51000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5c51000-b5c52000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:24.652  6260  6260 W art     : b5c52000-b5c53000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:24.652  6260  6260 W art     : b5c54000-b5c5e000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:24.652  6260  6260 W art     : b5c5e000-b5c60000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:24.652  6260  6260 W art     : b5c60000-b5c61000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:24.652  6260  6260 W art     : b5c61000-b5c7a000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:24.652  6260  6260 W art     : b5c7a000-b5c7b000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:24.652  6260  6260 W art     : b5c7b000-b5c7e000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:24.652  6260  6260 W art     : b5c7e000-b5c82000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5c82000-b5cf6000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:24.652  6260  6260 W art     : b5cf6000-b5cf7000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5cf7000-b5cfa000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:24.652  6260  6260 W art     : b5cfa000-b5cfb000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:24.652  6260  6260 W art     : b5cfb000-b5cfc000 r--p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5cfc000-b5cff000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:24.652  6260  6260 W art     : b5cff000-b5d00000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:24.652  6260  6260 W art     : b5d00000-b5d01000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:24.652  6260  6260 W art     : b5d01000-b5d02000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d02000-b5d07000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:24.652  6260  6260 W art     : b5d07000-b5d08000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:24.652  6260  6260 W art     : b5d08000-b5d09000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:24.652  6260  6260 W art     : b5d09000-b5d0a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d0a000-b5d0d000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:24.652  6260  6260 W art     : b5d0d000-b5d0e000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:24.652  6260  6260 W art     : b5d0e000-b5d0f000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:24.652  6260  6260 W art     : b5d0f000-b5d10000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d10000-b5d14000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:24.652  6260  6260 W art     : b5d14000-b5d15000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:24.652  6260  6260 W art     : b5d15000-b5d16000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:24.652  6260  6260 W art     : b5d16000-b5d17000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:24.652  6260  6260 W art     : b5d17000-b5d1b000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:24.652  6260  6260 W art     : b5d1b000-b5d1c000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:24.652  6260  6260 W art     : b5d1c000-b5d1d000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:24.652  6260  6260 W art     : b5d1d000-b5d1e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d1e000-b5d2c000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:24.652  6260  6260 W art     : b5d2c000-b5d2d000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b5d2d000-b5d2e000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:24.652  6260  6260 W art     : b5d2e000-b5d2f000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:24.652  6260  6260 W art     : b5d2f000-b5d39000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:24.652  6260  6260 W art     : b5d39000-b5d3c000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:24.652  6260  6260 W art     : b5d3c000-b5d3d000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:24.652  6260  6260 W art     : b5d3d000-b5d3e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d3e000-b5d48000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:24.652  6260  6260 W art     : b5d48000-b5d4b000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:24.652  6260  6260 W art     : b5d4b000-b5d4c000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:24.652  6260  6260 W art     : b5d4c000-b5d50000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:24.652  6260  6260 W art     : b5d50000-b5d51000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:24.652  6260  6260 W art     : b5d51000-b5d52000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:24.652  6260  6260 W art     : b5d52000-b5d53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b5d53000-b5d60000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:24.652  6260  6260 W art     : b5d60000-b5d62000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:24.652  6260  6260 W art     : b5d62000-b5d63000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:24.652  6260  6260 W art     : b5d63000-b6175000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:24.652  6260  6260 W art     : b6175000-b6176000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b6176000-b617f000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:24.652  6260  6260 W art     : b617f000-b6183000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:24.652  6260  6260 W art     : b6183000-b6184000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b6184000-b618b000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:24.652  6260  6260 W art     : b618b000-b618c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:24.652  6260  6260 W art     : b618c000-b618d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:24.652  6260  6260 W art     : b618d000-b618e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b618e000-b61a9000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 12:25:24.652  6260  6260 W art     : b61a9000-b61aa000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 12:25:24.652  6260  6260 W art     : b61aa000-b61ab000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 12:25:24.652  6260  6260 W art     : b61ab000-b61ac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b61ac000-b61f8000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:24.652  6260  6260 W art     : b61f8000-b61f9000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b61f9000-b61fa000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:24.652  6260  6260 W art     : b61fa000-b61fb000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:24.652  6260  6260 W art     : b61fb000-b61fc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b61fc000-b6200000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:24.652  6260  6260 W art     : b6200000-b6201000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b6201000-b6202000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:24.652  6260  6260 W art     : b6202000-b6203000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:24.652  6260  6260 W art     : b6203000-b623b000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:24.652  6260  6260 W art     : b623b000-b623c000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:24.652  6260  6260 W art     : b623c000-b623d000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:24.652  6260  6260 W art     : b623d000-b623e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.652  6260  6260 W art     : b623e000-b62dc000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 12:25:24.652  6260  6260 W art     : b62dc000-b62dd000 ---p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b62dd000-b62fb000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 12:25:24.652  6260  6260 W art     : b62fb000-b62fc000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
,08-23 12:25:24.652  6260  6260 W art     : b62fc000-b646f000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:24.652  6260  6260 W art     : b646f000-b647a000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:24.652  6260  6260 W art     : b647a000-b647b000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:24.652  6260  6260 W art     : b647b000-b6592000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:24.652  6260  6260 W art     : b6592000-b659d000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:24.652  6260  6260 W art     : b659d000-b659e000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:24.652  6260  6260 W art     : b659e000-b65a2000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b65a2000-b65c6000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 12:25:24.652  6260  6260 W art     : b65c6000-b65c8000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 12:25:24.652  6260  6260 W art     : b65c8000-b65c9000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 12:25:24.652  6260  6260 W art     : b65c9000-b666f000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:24.652  6260  6260 W art     : b666f000-b667c000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:24.652  6260  6260 W art     : b667c000-b667d000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:24.652  6260  6260 W art     : b667d000-b667e000 rw-p 00000000 00:00 0 
08-23 12:25:24.652  6260  6260 W art     : b667e000-b66d1000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:24.662  6260  6260 W art     : b66d1000-b66d2000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b66d2000-b66d3000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:24.662  6260  6260 W art     : b66d3000-b66d4000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:24.662  6260  6260 W art     : b66d4000-b66d9000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b66d9000-b66eb000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:24.662  6260  6260 W art     : b66eb000-b66ec000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b66ec000-b66ed000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:24.662  6260  6260 W art     : b66ed000-b66ee000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:24.662  6260  6260 W art     : b66ee000-b66f5000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:24.662  6260  6260 W art     : b66f5000-b66f6000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:24.662  6260  6260 W art     : b66f6000-b66f7000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:24.662  6260  6260 W art     : b66f7000-b66f8000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b66f8000-b66fb000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:24.662  6260  6260 W art     : b66fb000-b66fc000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:24.662  6260  6260 W art     : b66fc000-b66fd000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:24.662  6260  6260 W art     : b66fd000-b6701000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:24.662  6260  6260 W art     : b6701000-b6702000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:24.662  6260  6260 W art     : b6702000-b6703000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:24.662  6260  6260 W art     : b6703000-b6711000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:24.662  6260  6260 W art     : b6711000-b6712000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6712000-b6713000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:24.662  6260  6260 W art     : b6713000-b6714000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:24.662  6260  6260 W art     : b6714000-b671d000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:24.662  6260  6260 W art     : b671d000-b671e000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:24.662  6260  6260 W art     : b671e000-b671f000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:24.662  6260  6260 W art     : b671f000-b6785000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:24.662  6260  6260 W art     : b6785000-b6786000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6786000-b6788000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:24.662  6260  6260 W art     : b6788000-b6791000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:24.662  6260  6260 W art     : b6791000-b6794000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6794000-b682b000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:24.662  6260  6260 W art     : b682b000-b682d000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:24.662  6260  6260 W art     : b682d000-b682e000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:24.662  6260  6260 W art     : b682e000-b682f000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b682f000-b6b50000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 12:25:24.662  6260  6260 W art     : b6b50000-b6b51000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6b51000-b6b6c000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 12:25:24.662  6260  6260 W art     : b6b6c000-b6b70000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 12:25:24.662  6260  6260 W art     : b6b70000-b6b75000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6b75000-b6b7d000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:24.662  6260  6260 W art     : b6b7d000-b6b7e000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:24.662  6260  6260 W art     : b6b7e000-b6b7f000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:24.662  6260  6260 W art     : b6b7f000-b6bad000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:24.662  6260  6260 W art     : b6bad000-b6bae000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6bae000-b6bb5000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:24.662  6260  6260 W art     : b6bb5000-b6bb6000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:24.662  6260  6260 W art     : b6bb6000-b6bfc000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:24.662  6260  6260 W art     : b6bfc000-b6bfd000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6bfd000-b6c00000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:24.662  6260  6260 W art     : b6c00000-b6c01000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:24.662  6260  6260 W art     : b6c01000-b6c1c000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:24.662  6260  6260 W art     : b6c1c000-b6c20000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:24.662  6260  6260 W art     : b6c20000-b6c21000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:24.662  6260  6260 W art     : b6c21000-b6c6e000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:24.662  6260  6260 W art     : b6c6e000-b6c6f000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6c6f000-b6c7b000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:24.662  6260  6260 W art     : b6c7b000-b6c7c000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:24.662  6260  6260 W art     : b6c7c000-b6c89000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 12:25:24.662  6260  6260 W art     : b6c89000-b6c8a000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6c8a000-b6c8b000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 12:25:24.662  6260  6260 W art     : b6c8b000-b6c8c000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 12:25:24.662  6260  6260 W art     : b6c8c000-b6c94000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:24.662  6260  6260 W art     : b6c94000-b6c95000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6c95000-b6c96000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:24.662  6260  6260 W art     : b6c96000-b6c97000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:24.662  6260  6260 W art     : b6c97000-b6c9e000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:24.662  6260  6260 W art     : b6c9e000-b6c9f000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:24.662  6260  6260 W art     : b6c9f000-b6ca0000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:24.662  6260  6260 W art     : b6ca0000-b6cb4000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:24.662  6260  6260 W art     : b6cb4000-b6cb6000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:24.662  6260  6260 W art     : b6cb6000-b6cb7000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:24.662  6260  6260 W art     : b6cb7000-b6cdf000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:24.662  6260  6260 W art     : b6cdf000-b6ce1000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:24.662  6260  6260 W art     : b6ce1000-b6ce2000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:24.662  6260  6260 W art     : b6ce2000-b6ce5000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:24.662  6260  6260 W art     : b6ce5000-b6ce6000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:24.662  6260  6260 W art     : b6ce6000-b6ce7000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:24.662  6260  6260 W art     : b6ce7000-b6cf0000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:24.662  6260  6260 W art     : b6cf0000-b6cf1000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:24.662  6260  6260 W art     : b6cf1000-b6cf2000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:24.662  6260  6260 W art     : b6cf2000-b6d12000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 12:25:24.662  6260  6260 W art     : b6d12000-b6d13000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 12:25:24.662  6260  6260 W art     : b6d13000-b6d14000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 12:25:24.662  6260  6260 W art     : b6d14000-b6d87000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 12:25:24.662  6260  6260 W art     : b6d87000-b6d8b000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 12:25:24.662  6260  6260 W art     : b6d8b000-b6d8e000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 12:25:24.662  6260  6260 W art     : b6d8e000-b6d98000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6d98000-b6e20000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:24.662  6260  6260 W art     : b6e20000-b6e21000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6e21000-b6e25000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:24.662  6260  6260 W art     : b6e25000-b6e26000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:24.662  6260  6260 W art     : b6e26000-b6e27000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6e27000-b6e50000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:24.662  6260  6260 W art     : b6e50000-b6e51000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6e51000-b6e54000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:24.662  6260  6260 W art     : b6e54000-b6e55000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:24.662  6260  6260 W art     : b6e55000-b6f2f000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:24.662  6260  6260 W art     : b6f2f000-b6f36000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:24.662  6260  6260 W art     : b6f36000-b6f3e000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:24.662  6260  6260 W art     : b6f3e000-b6f3f000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:24.662  6260  6260 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 12:25:24.662  6260  6260 W art     : b6f41000-b6f42000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6f42000-b6f45000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6f45000-b6f6a000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:24.662  6260  6260 W art     : b6f6a000-b6f6b000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6f6b000-b6f72000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:24.662  6260  6260 W art     : b6f72000-b6f73000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:24.662  6260  6260 W art     : b6f73000-b6f7a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:24.662  6260  6260 W art     : b6f7a000-b6f7b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:24.662  6260  6260 W art     : b6f7b000-b6f7c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:24.662  6260  6260 W art     : b6f7c000-b6f7d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6f7d000-b6f95000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 12:25:24.662  6260  6260 W art     : b6f95000-b6f96000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6f96000-b6f97000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 12:25:24.662  6260  6260 W art     : b6f97000-b6f98000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 12:25:24.662  6260  6260 W art     : b6f98000-b6fa6000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:24.662  6260  6260 W art     : b6fa6000-b6fa7000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6fa7000-b6fa8000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:24.662  6260  6260 W art     : b6fa8000-b6fa9000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:24.662  6260  6260 W art     : b6fa9000-b6faa000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:24.662  6260  6260 W art     : b6faa000-b6fac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6fac000-b6fad000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6fad000-b6fae000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:24.662  6260  6260 W art     : b6fae000-b6faf000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 12:25:24.662  6260  6260 W art     : b6faf000-b6fb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:24.662  6260  6260 W art     : b6fb0000-b6fd0000 r--s 00000000 00:0b 6572       /dev/__properties__
08-23 12:25:24.662  6260  6260 W art     : b6fd0000-b6fd1000 r--p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6fd1000-b6fd2000 ---p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6fd2000-b6fd4000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 12:25:24.662  6260  6260 W art     : b6fd4000-b6fd5000 r-xp 00000000 00:00 0          [sigpage]
08-23 12:25:24.662  6260  6260 W art     : b6fd5000-b6ff0000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 12:25:24.662  6260  6260 W art     : b6ff0000-b6ff1000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 12:25:24.662  6260  6260 W art     : b6ff1000-b6ff3000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 12:25:24.662  6260  6260 W art     : b6ff3000-b6ff5000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : b6ff5000-b6ffa000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 12:25:24.662  6260  6260 W art     : b6ffa000-b6ffb000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 12:25:24.662  6260  6260 W art     : b6ffb000-b6ffc000 rw-p 00000000 00:00 0 
08-23 12:25:24.662  6260  6260 W art     : be89b000-be8bc000 rw-p 00000000 00:00 0          [stack]
08-23 12:25:24.662  6260  6260 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 12:25:24.692   765   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e70e009 6350:com.android.mms/u0a49}
08-23 12:25:24.692  6260  6260 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 12:25:24.702   765  2044 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-23 12:25:24.722  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.722  6362  6362 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.742  6260  6260 I Radio-JNI: register_android_hardware_Radio DONE
08-23 12:25:24.752  6260  6260 E AffinityControl: AffinityControl: registerfunction enter
08-23 12:25:24.752  6350  6350 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-23 12:25:24.772  6260  6260 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 12:25:24.772  6362  6362 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-23 12:25:24.772  4043  6367 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-23 12:25:24.782   765  2127 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 12:25:24.792  6362  6362 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-23 12:25:24.792  6362  6362 D AASAservice: onCreate()
08-23 12:25:24.802  6350  6350 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-23 12:25:24.802  6350  6350 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-23 12:25:24.812   765  2127 D ActivityManager: mDVFSHelper.acquire()
08-23 12:25:24.812   765  2127 V WindowManager: addAppToken: AppWindowToken{93e73c5 token=Token{5be2a3c ActivityRecord{e9f642f u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-23 12:25:24.822   765   895 D SecWifiDisplayUtil: Metadata value : none
08-23 12:25:24.822   765   895 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{114567d V.E...... R.....ID 0,0-0,0}
08-23 12:25:24.822   765   895 D ISSUE_DEBUG: InputChannelName : 654c1c3 Starting com.test.thalitest
08-23 12:25:24.832  6382  6382 E Zygote  : v2
08-23 12:25:24.832  6382  6382 I libpersona: KNOX_SDCARD checking this for 10004
08-23 12:25:24.832  6382  6382 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:24.832  6382  6382 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:24.832  6382  6382 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:24.832  6382  6382 E Zygote  : accessInfo : 0
08-23 12:25:24.832  6382  6382 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 12:25:24.842   765  2127 I ActivityManager: Start proc 6382:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 12:25:24.842   765  2127 D InputDispatcher: Focused application set to: xxxx
08-23 12:25:24.842   765  2127 D InputDispatcher: Focus left window: 4343
08-23 12:25:24.842  6260  6260 D AndroidRuntime: Shutting down VM
08-23 12:25:24.852   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-23 12:25:24.862  6382  6382 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:24.862  6382  6382 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:24.862   765   837 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d79f065 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 12:25:24.862  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-23 12:25:24.872  5319  5319 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-23 12:25:24.872   765   895 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
08-23 12:25:24.872   765   895 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:24.872   765   895 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-23 12:25:24.872   765   895 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 12:25:24.872   765   895 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 12:25:24.872   765  2050 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 12:25:24.872   765  2050 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 12:25:24.892   765  2050 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 12:25:24.902   765   895 V WindowStateAnimator: Finishing drawing window Window{654c1c3 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 12:25:24.912  1669  1835 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 12:25:24.912  1669  1669 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 12:25:24.912   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbeffe364
08-23 12:25:24.922   293   361 I SurfaceFlinger: id=14 Removed YUIInstallC (6/10)
08-23 12:25:24.922   293   358 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/10)
08-23 12:25:24.922   293  1366 D libEGL  : eglTerminate EGLDisplay = 0xb4a3f64c
08-23 12:25:24.922   293  1366 D libEGL  : eglTerminate EGLDisplay = 0xb4a3f64c
08-23 12:25:24.922   293   358 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
08-23 12:25:24.922   293  4706 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-23 12:25:24.932  4343  4343 V ActivityThread: updateVisibility : ActivityRecord{4bd356e token=android.os.BinderProxy@368fad4 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 12:25:24.932   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
08-23 12:25:24.932  2340  3137 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 12:25:24.932  1669  1669 V ActivityThread: updateVisibility : ActivityRecord{1ac950d token=android.os.BinderProxy@b599da6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 12:25:24.932  1669  1669 D Launcher: onTrimMemory. Level: 20
,08-23 12:25:25.212   765  2050 I WindowManager: Screenshot max retries 4 of Token{5be2a3c ActivityRecord{e9f642f u0 com.test.thalitest/.MainActivity t168}} appWin=Window{654c1c3 u0 d0 Starting com.test.thalitest} drawState=4
,08-23 12:25:25.222   765   834 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-23 12:25:25.232   765   837 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{654c1c3 u0 d0 Starting com.test.thalitest}
08-23 12:25:25.232  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
,08-23 12:25:25.242  6350  6350 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-23 12:25:25.242  6382  6382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 12:25:25.252  6350  6400 D Mms/ArtClassLoader: init before art third
,08-23 12:25:25.252  6350  6399 D Mms/ArtClassLoader: init before art second
,08-23 12:25:25.252  6350  6398 D Mms/ArtClassLoader: init before art first
,08-23 12:25:25.262   765  3411 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 12:25:25.262  6350  6350 D Mms/TelephonyPermission: start operation mode monitor
,08-23 12:25:25.262  6350  6350 D Mms/TelephonyPermission: User ID is null set current User Id
,08-23 12:25:25.292  6382  6382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 12:25:25.292  6382  6382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 12:25:25.302  6382  6382 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-23 12:25:25.312  1788  6336 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 790 ms] updated apps [took 790 ms] 
,08-23 12:25:25.312  6350  6350 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 12:25:25.312  6350  6350 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 12:25:25.322  6350  6350 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 12:25:25.322  6350  6350 D Mms/TelephonyPermission: isDefault true
,08-23 12:25:25.322  6350  6350 D Mms/MmsApp: onCreate() com.android.mms
,08-23 12:25:25.332  6382  6382 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 12:25:25.342  6350  6400 D Mms/ArtClassLoader: init [DONE] art
,08-23 12:25:25.342  6382  6382 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 12:25:25.352  6382  6382 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1470-1473)
,08-23 12:25:25.352  6382  6382 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 12:25:25.372  6350  6350 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-23 12:25:25.372  6382  6408 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-23 12:25:25.372  6382  6382 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a152b6}
08-23 12:25:25.372  6382  6382 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 12:25:25.372  6382  6382 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 12:25:25.382  6350  6350 D Mms/MmsApp: [start]    initCountryIso consume time = 135.805053
,08-23 12:25:25.382   765  2103 D CountryDetector: The first listener is added
,08-23 12:25:25.382  6382  6382 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 12:25:25.382  6350  6350 D Mms/MmsApp: [end]    initCountryIso consume time = 5.834062
08-23 12:25:25.382  6350  6350 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.094271
,08-23 12:25:25.392  6350  6350 D Mms/MmsConfig: before partial update
,08-23 12:25:25.412  6382  6382 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 12:25:25.412  6382  6382 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 12:25:25.412  6382  6382 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 12:25:25.412  6382  6382 I Adreno-EGL: Local Branch: ss
08-23 12:25:25.412  6382  6382 I Adreno-EGL: Remote Branch: 
08-23 12:25:25.412  6382  6382 I Adreno-EGL: Local Patches: 
08-23 12:25:25.412  6382  6382 I Adreno-EGL: Reconstruct Branch: 
,08-23 12:25:25.422  6382  6382 D libEGL  : eglInitialize EGLDisplay = 0xbe82edac
,08-23 12:25:25.422  6350  6350 D Mms/MmsConfig: Load Resize quality : 80
,08-23 12:25:25.432  6350  6350 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-23 12:25:25.432  6350  6350 D EasySignUpManager_1.0.5: isAuth is false
,08-23 12:25:25.432  6350  6350 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-23 12:25:25.432  6350  6398 D Mms/ArtClassLoader: init [DONE] art
,08-23 12:25:25.442  6350  6350 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-23 12:25:25.442  6350  6350 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-23 12:25:25.442  6350  6350 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 12:25:25.442  6350  6350 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-23 12:25:25.442  6350  6350 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 12:25:25.442  6350  6350 D EasySignUpManager_1.0.5: isAuth is false
08-23 12:25:25.442  6350  6350 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-23 12:25:25.442  6350  6350 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-23 12:25:25.452  1655  1667 D TP/MmsSmsProvider: query, match:2117, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.452  1655  1667 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.981 ms
,08-23 12:25:25.462   765  2043 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-23 12:25:25.462   765  2043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-23 12:25:25.462  6350  6350 E CscParser: mps_code.dat does not exist
08-23 12:25:25.462  6350  6350 E CscParser: customer_path =/system/csc/customer.xml
08-23 12:25:25.462  6350  6350 E CscParser: fileName + /system/csc/customer.xml
,08-23 12:25:25.462  6350  6399 D Mms/ArtClassLoader: init [DONE] art
,08-23 12:25:25.472  6350  6350 E CscParser: mps_code.dat does not exist
08-23 12:25:25.472  6350  6350 E CscParser: customer_path =/system/csc/customer.xml
08-23 12:25:25.472  6350  6350 E CscParser: fileName + /system/csc/customer.xml
,08-23 12:25:25.482  6350  6350 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-23 12:25:25.492  6350  6350 D Mms/MmsConfig:  enable multiwindow = true
,08-23 12:25:25.492  6350  6350 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-23 12:25:25.492  6350  6350 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-23 12:25:25.492  6350  6350 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-23 12:25:25.492  6350  6350 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-23 12:25:25.492  6350  6350 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-23 12:25:25.492  6350  6350 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 12:25:25.492  6350  6350 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-23 12:25:25.502  6350  6350 D Mms/MmsConfig: [end]    init() consume time = 115.83974
,08-23 12:25:25.512  6350  6350 D Mms/Contact: [start]    init() consume time = 6.767448
,08-23 12:25:25.512  6382  6382 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-23 12:25:25.522  1655  1874 D TP/MmsSmsProvider: query, match:13, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.522  6350  6350 D Mms/Contact: [end]    init consume time = 11.971146
,08-23 12:25:25.522  1655  1874 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.408 ms
,08-23 12:25:25.522  6350  6350 D Mms:transaction: roaming -> false (slotId = 0)
08-23 12:25:25.522  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 12:25:25.522  6350  6350 D Mms:transaction: auto download without roaming -> true
08-23 12:25:25.522  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-23 12:25:25.522  6350  6350 D Mms:transaction: roaming -> false (slotId = 1)
08-23 12:25:25.522  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 12:25:25.522  6350  6350 D Mms:transaction: auto download without roaming -> true
08-23 12:25:25.522  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 12:25:25.522  6350  6350 D Mms:transaction: auto download during roaming secondary -> false
08-23 12:25:25.522  6350  6350 D Mms:transaction: mAutoDownload ------> true
,08-23 12:25:25.522  6382  6382 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 12:25:25.532  6382  6382 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-23 12:25:25.532  6382  6382 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-23 12:25:25.532  6350  6435 D Mms/DraftCache: [start]    rebuildCache consume time = 9.041041
,08-23 12:25:25.532  6382  6382 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-23 12:25:25.542  1655  1666 D TP/MmsSmsProvider: query, match:12, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.542  1655  1666 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.220 ms
,08-23 12:25:25.542  6350  6435 D Mms/DraftCache: [end]    rebuildCache consume time = 13.460521
,08-23 12:25:25.552  6382  6382 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-23 12:25:25.552  6382  6382 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 12:25:25.562  6350  6350 D ComposerPerformance: 1471947925577 ms / [DONE] Composer constructor
,08-23 12:25:25.572  6350  6437 D Mms/Conversation: [start]    init() consume time = 25.368802
,08-23 12:25:25.572  1655  1667 D TP/MmsSmsProvider: delete, match:1, calling pid = 6350
,08-23 12:25:25.572  1655  1667 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 12:25:25.572  1655  1667 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-23 12:25:25.572  6350  6350 D CII     : Log Level [5]
08-23 12:25:25.572  6350  6350 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-23 12:25:25.572  1655  1667 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-23 12:25:25.572  1655  1667 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 12:25:25.572  1655  1667 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-23 12:25:25.572  1655  1667 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-23 12:25:25.572  6350  6350 I Mms/ReservationManager: ReservationManager()
08-23 12:25:25.572  6350  6350 I Mms/ReservationManager: resetAfterConnected()
,08-23 12:25:25.582  1655  2658 D TP/MmsSmsProvider: query, match:7, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.582  1655  2658 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.341 ms
,08-23 12:25:25.592  1655  1667 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-23 12:25:25.592  1655  1667 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-23 12:25:25.592  1655  1667 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 12:25:25.592  1655  1667 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 3.689 ms
08-23 12:25:25.592  1655  1667 D TP/MmsSmsProvider: need read changed broadcast:false
,08-23 12:25:25.592  6350  6437 D Mms/Conversation: [end]    init consume time = 20.616667
,08-23 12:25:25.592  6350  6350 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-23 12:25:25.592  6350  6437 D Mms/MessagingNotification: [start]    init() consume time = 2.738854
08-23 12:25:25.592  6350  6437 D Mms/MessagingNotification: [end]    init consume time = 1.310364
08-23 12:25:25.592  6350  6440 D Mms/Synchronizer: [start]    doSync consume time = 2.664323
08-23 12:25:25.592  6350  6439 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.291771
08-23 12:25:25.592  1655  1667 D TP/MmsSmsProvider: update, match:300, calling pid = 6350
08-23 12:25:25.592  1655  1667 V TP/MmsSmsProvider: syncDBData start
08-23 12:25:25.592  1655  1667 V TP/MmsSmsProvider: syncDBData sms end
08-23 12:25:25.602  1655  1667 V TP/MmsSmsProvider: syncDBData mms end
08-23 12:25:25.602  1655  1667 V TP/MmsSmsProvider: syncDBData end
08-23 12:25:25.602  1655  1667 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.121 ms
08-23 12:25:25.602  6350  6440 D Mms/Synchronizer: [end]    doSync consume time = 4.398334
,08-23 12:25:25.602  6350  6350 D Mms/MmsApp: [end]    onCreate() consume time = 5.123958
08-23 12:25:25.602  6350  6350 D Mms/MmsApp: [end]    onCreate() consume time = 0.077552
,08-23 12:25:25.602  1655  1874 D TP/MmsSmsProvider: query, match:0, calling pid = 6350, accessRestricted = false
08-23 12:25:25.602  1655  1874 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-23 12:25:25.602  1655  1874 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.534 ms
,08-23 12:25:25.612  6350  6350 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-23 12:25:25.612  6350  6350 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-23 12:25:25.612  6350  6350 D Mms:transaction: roaming -> false (slotId = 0)
08-23 12:25:25.612  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 12:25:25.612  6350  6350 D Mms:transaction: auto download without roaming -> true
08-23 12:25:25.612  6350  6350 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 12:25:25.612  6350  6350 D Mms:transaction: mAutoDownload ------> true
,08-23 12:25:25.612  1655  1666 D TP/MmsSmsProvider: query, match:400, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.622   765  2127 I ActivityManager: Start proc 6441:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-23 12:25:25.622  6441  6441 E Zygote  : v2
08-23 12:25:25.622  6441  6441 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:25.622  6441  6441 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:25.622  6441  6441 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:25.622  6441  6441 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:25.622  6441  6441 E Zygote  : accessInfo : 0
,08-23 12:25:25.622  6350  6439 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 21.21401
,08-23 12:25:25.632  6093  6115 D BadgeProvider: query, [selection] : package=?
,08-23 12:25:25.632  6350  6437 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-23 12:25:25.652  6382  6382 D SecWifiDisplayUtil: Metadata value : none
,08-23 12:25:25.652  1655  1666 D TP/SmsProvider: query,matched:26, calling pid = 6350
,08-23 12:25:25.652  1655  1666 D TP/SmsProvider: query, match 26:Elapsed time : 1.075 ms
,08-23 12:25:25.662  6382  6382 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1c65f84 I.E...... R.....ID 0,0-0,0}
,08-23 12:25:25.662  6441  6441 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:25.662  6441  6441 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:25.662  6382  6456 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 12:25:25.662   765  2043 D ISSUE_DEBUG: InputChannelName : afa89d0 com.test.thalitest/com.test.thalitest.MainActivity
,08-23 12:25:25.672   765  1497 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98a3dc9 6441:com.samsung.android.bbc.bbcagent/1000}
,08-23 12:25:25.672   765  2050 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-23 12:25:25.672   765  2050 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 12:25:25.672   765   765 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 12:25:25.672   765   765 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-23 12:25:25.682  1655  2658 D TP/MmsSmsProvider: query, match:6, calling pid = 6350, accessRestricted = false
,08-23 12:25:25.682  6441  6441 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-23 12:25:25.682  1655  2658 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.086 ms
,08-23 12:25:25.692  6382  6382 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6382
,08-23 12:25:25.692   765   777 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6382 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 12:25:25.702   765  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-23 12:25:25.702   765  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 12:25:25.702   765  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 12:25:25.702   765  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-23 12:25:25.702   765  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 12:25:25.702   765  1680 I ActivityManager: Killing 5573:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-23 12:25:25.712  6382  6408 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-23 12:25:25.722  6382  6382 D SecWifiDisplayUtil: Metadata value : none
,08-23 12:25:25.722  6459  6459 E Zygote  : v2
08-23 12:25:25.722  6459  6459 I libpersona: KNOX_SDCARD checking this for 10024
08-23 12:25:25.722  6459  6459 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:25.722   765  1497 I ActivityManager: Start proc 6459:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-23 12:25:25.722  6459  6459 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:25.722  6459  6459 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:25.722  6459  6459 E Zygote  : accessInfo : 0
,08-23 12:25:25.722  6459  6459 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-23 12:25:25.732   293   293 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-23 12:25:25.742   765  2140 D InputDispatcher: Focus entered window: 6382
,08-23 12:25:25.742   765   895 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
,08-23 12:25:25.742  6382  6456 D libEGL  : eglInitialize EGLDisplay = 0x9c97a7c4
08-23 12:25:25.742   765   895 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:25.742  6382  6456 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:25:25.742   765   895 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-23 12:25:25.742   765   895 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 12:25:25.752   765  2043 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
08-23 12:25:25.752  6441  6441 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-23 12:25:25.762  6459  6459 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:25.762  6459  6459 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:25.772   765  2050 I ActivityManager: Killing 5130:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-23 12:25:25.802  6382  6382 V ActivityThread: updateVisibility : ActivityRecord{ad90c8f token=android.os.BinderProxy@7cd8197 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 12:25:25.802  6459  6459 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-23 12:25:25.802  6473  6473 E Zygote  : v2
08-23 12:25:25.802  6473  6473 I libpersona: KNOX_SDCARD checking this for 10097
08-23 12:25:25.802   765  2103 I ActivityManager: Start proc 6473:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-23 12:25:25.802  6473  6473 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:25.802  6473  6473 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:25.802  6473  6473 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:25.802   765  2103 I ActivityManager: Killing 5102:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-23 12:25:25.802  6473  6473 E Zygote  : accessInfo : 0
08-23 12:25:25.802  6473  6473 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-23 12:25:25.812   765  1318 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-23 12:25:25.812  6382  6382 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-23 12:25:25.832  6382  6382 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 12:25:25.842  6473  6473 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:25.842  6473  6473 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:25.852   765  2050 V WindowStateAnimator: Finishing drawing window Window{afa89d0 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-23 12:25:25.852  6382  6382 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 12:25:25.852   765   779 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 12:25:25.852   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbeffe364
,08-23 12:25:25.862   765  1680 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{146dd01 6473:com.google.android.apps.docs/u0a97}
,08-23 12:25:25.862   765   895 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 12:25:25.862   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 12:25:25.862   765   765 I KnoxTimeoutHandler: SD activityfalse
08-23 12:25:25.862   765   895 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +649ms (total +1s47ms)
,08-23 12:25:25.872   765   895 D ActivityManager: mDVFSHelper.release()
,08-23 12:25:25.872   765   895 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e9f642f u0 com.test.thalitest/.MainActivity t168} time:101994
,08-23 12:25:25.872   765   895 D ViewRootImpl: #3 mView = null
,08-23 12:25:25.872  6382  6487 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 12:25:25.872  6382  6487 D libEGL  : eglInitialize EGLDisplay = 0x9ae7f3ec
,08-23 12:25:25.872   293  1366 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
,08-23 12:25:25.872   293   361 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
,08-23 12:25:25.892  6382  6382 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 12:25:25.892   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
,08-23 12:25:25.892  6382  6382 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7cd8197 time:102012
,08-23 12:25:25.902  6459  6459 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-23 12:25:25.912   765  1668 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-23 12:25:25.912  6473  6473 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 12:25:25.932  6382  6382 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6382
,08-23 12:25:25.942   765   774 I art     : Background partial concurrent mark sweep GC freed 60734(3MB) AllocSpace objects, 9(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.977ms total 158.410ms
,08-23 12:25:25.952  6473  6473 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-23 12:25:25.972  6350  6437 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 12:25:25.982  6459  6459 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-23 12:25:26.002  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-23 12:25:26.002  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 12:25:26.012  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-23 12:25:26.022  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 12:25:26.022  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 12:25:26.022  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 12:25:26.022  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 12:25:26.022  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-23 12:25:26.072  6134  6134 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,08-23 12:25:26.072  6134  6134 D PreloadUpdateManagerStateMachine: exit::IDLE
08-23 12:25:26.072  6134  6134 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-23 12:25:26.072  6134  6134 D hcjo    : AutoUpdateTriggerManager:REQUEST2:requestInterval
,08-23 12:25:26.082  6382  6382 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:25:26.102  6134  6134 I Volley  : RestApi Request Add : 2307
,08-23 12:25:26.102  6134  6134 E File    : fail readDirectory() errno=2
,08-23 12:25:26.202   765  6159 I HarmonyEASService: Updating for all 1
,08-23 12:25:26.212  6382  6493 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1702889168
,08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 12:25:26.212  6382  6493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242b1dd added. We now have 1 listener(s)
,08-23 12:25:26.212  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-23 12:25:26.212  6382  6493 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-23 12:25:26.222  6382  6493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:25:26.222  6382  6493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 12:25:26.222  6382  6493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b33520 added. We now have 1 listener(s)
08-23 12:25:26.222  6382  6493 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:25:26.222  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:25:26.222  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 12:25:26.222  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:25:26.222   765  3412 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 12:25:26.222  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:25:26.222  6382  6493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 12:25:26.232  6382  6493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:25:26.232  6382  6493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-23 12:25:26.232  6382  6493 D BluetoothAdapter: STATE_ON
,08-23 12:25:26.242  6382  6493 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:25:26.242  6382  6493 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:25:26.242  6382  6493 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:25:26.242  6382  6493 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:25:26.242  6382  6493 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 12:25:26.242  6382  6382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:26.242  6382  6382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:26.262  6382  6382 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:25:26.312  4043  4951 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-23 12:25:26.352  6473  6497 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-23 12:25:26.352  6473  6497 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 12:25:26.352  6473  6497 I GAv4    :   adb logcat -s GAv4
,08-23 12:25:26.372  6473  6497 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 12:25:26.372   765  1416 V AlarmManager:  remove PendingIntent] PendingIntent{18a932c: PendingIntentRecord{e041f5 com.google.android.apps.docs broadcastIntent}}
,08-23 12:25:26.382  6473  6497 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:25:26.382  4043  4951 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 12:25:26.392  6473  6497 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:25:26.432  6473  6503 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:25:26.472   765  1235 V AlarmManager: Expired Alarm result :4
,08-23 12:25:26.502  4821  4874 I Finsky  : [665] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-23 12:25:26.512  4043  4951 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-23 12:25:26.532  6473  6473 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-23 12:25:26.532   765  2102 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 12:25:26.532   765  2102 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 12:25:26.532   765  2102 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-23 12:25:26.532   765  2102 D BatteryService: stay LED for charging
,08-23 12:25:26.542  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 12:25:26.542   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 12:25:26.542  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 12:25:26.542   765   765 I MotionRecognitionService: Plugged
08-23 12:25:26.542  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 12:25:26.542   765   765 D MotionRecognitionService:   cableConnection= 1
08-23 12:25:26.542  1998  1998 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 12:25:26.542   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 12:25:26.542  1998  2627 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 12:25:26.542   765   765 D MotionRecognitionService: skip setTransmitPower. 
08-23 12:25:26.542  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 12:25:26.552  6473  6473 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-23 12:25:26.562  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 12:25:26.562  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 12:25:26.592  6473  6497 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-23 12:25:26.592  6473  6497 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-23 12:25:26.592  6473  6497 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-23 12:25:26.592  6473  6497 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-23 12:25:26.662  6509  6509 E Zygote  : v2
08-23 12:25:26.662  6509  6509 I libpersona: KNOX_SDCARD checking this for 10098
08-23 12:25:26.662  6509  6509 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:26.662  6509  6509 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:26.662  6509  6509 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:26.672  6509  6509 E Zygote  : accessInfo : 0
08-23 12:25:26.672   765  2103 I ActivityManager: Start proc 6509:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-23 12:25:26.672  6509  6509 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-23 12:25:26.702  6509  6509 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:26.702  6509  6509 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:26.712  1452  1452 D Recents : onTaskStackChanged
,08-23 12:25:26.712   765  2102 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efbbaad 6509:com.sec.android.automotive.drivelink/u0a98}
,08-23 12:25:26.722  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 12:25:26.732  6509  6509 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 12:25:26.752  6509  6509 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-23 12:25:26.792  6509  6509 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 12:25:26.812   765  2043 V AlarmManager:  remove PendingIntent] PendingIntent{28f3030: PendingIntentRecord{cc654a9 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 12:25:26.822  6509  6527 I GMPM    : App measurement is starting up
,08-23 12:25:26.822  6509  6509 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-23 12:25:26.832  6509  6527 E GMPM    : getGoogleAppId failed with status: 10
,08-23 12:25:26.832  6509  6527 E GMPM    : Uploading is not possible. App measurement disabled
,08-23 12:25:26.832   765  2044 V AlarmManager:  remove PendingIntent] PendingIntent{1f3ba2e: PendingIntentRecord{cc654a9 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 12:25:26.852  6509  6509 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-23 12:25:26.862  6509  6509 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-23 12:25:26.882  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 12:25:26.882  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 12:25:26.912  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 12:25:26.982   765  1487 I ActivityManager: Start proc 6535:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-23 12:25:26.982  6535  6535 E Zygote  : v2
08-23 12:25:26.982  6535  6535 I libpersona: KNOX_SDCARD checking this for 10032
08-23 12:25:26.982  6535  6535 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:26.982   765  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 12:25:26.982  6535  6535 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:26.982  6535  6535 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:26.982  6535  6535 E Zygote  : accessInfo : 0
08-23 12:25:26.982  6535  6535 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-23 12:25:27.012  6535  6535 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:27.012  6535  6535 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:27.012  6134  6549 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 12:25:27.012  6134  6549 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 12:25:27.022   309  1196 D EnterpriseController: netId is 0
08-23 12:25:27.022   309  1196 D Netd    : getNetworkForDns: using netid 502 for uid 10039
,08-23 12:25:27.022  6473  6498 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 12:25:27.032   765  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 12:25:27.042  6535  6535 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-23 12:25:27.062  6535  6535 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-23 12:25:27.082  6134  6549 I qtaguid : Tagging socket 21 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6134, getuid(): 10039
,08-23 12:25:27.122  6382  6494 W jxcore-log: Initializing JXcore engine
08-23 12:25:27.122  6382  6494 W jxcore-log: JXcore engine is ready
,08-23 12:25:27.142  6473  6498 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 12:25:27.152  6473  6498 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-23 12:25:27.152  6473  6498 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 12:25:27.162  6473  6498 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 12:25:27.172  2023  2023 E audit   : type=1400 msg=audit(1471947927.172:288): avc:  denied  { ioctl } for  pid=6494 comm="Thread-891" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 12:25:27.172  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:27.172  2023  2023 E audit   : type=1300 msg=audit(1471947927.172:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a6c33c8 items=0 ppid=352 ppcomm=main pid=6494 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 12:25:27.172  2023  2023 E audit   : type=1327 msg=audit(1471947927.172:288): proctitle="com.test.thalitest"
08-23 12:25:27.172  2023  2023 E audit   : type=1320 msg=audit(1471947927.172:288): 
,08-23 12:25:27.172  2023  2023 E audit   : type=1400 msg=audit(1471947927.172:289): avc:  denied  { ioctl } for  pid=6494 comm="Thread-891" path="socket:[39599]" dev="sockfs" ino=39599 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 12:25:27.172  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:27.172  2023  2023 E audit   : type=1300 msg=audit(1471947927.172:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a6c33c8 items=0 ppid=352 ppcomm=main pid=6494 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 12:25:27.172  2023  2023 E audit   : type=1327 msg=audit(1471947927.172:289): proctitle="com.test.thalitest"
08-23 12:25:27.172  2023  2023 E audit   : type=1320 msg=audit(1471947927.172:289): 
,08-23 12:25:27.192  6382  6494 W jxcore-log: Starting JXcore engine
,08-23 12:25:27.212  6134  6549 I qtaguid : Untagging socket 21
,08-23 12:25:27.222  6509  6509 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-23 12:25:27.222  6134  6134 D hcjo    : AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,08-23 12:25:27.222  6134  6134 D hcjo    : AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,08-23 12:25:27.222  6509  6509 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-23 12:25:27.232  6509  6509 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-23 12:25:27.232  4821  4874 I Finsky  : [665] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-23 12:25:27.232  4821  4821 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-23 12:25:27.232  6473  6498 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 12:25:27.242  6535  6535 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-23 12:25:27.242  6134  6134 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
08-23 12:25:27.242  6134  6134 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
08-23 12:25:27.242  6134  6134 D PreloadUpdateManagerStateMachine: entry::REQ_UPDATE_CHECK
,08-23 12:25:27.252  6509  6509 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 23 12:25:27 GMT+02:00 2016
,08-23 12:25:27.252  6134  6134 I Volley  : RestApi Request Add : 2315
,08-23 12:25:27.262  6509  6509 D DialogFlow: initQueue()
,08-23 12:25:27.262  6134  6550 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 12:25:27.262  6557  6557 E Zygote  : v2
08-23 12:25:27.262  6557  6557 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:27.262  6557  6557 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:27.262   765  2050 I ActivityManager: Start proc 6557:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-23 12:25:27.262  6557  6557 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:27.262  6557  6557 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:27.262  6557  6557 E Zygote  : accessInfo : 0
,08-23 12:25:27.272   765  2050 I ActivityManager: Killing 5489:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-23 12:25:27.272   765  2050 I ActivityManager: Killing 5154:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-23 12:25:27.272  6134  6550 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 12:25:27.272  6134  6550 I qtaguid : Tagging socket 23 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6134, getuid(): 10039
,08-23 12:25:27.282  6382  6494 W jxcore-log: Platform android
08-23 12:25:27.282  6382  6494 W jxcore-log: 
08-23 12:25:27.282  6382  6494 W jxcore-log: Process ARCH arm
08-23 12:25:27.282  6382  6494 W jxcore-log: 
,08-23 12:25:27.302   765  2000 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-23 12:25:27.302  6557  6557 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:27.302  6557  6557 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:27.302   765  1680 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-23 12:25:27.312   765   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e00ba19 6557:com.samsung.android.app.filterinstaller/1000}
,08-23 12:25:27.312  6535  6535 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-23 12:25:27.322  6557  6557 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-23 12:25:27.342  6557  6557 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-23 12:25:27.342  6557  6557 E FilterPackageIntentReceiver: This package is not a effect filter
,08-23 12:25:27.362  6573  6573 E Zygote  : v2
08-23 12:25:27.362  6573  6573 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:27.362  6573  6573 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:27.362  6573  6573 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:27.362  6573  6573 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:27.362   765  2127 I ActivityManager: Start proc 6573:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-23 12:25:27.362  6573  6573 E Zygote  : accessInfo : 0
08-23 12:25:27.362   765  2127 I ActivityManager: Killing 5056:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-23 12:25:27.372   765  1680 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-23 12:25:27.382  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:27.382  6573  6573 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:27.392   765  2102 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b342078 6573:com.samsung.helphub/1000}
,08-23 12:25:27.392   765  2050 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-23 12:25:27.402  6573  6573 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-23 12:25:27.412  6535  6535 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-23 12:25:27.412  6535  6535 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-23 12:25:27.412  6535  6535 D DialogFlow: initQueue()
,08-23 12:25:27.422  6573  6573 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-23 12:25:27.462  6585  6585 E Zygote  : v2
08-23 12:25:27.462  6585  6585 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:27.462  6585  6585 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:27.462  6585  6585 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:27.462  6585  6585 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:27.462   765  1416 I ActivityManager: Start proc 6585:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-23 12:25:27.462  6585  6585 E Zygote  : accessInfo : 0
,08-23 12:25:27.462   765  1416 I ActivityManager: Killing 5655:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-23 12:25:27.482   765  2102 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-23 12:25:27.492  6585  6585 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:27.492  6585  6585 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:27.492  6382  6494 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:25:27.492  6382  6494 I jxcore-log: 
,08-23 12:25:27.492  6382  6494 W jxcore-log: JXcore engine is started
,08-23 12:25:27.502   765  2140 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be69351 6585:com.samsung.android.app.mirrorlink/1000}
08-23 12:25:27.502  6382  6493 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 12:25:27.502  6382  6382 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:25:27.512  6585  6585 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-23 12:25:27.522  6382  6494 E jxcore  : Error!: missing name after . operator
08-23 12:25:27.522  6382  6494 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 12:25:27.522  6585  6585 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-23 12:25:27.522  6382  6382 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 12:25:27.522  6382  6382 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 12:25:27.532  6134  6550 I qtaguid : Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 6134, getuid(): 10039
08-23 12:25:27.532   765  2000 D InputDispatcher: Focused application set to: xxxx
08-23 12:25:27.532   765  2000 I ActivityManager: Killing 5437:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-23 12:25:27.542  6382  6382 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 12:25:27.542  6382  6382 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 12:25:27.542  6382  6382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:25:27.542  6382  6382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:25:27.542  6382  6382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:25:27.542  6382  6382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:25:27.542  6382  6382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242b1dd removed from the list
08-23 12:25:27.542  6382  6382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:25:27.542  6382  6382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b33520 removed from the list
08-23 12:25:27.542  6382  6382 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:25:27.542  6382  6382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 12:25:27.542  6382  6382 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:25:27.552  6382  6382 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-23 12:25:27.562  6382  6382 D ViewRootImpl: #3 mView = null
,08-23 12:25:27.562   293  4706 I SurfaceFlinger: id=17 Removed NainActivit (6/8)
,08-23 12:25:27.562   293  4706 I SurfaceFlinger: id=17 Removed NainActivit (-2/8)
,08-23 12:25:27.562   765  2127 D InputDispatcher: Focus left window: 6382
,08-23 12:25:27.562   765  2103 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-23 12:25:27.572   765   895 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
08-23 12:25:27.572   765   895 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:27.572   765   895 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-23 12:25:27.572   765   895 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 12:25:27.572  6382  6382 D cr_Ime  : [ImeAdapter.java:587] detach
,08-23 12:25:27.572  6382  6382 E ViewRootImpl: sendUserActionEvent() mView == null
,08-23 12:25:27.572   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
,08-23 12:25:27.582   765   779 D ActivityManager: mDVFSHelper.acquire()
,08-23 12:25:27.592   765   834 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.wssyncmldm
,08-23 12:25:27.592   765   779 V WindowOrientationListener: setCurrentAppOrientation :1
08-23 12:25:27.592   765   779 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-23 12:25:27.592  6585  6585 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-23 12:25:27.592  6585  6585 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-23 12:25:27.612   765  1487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6304504 5586:com.google.android.apps.plus/u0a134}
08-23 12:25:27.612  1669  1669 D Launcher: onRestart, Launcher: 224912450
08-23 12:25:27.612  1669  1669 D Launcher: onStart, Launcher: 224912450
08-23 12:25:27.612  1669  1669 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
08-23 12:25:27.612  1669  1669 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 12:25:27.612  1669  1669 D Launcher.HomeView: onStart
08-23 12:25:27.612  4343  4343 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(754/onResume)] 
,08-23 12:25:27.622  1669  1669 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-23 12:25:27.622  1669  1669 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-23 12:25:27.622  2340  2376 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
08-23 12:25:27.622  1669  1669 V ActivityThread: updateVisibility : ActivityRecord{1ac950d token=android.os.BinderProxy@b599da6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 12:25:27.622   765   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6304504 5586:com.google.android.apps.plus/u0a134}
,08-23 12:25:27.632   293   293 I SurfaceFlinger: id=18 createSurf (1080x1920),1 flag=4, Mauncher
,08-23 12:25:27.632   765   837 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d79f065 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 12:25:27.642  6350  6350 I Mms/MmsApp:  start initViewCache mms
08-23 12:25:27.642  6134  6550 I qtaguid : Untagging socket 23
08-23 12:25:27.642   765  2000 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-23 12:25:27.642   765  2000 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-23 12:25:27.642   765   765 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-23 12:25:27.642  4343  4343 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(747/onPause)] 
08-23 12:25:27.642   765   765 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 12:25:27.642   765   765 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-23 12:25:27.652   293   293 I SurfaceFlinger: id=19 createSurf (1146x1992),1 flag=4, YUIInstallC
08-23 12:25:27.652   765   837 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{90b2626 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
08-23 12:25:27.652  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-23 12:25:27.652   765   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6304504 5586:com.google.android.apps.plus/u0a134}
08-23 12:25:27.652   765  1497 D InputDispatcher: Focus entered window: 4343
08-23 12:25:27.652   765   895 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
08-23 12:25:27.652   765   895 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:27.662   765   895 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-23 12:25:27.662   765   895 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 12:25:27.662  6134  6134 D PreloadUpdateManagerStateMachine: execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
08-23 12:25:27.662  6134  6134 D PreloadUpdateManagerStateMachine: exit::REQ_UPDATE_CHECK
08-23 12:25:27.662  6134  6134 D PreloadUpdateManagerStateMachine: entry::NOTIFY_NOTIFICATION
08-23 12:25:27.662  6134  6134 D PreloadUpdateManagerStateMachine: exit::NOTIFY_NOTIFICATION
08-23 12:25:27.662  6134  6134 D PreloadUpdateManagerStateMachine: entry::FINISH
,08-23 12:25:27.672  6134  6134 D PreloadUpdateManagerStateMachine: exit::FINISH
,08-23 12:25:27.682  6134  6134 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-23 12:25:27.682   765  2127 I ActivityManager: Killing 5715:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
08-23 12:25:27.682   293   293 I SurfaceFlinger: id=20 createSurf (145x145),1 flag=4, YUIInstallC
,08-23 12:25:27.692  4343  4343 V ActivityThread: updateVisibility : ActivityRecord{4bd356e token=android.os.BinderProxy@368fad4 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-23 12:25:27.702   293   358 I SurfaceFlinger: id=19 Removed YUIInstallC (8/10)
,08-23 12:25:27.702   293  1366 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
,08-23 12:25:27.702   765   837 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{c7808bd u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-23 12:25:27.702  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,08-23 12:25:27.712   765  2102 D InputDispatcher: Focus left window: 4343
,08-23 12:25:27.712   765  2102 D InputDispatcher: Focus entered window: 4343
,08-23 12:25:27.712   765   895 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
,08-23 12:25:27.712   765   895 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:27.712   765   895 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-23 12:25:27.712   765   895 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 12:25:27.712   765  2050 V WindowStateAnimator: Finishing drawing window Window{c7808bd u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,08-23 12:25:27.722   765  1318 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 12:25:27.722   765   777 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-23 12:25:27.732  4343  4343 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@368fad4 time:103852
,08-23 12:25:27.732   765   895 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 12:25:27.732   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 12:25:27.732   765   765 I KnoxTimeoutHandler: SD activityfalse
,08-23 12:25:27.742  1965  1965 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 12:25:27.742   765   895 D ActivityManager: mDVFSHelper.release()
,08-23 12:25:27.742   765   895 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e0d57dd u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t167} time:103861
,08-23 12:25:27.822   765  1487 V WindowStateAnimator: Finishing drawing window Window{d79f065 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-23 12:25:27.822  1669  1669 D Launcher.HomeView: onStop
,08-23 12:25:27.822   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbeffe364
,08-23 12:25:27.832   765   895 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 12:25:27.832   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 12:25:27.832   765   895 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{584aed1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:103953
08-23 12:25:27.832   765   765 I KnoxTimeoutHandler: SD activityfalse
,08-23 12:25:27.862   765  2103 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-23 12:25:27.862   765  2050 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-23 12:25:27.862   765  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
08-23 12:25:27.862   765  1680 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-23 12:25:27.872   765  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
08-23 12:25:27.872   765  2000 I ActivityManager: Start proc 6608:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-23 12:25:27.872  6608  6608 E Zygote  : v2
08-23 12:25:27.872  6608  6608 I libpersona: KNOX_SDCARD checking this for 10165
08-23 12:25:27.872  6608  6608 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:27.872  6608  6608 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:27.872  6608  6608 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:27.872  6608  6608 E Zygote  : accessInfo : 0
08-23 12:25:27.872  6608  6608 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-23 12:25:27.872   765  2127 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-23 12:25:27.882   765  2044 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-23 12:25:27.882   765  2102 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-23 12:25:27.882   765   777 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-23 12:25:27.892   765  2050 I ActivityManager: Killing 5557:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-23 12:25:27.892  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:27.892  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:27.902   765  2000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5b0138d 6608:com.sec.kidsplat.installer/u0a165}
,08-23 12:25:27.912   765  2044 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-23 12:25:27.922  6608  6608 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-23 12:25:27.932  6608  6608 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-23 12:25:27.952   765  1680 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5b0138d 6608:com.sec.kidsplat.installer/u0a165}
,08-23 12:25:27.962  6608  6608 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-23 12:25:27.982   765  2000 I ActivityManager: Start proc 6620:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-23 12:25:27.982  6620  6620 E Zygote  : v2
08-23 12:25:27.982  6620  6620 I libpersona: KNOX_SDCARD checking this for 10142
08-23 12:25:27.982  6620  6620 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 12:25:27.982  6620  6620 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:27.982  6620  6620 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:27.982  6620  6620 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:27.982   765  2000 I ActivityManager: Killing 5304:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
08-23 12:25:27.982  6620  6620 E Zygote  : accessInfo : 64
08-23 12:25:27.982  6620  6620 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 12:25:27.982  6620  6620 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-23 12:25:27.982  6620  6620 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-23 12:25:28.002   765  1487 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-23 12:25:28.012  6620  6620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:28.012  6620  6620 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:28.022   765  1497 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfb7942 6620:com.sec.android.app.sbrowser/u0a142}
,08-23 12:25:28.022  6620  6620 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 12:25:28.062  6620  6620 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-23 12:25:28.072  6620  6620 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 12:25:28.072  6620  6620 D ManifestProvider: onCreate()
,08-23 12:25:28.082  6620  6620 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-23 12:25:28.082  6620  6620 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 12:25:28.082  6620  6620 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 12:25:28.082  6620  6620 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-23 12:25:28.092  6620  6620 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-23 12:25:28.092  6620  6620 D [MM]MHDataBaseProvider: onCreate()
,08-23 12:25:28.112  6620  6620 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@9d47c53)
,08-23 12:25:28.122  6350  6350 D Mms/BubbleViewCache: fillCache bubble = 4
,08-23 12:25:28.152   765  1318 I ActivityManager: Killing 5319:com.policydm/1000 (adj 15): DHA:empty #37
,08-23 12:25:28.162   765  1318 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb45a16 2018:com.google.android.gms.persistent/u0a11}
,08-23 12:25:28.172   765  1668 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{580a0b6 4043:com.google.android.gms/u0a11}
,08-23 12:25:28.172  4043  6635 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 12:25:28.192   765  2043 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-23 12:25:28.192  6362  6362 D AASAservice: onDestroy()
,08-23 12:25:28.192  6362  6362 I art     : System.exit called, status: 80
08-23 12:25:28.192  6362  6362 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-23 12:25:28.192  4043  6634 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-23 12:25:28.192  4043  6635 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 12:25:28.202  4043  4043 D AsyncTaskServiceImpl: Submit a task: nzm
,08-23 12:25:28.222  4043  6635 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 12:25:28.222   765  2103 I ActivityManager: Process com.samsung.aasaservice (pid 6362)(adj 0) has died(64,746)
,08-23 12:25:28.222   765  2103 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-23 12:25:28.222  4043  6635 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 12:25:28.232   765   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb45a16 2018:com.google.android.gms.persistent/u0a11}
,08-23 12:25:28.242  4043  4951 D nzm     : Processing package: com.test.thalitest
,08-23 12:25:28.252   765  2127 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{580a0b6 4043:com.google.android.gms/u0a11}
,08-23 12:25:28.252   352   352 I Zygote  : Process 6362 exited cleanly (80)
,08-23 12:25:28.262  4043  4043 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 12:25:28.282  4043  4951 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-23 12:25:28.282  4043  4951 D nzm     : Found info for package com.test.thalitest in db.
,08-23 12:25:28.352   765  2000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{982d6a7 4821:com.android.vending/u0a29}
,08-23 12:25:28.402  4821  4821 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-23 12:25:28.412   765  1668 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c10f2e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d0ca6 6134:com.sec.android.app.samsungapps/u0a39}
,08-23 12:25:28.412  4821  4821 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-23 12:25:28.422   765  2140 I ActivityManager: Start proc 6642:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-23 12:25:28.422  6642  6642 E Zygote  : v2
08-23 12:25:28.422  6642  6642 I libpersona: KNOX_SDCARD checking this for 10034
,08-23 12:25:28.422  6642  6642 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:28.422  6642  6642 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 12:25:28.422  6642  6642 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 12:25:28.432  6642  6642 E Zygote  : accessInfo : 0
,08-23 12:25:28.432  6642  6642 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-23 12:25:28.432  2018  2018 D WearableService: callingUid 10011, callindPid: 2018
,08-23 12:25:28.462  4821  4821 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-23 12:25:28.462  4821  4821 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-23 12:25:28.472  6535  6571 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 12:25:28.472  6535  6571 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 12:25:28.472  6642  6642 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:28.472  6642  6642 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:28.492   765  1497 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49138f9 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac7503e 6642:com.sec.android.app.shealth/u0a34}
,08-23 12:25:28.492  6535  6571 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 12:25:28.492  6535  6571 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 12:25:28.502  6535  6571 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-23 12:25:28.502  6535  6571 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 12:25:28.502  6535  6571 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 12:25:28.502  6642  6642 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-23 12:25:28.522  6642  6642 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-23 12:25:28.542  6642  6642 I MultiDex: VM with version 2.1.0 has multidex support
08-23 12:25:28.542  6642  6642 I MultiDex: install
08-23 12:25:28.542  6642  6642 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 12:25:28.542  6642  6642 I MultiDex: install
08-23 12:25:28.542  6642  6642 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 12:25:28.602  2023  2023 E audit   : type=1400 msg=audit(1471947928.602:290): avc:  denied  { execmod } for  pid=6597 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-23 12:25:28.612  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:28.612  2023  2023 E audit   : type=1300 msg=audit(1471947928.602:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8b000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6597 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:28.612  2023  2023 E audit   : type=1327 msg=audit(1471947928.602:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 12:25:28.612  2023  2023 E audit   : type=1320 msg=audit(1471947928.602:290): 
,08-23 12:25:28.642  1452  1452 D Recents : onTaskStackChanged
,08-23 12:25:28.642  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 12:25:28.662  2023  2023 E audit   : type=1400 msg=audit(1471947928.662:291): avc:  denied  { execmod } for  pid=6597 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 12:25:28.662  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:28.662  2023  2023 E audit   : type=1300 msg=audit(1471947928.662:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4b000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6597 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:28.662  2023  2023 E audit   : type=1327 msg=audit(1471947928.662:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 12:25:28.662  2023  2023 E audit   : type=1320 msg=audit(1471947928.662:291): 
,08-23 12:25:28.712  2023  2023 E audit   : type=1400 msg=audit(1471947928.712:292): avc:  denied  { execmod } for  pid=6597 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 12:25:28.712  2023  2023 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 12:25:28.712  2023  2023 E audit   : type=1300 msg=audit(1471947928.712:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4b000 a1=51000 a2=5 a3=4 items=0 ppid=3531 ppcomm=adbd pid=6597 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 12:25:28.712  2023  2023 E audit   : type=1327 msg=audit(1471947928.712:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 12:25:28.712  2023  2023 E audit   : type=1320 msg=audit(1471947928.712:292): 
,08-23 12:25:28.712  6597  6597 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 12:25:28.712  6597  6597 D AndroidRuntime: CheckJNI is OFF
08-23 12:25:28.712  6597  6597 D AndroidRuntime: readGMSProperty: start
08-23 12:25:28.712  6597  6597 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:25:28.712  6597  6597 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:25:28.712  6597  6597 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:25:28.712  6597  6597 D AndroidRuntime: readGMSProperty: end
08-23 12:25:28.712  6597  6597 D AndroidRuntime: addProductProperty: start
08-23 12:25:28.712   765  2044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49138f9 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{959ee60 1923:com.sec.android.app.shealth:remote/u0a34}
08-23 12:25:28.722  6642  6642 D HealthDataStore: Service for HealthDataStore is connected
08-23 12:25:28.722  6642  6642 D HealthDataStore: HealthConnectionErrorResult code : 9
08-23 12:25:28.722  6597  6597 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 12:25:28.722  6597  6597 W art     : aedb2000-b1cd8000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:28.722  6597  6597 W art     : b1cd8000-b3f47000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:28.722  6597  6597 W art     : b3f47000-b3f48000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 12:25:28.722  6597  6597 W art     : b3f48000-b3f49000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 12:25:28.722  6597  6597 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 12:25:28.722  6597  6597 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 12:25:28.722  6597  6597 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 12:25:28.722  6597  6597 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 12:25:28.722  6597  6597 W art     : b481b000-b481e000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:28.722  6597  6597 W art     : b481e000-b481f000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:28.722  6597  6597 W art     : b481f000-b4820000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 12:25:28.722  6597  6597 W art     : b4820000-b4821000 r--p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b4821000-b4841000 r--s 00000000 00:0b 6572       /dev/__properties__
08-23 12:25:28.722  6597  6597 W art     : b4841000-b5252000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:28.722  6597  6597 W art     : b5252000-b5253000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5253000-b529c000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:28.722  6597  6597 W art     : b529c000-b529d000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 12:25:28.722  6597  6597 W art     : b529d000-b52a5000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b52a5000-b52a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b52a6000-b52db000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:28.722  6597  6597 W art     : b52db000-b52dc000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b52dc000-b52dd000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:28.722  6597  6597 W art     : b52dd000-b52de000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 12:25:28.722  6597  6597 W art     : b52de000-b5336000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:28.722  6597  6597 W art     : b5336000-b5337000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5337000-b5338000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:28.722  6597  6597 W art     : b5338000-b5339000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 12:25:28.722  6597  6597 W art     : b533a000-b5340000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:28.722  6597  6597 W art     : b5340000-b5341000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:28.722  6597  6597 W art     : b5341000-b5342000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 12:25:28.722  6597  6597 W art     : b5342000-b5344000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5345000-b534f000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:28.722  6597  6597 W art     : b534f000-b5352000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:28.722  6597  6597 W art     : b5352000-b5353000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 12:25:28.722  6597  6597 W art     : b5354000-b536b000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:28.722  6597  6597 W art     : b536b000-b536c000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b536c000-b536d000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:28.722  6597  6597 W art     : b536d000-b536e000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 12:25:28.722  6597  6597 W art     : b536f000-b5379000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:28.722  6597  6597 W art     : b5379000-b537a000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:28.722  6597  6597 W art     : b537a000-b537b000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 12:25:28.722  6597  6597 W art     : b537b000-b537f000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:28.722  6597  6597 W art     : b537f000-b5380000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:28.722  6597  6597 W art     : b5380000-b5381000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 12:25:28.722  6597  6597 W art     : b5381000-b5397000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:28.722  6597  6597 W art     : b5397000-b5398000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:28.722  6597  6597 W art     : b5398000-b5399000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 12:25:28.722  6597  6597 W art     : b5399000-b53a6000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:28.722  6597  6597 W art     : b53a6000-b53a7000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:28.722  6597  6597 W art     : b53a7000-b53a8000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 12:25:28.722  6597  6597 W art     : b53a8000-b5408000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 12:25:28.722  6597  6597 W art     : b5408000-b540b000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 12:25:28.722  6597  6597 W art     : b540b000-b540f000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b540f000-b5470000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 12:25:28.722  6597  6597 W art     : b5470000-b5471000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 12:25:28.722  6597  6597 W art     : b5471000-b54c0000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:28.722  6597  6597 W art     : b54c0000-b54c2000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:28.722  6597  6597 W art     : b54c2000-b54c3000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 12:25:28.722  6597  6597 W art     : b54c3000-b54c4000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b54c4000-b54cb000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54cb000-b54cc000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54cc000-b54cd000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 12:25:28.722  6597  6597 W art     : avc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54ce000-b54d1000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54d1000-b54d2000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54d2000-b54d3000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 12:25:28.722  6597  6597 W art     : enc_common.so
08-23 12:25:28.722  6597  6597 W art     : b54d4000-b54d8000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 12:25:28.722  6597  6597 W art     : b54d8000-b54d9000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b54d9000-b54da000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 12:25:28.722  6597  6597 W art     : b54da000-b54db000 rw-p 00005000 b3:17 2510       /syste
08-23 12:25:28.722  6597  6597 W art     : m/lib/libpowermanager.so
08-23 12:25:28.722  6597  6597 W art     : b54dc000-b54f9000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:28.722  6597  6597 W art     : b54f9000-b54fa000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:28.722  6597  6597 W art     : b54fa000-b54fb000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 12:25:28.722  6597  6597 W art     : b54fc000-b5501000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:28.722  6597  6597 W art     : b5501000-b5502000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:28.722  6597  6597 W art     : b5502000-b5503000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 12:25:28.722  6597  6597 W art     : b5504000-b5535000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:28.722  6597  6597 W art     : b5535000-b5538000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:28.722  6597  6597 W art     : b5538000-b5539000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 12:25:28.722  6597  6597 W art     : b553a000-b5575000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 12:25:28.722  6597  6597 W art     : b5575000-b5576000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 12:25:28.722  6597  6597 W art     : b5576000-b5577000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 12:25:28.722  6597  6597 W art     : b5578000-b557f000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:28.722  6597  6597 W art     : b557f000-b5580000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5580000-b5581000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:28.722  6597  6597 W art     : b5581000-b5582000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 12:25:28.722  6597  6597 W art     : b5582000-b5583000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b5583000-b559a000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:28.722  6597  6597 W art     : b559a000-b559b000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b559b000-b559e000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:28.722  6597  6597 W art     : b559e000-b559f000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 12:25:28.722  6597  6597 W art     : b559f000-b55be000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:28.722  6597  6597 W art     : b55be000-b55bf000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:28.722  6597  6597 W art     : b55bf000-b55c0000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 12:25:28.722  6597  6597 W art     : b55c0000-b55fe000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:28.722  6597  6597 W art     : b55fe000-b55ff000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b55ff000-b5601000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:28.722  6597  6597 W art     : b5601000-b5602000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 12:25:28.722  6597  6597 W art     : b5603000-b560a000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:28.722  6597  6597 W art     : b560a000-b560b000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:28.722  6597  6597 W art     : b560b000-b560c000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 12:25:28.722  6597  6597 W art     : b560d000-b5610000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:28.722  6597  6597 W art     : b5610000-b5611000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:28.722  6597  6597 W art     : b5611000-b5612000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 12:25:28.722  6597  6597 W art     : b5612000-b5618000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:28.722  6597  6597 W art     : b5618000-b5619000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5619000-b561a000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:28.722  6597  6597 W art     : b561a000-b561b000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 12:25:28.722  6597  6597 W art     : b561b000-b5624000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:28.722  6597  6597 W art     : b5624000-b5625000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:28.722  6597  6597 W art     : b5625000-b5626000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 12:25:28.722  6597  6597 W art     : b5626000-b56b7000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:28.722  6597  6597 W art     : b56b7000-b56b8000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b56b8000-b56c3000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:28.722  6597  6597 W art     : b56c3000-b56c4000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 12:25:28.722  6597  6597 W art     : b56c5000-b56d7000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:28.722  6597  6597 W art     : b56d7000-b56d8000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:28.722  6597  6597 W art     : b56d8000-b56d9000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 12:25:28.722  6597  6597 W art     : b56da000-b56df000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:28.722  6597  6597 W art     : b56df000-b56e0000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:28.722  6597  6597 W art     : b56e0000-b56e1000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 12:25:28.722  6597  6597 W art     : b56e2000-b574f000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:28.722  6597  6597 W art     : b574f000-b5750000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5750000-b5752000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:28.722  6597  6597 W art     : b5752000-b5753000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 12:25:28.722  6597  6597 W art     : b5753000-b5754000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b5754000-b575b000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:28.722  6597  6597 W art     : b575b000-b575c000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:28.722  6597  6597 W art     : b575c000-b575d000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 12:25:28.722  6597  6597 W art     : b575e000-b57de000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:28.722  6597  6597 W art     : b57de000-b57df000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b57df000-b57e0000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:28.722  6597  6597 W art     : b57e0000-b57e1000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 12:25:28.722  6597  6597 W art     : b57e1000-b57f8000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b57f8000-b582f000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 12:25:28.722  6597  6597 W art     : ib/libqc-opt.so
08-23 12:25:28.722  6597  6597 W art     : b582f000-b5830000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 12:25:28.722  6597  6597 W art     : b5830000-b5831000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 12:25:28.722  6597  6597 W art     : b5831000-b584d000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:28.722  6597  6597 W art     : b584d000-b584e000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:28.722  6597  6597 W art     : b584e000-b584f000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 12:25:28.722  6597  6597 W art     : b5850000-b58b1000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:28.722  6597  6597 W art     : b58b1000-b58b3000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:28.722  6597  6597 W art     : b58b3000-b58b4000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 12:25:28.722  6597  6597 W art     : b58b5000-b58dc000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:28.722  6597  6597 W art     : b58dc000-b58dd000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b58dd000-b58de000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:28.722  6597  6597 W art     : b58de000-b58df000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 12:25:28.722  6597  6597 W art     : b58e0000-b58e8000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:28.722  6597  6597 W art     : b58e8000-b58ea000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:28.722  6597  6597 W art     : b58ea000-b58eb000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 12:25:28.722  6597  6597 W art     : b58ec000-b58ef000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:28.722  6597  6597 W art     : b58ef000-b58f0000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:28.722  6597  6597 W art     : b58f0000-b58f1000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 12:25:28.722  6597  6597 W art     : b58f1000-b58f5000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:28.722  6597  6597 W art     : b58f5000-b58f6000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b58f6000-b58f7000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:28.722  6597  6597 W art     : b58f7000-b58f8000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 12:25:28.722  6597  6597 W art     : b58f8000-b5908000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:28.722  6597  6597 W art     : b5908000-b5909000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:28.722  6597  6597 W art     : b5909000-b590a000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 12:25:28.722  6597  6597 W art     : b590a000-b5950000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5950000-b5959000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:28.722  6597  6597 W art     : b5959000-b595a000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:28.722  6597  6597 W art     : b595a000-b595b000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 12:25:28.722  6597  6597 W art     : b595c000-b5961000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:28.722  6597  6597 W art     : b5961000-b5962000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:28.722  6597  6597 W art     : b5962000-b5963000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 12:25:28.722  6597  6597 W art     : b5963000-b5966000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:28.722  6597  6597 W art     : b5966000-b5967000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5967000-b5968000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:28.722  6597  6597 W art     : b5968000-b5969000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 12:25:28.722  6597  6597 W art     : b596a000-b5982000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:28.722  6597  6597 W art     : b5982000-b5983000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5983000-b5984000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:28.722  6597  6597 W art     : b5984000-b5985000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 12:25:28.722  6597  6597 W art     : b5986000-b5b20000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:28.722  6597  6597 W art     : b5b20000-b5b21000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5b21000-b5b2e000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:28.722  6597  6597 W art     : b5b2e000-b5b2f000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 12:25:28.722  6597  6597 W art     : b5b2f000-b5b33000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:28.722  6597  6597 W art     : b5b33000-b5b34000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5b34000-b5b35000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:28.722  6597  6597 W art     : b5b35000-b5b36000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 12:25:28.722  6597  6597 W art     : b5b36000-b5b49000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:28.722  6597  6597 W art     : b5b49000-b5b4a000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:28.722  6597  6597 W art     : b5b4a000-b5b4b000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 12:25:28.722  6597  6597 W art     : b5b4b000-b5b4c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:28.722  6597  6597 W art     : b5b4c000-b5b97000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:28.722  6597  6597 W art     : b5b97000-b5b98000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:28.722  6597  6597 W art     : b5b98000-b5b99000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 12:25:28.722  6597  6597 W art     : b5b99000-b5b9b000 rw-p 00000000 00:00 0 
,08-23 12:25:28.722  6597  6597 W art     : b5b9c000-b5bad000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:28.722  6597  6597 W art     : b5bad000-b5bae000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5bae000-b5baf000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:28.722  6597  6597 W art     : b5baf000-b5bb0000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 12:25:28.722  6597  6597 W art     : b5bb1000-b5bbb000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:28.722  6597  6597 W art     : b5bbb000-b5bbd000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:28.722  6597  6597 W art     : b5bbd000-b5bbe000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 12:25:28.722  6597  6597 W art     : b5bbe000-b5bd7000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:28.722  6597  6597 W art     : b5bd7000-b5bd8000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:28.722  6597  6597 W art     : b5bd8000-b5bdb000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 12:25:28.722  6597  6597 W art     : b5bdb000-b5bdf000 rw-p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5bdf000-b5c53000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:28.722  6597  6597 W art     : b5c53000-b5c54000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5c54000-b5c57000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:28.722  6597  6597 W art     : b5c57000-b5c58000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 12:25:28.722  6597  6597 W art     : b5c58000-b5c59000 r--p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5c59000-b5c5c000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:28.722  6597  6597 W art     : b5c5c000-b5c5d000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:28.722  6597  6597 W art     : b5c5d000-b5c5e000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 12:25:28.722  6597  6597 W art     : b5c5e000-b5c5f000 r--p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5c5f000-b5c64000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:28.722  6597  6597 W art     : b5c64000-b5c65000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:28.722  6597  6597 W art     : b5c65000-b5c66000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 12:25:28.722  6597  6597 W art     : b5c66000-b5c67000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b5c67000-b5c6a000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:28.722  6597  6597 W art     : b5c6a000-b5c6b000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:28.722  6597  6597 W art     : b5c6b000-b5c6c000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 12:25:28.722  6597  6597 W art     : b5c6c000-b5c6d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b5c6d000-b5c71000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:28.722  6597  6597 W art     : b5c71000-b5c72000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:28.722  6597  6597 W art     : b5c72000-b5c73000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 12:25:28.722  6597  6597 W art     : b5c73000-b5c74000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:28.722  6597  6597 W art     : b5c74000-b5c78000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:28.722  6597  6597 W art     : b5c78000-b5c79000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:28.722  6597  6597 W art     : b5c79000-b5c7a000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 12:25:28.722  6597  6597 W art     : b5c7a000-b5c7b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.722  6597  6597 W art     : b5c7b000-b5c89000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:28.722  6597  6597 W art     : b5c89000-b5c8a000 ---p 00000000 00:00 0 
08-23 12:25:28.722  6597  6597 W art     : b5c8a000-b5c8b000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:28.722  6597  6597 W art     : b5c8b000-b5c8c000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 12:25:28.722  6597  6597 W art     : b5c8c000-b5c96000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:28.732  6597  6597 W art     : b5c96000-b5c99000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:28.732  6597  6597 W art     : b5c99000-b5c9a000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 12:25:28.732  6597  6597 W art     : b5c9a000-b5c9b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b5c9b000-b5ca5000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:28.732  6597  6597 W art     : b5ca5000-b5ca8000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:28.732  6597  6597 W art     : b5ca8000-b5ca9000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 12:25:28.732  6597  6597 W art     : b5ca9000-b5cad000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:28.732  6597  6597 W art     : b5cad000-b5cae000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:28.732  6597  6597 W art     : b5cae000-b5caf000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 12:25:28.732  6597  6597 W art     : b5caf000-b5cb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b5cb0000-b5cbd000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:28.732  6597  6597 W art     : b5cbd000-b5cbf000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:28.732  6597  6597 W art     : b5cbf000-b5cc0000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 12:25:28.732  6597  6597 W art     : b5cc0000-b60d2000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:28.732  6597  6597 W art     : b60d2000-b60d3000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b60d3000-b60dc000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:28.732  6597  6597 W art     : b60dc000-b60e0000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 12:25:28.732  6597  6597 W art     : b60e0000-b60e1000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b60e1000-b60e8000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:28.732  6597  6597 W art     : b60e8000-b60e9000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:28.732  6597  6597 W art     : b60e9000-b60ea000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 12:25:28.732  6597  6597 W art     : b60ea000-b60eb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b60eb000-b6106000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 12:25:28.732  6597  6597 W art     : b6106000-b6107000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 12:25:28.732  6597  6597 W art     : b6107000-b6108000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 12:25:28.732  6597  6597 W art     : b6108000-b6109000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6109000-b6155000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:28.732  6597  6597 W art     : b6155000-b6156000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6156000-b6157000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:28.732  6597  6597 W art     : b6157000-b6158000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 12:25:28.732  6597  6597 W art     : b6158000-b6159000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6159000-b615d000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:28.732  6597  6597 W art     : b615d000-b615e000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b615e000-b615f000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:28.732  6597  6597 W art     : b615f000-b6160000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 12:25:28.732  6597  6597 W art     : b6160000-b6198000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:28.732  6597  6597 W art     : b6198000-b6199000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:28.732  6597  6597 W art     : b6199000-b619a000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 12:25:28.732  6597  6597 W art     : b619a000-b619b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b619b000-b6239000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 12:25:28.732  6597  6597 W art     : b6239000-b623a000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b623a000-b6258000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 12:25:28.732  6597  6597 W art     : b6258000-b6259000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 12:25:28.732  6597  6597 W art     : b6259000-b63cc000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:28.732  6597  6597 W art     : b63cc000-b63d7000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:28.732  6597  6597 W art     : b63d7000-b63d8000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 12:25:28.732  6597  6597 W art     : b63d8000-b64ef000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:28.732  6597  6597 W art     : b64ef000-b64fa000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:28.732  6597  6597 W art     : b64fa000-b64fb000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 12:25:28.732  6597  6597 W art     : b64fb000-b64ff000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b64ff000-b6523000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 12:25:28.732  6597  6597 W art     : b6523000-b6525000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 12:25:28.732  6597  6597 W art     : b6525000-b6526000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 12:25:28.732  6597  6597 W art     : b6526000-b65cc000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:28.732  6597  6597 W art     : b65cc000-b65d9000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:28.732  6597  6597 W art     : b65d9000-b65da000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 12:25:28.732  6597  6597 W art     : b65da000-b65db000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b65db000-b662e000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:28.732  6597  6597 W art     : b662e000-b662f000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b662f000-b6630000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:28.732  6597  6597 W art     : b6630000-b6631000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 12:25:28.732  6597  6597 W art     : b6631000-b6636000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6636000-b6648000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:28.732  6597  6597 W art     : b6648000-b6649000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6649000-b664a000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:28.732  6597  6597 W art     : b664a000-b664b000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 12:25:28.732  6597  6597 W art     : b664b000-b6652000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:28.732  6597  6597 W art     : b6652000-b6653000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:28.732  6597  6597 W art     : b6653000-b6654000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 12:25:28.732  6597  6597 W art     : b6654000-b6655000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6655000-b6658000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:28.732  6597  6597 W art     : b6658000-b6659000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:28.732  6597  6597 W art     : b6659000-b665a000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 12:25:28.732  6597  6597 W art     : b665a000-b665e000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:28.732  6597  6597 W art     : b665e000-b665f000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:28.732  6597  6597 W art     : b665f000-b6660000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 12:25:28.732  6597  6597 W art     : b6660000-b666e000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:28.732  6597  6597 W art     : b666e000-b666f000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b666f000-b6670000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:28.732  6597  6597 W art     : b6670000-b6671000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 12:25:28.732  6597  6597 W art     : b6671000-b667a000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:28.732  6597  6597 W art     : b667a000-b667b000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:28.732  6597  6597 W art     : b667b000-b667c000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 12:25:28.732  6597  6597 W art     : b667c000-b66e2000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:28.732  6597  6597 W art     : b66e2000-b66e3000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b66e3000-b66e5000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:28.732  6597  6597 W art     : b66e5000-b66ee000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 12:25:28.732  6597  6597 W art     : b66ee000-b66f1000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b66f1000-b6788000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:28.732  6597  6597 W art     : b6788000-b678a000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:28.732  6597  6597 W art     : b678a000-b678b000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 12:25:28.732  6597  6597 W art     : b678b000-b678c000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b678c000-b6aad000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 12:25:28.732  6597  6597 W art     : b6aad000-b6aae000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6aae000-b6ac9000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 12:25:28.732  6597  6597 W art     : b6ac9000-b6acd000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 12:25:28.732  6597  6597 W art     : b6acd000-b6ad2000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6ad2000-b6ada000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:28.732  6597  6597 W art     : b6ada000-b6adb000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:28.732  6597  6597 W art     : b6adb000-b6adc000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 12:25:28.732  6597  6597 W art     : b6adc000-b6b0a000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:28.732  6597  6597 W art     : b6b0a000-b6b0b000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6b0b000-b6b12000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:28.732  6597  6597 W art     : b6b12000-b6b13000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 12:25:28.732  6597  6597 W art     : b6b13000-b6b59000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:28.732  6597  6597 W art     : b6b59000-b6b5a000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6b5a000-b6b5d000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:28.732  6597  6597 W art     : b6b5d000-b6b5e000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 12:25:28.732  6597  6597 W art     : b6b5e000-b6b79000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:28.732  6597  6597 W art     : b6b79000-b6b7d000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:28.732  6597  6597 W art     : b6b7d000-b6b7e000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 12:25:28.732  6597  6597 W art     : b6b7e000-b6bcb000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:28.732  6597  6597 W art     : b6bcb000-b6bcc000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6bcc000-b6bd8000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:28.732  6597  6597 W art     : b6bd8000-b6bd9000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 12:25:28.732  6597  6597 W art     : b6bd9000-b6be6000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 12:25:28.732  6597  6597 W art     : b6be6000-b6be7000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6be7000-b6be8000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 12:25:28.732  6597  6597 W art     : b6be8000-b6be9000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 12:25:28.732  6597  6597 W art     : b6be9000-b6bf1000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:28.732  6597  6597 W art     : b6bf1000-b6bf2000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6bf2000-b6bf3000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:28.732  6597  6597 W art     : b6bf3000-b6bf4000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 12:25:28.732  6597  6597 W art     : b6bf4000-b6bfb000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:28.732  6597  6597 W art     : b6bfb000-b6bfc000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:28.732  6597  6597 W art     : b6bfc000-b6bfd000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 12:25:28.732  6597  6597 W art     : b6bfd000-b6c11000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:28.732  6597  6597 W art     : b6c11000-b6c13000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:28.732  6597  6597 W art     : b6c13000-b6c14000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 12:25:28.732  6597  6597 W art     : b6c14000-b6c3c000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:28.732  6597  6597 W art     : b6c3c000-b6c3e000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:28.732  6597  6597 W art     : b6c3e000-b6c3f000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 12:25:28.732  6597  6597 W art     : b6c3f000-b6c42000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:28.732  6597  6597 W art     : b6c42000-b6c43000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:28.732  6597  6597 W art     : b6c43000-b6c44000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 12:25:28.732  6597  6597 W art     : b6c44000-b6c4d000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:28.732  6597  6597 W art     : b6c4d000-b6c4e000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:28.732  6597  6597 W art     : b6c4e000-b6c4f000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 12:25:28.732  6597  6597 W art     : b6c4f000-b6c6f000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 12:25:28.732  6597  6597 W art     : b6c6f000-b6c70000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 12:25:28.732  6597  6597 W art     : b6c70000-b6c71000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 12:25:28.732  6597  6597 W art     : b6c71000-b6ce4000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 12:25:28.732  6597  6597 W art     : b6ce4000-b6ce8000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 12:25:28.732  6597  6597 W art     : b6ce8000-b6ceb000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 12:25:28.732  6597  6597 W art     : b6ceb000-b6cf5000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6cf5000-b6d7d000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:28.732  6597  6597 W art     : b6d7d000-b6d7e000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6d7e000-b6d82000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:28.732  6597  6597 W art     : b6d82000-b6d83000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 12:25:28.732  6597  6597 W art     : b6d83000-b6d84000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6d84000-b6dad000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:28.732  6597  6597 W art     : b6dad000-b6dae000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6dae000-b6db1000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:28.732  6597  6597 W art     : b6db1000-b6db2000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 12:25:28.732  6597  6597 W art     : b6db2000-b6e8c000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:28.732  6597  6597 W art     : b6e8c000-b6e93000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:28.732  6597  6597 W art     : b6e93000-b6e9b000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 12:25:28.732  6597  6597 W art     : b6e9b000-b6e9c000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6e9c000-b6e9d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:28.732  6597  6597 W art     : b6e9d000-b6e9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 12:25:28.732  6597  6597 W art     : b6e9e000-b6e9f000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6e9f000-b6ea2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6ea2000-b6ec7000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:28.732  6597  6597 W art     : b6ec7000-b6ec8000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6ec8000-b6ecf000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:28.732  6597  6597 W art     : b6ecf000-b6ed0000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 12:25:28.732  6597  6597 W art     : b6ed0000-b6ed7000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:28.732  6597  6597 W art     : b6ed7000-b6ed8000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:28.732  6597  6597 W art     : b6ed8000-b6ed9000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 12:25:28.732  6597  6597 W art     : b6ed9000-b6eda000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6eda000-b6ef2000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 12:25:28.732  6597  6597 W art     : b6ef2000-b6ef3000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6ef3000-b6ef4000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 12:25:28.732  6597  6597 W art     : b6ef4000-b6ef5000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 12:25:28.732  6597  6597 W art     : b6ef5000-b6f03000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:28.732  6597  6597 W art     : b6f03000-b6f04000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6f04000-b6f05000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:28.732  6597  6597 W art     : b6f05000-b6f06000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 12:25:28.732  6597  6597 W art     : b6f06000-b6f07000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:28.732  6597  6597 W art     : b6f07000-b6f09000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6f09000-b6f0a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6f0a000-b6f0b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 12:25:28.732  6597  6597 W art     : b6f0b000-b6f0c000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 12:25:28.732  6597  6597 W art     : b6f0c000-b6f0d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 12:25:28.732  6597  6597 W art     : b6f0d000-b6f2d000 r--s 00000000 00:0b 6572       /dev/__properties__
08-23 12:25:28.732  6597  6597 W art     : b6f2d000-b6f2e000 r--p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6f2e000-b6f2f000 ---p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6f2f000-b6f31000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 12:25:28.732  6597  6597 W art     : b6f31000-b6f32000 r-xp 00000000 00:00 0          [sigpage]
08-23 12:25:28.732  6597  6597 W art     : b6f32000-b6f4d000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 12:25:28.732  6597  6597 W art     : b6f4d000-b6f4e000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 12:25:28.732  6597  6597 W art     : b6f4e000-b6f50000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 12:25:28.732  6597  6597 W art     : b6f50000-b6f52000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : b6f52000-b6f57000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 12:25:28.732  6597  6597 W art     : b6f57000-b6f58000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 12:25:28.732  6597  6597 W art     : b6f58000-b6f59000 rw-p 00000000 00:00 0 
08-23 12:25:28.732  6597  6597 W art     : bed0f000-bed30000 rw-p 00000000 00:00 0          [stack]
08-23 12:25:28.732  6597  6597 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 12:25:28.752  6642  6642 D HealthConsole: Service for HealthDataConsole is connected
08-23 12:25:28.772  6597  6597 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 12:25:28.772  6642  6642 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
08-23 12:25:28.772  6642  6642 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 12:25:28.782   765  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49138f9 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{959ee60 1923:com.sec.android.app.shealth:remote/u0a34}
08-23 12:25:28.802   765   765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc32c84 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb45a16 2018:com.google.android.gms.persistent/u0a11}
08-23 12:25:28.812  6597  6597 I Radio-JNI: register_android_hardware_Radio DONE
08-23 12:25:28.822   765   765 I BackgroundCompactionService: onStart. jobID=801
08-23 12:25:28.822  6597  6597 E AffinityControl: AffinityControl: registerfunction enter
08-23 12:25:28.822   765   765 I BackgroundCompactionService: onStart done. jobID=801
,08-23 12:25:28.822   765  6666 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-23 12:25:28.822   765  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 12:25:28.832   765  6666 I BackgroundCompactionService: compact_memory command done
,08-23 12:25:28.842  6597  6597 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:25:28.872   765  2000 D PackageManager: START PACKAGE DELETE: observer{109462766}
08-23 12:25:28.872   765  2000 D PackageManager: pkg{<packageName>}
08-23 12:25:28.872   765  2000 D PackageManager: user{0}
08-23 12:25:28.872   765  2000 D PackageManager: caller{2000}
08-23 12:25:28.872   765  2000 D PackageManager: flags{2}
,08-23 12:25:28.872   765  2000 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 12:25:28.872   765  2000 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 12:25:28.872   765  2000 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 12:25:28.872   765  2000 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 12:25:28.872   765  2000 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 12:25:28.872   765   925 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-23 12:25:28.872   765   925 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 12:25:28.872   765   925 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 12:25:28.872   765   925 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 12:25:28.872   765   925 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 12:25:28.872   765   925 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-23 12:25:28.882   765   925 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 12:25:28.882   765   925 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-23 12:25:28.882   765   925 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 12:25:28.882   765   834 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-23 12:25:28.882   765   925 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-23 12:25:28.882   765   834 I ActivityManager: Killing 6382:com.test.thalitest/u0a4 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 12:25:28.882   765   834 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 12:25:28.882   765   834 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-23 12:25:28.922   765   925 D AASAinstall: there is not AASApackages.xml file
,08-23 12:25:28.932   765   779 D GraphicsStats: Buffer count: 4
,08-23 12:25:28.932   765   777 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@e400d8f)
,08-23 12:25:28.932   765  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 12:25:28.932   765  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 12:25:28.932   765  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 12:25:29.242   765   925 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-23 12:25:29.342   765   925 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 12:25:29.352   334   334 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-23 12:25:29.352   765   925 I art     : Starting a blocking GC Explicit
,08-23 12:25:29.382  4043  6640 E GameAgent: Caller attempted to insert game data for non-existent package.
08-23 12:25:29.382  4043  6640 E GameAgent: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 12:25:29.382  4043  6640 E GameAgent: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at com.google.android.gms.games.broker.GameAgent.registerGame(GameAgent.java:1620)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at com.google.android.gms.games.broker.DataBroker.registerGame(DataBroker.java:3357)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:29.382  4043  6640 E GameAgent: 	at java.lang.Thread.run(Thread.java:818)
,08-23 12:25:29.402  4043  5046 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-23 12:25:29.402  4043  5046 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-23 12:25:29.472   765   925 I art     : Explicit concurrent mark sweep GC freed 104853(5MB) AllocSpace objects, 7(140KB) LOS objects, 27% free, 42MB/58MB, paused 1.263ms total 110.641ms
,08-23 12:25:29.502   765   925 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 12:25:29.502   765   925 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-23 12:25:29.502   765   925 D AASAinstall: there is not AASApackages.xml file
08-23 12:25:29.502   765   925 D PackageManager: result of delete: 1{109462766}
,08-23 12:25:29.512  6597  6597 I art     : System.exit called, status: 0
08-23 12:25:29.512  6597  6597 I AndroidRuntime: VM exiting with result code 0.
,08-23 12:25:29.522   765   925 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 12:25:29.522   765   925 D PackageManager: userId{-1}
08-23 12:25:29.522   765   925 D PackageManager: andCode{true}
,08-23 12:25:29.532   765   925 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-23 12:25:29.562   765   765 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.562  5887  6322 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-23 12:25:29.562   765   765 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.562   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.572  5887  6322 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
08-23 12:25:29.572   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.572   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.572  5887  6322 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-23 12:25:29.572  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-23 12:25:29.572  1381  1381 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-23 12:25:29.572   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.582   765   895 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.592   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.592   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.592   765   895 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.592   765  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:25:29.602   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.602   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.642  2018  2552 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.642  1655  1655 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.642  1788  1798 I art     : Background partial concurrent mark sweep GC freed 25119(2MB) AllocSpace objects, 7(240KB) LOS objects, 40% free, 19MB/32MB, paused 507us total 102.116ms
,08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.642   765   765 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.652   765   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5787f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b5d6ff 4208:com.samsung.klmsagent/u0a18}
,08-23 12:25:29.652  1965  1965 E SamsungIME: mOCRHelper is null
,08-23 12:25:29.652   765   765 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.662   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.662  1452  1462 I art     : Background partial concurrent mark sweep GC freed 6219(440KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 222us total 109.280ms
,08-23 12:25:29.672  4208  4208 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 23 12:25:29 GMT+02:00 2016
,08-23 12:25:29.672   765   830 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-23 12:25:29.672   765   830 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 12:25:29.682   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.682   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.682  1669  1678 I art     : Background partial concurrent mark sweep GC freed 45247(3MB) AllocSpace objects, 23(3MB) LOS objects, 24% free, 49MB/65MB, paused 197us total 124.903ms
,08-23 12:25:29.682  3176  3191 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 12:25:29.682  3176  3191 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 12:25:29.682  3176  3191 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 12:25:29.692   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.692   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.692   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.692   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.692   765  1321 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-23 12:25:29.692   765  1321 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-23 12:25:29.692  3176  3191 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 12:25:29.692   765  2140 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-23 12:25:29.692   765  1320 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:25:29.692   765  1320 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-23 12:25:29.692   765  1320 V NetworkStats: performPollLocked(flags=0x3)
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702   765   830 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702  4208  4208 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765  1320 V NetworkStats: performPollLocked() took 10ms
,08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765  1320 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.702   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.712   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.712   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.712   765  2044 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5787f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc7ff86 765:system/1000}
,08-23 12:25:29.712   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.712   765   765 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.712   765  1321 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:25:29.722   765  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:25:29.722   765   765 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.722   765   765 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.722  1643  6698 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-23 12:25:29.722   765  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
08-23 12:25:29.722  1643  6698 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-23 12:25:29.722  1643  6698 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 12:25:29.722  1643  6698 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 12:25:29.722  1643  6698 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 12:25:29.722  4208  4208 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-23 12:25:29.722  4208  4208 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 12:25:29.732  4208  4208 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.732   765   765 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.732  4208  6699 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742  4208  6699 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742   765   765 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.742   765  1296 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-23 12:25:29.752   765  1320 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7088e436 in tid 1320 (NetworkStats)
,08-23 12:25:29.752  4208  6699 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d3f314 in tid 6699 (IntentService[K)
08-23 12:25:29.752   765   830 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.752  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.752   765   830 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-23 12:25:29.752  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.752   765   765 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-23 12:25:29.752  4208  6699 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 12:25:29.752  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
,08-23 12:25:29.822   352   352 I Zygote  : Process 4208 exited due to signal (7)
,08-23 12:25:29.822   292   292 I ServiceManager: service 'connectivity' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'sb_service' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'servicediscovery' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'updatelock' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'notification' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'location' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'country_detector' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'sec_location' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'search' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'execute' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'dropbox' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'wallpaper' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'audio' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'DockObserver' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'midi' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'usb' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'serial' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'kiesusb' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'jobscheduler' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'backup' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'appwidget' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'voiceinteraction' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'diskstats' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'mDNIe' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'AAS' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'MSCS' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'spengestureservice' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'sec_analytics' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'telecom' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'display' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'persona_policy' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'user' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'procstats' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'meminfo' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'gfxinfo' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'dbinfo' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'cpuinfo' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'permission' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'processinfo' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'sensorservice' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'quickconnect' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'samplingprofiler' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'battery' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'activity' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'usagestats' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'webviewupdate' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'scheduling_policy' died
08-23 12:25:29.822   292   292 I ServiceManager: service 'telephony.registry' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'persona' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'rcp' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'input_method' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'accessibility' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'cover' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'mount' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'deviceidle' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'lock_settings' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'device_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'harmony_eas_service' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'sdp' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'sdp_log' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'dlp' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'log_manager_service' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'application_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'wifi_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'remoteinjection' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'edm_proxy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'mum_container_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'otp_service' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'enterprise_policy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'statusbar' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'clipboard' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'clipboardEx' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'network_management' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'commontime_management' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-23 12:25:29.832  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.832   292   292 I ServiceManager: service 'textservices' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'network_score' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'netstats' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'netpolicy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'wifip2p' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'wifi' died
08-23 12:25:29.842  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.832  1669  1679 W Sensors : sensorservice died [0xad9b62c0]
08-23 12:25:29.842  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.832   292   292 I ServiceManager: service 'wifihs20' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'wifiscanner' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'rttmanager' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'ethernet' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'edmnativehelper' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'graphicsstats' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'print' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'restrictions' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'media_session' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'media_router' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'trust' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'fingerprint' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'launcherapps' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'voip' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'media_projection' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'lpnet' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'imms' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'alarm' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'context_aware' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'scontext' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'barbeam' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'multiwindow_facade' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'window' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'input' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'dreams' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'package' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'SEAMService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'media.camera.proxy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'account' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'content' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'DirEncryptService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'LSManager' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'ReactiveService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'EngineeringModeService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'SatsService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'sedenial' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'vibrator' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'tw_toolbox' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'tima' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'iccc' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'cepproxyks' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'emailksproxy' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'consumer_ir' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'bluetooth_manager' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'uimode' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'batterystats' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'appops' died
08-23 12:25:29.832   292   292 I ServiceManager: service 'power' died
08-23 12:25:29.832   326   963 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb68ab1ba in tid 963 (Binder_3)
08-23 12:25:29.832   293   361 D libEGL  : eglTerminate EGLDisplay = 0xb65ff6fc
08-23 12:25:29.832   293   361 D libEGL  : eglTerminate EGLDisplay = 0xb65ff6fc
08-23 12:25:29.832   326   963 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.832   293   361 I SurfaceFlinger: restart the boot-animation @ binderDied
08-23 12:25:29.832  2842  2853 W Sensors : sensorservice died [0xad5edb80]
08-23 12:25:29.832   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
08-23 12:25:29.832   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-23 12:25:29.832  1381  1609 E WifiManager: Channel connection lost
08-23 12:25:29.832  2018  2550 E WifiManager: Channel connection lost
08-23 12:25:29.832  1381  2429 W Sensors : sensorservice died [0xa9862e00]
08-23 12:25:29.832  1643  1643 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7168ab05 in tid 1643 (com.android.nfc)
08-23 12:25:29.832  1788  1914 E WifiManager: Channel connection lost
08-23 12:25:29.842  1643  1643 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.842  3766  4016 E WifiManager: Channel connection lost
08-23 12:25:29.842  1998  1998 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ebbdc64 in tid 1998 (droid.bluetooth)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=8 Removed EimLayer(Di (6/9)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=2 Removed GocusedStac (5/8)
08-23 12:25:29.842  1998  1998 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/7)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=4 Removed EimLayer(An (0/6)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=9 Removed EimLayer(An (0/5)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=18 Removed Mauncher (0/2)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=15 Removed DolorFade (1/1)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=15 Removed DolorFade (-2/1)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=8 Removed EimLayer(Di (-2/1)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=9 Removed EimLayer(An (-2/1)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=20 Removed YUIInstallC (0/0)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=18 Removed Mauncher (-2/0)
08-23 12:25:29.842   293  1366 I SurfaceFlinger: id=20 Removed YUIInstallC (-2/0)
08-23 12:25:29.842  2842  3150 E WifiManager: Channel connection lost
08-23 12:25:29.842   332   332 E installd: eof
08-23 12:25:29.842   332   332 E installd: failed to read size
08-23 12:25:29.842   332   332 I installd: closing connection
08-23 12:25:29.842  1655  1655 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-23 12:25:29.842  1655  2543 E WifiManager: Channel connection lost
08-23 12:25:29.852  1923  1937 W Sensors : sensorservice died [0xb3ebfdc0]
08-23 12:25:29.862  2079  2079 D BluetoothA2dp: Proxy object disconnected
08-23 12:25:29.862  2842  2842 D BluetoothMap: Proxy object disconnected
08-23 12:25:29.862  2842  2842 D MapProfile: Bluetooth service disconnected
08-23 12:25:29.862  2842  2842 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b8682bd in tid 2842 (ndroid.settings)
08-23 12:25:29.862  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.862  2842  2842 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.862  2089  2112 W Sensors : sensorservice died [0xb3ebfc80]
08-23 12:25:29.872  2018  5947 W Sensors : sensorservice died [0xb4724940]
08-23 12:25:29.882   292   292 I ServiceManager: service 'secontroller' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'nfccontroller' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'nfc' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.audio_flinger' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.player' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.resource_manager' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.camera' died
08-23 12:25:29.882  1381  1925 W IMediaDeathNotifier: media server died
08-23 12:25:29.882   292   292 I ServiceManager: service 'listen.service' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.radio' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.sound_trigger_hw' died
08-23 12:25:29.882   292   292 I ServiceManager: service 'media.audio_policy' died
08-23 12:25:29.882  1788  1852 W AudioSystem: AudioFlinger server died!
08-23 12:25:29.882  1381  1925 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb61b4698 in tid 1925 (Binder_3)
08-23 12:25:29.882  1788  1852 W AudioSystem: AudioPolicyService server died!
08-23 12:25:29.882  1381  1925 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.882  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.892  3766  3780 W AudioSystem: AudioPolicyService server died!
08-23 12:25:29.892  2079  2105 W AudioSystem: AudioPolicyService server died!
08-23 12:25:29.892  1965  2289 W IMediaDeathNotifier: media server died
08-23 12:25:29.892  1965  2289 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb61b4698 in tid 2289 (Binder_3)
08-23 12:25:29.892  1965  2289 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.892  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.892  4043  4043 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70f97766 in tid 4043 (gle.android.gms)
08-23 12:25:29.892  4043  4043 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:29.892  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:29.922   352   352 I Zygote  : Process 2842 exited due to signal (7)
08-23 12:25:29.932   293  1366 D libEGL  : eglTerminate EGLDisplay = 0xb4a3f6fc
08-23 12:25:29.932   293  1366 D libEGL  : eglTerminate EGLDisplay = 0xb4a3f6fc
08-23 12:25:29.932   352   352 I Zygote  : Process 1643 exited due to signal (7)
08-23 12:25:29.932   352   352 I Zygote  : Process 1998 exited due to signal (7)
08-23 12:25:29.952   352   352 I Zygote  : Process 1381 exited due to signal (7)
08-23 12:25:29.972   352   352 I Zygote  : Process 4043 exited due to signal (7)
08-23 12:25:29.972   352   352 I Zygote  : Process 1965 exited due to signal (7)
08-23 12:25:30.062   291   291 I lowmemorykiller: ActivityManager disconnected
08-23 12:25:30.062   291   291 I lowmemorykiller: Closing Activity Manager data connection
08-23 12:25:30.082   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-23 12:25:30.082   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-23 12:25:30.312  1788  1788 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70f97afa in tid 1788 (earchbox:search)
08-23 12:25:30.312  1788  1788 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:30.312  2023  2023 E audit_log: File locking failed. error= Bad file descriptor
08-23 12:25:30.332   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
08-23 12:25:30.332   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
08-23 12:25:30.332   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
08-23 12:25:30.332   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe38c
08-23 12:25:30.332   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe38c
08-23 12:25:30.332   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeffe3a4
08-23 12:25:30.362   293   293 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
08-23 12:25:30.362   293   293 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
08-23 12:25:30.362   293   293 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
08-23 12:25:30.362   293   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-23 12:25:30.382  1669  1669 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ef6df15 in tid 1669 (id.app.launcher)
08-23 12:25:30.382  1669  1669 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 12:25:30.382  2023  2023 E audit_log: File locking failed. error= Bad file descriptor

```
