#### Test 80912877ea0a40f_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
,08-11 12:01:58.921  5522  5522 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-11 12:01:58.921  5522  5522 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-11 12:01:58.921  5522  5522 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-11 12:01:58.921  5522  5522 I art     : System.exit called, status: 0
08-11 12:01:58.921  5522  5522 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 12:01:58.951  5485  5485 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
--------- beginning of system
08-11 12:01:58.961   782  2587 I ActivityManager: Process com.samsung.aasaservice (pid 5522)(adj 0) has died(94,732)
08-11 12:01:58.961   782  2587 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-11 12:01:58.961   782  2587 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-11 12:01:58.961   782  2587 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-11 12:01:58.981  6377  6377 E Zygote  : v2
08-11 12:01:58.981  6377  6377 I libpersona: KNOX_SDCARD checking this for 10014
08-11 12:01:58.981  6377  6377 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:58.981  6377  6377 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:58.981  6377  6377 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:58.981   782   880 I ActivityManager: Start proc 6377:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-11 12:01:58.981  6377  6377 E Zygote  : accessInfo : 0
08-11 12:01:58.981   782  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 12:01:58.981  6377  6377 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-11 12:01:59.011  6377  6377 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.011  6377  6377 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.031   782   797 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e0dd54 6377:com.google.android.partnersetup/u0a14}
08-11 12:01:59.031   782  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-11 12:01:59.031  6377  6377 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-11 12:01:59.041  6377  6377 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-11 12:01:59.061   782  2587 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e0dd54 6377:com.google.android.partnersetup/u0a14}
08-11 12:01:59.081  6396  6396 E Zygote  : v2
08-11 12:01:59.081  6396  6396 I libpersona: KNOX_SDCARD checking this for 10015
08-11 12:01:59.081  6396  6396 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.081  6396  6396 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.081  6396  6396 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.091  6396  6396 E Zygote  : accessInfo : 0
08-11 12:01:59.091  6396  6396 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-11 12:01:59.091   782   797 I ActivityManager: Start proc 6396:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-11 12:01:59.121  6396  6396 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.121  6396  6396 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.131   782  1643 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88e5443 6396:com.samsung.groupcast/u0a15}
08-11 12:01:59.141  6396  6396 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-11 12:01:59.171  6396  6396 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-11 12:01:59.191  6396  6396 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-11 12:01:59.191  6396  6396 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-11 12:01:59.191  6396  6396 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-11 12:01:59.191  6396  6396 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-11 12:01:59.191  6396  6396 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:01:59.201  6396  6396 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 12:01:59.201  6396  6396 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:01:59.201  6396  6396 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 12:01:59.201  6396  6396 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 12:01:59.201   782  2587 I ActivityManager: Killing 5431:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
08-11 12:01:59.211   782  2587 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16fd321 1909:com.sec.android.app.shealth:remote/u0a34}
08-11 12:01:59.231   782  1319 I ActivityManager: Start proc 6414:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-11 12:01:59.231  6414  6414 E Zygote  : v2
08-11 12:01:59.231  6414  6414 I libpersona: KNOX_SDCARD checking this for 10041
08-11 12:01:59.231  6414  6414 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.231  6414  6414 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.231  6414  6414 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.231  6414  6414 E Zygote  : accessInfo : 0
08-11 12:01:59.231  6414  6414 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-11 12:01:59.241   782  2603 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
08-11 12:01:59.251  6414  6414 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.251  6414  6414 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.261   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1187ac0 6414:com.samsung.android.sdk.samsunglink/u0a41}
08-11 12:01:59.261  6414  6414 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-11 12:01:59.311   782  3525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-11 12:01:59.341  6414  6414 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 12:01:59.341  6414  6414 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-11 12:01:59.401  6414  6414 I SL_DEBUG: isLoggable:: isProductShip = 1
08-11 12:01:59.401  6414  6414 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-11 12:01:59.411   782  2615 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.411   782  2620 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-11 12:01:59.421   782  1807 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.421   782  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.421   782  2587 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.421   782   796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.431   782  1570 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.431   782  1802 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.431   782  1628 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.441   782   797 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-11 12:01:59.541  6414  6414 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-11 12:01:59.551  6414  6414 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-11 12:01:59.551  6414  6414 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-11 12:01:59.551  6414  6414 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-11 12:01:59.551  6414  6414 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-11 12:01:59.551  6414  6414 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:01:59.551  6414  6414 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 12:01:59.551  6414  6414 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:01:59.551  6414  6414 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 12:01:59.551  6414  6414 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 12:01:59.551   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba172ed 1691:android.process.acore/u0a19}
08-11 12:01:59.561   782  2587 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b35f742 5222:com.sec.android.gallery3d/u0a47}
08-11 12:01:59.571  5222  5222 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-11 12:01:59.571   782  1806 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-11 12:01:59.601   782  2603 I ActivityManager: Start proc 6438:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-11 12:01:59.601  6438  6438 E Zygote  : v2
08-11 12:01:59.601  6438  6438 I libpersona: KNOX_SDCARD checking this for 10050
08-11 12:01:59.601  6438  6438 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.601  6438  6438 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.601  6438  6438 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.601  6438  6438 E Zygote  : accessInfo : 0
08-11 12:01:59.601  6438  6438 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-11 12:01:59.621   782  1802 I ActivityManager: Killing 5588:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-11 12:01:59.631  6438  6438 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.631  6438  6438 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.641   782  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a013f0 6438:com.sec.android.app.myfiles/u0a50}
08-11 12:01:59.641   782  1643 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-11 12:01:59.651  6438  6438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-11 12:01:59.661  6438  6438 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-11 12:01:59.701  6438  6438 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-11 12:01:59.711   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de3fa15 2888:com.android.settings/1000}
08-11 12:01:59.721   321   321 E installd: system dir 0 : /system/app/
08-11 12:01:59.721   321   321 E installd: system dir 1 : /system/priv-app/
08-11 12:01:59.721   321   321 E installd: system dir 2 : /vendor/app/
08-11 12:01:59.721   321   321 E installd: system dir 3 : /oem/app/
08-11 12:01:59.731   782   950 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-11 12:01:59.731   782  1570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de3fa15 2888:com.android.settings/1000}
08-11 12:01:59.751   782  1802 I ActivityManager: Start proc 6454:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-11 12:01:59.751  6454  6454 E Zygote  : v2
08-11 12:01:59.751  6454  6454 I libpersona: KNOX_SDCARD checking this for 10169
08-11 12:01:59.751  6454  6454 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.751  6454  6454 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.751  6454  6454 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.751  6454  6454 E Zygote  : accessInfo : 0
08-11 12:01:59.751  6454  6454 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-11 12:01:59.771  6454  6454 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.771  6454  6454 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.781   782  2603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8a7f1c 6454:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-11 12:01:59.791  6454  6454 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-11 12:01:59.791  6454  6454 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-11 12:01:59.811   782  1802 I ActivityManager: Killing 5604:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-11 12:01:59.821   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59d7871 1762:com.android.phone/1001}
08-11 12:01:59.821   782  2604 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
08-11 12:01:59.821   782  2604 V MARsPolicyManager: updateSMDBValues
08-11 12:01:59.821   782   906 E MARsDBManager: updateDBAll : begin --size 0
08-11 12:01:59.821   782   906 E MARsDBManager: updateDBAll : end
08-11 12:01:59.821  2512  2512 E audit   : type=1400 msg=audit(1470909719.821:285): avc:  denied  { execmod } for  pid=6379 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 12:01:59.821  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.821  2512  2512 E audit   : type=1300 msg=audit(1470909719.821:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd6000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6379 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 12:01:59.821  2512  2512 E audit   : type=1327 msg=audit(1470909719.821:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 12:01:59.821  2512  2512 E audit   : type=1320 msg=audit(1470909719.821:285): 
08-11 12:01:59.831   782   797 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-11 12:01:59.841   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d323ad 1860:com.google.android.googlequicksearchbox:search/u0a61}
08-11 12:01:59.851   782  1643 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d323ad 1860:com.google.android.googlequicksearchbox:search/u0a61}
08-11 12:01:59.861   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d910fa 6307:com.samsung.android.sm.provider/1000}
08-11 12:01:59.871  6468  6468 E Zygote  : v2
08-11 12:01:59.871  6468  6468 I libpersona: KNOX_SDCARD checking this for 5012
08-11 12:01:59.871   782  1570 I ActivityManager: Start proc 6468:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-11 12:01:59.881  6468  6468 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.881  6468  6468 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.881  6468  6468 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.881  6468  6468 E Zygote  : accessInfo : 0
08-11 12:01:59.881  6468  6468 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-11 12:01:59.881  2512  2512 E audit   : type=1400 msg=audit(1470909719.881:286): avc:  denied  { execmod } for  pid=6379 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 12:01:59.881  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.881  2512  2512 E audit   : type=1300 msg=audit(1470909719.881:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f96000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6379 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 12:01:59.881  2512  2512 E audit   : type=1327 msg=audit(1470909719.881:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 12:01:59.881  2512  2512 E audit   : type=1320 msg=audit(1470909719.881:286): 
08-11 12:01:59.881  1860  6466 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 12:01:59.901  6468  6468 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:01:59.901  6468  6468 D ActivityThread: Added TimaKeyStore provider
08-11 12:01:59.911   782  2620 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f496ab 6468:com.samsung.android.sm.devicesecurity/5012}
08-11 12:01:59.921  6468  6468 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-11 12:01:59.931  2512  2512 E audit   : type=1400 msg=audit(1470909719.931:287): avc:  denied  { execmod } for  pid=6379 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 12:01:59.931  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.931  2512  2512 E audit   : type=1300 msg=audit(1470909719.931:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f96000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6379 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 12:01:59.931  2512  2512 E audit   : type=1327 msg=audit(1470909719.931:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 12:01:59.931  2512  2512 E audit   : type=1320 msg=audit(1470909719.931:287): 
08-11 12:01:59.931  6379  6379 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 12:01:59.931  6379  6379 D AndroidRuntime: CheckJNI is OFF
08-11 12:01:59.931  6379  6379 D AndroidRuntime: readGMSProperty: start
08-11 12:01:59.931  6379  6379 D AndroidRuntime: readGMSProperty: already setted!!
08-11 12:01:59.931  6379  6379 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 12:01:59.931  6379  6379 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 12:01:59.931  6379  6379 D AndroidRuntime: readGMSProperty: end
08-11 12:01:59.931  6379  6379 D AndroidRuntime: addProductProperty: start
08-11 12:01:59.941  6379  6379 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 12:01:59.941  6379  6379 W art     : aedfd000-b1d23000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:01:59.941  6379  6379 W art     : b1d23000-b3f92000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:01:59.941  6379  6379 W art     : b3f92000-b3f93000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:01:59.941  6379  6379 W art     : b3f93000-b3f94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 12:01:59.941  6379  6379 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-11 12:01:59.941  6379  6379 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 12:01:59.941  6379  6379 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 12:01:59.941  6379  6379 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-11 12:01:59.941  6379  6379 W art     : b4865000-b4868000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-11 12:01:59.941  6379  6379 W art     : b4868000-b4869000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-11 12:01:59.941  6379  6379 W art     : b4869000-b486a000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-11 12:01:59.941  6379  6379 W art     : b486a000-b486b000 r--p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b486b000-b488b000 r--s 00000000 00:0b 6710       /dev/__properties__
08-11 12:01:59.941  6379  6379 W art     : b488b000-b529c000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-11 12:01:59.941  6379  6379 W art     : b529c000-b529d000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b529d000-b52e6000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-11 12:01:59.941  6379  6379 W art     : b52e6000-b52e7000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-11 12:01:59.941  6379  6379 W art     : b52e7000-b52ef000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b52ef000-b52f0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b52f0000-b5325000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-11 12:01:59.941  6379  6379 W art     : b5325000-b5326000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5326000-b5327000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-11 12:01:59.941  6379  6379 W art     : b5327000-b5328000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-11 12:01:59.941  6379  6379 W art     : b5328000-b5380000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 12:01:59.941  6379  6379 W art     : b5380000-b5381000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5381000-b5382000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-11 12:01:59.941  6379  6379 W art     : b5382000-b5383000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-11 12:01:59.941  6379  6379 W art     : b5384000-b538a000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 12:01:59.941  6379  6379 W art     : b538a000-b538b000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 12:01:59.941  6379  6379 W art     : b538b000-b538c000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 12:01:59.941  6379  6379 W art     : b538c000-b538e000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b538f000-b5399000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:01:59.941  6379  6379 W art     : b5399000-b539c000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:01:59.941  6379  6379 W art     : b539c000-b539d000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:01:59.941  6379  6379 W art     : b539e000-b53b5000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:01:59.941  6379  6379 W art     : b53b5000-b53b6000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b53b6000-b53b7000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:01:59.941  6379  6379 W art     : b53b7000-b53b8000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:01:59.941  6379  6379 W art     : b53b9000-b53c3000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:01:59.941  6379  6379 W art     : b53c3000-b53c4000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:01:59.941  6379  6379 W art     : b53c4000-b53c5000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:01:59.941  6379  6379 W art     : b53c5000-b53c9000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 12:01:59.941  6379  6379 W art     : b53c9000-b53ca000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 12:01:59.941  6379  6379 W art     : b53ca000-b53cb000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 12:01:59.941  6379  6379 W art     : b53cb000-b53e1000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 12:01:59.941  6379  6379 W art     : b53e1000-b53e2000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 12:01:59.941  6379  6379 W art     : b53e2000-b53e3000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-11 12:01:59.941  6379  6379 W art     : b53e3000-b53f0000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:01:59.941  6379  6379 W art     : b53f0000-b53f1000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:01:59.941  6379  6379 W art     : b53f1000-b53f2000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:01:59.941  6379  6379 W art     : b53f2000-b5452000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-11 12:01:59.941  6379  6379 W art     : b5452000-b5455000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-11 12:01:59.941  6379  6379 W art     : b5455000-b5459000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5459000-b54ba000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-11 12:01:59.941  6379  6379 W art     : b54ba000-b54bb000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 12:01:59.941  6379  6379 W art     : b54bb000-b550a000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-11 12:01:59.941  6379  6379 W art     : b550a000-b550c000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 12:01:59.941  6379  6379 W art     : b550c000-b550d000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-11 12:01:59.941  6379  6379 W art     : b550d000-b550e000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b550e000-b5515000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 12:01:59.941  6379  6379 W art     : b5515000-b5516000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 12:01:59.941  6379  6379 W art     : b5516000-b5517000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-11 12:01:59.941  6379  6379 W art     : avc_common.so
08-11 12:01:59.941  6379  6379 W art     : b5518000-b551b000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 12:01:59.941  6379  6379 W art     : b551b000-b551c000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 12:01:59.941  6379  6379 W art     : b551c000-b551d000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-11 12:01:59.941  6379  6379 W art     : enc_common.so
08-11 12:01:59.941  6379  6379 W art     : b551e000-b5522000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-11 12:01:59.941  6379  6379 W art     : b5522000-b5523000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5523000-b5524000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-11 12:01:59.941  6379  6379 W art     : b5524000-b5525000 rw-p 00005000 b3:17 2510       /syste
08-11 12:01:59.941  6379  6379 W art     : m/lib/libpowermanager.so
08-11 12:01:59.941  6379  6379 W art     : b5526000-b5543000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 12:01:59.941  6379  6379 W art     : b5543000-b5544000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 12:01:59.941  6379  6379 W art     : b5544000-b5545000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 12:01:59.941  6379  6379 W art     : b5546000-b554b000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:01:59.941  6379  6379 W art     : b554b000-b554c000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:01:59.941  6379  6379 W art     : b554c000-b554d000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:01:59.941  6379  6379 W art     : b554e000-b557f000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:01:59.941  6379  6379 W art     : b557f000-b5582000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:01:59.941  6379  6379 W art     : b5582000-b5583000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:01:59.941  6379  6379 W art     : b5584000-b55bf000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-11 12:01:59.941  6379  6379 W art     : b55bf000-b55c0000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 12:01:59.941  6379  6379 W art     : b55c0000-b55c1000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-11 12:01:59.941  6379  6379 W art     : b55c2000-b55c9000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 12:01:59.941  6379  6379 W art     : b55c9000-b55ca000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b55ca000-b55cb000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 12:01:59.941  6379  6379 W art     : b55cb000-b55cc000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-11 12:01:59.941  6379  6379 W art     : b55cc000-b55cd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b55cd000-b55e4000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:01:59.941  6379  6379 W art     : b55e4000-b55e5000 ---p 00000000 00:00 0 
08-11 12:01:59.951  1860  6466 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-11 12:01:59.941  6379  6379 W art     : b55e5000-b55e8000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:01:59.941  6379  6379 W art     : b55e8000-b55e9000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:01:59.941  6379  6379 W art     : b55e9000-b5608000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:01:59.941  6379  6379 W art     : b5608000-b5609000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:01:59.941  6379  6379 W art     : b5609000-b560a000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:01:59.941  6379  6379 W art     : b560a000-b5648000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-11 12:01:59.941  6379  6379 W art     : b5648000-b5649000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5649000-b564b000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 12:01:59.941  6379  6379 W art     : b564b000-b564c000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 12:01:59.941  6379  6379 W art     : b564d000-b5654000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 12:01:59.941  6379  6379 W art     : b5654000-b5655000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 12:01:59.941  6379  6379 W art     : b5655000-b5656000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 12:01:59.941  6379  6379 W art     : b5657000-b565a000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:01:59.941  6379  6379 W art     : b565a000-b565b000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:01:59.941  6379  6379 W art     : b565b000-b565c000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:01:59.941  6379  6379 W art     : b565c000-b5662000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b5662000-b5663000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5663000-b5664000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b5664000-b5665000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b5665000-b566e000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:01:59.941  6379  6379 W art     : b566e000-b566f000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:01:59.941  6379  6379 W art     : b566f000-b5670000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:01:59.941  6379  6379 W art     : b5670000-b5701000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:01:59.941  6379  6379 W art     : b5701000-b5702000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5702000-b570d000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:01:59.941  6379  6379 W art     : b570d000-b570e000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:01:59.941  6379  6379 W art     : b570f000-b5721000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-11 12:01:59.941  6379  6379 W art     : b5721000-b5722000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-11 12:01:59.941  6379  6379 W art     : b5722000-b5723000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 12:01:59.941  6379  6379 W art     : b5724000-b5729000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 12:01:59.941  6379  6379 W art     : b5729000-b572a000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-11 12:01:59.941  6379  6379 W art     : b572a000-b572b000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-11 12:01:59.941  6379  6379 W art     : b572c000-b5799000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:01:59.941  6379  6379 W art     : b5799000-b579a000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b579a000-b579c000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:01:59.941  6379  6379 W art     : b579c000-b579d000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:01:59.941  6379  6379 W art     : b579d000-b579e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b579e000-b57a5000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 12:01:59.941  6379  6379 W art     : b57a5000-b57a6000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 12:01:59.941  6379  6379 W art     : b57a6000-b57a7000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 12:01:59.941  6379  6379 W art     : b57a8000-b5828000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:01:59.941  6379  6379 W art     : b5828000-b5829000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5829000-b582a000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:01:59.941  6379  6379 W art     : b582a000-b582b000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:01:59.941  6379  6379 W art     : b582b000-b5842000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5842000-b5879000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-11 12:01:59.941  6379  6379 W art     : ib/libqc-opt.so
08-11 12:01:59.941  6379  6379 W art     : b5879000-b587a000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 12:01:59.941  6379  6379 W art     : b587a000-b587b000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 12:01:59.941  6379  6379 W art     : b587b000-b5897000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:01:59.941  6379  6379 W art     : b5897000-b5898000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:01:59.941  6379  6379 W art     : b5898000-b5899000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:01:59.941  6379  6379 W art     : b589a000-b58fb000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 12:01:59.941  6379  6379 W art     : b58fb000-b58fd000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 12:01:59.941  6379  6379 W art     : b58fd000-b58fe000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-11 12:01:59.941  6379  6379 W art     : b58ff000-b5926000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 12:01:59.941  6379  6379 W art     : b5926000-b5927000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5927000-b5928000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-11 12:01:59.941  6379  6379 W art     : b5928000-b5929000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 12:01:59.941  6379  6379 W art     : b592a000-b5932000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:01:59.941  6379  6379 W art     : b5932000-b5934000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:01:59.941  6379  6379 W art     : b5934000-b5935000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:01:59.941  6379  6379 W art     : b5936000-b5939000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 12:01:59.941  6379  6379 W art     : b5939000-b593a000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 12:01:59.941  6379  6379 W art     : b593a000-b593b000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-11 12:01:59.941  6379  6379 W art     : b593b000-b593f000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-11 12:01:59.941  6379  6379 W art     : b593f000-b5940000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5940000-b5941000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 12:01:59.941  6379  6379 W art     : b5941000-b5942000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-11 12:01:59.941  6379  6379 W art     : b5942000-b5952000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 12:01:59.941  6379  6379 W art     : b5952000-b5953000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-11 12:01:59.941  6379  6379 W art     : b5953000-b5954000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 12:01:59.941  6379  6379 W art     : b5954000-b599a000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b599a000-b59a3000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 12:01:59.941  6379  6379 W art     : b59a3000-b59a4000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-11 12:01:59.941  6379  6379 W art     : b59a4000-b59a5000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-11 12:01:59.941  6379  6379 W art     : b59a6000-b59ab000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 12:01:59.941  6379  6379 W art     : b59ab000-b59ac000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 12:01:59.941  6379  6379 W art     : b59ac000-b59ad000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-11 12:01:59.941  6379  6379 W art     : b59ad000-b59b0000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:01:59.941  6379  6379 W art     : b59b0000-b59b1000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b59b1000-b59b2000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:01:59.941  6379  6379 W art     : b59b2000-b59b3000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:01:59.941  6379  6379 W art     : b59b4000-b59cc000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 12:01:59.941  6379  6379 W art     : b59cc000-b59cd000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b59cd000-b59ce000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 12:01:59.941  6379  6379 W art     : b59ce000-b59cf000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 12:01:59.941  6379  6379 W art     : b59d0000-b5b6a000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:01:59.941  6379  6379 W art     : b5b6a000-b5b6b000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5b6b000-b5b78000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:01:59.941  6379  6379 W art     : b5b78000-b5b79000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:01:59.941  6379  6379 W art     : b5b79000-b5b7d000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 12:01:59.941  6379  6379 W art     : b5b7d000-b5b7e000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5b7e000-b5b7f000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 12:01:59.941  6379  6379 W art     : b5b7f000-b5b80000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 12:01:59.941  6379  6379 W art     : b5b80000-b5b93000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:01:59.941  6379  6379 W art     : b5b93000-b5b94000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:01:59.941  6379  6379 W art     : b5b94000-b5b95000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:01:59.941  6379  6379 W art     : b5b95000-b5b96000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:01:59.941  6379  6379 W art     : b5b96000-b5be1000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 12:01:59.941  6379  6379 W art     : b5be1000-b5be2000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 12:01:59.941  6379  6379 W art     : b5be2000-b5be3000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-11 12:01:59.941  6379  6379 W art     : b5be3000-b5be5000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5be6000-b5bf7000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:01:59.941  6379  6379 W art     : b5bf7000-b5bf8000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5bf8000-b5bf9000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:01:59.941  6379  6379 W art     : b5bf9000-b5bfa000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:01:59.941  6379  6379 W art     : b5bfb000-b5c05000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:01:59.941  6379  6379 W art     : b5c05000-b5c07000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:01:59.941  6379  6379 W art     : b5c07000-b5c08000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:01:59.941  6379  6379 W art     : b5c08000-b5c21000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-11 12:01:59.941  6379  6379 W art     : b5c21000-b5c22000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-11 12:01:59.941  6379  6379 W art     : b5c22000-b5c25000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 12:01:59.941  6379  6379 W art     : b5c25000-b5c29000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5c29000-b5c9d000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 12:01:59.941  6379  6379 W art     : b5c9d000-b5c9e000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5c9e000-b5ca1000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 12:01:59.941  6379  6379 W art     : b5ca1000-b5ca2000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 12:01:59.941  6379  6379 W art     : b5ca2000-b5ca3000 r--p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5ca3000-b5ca6000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-11 12:01:59.941  6379  6379 W art     : b5ca6000-b5ca7000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 12:01:59.941  6379  6379 W art     : b5ca7000-b5ca8000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 12:01:59.941  6379  6379 W art     : b5ca8000-b5ca9000 r--p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5ca9000-b5cae000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:01:59.941  6379  6379 W art     : b5cae000-b5caf000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:01:59.941  6379  6379 W art     : b5caf000-b5cb0000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:01:59.941  6379  6379 W art     : b5cb0000-b5cb1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b5cb1000-b5cb4000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b5cb4000-b5cb5000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b5cb5000-b5cb6000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b5cb6000-b5cb7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b5cb7000-b5cbb000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:01:59.941  6379  6379 W art     : b5cbb000-b5cbc000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:01:59.941  6379  6379 W art     : b5cbc000-b5cbd000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:01:59.941  6379  6379 W art     : b5cbd000-b5cbe000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:01:59.941  6379  6379 W art     : b5cbe000-b5cc2000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 12:01:59.941  6379  6379 W art     : b5cc2000-b5cc3000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 12:01:59.941  6379  6379 W art     : b5cc3000-b5cc4000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 12:01:59.941  6379  6379 W art     : b5cc4000-b5cc5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b5cc5000-b5cd3000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 12:01:59.941  6379  6379 W art     : b5cd3000-b5cd4000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b5cd4000-b5cd5000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-11 12:01:59.941  6379  6379 W art     : b5cd5000-b5cd6000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 12:01:59.941  6379  6379 W art     : b5cd6000-b5ce0000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 12:01:59.941  6379  6379 W art     : b5ce0000-b5ce3000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 12:01:59.941  6379  6379 W art     : b5ce3000-b5ce4000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 12:01:59.941  6379  6379 W art     : b5ce4000-b5ce5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b5ce5000-b5cef000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-11 12:01:59.941  6379  6379 W art     : b5cef000-b5cf2000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 12:01:59.941  6379  6379 W art     : b5cf2000-b5cf3000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 12:01:59.941  6379  6379 W art     : b5cf3000-b5cf7000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:01:59.941  6379  6379 W art     : b5cf7000-b5cf8000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:01:59.941  6379  6379 W art     : b5cf8000-b5cf9000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:01:59.941  6379  6379 W art     : b5cf9000-b5cfa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b5cfa000-b5d07000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:01:59.941  6379  6379 W art     : b5d07000-b5d09000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:01:59.941  6379  6379 W art     : b5d09000-b5d0a000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:01:59.941  6379  6379 W art     : b5d0a000-b611c000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 12:01:59.941  6379  6379 W art     : b611c000-b611d000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b611d000-b6126000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 12:01:59.941  6379  6379 W art     : b6126000-b612a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-11 12:01:59.941  6379  6379 W art     : b612a000-b612b000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b612b000-b6132000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:01:59.941  6379  6379 W art     : b6132000-b6133000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:01:59.941  6379  6379 W art     : b6133000-b6134000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:01:59.941  6379  6379 W art     : b6134000-b6135000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b6135000-b6150000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 12:01:59.941  6379  6379 W art     : b6150000-b6151000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-11 12:01:59.941  6379  6379 W art     : b6151000-b6152000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 12:01:59.941  6379  6379 W art     : b6152000-b6153000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b6153000-b619f000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:01:59.941  6379  6379 W art     : b619f000-b61a0000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b61a0000-b61a1000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:01:59.941  6379  6379 W art     : b61a1000-b61a2000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:01:59.941  6379  6379 W art     : b61a2000-b61a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b61a3000-b61a7000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-11 12:01:59.941  6379  6379 W art     : b61a7000-b61a8000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b61a8000-b61a9000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 12:01:59.941  6379  6379 W art     : b61a9000-b61aa000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 12:01:59.941  6379  6379 W art     : b61aa000-b61e2000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:01:59.941  6379  6379 W art     : b61e2000-b61e3000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:01:59.941  6379  6379 W art     : b61e3000-b61e4000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:01:59.941  6379  6379 W art     : b61e4000-b61e5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b61e5000-b6283000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-11 12:01:59.941  6379  6379 W art     : b6283000-b6284000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6284000-b62a2000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 12:01:59.941  6379  6379 W art     : b62a2000-b62a3000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 12:01:59.941  6379  6379 W art     : b62a3000-b6416000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:01:59.941  6379  6379 W art     : b6416000-b6421000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:01:59.941  6379  6379 W art     : b6421000-b6422000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:01:59.941  6379  6379 W art     : b6422000-b6539000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-11 12:01:59.941  6379  6379 W art     : b6539000-b6544000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 12:01:59.941  6379  6379 W art     : b6544000-b6545000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-11 12:01:59.941  6379  6379 W art     : b6545000-b6549000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6549000-b656d000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 12:01:59.941  6379  6379 W art     : b656d000-b656f000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 12:01:59.941  6379  6379 W art     : b656f000-b6570000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 12:01:59.941  6379  6379 W art     : b6570000-b6616000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-11 12:01:59.941  6379  6379 W art     : b6616000-b6623000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 12:01:59.941  6379  6379 W art     : b6623000-b6624000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 12:01:59.941  6379  6379 W art     : b6624000-b6625000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6625000-b6678000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:01:59.941  6379  6379 W art     : b6678000-b6679000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6679000-b667a000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:01:59.941  6379  6379 W art     : b667a000-b667b000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:01:59.941  6379  6379 W art     : b667b000-b6680000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6680000-b6692000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 12:01:59.941  6379  6379 W art     : b6692000-b6693000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6693000-b6694000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 12:01:59.941  6379  6379 W art     : b6694000-b6695000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-11 12:01:59.941  6379  6379 W art     : b6695000-b669c000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:01:59.941  6379  6379 W art     : b669c000-b669d000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:01:59.941  6379  6379 W art     : b669d000-b669e000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:01:59.941  6379  6379 W art     : b669e000-b669f000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b669f000-b66a2000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 12:01:59.941  6379  6379 W art     : b66a2000-b66a3000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 12:01:59.941  6379  6379 W art     : b66a3000-b66a4000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-11 12:01:59.941  6379  6379 W art     : b66a4000-b66a8000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 12:01:59.941  6379  6379 W art     : b66a8000-b66a9000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 12:01:59.941  6379  6379 W art     : b66a9000-b66aa000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 12:01:59.941  6379  6379 W art     : b66aa000-b66b8000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:01:59.941  6379  6379 W art     : b66b8000-b66b9000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b66b9000-b66ba000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:01:59.941  6379  6379 W art     : b66ba000-b66bb000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:01:59.941  6379  6379 W art     : b66bb000-b66c4000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:01:59.941  6379  6379 W art     : b66c4000-b66c5000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:01:59.941  6379  6379 W art     : b66c5000-b66c6000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:01:59.941  6379  6379 W art     : b66c6000-b672c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 12:01:59.941  6379  6379 W art     : b672c000-b672d000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b672d000-b672f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 12:01:59.941  6379  6379 W art     : b672f000-b6738000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 12:01:59.941  6379  6379 W art     : b6738000-b673b000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b673b000-b67d2000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-11 12:01:59.971   782   880 I ActivityManager: Start proc 6480:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-11 12:01:59.941  6379  6379 W art     : b67d2000-b67d4000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 12:01:59.941  6379  6379 W art     : b67d4000-b67d5000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 12:01:59.941  6379  6379 W art     : b67d5000-b67d6000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b67d6000-b6af7000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-11 12:01:59.941  6379  6379 W art     : b6af7000-b6af8000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6af8000-b6b13000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 12:01:59.941  6379  6379 W art     : b6b13000-b6b17000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-11 12:01:59.941  6379  6379 W art     : b6b17000-b6b1c000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6b1c000-b6b24000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b6b24000-b6b25000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b6b25000-b6b26000 rw-p 00008000 b3:17 2591 ,      /system/lib/libcamera_metadata.so
08-11 12:01:59.941  6379  6379 W art     : b6b26000-b6b54000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:01:59.941  6379  6379 W art     : b6b54000-b6b55000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6b55000-b6b5c000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:01:59.941  6379  6379 W art     : b6b5c000-b6b5d000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:01:59.941  6379  6379 W art     : b6b5d000-b6ba3000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:01:59.941  6379  6379 W art     : b6ba3000-b6ba4000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6ba4000-b6ba7000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:01:59.941  6379  6379 W art     : b6ba7000-b6ba8000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:01:59.941  6379  6379 W art     : b6ba8000-b6bc3000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-11 12:01:59.941  6379  6379 W art     : b6bc3000-b6bc7000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-11 12:01:59.941  6379  6379 W art     : b6bc7000-b6bc8000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 12:01:59.941  6379  6379 W art     : b6bc8000-b6c15000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-11 12:01:59.941  6379  6379 W art     : b6c15000-b6c16000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6c16000-b6c22000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 12:01:59.941  6379  6379 W art     : b6c22000-b6c23000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 12:01:59.941  6379  6379 W art     : b6c23000-b6c30000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 12:01:59.941  6379  6379 W art     : b6c30000-b6c31000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6c31000-b6c32000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 12:01:59.941  6379  6379 W art     : b6c32000-b6c33000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-11 12:01:59.941  6379  6379 W art     : b6c33000-b6c3b000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:01:59.941  6379  6379 W art     : b6c3b000-b6c3c000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6c3c000-b6c3d000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:01:59.941  6379  6379 W art     : b6c3d000-b6c3e000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:01:59.941  6379  6379 W art     : b6c3e000-b6c45000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b6c45000-b6c46000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b6c46000-b6c47000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:01:59.941  6379  6379 W art     : b6c47000-b6c5b000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-11 12:01:59.941  6379  6379 W art     : b6c5b000-b6c5d000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 12:01:59.941  6379  6379 W art     : b6c5d000-b6c5e000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 12:01:59.941  6379  6379 W art     : b6c5e000-b6c86000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:01:59.941  6379  6379 W art     : b6c86000-b6c88000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:01:59.941  6379  6379 W art     : b6c88000-b6c89000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:01:59.941  6379  6379 W art     : b6c89000-b6c8c000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 12:01:59.941  6379  6379 W art     : b6c8c000-b6c8d000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.s,o
08-11 12:01:59.941  6379  6379 W art     : b6c8d000-b6c8e000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-11 12:01:59.941  6379  6379 W art     : b6c8e000-b6c97000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:01:59.941  6379  6379 W art     : b6c97000-b6c98000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:01:59.941  6379  6379 W art     : b6c98000-b6c99000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:01:59.941  6379  6379 W art     : b6c99000-b6cb9000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 12:01:59.941  6379  6379 W art     : b6cb9000-b6cba000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 12:01:59.941  6379  6379 W art     : b6cba000-b6cbb000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 12:01:59.941  6379  6379 W art     : b6cbb000-b6d2e000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 12:01:59.941  6379  6379 W art     : b6d2e000-b6d32000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-11 12:01:59.941  6379  6379 W art     : b6d32000-b6d35000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 12:01:59.941  6379  6379 W art     : b6d35000-b6d3f000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6d3f000-b6dc7000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-11 12:01:59.941  6468  6468 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-11 12:01:59.941  6379  6379 W art     : b6dc7000-b6dc8000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6dc8000-b6dcc000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 12:01:59.941  6379  6379 W art     : b6dcc000-b6dcd000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 12:01:59.941  6379  6379 W art     : b6dcd000-b6dce000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6dce000-b6df7000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-11 12:01:59.941  6379  6379 W art     : b6df7000-b6df8000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6df8000-b6dfb000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 12:01:59.941  6379  6379 W art     : b6dfb000-b6dfc000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-11 12:01:59.941  6379  6379 W art     : b6dfc000-b6ed6000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:01:59.941  6379  6379 W art     : b6ed6000-b6edd000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:01:59.941  6379  6379 W art     : b6edd000-b6ee5000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:01:59.941  6379  6379 W art     : b6ee5000-b6ee6000 rw-p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6ee6000-b6ee7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:01:59.941  6379  6379 W art     : b6ee7000-b6ee8000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 12:01:59.941  6379  6379 W art     : b6ee8000-b6ee9000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b6ee9000-b6eec000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b6eec000-b6f11000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 12:01:59.981  6480  6480 I libpersona: KNOX_SDCARD checking this for 10210
08-11 12:01:59.941  6379  6379 W art     : b6f11000-b6f12000 ---p 00000000 00:00 0 
08-11 12:01:59.981  6480  6480 I libpersona: KNOX_SDCARD not a persona
08-11 12:01:59.941  6379  6379 W art     : b6f12000-b6f19000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 12:01:59.941  6379  6379 W art     : b6f19000-b6f1a000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 12:01:59.941  6379  6379 W art     : b6f1a000-b6f21000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-11 12:01:59.941  6379  6379 W art     : b6f21000-b6f22000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 12:01:59.941  6379  6379 W art     : b6f22000-b6f23000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-11 12:01:59.941  6379  6379 W art     : b6f23000-b6f24000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.941  6379  6379 W art     : b6f24000-b6f3c000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 12:01:59.941  6379  6379 W art     : b6f3c000-b6f3d000 ---p 00000000 00:00 0 
08-11 12:01:59.941  6379  6379 W art     : b6f3d000-b6f3e000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 12:01:59.941  6379  6379 W art     : b6f3e000-b6f3f000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 12:01:59.941  6379  6379 W art     : b6f3f000-b6f4d000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 12:01:59.941  6379  6379 W art     : b6f4d000-b6f4e000 ---p 00000000 00:00 0 
08-11 12:01:59.951  6379  6379 W art     : b6f4e000-b6f4f000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-11 12:01:59.951  6379  6379 W art     : b6f4f000-b6f50000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 12:01:59.951  6379  6379 W art     : b6f50000-b6f51000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:01:59.951  6379  6379 W art     : b6f51000-b6f53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.951  6379  6379 W art     : b6f53000-b6f54000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.951  6379  6379 W art     : b6f54000-b6f55000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:01:59.951  6379  6379 W art     : b6f55000-b6f56000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-11 12:01:59.951  6379  6379 W art     : b6f56000-b6f57000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:01:59.951  6379  6379 W art     : b6f57000-b6f77000 r--s 00000000 00:0b 6710       /dev/__properties__
08-11 12:01:59.951  6379  6379 W art     : b6f77000-b6f78000 r--p 00000000 00:00 0 
08-11 12:01:59.951  6379  6379 W art     : b6f78000-b6f79000 ---p 00000000 00:00 0 
08-11 12:01:59.951  6379  6379 W art     : b6f79000-b6f7b000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 12:01:59.951  6379  6379 W art     : b6f7b000-b6f7c000 r-xp 00000000 00:00 0          [sigpage]
08-11 12:01:59.951  6379  6379 W art     : b6f7c000-b6f97000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-11 12:01:59.951  6379  6379 W art     : b6f97000-b6f98000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 12:01:59.951  6379  6379 W art     : b6f98000-b6f9a000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 12:01:59.951  6379  6379 W art     : b6f9a000-b6f9c000 rw-p 00000000 00:00 0 
08-11 12:01:59.951  6379  6379 W art     : b6f9c000-b6fa1000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 12:01:59.951  6379  6379 W art     : b6fa1000-b6fa2000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 12:01:59.951  6379  6379 W art     : b6fa2000-b6fa3000 rw-p 00000000 00:00 0 
08-11 12:01:59.951  6379  6379 W art     : bee3d000-bee5e000 rw-p 00000000 00:00 0          [stack]
08-11 12:01:59.951  6379  6379 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-11 12:01:59.981  6480  6480 E Zygote  : v2
08-11 12:01:59.981  6480  6480 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:01:59.981  6480  6480 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:01:59.981  6480  6480 E Zygote  : accessInfo : 0
08-11 12:01:59.981  6480  6480 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-11 12:01:59.981  6379  6379 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 12:01:59.991   782  1236 V AlarmManager: Expired Alarm result :8
08-11 12:01:59.991  1860  6466 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-11 12:02:00.011  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:00.011  6480  6480 D ActivityThread: Added TimaKeyStore provider
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: onUnbind
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: CSB onClientsDisconnected
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: tearDown
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: tearDownCarState
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: Skip, car not connected.
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: tearDownClientState
08-11 12:02:00.021  6276  6276 D CAR.SERVICE: requestStop
08-11 12:02:00.031  6379  6379 I Radio-JNI: register_android_hardware_Radio DONE
08-11 12:02:00.031  6379  6379 E AffinityControl: AffinityControl: registerfunction enter
08-11 12:02:00.051   782  1806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c73f3 3253:com.android.contacts/u0a19}
08-11 12:02:00.051  6276  6276 D CAR.SERVICE: onDestroy
08-11 12:02:00.051  6379  6379 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 12:02:00.061  6276  6276 D CAR.SERVICE: tearDown
08-11 12:02:00.061  6276  6276 D CAR.SERVICE: tearDownCarState
08-11 12:02:00.061  6276  6276 D CAR.SERVICE: Skip, car not connected.
08-11 12:02:00.061  6276  6276 D CAR.SERVICE: tearDownClientState
08-11 12:02:00.061  6276  6276 D CAR.SERVICE: requestStop
08-11 12:02:00.061  6480  6480 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-11 12:02:00.071  6499  6499 E Zygote  : v2
08-11 12:02:00.071  6499  6499 I libpersona: KNOX_SDCARD checking this for 10049
08-11 12:02:00.071  6499  6499 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:00.071  6499  6499 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:00.071  6499  6499 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:00.071  6499  6499 E Zygote  : accessInfo : 0
08-11 12:02:00.081  6499  6499 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-11 12:02:00.081   782  1806 I ActivityManager: Start proc 6499:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-11 12:02:00.081  6480  6480 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-11 12:02:00.101  6480  6480 D AASAservice: onCreate()
08-11 12:02:00.111   782   797 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:00.111  6276  6276 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@a27d61 that was originally bound here
08-11 12:02:00.111  6276  6276 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@a27d61 that was originally bound here
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 12:02:00.111  6276  6276 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 12:02:00.111  6499  6499 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:00.111  6499  6499 D ActivityThread: Added TimaKeyStore provider
08-11 12:02:00.121  1860  6466 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 240 ms] updated apps [took 240 ms] 
08-11 12:02:00.121   782   797 D ActivityManager: mDVFSHelper.acquire()
08-11 12:02:00.131   782   797 V WindowManager: addAppToken: AppWindowToken{3b4c552 token=Token{82dc5dd ActivityRecord{ddd95b4 u0 com.test.thalitest/.MainActivity t153}}} to stack=1 task=153 at 0
08-11 12:02:00.131   782   909 D SecWifiDisplayUtil: Metadata value : none
08-11 12:02:00.131   782   909 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{517acaa V.E...... R.....ID 0,0-0,0}
08-11 12:02:00.141   782   909 D ISSUE_DEBUG: InputChannelName : 42c38 Starting com.test.thalitest
08-11 12:02:00.151  6512  6512 E Zygote  : v2
08-11 12:02:00.151  6512  6512 I libpersona: KNOX_SDCARD checking this for 10004
08-11 12:02:00.151   782   797 I ActivityManager: Start proc 6512:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-11 12:02:00.151  6512  6512 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:00.151  6512  6512 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:00.151  6512  6512 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:00.151  6512  6512 E Zygote  : accessInfo : 0
08-11 12:02:00.151  6512  6512 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-11 12:02:00.151   782   797 D InputDispatcher: Focused application set to: xxxx
08-11 12:02:00.151   782   797 D InputDispatcher: Focus left window: 4526
08-11 12:02:00.151  6379  6379 D AndroidRuntime: Shutting down VM
08-11 12:02:00.151   782  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 12:02:00.151  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-11 12:02:00.151   782   882 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5da272d u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-11 12:02:00.161   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-11 12:02:00.171   782  2603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2901411 6499:com.android.mms/u0a49}
08-11 12:02:00.171   782  1807 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@39be976
08-11 12:02:00.171  5485  5485 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-11 12:02:00.171   782  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-11 12:02:00.181   782   796 I ActivityManager: Killing 4973:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-11 12:02:00.181  6499  6499 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-11 12:02:00.181   782   909 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:782 uid:1000
08-11 12:02:00.181   782   909 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 12:02:00.181   782   909 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:782 uid:1000
08-11 12:02:00.181   782   909 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-11 12:02:00.181   782   909 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-11 12:02:00.181   782   796 I ActivityManager: Killing 4207:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
08-11 12:02:00.191  6512  6512 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:00.191  6512  6512 D ActivityThread: Added TimaKeyStore provider
08-11 12:02:00.191   782  2620 V WindowOrientationListener: setCurrentAppOrientation :-1
08-11 12:02:00.191   782  2620 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-11 12:02:00.201   782   882 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{42c38 u0 d0 Starting com.test.thalitest}
08-11 12:02:00.211  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-11 12:02:00.231  6499  6499 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-11 12:02:00.231   782  2620 D ActivityManager:  Launching com.test.thalitest, updated priority
08-11 12:02:00.231   294   375 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-11 12:02:00.231   294  1295 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-11 12:02:00.241   782   909 V WindowStateAnimator: Finishing drawing window Window{42c38 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-11 12:02:00.241  4526  4526 V ActivityThread: updateVisibility : ActivityRecord{f6f7031 token=android.os.BinderProxy@d5d889a {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-11 12:02:00.241   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbefdc364
08-11 12:02:00.241  6499  6499 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-11 12:02:00.261  1778  1972 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-11 12:02:00.261  1778  1778 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-11 12:02:00.261   294  1295 D libEGL  : eglTerminate EGLDisplay = 0xb2d7f64c
08-11 12:02:00.271   294  1295 D libEGL  : eglTerminate EGLDisplay = 0xb2d7f64c
08-11 12:02:00.271   294   378 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-11 12:02:00.271   294  2107 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-11 12:02:00.271   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbefdc3a4
08-11 12:02:00.281  2318  3240 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-11 12:02:00.281  1778  1778 V ActivityThread: updateVisibility : ActivityRecord{912d2aa token=android.os.BinderProxy@39ff16f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-11 12:02:00.281  1778  1778 D Launcher: onTrimMemory. Level: 20
,08-11 12:02:00.551   782  2620 I WindowManager: Screenshot max retries 4 of Token{82dc5dd ActivityRecord{ddd95b4 u0 com.test.thalitest/.MainActivity t153}} appWin=Window{42c38 u0 d0 Starting com.test.thalitest} drawState=4
,08-11 12:02:00.561   782   880 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-11 12:02:00.561   782  2615 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-11 12:02:00.571   782  1643 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-11 12:02:00.581  6512  6512 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 12:02:00.591   782  3488 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 12:02:00.591  6499  6499 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-11 12:02:00.601  6499  6529 D Mms/ArtClassLoader: init before art third
,08-11 12:02:00.611  6499  6528 D Mms/ArtClassLoader: init before art second
,08-11 12:02:00.611  6499  6527 D Mms/ArtClassLoader: init before art first
,08-11 12:02:00.611  6499  6499 D Mms/TelephonyPermission: start operation mode monitor
,08-11 12:02:00.611  6499  6499 D Mms/TelephonyPermission: User ID is null set current User Id
,08-11 12:02:00.621  6512  6512 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 12:02:00.621  6512  6512 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 12:02:00.631  6499  6499 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 12:02:00.641  6499  6499 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 12:02:00.641  6499  6499 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-11 12:02:00.641  6499  6499 D Mms/TelephonyPermission: isDefault true
,08-11 12:02:00.641  6499  6499 D Mms/MmsApp: onCreate() com.android.mms
,08-11 12:02:00.641  6512  6512 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-11 12:02:00.661  6512  6512 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 12:02:00.671  6512  6512 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 12:02:00.681  6512  6512 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 7519-7522)
08-11 12:02:00.681  6512  6512 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-11 12:02:00.691  6499  6529 D Mms/ArtClassLoader: init [DONE] art
,08-11 12:02:00.691  6499  6499 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-11 12:02:00.701  6512  6512 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e23300c}
,08-11 12:02:00.701  6512  6512 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-11 12:02:00.701  6512  6536 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-11 12:02:00.701  6512  6512 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 12:02:00.701  6499  6499 D Mms/MmsApp: [start]    initCountryIso consume time = 122.559844
,08-11 12:02:00.711   782  2615 D CountryDetector: The first listener is added
,08-11 12:02:00.711  6512  6512 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-11 12:02:00.711  6499  6499 D Mms/MmsApp: [end]    initCountryIso consume time = 10.138437
08-11 12:02:00.711  6499  6499 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.096042
,08-11 12:02:00.731  6499  6499 D Mms/MmsConfig: before partial update
,08-11 12:02:00.741  6512  6512 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 12:02:00.741  6512  6512 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 12:02:00.741  6512  6512 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 12:02:00.741  6512  6512 I Adreno-EGL: Local Branch: ss
08-11 12:02:00.741  6512  6512 I Adreno-EGL: Remote Branch: 
08-11 12:02:00.741  6512  6512 I Adreno-EGL: Local Patches: 
08-11 12:02:00.741  6512  6512 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:02:00.741  6512  6512 D libEGL  : eglInitialize EGLDisplay = 0xbecd8dac
,08-11 12:02:00.761  6499  6499 D Mms/MmsConfig: Load Resize quality : 80
,08-11 12:02:00.771  6499  6499 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 12:02:00.771  6499  6499 D EasySignUpManager_1.0.5: isAuth is false
08-11 12:02:00.771  6499  6499 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-11 12:02:00.771  6499  6499 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-11 12:02:00.771  6499  6499 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-11 12:02:00.771  6499  6499 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-11 12:02:00.771  6499  6499 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-11 12:02:00.771  6499  6499 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 12:02:00.771  6499  6499 D EasySignUpManager_1.0.5: isAuth is false
08-11 12:02:00.771  6499  6499 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-11 12:02:00.771  6499  6499 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-11 12:02:00.781   782  1319 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-11 12:02:00.781   782  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-11 12:02:00.801  6499  6528 D Mms/ArtClassLoader: init [DONE] art
,08-11 12:02:00.811  1762  2128 D TP/MmsSmsProvider: query, match:2117, calling pid = 6499, accessRestricted = false
,08-11 12:02:00.821  1762  2128 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 2.099 ms
,08-11 12:02:00.821  6499  6527 D Mms/ArtClassLoader: init [DONE] art
,08-11 12:02:00.831  6499  6499 E CscParser: mps_code.dat does not exist
08-11 12:02:00.831  6499  6499 E CscParser: customer_path =/system/csc/customer.xml
08-11 12:02:00.831  6499  6499 E CscParser: fileName + /system/csc/customer.xml
,08-11 12:02:00.831  6512  6512 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-11 12:02:00.841  6499  6499 E CscParser: mps_code.dat does not exist
08-11 12:02:00.841  6499  6499 E CscParser: customer_path =/system/csc/customer.xml
08-11 12:02:00.841  6499  6499 E CscParser: fileName + /system/csc/customer.xml
,08-11 12:02:00.841  6512  6512 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 12:02:00.841  6512  6512 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-11 12:02:00.841  6512  6512 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-11 12:02:00.841  6512  6512 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-11 12:02:00.851  6499  6499 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-11 12:02:00.851  6499  6499 D Mms/MmsConfig:  enable multiwindow = true
,08-11 12:02:00.851  6499  6499 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-11 12:02:00.851  6499  6499 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-11 12:02:00.851  6499  6499 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-11 12:02:00.851  6499  6499 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-11 12:02:00.851  6499  6499 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-11 12:02:00.851  6499  6499 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-11 12:02:00.851  6499  6499 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-11 12:02:00.861  6499  6499 D Mms/MmsConfig: [end]    init() consume time = 142.348698
,08-11 12:02:00.861  6499  6499 D Mms/Contact: [start]    init() consume time = 3.5075
,08-11 12:02:00.861  6512  6512 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-11 12:02:00.871  6512  6512 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-11 12:02:00.871  6499  6499 D Mms/Contact: [end]    init consume time = 12.983698
,08-11 12:02:00.881  6499  6564 D Mms/DraftCache: [start]    rebuildCache consume time = 4.009063
,08-11 12:02:00.881  1762  1777 D TP/MmsSmsProvider: query, match:13, calling pid = 6499, accessRestricted = false
,08-11 12:02:00.881  1762  1776 D TP/MmsSmsProvider: query, match:12, calling pid = 6499, accessRestricted = false
,08-11 12:02:00.881  1762  1777 D TP/MmsSmsProvider: query, match 13:Elapsed time : 0.440 ms
,08-11 12:02:00.891  1762  1776 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.752 ms
,08-11 12:02:00.891  6499  6564 D Mms/DraftCache: [end]    rebuildCache consume time = 12.717031
,08-11 12:02:00.891  6499  6499 D Mms:transaction: roaming -> false (slotId = 0)
08-11 12:02:00.891  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 12:02:00.891  6499  6499 D Mms:transaction: auto download without roaming -> true
08-11 12:02:00.891  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-11 12:02:00.891  6499  6499 D Mms:transaction: roaming -> false (slotId = 1)
08-11 12:02:00.891  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-11 12:02:00.891  6499  6499 D Mms:transaction: auto download without roaming -> true
08-11 12:02:00.891  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-11 12:02:00.891  6499  6499 D Mms:transaction: auto download during roaming secondary -> false
08-11 12:02:00.891  6499  6499 D Mms:transaction: mAutoDownload ------> true
,08-11 12:02:00.941  6499  6499 D ComposerPerformance: 1470909720954 ms / [DONE] Composer constructor
,08-11 12:02:00.941  6499  6567 D Mms/Conversation: [start]    init() consume time = 50.631979
,08-11 12:02:00.941  6499  6499 D CII     : Log Level [5]
08-11 12:02:00.941  6499  6499 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-11 12:02:00.941  1762  2128 D TP/MmsSmsProvider: delete, match:1, calling pid = 6499
,08-11 12:02:00.941  1762  2128 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-11 12:02:00.941  1762  2128 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-11 12:02:00.941  6499  6499 I Mms/ReservationManager: ReservationManager()
08-11 12:02:00.941  6499  6499 I Mms/ReservationManager: resetAfterConnected()
08-11 12:02:00.941  1762  2128 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-11 12:02:00.951  1762  2128 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-11 12:02:00.951  1762  2128 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-11 12:02:00.951  1762  1777 D TP/MmsSmsProvider: query, match:7, calling pid = 6499, accessRestricted = false
,08-11 12:02:00.961  1762  2128 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-11 12:02:00.961  1762  1777 D TP/MmsSmsProvider: query, match 7:Elapsed time : 6.807 ms
,08-11 12:02:00.961  6499  6499 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-11 12:02:00.961  6512  6512 D SecWifiDisplayUtil: Metadata value : none
08-11 12:02:00.971  1762  2128 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-11 12:02:00.971  1762  2128 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-11 12:02:00.971  1762  2128 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-11 12:02:00.971  1762  2128 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 15.175 ms
08-11 12:02:00.971  1762  2128 D TP/MmsSmsProvider: need read changed broadcast:false
,08-11 12:02:00.971  6499  6567 D Mms/Conversation: [end]    init consume time = 25.920938
08-11 12:02:00.971  6512  6512 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7477eca I.E...... R.....ID 0,0-0,0}
08-11 12:02:00.971  6499  6567 D Mms/MessagingNotification: [start]    init() consume time = 3.520781
,08-11 12:02:00.971  6512  6570 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 12:02:00.971  6499  6499 D Mms/MmsApp: [end]    onCreate() consume time = 3.720989
,08-11 12:02:00.971  6499  6567 D Mms/MessagingNotification: [end]    init consume time = 0.558802
,08-11 12:02:00.971  6499  6499 D Mms/MmsApp: [end]    onCreate() consume time = 0.171666
,08-11 12:02:00.971   782  1802 D ISSUE_DEBUG: InputChannelName : 1ceb0e5 com.test.thalitest/com.test.thalitest.MainActivity
,08-11 12:02:00.981   782  2603 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-11 12:02:00.981   782  2603 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-11 12:02:00.981   782   782 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 12:02:00.981   782   782 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-11 12:02:00.981  6499  6499 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-11 12:02:00.981  6499  6499 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-11 12:02:00.981  6499  6499 D Mms:transaction: roaming -> false (slotId = 0)
08-11 12:02:00.981  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 12:02:00.981  6499  6499 D Mms:transaction: auto download without roaming -> true
08-11 12:02:00.981  6499  6499 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-11 12:02:00.981  6499  6499 D Mms:transaction: mAutoDownload ------> true
,08-11 12:02:00.981  6499  6571 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 9.82974
,08-11 12:02:00.981  6499  6573 D Mms/Synchronizer: [start]    doSync consume time = 1.249271
,08-11 12:02:01.001  1762  1970 D TP/MmsSmsProvider: query, match:0, calling pid = 6499, accessRestricted = false
,08-11 12:02:01.001  1762  1970 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-11 12:02:01.001  1762  1970 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.237 ms
,08-11 12:02:01.011  6574  6574 E Zygote  : v2
08-11 12:02:01.011  6574  6574 I libpersona: KNOX_SDCARD checking this for 1000
08-11 12:02:01.011  6574  6574 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:01.011   782  2615 I ActivityManager: Start proc 6574:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-11 12:02:01.011  6574  6574 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:01.011  6574  6574 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:01.011  6574  6574 E Zygote  : accessInfo : 0
,08-11 12:02:01.021  6512  6512 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6512
,08-11 12:02:01.021   782  2615 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6512 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 12:02:01.031   782  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-11 12:02:01.031   782  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 12:02:01.031   782  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 12:02:01.031   782  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-11 12:02:01.031   782  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 12:02:01.031   782  1628 I ActivityManager: Killing 5317:com.samsung.android.sm/1000 (adj 15): DHA:empty #37
,08-11 12:02:01.051  1762  2128 D TP/MmsSmsProvider: update, match:300, calling pid = 6499
08-11 12:02:01.051  1762  2128 V TP/MmsSmsProvider: syncDBData start
,08-11 12:02:01.051  1762  2128 V TP/MmsSmsProvider: syncDBData sms end
,08-11 12:02:01.051  1762  2128 V TP/MmsSmsProvider: syncDBData mms end
,08-11 12:02:01.051  1762  2128 V TP/MmsSmsProvider: syncDBData end
08-11 12:02:01.051  1762  2128 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.668 ms
,08-11 12:02:01.061  6133  6146 D BadgeProvider: query, [selection] : package=?
,08-11 12:02:01.061  1762  2129 D TP/MmsSmsProvider: query, match:400, calling pid = 6499, accessRestricted = false
,08-11 12:02:01.061   782  2615 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,08-11 12:02:01.061  6512  6536 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-11 12:02:01.061  6512  6512 D SecWifiDisplayUtil: Metadata value : none
,08-11 12:02:01.061  6499  6573 D Mms/Synchronizer: [end]    doSync consume time = 78.725052
,08-11 12:02:01.071  6574  6574 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:01.071  6574  6574 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:01.071   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-11 12:02:01.081   782  1570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{17a1674 6574:com.samsung.android.bbc.bbcagent/1000}
,08-11 12:02:01.091  6499  6571 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 21.998334
,08-11 12:02:01.091   782  2620 D InputDispatcher: Focus entered window: 6512
,08-11 12:02:01.091  6574  6574 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-11 12:02:01.091   782   909 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:782 uid:1000
08-11 12:02:01.091   782   909 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 12:02:01.091   782   909 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:782 uid:1000
08-11 12:02:01.091   782   909 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 12:02:01.091  6512  6570 D libEGL  : eglInitialize EGLDisplay = 0x9ca7c7c4
,08-11 12:02:01.091  6512  6570 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 12:02:01.091  6499  6567 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-11 12:02:01.111  6574  6574 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-11 12:02:01.111  1762  1776 D TP/SmsProvider: query,matched:26, calling pid = 6499
,08-11 12:02:01.111  1762  1776 D TP/SmsProvider: query, match 26:Elapsed time : 1.129 ms
,08-11 12:02:01.131  1762  2128 D TP/MmsSmsProvider: query, match:6, calling pid = 6499, accessRestricted = false
,08-11 12:02:01.131  1762  2128 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.162 ms
,08-11 12:02:01.151  6512  6512 V ActivityThread: updateVisibility : ActivityRecord{f005aed token=android.os.BinderProxy@90a1a35 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-11 12:02:01.161  6512  6512 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-11 12:02:01.161  6512  6512 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 12:02:01.181   782   796 V WindowStateAnimator: Finishing drawing window Window{1ceb0e5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-11 12:02:01.181  6512  6512 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-11 12:02:01.181   782  2615 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-11 12:02:01.181   782   909 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 12:02:01.181   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbefdc364
,08-11 12:02:01.191   782   782 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 12:02:01.191   782   782 I KnoxTimeoutHandler: SD activityfalse
,08-11 12:02:01.201  6591  6591 E Zygote  : v2
08-11 12:02:01.201  6591  6591 I libpersona: KNOX_SDCARD checking this for 10024
08-11 12:02:01.201   782  1319 I ActivityManager: Start proc 6591:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-11 12:02:01.201  6591  6591 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:01.201  6591  6591 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:01.201  6591  6591 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:01.201  6591  6591 E Zygote  : accessInfo : 0
,08-11 12:02:01.201  6591  6591 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-11 12:02:01.211   782   792 I art     : Background partial concurrent mark sweep GC freed 144873(8MB) AllocSpace objects, 7(1856KB) LOS objects, 27% free, 42MB/58MB, paused 2.860ms total 178.008ms
,08-11 12:02:01.221   782   909 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +664ms (total +1s80ms)
,08-11 12:02:01.221  6512  6596 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:02:01.221  6512  6596 D libEGL  : eglInitialize EGLDisplay = 0x9b46f3ec
,08-11 12:02:01.231   782   909 D ActivityManager: mDVFSHelper.release()
08-11 12:02:01.231   782   909 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ddd95b4 u0 com.test.thalitest/.MainActivity t153} time:98071
,08-11 12:02:01.231   782   909 D ViewRootImpl: #3 mView = null
,08-11 12:02:01.231   294  1295 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-11 12:02:01.231   294   375 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-11 12:02:01.231   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbefdc3a4
,08-11 12:02:01.231  6512  6512 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-11 12:02:01.241  6512  6512 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@90a1a35 time:98085
,08-11 12:02:01.251  4355  5173 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-11 12:02:01.251  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:01.251  6591  6591 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:01.261   782  1643 I ActivityManager: Killing 5246:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-11 12:02:01.291  6591  6591 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-11 12:02:01.291   782  1628 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-11 12:02:01.291  6512  6512 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6512
,08-11 12:02:01.311  6609  6609 E Zygote  : v2
08-11 12:02:01.311  6609  6609 I libpersona: KNOX_SDCARD checking this for 10097
08-11 12:02:01.311  6609  6609 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:01.311  6609  6609 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:01.311  6609  6609 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:01.311  6609  6609 E Zygote  : accessInfo : 0
,08-11 12:02:01.311  6609  6609 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-11 12:02:01.311   782  1806 I ActivityManager: Start proc 6609:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-11 12:02:01.311   782  1806 I ActivityManager: Killing 5265:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-11 12:02:01.321  6591  6591 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-11 12:02:01.331   782  6273 I HarmonyEASService: Updating for all 1
,08-11 12:02:01.351   782  1416 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-11 12:02:01.351  6609  6609 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:01.351  6609  6609 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:01.361   782  2587 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd91412 6609:com.google.android.apps.docs/u0a97}
,08-11 12:02:01.371  6609  6609 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 12:02:01.371  4355  5173 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-11 12:02:01.381  6591  6591 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-11 12:02:01.391  6609  6609 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-11 12:02:01.391  6499  6567 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-11 12:02:01.421  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-11 12:02:01.421  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-11 12:02:01.421  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-11 12:02:01.421  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-11 12:02:01.421  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-11 12:02:01.421  4355  5173 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-11 12:02:01.431  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-11 12:02:01.481  6512  6512 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:02:01.571   782  3494 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:01.601  6512  6625 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1698965200
,08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 12:02:01.611  6512  6625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5a262b added. We now have 1 listener(s)
,08-11 12:02:01.611  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-11 12:02:01.611  6512  6625 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-11 12:02:01.611  6512  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:02:01.621  6512  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 12:02:01.621  6512  6625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c7b846 added. We now have 1 listener(s)
,08-11 12:02:01.621  6512  6625 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:02:01.621  6512  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-11 12:02:01.631  6512  6625 D BluetoothAdapter: STATE_ON
,08-11 12:02:01.631  6512  6625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:02:01.631  6512  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:02:01.631  6512  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:02:01.631  6512  6625 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:02:01.631  6512  6625 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 12:02:01.631  6512  6512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:02:01.631  6512  6512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:02:01.651  6512  6512 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:02:01.691  6609  6629 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-11 12:02:01.691  6609  6629 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 12:02:01.691  6609  6629 I GAv4    :   adb logcat -s GAv4
,08-11 12:02:01.731  6609  6629 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 12:02:01.731   782  1628 V AlarmManager:  remove PendingIntent] PendingIntent{f5cd0f8: PendingIntentRecord{a00b9d1 com.google.android.apps.docs broadcastIntent}}
,08-11 12:02:01.731  6609  6629 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:02:01.731  6609  6629 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:02:01.761  6609  6635 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:02:01.801  6609  6609 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-11 12:02:01.811  6609  6609 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-11 12:02:01.831  6609  6629 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-11 12:02:01.831  6609  6629 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-11 12:02:01.831  6609  6629 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-11 12:02:01.831  6609  6629 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-11 12:02:01.901  6641  6641 E Zygote  : v2
08-11 12:02:01.901  6641  6641 I libpersona: KNOX_SDCARD checking this for 10098
08-11 12:02:01.901  6641  6641 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:01.901  6641  6641 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:01.901   782   797 I ActivityManager: Start proc 6641:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-11 12:02:01.901  6641  6641 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:01.901   782   797 I ActivityManager: Killing 5287:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-11 12:02:01.901  6641  6641 E Zygote  : accessInfo : 0
,08-11 12:02:01.901  6641  6641 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-11 12:02:01.951   782  1802 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-11 12:02:01.951  6641  6641 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:01.951  6641  6641 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:01.961   782  1628 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{586220d 6641:com.sec.android.automotive.drivelink/u0a98}
,08-11 12:02:01.961  6641  6641 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 12:02:01.981  1449  1449 D Recents : onTaskStackChanged
,08-11 12:02:01.991  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 12:02:02.001  6641  6641 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-11 12:02:02.021  2076  2076 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 12:02:02.021  2076  2076 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 12:02:02.041  2076  2076 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 12:02:02.041  6641  6641 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 12:02:02.051   782  2620 V AlarmManager:  remove PendingIntent] PendingIntent{28f764b: PendingIntentRecord{6226828 com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 12:02:02.061  6641  6661 I GMPM    : App measurement is starting up
,08-11 12:02:02.071  6641  6661 E GMPM    : getGoogleAppId failed with status: 10
,08-11 12:02:02.071  6641  6661 E GMPM    : Uploading is not possible. App measurement disabled
,08-11 12:02:02.071   782  1807 V AlarmManager:  remove PendingIntent] PendingIntent{f52b941: PendingIntentRecord{6226828 com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 12:02:02.071  6641  6641 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-11 12:02:02.101  6641  6641 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-11 12:02:02.111  6609  6630 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 12:02:02.111  6641  6641 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-11 12:02:02.151  6609  6630 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-11 12:02:02.161  6667  6667 E Zygote  : v2
08-11 12:02:02.161   782  1643 I ActivityManager: Start proc 6667:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-11 12:02:02.161  6667  6667 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.161  6667  6667 I libpersona: KNOX_SDCARD checking this for 10032
08-11 12:02:02.161  6667  6667 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:02.161  6667  6667 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:02.161  6667  6667 E Zygote  : accessInfo : 0
08-11 12:02:02.161   782  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 12:02:02.161  6667  6667 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-11 12:02:02.181  6609  6630 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-11 12:02:02.181  6609  6630 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-11 12:02:02.181  6667  6667 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.181  6667  6667 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.191  6609  6630 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-11 12:02:02.191   782  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-11 12:02:02.201  6667  6667 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-11 12:02:02.221  6609  6630 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 12:02:02.221  6667  6667 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-11 12:02:02.301  6641  6641 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-11 12:02:02.311  6641  6641 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-11 12:02:02.311  6641  6641 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-11 12:02:02.331  6641  6641 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDThu Aug 11 12:02:02 GMT+02:00 2016
,08-11 12:02:02.331  6641  6641 D DialogFlow: initQueue()
,08-11 12:02:02.341   782   796 I ActivityManager: Start proc 6681:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-11 12:02:02.341  6681  6681 E Zygote  : v2
08-11 12:02:02.341  6681  6681 I libpersona: KNOX_SDCARD checking this for 1000
08-11 12:02:02.341  6681  6681 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:02.341  6681  6681 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.341  6681  6681 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:02.341   782   796 I ActivityManager: Killing 5576:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-11 12:02:02.341   782   796 I ActivityManager: Killing 4727:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-11 12:02:02.341  6681  6681 E Zygote  : accessInfo : 0
,08-11 12:02:02.351  6667  6667 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-11 12:02:02.361   782  1806 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-11 12:02:02.381  6681  6681 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.381  6681  6681 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.391   782  1628 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d01440 6681:com.samsung.android.app.filterinstaller/1000}
,08-11 12:02:02.401  6681  6681 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-11 12:02:02.401  6667  6667 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-11 12:02:02.401  6512  6626 W jxcore-log: Initializing JXcore engine
08-11 12:02:02.401  6512  6626 W jxcore-log: JXcore engine is ready
,08-11 12:02:02.411   782  2603 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-11 12:02:02.421  6681  6681 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-11 12:02:02.431  6681  6681 E FilterPackageIntentReceiver: This package is not a effect filter
,08-11 12:02:02.441  6697  6697 E Zygote  : v2
08-11 12:02:02.441  6697  6697 I libpersona: KNOX_SDCARD checking this for 1000
08-11 12:02:02.441  6697  6697 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:02.441  6697  6697 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.441  6697  6697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:02.441  6697  6697 E Zygote  : accessInfo : 0
,08-11 12:02:02.441   782  1416 I ActivityManager: Start proc 6697:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-11 12:02:02.451   782  1416 I ActivityManager: Killing 5174:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-11 12:02:02.451  2512  2512 E audit   : type=1400 msg=audit(1470909722.451:288): avc:  denied  { ioctl } for  pid=6626 comm="Thread-912" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 12:02:02.461  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:02.461  2512  2512 E audit   : type=1300 msg=audit(1470909722.451:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9aab53c8 items=0 ppid=350 ppcomm=main pid=6626 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-912" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 12:02:02.461  2512  2512 E audit   : type=1327 msg=audit(1470909722.451:288): proctitle="com.test.thalitest"
08-11 12:02:02.461  2512  2512 E audit   : type=1320 msg=audit(1470909722.451:288): 
,08-11 12:02:02.461  2512  2512 E audit   : type=1400 msg=audit(1470909722.461:289): avc:  denied  { ioctl } for  pid=6626 comm="Thread-912" path="socket:[38739]" dev="sockfs" ino=38739 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 12:02:02.461  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:02.461  2512  2512 E audit   : type=1300 msg=audit(1470909722.461:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9aab53c8 items=0 ppid=350 ppcomm=main pid=6626 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-912" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 12:02:02.461  2512  2512 E audit   : type=1327 msg=audit(1470909722.461:289): proctitle="com.test.thalitest"
08-11 12:02:02.461  2512  2512 E audit   : type=1320 msg=audit(1470909722.461:289): 
,08-11 12:02:02.471  6512  6626 W jxcore-log: Starting JXcore engine
,08-11 12:02:02.471  6697  6697 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.471  6697  6697 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.481   782  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2444f79 6697:com.samsung.helphub/1000}
,08-11 12:02:02.491   782  1570 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-11 12:02:02.501  6697  6697 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-11 12:02:02.511  6697  6697 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-11 12:02:02.511  6667  6667 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-11 12:02:02.521  6667  6667 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-11 12:02:02.521   782  1807 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-11 12:02:02.521  6667  6667 D DialogFlow: initQueue()
,08-11 12:02:02.561  6512  6626 W jxcore-log: Platform android
08-11 12:02:02.561  6512  6626 W jxcore-log: 
08-11 12:02:02.561  6512  6626 W jxcore-log: Process ARCH arm
08-11 12:02:02.561  6512  6626 W jxcore-log: 
,08-11 12:02:02.561  6710  6710 E Zygote  : v2
08-11 12:02:02.561  6710  6710 I libpersona: KNOX_SDCARD checking this for 1000
08-11 12:02:02.561  6710  6710 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:02.561   782  1628 I ActivityManager: Start proc 6710:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-11 12:02:02.561  6710  6710 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.561  6710  6710 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:02.571  6710  6710 E Zygote  : accessInfo : 0
,08-11 12:02:02.571   782  1628 I ActivityManager: Killing 5673:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-11 12:02:02.591   782  1806 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-11 12:02:02.591  6710  6710 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.591  6710  6710 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.601   782  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d42b58 6710:com.samsung.android.app.mirrorlink/1000}
,08-11 12:02:02.611  6710  6710 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-11 12:02:02.621  6710  6710 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-11 12:02:02.661  6710  6710 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-11 12:02:02.661  6710  6710 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-11 12:02:02.661   782  2587 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbcf320 5811:com.google.android.apps.plus/u0a134}
,08-11 12:02:02.681   782  2615 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbcf320 5811:com.google.android.apps.plus/u0a134}
,08-11 12:02:02.701   782  1570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbcf320 5811:com.google.android.apps.plus/u0a134}
,08-11 12:02:02.701   782  3488 D SSRM:n  : SIOP:: AP = 480, PST = 450, CUR = 450, LCD = 0
,08-11 12:02:02.711   782  3488 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 12:02:02.741  6512  6626 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:02:02.741  6512  6626 I jxcore-log: 
,08-11 12:02:02.741  6512  6626 W jxcore-log: JXcore engine is started
,08-11 12:02:02.741  6512  6625 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 12:02:02.751  6512  6512 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 12:02:02.781   782  1628 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-11 12:02:02.791   782  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-11 12:02:02.791   782  2587 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-11 12:02:02.791   782  1319 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-11 12:02:02.801   782  1807 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-11 12:02:02.811   782  2603 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-11 12:02:02.811   782   796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-11 12:02:02.821   782   797 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-11 12:02:02.831  6726  6726 E Zygote  : v2
08-11 12:02:02.831  6726  6726 I libpersona: KNOX_SDCARD checking this for 10165
08-11 12:02:02.831  6726  6726 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:02.831  6726  6726 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.831  6726  6726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:02.831   782  2620 I ActivityManager: Start proc 6726:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-11 12:02:02.831  6726  6726 E Zygote  : accessInfo : 0
,08-11 12:02:02.831  6726  6726 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-11 12:02:02.841   782  1806 I ActivityManager: Killing 5485:com.policydm/1000 (adj 15): DHA:empty #37
,08-11 12:02:02.861  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.861  6726  6726 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.871   782   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d36d17 6726:com.sec.kidsplat.installer/u0a165}
,08-11 12:02:02.881  6726  6726 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-11 12:02:02.881   782  1802 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-11 12:02:02.881  6480  6480 D AASAservice: onDestroy()
,08-11 12:02:02.881  6480  6480 I art     : System.exit called, status: 80
,08-11 12:02:02.881  6480  6480 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-11 12:02:02.891  6726  6726 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-11 12:02:02.901   782  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d36d17 6726:com.sec.kidsplat.installer/u0a165}
,08-11 12:02:02.911   782  1807 I ActivityManager: Process com.samsung.aasaservice (pid 6480)(adj 0) has died(53,762)
,08-11 12:02:02.911   782  1807 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-11 12:02:02.911  6726  6726 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-11 12:02:02.921  6739  6739 E Zygote  : v2
08-11 12:02:02.921  6739  6739 I libpersona: KNOX_SDCARD checking this for 10142
08-11 12:02:02.921  6739  6739 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:02.931  6739  6739 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 12:02:02.931  6739  6739 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:02.931   782  1643 I ActivityManager: Start proc 6739:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-11 12:02:02.931  6739  6739 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:02.931  6739  6739 E Zygote  : accessInfo : 64
08-11 12:02:02.931  6739  6739 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 12:02:02.931  6739  6739 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-11 12:02:02.931  6739  6739 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-11 12:02:02.951   350   350 I Zygote  : Process 6480 exited cleanly (80)
,08-11 12:02:02.951  6739  6739 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:02.951  6739  6739 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:02.961   782   797 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c1aaed 6739:com.sec.android.app.sbrowser/u0a142}
,08-11 12:02:02.961  6739  6739 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 12:02:02.981  6739  6739 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-11 12:02:03.011  6499  6499 I Mms/MmsApp:  start initViewCache mms
,08-11 12:02:03.061  6739  6739 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 12:02:03.081  6739  6739 D ManifestProvider: onCreate()
,08-11 12:02:03.101  6739  6739 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-11 12:02:03.101  6739  6739 I SBrowserUtils: getSystemProperty of country_code : Poland
08-11 12:02:03.101  6739  6739 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-11 12:02:03.101  6739  6739 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-11 12:02:03.111  6739  6739 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-11 12:02:03.111  6739  6739 D [MM]MHDataBaseProvider: onCreate()
,08-11 12:02:03.131  6739  6739 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@d1c69d1)
,08-11 12:02:03.151   782  1643 I ActivityManager: Killing 5699:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-11 12:02:03.161   782  1643 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53647b6 2076:com.google.android.gms.persistent/u0a11}
,08-11 12:02:03.171   782   797 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5cad251 4355:com.google.android.gms/u0a11}
,08-11 12:02:03.171  4355  6754 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-11 12:02:03.171  4355  6755 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 12:02:03.181  4355  6755 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 12:02:03.191  4355  4355 D AsyncTaskServiceImpl: Submit a task: nzm
,08-11 12:02:03.201   782  2620 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-11 12:02:03.211   782  1364 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/153_task.xml.bak
,08-11 12:02:03.221  4355  6755 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 12:02:03.231   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53647b6 2076:com.google.android.gms.persistent/u0a11}
,08-11 12:02:03.231  4355  6755 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 12:02:03.241  4355  5173 D nzm     : Processing package: com.test.thalitest
,08-11 12:02:03.251   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5cad251 4355:com.google.android.gms/u0a11}
,08-11 12:02:03.271  4355  4355 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 12:02:03.291  6499  6499 D Mms/BubbleViewCache: fillCache bubble = 4
,08-11 12:02:03.291  4355  5173 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-11 12:02:03.291  4355  5173 D nzm     : Found info for package com.test.thalitest in db.
,08-11 12:02:03.381   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31dbfc8 5834:com.android.vending/u0a29}
,08-11 12:02:03.401  6667  6696 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 12:02:03.401  6667  6696 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 12:02:03.421   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1822d u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64d5c1c 6220:com.sec.android.app.samsungapps/u0a39}
,08-11 12:02:03.431  5834  5834 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-11 12:02:03.431  2076  2076 D WearableService: callingUid 10011, callindPid: 2076
,08-11 12:02:03.441   782  1628 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{298ffa3 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53647b6 2076:com.google.android.gms.persistent/u0a11}
,08-11 12:02:03.451  5834  5834 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-11 12:02:03.461   782  2615 V AlarmManager:  remove PendingIntent] PendingIntent{98afe59: PendingIntentRecord{36f2c9a com.google.android.gms broadcastIntent}}
,08-11 12:02:03.461  5834  5834 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 12:02:03.461  5834  5834 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-11 12:02:03.471   782  1807 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b839a1e u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31dbfc8 5834:com.android.vending/u0a29}
,08-11 12:02:03.481  6667  6696 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 12:02:03.481  6667  6696 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-11 12:02:03.481  6667  6696 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-11 12:02:03.491  6667  6696 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 12:02:03.491  6667  6696 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 12:02:03.501  5834  6762 I Finsky  : [839] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-11 12:02:03.501   782   782 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a8858cc u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fab21d3 5881:com.sec.android.app.shealth/u0a34}
,08-11 12:02:03.501  5834  5857 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-11 12:02:03.511   782  1628 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a8858cc u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16fd321 1909:com.sec.android.app.shealth:remote/u0a34}
,08-11 12:02:03.521  5834  6763 I PlayCommon: [840] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-11 12:02:03.521  5834  6763 I PlayCommon: [840] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-11 12:02:03.531   782   782 I BackgroundCompactionService: onStart. jobID=801
,08-11 12:02:03.531   782   782 I BackgroundCompactionService: onStart done. jobID=801
,08-11 12:02:03.531   782  6764 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-11 12:02:03.531   782  6764 I BackgroundCompactionService: compact_memory command done
,08-11 12:02:03.571   782  1806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a8858cc u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16fd321 1909:com.sec.android.app.shealth:remote/u0a34}
,08-11 12:02:03.591  2076  2076 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 12:02:03.631  5834  5857 I PlayCommon: [809] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-11 12:02:03.631  5834  5857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-11 12:02:03.641  5834  5857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-11 12:02:03.651   782  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cb399ef u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53647b6 2076:com.google.android.gms.persistent/u0a11}
,08-11 12:02:03.701   306  1166 D EnterpriseController: netId is 0
08-11 12:02:03.701   306  1166 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-11 12:02:03.941  5834  5857 I PlayCommon: [809] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-11 12:02:03.961  5834  5857 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-11 12:02:03.961  5834  5857 I PlayCommon: [809] com.google.android.play.a.al.e(732): No file ready to send
,08-11 12:02:04.311   782  3525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 12:02:04.601  4355  5143 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-11 12:02:04.651  4355  5143 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 12:02:04.661  4355  5143 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 12:02:04.691  4355  5143 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-11 12:02:06.611   782  3488 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 12:02:09.311   782  3525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 12:02:09.781   782   950 D PackageManager: [MSG] MCS_UNBIND
,08-11 12:02:09.781   782  1570 I ActivityManager: Killing 5785:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-11 12:02:09.811   782  1807 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-11 12:02:10.181   782   950 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-11 12:02:10.211   782   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 12:02:11.261  3746  3746 D FactoryTest: User mode
,08-11 12:02:11.261  3746  3746 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-11 12:02:11.261  3746  3746 D MTPRx   : still no open session command from host, so toast
,08-11 12:02:11.261   782  2587 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 12:02:11.271   782  2587 D ActivityManager: mDVFSHelper.acquire()
,08-11 12:02:11.271   782  2587 V WindowManager: addAppToken: AppWindowToken{be81da token=Token{b5dff85 ActivityRecord{f398cfc u0 com.samsung.android.MtpApplication/.USBConnection t154}}} to stack=1 task=154 at 0
,08-11 12:02:11.281   782  2587 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-11 12:02:11.281   782  2587 I ActivityManager: Killing 5798:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-11 12:02:11.291   782   880 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-11 12:02:11.311   782  2587 D InputDispatcher: Focused application set to: xxxx
,08-11 12:02:11.311   782  2587 D InputDispatcher: Focus left window: 6512
,08-11 12:02:11.311   782   909 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:782 uid:1000
08-11 12:02:11.311   782   909 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 12:02:11.311   782   909 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:782 uid:1000
08-11 12:02:11.311   782   909 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 12:02:11.321  3746  3746 E MTPRx   : started activity for popup
,08-11 12:02:11.321  3746  3746 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 12:02:11.321  3746  3746 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 12:02:11.331  3746  3746 D MTPUSBConnection: onCreate in USBConnection
08-11 12:02:11.331  3746  3746 V MTPUSBConnection: Registering broadcast receiver.
,08-11 12:02:11.341  3746  3746 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-11 12:02:11.341   782  1570 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-11 12:02:11.341   782  3488 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 12:02:11.371   782  1643 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-11 12:02:11.391  3746  3746 D TAG     : dev.kiessupport is : TRUE
,08-11 12:02:11.411  3746  3746 D SecWifiDisplayUtil: Metadata value : none
,08-11 12:02:11.411  3746  3746 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fa5465 V.E...... R.....I. 0,0-0,0}
,08-11 12:02:11.421  3746  6794 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 12:02:11.421   782  1570 D ISSUE_DEBUG: InputChannelName : 7fb7232 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 12:02:11.421   782  1570 D InputDispatcher: Focus entered window: 3746
,08-11 12:02:11.421   782   909 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:782 uid:1000
08-11 12:02:11.421   782   909 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 12:02:11.421   782   909 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:782 uid:1000
08-11 12:02:11.421   782   909 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 12:02:11.421   782   882 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7fb7232 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-11 12:02:11.421  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-11 12:02:11.431  3746  3746 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{317ab1d I.E...... R.....I. 0,0-0,0}
,08-11 12:02:11.431   782  2615 D ISSUE_DEBUG: InputChannelName : 4540100 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 12:02:11.431   782  1807 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-11 12:02:11.431   782  1807 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 12:02:11.431   782   782 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 12:02:11.431   782   782 I KnoxTimeoutHandler: Shared devices show user statefalse
08-11 12:02:11.431   782   782 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-11 12:02:11.461   294   294 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-11 12:02:11.481  3746  6794 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 12:02:11.481  3746  6794 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 12:02:11.481  3746  6794 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 12:02:11.481  3746  6794 I Adreno-EGL: Local Branch: ss
08-11 12:02:11.481  3746  6794 I Adreno-EGL: Remote Branch: 
08-11 12:02:11.481  3746  6794 I Adreno-EGL: Local Patches: 
08-11 12:02:11.481  3746  6794 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:02:11.481  3746  6794 D libEGL  : eglInitialize EGLDisplay = 0x9eeff7c4
08-11 12:02:11.481  3746  6794 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 12:02:11.521   294   294 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-11 12:02:11.531  3746  3746 V ActivityThread: updateVisibility : ActivityRecord{5926f60 token=android.os.BinderProxy@b6ae53a {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-11 12:02:11.541  3746  3746 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 12:02:11.631   782  2620 V WindowStateAnimator: Finishing drawing window Window{7fb7232 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 12:02:11.631  3746  3746 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 12:02:11.641   782   796 V WindowStateAnimator: Finishing drawing window Window{4540100 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 12:02:11.641  3746  3746 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-11 12:02:11.641  3746  3746 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-11 12:02:11.641   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbefdc364
,08-11 12:02:11.641   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbefdc364
,08-11 12:02:11.641   782  1643 V WindowStateAnimator: Finishing drawing window Window{7fb7232 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 12:02:11.641   782   909 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-11 12:02:11.641   782   782 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-11 12:02:11.641   782  1806 V WindowStateAnimator: Finishing drawing window Window{4540100 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 12:02:11.651  3746  3746 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b6ae53a time:108490
08-11 12:02:11.651   782   782 I KnoxTimeoutHandler: SD activityfalse
,08-11 12:02:11.651   782   909 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +346ms (total +370ms)
,08-11 12:02:11.651   782   909 D ActivityManager: mDVFSHelper.release()
,08-11 12:02:11.651   782   909 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f398cfc u0 com.samsung.android.MtpApplication/.USBConnection t154} time:108495
,08-11 12:02:11.661   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbefdc364
,08-11 12:02:12.321   782  3494 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 12:02:12.441  1449  1449 D Recents : onTaskStackChanged
,08-11 12:02:12.451  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 12:02:12.591   782  1236 V AlarmManager: Expired Alarm result :4
,08-11 12:02:12.611   782   782 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-11 12:02:12.621   782   782 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-11 12:02:12.621   782   782 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-11 12:02:12.621  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-11 12:02:12.621  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-11 12:02:12.621  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 12:02:12.621   782  2603 V AlarmManager:  remove PendingIntent] PendingIntent{424dcdf: PendingIntentRecord{f1c6f64 com.google.android.gms broadcastIntent}}
,08-11 12:02:12.631   782  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 12:02:12.631   782  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 12:02:12.641  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-11 12:02:12.641  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,08-11 12:02:12.641  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.641  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.651  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.651  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.651   782   796 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-11 12:02:12.651   782   796 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4358, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-11 12:02:12.651   782   796 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-11 12:02:12.651   782   796 D BatteryService: stay LED for charging
,08-11 12:02:12.651   782   782 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-11 12:02:12.661   782   782 I MotionRecognitionService: Plugged
,08-11 12:02:12.661   782   782 D MotionRecognitionService:   cableConnection= 1
08-11 12:02:12.661   782   782 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-11 12:02:12.661   782   782 D MotionRecognitionService: skip setTransmitPower. 
,08-11 12:02:12.661  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.671  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.671  2507  2507 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-11 12:02:12.671  2507  2913 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 12:02:12.671  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.671  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-11 12:02:12.671  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-11 12:02:12.681  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 12:02:12.681  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 12:02:12.681  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 12:02:12.681  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-11 12:02:12.721  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 12:02:12.751   782  3488 D SSRM:n  : SIOP:: AP = 460, PST = 451, CUR = 450, LCD = 0
,08-11 12:02:13.111  6512  6626 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:02:13.111  6512  6626 I jxcore-log: 
,08-11 12:02:13.111  6512  6626 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:02:13.111  6512  6626 I jxcore-log: 
,08-11 12:02:13.111  6512  6626 D BluetoothAdapter: STATE_ON
,08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:02:13.121  6512  6626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:02:13.121  6512  6626 D BluetoothAdapter: STATE_ON
,08-11 12:02:13.121  6512  6626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:02:13.121  6512  6626 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:02:13.121  6512  6626 I jxcore-log: 
,08-11 12:02:13.121  6512  6626 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:02:13.121  6512  6626 I jxcore-log: 
,08-11 12:02:13.471  6512  6626 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 12:02:13.471  6512  6626 I jxcore-log: Failed to execute UT.
08-11 12:02:13.471  6512  6626 I jxcore-log: 
08-11 12:02:13.471  6512  6626 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 12:02:13.471  6512  6626 I jxcore-log: 
,08-11 12:02:13.481  6512  6626 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:02:13.481  6512  6626 I jxcore-log: 
,08-11 12:02:13.481  6512  6512 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 12:02:14.311   782  3525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 12:02:14.461  2512  2512 E audit   : type=1400 msg=audit(1470909734.451:290): avc:  denied  { execmod } for  pid=6816 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 12:02:14.461  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:14.461  2512  2512 E audit   : type=1300 msg=audit(1470909734.451:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe5000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6816 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 12:02:14.461  2512  2512 E audit   : type=1327 msg=audit(1470909734.451:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 12:02:14.461  2512  2512 E audit   : type=1320 msg=audit(1470909734.451:290): 
,08-11 12:02:14.511  2512  2512 E audit   : type=1400 msg=audit(1470909734.511:291): avc:  denied  { execmod } for  pid=6816 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0,
,08-11 12:02:14.511  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:14.521  2512  2512 E audit   : type=1300 msg=audit(1470909734.511:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa5000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6816 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null),
,08-11 12:02:14.521  2512  2512 E audit   : type=1327 msg=audit(1470909734.511:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-11 12:02:14.521  2512  2512 E audit   : type=1320 msg=audit(1470909734.511:291): 
,08-11 12:02:14.561  2512  2512 E audit   : type=1400 msg=audit(1470909734.561:292): avc:  denied  { execmod } for  pid=6816 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 12:02:14.561  2512  2512 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:14.561  6816  6816 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 12:02:14.561  2512  2512 E audit   : type=1300 msg=audit(1470909734.561:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa5000 a1=51000 a2=5 a3=4 items=0 ppid=3628 ppcomm=adbd pid=6816 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 12:02:14.561  2512  2512 E audit   : type=1327 msg=audit(1470909734.561:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 12:02:14.561  2512  2512 E audit   : type=1320 msg=audit(1470909734.561:292): 
,08-11 12:02:14.571  6816  6816 D AndroidRuntime: CheckJNI is OFF
,08-11 12:02:14.571  6816  6816 D AndroidRuntime: readGMSProperty: start
,08-11 12:02:14.571  6816  6816 D AndroidRuntime: readGMSProperty: already setted!!
08-11 12:02:14.571  6816  6816 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 12:02:14.571  6816  6816 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 12:02:14.571  6816  6816 D AndroidRuntime: readGMSProperty: end
08-11 12:02:14.571  6816  6816 D AndroidRuntime: addProductProperty: start
,08-11 12:02:14.581  6816  6816 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-11 12:02:14.581  6816  6816 W art     : aee0c000-b1d32000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:02:14.581  6816  6816 W art     : b1d32000-b3fa1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:02:14.581  6816  6816 W art     : b3fa1000-b3fa2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 12:02:14.581  6816  6816 W art     : b3fa2000-b3fa3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.581  6816  6816 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-11 12:02:14.581  6816  6816 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
,08-11 12:02:14.581  6816  6816 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 12:02:14.581  6816  6816 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 12:02:14.581  6816  6816 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-11 12:02:14.581  6816  6816 W art     : b484e000-b4877000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 12:02:14.581  6816  6816 W art     : b4877000-b487a000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-11 12:02:14.581  6816  6816 W art     : b487a000-b487b000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-11 12:02:14.581  6816  6816 W art     : b487b000-b487c000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-11 12:02:14.581  6816  6816 W art     : b487c000-b487d000 r--p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b487d000-b489d000 r--s 00000000 00:0b 6710       /dev/__properties__
08-11 12:02:14.581  6816  6816 W art     : b489d000-b52ae000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-11 12:02:14.581  6816  6816 W art     : b52ae000-b52af000 ---p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b52af000-b52f8000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-11 12:02:14.581  6816  6816 W art     : b52f8000-b52f9000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-11 12:02:14.581  6816  6816 W art     : b52f9000-b5301000 rw-p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b5301000-b5302000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.581  6816  6816 W art     : b5302000-b5337000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-11 12:02:14.581  6816  6816 W art     : b5337000-b5338000 ---p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b5338000-b5339000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-11 12:02:14.581  6816  6816 W art     : b5339000-b533a000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
,08-11 12:02:14.581  6816  6816 W art     : b533a000-b5392000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 12:02:14.581  6816  6816 W art     : b5392000-b5393000 ---p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b5393000-b5394000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-11 12:02:14.581  6816  6816 W art     : b5394000-b5395000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-11 12:02:14.581  6816  6816 W art     : b5396000-b539c000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 12:02:14.581  6816  6816 W art     : b539c000-b539d000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-11 12:02:14.581  6816  6816 W art     : b539d000-b539e000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 12:02:14.581  6816  6816 W art     : b539e000-b53a0000 rw-p 00000000 00:00 0 
08-11 12:02:14.581  6816  6816 W art     : b53a1000-b53ab000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:02:14.581  6816  6816 W art     : b53ab000-b53ae000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:02:14.581  6816  6816 W art     : b53ae000-b53af000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 12:02:14.581  6816  6816 W art     : b53b0000-b53c7000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:02:14.581  6816  6816 W art     : b53c7000-b53c8000 ---p 00000000 00:00 0 
,08-11 12:02:14.581  6816  6816 W art     : b53c8000-b53c9000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:02:14.581  6816  6816 W art     : b53c9000-b53ca000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 12:02:14.581  6816  6816 W art     : b53cb000-b53d5000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:02:14.581  6816  6816 W art     : b53d5000-b53d6000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:02:14.581  6816  6816 W art     : b53d6000-b53d7000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 12:02:14.581  6816  6816 W art     : b53d7000-b53db000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-11 12:02:14.581  6816  6816 W art     : b53db000-b53dc000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 12:02:14.581  6816  6816 W art     : b53dc000-b53dd000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 12:02:14.581  6816  6816 W art     : b53dd000-b53f3000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 12:02:14.581  6816  6816 W art     : b53f3000-b53f4000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 12:02:14.581  6816  6816 W art     : b53f4000-b53f5000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-11 12:02:14.581  6816  6816 W art     : b53f5000-b5402000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:02:14.581  6816  6816 W art     : b5402000-b5403000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:02:14.581  6816  6816 W art     : b5403000-b5404000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-11 12:02:14.581  6816  6816 W art     : b5404000-b5464000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-11 12:02:14.591  6816  6816 W art     : b5464000-b5467000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-11 12:02:14.591  6816  6816 W art     : b5467000-b546b000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b546b000-b54cc000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-11 12:02:14.591  6816  6816 W art     : b54cc000-b54cd000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 12:02:14.591  6816  6816 W art     : b54cd000-b551c000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-11 12:02:14.591  6816  6816 W art     : b551c000-b551e000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 12:02:14.591  6816  6816 W art     : b551e000-b551f000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-11 12:02:14.591  6816  6816 W art     : b551f000-b5520000 rw-p 00000000 00:00 0 
,08-11 12:02:14.591  6816  6816 W art     : b5520000-b5527000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 12:02:14.591  6816  6816 W art     : b5527000-b5528000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 12:02:14.591  6816  6816 W art     : b5528000-b5529000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-11 12:02:14.591  6816  6816 W art     : avc_common.so
08-11 12:02:14.591  6816  6816 W art     : b552a000-b552d000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 12:02:14.591  6816  6816 W art     : b552d000-b552e000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 12:02:14.591  6816  6816 W art     : b552e000-b552f000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-11 12:02:14.591  6816  6816 W art     : enc_common.so
08-11 12:02:14.591  6816  6816 W art     : b5530000-b5534000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
,08-11 12:02:14.591  6816  6816 W art     : b5534000-b5535000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5535000-b5536000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-11 12:02:14.591  6816  6816 W art     : b5536000-b5537000 rw-p 00005000 b3:17 2510       /syste
08-11 12:02:14.591  6816  6816 W art     : m/lib/libpowermanager.so
08-11 12:02:14.591  6816  6816 W art     : b5538000-b5555000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 12:02:14.591  6816  6816 W art     : b5555000-b5556000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 12:02:14.591  6816  6816 W art     : b5556000-b5557000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
,08-11 12:02:14.591  6816  6816 W art     : b5558000-b555d000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:02:14.591  6816  6816 W art     : b555d000-b555e000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:02:14.591  6816  6816 W art     : b555e000-b555f000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 12:02:14.591  6816  6816 W art     : b5560000-b5591000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:02:14.591  6816  6816 W art     : b5591000-b5594000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:02:14.591  6816  6816 W art     : b5594000-b5595000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 12:02:14.591  6816  6816 W art     : b5596000-b55d1000 r-xp 00000000 b3:17 893        /system/lib/libopus.so,
08-11 12:02:14.591  6816  6816 W art     : b55d1000-b55d2000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 12:02:14.591  6816  6816 W art     : b55d2000-b55d3000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-11 12:02:14.591  6816  6816 W art     : b55d4000-b55db000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 12:02:14.591  6816  6816 W art     : b55db000-b55dc000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b55dc000-b55dd000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 12:02:14.591  6816  6816 W art     : b55dd000-b55de000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
,08-11 12:02:14.591  6816  6816 W art     : b55de000-b55df000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b55df000-b55f6000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:02:14.591  6816  6816 W art     : b55f6000-b55f7000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b55f7000-b55fa000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:02:14.591  6816  6816 W art     : b55fa000-b55fb000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 12:02:14.591  6816  6816 W art     : b55fb000-b561a000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:02:14.591  6816  6816 W art     : b561a000-b561b000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:02:14.591  6816  6816 W art     : b561b000-b561c000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 12:02:14.591  6816  6816 W art     : b561c000-b565a000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-11 12:02:14.591  6816  6816 W art     : b565a000-b565b000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b565b000-b565d000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 12:02:14.591  6816  6816 W art     : b565d000-b565e000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 12:02:14.591  6816  6816 W art     : b565f000-b5666000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so,
08-11 12:02:14.591  6816  6816 W art     : b5666000-b5667000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 12:02:14.591  6816  6816 W art     : b5667000-b5668000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 12:02:14.591  6816  6816 W art     : b5669000-b566c000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:02:14.591  6816  6816 W art     : b566c000-b566d000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:02:14.591  6816  6816 W art     : b566d000-b566e000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 12:02:14.591  6816  6816 W art     : b566e000-b5674000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-11 12:02:14.591  6816  6816 W art     : b5674000-b5675000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5675000-b5676000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 12:02:14.591  6816  6816 W art     : b5676000-b5677000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 12:02:14.591  6816  6816 W art     : b5677000-b5680000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:02:14.591  6816  6816 W art     : b5680000-b5681000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:02:14.591  6816  6816 W art     : b5681000-b5682000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 12:02:14.591  6816  6816 W art     : b5682000-b5713000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:02:14.591  6816  6816 W art     : b5713000-b5714000 ---p 00000000 00:00 0 
,08-11 12:02:14.591  6816  6816 W art     : b5714000-b571f000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:02:14.591  6816  6816 W art     : b571f000-b5720000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 12:02:14.591  6816  6816 W art     : b5721000-b5733000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-11 12:02:14.591  6816  6816 W art     : b5733000-b5734000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-11 12:02:14.591  6816  6816 W art     : b5734000-b5735000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 12:02:14.591  6816  6816 W art     : b5736000-b573b000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 12:02:14.591  6816  6816 W art     : b573b000-b573c000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
,08-11 12:02:14.591  6816  6816 W art     : b573c000-b573d000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-11 12:02:14.591  6816  6816 W art     : b573e000-b57ab000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:02:14.591  6816  6816 W art     : b57ab000-b57ac000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b57ac000-b57ae000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:02:14.591  6816  6816 W art     : b57ae000-b57af000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 12:02:14.591  6816  6816 W art     : b57af000-b57b0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b57b0000-b57b7000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 12:02:14.591  6816  6816 W art     : b57b7000-b57b8000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-11 12:02:14.591  6816  6816 W art     : b57b8000-b57b9000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 12:02:14.591  6816  6816 W art     : b57ba000-b583a000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:02:14.591  6816  6816 W art     : b583a000-b583b000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b583b000-b583c000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:02:14.591  6816  6816 W art     : b583c000-b583d000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 12:02:14.591  6816  6816 W art     : b583d000-b5854000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5854000-b588b000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-11 12:02:14.591  6816  6816 W art     : ib/libqc-opt.so
08-11 12:02:14.591  6816  6816 W art     : b588b000-b588c000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-11 12:02:14.591  6816  6816 W art     : b588c000-b588d000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 12:02:14.591  6816  6816 W art     : b588d000-b58a9000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:02:14.591  6816  6816 W art     : b58a9000-b58aa000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:02:14.591  6816  6816 W art     : b58aa000-b58ab000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 12:02:14.591  6816  6816 W art     : b58ac000-b590d000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 12:02:14.591  6816  6816 W art     : b590d000-b590f000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 12:02:14.591  6816  6816 W art     : b590f000-b5910000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-11 12:02:14.591  6816  6816 W art     : b5911000-b5938000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 12:02:14.591  6816  6816 W art     : b5938000-b5939000 ---p 00000000 00:00 0 
,08-11 12:02:14.591  6816  6816 W art     : b5939000-b593a000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-11 12:02:14.591  6816  6816 W art     : b593a000-b593b000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 12:02:14.591  6816  6816 W art     : b593c000-b5944000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:02:14.591  6816  6816 W art     : b5944000-b5946000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:02:14.591  6816  6816 W art     : b5946000-b5947000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 12:02:14.591  6816  6816 W art     : b5948000-b594b000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 12:02:14.591  6816  6816 W art     : b594b000-b594c000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 12:02:14.591  6816  6816 W art     : b594c000-b594d000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-11 12:02:14.591  6816  6816 W art     : b594d000-b5951000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
,08-11 12:02:14.591  6816  6816 W art     : b5951000-b5952000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5952000-b5953000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 12:02:14.591  6816  6816 W art     : b5953000-b5954000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-11 12:02:14.591  6816  6816 W art     : b5954000-b5964000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 12:02:14.591  6816  6816 W art     : b5964000-b5965000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-11 12:02:14.591  6816  6816 W art     : b5965000-b5966000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 12:02:14.591  6816  6816 W art     : b5966000-b59ac000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b59ac000-b59b5000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 12:02:14.591  6816  6816 W art     : b59b5000-b59b6000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
,08-11 12:02:14.591  6816  6816 W art     : b59b6000-b59b7000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-11 12:02:14.591  6816  6816 W art     : b59b8000-b59bd000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 12:02:14.591  6816  6816 W art     : b59bd000-b59be000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 12:02:14.591  6816  6816 W art     : b59be000-b59bf000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-11 12:02:14.591  6816  6816 W art     : b59bf000-b59c2000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:02:14.591  6816  6816 W art     : b59c2000-b59c3000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b59c3000-b59c4000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:02:14.591  6816  6816 W art     : b59c4000-b59c5000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 12:02:14.591  6816  6816 W art     : b59c6000-b59de000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-11 12:02:14.591  6816  6816 W art     : b59de000-b59df000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b59df000-b59e0000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 12:02:14.591  6816  6816 W art     : b59e0000-b59e1000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 12:02:14.591  6816  6816 W art     : b59e2000-b5b7c000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:02:14.591  6816  6816 W art     : b5b7c000-b5b7d000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5b7d000-b5b8a000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:02:14.591  6816  6816 W art     : b5b8a000-b5b8b000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 12:02:14.591  6816  6816 W art     : b5b8b000-b5b8f000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 12:02:14.591  6816  6816 W art     : b5b8f000-b5b90000 ---p 00000000 00:00 0 
,08-11 12:02:14.591  6816  6816 W art     : b5b90000-b5b91000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 12:02:14.591  6816  6816 W art     : b5b91000-b5b92000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 12:02:14.591  6816  6816 W art     : b5b92000-b5ba5000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:02:14.591  6816  6816 W art     : b5ba5000-b5ba6000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:02:14.591  6816  6816 W art     : b5ba6000-b5ba7000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-11 12:02:14.591  6816  6816 W art     : b5ba7000-b5ba8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:02:14.591  6816  6816 W art     : b5ba8000-b5bf3000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 12:02:14.591  6816  6816 W art     : b5bf3000-b5bf4000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 12:02:14.591  6816  6816 W art     : b5bf4000-b5bf5000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
,08-11 12:02:14.591  6816  6816 W art     : b5bf5000-b5bf7000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5bf8000-b5c09000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:02:14.591  6816  6816 W art     : b5c09000-b5c0a000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5c0a000-b5c0b000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:02:14.591  6816  6816 W art     : b5c0b000-b5c0c000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 12:02:14.591  6816  6816 W art     : b5c0d000-b5c17000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:02:14.591  6816  6816 W art     : b5c17000-b5c19000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:02:14.591  6816  6816 W art     : b5c19000-b5c1a000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 12:02:14.591  6816  6816 W art     : b5c1a000-b5c33000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
,08-11 12:02:14.591  6816  6816 W art     : b5c33000-b5c34000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-11 12:02:14.591  6816  6816 W art     : b5c34000-b5c37000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 12:02:14.591  6816  6816 W art     : b5c37000-b5c3b000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5c3b000-b5caf000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 12:02:14.591  6816  6816 W art     : b5caf000-b5cb0000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5cb0000-b5cb3000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 12:02:14.591  6816  6816 W art     : b5cb3000-b5cb4000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 12:02:14.591  6816  6816 W art     : b5cb4000-b5cb5000 r--p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5cb5000-b5cb8000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,08-11 12:02:14.591  6816  6816 W art     : b5cb8000-b5cb9000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 12:02:14.591  6816  6816 W art     : b5cb9000-b5cba000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 12:02:14.591  6816  6816 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5cbb000-b5cc0000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:02:14.591  6816  6816 W art     : b5cc0000-b5cc1000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:02:14.591  6816  6816 W art     : b5cc1000-b5cc2000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 12:02:14.591  6816  6816 W art     : b5cc2000-b5cc3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b5cc3000-b5cc6000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 12:02:14.591  6816  6816 W art     : b5cc6000-b5cc7000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
,08-11 12:02:14.591  6816  6816 W art     : b5cc7000-b5cc8000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 12:02:14.591  6816  6816 W art     : b5cc8000-b5cc9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b5cc9000-b5ccd000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:02:14.591  6816  6816 W art     : b5ccd000-b5cce000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:02:14.591  6816  6816 W art     : b5cce000-b5ccf000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 12:02:14.591  6816  6816 W art     : b5ccf000-b5cd0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:02:14.591  6816  6816 W art     : b5cd0000-b5cd4000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 12:02:14.591  6816  6816 W art     : b5cd4000-b5cd5000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
,08-11 12:02:14.591  6816  6816 W art     : b5cd5000-b5cd6000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 12:02:14.591  6816  6816 W art     : b5cd6000-b5cd7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b5cd7000-b5ce5000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 12:02:14.591  6816  6816 W art     : b5ce5000-b5ce6000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b5ce6000-b5ce7000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-11 12:02:14.591  6816  6816 W art     : b5ce7000-b5ce8000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 12:02:14.591  6816  6816 W art     : b5ce8000-b5cf2000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 12:02:14.591  6816  6816 W art     : b5cf2000-b5cf5000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 12:02:14.591  6816  6816 W art     : b5cf5000-b5cf6000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-11 12:02:14.591  6816  6816 W art     : b5cf6000-b5cf7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b5cf7000-b5d01000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-11 12:02:14.591  6816  6816 W art     : b5d01000-b5d04000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 12:02:14.591  6816  6816 W art     : b5d04000-b5d05000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 12:02:14.591  6816  6816 W art     : b5d05000-b5d09000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:02:14.591  6816  6816 W art     : b5d09000-b5d0a000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:02:14.591  6816  6816 W art     : b5d0a000-b5d0b000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 12:02:14.591  6816  6816 W art     : b5d0b000-b5d0c000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-11 12:02:14.591  6816  6816 W art     : b5d0c000-b5d19000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:02:14.591  6816  6816 W art     : b5d19000-b5d1b000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:02:14.591  6816  6816 W art     : b5d1b000-b5d1c000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 12:02:14.591  6816  6816 W art     : b5d1c000-b612e000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 12:02:14.591  6816  6816 W art     : b612e000-b612f000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b612f000-b6138000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 12:02:14.591  6816  6816 W art     : b6138000-b613c000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
,08-11 12:02:14.591  6816  6816 W art     : b613c000-b613d000 rw-p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b613d000-b6144000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:02:14.591  6816  6816 W art     : b6144000-b6145000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:02:14.591  6816  6816 W art     : b6145000-b6146000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 12:02:14.591  6816  6816 W art     : b6146000-b6147000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b6147000-b6162000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 12:02:14.591  6816  6816 W art     : b6162000-b6163000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
,08-11 12:02:14.591  6816  6816 W art     : b6163000-b6164000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 12:02:14.591  6816  6816 W art     : b6164000-b6165000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b6165000-b61b1000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:02:14.591  6816  6816 W art     : b61b1000-b61b2000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b61b2000-b61b3000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:02:14.591  6816  6816 W art     : b61b3000-b61b4000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 12:02:14.591  6816  6816 W art     : b61b4000-b61b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.591  6816  6816 W art     : b61b5000-b61b9000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
,08-11 12:02:14.591  6816  6816 W art     : b61b9000-b61ba000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b61ba000-b61bb000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 12:02:14.591  6816  6816 W art     : b61bb000-b61bc000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 12:02:14.591  6816  6816 W art     : b61bc000-b61f4000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:02:14.591  6816  6816 W art     : b61f4000-b61f5000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:02:14.591  6816  6816 W art     : b61f5000-b61f6000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 12:02:14.591  6816  6816 W art     : b61f6000-b61f7000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-11 12:02:14.591  6816  6816 W art     : b61f7000-b6295000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-11 12:02:14.591  6816  6816 W art     : b6295000-b6296000 ---p 00000000 00:00 0 
08-11 12:02:14.591  6816  6816 W art     : b6296000-b62b4000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 12:02:14.591  6816  6816 W art     : b62b4000-b62b5000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 12:02:14.591  6816  6816 W art     : b62b5000-b6428000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:02:14.601  6816  6816 W art     : b6428000-b6433000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:02:14.601  6816  6816 W art     : b6433000-b6434000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 12:02:14.601  6816  6816 W art     : b6434000-b654b000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
,08-11 12:02:14.601  6816  6816 W art     : b654b000-b6556000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 12:02:14.601  6816  6816 W art     : b6556000-b6557000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-11 12:02:14.601  6816  6816 W art     : b6557000-b655b000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b655b000-b657f000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 12:02:14.601  6816  6816 W art     : b657f000-b6581000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 12:02:14.601  6816  6816 W art     : b6581000-b6582000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 12:02:14.601  6816  6816 W art     : b6582000-b6628000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
,08-11 12:02:14.601  6816  6816 W art     : b6628000-b6635000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 12:02:14.601  6816  6816 W art     : b6635000-b6636000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 12:02:14.601  6816  6816 W art     : b6636000-b6637000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6637000-b668a000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:02:14.601  6816  6816 W art     : b668a000-b668b000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b668b000-b668c000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:02:14.601  6816  6816 W art     : b668c000-b668d000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 12:02:14.601  6816  6816 W art     : b668d000-b6692000 rw-p 00000000 00:00 0 
,08-11 12:02:14.601  6816  6816 W art     : b6692000-b66a4000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 12:02:14.601  6816  6816 W art     : b66a4000-b66a5000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b66a5000-b66a6000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 12:02:14.601  6816  6816 W art     : b66a6000-b66a7000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-11 12:02:14.601  6816  6816 W art     : b66a7000-b66ae000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:02:14.601  6816  6816 W art     : b66ae000-b66af000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:02:14.601  6816  6816 W art     : b66af000-b66b0000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 12:02:14.601  6816  6816 W art     : b66b0000-b66b1000 rw-p 00000000 00:00 0 
,08-11 12:02:14.601  6816  6816 W art     : b66b1000-b66b4000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 12:02:14.601  6816  6816 W art     : b66b4000-b66b5000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 12:02:14.601  6816  6816 W art     : b66b5000-b66b6000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-11 12:02:14.601  6816  6816 W art     : b66b6000-b66ba000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 12:02:14.601  6816  6816 W art     : b66ba000-b66bb000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 12:02:14.601  6816  6816 W art     : b66bb000-b66bc000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 12:02:14.601  6816  6816 W art     : b66bc000-b66ca000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:02:14.601  6816  6816 W art     : b66ca000-b66cb000 ---p 00000000 00:00 0 
,08-11 12:02:14.601  6816  6816 W art     : b66cb000-b66cc000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:02:14.601  6816  6816 W art     : b66cc000-b66cd000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 12:02:14.601  6816  6816 W art     : b66cd000-b66d6000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:02:14.601  6816  6816 W art     : b66d6000-b66d7000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:02:14.601  6816  6816 W art     : b66d7000-b66d8000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 12:02:14.601  6816  6816 W art     : b66d8000-b673e000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 12:02:14.601  6816  6816 W art     : b673e000-b673f000 ---p 00000000 00:00 0 
,08-11 12:02:14.601  6816  6816 W art     : b673f000-b6741000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 12:02:14.601  6816  6816 W art     : b6741000-b674a000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 12:02:14.601  6816  6816 W art     : b674a000-b674d000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b674d000-b67e4000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-11 12:02:14.601  6816  6816 W art     : b67e4000-b67e6000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 12:02:14.601  6816  6816 W art     : b67e6000-b67e7000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 12:02:14.601  6816  6816 W art     : b67e7000-b67e8000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b67e8000-b6b09000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
,08-11 12:02:14.601  6816  6816 W art     : b6b09000-b6b0a000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6b0a000-b6b25000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 12:02:14.601  6816  6816 W art     : b6b25000-b6b29000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-11 12:02:14.601  6816  6816 W art     : b6b29000-b6b2e000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6b2e000-b6b36000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 12:02:14.601  6816  6816 W art     : b6b36000-b6b37000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 12:02:14.601  6816  6816 W art     : b6b37000-b6b38000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 12:02:14.601  6816  6816 W art     : b6b38000-b6b66000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:02:14.601  6816  6816 W art     : b6b66000-b6b67000 ---p 00000000 00:00 0 
,08-11 12:02:14.601  6816  6816 W art     : b6b67000-b6b6e000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:02:14.601  6816  6816 W art     : b6b6e000-b6b6f000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 12:02:14.601  6816  6816 W art     : b6b6f000-b6bb5000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:02:14.601  6816  6816 W art     : b6bb5000-b6bb6000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6bb6000-b6bb9000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:02:14.601  6816  6816 W art     : b6bb9000-b6bba000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 12:02:14.601  6816  6816 W art     : b6bba000-b6bd5000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
,08-11 12:02:14.601  6816  6816 W art     : b6bd5000-b6bd9000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-11 12:02:14.601  6816  6816 W art     : b6bd9000-b6bda000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 12:02:14.601  6816  6816 W art     : b6bda000-b6c27000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
,08-11 12:02:14.601  6816  6816 W art     : b6c27000-b6c28000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6c28000-b6c34000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 12:02:14.601  6816  6816 W art     : b6c34000-b6c35000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 12:02:14.601  6816  6816 W art     : b6c35000-b6c42000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 12:02:14.601  6816  6816 W art     : b6c42000-b6c43000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6c43000-b6c44000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 12:02:14.601  6816  6816 W art     : b6c44000-b6c45000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
,08-11 12:02:14.601  6816  6816 W art     : b6c45000-b6c4d000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:02:14.601  6816  6816 W art     : b6c4d000-b6c4e000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6c4e000-b6c4f000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:02:14.601  6816  6816 W art     : b6c4f000-b6c50000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 12:02:14.601  6816  6816 W art     : b6c50000-b6c57000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:02:14.601  6816  6816 W art     : b6c57000-b6c58000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:02:14.601  6816  6816 W art     : b6c58000-b6c59000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-11 12:02:14.601  6816  6816 W art     : b6c59000-b6c6d000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
,08-11 12:02:14.601  6816  6816 W art     : b6c6d000-b6c6f000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 12:02:14.601  6816  6816 W art     : b6c6f000-b6c70000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 12:02:14.601  6816  6816 W art     : b6c70000-b6c98000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:02:14.601  6816  6816 W art     : b6c98000-b6c9a000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:02:14.601  6816  6816 W art     : b6c9a000-b6c9b000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 12:02:14.601  6816  6816 W art     : b6c9b000-b6c9e000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 12:02:14.601  6816  6816 W art     : b6c9e000-b6c9f000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-11 12:02:14.601  6816  6816 W art     : b6c9f000-b6ca0000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
,08-11 12:02:14.601  6816  6816 W art     : b6ca0000-b6ca9000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:02:14.601  6816  6816 W art     : b6ca9000-b6caa000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:02:14.601  6816  6816 W art     : b6caa000-b6cab000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-11 12:02:14.601  6816  6816 W art     : b6cab000-b6ccb000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 12:02:14.601  6816  6816 W art     : b6ccb000-b6ccc000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 12:02:14.601  6816  6816 W art     : b6ccc000-b6ccd000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 12:02:14.601  6816  6816 W art     : b6ccd000-b6d40000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 12:02:14.601  6816  6816 W art     : b6d40000-b6d44000 r--p 00072000 b3:17 860        /system/lib/libc.so
,08-11 12:02:14.601  6816  6816 W art     : b6d44000-b6d47000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 12:02:14.601  6816  6816 W art     : b6d47000-b6d51000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6d51000-b6dd9000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-11 12:02:14.601  6816  6816 W art     : b6dd9000-b6dda000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6dda000-b6dde000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 12:02:14.601  6816  6816 W art     : b6dde000-b6ddf000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 12:02:14.601  6816  6816 W art     : b6ddf000-b6de0000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6de0000-b6e09000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
,08-11 12:02:14.601  6816  6816 W art     : b6e09000-b6e0a000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6e0a000-b6e0d000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 12:02:14.601  6816  6816 W art     : b6e0d000-b6e0e000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-11 12:02:14.601  6816  6816 W art     : b6e0e000-b6ee8000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:02:14.601  6816  6816 W art     : b6ee8000-b6eef000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:02:14.601  6816  6816 W art     : b6eef000-b6ef7000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 12:02:14.601  6816  6816 W art     : b6ef7000-b6ef8000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6ef8000-b6ef9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-11 12:02:14.601  6816  6816 W art     : b6ef9000-b6efa000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 12:02:14.601  6816  6816 W art     : b6efa000-b6efb000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6efb000-b6efe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6efe000-b6f23000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 12:02:14.601  6816  6816 W art     : b6f23000-b6f24000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6f24000-b6f2b000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 12:02:14.601  6816  6816 W art     : b6f2b000-b6f2c000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 12:02:14.601  6816  6816 W art     : b6f2c000-b6f33000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,08-11 12:02:14.601  6816  6816 W art     : b6f33000-b6f34000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 12:02:14.601  6816  6816 W art     : b6f34000-b6f35000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-11 12:02:14.601  6816  6816 W art     : b6f35000-b6f36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6f36000-b6f4e000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f4e000-b6f4f000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6f4f000-b6f50000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f50000-b6f51000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f51000-b6f5f000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f5f000-b6f60000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6f60000-b6f61000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f61000-b6f62000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 12:02:14.601  6816  6816 W art     : b6f62000-b6f63000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:02:14.601  6816  6816 W art     : b6f63000-b6f65000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6f65000-b6f66000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6f66000-b6f67000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 12:02:14.601  6816  6816 W art     : b6f67000-b6f68000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
,08-11 12:02:14.601  6816  6816 W art     : b6f68000-b6f69000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 12:02:14.601  6816  6816 W art     : b6f69000-b6f89000 r--s 00000000 00:0b 6710       /dev/__properties__
08-11 12:02:14.601  6816  6816 W art     : b6f89000-b6f8a000 r--p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6f8a000-b6f8b000 ---p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6f8b000-b6f8d000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 12:02:14.601  6816  6816 W art     : b6f8d000-b6f8e000 r-xp 00000000 00:00 0          [sigpage]
08-11 12:02:14.601  6816  6816 W art     : b6f8e000-b6fa9000 r-xp 00000000 b3:17 2770       /system/bin/linker
,08-11 12:02:14.601  6816  6816 W art     : b6fa9000-b6faa000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 12:02:14.601  6816  6816 W art     : b6faa000-b6fac000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 12:02:14.601  6816  6816 W art     : b6fac000-b6fae000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : b6fae000-b6fb3000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 12:02:14.601  6816  6816 W art     : b6fb3000-b6fb4000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 12:02:14.601  6816  6816 W art     : b6fb4000-b6fb5000 rw-p 00000000 00:00 0 
08-11 12:02:14.601  6816  6816 W art     : beb43000-beb64000 rw-p 00000000 00:00 0          [stack]
08-11 12:02:14.601  6816  6816 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-11 12:02:14.671  6816  6816 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 12:02:14.731  6816  6816 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 12:02:14.741  6816  6816 E AffinityControl: AffinityControl: registerfunction enter
,08-11 12:02:14.761  6816  6816 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 12:02:14.781   782   796 D PackageManager: START PACKAGE DELETE: observer{41430316}
08-11 12:02:14.781   782   796 D PackageManager: pkg{<packageName>}
08-11 12:02:14.781   782   796 D PackageManager: user{0}
08-11 12:02:14.781   782   796 D PackageManager: caller{2000}
08-11 12:02:14.781   782   796 D PackageManager: flags{2}
08-11 12:02:14.781   782   796 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-11 12:02:14.781   782   796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-11 12:02:14.781   782   796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-11 12:02:14.781   782   796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-11 12:02:14.781   782   796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-11 12:02:14.781   782   950 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-11 12:02:14.781   782   950 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-11 12:02:14.781   782   950 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-11 12:02:14.781   782   950 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-11 12:02:14.781   782   950 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-11 12:02:14.781   782   950 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-11 12:02:14.781   782   950 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-11 12:02:14.781   782   950 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-11 12:02:14.781   782   950 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-11 12:02:14.781   782   880 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-11 12:02:14.781   782   950 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-11 12:02:14.781   782   880 I ActivityManager: Killing 6512:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-11 12:02:14.791   782   880 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-11 12:02:14.791   782   880 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 12:02:14.811  6825  6825 E Zygote  : v2
08-11 12:02:14.811   782   880 I ActivityManager: Start proc 6825:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-11 12:02:14.811  6825  6825 I libpersona: KNOX_SDCARD checking this for 10004
08-11 12:02:14.811  6825  6825 I libpersona: KNOX_SDCARD not a persona
08-11 12:02:14.811   782   880 I ActivityManager:   Force finishing activity ActivityRecord{ddd95b4 u0 com.test.thalitest/.MainActivity t153}
,08-11 12:02:14.811  6825  6825 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 12:02:14.811  6825  6825 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 12:02:14.811  6825  6825 E Zygote  : accessInfo : 0
,08-11 12:02:14.821  6825  6825 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-11 12:02:14.821   294   375 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
,08-11 12:02:14.821   294  2107 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
,08-11 12:02:14.831   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbefdc38c
,08-11 12:02:14.841   782   950 D AASAinstall: there is not AASApackages.xml file
,08-11 12:02:14.871  6825  6825 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 12:02:14.871  6825  6825 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:14.891   782  2620 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@6f6d3f5)
,08-11 12:02:14.891   782  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 12:02:14.891   782  2615 D GraphicsStats: Buffer count: 5
08-11 12:02:14.891   782  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:02:14.891   782  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 12:02:15.121   782   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-11 12:02:15.151   782   950 W PackageSettings: Skipping PackageSetting{b487820 com.example.hello/10192} due to missing metadata
,08-11 12:02:15.241   782   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 12:02:15.251   782   797 I ActivityManager: Killing 4832:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-11 12:02:15.271   325   325 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-11 12:02:15.271  6825  6825 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 12:02:15.281  6825  6825 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-11 12:02:15.281  6825  6825 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-11 12:02:15.281   782   950 I art     : Starting a blocking GC Explicit
08-11 12:02:15.281  6825  6825 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-11 12:02:15.281  6825  6825 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-11 12:02:15.291   782  1628 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-11 12:02:15.311  6825  6825 D AndroidRuntime: Shutting down VM
,08-11 12:02:15.311  6825  6825 E AndroidRuntime: FATAL EXCEPTION: main
08-11 12:02:15.311  6825  6825 E AndroidRuntime: Process: com.test.thalitest, PID: 6825
08-11 12:02:15.311  6825  6825 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-11 12:02:15.311  6825  6825 E AndroidRuntime: 	... 9 more
,08-11 12:02:15.321  6825  6825 I Process : Sending signal. PID: 6825 SIG: 9
,08-11 12:02:15.341   782   880 I ActivityManager: Start proc 6853:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-11 12:02:15.341  6853  6853 E Zygote  : v2
08-11 12:02:15.341  6853  6853 I libpersona: KNOX_SDCARD checking this for 1000
08-11 12:02:15.341  6853  6853 I libpersona: KNOX_SDCARD not a persona
,08-11 12:02:15.341  6853  6853 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 12:02:15.341  6853  6853 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 12:02:15.341  6853  6853 E Zygote  : accessInfo : 0
,08-11 12:02:15.351   782  2603 I ActivityManager: Process com.test.thalitest (pid 6825)(adj 9) has died(153,733)
,08-11 12:02:15.351   782  2603 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 12:02:15.351   782  2603 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 12:02:15.361   782  2603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-11 12:02:15.371   782   880 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-11 12:02:15.371   782   880 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-11 12:02:15.381  6853  6853 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 12:02:15.381  6853  6853 D ActivityThread: Added TimaKeyStore provider
,08-11 12:02:15.381   782  1802 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b158a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a467fb 6853:com.samsung.android.sm/1000}
,08-11 12:02:15.391  6853  6853 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-11 12:02:15.421  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-11 12:02:15.431   782  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b158a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5cad251 4355:com.google.android.gms/u0a11}
,08-11 12:02:15.491  4355  6871 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-11 12:02:15.501   782   950 I art     : Explicit concurrent mark sweep GC freed 112914(5MB) AllocSpace objects, 21(420KB) LOS objects, 27% free, 42MB/58MB, paused 1.785ms total 217.174ms
08-11 12:02:15.501   782   792 I art     : WaitForGcToComplete blocked for 39.068ms for cause Background
,08-11 12:02:15.521   782   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 12:02:15.521   782   950 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-11 12:02:15.521   782   950 D AASAinstall: there is not AASApackages.xml file
08-11 12:02:15.521   782   950 D PackageManager: result of delete: 1{41430316}
,08-11 12:02:15.521  6816  6816 I art     : System.exit called, status: 0
08-11 12:02:15.521  6816  6816 I AndroidRuntime: VM exiting with result code 0.
08-11 12:02:15.521   782   950 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-11 12:02:15.521   782   950 D PackageManager: userId{-1}
08-11 12:02:15.521   782   950 D PackageManager: andCode{true}
,08-11 12:02:15.531   782   950 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-11 12:02:15.551  5988  6874 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-11 12:02:15.551  5988  6874 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-11 12:02:15.551  5988  6874 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-11 12:02:15.581   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.591  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-11 12:02:15.591  1379  1379 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-11 12:02:15.591   782   909 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.591   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.591   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.591   782   909 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.601   782  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 12:02:15.601  2060  2060 E SamsungIME: mOCRHelper is null
,08-11 12:02:15.611   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.611   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.611  2076  2337 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   880 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7df57f4 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a3b007 4382:com.samsung.klmsagent/u0a18}
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621   782   782 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.621  1762  1762 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 12:02:15.631   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.631   782   866 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
,08-11 12:02:15.631   782   866 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-11 12:02:15.631   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.631   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.631   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.631   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.631  3253  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 12:02:15.641  3253  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 12:02:15.641   782  1364 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/153_task.xml
,08-11 12:02:15.641  3253  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 12:02:15.641  3253  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.641  4382  4382 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Thu Aug 11 12:02:15 GMT+02:00 2016
,08-11 12:02:15.641   782  1319 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.641   782   782 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.651   782  1322 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-11 12:02:15.651   782  1322 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-11 12:02:15.651   782  1321 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-11 12:02:15.651   782  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 12:02:15.651   782  1321 V NetworkStats: performPollLocked(flags=0x3)
,08-11 12:02:15.651   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.651   782   782 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.651   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.651  4382  4382 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-11 12:02:15.661   782  1321 V NetworkStats: performPollLocked() took 8ms
,08-11 12:02:15.661   782  1321 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 12:02:15.661   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.661   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.661   782  2603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7df57f4 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{834375c 782:system/1000}
,08-11 12:02:15.661   782  1322 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 12:02:15.661   782  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 12:02:15.661  4382  4382 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-11 12:02:15.661  4382  4382 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-11 12:02:15.671  4382  4382 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 12:02:15.671  4382  6886 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-11 12:02:15.671  4382  6886 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-11 12:02:15.671  4382  6886 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-11 12:02:15.671  4382  6886 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,08-11 12:02:15.671  4382  6886 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-11 12:02:15.671  4382  6886 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-11 12:02:15.671   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.671   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.671   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.671   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.681  4382  6886 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-11 12:02:15.681  4382  6886 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 12:02:15.681  1750  6887 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-11 12:02:15.681  1750  6887 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 12:02:15.681  1750  6887 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 12:02:15.681  1750  6887 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 12:02:15.681  1750  6887 D RegisteredComponentCache: Collect Tech packages for Knox
,08-11 12:02:15.681   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.681   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.681   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.681   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.691   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691  4382  6886 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.691   782   866 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.691   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.691  4382  6886 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-11 12:02:15.701  4382  6886 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701  4382  6886 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: #################################################################
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: #################################################################
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:02:15.701  4382  6886 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: #################################################################
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: #################################################################
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-11 12:02:15.701  4382  6886 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.701   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.711   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.711   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.711  4382  6886 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-11 12:02:15.711   782   782 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.711   782   866 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.711   782   782 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.711  4382  6886 E SQLiteLog: (10) unixRead() File Descriptor : 21 gets errno : 5
08-11 12:02:15.711  4382  6886 E SQLiteLog: (266) statement aborts at 14: [SELECT TIME, TRACKER_ID, PACKAGE_NAME, _id, LICENSE_EXPIRY, LICENSE_STATUS, NEXT_VALIDATION, ALARM_TIME, ONPREM_INFO FROM deviceinfo] 
,08-11 12:02:15.711   782   782 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.721   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.721   782   782 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.721   782   866 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.721   782   866 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.721  4382  6886 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x713d2698 in tid 6886 (IntentService[K)
,08-11 12:02:15.721   782  1297 I EventHub: Removing device '/dev/input/event4' due to inotify event
08-11 12:02:15.721   782   866 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731  2512  2512 E audit_log: File locking failed. error= Bad file descriptor
,08-11 12:02:15.731  2512  2512 E audit_log: File locking failed. error= Bad file descriptor
08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.731   782   782 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731   782   866 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.731   782   866 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.731   782   866 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   866 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-11 12:02:15.741   782   866 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-11 12:02:15.741   782   866 W TextServicesManagerService: no available spell checker services found
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   782 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.741   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.751   782  2603 I ActivityManager: Process com.samsung.klmsagent (pid 4382)(adj 5) has died(182,716)
,08-11 12:02:15.751   782  2603 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
08-11 12:02:15.751   782   782 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.751   782   782 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.751   782  2603 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782  1297 I EventHub: Removing device '/dev/input/event5' due to inotify event
08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.761   782   866 W ResourcesManager: getTopLevelResources: /system/app/SecMemoDL/SecMemoDL.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   866 W ResourcesManager: getTopLevelResources: /system/app/SecMemoDL/SecMemoDL.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   866 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.771   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.801   350   350 I Zygote  : Process 4382 exited due to signal (7)
,08-11 12:02:15.801   782  1297 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-11 12:02:15.801   782   866 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   866 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.801   782   782 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.811   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 12:02:15.821   782   782 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-11 12:02:15.821   782   782 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d723aeb in tid 782 (system_server)
08-11 12:02:15.821   782   782 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 12:02:15.821  2512  2512 E audit_log: File locking failed. error= Bad file descriptor
,08-11 12:02:16.111   294   554 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
