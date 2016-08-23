#### Test 79763830b1f5deb_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-23 17:04:07.472  5461  5461 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-23 17:04:07.472  5461  5461 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-23 17:04:07.472  5461  5461 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-23 17:04:07.472  5461  5461 I art     : System.exit called, status: 0
08-23 17:04:07.472  5461  5461 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 17:04:07.552  5414  5414 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
--------- beginning of system
08-23 17:04:07.562   751  1791 I ActivityManager: Process com.samsung.aasaservice (pid 5461)(adj 0) has died(122,716)
08-23 17:04:07.562   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 17:04:07.562   751  1791 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-23 17:04:07.562   751  1791 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-23 17:04:07.592  6282  6282 E Zygote  : v2
08-23 17:04:07.592  6282  6282 I libpersona: KNOX_SDCARD checking this for 10014
08-23 17:04:07.592  6282  6282 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:07.592   751   835 I ActivityManager: Start proc 6282:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-23 17:04:07.592   751  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 17:04:07.602  6282  6282 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:07.602  6282  6282 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:07.602  6282  6282 E Zygote  : accessInfo : 0
08-23 17:04:07.602  6282  6282 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-23 17:04:07.632  6282  6282 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:07.632  6282  6282 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:07.642   751  2440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68d6427 6282:com.google.android.partnersetup/u0a14}
08-23 17:04:07.642   751  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-23 17:04:07.642  6282  6282 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-23 17:04:07.662  6282  6282 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-23 17:04:07.682   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68d6427 6282:com.google.android.partnersetup/u0a14}
08-23 17:04:07.712  6302  6302 E Zygote  : v2
08-23 17:04:07.712  6302  6302 I libpersona: KNOX_SDCARD checking this for 10015
08-23 17:04:07.712  6302  6302 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:07.712  6302  6302 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:07.712  6302  6302 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:07.712  6302  6302 E Zygote  : accessInfo : 0
08-23 17:04:07.712  6302  6302 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-23 17:04:07.712   751  1663 I ActivityManager: Start proc 6302:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-23 17:04:07.732   751  1490 I ActivityManager: Killing 5473:com.sec.esdk.elm/u0a103 (adj 15): DHA:empty #37
08-23 17:04:07.742  6302  6302 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:07.742  6302  6302 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:07.742   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5939b72 6302:com.samsung.groupcast/u0a15}
08-23 17:04:07.752   751  1623 D ActivityManager: isAutoRunBlockedApp:: com.sec.esdk.elm, Auto Run ON
08-23 17:04:07.752  6302  6302 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-23 17:04:07.782  6302  6302 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-23 17:04:07.802  6302  6302 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-23 17:04:07.802  6302  6302 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 17:04:07.802  6302  6302 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-23 17:04:07.802  6302  6302 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 17:04:07.802  6302  6302 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 17:04:07.812  6302  6302 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 17:04:07.812  6302  6302 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 17:04:07.812  6302  6302 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 17:04:07.812   751  1663 I ActivityManager: Killing 5529:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-23 17:04:07.822   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54bd7e 1861:com.sec.android.app.shealth:remote/u0a34}
08-23 17:04:07.842  6315  6315 E Zygote  : v2
08-23 17:04:07.842  6315  6315 I libpersona: KNOX_SDCARD checking this for 10041
08-23 17:04:07.842  6315  6315 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:07.842   751   764 I ActivityManager: Start proc 6315:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-23 17:04:07.842  6315  6315 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:07.842  6315  6315 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:07.842  6315  6315 E Zygote  : accessInfo : 0
08-23 17:04:07.842  6315  6315 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-23 17:04:07.852   751   765 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-23 17:04:07.872  6315  6315 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:07.872  6315  6315 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:07.882   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5621bc3 6315:com.samsung.android.sdk.samsunglink/u0a41}
08-23 17:04:07.882  6315  6315 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-23 17:04:07.982  6315  6315 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 17:04:07.982  6315  6315 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 17:04:08.042  6315  6315 I SL_DEBUG: isLoggable:: isProductShip = 1
08-23 17:04:08.042  6315  6315 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-23 17:04:08.062   751  1722 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.062   751  1424 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-23 17:04:08.072   751  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.072   751  2440 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.072   751  2070 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.072   751  1663 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.082   751  3780 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.082   751  1726 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.082   751  1623 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.082   751  1632 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-23 17:04:08.212  6315  6315 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-23 17:04:08.212  6315  6315 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-23 17:04:08.212  6315  6315 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-23 17:04:08.212  6315  6315 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-23 17:04:08.212  6315  6315 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-23 17:04:08.212  6315  6315 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 17:04:08.212  6315  6315 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 17:04:08.212  6315  6315 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 17:04:08.212  6315  6315 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 17:04:08.212  6315  6315 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 17:04:08.222   751  1632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1a703e 1666:android.process.acore/u0a19}
08-23 17:04:08.232   751  1490 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4e4711 5104:com.sec.android.gallery3d/u0a47}
08-23 17:04:08.242  5104  5104 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 17:04:08.262   751  2440 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 17:04:08.282  6345  6345 E Zygote  : v2
08-23 17:04:08.282  6345  6345 I libpersona: KNOX_SDCARD checking this for 10050
08-23 17:04:08.282  6345  6345 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.282  6345  6345 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.282  6345  6345 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.282   751  2070 I ActivityManager: Start proc 6345:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-23 17:04:08.282  6345  6345 E Zygote  : accessInfo : 0
08-23 17:04:08.282  6345  6345 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-23 17:04:08.332  6345  6345 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:08.332  6345  6345 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:08.342   751  1722 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6717bb3 6345:com.sec.android.app.myfiles/u0a50}
08-23 17:04:08.352  6345  6345 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-23 17:04:08.372  6345  6345 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-23 17:04:08.412  6345  6345 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 17:04:08.452   751  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4251c1c 2818:com.android.settings/1000}
08-23 17:04:08.462   326   326 E installd: system dir 0 : /system/app/
08-23 17:04:08.462   326   326 E installd: system dir 1 : /system/priv-app/
08-23 17:04:08.462   326   326 E installd: system dir 2 : /vendor/app/
08-23 17:04:08.462   326   326 E installd: system dir 3 : /oem/app/
08-23 17:04:08.472   751   920 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 17:04:08.472   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4251c1c 2818:com.android.settings/1000}
08-23 17:04:08.502  6362  6362 E Zygote  : v2
08-23 17:04:08.502  6362  6362 I libpersona: KNOX_SDCARD checking this for 10169
08-23 17:04:08.502  6362  6362 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.502  6362  6362 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.502  6362  6362 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.502  6362  6362 E Zygote  : accessInfo : 0
08-23 17:04:08.502  6362  6362 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-23 17:04:08.502   751  2440 I ActivityManager: Start proc 6362:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-23 17:04:08.532  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:08.532  6362  6362 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:08.542   751  1623 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e200f 6362:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-23 17:04:08.542  6362  6362 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-23 17:04:08.552  6362  6362 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-23 17:04:08.572   751   835 I ActivityManager: Start proc 6374:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-23 17:04:08.572  6374  6374 E Zygote  : v2
08-23 17:04:08.572  6374  6374 I libpersona: KNOX_SDCARD checking this for 10210
08-23 17:04:08.572  6374  6374 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.572  6374  6374 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.572  6374  6374 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.572  6374  6374 E Zygote  : accessInfo : 0
08-23 17:04:08.572  6374  6374 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-23 17:04:08.592   751  2440 I ActivityManager: Killing 5543:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-23 17:04:08.592  2309  2309 E audit   : type=1400 msg=audit(1471964648.592:284): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:04:08.592  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.602  2309  2309 E audit   : type=1300 msg=audit(1471964648.592:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:04:08.602  2309  2309 E audit   : type=1327 msg=audit(1471964648.592:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 17:04:08.602  2309  2309 E audit   : type=1320 msg=audit(1471964648.592:284): 
08-23 17:04:08.602   751  2440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e271f07 1700:com.android.phone/1001}
08-23 17:04:08.612  6374  6374 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:08.612  6374  6374 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:08.612   751  1490 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b6a240 1814:com.google.android.googlequicksearchbox:search/u0a61}
08-23 17:04:08.632   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-23 17:04:08.642  6374  6374 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-23 17:04:08.652   751  1424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b6a240 1814:com.google.android.googlequicksearchbox:search/u0a61}
08-23 17:04:08.652  6374  6374 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-23 17:04:08.662   751  3780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e5e42a5 6209:com.samsung.android.sm.provider/1000}
08-23 17:04:08.662  6374  6374 D AASAservice: onCreate()
08-23 17:04:08.662  1814  6386 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 17:04:08.672  2309  2309 E audit   : type=1400 msg=audit(1471964648.672:285): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:04:08.672  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.672  2309  2309 E audit   : type=1300 msg=audit(1471964648.672:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3a000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:04:08.672  2309  2309 E audit   : type=1327 msg=audit(1471964648.672:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 17:04:08.672  2309  2309 E audit   : type=1320 msg=audit(1471964648.672:285): 
08-23 17:04:08.672  5414  5414 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-23 17:04:08.702   751   765 I ActivityManager: Start proc 6388:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-23 17:04:08.702   751   765 I ActivityManager: Killing 4034:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-23 17:04:08.702  6388  6388 E Zygote  : v2
08-23 17:04:08.702  6388  6388 I libpersona: KNOX_SDCARD checking this for 5012
08-23 17:04:08.702  6388  6388 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.702  6388  6388 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.702  6388  6388 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.702  6388  6388 E Zygote  : accessInfo : 0
08-23 17:04:08.702  6388  6388 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-23 17:04:08.722  2309  2309 E audit   : type=1400 msg=audit(1471964648.722:286): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:04:08.722  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.722  2309  2309 E audit   : type=1300 msg=audit(1471964648.722:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3a000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:04:08.722  2309  2309 E audit   : type=1327 msg=audit(1471964648.722:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 17:04:08.722  2309  2309 E audit   : type=1320 msg=audit(1471964648.722:286): 
08-23 17:04:08.722  6279  6279 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 17:04:08.732  6279  6279 D AndroidRuntime: CheckJNI is OFF
08-23 17:04:08.732  6279  6279 D AndroidRuntime: readGMSProperty: start
08-23 17:04:08.732  6279  6279 D AndroidRuntime: readGMSProperty: already setted!!
08-23 17:04:08.732  6279  6279 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 17:04:08.732  6279  6279 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 17:04:08.732  6279  6279 D AndroidRuntime: readGMSProperty: end
08-23 17:04:08.732  6279  6279 D AndroidRuntime: addProductProperty: start
08-23 17:04:08.742   751  1632 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-23 17:04:08.742  6279  6279 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 17:04:08.742  6279  6279 W art     : af0e4000-b200a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:04:08.742  6279  6279 W art     : b200a000-b4279000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:04:08.742  6279  6279 W art     : b4279000-b427a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:04:08.742  6279  6279 W art     : b427a000-b42a3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 17:04:08.742  6279  6279 W art     : b42a3000-b46f1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 17:04:08.742  6279  6279 W art     : b46f1000-b46f2000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b46f2000-b46fc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 17:04:08.742  6279  6279 W art     : b46fc000-b46fd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 17:04:08.742  6279  6279 W art     : b46fd000-b46ff000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b46ff000-b4700000 r--p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 17:04:08.742  6279  6279 W art     : b480b000-b480e000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:04:08.742  6279  6279 W art     : b480e000-b480f000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:04:08.742  6279  6279 W art     : b480f000-b4810000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:04:08.742  6279  6279 W art     : b4810000-b4811000 r--p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b4811000-b4831000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 17:04:08.742  6279  6279 W art     : b4831000-b5242000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:04:08.742  6279  6279 W art     : b5242000-b5243000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5243000-b528c000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:04:08.742  6279  6279 W art     : b528c000-b528d000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:04:08.742  6279  6279 W art     : b528d000-b5295000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5295000-b5296000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5296000-b52cb000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:04:08.742  6279  6279 W art     : b52cb000-b52cc000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b52cc000-b52cd000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:04:08.742  6279  6279 W art     : b52cd000-b52ce000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:04:08.742  6279  6279 W art     : b52ce000-b5326000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 17:04:08.742  6279  6279 W art     : b5326000-b5327000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5327000-b5328000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 17:04:08.742  6279  6279 W art     : b5328000-b5329000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 17:04:08.742  6279  6279 W art     : b532a000-b5330000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:04:08.742  6279  6279 W art     : b5330000-b5331000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:04:08.742  6279  6279 W art     : b5331000-b5332000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:04:08.742  6279  6279 W art     : b5332000-b5334000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5335000-b533f000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:04:08.742  6279  6279 W art     : b533f000-b5342000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:04:08.742  6279  6279 W art     : b5342000-b5343000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:04:08.742  6279  6279 W art     : b5344000-b535b000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:04:08.742  6279  6279 W art     : b535b000-b535c000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b535c000-b535d000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:04:08.742  6279  6279 W art     : b535d000-b535e000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:04:08.742  6279  6279 W art     : b535f000-b5369000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:04:08.742  6279  6279 W art     : b5369000-b536a000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:04:08.742  6279  6279 W art     : b536a000-b536b000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:04:08.742  6279  6279 W art     : b536b000-b536f000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:04:08.742  6279  6279 W art     : b536f000-b5370000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:04:08.742  6279  6279 W art     : b5370000-b5371000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:04:08.742  6279  6279 W art     : b5371000-b5387000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 17:04:08.742  6279  6279 W art     : b5387000-b5388000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 17:04:08.742  6279  6279 W art     : b5388000-b5389000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 17:04:08.742  6279  6279 W art     : b5389000-b5396000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:04:08.742  6279  6279 W art     : b5396000-b5397000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:04:08.742  6279  6279 W art     : b5397000-b5398000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:04:08.742  6279  6279 W art     : b5398000-b53f8000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 17:04:08.742  6279  6279 W art     : b53f8000-b53fb000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 17:04:08.742  6279  6279 W art     : b53fb000-b53ff000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b53ff000-b5460000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 17:04:08.742  6279  6279 W art     : b5460000-b5461000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 17:04:08.742  6279  6279 W art     : b5461000-b54b0000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:04:08.742  6279  6279 W art     : b54b0000-b54b2000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:04:08.742  6279  6279 W art     : b54b2000-b54b3000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:04:08.742  6279  6279 W art     : b54b3000-b54b4000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b54b4000-b54bb000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54bb000-b54bc000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54bc000-b54bd000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 17:04:08.742  6279  6279 W art     : avc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54be000-b54c1000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54c1000-b54c2000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54c2000-b54c3000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 17:04:08.742  6279  6279 W art     : enc_common.so
08-23 17:04:08.742  6279  6279 W art     : b54c4000-b54c8000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 17:04:08.742  6279  6279 W art     : b54c8000-b54c9000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b54c9000-b54ca000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 17:04:08.742  6279  6279 W art     : b54ca000-b54cb000 rw-p 00005000 b3:17 2510       /syste
08-23 17:04:08.742  6279  6279 W art     : m/lib/libpowermanager.so
08-23 17:04:08.742  6279  6279 W art     : b54cc000-b54e9000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:04:08.742  6279  6279 W art     : b54e9000-b54ea000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:04:08.742  6279  6279 W art     : b54ea000-b54eb000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:04:08.742  6279  6279 W art     : b54ec000-b54f1000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:04:08.742  6279  6279 W art     : b54f1000-b54f2000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:04:08.742  6279  6279 W art     : b54f2000-b54f3000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:04:08.742  6279  6279 W art     : b54f4000-b5525000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:04:08.742  6279  6279 W art     : b5525000-b5528000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:04:08.742  6279  6279 W art     : b5528000-b5529000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:04:08.742  6279  6279 W art     : b552a000-b5565000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 17:04:08.742  6279  6279 W art     : b5565000-b5566000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 17:04:08.742  6279  6279 W art     : b5566000-b5567000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 17:04:08.742  6279  6279 W art     : b5568000-b556f000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:04:08.742  6279  6279 W art     : b556f000-b5570000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5570000-b5571000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:04:08.742  6279  6279 W art     : b5571000-b5572000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:04:08.742  6279  6279 W art     : b5572000-b5573000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5573000-b558a000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:04:08.742  6279  6279 W art     : b558a000-b558b000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b558b000-b558e000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:04:08.742  6279  6279 W art     : b558e000-b558f000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:04:08.742  6279  6279 W art     : b558f000-b55ae000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:04:08.742  6279  6279 W art     : b55ae000-b55af000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:04:08.742  6279  6279 W art     : b55af000-b55b0000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:04:08.742  6279  6279 W art     : b55b0000-b55ee000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 17:04:08.742  6279  6279 W art     : b55ee000-b55ef000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b55ef000-b55f1000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 17:04:08.742  6279  6279 W art     : b55f1000-b55f2000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 17:04:08.742  6279  6279 W art     : b55f3000-b55fa000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:04:08.742  6279  6279 W art     : b55fa000-b55fb000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:04:08.742  6279  6279 W art     : b55fb000-b55fc000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:04:08.742  6279  6279 W art     : b55fd000-b5600000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:04:08.742  6279  6279 W art     : b5600000-b5601000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:04:08.742  6279  6279 W art     : b5601000-b5602000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:04:08.742  6279  6279 W art     : b5602000-b5608000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:04:08.742  6279  6279 W art     : b5608000-b5609000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5609000-b560a000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:04:08.742  6279  6279 W art     : b560a000-b560b000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:04:08.742  6279  6279 W art     : b560b000-b5614000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:04:08.742  6279  6279 W art     : b5614000-b5615000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:04:08.742  6279  6279 W art     : b5615000-b5616000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:04:08.742  6279  6279 W art     : b5616000-b56a7000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:04:08.742  6279  6279 W art     : b56a7000-b56a8000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b56a8000-b56b3000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:04:08.742  6279  6279 W art     : b56b3000-b56b4000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:04:08.742  6279  6279 W art     : b56b5000-b56c7000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 17:04:08.742  6279  6279 W art     : b56c7000-b56c8000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 17:04:08.742  6279  6279 W art     : b56c8000-b56c9000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 17:04:08.742  6279  6279 W art     : b56ca000-b56cf000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:04:08.742  6279  6279 W art     : b56cf000-b56d0000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:04:08.742  6279  6279 W art     : b56d0000-b56d1000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:04:08.742  6279  6279 W art     : b56d2000-b573f000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:04:08.742  6279  6279 W art     : b573f000-b5740000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5740000-b5742000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:04:08.742  6279  6279 W art     : b5742000-b5743000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:04:08.742  6279  6279 W art     : b5743000-b5744000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5744000-b574b000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:04:08.742  6279  6279 W art     : b574b000-b574c000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:04:08.742  6279  6279 W art     : b574c000-b574d000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:04:08.742  6279  6279 W art     : b574e000-b57ce000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:04:08.742  6279  6279 W art     : b57ce000-b57cf000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b57cf000-b57d0000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:04:08.742  6279  6279 W art     : b57d0000-b57d1000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:04:08.742  6279  6279 W art     : b57d1000-b57e8000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b57e8000-b581f000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 17:04:08.742  6279  6279 W art     : ib/libqc-opt.so
08-23 17:04:08.742  6279  6279 W art     : b581f000-b5820000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 17:04:08.742  6279  6279 W art     : b5820000-b5821000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 17:04:08.742  6279  6279 W art     : b5821000-b583d000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:04:08.742  6279  6279 W art     : b583d000-b583e000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:04:08.742  6279  6279 W art     : b583e000-b583f000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:04:08.742  6279  6279 W art     : b5840000-b58a1000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 17:04:08.742  6279  6279 W art     : b58a1000-b58a3000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 17:04:08.742  6279  6279 W art     : b58a3000-b58a4000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 17:04:08.742  6279  6279 W art     : b58a5000-b58cc000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 17:04:08.742  6279  6279 W art     : b58cc000-b58cd000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b58cd000-b58ce000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 17:04:08.742  6279  6279 W art     : b58ce000-b58cf000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 17:04:08.742  6279  6279 W art     : b58d0000-b58d8000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:04:08.742  6279  6279 W art     : b58d8000-b58da000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:04:08.742  6279  6279 W art     : b58da000-b58db000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:04:08.742  6279  6279 W art     : b58dc000-b58df000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 17:04:08.742  6279  6279 W art     : b58df000-b58e0000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 17:04:08.742  6279  6279 W art     : b58e0000-b58e1000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 17:04:08.742  6279  6279 W art     : b58e1000-b58e5000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:04:08.742  6279  6279 W art     : b58e5000-b58e6000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b58e6000-b58e7000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:04:08.742  6279  6279 W art     : b58e7000-b58e8000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:04:08.742  6279  6279 W art     : b58e8000-b58f8000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 17:04:08.742  6279  6279 W art     : b58f8000-b58f9000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 17:04:08.742  6279  6279 W art     : b58f9000-b58fa000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 17:04:08.742  6279  6279 W art     : b58fa000-b5940000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5940000-b5949000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 17:04:08.742  6279  6279 W art     : b5949000-b594a000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 17:04:08.742  6279  6279 W art     : b594a000-b594b000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 17:04:08.742  6279  6279 W art     : b594c000-b5951000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 17:04:08.742  6279  6279 W art     : b5951000-b5952000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 17:04:08.742  6279  6279 W art     : b5952000-b5953000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 17:04:08.742  6279  6279 W art     : b5953000-b5956000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:04:08.742  6279  6279 W art     : b5956000-b5957000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5957000-b5958000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:04:08.742  6279  6279 W art     : b5958000-b5959000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:04:08.742  6279  6279 W art     : b595a000-b5972000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:04:08.742  6279  6279 W art     : b5972000-b5973000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5973000-b5974000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:04:08.742  6279  6279 W art     : b5974000-b5975000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:04:08.742  6279  6279 W art     : b5976000-b5b10000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:04:08.742  6279  6279 W art     : b5b10000-b5b11000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5b11000-b5b1e000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:04:08.742  6279  6279 W art     : b5b1e000-b5b1f000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:04:08.742  6279  6279 W art     : b5b1f000-b5b23000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 17:04:08.742  6279  6279 W art     : b5b23000-b5b24000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5b24000-b5b25000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 17:04:08.742  6279  6279 W art     : b5b25000-b5b26000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 17:04:08.742  6279  6279 W art     : b5b26000-b5b39000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:04:08.742  6279  6279 W art     : b5b39000-b5b3a000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:04:08.742  6279  6279 W art     : b5b3a000-b5b3b000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:04:08.742  6279  6279 W art     : b5b3b000-b5b3c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:04:08.742  6279  6279 W art     : b5b3c000-b5b87000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:04:08.742  6279  6279 W art     : b5b87000-b5b88000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:04:08.742  6279  6279 W art     : b5b88000-b5b89000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:04:08.742  6279  6279 W art     : b5b89000-b5b8b000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5b8c000-b5b9d000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:04:08.742  6279  6279 W art     : b5b9d000-b5b9e000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5b9e000-b5b9f000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:04:08.762  1814  6386 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 17:04:08.742  6279  6279 W art     : b5b9f000-b5ba0000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:04:08.742  6279  6279 W art     : b5ba1000-b5bab000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:04:08.742  6279  6279 W art     : b5bab000-b5bad000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:04:08.742  6279  6279 W art     : b5bad000-b5bae000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:04:08.742  6279  6279 W art     : b5bae000-b5bc7000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:04:08.742  6279  6279 W art     : b5bc7000-b5bc8000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:04:08.742  6279  6279 W art     : b5bc8000-b5bcb000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:04:08.742  6279  6279 W art     : b5bcb000-b5bcf000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5bcf000-b5c43000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 17:04:08.742  6279  6279 W art     : b5c43000-b5c44000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5c44000-b5c47000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 17:04:08.742  6279  6279 W art     : b5c47000-b5c48000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 17:04:08.742  6279  6279 W art     : b5c48000-b5c49000 r--p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5c49000-b5c4c000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:04:08.742  6279  6279 W art     : b5c4c000-b5c4d000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:04:08.742  6279  6279 W art     : b5c4d000-b5c4e000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:04:08.742  6279  6279 W art     : b5c4e000-b5c4f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5c4f000-b5c54000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:04:08.742  6279  6279 W art     : b5c54000-b5c55000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:04:08.742  6279  6279 W art     : b5c55000-b5c56000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:04:08.742  6279  6279 W art     : b5c56000-b5c57000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5c57000-b5c5a000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:04:08.742  6279  6279 W art     : b5c5a000-b5c5b000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:04:08.742  6279  6279 W art     : b5c5b000-b5c5c000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:04:08.742  6279  6279 W art     : b5c5c000-b5c5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5c5d000-b5c61000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:04:08.742  6279  6279 W art     : b5c61000-b5c62000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:04:08.742  6279  6279 W art     : b5c62000-b5c63000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:04:08.742  6279  6279 W art     : b5c63000-b5c64000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:04:08.742  6279  6279 W art     : b5c64000-b5c68000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:04:08.742  6279  6279 W art     : b5c68000-b5c69000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:04:08.742  6279  6279 W art     : b5c69000-b5c6a000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:04:08.742  6279  6279 W art     : b5c6a000-b5c6b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5c6b000-b5c79000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 17:04:08.742  6279  6279 W art     : b5c79000-b5c7a000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b5c7a000-b5c7b000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 17:04:08.742  6279  6279 W art     : b5c7b000-b5c7c000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 17:04:08.742  6279  6279 W art     : b5c7c000-b5c86000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:04:08.742  6279  6279 W art     : b5c86000-b5c89000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:04:08.742  6279  6279 W art     : b5c89000-b5c8a000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:04:08.742  6279  6279 W art     : b5c8a000-b5c8b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5c8b000-b5c95000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 17:04:08.742  6279  6279 W art     : b5c95000-b5c98000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 17:04:08.742  6279  6279 W art     : b5c98000-b5c99000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 17:04:08.742  6279  6279 W art     : b5c99000-b5c9d000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:04:08.742  6279  6279 W art     : b5c9d000-b5c9e000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:04:08.742  6279  6279 W art     : b5c9e000-b5c9f000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:04:08.742  6279  6279 W art     : b5c9f000-b5ca0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b5ca0000-b5cad000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:04:08.742  6279  6279 W art     : b5cad000-b5caf000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:04:08.742  6279  6279 W art     : b5caf000-b5cb0000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:04:08.742  6279  6279 W art     : b5cb0000-b60c2000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 17:04:08.742  6279  6279 W art     : b60c2000-b60c3000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b60c3000-b60cc000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 17:04:08.742  6279  6279 W art     : b60cc000-b60d0000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 17:04:08.742  6279  6279 W art     : b60d0000-b60d1000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b60d1000-b60d8000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:04:08.742  6279  6279 W art     : b60d8000-b60d9000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:04:08.742  6279  6279 W art     : b60d9000-b60da000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:04:08.742  6279  6279 W art     : b60da000-b60db000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b60db000-b60f6000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 17:04:08.742  6279  6279 W art     : b60f6000-b60f7000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 17:04:08.742  6279  6279 W art     : b60f7000-b60f8000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 17:04:08.742  6279  6279 W art     : b60f8000-b60f9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b60f9000-b6145000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:04:08.742  6279  6279 W art     : b6145000-b6146000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b6146000-b6147000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:04:08.742  6279  6279 W art     : b6147000-b6148000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:04:08.742  6279  6279 W art     : b6148000-b6149000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b6149000-b614d000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:04:08.742  6279  6279 W art     : b614d000-b614e000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b614e000-b614f000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:04:08.742  6279  6279 W art     : b614f000-b6150000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:04:08.742  6279  6279 W art     : b6150000-b6188000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:04:08.742  6279  6279 W art     : b6188000-b6189000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:04:08.742  6279  6279 W art     : b6189000-b618a000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:04:08.742  6279  6279 W art     : b618a000-b618b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.742  6279  6279 W art     : b618b000-b6229000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 17:04:08.742  6279  6279 W art     : b6229000-b622a000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b622a000-b6248000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 17:04:08.742  6279  6279 W art     : b6248000-b6249000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 17:04:08.742  6279  6279 W art     : b6249000-b63bc000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:04:08.742  6279  6279 W art     : b63bc000-b63c7000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:04:08.742  6279  6279 W art     : b63c7000-b63c8000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:04:08.742  6279  6279 W art     : b63c8000-b64df000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:04:08.742  6279  6279 W art     : b64df000-b64ea000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:04:08.742  6279  6279 W art     : b64ea000-b64eb000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:04:08.742  6279  6279 W art     : b64eb000-b64ef000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b64ef000-b6513000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 17:04:08.742  6279  6279 W art     : b6513000-b6515000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 17:04:08.742  6279  6279 W art     : b6515000-b6516000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 17:04:08.742  6279  6279 W art     : b6516000-b65bc000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 17:04:08.742  6279  6279 W art     : b65bc000-b65c9000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 17:04:08.742  6279  6279 W art     : b65c9000-b65ca000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 17:04:08.742  6279  6279 W art     : b65ca000-b65cb000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b65cb000-b661e000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:04:08.742  6279  6279 W art     : b661e000-b661f000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b661f000-b6620000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:04:08.742  6279  6279 W art     : b6620000-b6621000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:04:08.742  6279  6279 W art     : b6621000-b6626000 rw-p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b6626000-b6638000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 17:04:08.742  6279  6279 W art     : b6638000-b6639000 ---p 00000000 00:00 0 
08-23 17:04:08.742  6279  6279 W art     : b6639000-b663a000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 17:04:08.742  6279  6279 W art     : b663a000-b663b000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 17:04:08.752  6279  6279 W art     : b663b000-b6642000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:04:08.752  6279  6279 W art     : b6642000-b6643000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:04:08.752  6279  6279 W art     : b6643000-b6644000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:04:08.752  6279  6279 W art     : b6644000-b6645000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6645000-b6648000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 17:04:08.752  6279  6279 W art     : b6648000-b6649000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 17:04:08.752  6279  6279 W art     : b6649000-b664a000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 17:04:08.752  6279  6279 W art     : b664a000-b664e000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 17:04:08.752  6279  6279 W art     : b664e000-b664f000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 17:04:08.752  6279  6279 W art     : b664f000-b6650000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 17:04:08.752  6279  6279 W art     : b6650000-b665e000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:04:08.752  6279  6279 W art     : b665e000-b665f000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b665f000-b6660000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:04:08.752  6279  6279 W art     : b6660000-b6661000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:04:08.752  6279  6279 W art     : b6661000-b666a000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:04:08.752  6279  6279 W art     : b666a000-b666b000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:04:08.752  6279  6279 W art     : b666b000-b666c000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:04:08.752  6279  6279 W art     : b666c000-b66d2000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 17:04:08.752  6279  6279 W art     : b66d2000-b66d3000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b66d3000-b66d5000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 17:04:08.752  6279  6279 W art     : b66d5000-b66de000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 17:04:08.752  6279  6279 W art     : b66de000-b66e1000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b66e1000-b6778000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 17:04:08.752  6279  6279 W art     : b6778000-b677a000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 17:04:08.752  6279  6279 W art     : b677a000-b677b000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 17:04:08.752  6279  6279 W art     : b677b000-b677c000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b677c000-b6a9d000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 17:04:08.752  6279  6279 W art     : b6a9d000-b6a9e000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6a9e000-b6ab9000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 17:04:08.752  6279  6279 W art     : b6ab9000-b6abd000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 17:04:08.752  6279  6279 W art     : b6abd000-b6ac2000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6ac2000-b6aca000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 17:04:08.752  6279  6279 W art     : b6aca000-b6acb000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 17:04:08.752  6279  6279 W art     : b6acb000-b6acc000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_met,adata.so
08-23 17:04:08.752  6279  6279 W art     : b6acc000-b6afa000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:04:08.752  6279  6279 W art     : b6afa000-b6afb000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6afb000-b6b02000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:04:08.752  6279  6279 W art     : b6b02000-b6b03000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:04:08.752  6279  6279 W art     : b6b03000-b6b49000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:04:08.752  6279  6279 W art     : b6b49000-b6b4a000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6b4a000-b6b4d000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:04:08.752  6279  6279 W art     : b6b4d000-b6b4e000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:04:08.752  6279  6279 W art     : b6b4e000-b6b69000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 17:04:08.752  6279  6279 W art     : b6b69000-b6b6d000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 17:04:08.752  6279  6279 W art     : b6b6d000-b6b6e000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 17:04:08.752  6279  6279 W art     : b6b6e000-b6bbb000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 17:04:08.752  6279  6279 W art     : b6bbb000-b6bbc000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6bbc000-b6bc8000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 17:04:08.752  6279  6279 W art     : b6bc8000-b6bc9000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 17:04:08.752  6279  6279 W art     : b6bc9000-b6bd6000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 17:04:08.752  6279  6279 W art     : b6bd6000-b6bd7000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6bd7000-b6bd8000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 17:04:08.752  6279  6279 W art     : b6bd8000-b6bd9000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 17:04:08.752  6279  6279 W art     : b6bd9000-b6be1000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:04:08.752  6279  6279 W art     : b6be1000-b6be2000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6be2000-b6be3000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:04:08.752  6279  6279 W art     : b6be3000-b6be4000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:04:08.752  6279  6279 W art     : b6be4000-b6beb000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:04:08.752  6279  6279 W art     : b6beb000-b6bec000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:04:08.752  6279  6279 W art     : b6bec000-b6bed000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:04:08.752  6279  6279 W art     : b6bed000-b6c01000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 17:04:08.752  6279  6279 W art     : b6c01000-b6c03000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 17:04:08.752  6279  6279 W art     : b6c03000-b6c04000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 17:04:08.752  6279  6279 W art     : b6c04000-b6c2c000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:04:08.752  6279  6279 W art     : b6c2c000-b6c2e000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:04:08.752  6279  6279 W art     : b6c2e000-b6c2f000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:04:08.752  6279  6279 W art     : b6c2f000-b6c32000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:04:08.752  6279  6279 W art     : b6c32000-b6c33000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:04:08.752  6279  6279 W art     : b6c33000-b6c34000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:04:08.752  6279  6279 W art     : b6c34000-b6c3d000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:04:08.752  6279  6279 W art     : b6c3d000-b6c3e000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:04:08.752  6279  6279 W art     : b6c3e000-b6c3f000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:04:08.752  6279  6279 W art     : b6c3f000-b6c5f000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 17:04:08.752  6279  6279 W art     : b6c5f000-b6c60000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 17:04:08.752  6279  6279 W art     : b6c60000-b6c61000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 17:04:08.752  6279  6279 W art     : b6c61000-b6cd4000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 17:04:08.752  6279  6279 W art     : b6cd4000-b6cd8000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 17:04:08.752  6279  6279 W art     : b6cd8000-b6cdb000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 17:04:08.752  6279  6279 W art     : b6cdb000-b6ce5000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6ce5000-b6d6d000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 17:04:08.752  6279  6279 W art     : b6d6d000-b6d6e000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6d6e000-b6d72000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 17:04:08.752  6279  6279 W art     : b6d72000-b6d73000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 17:04:08.752  6279  6279 W art     : b6d73000-b6d74000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6d74000-b6d9d000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:04:08.752  6279  6279 W art     : b6d9d000-b6d9e000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6d9e000-b6da1000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:04:08.752  6279  6279 W art     : b6da1000-b6da2000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:04:08.752  6279  6279 W art     : b6da2000-b6e7c000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:04:08.752  6279  6279 W art     : b6e7c000-b6e83000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:04:08.752  6279  6279 W art     : b6e83000-b6e8b000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:04:08.752  6279  6279 W art     : b6e8b000-b6e8c000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6e8c000-b6e8d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:04:08.752  6279  6279 W art     : b6e8d000-b6e8e000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 17:04:08.752  6279  6279 W art     : b6e8e000-b6e8f000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6e8f000-b6e92000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6e92000-b6eb7000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 17:04:08.752  6279  6279 W art     : b6eb7000-b6eb8000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6eb8000-b6ebf000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 17:04:08.752  6279  6279 W art     : b6ebf000-b6ec0000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 17:04:08.752  6279  6279 W art     : b6ec0000-b6ec7000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 17:04:08.752  6279  6279 W art     : b6ec7000-b6ec8000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 17:04:08.752  6279  6279 W art     : b6ec8000-b6ec9000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 17:04:08.752  6279  6279 W art     : b6ec9000-b6eca000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6eca000-b6ee2000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ee2000-b6ee3000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6ee3000-b6ee4000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ee4000-b6ee5000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ee5000-b6ef3000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ef3000-b6ef4000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6ef4000-b6ef5000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ef5000-b6ef6000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 17:04:08.752  6279  6279 W art     : b6ef6000-b6ef7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:04:08.752  6279  6279 W art     : b6ef7000-b6ef9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6ef9000-b6efa000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6efa000-b6efb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:04:08.752  6279  6279 W art     : b6efb000-b6efc000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 17:04:08.752  6279  6279 W art     : b6efc000-b6efd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:04:08.752  6279  6279 W art     : b6efd000-b6f1d000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 17:04:08.752  6279  6279 W art     : b6f1d000-b6f1e000 r--p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6f1e000-b6f1f000 ---p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6f1f000-b6f21000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 17:04:08.752  6279  6279 W art     : b6f21000-b6f22000 r-xp 00000000 00:00 0          [sigpage]
08-23 17:04:08.752  6279  6279 W art     : b6f22000-b6f3d000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 17:04:08.752  6279  6279 W art     : b6f3d000-b6f3e000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 17:04:08.752  6279  6279 W art     : b6f3e000-b6f40000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 17:04:08.752  6279  6279 W art     : b6f40000-b6f42000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : b6f42000-b6f47000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 17:04:08.752  6279  6279 W art     : b6f47000-b6f48000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 17:04:08.752  6279  6279 W art     : b6f48000-b6f49000 rw-p 00000000 00:00 0 
08-23 17:04:08.752  6279  6279 W art     : befd0000-beff1000 rw-p 00000000 00:00 0          [stack]
08-23 17:04:08.752  6279  6279 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 17:04:08.792  6388  6388 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:08.792  6388  6388 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:08.792  6279  6279 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 17:04:08.802  1814  6386 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 17:04:08.802   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{70ed67a 6388:com.samsung.android.sm.devicesecurity/5012}
08-23 17:04:08.812  6388  6388 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-23 17:04:08.832  6388  6388 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-23 17:04:08.842   751   764 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-23 17:04:08.852  6279  6279 I Radio-JNI: register_android_hardware_Radio DONE
08-23 17:04:08.862  6279  6279 E AffinityControl: AffinityControl: registerfunction enter
08-23 17:04:08.882  6279  6279 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 17:04:08.892  4200  6405 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-23 17:04:08.902   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f96c056 3189:com.android.contacts/u0a19}
08-23 17:04:08.922   751  1623 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 17:04:08.932   751  1623 D ActivityManager: mDVFSHelper.acquire()
08-23 17:04:08.942   751  1623 V WindowManager: addAppToken: AppWindowToken{608b21e token=Token{5157659 ActivityRecord{5e40aa0 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-23 17:04:08.942   751   891 D SecWifiDisplayUtil: Metadata value : none
08-23 17:04:08.942   751   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d4ae6f6 V.E...... R.....ID 0,0-0,0}
08-23 17:04:08.952   751   891 D ISSUE_DEBUG: InputChannelName : a30cd64 Starting com.test.thalitest
08-23 17:04:08.952  6409  6409 E Zygote  : v2
08-23 17:04:08.952  6409  6409 I libpersona: KNOX_SDCARD checking this for 10004
08-23 17:04:08.952  6409  6409 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.952   751  1623 I ActivityManager: Start proc 6409:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 17:04:08.952  6409  6409 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.952  6409  6409 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.952  6409  6409 E Zygote  : accessInfo : 0
08-23 17:04:08.952  6409  6409 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 17:04:08.952   751  1623 D InputDispatcher: Focused application set to: xxxx
08-23 17:04:08.962   751  1623 D InputDispatcher: Focus left window: 4535
08-23 17:04:08.962  6279  6279 D AndroidRuntime: Shutting down VM
08-23 17:04:08.962   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-23 17:04:08.972   751  2070 I ActivityManager: Start proc 6420:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-23 17:04:08.972  6420  6420 E Zygote  : v2
08-23 17:04:08.972  6420  6420 I libpersona: KNOX_SDCARD checking this for 10049
08-23 17:04:08.972  6420  6420 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:08.972  6420  6420 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:08.972  6420  6420 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:08.982  6420  6420 E Zygote  : accessInfo : 0
08-23 17:04:08.982  6420  6420 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-23 17:04:08.982   751   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-23 17:04:08.982   751   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:08.982   751   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-23 17:04:08.982   751   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 17:04:08.982   751   891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 17:04:08.982   751   838 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6957b51 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 17:04:08.992  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-23 17:04:09.002   751   891 V WindowStateAnimator: Finishing drawing window Window{a30cd64 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 17:04:09.012  6409  6409 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:09.022  6409  6409 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:09.022  6420  6420 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:09.022  6420  6420 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:09.022   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebde364
08-23 17:04:09.032   751   765 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 17:04:09.032   751   765 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 17:04:09.062   751   765 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 17:04:09.082  1714  1844 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 17:04:09.082  1714  1714 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 17:04:09.082   294  1502 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-23 17:04:09.082   294   365 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-23 17:04:09.092  4535  4535 V ActivityThread: updateVisibility : ActivityRecord{ece7a43 token=android.os.BinderProxy@d6f34b6 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 17:04:09.092   294   348 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-23 17:04:09.092   294   348 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-23 17:04:09.102   294  1502 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-23 17:04:09.102   294   365 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-23 17:04:09.102  2186  2199 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 17:04:09.102  1714  1714 V ActivityThread: updateVisibility : ActivityRecord{a3c66b4 token=android.os.BinderProxy@7438776 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 17:04:09.102  1714  1714 D Launcher: onTrimMemory. Level: 20
08-23 17:04:09.102   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebde3a4
,08-23 17:04:09.212  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 17:04:09.212   751  3780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf3a7c9 6420:com.android.mms/u0a49}
,08-23 17:04:09.212   751   835 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-23 17:04:09.222   751  3426 D M       : limitCPUFreq:: freq = -1
08-23 17:04:09.222   751  3426 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  tag : SIOP_ARM_MAX@25
,08-23 17:04:09.222   751  3426 D M       : limitGPUFreq:: freq = -1
,08-23 17:04:09.222   751   838 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a30cd64 u0 d0 Starting com.test.thalitest}
,08-23 17:04:09.222  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
,08-23 17:04:09.242   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:04:09.252  6420  6420 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 17:04:09.272  6420  6420 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-23 17:04:09.272  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 17:04:09.272  6420  6420 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-23 17:04:09.272  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 17:04:09.282  1814  6386 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 618 ms] updated apps [took 618 ms] 
,08-23 17:04:09.302  6409  6409 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-23 17:04:09.322  6420  6420 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-23 17:04:09.322  6420  6435 D Mms/ArtClassLoader: init before art third
,08-23 17:04:09.332  6420  6434 D Mms/ArtClassLoader: init before art second
,08-23 17:04:09.332  6420  6433 D Mms/ArtClassLoader: init before art first
,08-23 17:04:09.332  6409  6409 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 17:04:09.332  6420  6420 D Mms/TelephonyPermission: start operation mode monitor
,08-23 17:04:09.332  6420  6420 D Mms/TelephonyPermission: User ID is null set current User Id
,08-23 17:04:09.332  6409  6409 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 17:04:09.352  6420  6420 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 17:04:09.352  6409  6409 I cr_LibraryLoader: Time to load native libraries: 10 ms (timestamps 5573-5583)
,08-23 17:04:09.352  6409  6409 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 17:04:09.352  6420  6435 D Mms/ArtClassLoader: init [DONE] art
,08-23 17:04:09.352  6420  6420 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 17:04:09.372  6420  6420 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,08-23 17:04:09.372  6420  6420 D Mms/TelephonyPermission: isDefault true
,08-23 17:04:09.372  6420  6420 D Mms/MmsApp: onCreate() com.android.mms
,08-23 17:04:09.372  6409  6409 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f4b3886}
08-23 17:04:09.372  6409  6409 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 17:04:09.382  6409  6409 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 17:04:09.382  6409  6409 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 17:04:09.382   751   761 I art     : Background partial concurrent mark sweep GC freed 142238(8MB) AllocSpace objects, 10(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.837ms total 185.936ms
,08-23 17:04:09.392  6409  6438 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-23 17:04:09.412  6409  6409 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 17:04:09.412  6409  6409 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 17:04:09.412  6409  6409 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 17:04:09.412  6409  6409 I Adreno-EGL: Local Branch: ss
08-23 17:04:09.412  6409  6409 I Adreno-EGL: Remote Branch: 
08-23 17:04:09.412  6409  6409 I Adreno-EGL: Local Patches: 
08-23 17:04:09.412  6409  6409 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:04:09.422  6409  6409 D libEGL  : eglInitialize EGLDisplay = 0xbed4edac
,08-23 17:04:09.422  6420  6420 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-23 17:04:09.432  6420  6420 D Mms/MmsApp: [start]    initCountryIso consume time = 111.465937
,08-23 17:04:09.452   751  1791 D CountryDetector: The first listener is added
08-23 17:04:09.452   751  1490 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-23 17:04:09.452   751  1490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-23 17:04:09.452  6420  6420 D Mms/MmsApp: [end]    initCountryIso consume time = 25.282135
08-23 17:04:09.452  6420  6420 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.108177
,08-23 17:04:09.492  6420  6420 D Mms/MmsConfig: before partial update
,08-23 17:04:09.502  6409  6409 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-23 17:04:09.512  6409  6409 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 17:04:09.512  6409  6409 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-23 17:04:09.512  6409  6409 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-23 17:04:09.512  6409  6409 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-23 17:04:09.532  6409  6409 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-23 17:04:09.532  6420  6434 D Mms/ArtClassLoader: init [DONE] art
,08-23 17:04:09.532  6420  6420 D Mms/MmsConfig: Load Resize quality : 80
,08-23 17:04:09.542  6409  6409 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 17:04:09.542  6420  6433 D Mms/ArtClassLoader: init [DONE] art
08-23 17:04:09.542  6420  6420 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 17:04:09.542  6420  6420 D EasySignUpManager_1.0.5: isAuth is false
08-23 17:04:09.542  6420  6420 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-23 17:04:09.542  6420  6420 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-23 17:04:09.542  6420  6420 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-23 17:04:09.542  6420  6420 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 17:04:09.542  6420  6420 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-23 17:04:09.542  6420  6420 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 17:04:09.542  6420  6420 D EasySignUpManager_1.0.5: isAuth is false
08-23 17:04:09.542  6420  6420 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-23 17:04:09.542  6420  6420 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-23 17:04:09.552  1700  1929 D TP/MmsSmsProvider: query, match:2117, calling pid = 6420, accessRestricted = false
,08-23 17:04:09.552  1700  1929 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.104 ms
,08-23 17:04:09.562  6420  6420 E CscParser: mps_code.dat does not exist
08-23 17:04:09.562  6420  6420 E CscParser: customer_path =/system/csc/customer.xml
08-23 17:04:09.572  6420  6420 E CscParser: fileName + /system/csc/customer.xml
08-23 17:04:09.572  6420  6420 E CscParser: mps_code.dat does not exist
08-23 17:04:09.572  6420  6420 E CscParser: customer_path =/system/csc/customer.xml
08-23 17:04:09.572  6420  6420 E CscParser: fileName + /system/csc/customer.xml
08-23 17:04:09.582  6420  6420 D CscParser: getInstance fileName =/system/csc/customer.xml
08-23 17:04:09.582  6420  6420 D Mms/MmsConfig:  enable multiwindow = true
08-23 17:04:09.582  6420  6420 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-23 17:04:09.582  6420  6420 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-23 17:04:09.582  6420  6420 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-23 17:04:09.582  6420  6420 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-23 17:04:09.582  6420  6420 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-23 17:04:09.582  6420  6420 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 17:04:09.582  6420  6420 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-23 17:04:09.592  6420  6420 D Mms/MmsConfig: [end]    init() consume time = 132.563022
08-23 17:04:09.592  6420  6420 D Mms/Contact: [start]    init() consume time = 6.581405
08-23 17:04:09.602  1700  1713 D TP/MmsSmsProvider: query, match:13, calling pid = 6420, accessRestricted = false
08-23 17:04:09.602  1700  1713 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.669 ms
08-23 17:04:09.622  6420  6420 D Mms/Contact: [end]    init consume time = 24.271043
08-23 17:04:09.622  6420  6468 D Mms/DraftCache: [start]    rebuildCache consume time = 5.600624
08-23 17:04:09.642  6409  6409 D SecWifiDisplayUtil: Metadata value : none
08-23 17:04:09.642  1700  2092 D TP/MmsSmsProvider: query, match:12, calling pid = 6420, accessRestricted = false
08-23 17:04:09.642  6409  6409 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{89429d4 I.E...... R.....ID 0,0-0,0}
08-23 17:04:09.642  1700  2092 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.150 ms
08-23 17:04:09.652  6420  6468 D Mms/DraftCache: [end]    rebuildCache consume time = 23.990834
08-23 17:04:09.652  6409  6469 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 17:04:09.652  6420  6420 D Mms:transaction: roaming -> false (slotId = 0)
08-23 17:04:09.652  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 17:04:09.652  6420  6420 D Mms:transaction: auto download without roaming -> true
08-23 17:04:09.652  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 17:04:09.652  6420  6420 D Mms:transaction: roaming -> false (slotId = 1)
08-23 17:04:09.652  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 17:04:09.652  6420  6420 D Mms:transaction: auto download without roaming -> true
08-23 17:04:09.652  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 17:04:09.652   751  3780 D ISSUE_DEBUG: InputChannelName : ee99c65 com.test.thalitest/com.test.thalitest.MainActivity
08-23 17:04:09.652  6420  6420 D Mms:transaction: auto download during roaming secondary -> false
08-23 17:04:09.652  6420  6420 D Mms:transaction: mAutoDownload ------> true
08-23 17:04:09.662   751  2440 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-23 17:04:09.662   751  2440 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 17:04:09.662   751   751 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 17:04:09.662   751   751 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 17:04:09.682  6409  6409 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6409
08-23 17:04:09.682   751   764 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6409 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 17:04:09.682   751  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-23 17:04:09.682   751  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 17:04:09.682   751  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-23 17:04:09.682   751  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 17:04:09.702  6409  6409 D SecWifiDisplayUtil: Metadata value : none
08-23 17:04:09.702  6409  6438 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-23 17:04:09.712   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
08-23 17:04:09.712  6420  6420 D ComposerPerformance: 1471964649722 ms / [DONE] Composer constructor
08-23 17:04:09.722  6420  6420 D CII     : Log Level [5]
08-23 17:04:09.722  6420  6420 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-23 17:04:09.722   751  1726 D InputDispatcher: Focus entered window: 6409
08-23 17:04:09.722  6420  6472 D Mms/Conversation: [start]    init() consume time = 71.658385
08-23 17:04:09.722  1700  1713 D TP/MmsSmsProvider: delete, match:1, calling pid = 6420
08-23 17:04:09.722  1700  1713 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 17:04:09.722  1700  1713 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-23 17:04:09.722   751   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-23 17:04:09.722   751   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:09.722   751   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-23 17:04:09.722   751   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 17:04:09.722  6409  6469 D libEGL  : eglInitialize EGLDisplay = 0x9caf97c4
08-23 17:04:09.722  6409  6469 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 17:04:09.732  1700  1713 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-23 17:04:09.732  1700  1713 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 17:04:09.732  1700  1713 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-23 17:04:09.732  1700  1713 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-23 17:04:09.742  6420  6420 I Mms/ReservationManager: ReservationManager()
08-23 17:04:09.742  6420  6420 I Mms/ReservationManager: resetAfterConnected()
08-23 17:04:09.742  1700  1713 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-23 17:04:09.742  1700  1713 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-23 17:04:09.742  1700  1713 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 17:04:09.742  1700  1713 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 21.421 ms
08-23 17:04:09.742  1700  1713 D TP/MmsSmsProvider: need read changed broadcast:false
08-23 17:04:09.742  6420  6472 D Mms/Conversation: [end]    init consume time = 24.098542
08-23 17:04:09.752  1700  1712 D TP/MmsSmsProvider: query, match:7, calling pid = 6420, accessRestricted = false
08-23 17:04:09.752  1700  1712 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.523 ms
08-23 17:04:09.762  6420  6420 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-23 17:04:09.762  6420  6420 D Mms/MmsApp: [end]    onCreate() consume time = 10.913646
08-23 17:04:09.762  6420  6420 D Mms/MmsApp: [end]    onCreate() consume time = 0.24599
08-23 17:04:09.762  6420  6472 D Mms/MessagingNotification: [start]    init() consume time = 6.196614
08-23 17:04:09.762  6420  6420 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
08-23 17:04:09.762  6420  6420 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-23 17:04:09.762  6420  6420 D Mms:transaction: roaming -> false (slotId = 0)
08-23 17:04:09.762  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 17:04:09.762  6420  6420 D Mms:transaction: auto download without roaming -> true
08-23 17:04:09.762  6420  6420 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 17:04:09.762  6420  6420 D Mms:transaction: mAutoDownload ------> true
08-23 17:04:09.772  6475  6475 E Zygote  : v2
08-23 17:04:09.772  6475  6475 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:09.772  6475  6475 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:09.772  6475  6475 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:09.772  6475  6475 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:09.772  6475  6475 E Zygote  : accessInfo : 0
08-23 17:04:09.772   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 17:04:09.782   751   765 I ActivityManager: Start proc 6475:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-23 17:04:09.782   751   765 I ActivityManager: Killing 5166:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-23 17:04:09.812  6409  6409 V ActivityThread: updateVisibility : ActivityRecord{805f01f token=android.os.BinderProxy@385c327 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 17:04:09.812  6420  6472 D Mms/MessagingNotification: [end]    init consume time = 50.144739
08-23 17:04:09.822  6475  6475 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:09.822  6409  6409 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 17:04:09.822  6475  6475 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:09.822  6409  6409 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-23 17:04:09.822   751   764 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-23 17:04:09.832  6420  6488 D Mms/Synchronizer: [start]    doSync consume time = 16.513907
08-23 17:04:09.832  6420  6487 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.734323
08-23 17:04:09.842   751  1663 V WindowStateAnimator: Finishing drawing window Window{ee99c65 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-23 17:04:09.842  1700  1929 D TP/MmsSmsProvider: query, match:0, calling pid = 6420, accessRestricted = false
08-23 17:04:09.842  1700  1929 V TP/MmsSmsProvider: getSimpleConversations entered.
08-23 17:04:09.842  1700  1929 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.224 ms
08-23 17:04:09.842  6409  6409 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 17:04:09.842   751  1490 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 17:04:09.842   751  1424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44cacde 6475:com.samsung.android.bbc.bbcagent/1000}
08-23 17:04:09.842   751   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 17:04:09.842   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 17:04:09.842   751   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +646ms (total +908ms)
08-23 17:04:09.852   751   751 I KnoxTimeoutHandler: SD activityfalse
08-23 17:04:09.852   751   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5e40aa0 u0 com.test.thalitest/.MainActivity t168} time:106081
08-23 17:04:09.852   751   891 D ActivityManager: mDVFSHelper.release()
08-23 17:04:09.852   751   891 D ViewRootImpl: #3 mView = null
08-23 17:04:09.852   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebde364
08-23 17:04:09.852   294   365 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
08-23 17:04:09.852  6409  6409 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 17:04:09.862   294  2022 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
08-23 17:04:09.872   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebde3a4
08-23 17:04:09.872  6409  6409 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@385c327 time:106107
08-23 17:04:09.872  1700  1929 D TP/MmsSmsProvider: query, match:400, calling pid = 6420, accessRestricted = false
08-23 17:04:09.882  6475  6475 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
08-23 17:04:09.882  6420  6487 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 50.338906
08-23 17:04:09.882  1700  1713 D TP/MmsSmsProvider: update, match:300, calling pid = 6420
08-23 17:04:09.882  1700  1713 V TP/MmsSmsProvider: syncDBData start
08-23 17:04:09.882  1700  1713 V TP/MmsSmsProvider: syncDBData sms end
08-23 17:04:09.882  1700  1713 V TP/MmsSmsProvider: syncDBData mms end
08-23 17:04:09.882  1700  1713 V TP/MmsSmsProvider: syncDBData end
08-23 17:04:09.882  1700  1713 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.155 ms
08-23 17:04:09.882  6038  6048 D BadgeProvider: query, [selection] : package=?
08-23 17:04:09.892  6420  6488 D Mms/Synchronizer: [end]    doSync consume time = 9.961771
08-23 17:04:09.892  6420  6472 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-23 17:04:09.902  6409  6492 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 17:04:09.902  6409  6492 D libEGL  : eglInitialize EGLDisplay = 0x9b5ac3ec
08-23 17:04:09.902  1700  1712 D TP/SmsProvider: query,matched:26, calling pid = 6420
08-23 17:04:09.902  1700  1712 D TP/SmsProvider: query, match 26:Elapsed time : 1.270 ms
08-23 17:04:09.922  1700  2092 D TP/MmsSmsProvider: query, match:6, calling pid = 6420, accessRestricted = false
08-23 17:04:09.922  1700  2092 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.781 ms
08-23 17:04:09.922  6475  6475 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
08-23 17:04:09.952   751  1320 I ActivityManager: Start proc 6495:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-23 17:04:09.952  6495  6495 E Zygote  : v2
08-23 17:04:09.952  6495  6495 I libpersona: KNOX_SDCARD checking this for 10024
08-23 17:04:09.952  6495  6495 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:09.952  6495  6495 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:09.952  6495  6495 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:09.952  6495  6495 E Zygote  : accessInfo : 0
08-23 17:04:09.952  6495  6495 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-23 17:04:09.952  6409  6409 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6409
08-23 17:04:09.972  6495  6495 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:09.972  6495  6495 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:09.982   751  1663 I ActivityManager: Killing 5142:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-23 17:04:10.002  6495  6495 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
08-23 17:04:10.012   751  2440 I ActivityManager: Start proc 6508:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-23 17:04:10.012  6508  6508 E Zygote  : v2
08-23 17:04:10.012  6508  6508 I libpersona: KNOX_SDCARD checking this for 10097
08-23 17:04:10.012  6508  6508 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:10.012  6508  6508 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:10.012  6508  6508 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:10.012  6508  6508 E Zygote  : accessInfo : 0
08-23 17:04:10.012  6508  6508 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-23 17:04:10.012   751  1323 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 17:04:10.012   751  1632 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-23 17:04:10.012   751  1632 I ActivityManager: Killing 5201:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
08-23 17:04:10.022   751  1323 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:04:10.042  6495  6495 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
08-23 17:04:10.042   751  2070 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
08-23 17:04:10.052  6508  6508 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:10.052  6508  6508 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:10.062   751  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c8898c 6508:com.google.android.apps.docs/u0a97}
08-23 17:04:10.062  6508  6508 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-23 17:04:10.092  6508  6508 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
08-23 17:04:10.092  6495  6495 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
08-23 17:04:10.102  6420  6472 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-23 17:04:10.122  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-23 17:04:10.132  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-23 17:04:10.132  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-23 17:04:10.132  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-23 17:04:10.132  6495  6495 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-23 17:04:10.152  6409  6409 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 17:04:10.222   751  3430 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 17:04:10.262  6409  6522 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1695811280
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 17:04:10.262  6409  6522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9759ed added. We now have 1 listener(s)
08-23 17:04:10.272  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
08-23 17:04:10.272  6409  6522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
08-23 17:04:10.272  6409  6522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 17:04:10.272  6409  6522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 17:04:10.272  4200  5069 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 17:04:10.272  6409  6522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c9c870 added. We now have 1 listener(s)
08-23 17:04:10.272  6409  6522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 17:04:10.272  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 17:04:10.272  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 17:04:10.282  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 17:04:10.282  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 17:04:10.282  6409  6522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 17:04:10.282  6409  6522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 17:04:10.282  6409  6522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
08-23 17:04:10.292  6409  6522 D BluetoothAdapter: STATE_ON
08-23 17:04:10.292  6409  6522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:10.292  6409  6522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 17:04:10.292  6409  6522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 17:04:10.292  6409  6522 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 17:04:10.292  6409  6522 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 17:04:10.302  6409  6409 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 17:04:10.302  6409  6409 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 17:04:10.322  6409  6409 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-23 17:04:10.352  4200  5069 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-23 17:04:10.492  6508  6526 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-23 17:04:10.492  6508  6526 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 17:04:10.492  6508  6526 I GAv4    :   adb logcat -s GAv4
08-23 17:04:10.512  4200  5069 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
08-23 17:04:10.522  6508  6526 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-23 17:04:10.522   751  1663 V AlarmManager:  remove PendingIntent] PendingIntent{cfd7b42: PendingIntentRecord{a87c753 com.google.android.apps.docs broadcastIntent}}
08-23 17:04:10.522  6508  6526 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-23 17:04:10.532  6508  6526 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-23 17:04:10.542   751  1237 V AlarmManager: Expired Alarm result :4
08-23 17:04:10.552  6508  6532 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-23 17:04:10.552  4902  4950 I Finsky  : [685] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
08-23 17:04:10.552   751   751 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
08-23 17:04:10.552   751   751 V AlarmManagerEXT: <AppSync3 Whitelist>
08-23 17:04:10.552   751   751 V AlarmManagerEXT: (AppSync) ### 0 added ###
08-23 17:04:10.562  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-23 17:04:10.562  1382  1382 I PERF    : received broadcast android.intent.action.TIME_TICK
08-23 17:04:10.562  1382  1382 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 17:04:10.572  1382  1382 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-23 17:04:10.572  1382  1382 D SecKeyguardClockView: HomeTimezone(): 1
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.582  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.592  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 17:04:10.592   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:04:10.592   751  1490 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4240, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 17:04:10.592   751  1490 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-23 17:04:10.592   751  1490 D BatteryService: stay LED for charging
08-23 17:04:10.592   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:04:10.592   751   751 I MotionRecognitionService: Plugged
08-23 17:04:10.592   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:04:10.592   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:04:10.592   751   751 D MotionRecognitionService: skip setTransmitPower. 
08-23 17:04:10.622  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:04:10.622  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:04:10.622  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:04:10.632  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 17:04:10.632  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 17:04:10.632  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 17:04:10.632  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:04:10.632  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:04:10.672  1452  1452 D Recents : onTaskStackChanged
,08-23 17:04:10.692  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 17:04:10.692  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:04:10.722   751  6184 I HarmonyEASService: Updating for all 1
,08-23 17:04:10.742  6508  6508 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-23 17:04:10.742  6508  6508 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-23 17:04:10.802  6508  6526 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-23 17:04:10.802  6508  6526 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-23 17:04:10.802  6508  6526 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-23 17:04:10.802  6508  6526 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-23 17:04:10.822  6539  6539 E Zygote  : v2
08-23 17:04:10.822  6539  6539 I libpersona: KNOX_SDCARD checking this for 10098
08-23 17:04:10.822  6539  6539 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:10.832  6539  6539 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:10.832  6539  6539 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:10.832  6539  6539 E Zygote  : accessInfo : 0
08-23 17:04:10.832  6539  6539 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-23 17:04:10.842   751  3780 I ActivityManager: Start proc 6539:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-23 17:04:10.862  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:10.862  6539  6539 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:10.862   751  1632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e23309a 6539:com.sec.android.automotive.drivelink/u0a98}
,08-23 17:04:10.872  6539  6539 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 17:04:10.892  6539  6539 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-23 17:04:10.952  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:10.952  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:10.952  6539  6539 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 17:04:10.972   751  2070 V AlarmManager:  remove PendingIntent] PendingIntent{b73bc66: PendingIntentRecord{927ba7 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 17:04:10.972  6539  6555 I GMPM    : App measurement is starting up
,08-23 17:04:10.982  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:10.982  6539  6539 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-23 17:04:10.992  6539  6555 E GMPM    : getGoogleAppId failed with status: 10
,08-23 17:04:10.992  6539  6555 E GMPM    : Uploading is not possible. App measurement disabled
,08-23 17:04:10.992   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{46005c0: PendingIntentRecord{927ba7 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 17:04:11.012  6539  6539 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-23 17:04:11.022  6539  6539 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-23 17:04:11.062  4902  4950 I Finsky  : [685] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-23 17:04:11.062  4902  4902 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-23 17:04:11.062   751  1490 I ActivityManager: Killing 5559:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-23 17:04:11.072  6508  6527 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 17:04:11.082   751  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-23 17:04:11.112  6561  6561 E Zygote  : v2
08-23 17:04:11.112  6561  6561 I libpersona: KNOX_SDCARD checking this for 10032
08-23 17:04:11.112  6561  6561 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:11.112  6561  6561 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:11.112  6561  6561 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:11.112   751  2070 I ActivityManager: Start proc 6561:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-23 17:04:11.112   751  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 17:04:11.112  6561  6561 E Zygote  : accessInfo : 0
08-23 17:04:11.112  6561  6561 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-23 17:04:11.132  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:11.132  6561  6561 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.142   751  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 17:04:11.152  6561  6561 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-23 17:04:11.152  6508  6527 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 17:04:11.162  6561  6561 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-23 17:04:11.172  6508  6527 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-23 17:04:11.172  6508  6527 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 17:04:11.172  6508  6527 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 17:04:11.202  6508  6527 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 17:04:11.232  6409  6523 W jxcore-log: Initializing JXcore engine
08-23 17:04:11.232  6409  6523 W jxcore-log: JXcore engine is ready
,08-23 17:04:11.242  6539  6539 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-23 17:04:11.242  6539  6539 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-23 17:04:11.252  6539  6539 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-23 17:04:11.262  6561  6561 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-23 17:04:11.272  6539  6539 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 23 17:04:11 GMT+02:00 2016
,08-23 17:04:11.282  6539  6539 D DialogFlow: initQueue()
,08-23 17:04:11.292  6575  6575 E Zygote  : v2
08-23 17:04:11.292  6575  6575 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:11.292  6575  6575 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:11.292  6575  6575 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:11.292  6575  6575 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:11.292  6575  6575 E Zygote  : accessInfo : 0
08-23 17:04:11.292   751  1632 I ActivityManager: Start proc 6575:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-23 17:04:11.292   751  1632 I ActivityManager: Killing 5497:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-23 17:04:11.292   751  1632 I ActivityManager: Killing 5070:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-23 17:04:11.302  2309  2309 E audit   : type=1400 msg=audit(1471964651.302:287): avc:  denied  { ioctl } for  pid=6523 comm="Thread-891" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 17:04:11.302  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:11.302  2309  2309 E audit   : type=1300 msg=audit(1471964651.302:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98de43c8 items=0 ppid=353 ppcomm=main pid=6523 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 17:04:11.302  2309  2309 E audit   : type=1327 msg=audit(1471964651.302:287): proctitle="com.test.thalitest"
08-23 17:04:11.302  2309  2309 E audit   : type=1320 msg=audit(1471964651.302:287): 
08-23 17:04:11.302  2309  2309 E audit   : type=1400 msg=audit(1471964651.302:288): avc:  denied  { ioctl } for  pid=6523 comm="Thread-891" path="socket:[40143]" dev="sockfs" ino=40143 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 17:04:11.302  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:11.302  2309  2309 E audit   : type=1300 msg=audit(1471964651.302:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98de43c8 items=0 ppid=353 ppcomm=main pid=6523 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 17:04:11.302  2309  2309 E audit   : type=1327 msg=audit(1471964651.302:288): proctitle="com.test.thalitest"
08-23 17:04:11.302  2309  2309 E audit   : type=1320 msg=audit(1471964651.302:288): 
,08-23 17:04:11.312  6575  6575 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:11.312  6575  6575 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.322  6409  6523 W jxcore-log: Starting JXcore engine
,08-23 17:04:11.332   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{72abfbb 6575:com.samsung.android.app.filterinstaller/1000}
,08-23 17:04:11.332   751  1623 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-23 17:04:11.342  6575  6575 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-23 17:04:11.342   751  1490 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-23 17:04:11.352  6561  6561 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-23 17:04:11.352  6575  6575 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-23 17:04:11.362  6575  6575 E FilterPackageIntentReceiver: This package is not a effect filter
,08-23 17:04:11.372  6588  6588 E Zygote  : v2
08-23 17:04:11.372   751   765 I ActivityManager: Start proc 6588:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-23 17:04:11.372  6588  6588 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:11.372  6588  6588 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:11.372  6588  6588 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:11.372  6588  6588 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:11.372   751   765 I ActivityManager: Killing 4775:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-23 17:04:11.372  6588  6588 E Zygote  : accessInfo : 0
,08-23 17:04:11.392  6588  6588 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:11.392  6588  6588 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.402   751   764 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-23 17:04:11.412   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{940ccd8 6588:com.samsung.helphub/1000}
,08-23 17:04:11.412  6409  6523 W jxcore-log: Platform android
08-23 17:04:11.412  6409  6523 W jxcore-log: 
,08-23 17:04:11.412  6409  6523 W jxcore-log: Process ARCH arm
08-23 17:04:11.412  6409  6523 W jxcore-log: 
,08-23 17:04:11.422  6588  6588 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-23 17:04:11.422   751  1791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-23 17:04:11.432  6588  6588 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-23 17:04:11.452  6561  6561 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-23 17:04:11.452  6561  6561 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-23 17:04:11.452  6561  6561 D DialogFlow: initQueue()
,08-23 17:04:11.472  6603  6603 E Zygote  : v2
08-23 17:04:11.472  6603  6603 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:11.472  6603  6603 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:11.482   751   765 I ActivityManager: Start proc 6603:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-23 17:04:11.482  6603  6603 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:11.482  6603  6603 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:11.482  6603  6603 E Zygote  : accessInfo : 0
08-23 17:04:11.482   751   765 I ActivityManager: Killing 5680:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-23 17:04:11.502   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-23 17:04:11.512  6603  6603 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:11.512  6603  6603 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.512   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{136b33 6603:com.samsung.android.app.mirrorlink/1000}
,08-23 17:04:11.522  6603  6603 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-23 17:04:11.532  6603  6603 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-23 17:04:11.572  6603  6603 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-23 17:04:11.572  6603  6603 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-23 17:04:11.572   751  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{561365e 5129:com.google.android.apps.plus/u0a134}
,08-23 17:04:11.582  3680  3680 D FactoryTest: User mode
,08-23 17:04:11.582  3680  3680 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 17:04:11.582  3680  3680 D MTPRx   : still no open session command from host, so toast
,08-23 17:04:11.592   751  1623 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-23 17:04:11.602   751  1623 D ActivityManager: mDVFSHelper.acquire()
,08-23 17:04:11.602   751  1623 V WindowManager: addAppToken: AppWindowToken{70f878f token=Token{f5f66ee ActivityRecord{695bc69 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,08-23 17:04:11.602   751  1623 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-23 17:04:11.602   751   835 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-23 17:04:11.622   751  1623 D InputDispatcher: Focused application set to: xxxx
,08-23 17:04:11.622   751  1623 D InputDispatcher: Focus left window: 6409
,08-23 17:04:11.622   751   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
,08-23 17:04:11.622   751   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:11.622   751   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-23 17:04:11.622   751   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 17:04:11.622  3680  3680 E MTPRx   : started activity for popup
,08-23 17:04:11.622  6409  6523 I jxcore-log: JXcore Cordova bridge is ready!
08-23 17:04:11.622  6409  6523 I jxcore-log: 
,08-23 17:04:11.622  6409  6523 W jxcore-log: JXcore engine is started
,08-23 17:04:11.632  3680  3680 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-23 17:04:11.632   751  3780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{561365e 5129:com.google.android.apps.plus/u0a134}
,08-23 17:04:11.632  6409  6522 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 17:04:11.632  3680  3680 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-23 17:04:11.632  6409  6409 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 17:04:11.652   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{561365e 5129:com.google.android.apps.plus/u0a134}
,08-23 17:04:11.652  3680  3680 D MTPUSBConnection: onCreate in USBConnection
08-23 17:04:11.652  3680  3680 V MTPUSBConnection: Registering broadcast receiver.
,08-23 17:04:11.652  3680  3680 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-23 17:04:11.652   751  3780 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-23 17:04:11.702   751  3780 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-23 17:04:11.702   751   765 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-23 17:04:11.702   751  1663 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-23 17:04:11.712   751  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-23 17:04:11.712   751  1623 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-23 17:04:11.712  3680  3680 D TAG     : dev.kiessupport is : TRUE
,08-23 17:04:11.722   751  1722 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-23 17:04:11.722   751  1722 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-23 17:04:11.722   751  1726 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-23 17:04:11.742   751  1791 I ActivityManager: Start proc 6618:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-23 17:04:11.742  6618  6618 E Zygote  : v2
08-23 17:04:11.742  6618  6618 I libpersona: KNOX_SDCARD checking this for 10165
08-23 17:04:11.742  6618  6618 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:11.742  6618  6618 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:11.742  6618  6618 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 17:04:11.742  6618  6618 E Zygote  : accessInfo : 0
08-23 17:04:11.742  6618  6618 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-23 17:04:11.742  3680  3680 D SecWifiDisplayUtil: Metadata value : none
,08-23 17:04:11.742  3680  3680 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{872dfd7 V.E...... R.....I. 0,0-0,0}
,08-23 17:04:11.752   751  1623 I ActivityManager: Killing 5697:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-23 17:04:11.762  3680  6629 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 17:04:11.772   751   765 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-23 17:04:11.772   751  3780 D ISSUE_DEBUG: InputChannelName : 6bbf0b4 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-23 17:04:11.772   751   838 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6bbf0b4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-23 17:04:11.772   751  3780 D InputDispatcher: Focus entered window: 3680
08-23 17:04:11.772  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-23 17:04:11.772   751   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:751 uid:1000
08-23 17:04:11.772   751   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:11.772   751   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:751 uid:1000
08-23 17:04:11.772   751   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 17:04:11.772  6618  6618 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:11.772  6618  6618 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.792   751  2440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9484dd 6618:com.sec.kidsplat.installer/u0a165}
08-23 17:04:11.792  3680  3680 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a83f2cf I.E...... R.....I. 0,0-0,0}
,08-23 17:04:11.792   751  1623 D ISSUE_DEBUG: InputChannelName : 68d8723 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-23 17:04:11.792   751  2070 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-23 17:04:11.792   751  2070 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 17:04:11.792   751   751 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 17:04:11.792   751   751 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-23 17:04:11.802   751   751 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-23 17:04:11.802  6618  6618 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-23 17:04:11.812  6420  6420 I Mms/MmsApp:  start initViewCache mms
,08-23 17:04:11.832   294   294 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-23 17:04:11.842  6618  6618 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-23 17:04:11.862   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9484dd 6618:com.sec.kidsplat.installer/u0a165}
,08-23 17:04:11.862  3680  6629 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 17:04:11.862  3680  6629 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 17:04:11.862  3680  6629 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 17:04:11.862  3680  6629 I Adreno-EGL: Local Branch: ss
08-23 17:04:11.862  3680  6629 I Adreno-EGL: Remote Branch: 
08-23 17:04:11.862  3680  6629 I Adreno-EGL: Local Patches: 
08-23 17:04:11.862  3680  6629 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:04:11.872  6618  6618 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-23 17:04:11.872  3680  6629 D libEGL  : eglInitialize EGLDisplay = 0x9eff77c4
08-23 17:04:11.872  3680  6629 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 17:04:11.872   751   761 I art     : Background partial concurrent mark sweep GC freed 27598(1780KB) AllocSpace objects, 2(40KB) LOS objects, 27% free, 42MB/58MB, paused 7.398ms total 107.331ms
,08-23 17:04:11.882   751  1632 I ActivityManager: Start proc 6631:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-23 17:04:11.882   751  1632 I ActivityManager: Killing 5835:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-23 17:04:11.882  6631  6631 E Zygote  : v2
08-23 17:04:11.882  6631  6631 I libpersona: KNOX_SDCARD checking this for 10142
08-23 17:04:11.882  6631  6631 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:11.882  6631  6631 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 17:04:11.882  6631  6631 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:04:11.882  6631  6631 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:11.882  6631  6631 E Zygote  : accessInfo : 64
,08-23 17:04:11.882  6631  6631 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 17:04:11.882  6631  6631 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-23 17:04:11.882  6631  6631 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-23 17:04:11.912   294   294 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-23 17:04:11.912  6631  6631 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:11.912  6631  6631 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:11.932   751  1722 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{15991d9 6631:com.sec.android.app.sbrowser/u0a142}
,08-23 17:04:11.932   751  1623 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-23 17:04:11.952  3680  3680 V ActivityThread: updateVisibility : ActivityRecord{bb1d83a token=android.os.BinderProxy@6700c4 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-23 17:04:11.952  3680  3680 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 17:04:11.962  6631  6631 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 17:04:12.002   751  1367 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-23 17:04:12.012  6631  6631 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-23 17:04:12.052   751  1632 V WindowStateAnimator: Finishing drawing window Window{6bbf0b4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-23 17:04:12.062  3680  3680 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 17:04:12.062   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebde364
,08-23 17:04:12.062   751  1722 V WindowStateAnimator: Finishing drawing window Window{68d8723 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-23 17:04:12.062  3680  3680 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-23 17:04:12.062  3680  3680 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-23 17:04:12.072   751  3780 V WindowStateAnimator: Finishing drawing window Window{6bbf0b4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-23 17:04:12.072   751  1663 V WindowStateAnimator: Finishing drawing window Window{68d8723 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-23 17:04:12.072  3680  3680 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6700c4 time:108305
,08-23 17:04:12.072   751   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 17:04:12.072   751   751 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 17:04:12.072   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebde364
08-23 17:04:12.072   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebde364
,08-23 17:04:12.072   751   891 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +462ms (total +476ms)
,08-23 17:04:12.072   751   751 I KnoxTimeoutHandler: SD activityfalse
,08-23 17:04:12.082   751   891 D ActivityManager: mDVFSHelper.release()
08-23 17:04:12.082   751   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{695bc69 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108312
,08-23 17:04:12.082  6631  6631 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 17:04:12.092  6631  6631 D ManifestProvider: onCreate()
,08-23 17:04:12.102  6631  6631 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-23 17:04:12.102  6631  6631 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 17:04:12.102  6631  6631 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 17:04:12.102  6631  6631 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-23 17:04:12.112  6631  6631 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-23 17:04:12.112  6631  6631 D [MM]MHDataBaseProvider: onCreate()
,08-23 17:04:12.122  6631  6631 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@8c2bee3)
,08-23 17:04:12.142   751  1490 I ActivityManager: Killing 5667:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-23 17:04:12.152   751  1490 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6004aeb 2042:com.google.android.gms.persistent/u0a11}
,08-23 17:04:12.162   751  3780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b51c75 4200:com.google.android.gms/u0a11}
,08-23 17:04:12.172  4200  6652 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 17:04:12.182   751   765 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-23 17:04:12.182  4200  6651 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-23 17:04:12.192  4200  4200 D AsyncTaskServiceImpl: Submit a task: nzm
,08-23 17:04:12.202  4200  6652 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 17:04:12.202  4200  5069 D nzm     : Processing package: com.test.thalitest
,08-23 17:04:12.212   751  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6004aeb 2042:com.google.android.gms.persistent/u0a11}
,08-23 17:04:12.222  4200  6652 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 17:04:12.232   751  1424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b51c75 4200:com.google.android.gms/u0a11}
,08-23 17:04:12.232  4200  6652 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 17:04:12.232  4200  4200 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 17:04:12.252  4200  5069 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-23 17:04:12.252  4200  5069 D nzm     : Found info for package com.test.thalitest in db.
,08-23 17:04:12.272  6420  6420 D Mms/BubbleViewCache: fillCache bubble = 4
,08-23 17:04:12.352   751  1424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3015aae 4902:com.android.vending/u0a29}
,08-23 17:04:12.412   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2cfcfd u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e90510f 6069:com.sec.android.app.samsungapps/u0a39}
,08-23 17:04:12.422  4902  4902 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-23 17:04:12.432   751  1663 I ActivityManager: Start proc 6658:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-23 17:04:12.442  6658  6658 E Zygote  : v2
08-23 17:04:12.442  6658  6658 I libpersona: KNOX_SDCARD checking this for 10034
08-23 17:04:12.442  6658  6658 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:12.442  6658  6658 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:12.442  6658  6658 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:12.442  6658  6658 E Zygote  : accessInfo : 0
,08-23 17:04:12.442  6658  6658 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-23 17:04:12.442  4902  4902 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-23 17:04:12.462  2042  2042 D WearableService: callingUid 10011, callindPid: 2042
,08-23 17:04:12.472  6658  6658 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:12.472  6658  6658 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:12.472  4902  4902 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-23 17:04:12.472  4902  4902 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-23 17:04:12.482   751  1623 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a47f96f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97f367c 6658:com.sec.android.app.shealth/u0a34}
,08-23 17:04:12.482  6561  6602 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 17:04:12.492  6561  6602 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 17:04:12.492  6658  6658 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-23 17:04:12.512  6658  6658 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-23 17:04:12.522  6658  6658 I MultiDex: VM with version 2.1.0 has multidex support
08-23 17:04:12.522  6658  6658 I MultiDex: install
08-23 17:04:12.522  6658  6658 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 17:04:12.522  6658  6658 I MultiDex: install
08-23 17:04:12.522  6658  6658 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 17:04:12.532  6561  6602 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 17:04:12.532  6561  6602 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 17:04:12.532  6561  6602 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-23 17:04:12.562  6561  6602 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-23 17:04:12.562  6561  6602 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 17:04:12.642   751  1663 I ActivityManager: Killing 5392:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-23 17:04:12.642   751  3430 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-23 17:04:12.642   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a47f96f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54bd7e 1861:com.sec.android.app.shealth:remote/u0a34}
08-23 17:04:12.662  6658  6658 D HealthDataStore: Service for HealthDataStore is connected
08-23 17:04:12.662  6658  6658 D HealthDataStore: HealthConnectionErrorResult code : 9
08-23 17:04:12.672  6658  6658 D HealthConsole: Service for HealthDataConsole is connected
,08-23 17:04:12.682   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-23 17:04:12.692   751  2440 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a47f96f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54bd7e 1861:com.sec.android.app.shealth:remote/u0a34}
,08-23 17:04:12.712   751  1632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{87fa767 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6004aeb 2042:com.google.android.gms.persistent/u0a11}
,08-23 17:04:12.742  6658  6658 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-23 17:04:12.742  6658  6658 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 17:04:12.792  1452  1452 D Recents : onTaskStackChanged
,08-23 17:04:12.802  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 17:04:13.422  4200  5019 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-23 17:04:13.482  4200  5019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 17:04:13.522  4200  5019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 17:04:13.522  4200  5019 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-23 17:04:13.642   751  1237 V AlarmManager: Expired Alarm result :4
,08-23 17:04:13.652   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-23 17:04:13.652   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-23 17:04:13.662   751  1791 V AlarmManager:  remove PendingIntent] PendingIntent{ff17280: PendingIntentRecord{8e068e4 com.google.android.gms broadcastIntent}}
,08-23 17:04:13.862   751  3426 D SSRM:n  : SIOP:: AP = 480, PST = 467, CUR = 350, LCD = 0
,08-23 17:04:13.872   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:04:14.792   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:04:17.662   751  3426 D M       : limitCPUFreq:: freq = 1728000
,08-23 17:04:17.662   751  3426 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  pkgName : SIOP_ARM_MAX@25
,08-23 17:04:17.662   751  3426 D M       : limitGPUFreq:: freq = 389000000
,08-23 17:04:17.672   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:04:18.522   751   920 D PackageManager: [MSG] MCS_UNBIND
,08-23 17:04:18.552   751  3780 I ActivityManager: Killing 5852:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-23 17:04:18.582   751  1663 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-23 17:04:18.982   751   920 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 17:04:18.992   751   920 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 17:04:22.882  6409  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 17:04:22.882  6409  6523 I jxcore-log: 
,08-23 17:04:22.882  6409  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 17:04:22.882  6409  6523 I jxcore-log: 
,08-23 17:04:22.892  6409  6523 D BluetoothAdapter: STATE_ON
,08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:22.892  6409  6523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 17:04:22.902  6409  6523 D BluetoothAdapter: STATE_ON
,08-23 17:04:22.902  6409  6523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 17:04:22.902  6409  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 17:04:22.902  6409  6523 I jxcore-log: 
,08-23 17:04:22.902  6409  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 17:04:22.902  6409  6523 I jxcore-log: 
,08-23 17:04:23.202   751   835 I ActivityManager: Waited long enough for: ServiceRecord{949403b u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-23 17:04:23.562  6409  6523 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-23 17:04:23.562  6409  6523 I jxcore-log: Failed to execute UT.
08-23 17:04:23.562  6409  6523 I jxcore-log: 
,08-23 17:04:23.562  6409  6523 I jxcore-log: Unit Test app is loaded
08-23 17:04:23.562  6409  6523 I jxcore-log: 
,08-23 17:04:23.572  6409  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 17:04:23.572  6409  6523 I jxcore-log: 
,08-23 17:04:23.572  6409  6523 I jxcore-log: My device name is: samsung-SM-G900F
08-23 17:04:23.572  6409  6523 I jxcore-log: 
,08-23 17:04:23.572  6409  6523 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 17:04:23.572  6409  6523 I jxcore-log: 
,08-23 17:04:23.592  6409  6409 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-23 17:04:23.702   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-23 17:04:23.702   751  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-23 17:04:23.922   751  3426 D SSRM:n  : SIOP:: AP = 450, PST = 464, CUR = 350, LCD = 0
,08-23 17:04:23.932   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:04:24.302   751  1632 I ActivityManager: Killing 5414:com.policydm/1000 (adj 15): DHA:empty #37
,08-23 17:04:24.342   751  1320 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-23 17:04:24.352  6374  6374 D AASAservice: onDestroy()
,08-23 17:04:24.352  6374  6374 I art     : System.exit called, status: 80
08-23 17:04:24.352  6374  6374 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-23 17:04:24.362   751  1623 I ActivityManager: Process com.samsung.aasaservice (pid 6374)(adj 0) has died(94,697)
,08-23 17:04:24.362   751  1623 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-23 17:04:24.402   353   353 I Zygote  : Process 6374 exited cleanly (80)
,08-23 17:04:24.762   751  1574 E Watchdog: !@Sync 3 [08-23 17:04:24.770]
,08-23 17:04:27.362   751  1237 V AlarmManager: Expired Alarm result :4
,08-23 17:04:27.382   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5501c5f u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6004aeb 2042:com.google.android.gms.persistent/u0a11}
,08-23 17:04:27.422   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{7e0fb0a: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:27.442   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:27.442   751  2070 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4361, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 17:04:27.442   751  2070 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-23 17:04:27.442   751  2070 D BatteryService: stay LED for charging
08-23 17:04:27.442   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:27.452   751   751 I MotionRecognitionService: Plugged
,08-23 17:04:27.452   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:04:27.452  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:04:27.452  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:27.452   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:04:27.452   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:04:27.452  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:27.452  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:27.452  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:04:27.452  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:04:27.452  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:27.452  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:27.462  4902  4950 I Finsky  : [685] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-23 17:04:27.572   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{67b1198: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:27.682  4200  6735 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-23 17:04:27.682  4200  6735 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 17:04:27.712  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:27.722   751   764 V AlarmManager:  remove PendingIntent] PendingIntent{24102f3: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:27.752   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f867bb0 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6004aeb 2042:com.google.android.gms.persistent/u0a11}
,08-23 17:04:27.782   751  1490 V AlarmManager:  remove PendingIntent] PendingIntent{127a29: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:27.822   751  1791 V AlarmManager:  remove PendingIntent] PendingIntent{dccb1ae: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:27.942  4902  4950 I Finsky  : [685] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-23 17:04:27.942  4902  4902 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-23 17:04:28.072   751   765 I ActivityManager: Start proc 6742:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-23 17:04:28.072  6742  6742 E Zygote  : v2
08-23 17:04:28.072  6742  6742 I libpersona: KNOX_SDCARD checking this for 10011
08-23 17:04:28.072  6742  6742 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:28.072  6742  6742 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:04:28.072  6742  6742 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:28.072  6742  6742 E Zygote  : accessInfo : 0
,08-23 17:04:28.072  6742  6742 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-23 17:04:28.092  6742  6742 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:28.092  6742  6742 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:28.112  6742  6742 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 17:04:28.152  6742  6742 I MultiDex: VM with version 2.1.0 has multidex support
,08-23 17:04:28.152  6742  6742 I MultiDex: install
08-23 17:04:28.152  6742  6742 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 17:04:28.182  6742  6742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 17:04:28.202  6742  6742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-23 17:04:28.202  6742  6742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 17:04:28.202  6742  6742 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 17:04:28.242  6742  6742 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 17:04:28.252  6742  6742 D ChimeraCfgMgr: Reading stored module config
,08-23 17:04:28.372  6742  6756 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 17:04:28.412  2042  2042 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=7e5a2c12-b9d4-4a67-ae66-7542abbda67a
,08-23 17:04:28.432  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:28.432  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:28.452   320   951 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6742)
,08-23 17:04:28.512   320   965 D WVCdm   : Instantiating CDM.
,08-23 17:04:28.512   320   320 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6742)
08-23 17:04:28.512   320   320 I WVCdm   : CdmEngine::OpenSession
08-23 17:04:28.512   320   320 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-23 17:04:28.522   320   320 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 17:04:28.532   320   320 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,08-23 17:04:28.532   320   320 D DrmWidevineDash: Service_Initialize: starts!
08-23 17:04:28.532   320   320 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-23 17:04:28.532   320   320 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:04:28.532   320   320 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-23 17:04:28.532   320   320 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 17:04:28.532   320   320 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 17:04:28.532   320   320 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:04:28.532   320   320 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-23 17:04:28.532   320   320 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 17:04:28.532   320   320 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 17:04:28.532   320   320 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:04:28.562   320   320 D QSEECOMAPI: : Loaded image: APP id = 3
,08-23 17:04:28.572   320   320 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-23 17:04:28.572   320   320 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee4c000
08-23 17:04:28.572   320   320 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee4c000
,08-23 17:04:28.572  6742  6752 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:28.572  6742  6752 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:28.582   307  1199 D EnterpriseController: netId is 0
08-23 17:04:28.582   307  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 17:04:28.592   320   320 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-23 17:04:28.592   320   320 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-23 17:04:28.592   320   320 D DrmWidevineDash: hlos api version =  10
08-23 17:04:28.592   320   320 D DrmWidevineDash: tz api version =  10
08-23 17:04:28.592   320   320 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-23 17:04:28.592   320   320 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-23 17:04:28.602   320   320 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-23 17:04:28.602   320   320 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-23 17:04:28.602   320   320 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbecd06b4
,08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e1ddc8, dataLength=8
,08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xad705c00, wrapped_rsa_key_length=1280
,08-23 17:04:28.612   320   320 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-23 17:04:28.622   320   320 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 17:04:28.622   320   958 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-23 17:04:28.622   320   958 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-23 17:04:28.622   320   958 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 17:04:28.622   320   958 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xad3fbe60, idLength=0xaf0eaf2c
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
,08-23 17:04:28.632  6742  6752 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6742, getuid(): 10011
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-23 17:04:28.632   320   958 D DrmWidevineDash: hlos api version =  10
,08-23 17:04:28.632   320   958 D DrmWidevineDash: tz api version =  10
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-23 17:04:28.632   320   958 D WVCdm   : PrepareKeyRequest: nonce=4024919451
,08-23 17:04:28.632   320   958 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xad477c00
08-23 17:04:28.632   320   958 D DrmWidevineDash: message_length=1631, signature=0xaf55edc0, signature_length=2936975364
,08-23 17:04:28.652  2042  2240 W GCoreFlp: No location to return for getLastLocation()
,08-23 17:04:28.742  4200  6736 D UdcContextInitService: registered all accounts: true
,08-23 17:04:28.762   320   958 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-23 17:04:28.762   320   965 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6742)
08-23 17:04:28.762   320   965 I WVCdm   : CdmEngine::CloseSession
08-23 17:04:28.762   320   965 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-23 17:04:28.772   320   965 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-23 17:04:28.772   320   965 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-23 17:04:28.772   320   965 D DrmWidevineDash: Service_Uninitialize: starts!
08-23 17:04:28.772   320   965 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-23 17:04:28.772   320   965 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-23 17:04:28.772   320   965 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-23 17:04:28.772   320   965 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-23 17:04:28.772  2042  2449 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 17:04:28.782  6742  6752 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6742, getuid(): 10011
,08-23 17:04:28.782  2042  2585 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 17:04:28.902  6742  6752 I qtaguid : Untagging socket 21
,08-23 17:04:28.942  6742  6752 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 17:04:28.942  6742  6752 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 17:04:29.002  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 17:04:29.002  6409  6523 I jxcore-log: 
,08-23 17:04:29.002   751   761 I art     : Background partial concurrent mark sweep GC freed 28877(1590KB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 42MB/58MB, paused 2.015ms total 170.329ms
,08-23 17:04:29.472  6768  6768 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-23 17:04:29.582  6768  6768 I dex2oat : ----------------------------------------------------
08-23 17:04:29.582  6768  6768 I dex2oat : <SS>: S T A R T I N G . . .
08-23 17:04:29.582  6768  6768 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-23 17:04:29.582  6768  6768 I dex2oat : dex2oat took 106.197ms (threads: 4) arena alloc=56KB java alloc=43KB native alloc=1414KB free=1657KB
,08-23 17:04:29.592  6742  6752 W System  : ClassLoader referenced unknown path: 
,08-23 17:04:29.592  6742  6752 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-23 17:04:29.592  6742  6752 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 17:04:29.592  6742  6752 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 17:04:29.592  6742  6752 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 17:04:29.592  6742  6752 I Adreno-EGL: Local Branch: ss
08-23 17:04:29.592  6742  6752 I Adreno-EGL: Remote Branch: 
08-23 17:04:29.592  6742  6752 I Adreno-EGL: Local Patches: 
08-23 17:04:29.592  6742  6752 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:04:29.602  6742  6752 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-23 17:04:29.672  6742  6752 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-23 17:04:29.672  6742  6752 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 17:04:29.672  6742  6752 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 17:04:29.672  6742  6752 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 17:04:29.672  6742  6752 I Adreno-EGL: Local Branch: ss
08-23 17:04:29.672  6742  6752 I Adreno-EGL: Remote Branch: 
08-23 17:04:29.672  6742  6752 I Adreno-EGL: Local Patches: 
08-23 17:04:29.672  6742  6752 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:04:29.672  6742  6752 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-23 17:04:29.722  6742  6752 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-23 17:04:29.842  6742  6752 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 17:04:29.842  6742  6752 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 17:04:29.842  6742  6752 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 17:04:29.842  6742  6752 I Adreno-EGL: Local Branch: ss
08-23 17:04:29.842  6742  6752 I Adreno-EGL: Remote Branch: 
08-23 17:04:29.842  6742  6752 I Adreno-EGL: Local Patches: 
08-23 17:04:29.842  6742  6752 I Adreno-EGL: Reconstruct Branch: 
,08-23 17:04:29.842  6742  6752 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-23 17:04:29.902  6742  6752 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-23 17:04:29.982  2042  6738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:29.982  2042  6738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:29.982   307  1199 D EnterpriseController: netId is 0
08-23 17:04:29.982   307  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 17:04:29.992  2042  6738 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 2042, getuid(): 10011
,08-23 17:04:30.042  2042  6738 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 2042, getuid(): 10011
,08-23 17:04:30.252  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 17:04:30.252  6409  6523 I jxcore-log: 
,08-23 17:04:30.292  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 17:04:30.292  6409  6523 I jxcore-log: 
,08-23 17:04:30.292  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 17:04:30.292  6409  6523 I jxcore-log: 
,08-23 17:04:30.312   751  2440 V AlarmManager:  remove PendingIntent] PendingIntent{1775870: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:30.322  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 17:04:30.322  6409  6523 I jxcore-log: 
,08-23 17:04:30.322  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 17:04:30.322  6409  6523 I jxcore-log: 
,08-23 17:04:30.352  2042  2585 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 17:04:30.362  2042  2585 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-23 17:04:30.362  2042  2585 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-23 17:04:28.871+0200, stopTime=2016-08-23 17:04:30.369+0200, duration=1498ms
,08-23 17:04:30.372  2042  6791 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:30.372  2042  6791 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:30.372   307  1199 D EnterpriseController: netId is 0
08-23 17:04:30.372   307  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 17:04:30.372  2042  6791 I qtaguid : Tagging socket 53 with tag 1000310500000000{268448005,0} uid 10011, pid: 2042, getuid(): 10011
,08-23 17:04:30.412  2042  6791 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 2042, getuid(): 10011
,08-23 17:04:30.652  2042  6791 I qtaguid : Untagging socket 53
08-23 17:04:30.652   751  1726 V AlarmManager:  remove PendingIntent] PendingIntent{fe2bc6e: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:30.732  2042  2585 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 17:04:30.892  2042  6806 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:30.892  2042  6803 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:30.902  2042  6806 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:30.902  2042  6803 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:30.922  2042  6806 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:30.922  2042  6803 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:30.932  2042  6803 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-23 17:04:30.942  2042  6803 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 17:04:31.012   751  1663 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.042  2042  6803 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-23 17:04:31.062  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.062  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.062   307  1199 D EnterpriseController: netId is 0
08-23 17:04:31.062   307  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 17:04:31.072  2042  6803 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.122  2042  6803 I qtaguid : Tagging socket 66 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.352   751  1791 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.382  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:31.382  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.382  2042  6803 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.532   751  1726 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.542  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.542  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.542  2042  6803 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.682   751  1632 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.682  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.682  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.682  2042  6803 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.822   751  1490 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.842  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.842  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.842  2042  6803 I qtaguid : Tagging socket 63 with tag fffffca200000000{4294966434,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:31.972   751   764 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:31.992  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.992  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:31.992  2042  6803 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:32.142   751   765 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:32.152  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:32.152  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:32.152  2042  6803 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:32.282   751  1791 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:32.292  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:32.292  2042  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:32.292  2042  6803 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 2042, getuid(): 10011
,08-23 17:04:32.502   751  3780 V AlarmManager:  remove PendingIntent] PendingIntent{c39c588: PendingIntentRecord{33ccc2 com.google.android.gms broadcastIntent}}
,08-23 17:04:32.522  2042  6789 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:32.522  2042  6789 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:32.522  2042  6789 I qtaguid : Tagging socket 53 with tag 1000310200000000{268448002,0} uid 10011, pid: 2042, getuid(): 10011
,08-23 17:04:32.772  2042  6789 I qtaguid : Untagging socket 53
,08-23 17:04:32.772  2042  2585 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 17:04:33.992   751  3426 D SSRM:n  : SIOP:: AP = 440, PST = 460, CUR = 350, LCD = 0
,08-23 17:04:34.542  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 17:04:34.542  6409  6523 I jxcore-log: 
,08-23 17:04:34.552  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 17:04:34.552  6409  6523 I jxcore-log: 
,08-23 17:04:34.572  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 17:04:34.572  6409  6523 I jxcore-log: 
,08-23 17:04:34.772  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 17:04:34.772  6409  6523 I jxcore-log: 
,08-23 17:04:34.792   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:04:35.832  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 17:04:35.832  6409  6523 I jxcore-log: 
,08-23 17:04:36.142  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 17:04:36.142  6409  6523 I jxcore-log: 
,08-23 17:04:36.152  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 17:04:36.152  6409  6523 I jxcore-log: 
,08-23 17:04:36.402  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 17:04:36.402  6409  6523 I jxcore-log: 
,08-23 17:04:36.432  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 17:04:36.432  6409  6523 I jxcore-log: 
,08-23 17:04:36.432  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 17:04:36.432  6409  6523 I jxcore-log: 
,08-23 17:04:36.442  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 17:04:36.442  6409  6523 I jxcore-log: 
,08-23 17:04:36.462  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-23 17:04:36.462  6409  6523 I jxcore-log: 
,08-23 17:04:36.482  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 17:04:36.482  6409  6523 I jxcore-log: 
,08-23 17:04:36.592  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 17:04:36.592  6409  6523 I jxcore-log: 
,08-23 17:04:36.602  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 17:04:36.602  6409  6523 I jxcore-log: 
,08-23 17:04:36.632  6409  6523 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 17:04:36.632  6409  6523 I jxcore-log: 
,08-23 17:04:36.652  6409  6523 D BluetoothAdapter: STATE_ON
,08-23 17:04:36.652  6409  6523 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 17:04:36.652  6409  6523 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 17:04:36.652  6409  6523 I jxcore-log: 
,08-23 17:04:37.522   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:37.522   751  1722 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:04:37.532   751  1722 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:04:37.532   751  1722 D BatteryService: stay LED for charging
08-23 17:04:37.532   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:37.532   751   751 I MotionRecognitionService: Plugged
,08-23 17:04:37.532   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:04:37.532   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:04:37.532   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:04:37.542  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:37.542  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:37.542  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:37.552  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:37.552  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:04:37.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:37.572  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:37.572  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:44.052   751  3426 D SSRM:n  : SIOP:: AP = 410, PST = 449, CUR = 350, LCD = 0
,08-23 17:04:44.052   751  3426 D M       : limitCPUFreq:: freq = -1
,08-23 17:04:44.052   751  3426 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 751  tag : SIOP_ARM_MAX@25
,08-23 17:04:44.062   751  3426 D M       : limitGPUFreq:: freq = -1
,08-23 17:04:44.062   751  3426 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-23 17:04:44.082   751   835 I ActivityManager: Start proc 6839:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-23 17:04:44.082   751  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-23 17:04:44.092  6839  6839 E Zygote  : v2
,08-23 17:04:44.092  6839  6839 I libpersona: KNOX_SDCARD checking this for 10053
,08-23 17:04:44.092  6839  6839 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:44.092  6839  6839 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:04:44.102  6839  6839 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:04:44.102   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:04:44.102  6839  6839 E Zygote  : accessInfo : 0
,08-23 17:04:44.102  6839  6839 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-23 17:04:44.132  2769  2769 D ContentApp:  LEVEL : 1
,08-23 17:04:44.142  6839  6839 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:44.142  6839  6839 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:44.192   751  1632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{871eb46 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54b107 6839:com.sec.android.app.videoplayer/u0a53}
,08-23 17:04:44.202   751  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 17:04:44.212  6839  6839 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 17:04:44.252  6839  6839 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-23 17:04:44.282  6839  6839 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 17:04:44.312  6839  6839 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 17:04:44.312  6839  6839 D videowall-Global: core_num = 4
,08-23 17:04:44.332  6839  6839 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-23 17:04:44.332  6839  6839 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-23 17:04:44.352  6839  6839 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-23 17:04:44.352   751  2070 I ActivityManager: Killing 5929:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-23 17:04:44.382   751  1726 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-23 17:04:47.602   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:47.612   751  1722 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:04:47.612   751  1722 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:04:47.612   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:47.632   751   751 I MotionRecognitionService: Plugged
,08-23 17:04:47.632   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:04:47.632   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:04:47.632   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:04:47.632  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:47.632  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:47.642  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:47.642   751  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-23 17:04:47.642   751  1722 D BatteryService: stay LED for charging
,08-23 17:04:47.652  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:47.652  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:04:47.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:47.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:47.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:54.192   751  3426 D SSRM:n  : SIOP:: AP = 400, PST = 440, CUR = 350, LCD = 0
,08-23 17:04:54.772   751  1574 E Watchdog: !@Sync 4 [08-23 17:04:54.772]
,08-23 17:04:54.802   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:04:55.682  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:04:57.682   751  1632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:57.682   751  1632 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:04:57.682   751  1632 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:04:57.692   751  1632 D BatteryService: stay LED for charging
,08-23 17:04:57.692   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:57.702   751   751 I MotionRecognitionService: Plugged
,08-23 17:04:57.702   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:04:57.712   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:04:57.712   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:04:57.732  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:57.732  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:57.732  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:57.742  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:57.742  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:04:57.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:57.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:57.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:04:59.532   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:04:59.532   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:04:59.532   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:04:59.992   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:05:00.402   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:05:00.402   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:05:00.402   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:05:04.252   751  3426 D SSRM:n  : SIOP:: AP = 380, PST = 434, CUR = 350, LCD = 0
,08-23 17:05:10.322   751  1237 V AlarmManager: Expired Alarm result :4
,08-23 17:05:10.392   751  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:10.392   751  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:05:10.392   751  1424 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:05:10.392   751  1424 D BatteryService: stay LED for charging
,08-23 17:05:10.442  6880  6880 E Zygote  : v2
,08-23 17:05:10.442  6880  6880 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:05:10.442  6880  6880 I libpersona: KNOX_SDCARD not a persona
,08-23 17:05:10.452  6880  6880 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:05:10.452  6880  6880 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:05:10.452  6880  6880 E Zygote  : accessInfo : 0
,08-23 17:05:10.452   751  1237 I ActivityManager: Start proc 6880:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-23 17:05:10.462  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 17:05:10.462  1382  1382 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 17:05:10.462  1382  1382 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:05:10.472  1382  1382 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:05:10.472  1382  1382 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 17:05:10.482   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:10.492   751   751 I MotionRecognitionService: Plugged
,08-23 17:05:10.492   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:05:10.492   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:05:10.492   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:05:10.492  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.492  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.492  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.492  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.502  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.512  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.512  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:05:10.512  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:05:10.512  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.512  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:10.512  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:10.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:05:10.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:05:10.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 17:05:10.522  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:10.542  6880  6880 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:05:10.542  6880  6880 D ActivityThread: Added TimaKeyStore provider
,08-23 17:05:10.562  6880  6880 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-23 17:05:10.582  6880  6880 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-23 17:05:10.592  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:10.612   751  3780 I ActivityManager: Killing 5949:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-23 17:05:10.632   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-23 17:05:14.322   751  3426 D SSRM:n  : SIOP:: AP = 360, PST = 426, CUR = 350, LCD = 0
,08-23 17:05:14.322   751  3426 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-23 17:05:14.382  2769  2769 D ContentApp:  LEVEL : 0
,08-23 17:05:14.392   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{facad59 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54b107 6839:com.sec.android.app.videoplayer/u0a53}
,08-23 17:05:14.402   751  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 17:05:14.422  6839  6839 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 17:05:14.422  6839  6839 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-23 17:05:14.802   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:05:15.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:05:15.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:05:15.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:05:20.482   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:20.482   751  2070 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:05:20.492   751  2070 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:05:20.492   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:20.502   751   751 I MotionRecognitionService: Plugged
,08-23 17:05:20.502   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:05:20.512   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:05:20.512   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:05:20.522   751  2070 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,08-23 17:05:20.522   751  2070 D BatteryService: stay LED for charging
,08-23 17:05:20.532  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:20.532  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:20.532  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:20.552  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:20.552  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:05:20.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:05:20.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:05:20.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 17:05:21.252  4200  5065 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 17:05:23.362  2042  3292 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 17:05:24.472   751  3426 D SSRM:n  : SIOP:: AP = 350, PST = 417, CUR = 350, LCD = 0
,08-23 17:05:24.772   751  1574 E Watchdog: !@Sync 5 [08-23 17:05:24.780]
,08-23 17:05:24.922   751  3430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-23 17:05:24.932   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{af5a2cd u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e5e42a5 6209:com.samsung.android.sm.provider/1000}
,08-23 17:05:25.082   751  3430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-23 17:05:25.092   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6452e93 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e5e42a5 6209:com.samsung.android.sm.provider/1000}
,08-23 17:05:30.582   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:30.582   751  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:05:30.592   751  1320 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:05:30.592   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:30.602   751   751 I MotionRecognitionService: Plugged
,08-23 17:05:30.602   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:05:30.602   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:05:30.602   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:05:30.612   751  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,08-23 17:05:30.612   751  1320 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 751) 
,08-23 17:05:30.622   751  1320 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-23 17:05:30.632  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:30.632  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:30.632  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:30.632  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:05:30.642   751  1320 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-23 17:05:30.652   751  1320 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-23 17:05:30.652  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:30.652  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:05:30.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:05:30.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:05:30.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:05:30.682   751  1320 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-23 17:05:30.682   751  1320 D BatteryService: turn on LED for fully charged
,08-23 17:05:31.052   751  1220 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-23 17:05:31.052   751   901 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-23 17:05:31.062   751   901 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-23 17:05:31.072   751   901 D SensorManager: unregisterListener ::   
,08-23 17:05:31.072   751   901 D lights  : led_pattern : 5 +
,08-23 17:05:31.092   751   901 D lights  : led_pattern : 5 -
,08-23 17:05:31.092   751   901 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-23 17:05:31.092   751   901 V AlarmManager:  remove PendingIntent] PendingIntent{ead2f50: PendingIntentRecord{c07b549 android broadcastIntent}}
,08-23 17:05:34.532   751  3426 D SSRM:n  : SIOP:: AP = 340, PST = 407, CUR = 350, LCD = 0
,08-23 17:05:34.532   751  3426 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-23 17:05:34.552  2769  2769 D ContentApp:  LEVEL : -1
,08-23 17:05:34.592   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3469ec9 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c54b107 6839:com.sec.android.app.videoplayer/u0a53}
,08-23 17:05:34.592  6839  6839 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 17:05:34.592  6839  6839 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-23 17:05:34.802   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:05:40.652   751  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:40.652   751  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:05:40.652   751  1791 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:05:40.662   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:40.682   751   751 I MotionRecognitionService: Plugged
,08-23 17:05:40.682   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:05:40.682   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:05:40.682   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:05:40.692   751  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,08-23 17:05:40.692   751  1791 D BatteryService: stay LED for fully charged
,08-23 17:05:40.692  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:40.692  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:05:40.692  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:40.712  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:40.712  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:05:40.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:05:40.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:05:40.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:05:44.642   751  3426 D SSRM:n  : SIOP:: AP = 340, PST = 395, CUR = 350, LCD = 0
,08-23 17:05:50.742   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:54.702   751  3426 D SSRM:n  : SIOP:: AP = 340, PST = 381, CUR = 350, LCD = 0
,08-23 17:05:54.782   751  1574 E Watchdog: !@Sync 6 [08-23 17:05:54.788]
,08-23 17:05:54.812   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:05:55.792  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:05:59.992   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:06:00.822   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:00.822   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:06:00.822   751  1490 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:06:00.832   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:00.842   751   751 I MotionRecognitionService: Plugged
,08-23 17:06:00.842   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:06:00.842   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:06:00.852   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:06:00.852   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 17:06:00.852   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:06:00.862  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:00.862  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:00.862  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:00.892  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:00.892  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:06:00.892  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:00.902  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:06:00.902  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:04.762   751  3426 D SSRM:n  : SIOP:: AP = 330, PST = 369, CUR = 350, LCD = 0
,08-23 17:06:10.912   751  2440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:10.912   751  2440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:06:10.912   751  2440 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:06:10.922   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:10.932   751   751 I MotionRecognitionService: Plugged
,08-23 17:06:10.932   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:06:10.942   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:06:10.942   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:06:10.942  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:10.942  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:06:10.942  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:10.942   751  2440 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
08-23 17:06:10.942   751  2440 D BatteryService: stay LED for fully charged
,08-23 17:06:10.962  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:10.962  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:06:10.972  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:10.972  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:10.972  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:14.812   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:06:14.822   751  3426 D SSRM:n  : SIOP:: AP = 330, PST = 358, CUR = 350, LCD = 0
,08-23 17:06:21.002   751  3780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:21.002   751  3780 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:06:21.002   751  3780 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:06:21.012   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:21.022   751   751 I MotionRecognitionService: Plugged
,08-23 17:06:21.022   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:06:21.022   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:06:21.032   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:06:21.032   751  3780 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:06:21.042   751  3780 D BatteryService: stay LED for fully charged
,08-23 17:06:21.042  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:21.042  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:06:21.042  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:21.052  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:21.062  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:06:21.062  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:21.072  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:21.072  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:24.792   751  1574 E Watchdog: !@Sync 7 [08-23 17:06:24.792]
,08-23 17:06:24.882   751  3426 D SSRM:n  : SIOP:: AP = 330, PST = 350, CUR = 350, LCD = 0
,08-23 17:06:31.082   751   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:31.082   751   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:06:31.082   751   764 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:06:31.092   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:31.102   751   751 I MotionRecognitionService: Plugged
,08-23 17:06:31.102   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:06:31.102   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:06:31.112   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:06:31.112   751   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:06:31.122   751   764 D BatteryService: stay LED for fully charged
,08-23 17:06:31.132  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:31.132  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:31.142  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:31.152  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:31.152  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:06:31.162  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:31.162  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:31.162  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:34.822   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:06:34.942   751  3426 D SSRM:n  : SIOP:: AP = 330, PST = 343, CUR = 350, LCD = 0
,08-23 17:06:41.172   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:44.992   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 337, CUR = 350, LCD = 0
,08-23 17:06:51.262   751  1632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:51.262   751  1632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:06:51.262   751  1632 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:06:51.272   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:51.282   751   751 I MotionRecognitionService: Plugged
,08-23 17:06:51.282   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:06:51.282   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:06:51.292   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:06:51.292   751  1632 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 17:06:51.292   751  1632 D BatteryService: stay LED for fully charged
,08-23 17:06:51.292  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:51.292  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:06:51.292  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:51.312  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:51.312  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:06:51.322  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:51.322  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:06:51.322  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:06:54.792   751  1574 E Watchdog: !@Sync 8 [08-23 17:06:54.799]
,08-23 17:06:54.822   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:06:55.052   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 333, CUR = 350, LCD = 0
,08-23 17:06:55.812  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:06:56.072  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 2Kb duration : 255ms lastUpdatedAfter : 167192ms
,08-23 17:07:01.342   751  1663 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:01.342   751  1663 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:07:01.342   751  1663 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:07:01.352   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:01.362   751   751 I MotionRecognitionService: Plugged
,08-23 17:07:01.362   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:07:01.362   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:07:01.372   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:07:01.372   751  1663 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 17:07:01.382   751  1663 D BatteryService: stay LED for fully charged
,08-23 17:07:01.392  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:01.392  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:01.392  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:01.402  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:01.402  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:07:01.412  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:01.412  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:07:01.422  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:05.122   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 350, LCD = 0
,08-23 17:07:11.422   751  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:11.432   751  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:07:11.432   751  1623 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:07:11.432   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:11.452   751   751 I MotionRecognitionService: Plugged
,08-23 17:07:11.452   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:07:11.452   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:07:11.452   751  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 17:07:11.462   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:07:11.462   751  1623 D BatteryService: stay LED for fully charged
,08-23 17:07:11.482  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:11.482  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:11.482  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:11.502  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:11.502  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:07:11.512  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:11.512  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:11.512  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:14.832   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:07:15.192   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 328, CUR = 350, LCD = 0
,08-23 17:07:21.502   751  2440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:24.802   751  1574 E Watchdog: !@Sync 9 [08-23 17:07:24.804]
,08-23 17:07:25.262   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 350, LCD = 0
,08-23 17:07:31.592   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:31.592   751  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:07:31.592   751  1320 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:07:31.602   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:31.612   751   751 I MotionRecognitionService: Plugged
,08-23 17:07:31.612   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:07:31.612   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:07:31.622   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:07:31.622   751  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:07:31.632   751  1320 D BatteryService: stay LED for fully charged
,08-23 17:07:31.642  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:31.642  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:31.642  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:31.652  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:31.652  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:07:31.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:31.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:31.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:34.832   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:07:35.322   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 350, LCD = 0
,08-23 17:07:39.582   751  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:07:39.582   751  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:07:39.592   751  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:07:39.602   751  1231 I TLC_TIMA_PKM_initialize: initializing...
,08-23 17:07:39.602   751  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-23 17:07:39.612   751  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-23 17:07:39.612   751  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-23 17:07:39.612   751  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-23 17:07:39.612   751  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-23 17:07:39.612   751  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-23 17:07:39.622   751  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-23 17:07:39.622   751  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-23 17:07:39.622   751  1231 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:07:39.662   751  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,08-23 17:07:39.672   751  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-23 17:07:39.682   751  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-23 17:07:41.682   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:42.962   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:07:42.972   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:07:42.982   751  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:07:42.982   751  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:07:45.382   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 350, LCD = 0
,08-23 17:07:51.762   751  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:51.762   751  1424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:07:51.762   751  1424 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:07:51.772   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:51.782   751   751 I MotionRecognitionService: Plugged
,08-23 17:07:51.782   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:07:51.782   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:07:51.792   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:07:51.792   751  1424 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:07:51.792   751  1424 D BatteryService: stay LED for fully charged
,08-23 17:07:51.792  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:51.792  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:51.792  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:51.812  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:51.812  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:07:51.822  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:51.822  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:51.822  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:07:54.802   751  1574 E Watchdog: !@Sync 10 [08-23 17:07:54.808]
,08-23 17:07:54.832   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:07:55.442   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 350, LCD = 0
,08-23 17:07:56.082  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:07:57.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:07:57.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:07:57.452   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:08:01.852   751  1663 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:05.502   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 350, LCD = 0
,08-23 17:08:14.842   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:08:15.052   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:08:15.052   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:08:15.052   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:08:15.562   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-23 17:08:17.502   751  1237 V AlarmManager: Expired Alarm result :4
,08-23 17:08:17.552  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 17:08:17.562  1382  1382 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 17:08:17.562  1382  1382 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:08:17.612   751  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:17.612   751  1424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 17:08:17.612   751  1424 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:08:17.612   751  1424 D BatteryService: stay LED for fully charged
,08-23 17:08:17.612  1382  1382 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:08:17.622  1382  1382 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 17:08:17.622  1558  1558 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-23 17:08:17.622  1558  1558 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-23 17:08:17.642  1558  1558 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 17:08:17.662  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.662  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.662   751   751 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d915e85 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b51c75 4200:com.google.android.gms/u0a11}
,08-23 17:08:17.672  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.672  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.672  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.672  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.672  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.682   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:17.692  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:17.702  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:08:17.702   751   751 I MotionRecognitionService: Plugged
,08-23 17:08:17.702   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:08:17.702   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:08:17.702   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:08:17.722  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:17.722  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:17.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:17.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:08:17.722  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:17.722  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:17.782  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:08:17.822  4200  6975 I EventLogChimeraService: Aggregate from 1471963097253 (log), 1471963097253 (data)
,08-23 17:08:18.062   751   835 I ActivityManager: Start proc 6981:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-23 17:08:18.062  6981  6981 E Zygote  : v2
,08-23 17:08:18.072  6981  6981 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:08:18.072  6981  6981 I libpersona: KNOX_SDCARD not a persona
,08-23 17:08:18.072  6981  6981 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:08:18.072  6981  6981 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:08:18.072  6981  6981 E Zygote  : accessInfo : 0
,08-23 17:08:18.142  6981  6981 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:08:18.142  6981  6981 D ActivityThread: Added TimaKeyStore provider
,08-23 17:08:18.162   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{48884a6 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ef3ee7 6981:com.samsung.android.sm/1000}
,08-23 17:08:18.172  6981  6981 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-23 17:08:18.272   751  2070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{48884a6 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b51c75 4200:com.google.android.gms/u0a11}
,08-23 17:08:18.302   751  1663 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201d93d u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ef3ee7 6981:com.samsung.android.sm/1000}
,08-23 17:08:18.342   751  1632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201d93d u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b51c75 4200:com.google.android.gms/u0a11}
,08-23 17:08:18.542  4200  6993 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 17:08:18.592  4200  6993 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 17:08:18.592   751  2070 I ActivityManager: Killing 5973:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-23 17:08:18.632   751  1424 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-23 17:08:19.512  4902  4932 I PlayCommon: [669] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 17:08:19.572  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:08:19.612  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:08:19.612  2042  2042 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:08:19.682  4902  4932 I PlayCommon: [669] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-23 17:08:19.682  4902  4932 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:08:19.682  4902  4932 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:08:19.682   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:08:19.682   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:08:19.682   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:08:19.692   307  1199 D EnterpriseController: netId is 0
08-23 17:08:19.692   307  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-23 17:08:20.322  4902  4932 I PlayCommon: [669] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-23 17:08:21.422  1558  1558 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
,08-23 17:08:21.422   307  1196 D Netd    : Iface wlan0 link up
,08-23 17:08:21.432   751   846 D Tethering: interfaceLinkStateChanged wlan0, true
,08-23 17:08:21.442   751   846 D Tethering: interfaceStatusChanged wlan0, true
,08-23 17:08:21.452  1558  1558 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-23 17:08:21.462   751  1324 D WifiP2pService: InactiveState{ what=147461 }
,08-23 17:08:21.462   751  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-23 17:08:21.462   751  1324 D WifiP2pService: DefaultState{ what=147461 }
,08-23 17:08:21.522   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8185ee2 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ba8676 1382:com.android.systemui/u0a58}
,08-23 17:08:24.802   751  1574 E Watchdog: !@Sync 11 [08-23 17:08:24.812]
,08-23 17:08:25.622   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-23 17:08:27.672   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:27.672   751  2070 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:08:27.672   751  2070 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:08:27.682   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:27.692   751   751 I MotionRecognitionService: Plugged
,08-23 17:08:27.692   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:08:27.702   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:08:27.702   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:08:27.702   751  2070 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:08:27.712   751  2070 D BatteryService: stay LED for fully charged
,08-23 17:08:27.712  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:27.712  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:08:27.712  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:27.732  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:27.732  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:08:27.742  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:27.742  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:08:27.742  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:34.842   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:08:35.682   751  3426 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-23 17:08:37.752   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:45.732   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 350, LCD = 0
,08-23 17:08:47.842   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:47.842   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:08:47.842   751  1490 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:08:47.852   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:47.862   751   751 I MotionRecognitionService: Plugged
,08-23 17:08:47.862   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:08:47.862   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:08:47.862   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:08:47.872   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 17:08:47.872   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:08:47.882  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:47.882  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:47.882  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:47.912  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:47.912  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:08:47.922  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:47.922  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:08:47.922  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:08:48.332   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:08:48.332   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:08:48.332   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:08:54.812   751  1574 E Watchdog: !@Sync 12 [08-23 17:08:54.815]
,08-23 17:08:54.842   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:08:55.802   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 350, LCD = 0
,08-23 17:08:56.222  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:08:57.912   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:59.992   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:09:05.852   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 350, LCD = 0
,08-23 17:09:08.012   751  2440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:09:08.022   751  2440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:09:08.022   751  2440 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:09:08.022   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:09:08.042   751   751 I MotionRecognitionService: Plugged
,08-23 17:09:08.042   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:09:08.042   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:09:08.042   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:09:08.052   751  2440 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 17:09:08.052   751  2440 D BatteryService: stay LED for fully charged
,08-23 17:09:08.062  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:09:08.062  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:09:08.062  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:09:08.072  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:09:08.072  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:09:08.082  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:09:08.082  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:09:08.082  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:09:14.852   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:09:15.912   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 350, LCD = 0
,08-23 17:09:24.812   751  1574 E Watchdog: !@Sync 13 [08-23 17:09:24.819]
,08-23 17:09:25.972   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 350, LCD = 0
,08-23 17:09:28.912   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:09:28.912   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:09:28.912   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:09:34.852   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:09:36.022   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 350, LCD = 0
,08-23 17:09:38.092   751   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:09:38.102   751   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:09:38.102   751   764 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:09:38.102   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:09:38.122   751   751 I MotionRecognitionService: Plugged
,08-23 17:09:38.122   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:09:38.122   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:09:38.122   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:09:38.132   751   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:09:38.132   751   764 D BatteryService: stay LED for fully charged
,08-23 17:09:38.152  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:09:38.152  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:09:38.162  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:09:38.172  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:09:38.172  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:09:38.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:09:38.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:09:38.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:09:46.082   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 350, LCD = 0
,08-23 17:09:47.852   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:09:47.852   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:09:47.852   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:09:54.822   751  1574 E Watchdog: !@Sync 14 [08-23 17:09:54.827]
,08-23 17:09:54.852   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:09:56.142   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 350, LCD = 0
,08-23 17:09:56.282  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:09:56.472  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 178ms lastUpdatedAfter : 180398ms
,08-23 17:10:06.202   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-23 17:10:08.162   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:08.162   751  2070 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:10:08.162   751  2070 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:10:08.172   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:10:08.182   751   751 I MotionRecognitionService: Plugged
,08-23 17:10:08.182   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:10:08.182   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:10:08.192   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:10:08.192   751  2070 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:10:08.192   751  2070 D BatteryService: stay LED for fully charged
,08-23 17:10:08.212  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:10:08.212  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:10:08.212  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:10:08.222  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:10:08.222  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:10:08.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:10:08.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:10:08.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:10:14.862   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:10:16.262   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:10:24.822   751  1574 E Watchdog: !@Sync 15 [08-23 17:10:24.831]
,08-23 17:10:26.322   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:10:29.222   371   371 I bootchecker: bootchecker wake up!!
,08-23 17:10:34.862   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:10:36.372   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:10:38.232   751  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:38.242   751  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:10:38.242   751  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:10:38.242   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:10:38.262   751   751 I MotionRecognitionService: Plugged
,08-23 17:10:38.262   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:10:38.262   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:10:38.262   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:10:38.272   751  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 17:10:38.272   751  1791 D BatteryService: stay LED for fully charged
,08-23 17:10:38.282  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:10:38.282  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:10:38.282  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:10:38.312  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:10:38.312  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:10:38.312  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:10:38.312  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:10:38.312  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:10:46.422   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:10:54.832   751  1574 E Watchdog: !@Sync 16 [08-23 17:10:54.836]
,08-23 17:10:54.872   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:10:56.492   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:10:56.572  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:11:06.552   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:11:08.302   751  3780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:08.312   751  3780 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:11:08.312   751  3780 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:11:08.312   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:11:08.322   751   751 I MotionRecognitionService: Plugged
,08-23 17:11:08.332   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:11:08.332   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:11:08.332   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:11:08.342   751  3780 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 17:11:08.342   751  3780 D BatteryService: stay LED for fully charged
,08-23 17:11:08.362  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:11:08.362  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:11:08.362  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:11:08.372  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:11:08.372  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:11:08.382  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:11:08.382  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:11:08.382  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:11:14.872   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:16.602   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:11:24.832   751  1574 E Watchdog: !@Sync 17 [08-23 17:11:24.840]
,08-23 17:11:26.662   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:11:32.072   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:11:32.072   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:11:32.072   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:11:34.872   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:36.722   751  3426 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-23 17:11:38.372   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:38.382   751  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:11:38.382   751  1722 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:11:38.382   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:11:38.392   751   751 I MotionRecognitionService: Plugged
,08-23 17:11:38.402   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:11:38.402   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:11:38.402   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:11:38.412   751  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 17:11:38.412   751  1722 D BatteryService: stay LED for fully charged
,08-23 17:11:38.412  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:11:38.412  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:11:38.412  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:11:38.422  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:11:38.432  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:11:38.442  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:11:38.442  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:11:38.442  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:11:46.792   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 350, LCD = 0
,08-23 17:11:47.092   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:11:47.092   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:11:47.092   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:11:54.842   751  1574 E Watchdog: !@Sync 18 [08-23 17:11:54.845]
,08-23 17:11:54.882   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:56.602  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:11:56.872   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 350, LCD = 0
,08-23 17:12:06.932   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 350, LCD = 0
,08-23 17:12:08.442   751  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:08.452   751  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:12:08.452   751  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:12:08.452   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:12:08.462   751   751 I MotionRecognitionService: Plugged
,08-23 17:12:08.472   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:12:08.472   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:12:08.472   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:12:08.482   751  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 17:12:08.482   751  1791 D BatteryService: stay LED for fully charged
,08-23 17:12:08.502  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:08.502  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:08.502  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:12:08.522  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:12:08.522  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:12:08.532  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:12:08.532  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:12:08.532  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:12:14.882   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:16.992   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 350, LCD = 0
,08-23 17:12:20.312   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:12:20.312   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:12:20.312   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:12:24.842   751  1574 E Watchdog: !@Sync 19 [08-23 17:12:24.849]
,08-23 17:12:27.052   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 350, LCD = 0
,08-23 17:12:34.892   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:35.372   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:12:35.372   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:12:35.372   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:12:37.112   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-23 17:12:38.512   751   765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:38.522   751   765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:12:38.522   751   765 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:12:38.522   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:12:38.532   751   751 I MotionRecognitionService: Plugged
,08-23 17:12:38.542   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:12:38.542   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:12:38.542   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:12:38.552   751   765 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:12:38.552   751   765 D BatteryService: stay LED for fully charged
,08-23 17:12:38.562  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:38.562  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:12:38.562  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:12:38.572  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:12:38.572  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:12:38.582  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:12:38.582  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:12:38.592  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:12:39.572   751  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:12:39.572   751  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:12:39.572   751  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:12:41.032   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:12:41.032   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:12:41.042   751  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:12:41.052   751  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:12:47.172   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 350, LCD = 0
,08-23 17:12:54.852   751  1574 E Watchdog: !@Sync 20 [08-23 17:12:54.853]
,08-23 17:12:54.892   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:56.622  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:12:56.792  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 155ms lastUpdatedAfter : 180318ms
,08-23 17:12:57.222   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 350, LCD = 0
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.412   751   831 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.422   751   831 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLo,cked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.432   751   831 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 17:12:59.442   751   831 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 17:12:59.512   751   891 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,08-23 17:12:59.522   751   891 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,08-23 17:13:07.302   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 350, LCD = 0
,08-23 17:13:08.582   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:14.902   751  3464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:13:17.352   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:13:20.342   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:13:20.342   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:13:20.342   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:13:20.362   751  1623 I ActivityManager: Killing 4667:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 603s, lastActivityTime 603s
,08-23 17:13:20.372   751  1623 I ActivityManager: Killing 3883:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 608s, lastActivityTime 608s
,08-23 17:13:20.432   293   293 I ServiceManager: service 'AtCmdFwd' died
,08-23 17:13:20.442   375  4888 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-23 17:13:20.442   375  4888 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:13:20.452   751  1632 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-23 17:13:20.452   751  1632 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
,08-23 17:13:20.452   751  1632 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-23 17:13:20.482   751  1663 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-23 17:13:20.482   751  1663 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
,08-23 17:13:20.482   751  1663 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10971ms
,08-23 17:13:21.442   375  4888 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:13:21.512   751   835 I ActivityManager: Start proc 7040:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-23 17:13:21.522  7040  7040 E Zygote  : v2
,08-23 17:13:21.522  7040  7040 I libpersona: KNOX_SDCARD checking this for 1000
,08-23 17:13:21.522  7040  7040 I libpersona: KNOX_SDCARD not a persona
,08-23 17:13:21.522  7040  7040 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:13:21.532  7040  7040 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:13:21.532  7040  7040 E Zygote  : accessInfo : 0
,08-23 17:13:21.572  7040  7040 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:13:21.572  7040  7040 D ActivityThread: Added TimaKeyStore provider
,08-23 17:13:21.592  7040  7040 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-23 17:13:21.612  7040  7040 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-23 17:13:21.612  7040  7040 D AtFwdService: onCreate method
,08-23 17:13:21.612  7040  7040 I AtFwdService: Instantiate AtCmdFwd Service
,08-23 17:13:21.632  7040  7052 D AtCkpdCmdHandler: De-queing command
,08-23 17:13:24.852   751  1574 E Watchdog: !@Sync 21 [08-23 17:13:24.858]
,08-23 17:13:27.412   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:13:31.512   751   835 I ActivityManager: Start proc 7054:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-23 17:13:31.522  7054  7054 E Zygote  : v2
,08-23 17:13:31.522  7054  7054 I libpersona: KNOX_SDCARD checking this for 10026
08-23 17:13:31.522  7054  7054 I libpersona: KNOX_SDCARD not a persona
,08-23 17:13:31.522  7054  7054 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:13:31.522  7054  7054 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:13:31.532  7054  7054 E Zygote  : accessInfo : 0
,08-23 17:13:31.532  7054  7054 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-23 17:13:31.582  7054  7054 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:13:31.582  7054  7054 D ActivityThread: Added TimaKeyStore provider
,08-23 17:13:31.602  7054  7054 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-23 17:13:31.622  7054  7054 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-23 17:13:31.632  7054  7054 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-23 17:13:31.642  7054  7054 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-23 17:13:35.492   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 17:13:35.492   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 17:13:35.492   307  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 17:13:37.482   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:13:38.652   751  1632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:38.662   751  1632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:13:38.662   751  1632 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:13:38.662   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:13:38.672   751   751 I MotionRecognitionService: Plugged
,08-23 17:13:38.682   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:13:38.682   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:13:38.682   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:13:38.692   751  1632 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:13:38.692   751  1632 D BatteryService: stay LED for fully charged
,08-23 17:13:38.702  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:13:38.712  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:13:38.712  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:13:38.722  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:13:38.722  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:13:38.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:13:38.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:13:38.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:13:43.612   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:13:47.532   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:13:54.862   751  1574 E Watchdog: !@Sync 22 [08-23 17:13:54.863]
,08-23 17:13:56.822  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:13:57.592   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:07.642   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:08.722   751  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:08.722   751  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:14:08.732   751  1623 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:14:08.732   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:14:08.742   751   751 I MotionRecognitionService: Plugged
,08-23 17:14:08.742   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:14:08.752   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:14:08.752   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:14:08.762   751  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 17:14:08.762   751  1623 D BatteryService: stay LED for fully charged
,08-23 17:14:08.762  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:14:08.762  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:14:08.762  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:14:08.772  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:14:08.782  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:14:08.792  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:08.792  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:08.792  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:17.702   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:24.862   751  1574 E Watchdog: !@Sync 23 [08-23 17:14:24.868]
,08-23 17:14:27.752   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:37.802   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:38.792   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:38.792   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:14:38.802   751  1490 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:14:38.802   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:14:38.812   751   751 I MotionRecognitionService: Plugged
,08-23 17:14:38.812   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:14:38.822   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:14:38.822   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:14:38.822   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:14:38.832   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:14:38.842  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:14:38.852  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:14:38.852  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:14:38.872  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:14:38.872  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:14:38.882  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:38.882  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:38.882  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:14:47.852   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:14:54.872   751  1574 E Watchdog: !@Sync 24 [08-23 17:14:54.873]
,08-23 17:14:56.932  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:14:57.912   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:07.962   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:08.862   751  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:08.872   751  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:15:08.872   751  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:15:08.872   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:08.882   751   751 I MotionRecognitionService: Plugged
,08-23 17:15:08.882   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:15:08.892   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:15:08.892   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:15:08.902   751  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 17:15:08.902   751  1791 D BatteryService: stay LED for fully charged
,08-23 17:15:08.912  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:08.912  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:15:08.912  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:15:08.932  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:15:08.932  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:15:08.942  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:15:08.952  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:15:08.952  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:15:18.062   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:18.162   751   761 I art     : Background sticky concurrent mark sweep GC freed 85825(8MB) AllocSpace objects, 332(6MB) LOS objects, 26% free, 42MB/58MB, paused 2.776ms total 142.180ms
,08-23 17:15:24.872   751  1574 E Watchdog: !@Sync 25 [08-23 17:15:24.877]
,08-23 17:15:28.122   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:38.172   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:38.932   751  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:38.942   751  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:15:38.942   751  1726 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:15:38.942   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:38.952   751   751 I MotionRecognitionService: Plugged
,08-23 17:15:38.962   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:15:38.962   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:15:38.962   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:15:38.972   751  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:15:38.972   751  1726 D BatteryService: stay LED for fully charged
,08-23 17:15:38.982  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:38.982  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:38.982  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:15:39.012  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:15:39.012  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:15:39.012  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:15:39.012  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:15:39.012  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:15:48.232   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:54.872   751  1574 E Watchdog: !@Sync 26 [08-23 17:15:54.881]
,08-23 17:15:56.992  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:15:57.192  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 181ms lastUpdatedAfter : 180396ms
,08-23 17:15:58.282   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:15:59.492   751  2405 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-23 17:15:59.492   751  2405 V MARsPolicyManager: updateSMDBValues
,08-23 17:15:59.502   751   888 E MARsDBManager: updateDBAll : begin --size 1
,08-23 17:15:59.522   751   888 I ActivityManager: Killing 1861:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 781s, lastActivityTime 706s
,08-23 17:15:59.532   751   888 I ActivityManager: Killing 6315:com.samsung.android.sdk.samsunglink/u0a41 (adj 8): SSR - service for lastStateTime 711s, lastActivityTime 711s
,08-23 17:15:59.542   751   888 I ActivityManager: Killing 3783:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 767s, lastActivityTime 732s
,08-23 17:15:59.542   751   888 I ActivityManager: Killing 1513:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 733s, lastActivityTime 733s
,08-23 17:15:59.582   751   888 E MARsDBManager: updateDBAll : end
,08-23 17:15:59.582   751   888 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-23 17:15:59.662   751   764 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,08-23 17:15:59.662   751   764 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,08-23 17:15:59.672  6658  6658 D HealthConsole: Service for HealthDataStore is disconnected
,08-23 17:15:59.682   751  2440 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
08-23 17:15:59.682   751  2440 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
,08-23 17:15:59.682   751  2440 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,08-23 17:15:59.692   751   765 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
08-23 17:15:59.692   751   765 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,08-23 17:15:59.712   751  1424 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-23 17:15:59.712   751  1424 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-23 17:15:59.712   751  1424 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10971ms
08-23 17:15:59.712   751  1424 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-23 17:15:59.712   751  1424 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 20971ms
,08-23 17:15:59.752   751  1722 I ActivityManager: Start proc 7088:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,08-23 17:15:59.752  7088  7088 E Zygote  : v2
08-23 17:15:59.752  7088  7088 I libpersona: KNOX_SDCARD checking this for 10034
08-23 17:15:59.752  7088  7088 I libpersona: KNOX_SDCARD not a persona
,08-23 17:15:59.762  7088  7088 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:15:59.762  7088  7088 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:15:59.772  7088  7088 E Zygote  : accessInfo : 0,
08-23 17:15:59.772  7088  7088 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,08-23 17:15:59.832  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:15:59.832  7088  7088 D ActivityThread: Added TimaKeyStore provider
,08-23 17:15:59.862  7088  7088 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-23 17:15:59.882  7088  7088 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-23 17:15:59.902  7088  7088 I MultiDex: VM with version 2.1.0 has multidex support
08-23 17:15:59.902  7088  7088 I MultiDex: install
08-23 17:15:59.902  7088  7088 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 17:15:59.902  7088  7088 I MultiDex: install
08-23 17:15:59.902  7088  7088 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 17:16:00.112   751  1791 I ActivityManager: Start proc 7109:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,08-23 17:16:00.112  7109  7109 E Zygote  : v2
08-23 17:16:00.112  7109  7109 I libpersona: KNOX_SDCARD checking this for 10016
08-23 17:16:00.112  7109  7109 I libpersona: KNOX_SDCARD not a persona
,08-23 17:16:00.112  7109  7109 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 17:16:00.112  7109  7109 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:16:00.112  7109  7109 E Zygote  : accessInfo : 0
,08-23 17:16:00.112  7109  7109 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,08-23 17:16:00.182  7109  7109 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:16:00.182  7109  7109 D ActivityThread: Added TimaKeyStore provider
,08-23 17:16:00.222  7109  7109 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,08-23 17:16:00.282  7088  7088 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-23 17:16:00.282  7088  7088 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-23 17:16:00.342  1382  1382 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,08-23 17:16:00.352   751  1632 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,08-23 17:16:00.372   751  2070 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,08-23 17:16:00.372   751   764 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,08-23 17:16:00.382  1382  1382 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{edbbbaa VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,08-23 17:16:00.382  1382  1382 D AdaptiveEventManager: M updateContainers()
08-23 17:16:00.382  1382  1382 D AdaptiveEventContainerSmall: C updatePedoContainer()
08-23 17:16:00.382  1382  1382 D AdaptiveEventContainerSmall: handlePedoUpdate()
,08-23 17:16:00.382   751  2440 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,08-23 17:16:00.382  1382  1382 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,08-23 17:16:00.422  7088  7088 I Health.HealthService: HealthService: onCreate() start (7088)
,08-23 17:16:00.582  6658  6658 D HealthDataStore: Service for HealthDataStore is connected
,08-23 17:16:00.582  6658  6658 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-23 17:16:00.602   751  1722 I ActivityManager: Killing 6018:com.android.email/u0a162 (adj 15): DHA:empty #37
,08-23 17:16:00.622  6658  6658 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-23 17:16:00.622  6658  6658 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 17:16:00.662   751  1791 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,08-23 17:16:00.692  7132  7132 E Zygote  : v2
08-23 17:16:00.692  7132  7132 I libpersona: KNOX_SDCARD checking this for 10181
08-23 17:16:00.692  7132  7132 I libpersona: KNOX_SDCARD not a persona
08-23 17:16:00.692   751   835 I ActivityManager: Start proc 7132:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,08-23 17:16:00.702   751  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 17:16:00.702  7132  7132 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 17:16:00.702  7132  7132 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 17:16:00.702  7132  7132 E Zygote  : accessInfo : 0
08-23 17:16:00.702  7132  7132 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,08-23 17:16:00.702  7088  7088 D HealthDataStore: Service for HealthDataStore is connected
,08-23 17:16:00.702  7088  7088 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-23 17:16:00.712  7088  7088 D HealthConsole: Service for HealthDataConsole is connected
,08-23 17:16:00.722  7088  7088 D HealthDataStore: Trying to connect with Health Service fails (error code: 9),
08-23 17:16:00.732  7088  7088 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 17:16:00.742  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:16:00.742  7132  7132 D ActivityThread: Added TimaKeyStore provider
,08-23 17:16:00.762   751  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-23 17:16:00.772  7132  7132 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,08-23 17:16:00.792  7132  7132 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,08-23 17:16:00.822  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,08-23 17:16:00.832  7132  7132 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 17:16:00.842   751   835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{99cbc89 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{424348e 7132:com.sec.android.daemonapp/u0a181}
,08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 17:16:00.862  7088  7124 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
08-23 17:16:00.862  7132  7132 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 17:16:00.892  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:00.892  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-23 17:16:00.892  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,08-23 17:16:00.902  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:00.902  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 17:16:00.902  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,08-23 17:16:00.902  7088  7146 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,08-23 17:16:00.912  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-23 17:16:00.932  7109  7120 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-23 17:16:00.942  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,08-23 17:16:00.942   437   437 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7109
08-23 17:16:00.942   437   437 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,08-23 17:16:00.942  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:00.942  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 17:16:00.952  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,08-23 17:16:00.952  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-23 17:16:00.952  7132  7132 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 17:16:00.962  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 17:16:00.962  7132  7132 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-23 17:16:00.962  7132  7132 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 17:16:00.962  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:00.962  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 17:16:00.972   751  1490 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2330b9a u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{424348e 7132:com.sec.android.daemonapp/u0a181}
,08-23 17:16:00.982  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:00.982  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 17:16:00.982  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 17:16:00.982  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 17:16:00.992  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 17:16:00.992  7132  7132 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 17:16:00.992  7132  7132 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 17:16:00.992  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:00.992  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 17:16:01.002   751  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{610ccb u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{424348e 7132:com.sec.android.daemonapp/u0a181}
,08-23 17:16:01.012  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:01.012  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 17:16:01.012  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 17:16:01.012  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 17:16:01.022  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 17:16:01.022  7132  7132 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 17:16:01.022  7132  7132 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 17:16:01.022  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:01.022  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 17:16:01.032   751  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3a7ca8 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{424348e 7132:com.sec.android.daemonapp/u0a181}
,08-23 17:16:01.032  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 17:16:01.032  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 17:16:01.032  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 17:16:01.032  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 17:16:01.042  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 17:16:01.042  7132  7132 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 17:16:01.042  7132  7132 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 17:16:01.042  7132  7132 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 17:16:01.042  7132  7132 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 17:16:01.132  7109  7120 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,08-23 17:16:01.182  7088  7146 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,08-23 17:16:01.312  7088  7146 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-23 17:16:01.312  7088  7146 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-23 17:16:01.562   437   437 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,08-23 17:16:01.612  7109  7120 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,08-23 17:16:01.612  7109  7120 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,08-23 17:16:01.622  7109  7120 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,08-23 17:16:08.342   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:16:09.012   751  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:09.012   751  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:16:09.012   751  1623 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:16:09.022   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:16:09.042   751  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-23 17:16:09.042   751  1623 D BatteryService: stay LED for fully charged
,08-23 17:16:09.052   751   751 I MotionRecognitionService: Plugged
,08-23 17:16:09.062   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:16:09.062   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:16:09.062   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:16:09.062  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:16:09.062  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:16:09.062  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:09.072  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:16:09.082  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:16:09.092  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:16:09.092  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:16:09.092  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:16:18.402   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:16:24.882   751  1574 E Watchdog: !@Sync 27 [08-23 17:16:24.887]
,08-23 17:16:28.452   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:16:38.512   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:16:39.072   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:39.082   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:16:39.082   751  1490 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:16:39.082   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:16:39.092   751   751 I MotionRecognitionService: Plugged
,08-23 17:16:39.102   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:16:39.102   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:16:39.102   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:16:39.112   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
08-23 17:16:39.112   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:16:39.112  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:16:39.112  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:16:39.112  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:39.132  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:16:39.132  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:16:39.142  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:16:39.142  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:16:39.142  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:16:48.562   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:16:54.892   751  1574 E Watchdog: !@Sync 28 [08-23 17:16:54.897]
,08-23 17:16:57.292  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:16:58.612   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:08.672   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:09.142   751  3780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:09.142   751  3780 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:17:09.152   751  3780 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:17:09.152   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:17:09.172   751   751 I MotionRecognitionService: Plugged
,08-23 17:17:09.172   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:17:09.172   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:17:09.172   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:17:09.182   751  3780 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 40ms
,08-23 17:17:09.192   751  3780 D BatteryService: stay LED for fully charged
,08-23 17:17:09.202  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:17:09.202  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:17:09.202  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:17:09.222  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:17:09.222  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:17:09.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:17:09.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:17:09.232  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:17:18.722   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:24.892   751  1574 E Watchdog: !@Sync 29 [08-23 17:17:24.901]
,08-23 17:17:28.782   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:38.832   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:39.212   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:39.572   751  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:17:39.572   751  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:17:39.572   751  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:17:42.912   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:17:42.912   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:17:42.922   751  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:17:42.932   751  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:17:48.892   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:17:54.902   751  1574 E Watchdog: !@Sync 30 [08-23 17:17:54.907]
,08-23 17:17:57.322  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:17:58.952   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:01.622   751  1237 V AlarmManager: Expired Alarm result :4
,08-23 17:18:01.662  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 17:18:01.662  1382  1382 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 17:18:01.672  1382  1382 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:18:01.712  1382  1382 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:18:01.712  1382  1382 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 17:18:01.722  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.722   751   835 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,08-23 17:18:01.742  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.752  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.752  2297  2482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 17:18:01.752  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.752  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 17:18:01.762  2297  2482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 17:18:01.762  2297  2482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 17:18:01.762  2297  2482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 17:18:01.762  2297  2519 D bt_upio : upio_start_stop_timer : timer_settime success
,08-23 17:18:01.762  2297  2519 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-23 17:18:01.772  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.772  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.772  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.772  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.772  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.772  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.772  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.772  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.772  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.772  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.772  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.772  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.772  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.772  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.772  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.782  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 17:18:01.782  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.782  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.782  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 17:18:01.782  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.782  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.782  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.792  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.792  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.792  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.802  2297  2519 D bt_vendor: op for 7
,08-23 17:18:01.802  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.802  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.802  2297  2519 D bt_vendor: op for 7
08-23 17:18:01.802  2297  2519 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 17:18:01.802  2297  2519 D bt_upio : BT_WAKE is asserted already
,08-23 17:18:01.802  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.812  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.812  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.812  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.822   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{6bf73f2: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.822   751  1663 V AlarmManager:  remove PendingIntent] PendingIntent{4044a43: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.842   751  2070 V AlarmManager:  remove PendingIntent] PendingIntent{74638c0: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.852   751   765 V AlarmManager:  remove PendingIntent] PendingIntent{2b0d9f9: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.852   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{74cdd3e: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.862   751  1722 V AlarmManager:  remove PendingIntent] PendingIntent{317479f: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.872   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{cb620ec: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.882   751   765 V AlarmManager:  remove PendingIntent] PendingIntent{a1c1cb5: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.882  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 17:18:01.892   751  1490 V AlarmManager:  remove PendingIntent] PendingIntent{7b58f4a: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.902   751  3780 V AlarmManager:  remove PendingIntent] PendingIntent{732bebb: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.912   751  1722 V AlarmManager:  remove PendingIntent] PendingIntent{65a5fd8: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.912   751   764 V AlarmManager:  remove PendingIntent] PendingIntent{6becf31: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.912   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{3455616: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.922   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{fc48b97: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.922   751  1791 V AlarmManager:  remove PendingIntent] PendingIntent{701a184: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.932   751  2440 V AlarmManager:  remove PendingIntent] PendingIntent{b002d6d: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.932   751  3780 V AlarmManager:  remove PendingIntent] PendingIntent{c38bda2: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.932   751  1722 V AlarmManager:  remove PendingIntent] PendingIntent{b3c4a33: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.942   751   764 V AlarmManager:  remove PendingIntent] PendingIntent{db951f0: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.942   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{e7f3369: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.952   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{a0911ee: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.952   751  1791 V AlarmManager:  remove PendingIntent] PendingIntent{567568f: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.962   751  1663 V AlarmManager:  remove PendingIntent] PendingIntent{af99d1c: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.962   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{9ce9d25: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.962   751  1632 V AlarmManager:  remove PendingIntent] PendingIntent{785efa: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.962   751  1722 V AlarmManager:  remove PendingIntent] PendingIntent{f8cccab: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.972   751  1490 V AlarmManager:  remove PendingIntent] PendingIntent{c916f08: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.972   751  2440 V AlarmManager:  remove PendingIntent] PendingIntent{1f0e6a1: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.972   751   765 V AlarmManager:  remove PendingIntent] PendingIntent{b5d70c6: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.972   751  1424 V AlarmManager:  remove PendingIntent] PendingIntent{e498887: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.982   751  1726 V AlarmManager:  remove PendingIntent] PendingIntent{c5273b4: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.982   751   764 V AlarmManager:  remove PendingIntent] PendingIntent{f944bdd: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.982   751  1320 V AlarmManager:  remove PendingIntent] PendingIntent{b2fd352: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.982   751  3780 V AlarmManager:  remove PendingIntent] PendingIntent{92c2623: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.992   751  2070 V AlarmManager:  remove PendingIntent] PendingIntent{d7d1720: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.992   751  1791 V AlarmManager:  remove PendingIntent] PendingIntent{e0ec8d9: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.992   751  1663 V AlarmManager:  remove PendingIntent] PendingIntent{e53d29e: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.992   751  1623 V AlarmManager:  remove PendingIntent] PendingIntent{811017f: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:01.992   751  1632 V AlarmManager:  remove PendingIntent] PendingIntent{4ec854c: PendingIntentRecord{b518afd com.android.bluetooth broadcastIntent}}
,08-23 17:18:02.562  2297  2725 D bt_upio : ..proc_btwrite_timeout..
,08-23 17:18:02.562  2297  2725 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-23 17:18:09.002   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:09.282   751   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:18:09.292   751   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:18:09.292   751   764 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:18:09.292   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:18:09.312   751   751 I MotionRecognitionService: Plugged
,08-23 17:18:09.312   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:18:09.312   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:18:09.322   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:18:09.332   751   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 43ms
,08-23 17:18:09.332   751   764 D BatteryService: stay LED for fully charged
,08-23 17:18:09.342  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:18:09.342  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:18:09.342  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:18:09.362  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:18:09.362  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:18:09.372  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:09.372  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:09.372  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:17.622   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:18:19.052   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:24.912   751  1574 E Watchdog: !@Sync 31 [08-23 17:18:24.912]
,08-23 17:18:29.112   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:39.162   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:39.362   751   765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:18:39.362   751   765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:18:39.372   751   765 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:18:39.372   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:18:39.382   751   751 I MotionRecognitionService: Plugged
,08-23 17:18:39.382   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:18:39.392   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:18:39.392   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:18:39.392   751   765 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:18:39.402   751   765 D BatteryService: stay LED for fully charged
,08-23 17:18:39.402  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:18:39.402  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:18:39.402  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:18:39.412  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:18:39.422  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:18:39.432  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:39.432  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:39.432  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:18:49.222   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:54.912   751  1574 E Watchdog: !@Sync 32 [08-23 17:18:54.919]
,08-23 17:18:57.442  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:18:57.632  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 171ms lastUpdatedAfter : 180443ms
,08-23 17:18:59.302   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:18:59.992   751  1237 V AlarmManager: Expired Alarm result :8
,08-23 17:19:09.372   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:19:09.452   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:19.422   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:19:24.922   751  1574 E Watchdog: !@Sync 33 [08-23 17:19:24.925]
,08-23 17:19:29.482   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:19:39.522   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:39.522   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:19:39.532   751  1490 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:19:39.532   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:19:39.542   751   751 I MotionRecognitionService: Plugged
,08-23 17:19:39.542   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:19:39.552   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:19:39.552   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:19:39.552   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:19:39.562   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:19:39.572  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:19:39.582  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:19:39.582  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:19:39.612  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:19:39.612  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:19:39.612  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:19:39.612  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:19:39.612  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:19:39.632   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:19:49.682   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:19:54.922   751  1574 E Watchdog: !@Sync 34 [08-23 17:19:54.929]
,08-23 17:19:57.642  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:19:59.752   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:20:09.592   751  1663 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:09.812   751  3426 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-23 17:20:19.862   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 350, LCD = 0
,08-23 17:20:24.932   751  1574 E Watchdog: !@Sync 35 [08-23 17:20:24.936]
,08-23 17:20:29.922   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 350, LCD = 0
,08-23 17:20:39.662   751  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:39.672   751  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:20:39.672   751  1726 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:20:39.672   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:20:39.692   751   751 I MotionRecognitionService: Plugged
,08-23 17:20:39.692   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:20:39.692   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:20:39.692   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:20:39.702   751  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 17:20:39.702   751  1726 D BatteryService: stay LED for fully charged
,08-23 17:20:39.702  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:20:39.702  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:20:39.702  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:20:39.722  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:20:39.722  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:20:39.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:20:39.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:20:39.732  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:20:39.982   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 350, LCD = 0
,08-23 17:20:50.042   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 350, LCD = 0
,08-23 17:20:54.932   751  1574 E Watchdog: !@Sync 36 [08-23 17:20:54.941]
,08-23 17:20:57.702  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:21:00.092   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 350, LCD = 0
,08-23 17:21:09.742   751  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:10.152   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 350, LCD = 0
,08-23 17:21:20.212   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 350, LCD = 0
,08-23 17:21:24.942   751  1574 E Watchdog: !@Sync 37 [08-23 17:21:24.947]
,08-23 17:21:30.262   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 350, LCD = 0
,08-23 17:21:39.822   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:39.832   751  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:21:39.832   751  1320 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:21:39.832   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:21:39.852   751   751 I MotionRecognitionService: Plugged
,08-23 17:21:39.852   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:21:39.852   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:21:39.852   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:21:39.862   751  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 17:21:39.862   751  1320 D BatteryService: stay LED for fully charged
,08-23 17:21:39.872  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:21:39.872  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:21:39.872  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:21:39.902  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:21:39.902  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:21:39.902  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:21:39.902  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:21:39.902  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:21:40.322   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 350, LCD = 0
,08-23 17:21:50.382   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:21:54.942   751  1574 E Watchdog: !@Sync 38 [08-23 17:21:54.952]
,08-23 17:21:57.822  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:21:58.012  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 170ms lastUpdatedAfter : 180376ms
,08-23 17:22:00.432   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:09.902   751  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:09.912   751  1424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:22:09.912   751  1424 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:22:09.912   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:22:09.932   751   751 I MotionRecognitionService: Plugged
,08-23 17:22:09.932   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:22:09.932   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:22:09.942   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:22:09.942   751  1424 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-23 17:22:09.942   751  1424 D BatteryService: stay LED for fully charged
,08-23 17:22:09.952  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:22:09.952  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:22:09.952  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:22:09.962  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:22:09.962  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:22:09.972  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:22:09.982  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:22:09.982  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:22:10.482   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:20.542   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:24.952   751  1574 E Watchdog: !@Sync 39 [08-23 17:22:24.957]
,08-23 17:22:30.602   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:39.572   751  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:22:39.572   751  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:22:39.572   751  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:22:39.992   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:40.662   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:41.082   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:22:41.092   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:22:41.102   751  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:22:41.102   751  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:22:50.722   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:22:51.632   751   831 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 17:22:54.962   751  1574 E Watchdog: !@Sync 40 [08-23 17:22:54.962]
,08-23 17:22:58.082  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:23:00.782   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:10.042   751  1632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:10.832   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:20.332  4902  4932 I PlayCommon: [669] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 17:23:20.342  4902  4932 I PlayCommon: [669] com.google.android.play.a.al.e(732): No file ready to send
,08-23 17:23:20.882   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:24.962   751  1574 E Watchdog: !@Sync 41 [08-23 17:23:24.968]
,08-23 17:23:30.942   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:40.112   751  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:40.122   751  1424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:23:40.122   751  1424 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:23:40.122   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:23:40.142   751   751 I MotionRecognitionService: Plugged
,08-23 17:23:40.142   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:23:40.142   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:23:40.152   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:23:40.152   751  1424 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 17:23:40.152   751  1424 D BatteryService: stay LED for fully charged
,08-23 17:23:40.152  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:23:40.152  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:23:40.162  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:23:40.172  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:23:40.172  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:23:40.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:23:40.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:23:40.182  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:23:41.002   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:51.052   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:23:54.972   751  1574 E Watchdog: !@Sync 42 [08-23 17:23:54.973]
,08-23 17:23:58.112  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:24:01.102   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:10.192   751   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:10.192   751   764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:24:10.202   751   764 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:24:10.202   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:24:10.212   751   751 I MotionRecognitionService: Plugged
,08-23 17:24:10.222   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:24:10.222   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:24:10.222   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:24:10.232   751   764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-23 17:24:10.232   751   764 D BatteryService: stay LED for fully charged
,08-23 17:24:10.252  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:24:10.252  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:24:10.252  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:24:10.262  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:24:10.262  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:24:10.272  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:10.272  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:10.272  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:11.152   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:21.212   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:24.972   751  1574 E Watchdog: !@Sync 43 [08-23 17:24:24.978]
,08-23 17:24:31.302   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:40.272   751  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:40.272   751  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:24:40.282   751  1726 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:24:40.282   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:24:40.292   751   751 I MotionRecognitionService: Plugged
,08-23 17:24:40.292   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:24:40.302   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:24:40.302   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:24:40.302   751  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 17:24:40.312   751  1726 D BatteryService: stay LED for fully charged
,08-23 17:24:40.322  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:24:40.322  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:24:40.322  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:24:40.352  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:24:40.352  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:24:40.352  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:40.352  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:40.352  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:24:41.352   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:51.402   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:24:54.982   751  1574 E Watchdog: !@Sync 44 [08-23 17:24:54.983]
,08-23 17:24:58.132  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:24:58.332  1666  1746 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 185ms lastUpdatedAfter : 180318ms
,08-23 17:25:01.462   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:10.352   751  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:10.352   751  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:25:10.362   751  1490 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:25:10.362   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:25:10.372   751   751 I MotionRecognitionService: Plugged
,08-23 17:25:10.372   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:25:10.382   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:25:10.382   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:25:10.392   751  1490 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 17:25:10.392   751  1490 D BatteryService: stay LED for fully charged
,08-23 17:25:10.402  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:25:10.402  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:25:10.402  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:25:10.412  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:25:10.412  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:25:10.422  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:10.422  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:10.432  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:11.522   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:21.572   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:24.982   751  1574 E Watchdog: !@Sync 45 [08-23 17:25:24.988]
,08-23 17:25:31.632   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:40.432   751  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:40.432   751  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:25:40.442   751  1722 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:25:40.442   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:25:40.452   751   751 I MotionRecognitionService: Plugged
,08-23 17:25:40.452   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:25:40.462   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:25:40.462   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:25:40.462   751  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 17:25:40.472   751  1722 D BatteryService: stay LED for fully charged
,08-23 17:25:40.482  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:25:40.492  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:25:40.492  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:25:40.512  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:25:40.512  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:25:40.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:40.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:40.522  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:25:41.682   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:51.732   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:25:54.992   751  1574 E Watchdog: !@Sync 46 [08-23 17:25:54.993]
,08-23 17:25:58.342  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:26:01.792   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:10.512   751  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:11.852   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:21.902   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:24.992   751  1574 E Watchdog: !@Sync 47 [08-23 17:26:24.999]
,08-23 17:26:31.962   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:40.592   751   764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:42.012   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:52.062   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:26:55.002   751  1574 E Watchdog: !@Sync 48 [08-23 17:26:55.004]
,08-23 17:26:58.372  1666  1746 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 17:27:02.122   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:27:10.672   751  2070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:27:10.682   751  2070 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 17:27:10.682   751  2070 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-23 17:27:10.682   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:27:10.702   751   751 I MotionRecognitionService: Plugged
,08-23 17:27:10.702   751   751 D MotionRecognitionService:   cableConnection= 1
,08-23 17:27:10.702   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 17:27:10.702   751   751 D MotionRecognitionService: skip setTransmitPower. 
,08-23 17:27:10.712   751  2070 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 17:27:10.712   751  2070 D BatteryService: stay LED for fully charged
,08-23 17:27:10.722  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:27:10.722  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:27:10.722  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:27:10.752  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:27:10.752  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 17:27:10.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:27:10.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:27:10.752  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 17:27:12.172   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:27:22.222   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:27:25.002   751  1574 E Watchdog: !@Sync 49 [08-23 17:27:25.009]
,08-23 17:27:32.282   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-23 17:27:39.572   751  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:27:39.572   751  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:27:39.572   751  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1400000ms),08-23 17:27:40.752   751  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:27:40.762   751  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 17:27:40.762   751  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-23 17:27:40.762   751   751 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:27:40.782   751   751 I MotionRecognitionService: Plugged
08-23 17:27:40.782   751   751 D MotionRecognitionService:   cableConnection= 1
08-23 17:27:40.782   751   751 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 17:27:40.782   751   751 D MotionRecognitionService: skip setTransmitPower. 
08-23 17:27:40.792   751  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
08-23 17:27:40.792   751  1791 D BatteryService: stay LED for fully charged
08-23 17:27:40.802  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:27:40.802  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:27:40.802  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:27:40.812  2297  2297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:27:40.812  2297  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 17:27:40.822  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:27:40.822  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:27:40.832  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 17:27:42.332   751  3426 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
08-23 17:27:42.712   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
08-23 17:27:42.712   751  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
08-23 17:27:42.722   751  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-23 17:27:42.722   751  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-23 17:27:43.262  2309  2309 E audit   : type=1400 msg=audit(1471966063.262:293): avc:  denied  { execmod } for  pid=7220 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:27:43.272  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:27:43.272  2309  2309 E audit   : type=1300 msg=audit(1471966063.262:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4023000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=7220 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:27:43.272  2309  2309 E audit   : type=1327 msg=audit(1471966063.262:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 17:27:43.272  2309  2309 E audit   : type=1320 msg=audit(1471966063.262:293): 
08-23 17:27:43.322  2309  2309 E audit   : type=1400 msg=audit(1471966063.322:294): avc:  denied  { execmod } for  pid=7220 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:27:43.322  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:27:43.322  2309  2309 E audit   : type=1300 msg=audit(1471966063.322:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=7220 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:27:43.322  2309  2309 E audit   : type=1327 msg=audit(1471966063.322:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 17:27:43.322  2309  2309 E audit   : type=1320 msg=audit(1471966063.322:294): 
08-23 17:27:43.372  2309  2309 E audit   : type=1400 msg=audit(1471966063.362:295): avc:  denied  { execmod } for  pid=7220 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 17:27:43.372  2309  2309 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 17:27:43.372  2309  2309 E audit   : type=1300 msg=audit(1471966063.362:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3576 ppcomm=adbd pid=7220 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 17:27:43.372  2309  2309 E audit   : type=1327 msg=audit(1471966063.362:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 17:27:43.372  2309  2309 E audit   : type=1320 msg=audit(1471966063.362:295): 
08-23 17:27:43.372  7220  7220 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 17:27:43.392  7220  7220 D AndroidRuntime: CheckJNI is OFF
08-23 17:27:43.392  7220  7220 D AndroidRuntime: readGMSProperty: start
08-23 17:27:43.392  7220  7220 D AndroidRuntime: readGMSProperty: already setted!!
08-23 17:27:43.392  7220  7220 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 17:27:43.392  7220  7220 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 17:27:43.392  7220  7220 D AndroidRuntime: readGMSProperty: end
08-23 17:27:43.392  7220  7220 D AndroidRuntime: addProductProperty: start
08-23 17:27:43.402  7220  7220 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 17:27:43.402  7220  7220 W art     : aee4a000-b1d70000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:27:43.402  7220  7220 W art     : b1d70000-b3fdf000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:27:43.402  7220  7220 W art     : b3fdf000-b3fe0000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 17:27:43.402  7220  7220 W art     : b3fe0000-b3fe1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.402  7220  7220 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 17:27:43.402  7220  7220 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 17:27:43.402  7220  7220 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 17:27:43.402  7220  7220 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 17:27:43.402  7220  7220 W art     : b4889000-b48b2000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 17:27:43.402  7220  7220 W art     : b48b2000-b48b5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:27:43.402  7220  7220 W art     : b48b5000-b48b6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:27:43.402  7220  7220 W art     : b48b6000-b48b7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 17:27:43.402  7220  7220 W art     : b48b7000-b48b8000 r--p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b48b8000-b48d8000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 17:27:43.402  7220  7220 W art     : b48d8000-b52e9000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:27:43.402  7220  7220 W art     : b52e9000-b52ea000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b52ea000-b5333000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:27:43.402  7220  7220 W art     : b5333000-b5334000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 17:27:43.402  7220  7220 W art     : b5334000-b533c000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b533c000-b533d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.402  7220  7220 W art     : b533d000-b5372000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:27:43.402  7220  7220 W art     : b5372000-b5373000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5373000-b5374000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:27:43.402  7220  7220 W art     : b5374000-b5375000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 17:27:43.402  7220  7220 W art     : b5375000-b53cd000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 17:27:43.402  7220  7220 W art     : b53cd000-b53ce000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b53ce000-b53cf000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 17:27:43.402  7220  7220 W art     : b53cf000-b53d0000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 17:27:43.402  7220  7220 W art     : b53d1000-b53d7000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:27:43.402  7220  7220 W art     : b53d7000-b53d8000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:27:43.402  7220  7220 W art     : b53d8000-b53d9000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 17:27:43.402  7220  7220 W art     : b53d9000-b53db000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b53dc000-b53e6000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:27:43.402  7220  7220 W art     : b53e6000-b53e9000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:27:43.402  7220  7220 W art     : b53e9000-b53ea000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 17:27:43.402  7220  7220 W art     : b53eb000-b5402000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:27:43.402  7220  7220 W art     : b5402000-b5403000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5403000-b5404000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:27:43.402  7220  7220 W art     : b5404000-b5405000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 17:27:43.402  7220  7220 W art     : b5406000-b5410000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:27:43.402  7220  7220 W art     : b5410000-b5411000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:27:43.402  7220  7220 W art     : b5411000-b5412000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 17:27:43.402  7220  7220 W art     : b5412000-b5416000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:27:43.402  7220  7220 W art     : b5416000-b5417000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:27:43.402  7220  7220 W art     : b5417000-b5418000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 17:27:43.402  7220  7220 W art     : b5418000-b542e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 17:27:43.402  7220  7220 W art     : b542e000-b542f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 17:27:43.402  7220  7220 W art     : b542f000-b5430000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 17:27:43.402  7220  7220 W art     : b5430000-b543d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:27:43.402  7220  7220 W art     : b543d000-b543e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:27:43.402  7220  7220 W art     : b543e000-b543f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 17:27:43.402  7220  7220 W art     : b543f000-b549f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 17:27:43.402  7220  7220 W art     : b549f000-b54a2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 17:27:43.402  7220  7220 W art     : b54a2000-b54a6000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b54a6000-b5507000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 17:27:43.402  7220  7220 W art     : b5507000-b5508000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 17:27:43.402  7220  7220 W art     : b5508000-b5557000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:27:43.402  7220  7220 W art     : b5557000-b5559000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:27:43.402  7220  7220 W art     : b5559000-b555a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 17:27:43.402  7220  7220 W art     : b555a000-b555b000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b555b000-b5562000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 17:27:43.402  7220  7220 W art     : b5562000-b5563000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 17:27:43.402  7220  7220 W art     : b5563000-b5564000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 17:27:43.402  7220  7220 W art     : avc_common.so
08-23 17:27:43.402  7220  7220 W art     : b5565000-b5568000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 17:27:43.402  7220  7220 W art     : b5568000-b5569000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 17:27:43.402  7220  7220 W art     : b5569000-b556a000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 17:27:43.402  7220  7220 W art     : enc_common.so
08-23 17:27:43.402  7220  7220 W art     : b556b000-b556f000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 17:27:43.402  7220  7220 W art     : b556f000-b5570000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5570000-b5571000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 17:27:43.402  7220  7220 W art     : b5571000-b5572000 rw-p 00005000 b3:17 2510       /syste
08-23 17:27:43.402  7220  7220 W art     : m/lib/libpowermanager.so
08-23 17:27:43.402  7220  7220 W art     : b5573000-b5590000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:27:43.402  7220  7220 W art     : b5590000-b5591000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:27:43.402  7220  7220 W art     : b5591000-b5592000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 17:27:43.402  7220  7220 W art     : b5593000-b5598000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:27:43.402  7220  7220 W art     : b5598000-b5599000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:27:43.402  7220  7220 W art     : b5599000-b559a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 17:27:43.402  7220  7220 W art     : b559b000-b55cc000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:27:43.402  7220  7220 W art     : b55cc000-b55cf000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:27:43.402  7220  7220 W art     : b55cf000-b55d0000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 17:27:43.402  7220  7220 W art     : b55d1000-b560c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 17:27:43.402  7220  7220 W art     : b560c000-b560d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 17:27:43.402  7220  7220 W art     : b560d000-b560e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 17:27:43.402  7220  7220 W art     : b560f000-b5616000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:27:43.402  7220  7220 W art     : b5616000-b5617000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5617000-b5618000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:27:43.402  7220  7220 W art     : b5618000-b5619000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 17:27:43.402  7220  7220 W art     : b5619000-b561a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.402  7220  7220 W art     : b561a000-b5631000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:27:43.402  7220  7220 W art     : b5631000-b5632000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5632000-b5635000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:27:43.402  7220  7220 W art     : b5635000-b5636000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 17:27:43.402  7220  7220 W art     : b5636000-b5655000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:27:43.402  7220  7220 W art     : b5655000-b5656000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:27:43.402  7220  7220 W art     : b5656000-b5657000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 17:27:43.402  7220  7220 W art     : b5657000-b5695000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 17:27:43.402  7220  7220 W art     : b5695000-b5696000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5696000-b5698000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 17:27:43.402  7220  7220 W art     : b5698000-b5699000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 17:27:43.402  7220  7220 W art     : b569a000-b56a1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:27:43.402  7220  7220 W art     : b56a1000-b56a2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:27:43.402  7220  7220 W art     : b56a2000-b56a3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 17:27:43.402  7220  7220 W art     : b56a4000-b56a7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:27:43.402  7220  7220 W art     : b56a7000-b56a8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:27:43.402  7220  7220 W art     : b56a8000-b56a9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 17:27:43.402  7220  7220 W art     : b56a9000-b56af000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:27:43.402  7220  7220 W art     : b56af000-b56b0000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b56b0000-b56b1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:27:43.402  7220  7220 W art     : b56b1000-b56b2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 17:27:43.402  7220  7220 W art     : b56b2000-b56bb000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:27:43.402  7220  7220 W art     : b56bb000-b56bc000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:27:43.402  7220  7220 W art     : b56bc000-b56bd000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 17:27:43.402  7220  7220 W art     : b56bd000-b574e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:27:43.402  7220  7220 W art     : b574e000-b574f000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b574f000-b575a000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:27:43.402  7220  7220 W art     : b575a000-b575b000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 17:27:43.402  7220  7220 W art     : b575c000-b576e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 17:27:43.402  7220  7220 W art     : b576e000-b576f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 17:27:43.402  7220  7220 W art     : b576f000-b5770000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 17:27:43.402  7220  7220 W art     : b5771000-b5776000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:27:43.402  7220  7220 W art     : b5776000-b5777000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:27:43.402  7220  7220 W art     : b5777000-b5778000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 17:27:43.402  7220  7220 W art     : b5779000-b57e6000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:27:43.402  7220  7220 W art     : b57e6000-b57e7000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b57e7000-b57e9000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:27:43.402  7220  7220 W art     : b57e9000-b57ea000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 17:27:43.402  7220  7220 W art     : b57ea000-b57eb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.402  7220  7220 W art     : b57eb000-b57f2000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:27:43.402  7220  7220 W art     : b57f2000-b57f3000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:27:43.402  7220  7220 W art     : b57f3000-b57f4000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 17:27:43.402  7220  7220 W art     : b57f5000-b5875000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:27:43.402  7220  7220 W art     : b5875000-b5876000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5876000-b5877000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:27:43.402  7220  7220 W art     : b5877000-b5878000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 17:27:43.402  7220  7220 W art     : b5878000-b588f000 rw-p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b588f000-b58c6000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 17:27:43.402  7220  7220 W art     : ib/libqc-opt.so
08-23 17:27:43.402  7220  7220 W art     : b58c6000-b58c7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 17:27:43.402  7220  7220 W art     : b58c7000-b58c8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 17:27:43.402  7220  7220 W art     : b58c8000-b58e4000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:27:43.402  7220  7220 W art     : b58e4000-b58e5000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:27:43.402  7220  7220 W art     : b58e5000-b58e6000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 17:27:43.402  7220  7220 W art     : b58e7000-b5948000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 17:27:43.402  7220  7220 W art     : b5948000-b594a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 17:27:43.402  7220  7220 W art     : b594a000-b594b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 17:27:43.402  7220  7220 W art     : b594c000-b5973000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 17:27:43.402  7220  7220 W art     : b5973000-b5974000 ---p 00000000 00:00 0 
08-23 17:27:43.402  7220  7220 W art     : b5974000-b5975000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 17:27:43.402  7220  7220 W art     : b5975000-b5976000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 17:27:43.412  7220  7220 W art     : b5977000-b597f000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:27:43.412  7220  7220 W art     : b597f000-b5981000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:27:43.412  7220  7220 W art     : b5981000-b5982000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 17:27:43.412  7220  7220 W art     : b5983000-b5986000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 17:27:43.412  7220  7220 W art     : b5986000-b5987000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 17:27:43.412  7220  7220 W art     : b5987000-b5988000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 17:27:43.412  7220  7220 W art     : b5988000-b598c000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:27:43.412  7220  7220 W art     : b598c000-b598d000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b598d000-b598e000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:27:43.412  7220  7220 W art     : b598e000-b598f000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 17:27:43.412  7220  7220 W art     : b598f000-b599f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 17:27:43.412  7220  7220 W art     : b599f000-b59a0000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 17:27:43.412  7220  7220 W art     : b59a0000-b59a1000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 17:27:43.412  7220  7220 W art     : b59a1000-b59e7000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b59e7000-b59f0000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 17:27:43.412  7220  7220 W art     : b59f0000-b59f1000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 17:27:43.412  7220  7220 W art     : b59f1000-b59f2000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 17:27:43.412  7220  7220 W art     : b59f3000-b59f8000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 17:27:43.412  7220  7220 W art     : b59f8000-b59f9000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 17:27:43.412  7220  7220 W art     : b59f9000-b59fa000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 17:27:43.412  7220  7220 W art     : b59fa000-b59fd000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:27:43.412  7220  7220 W art     : b59fd000-b59fe000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b59fe000-b59ff000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:27:43.412  7220  7220 W art     : b59ff000-b5a00000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 17:27:43.412  7220  7220 W art     : b5a01000-b5a19000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:27:43.412  7220  7220 W art     : b5a19000-b5a1a000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5a1a000-b5a1b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:27:43.412  7220  7220 W art     : b5a1b000-b5a1c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 17:27:43.412  7220  7220 W art     : b5a1d000-b5bb7000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:27:43.412  7220  7220 W art     : b5bb7000-b5bb8000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5bb8000-b5bc5000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:27:43.412  7220  7220 W art     : b5bc5000-b5bc6000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 17:27:43.412  7220  7220 W art     : b5bc6000-b5bca000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 17:27:43.412  7220  7220 W art     : b5bca000-b5bcb000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5bcb000-b5bcc000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 17:27:43.412  7220  7220 W art     : b5bcc000-b5bcd000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 17:27:43.412  7220  7220 W art     : b5bcd000-b5be0000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:27:43.412  7220  7220 W art     : b5be0000-b5be1000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:27:43.412  7220  7220 W art     : b5be1000-b5be2000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 17:27:43.412  7220  7220 W art     : b5be2000-b5be3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:27:43.412  7220  7220 W art     : b5be3000-b5c2e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:27:43.412  7220  7220 W art     : b5c2e000-b5c2f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:27:43.412  7220  7220 W art     : b5c2f000-b5c30000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 17:27:43.412  7220  7220 W art     : b5c30000-b5c32000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5c33000-b5c44000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:27:43.412  7220  7220 W art     : b5c44000-b5c45000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5c45000-b5c46000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:27:43.412  7220  7220 W art     : b5c46000-b5c47000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 17:27:43.412  7220  7220 W art     : b5c48000-b5c52000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:27:43.412  7220  7220 W art     : b5c52000-b5c54000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:27:43.412  7220  7220 W art     : b5c54000-b5c55000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 17:27:43.412  7220  7220 W art     : b5c55000-b5c6e000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:27:43.412  7220  7220 W art     : b5c6e000-b5c6f000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:27:43.412  7220  7220 W art     : b5c6f000-b5c72000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 17:27:43.412  7220  7220 W art     : b5c72000-b5c76000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5c76000-b5cea000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 17:27:43.412  7220  7220 W art     : b5cea000-b5ceb000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5ceb000-b5cee000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 17:27:43.412  7220  7220 W art     : b5cee000-b5cef000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 17:27:43.412  7220  7220 W art     : b5cef000-b5cf0000 r--p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5cf0000-b5cf3000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:27:43.412  7220  7220 W art     : b5cf3000-b5cf4000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:27:43.412  7220  7220 W art     : b5cf4000-b5cf5000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 17:27:43.412  7220  7220 W art     : b5cf5000-b5cf6000 r--p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5cf6000-b5cfb000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:27:43.412  7220  7220 W art     : b5cfb000-b5cfc000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:27:43.412  7220  7220 W art     : b5cfc000-b5cfd000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 17:27:43.412  7220  7220 W art     : b5cfd000-b5cfe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b5cfe000-b5d01000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b5d01000-b5d02000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b5d02000-b5d03000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b5d03000-b5d04000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b5d04000-b5d08000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:27:43.412  7220  7220 W art     : b5d08000-b5d09000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:27:43.412  7220  7220 W art     : b5d09000-b5d0a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 17:27:43.412  7220  7220 W art     : b5d0a000-b5d0b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:27:43.412  7220  7220 W art     : b5d0b000-b5d0f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:27:43.412  7220  7220 W art     : b5d0f000-b5d10000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:27:43.412  7220  7220 W art     : b5d10000-b5d11000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 17:27:43.412  7220  7220 W art     : b5d11000-b5d12000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b5d12000-b5d20000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 17:27:43.412  7220  7220 W art     : b5d20000-b5d21000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b5d21000-b5d22000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 17:27:43.412  7220  7220 W art     : b5d22000-b5d23000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 17:27:43.412  7220  7220 W art     : b5d23000-b5d2d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:27:43.412  7220  7220 W art     : b5d2d000-b5d30000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:27:43.412  7220  7220 W art     : b5d30000-b5d31000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 17:27:43.412  7220  7220 W art     : b5d31000-b5d32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b5d32000-b5d3c000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 17:27:43.412  7220  7220 W art     : b5d3c000-b5d3f000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 17:27:43.412  7220  7220 W art     : b5d3f000-b5d40000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 17:27:43.412  7220  7220 W art     : b5d40000-b5d44000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:27:43.412  7220  7220 W art     : b5d44000-b5d45000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:27:43.412  7220  7220 W art     : b5d45000-b5d46000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 17:27:43.412  7220  7220 W art     : b5d46000-b5d47000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b5d47000-b5d54000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:27:43.412  7220  7220 W art     : b5d54000-b5d56000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:27:43.412  7220  7220 W art     : b5d56000-b5d57000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 17:27:43.412  7220  7220 W art     : b5d57000-b6169000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 17:27:43.412  7220  7220 W art     : b6169000-b616a000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b616a000-b6173000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 17:27:43.412  7220  7220 W art     : b6173000-b6177000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 17:27:43.412  7220  7220 W art     : b6177000-b6178000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6178000-b617f000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:27:43.412  7220  7220 W art     : b617f000-b6180000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:27:43.412  7220  7220 W art     : b6180000-b6181000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 17:27:43.412  7220  7220 W art     : b6181000-b6182000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6182000-b619d000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 17:27:43.412  7220  7220 W art     : b619d000-b619e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 17:27:43.412  7220  7220 W art     : b619e000-b619f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 17:27:43.412  7220  7220 W art     : b619f000-b61a0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b61a0000-b61ec000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:27:43.412  7220  7220 W art     : b61ec000-b61ed000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b61ed000-b61ee000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:27:43.412  7220  7220 W art     : b61ee000-b61ef000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 17:27:43.412  7220  7220 W art     : b61ef000-b61f0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b61f0000-b61f4000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:27:43.412  7220  7220 W art     : b61f4000-b61f5000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b61f5000-b61f6000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:27:43.412  7220  7220 W art     : b61f6000-b61f7000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 17:27:43.412  7220  7220 W art     : b61f7000-b622f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:27:43.412  7220  7220 W art     : b622f000-b6230000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:27:43.412  7220  7220 W art     : b6230000-b6231000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 17:27:43.412  7220  7220 W art     : b6231000-b6232000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6232000-b62d0000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 17:27:43.412  7220  7220 W art     : b62d0000-b62d1000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b62d1000-b62ef000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 17:27:43.412  7220  7220 W art     : b62ef000-b62f0000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 17:27:43.412  7220  7220 W art     : b62f0000-b6463000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:27:43.412  7220  7220 W art     : b6463000-b646e000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:27:43.412  7220  7220 W art     : b646e000-b646f000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 17:27:43.412  7220  7220 W art     : b646f000-b6586000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:27:43.412  7220  7220 W art     : b6586000-b6591000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:27:43.412  7220  7220 W art     : b6591000-b6592000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 17:27:43.412  7220  7220 W art     : b6592000-b6596000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6596000-b65ba000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 17:27:43.412  7220  7220 W art     : b65ba000-b65bc000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 17:27:43.412  7220  7220 W art     : b65bc000-b65bd000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 17:27:43.412  7220  7220 W art     : b65bd000-b6663000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 17:27:43.412  7220  7220 W art     : b6663000-b6670000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 17:27:43.412  7220  7220 W art     : b6670000-b6671000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 17:27:43.412  7220  7220 W art     : b6671000-b6672000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6672000-b66c5000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:27:43.412  7220  7220 W art     : b66c5000-b66c6000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b66c6000-b66c7000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:27:43.412  7220  7220 W art     : b66c7000-b66c8000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 17:27:43.412  7220  7220 W art     : b66c8000-b66cd000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b66cd000-b66df000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 17:27:43.412  7220  7220 W art     : b66df000-b66e0000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b66e0000-b66e1000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 17:27:43.412  7220  7220 W art     : b66e1000-b66e2000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 17:27:43.412  7220  7220 W art     : b66e2000-b66e9000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:27:43.412  7220  7220 W art     : b66e9000-b66ea000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:27:43.412  7220  7220 W art     : b66ea000-b66eb000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 17:27:43.412  7220  7220 W art     : b66eb000-b66ec000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b66ec000-b66ef000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 17:27:43.412  7220  7220 W art     : b66ef000-b66f0000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 17:27:43.412  7220  7220 W art     : b66f0000-b66f1000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 17:27:43.412  7220  7220 W art     : b66f1000-b66f5000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 17:27:43.412  7220  7220 W art     : b66f5000-b66f6000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 17:27:43.412  7220  7220 W art     : b66f6000-b66f7000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 17:27:43.412  7220  7220 W art     : b66f7000-b6705000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:27:43.412  7220  7220 W art     : b6705000-b6706000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6706000-b6707000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:27:43.412  7220  7220 W art     : b6707000-b6708000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 17:27:43.412  7220  7220 W art     : b6708000-b6711000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:27:43.412  7220  7220 W art     : b6711000-b6712000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:27:43.412  7220  7220 W art     : b6712000-b6713000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 17:27:43.412  7220  7220 W art     : b6713000-b6779000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 17:27:43.412  7220  7220 W art     : b6779000-b677a000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b677a000-b677c000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 17:27:43.412  7220  7220 W art     : b677c000-b6785000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 17:27:43.412  7220  7220 W art     : b6785000-b6788000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6788000-b681f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 17:27:43.412  7220  7220 W art     : b681f000-b6821000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 17:27:43.412  7220  7220 W art     : b6821000-b6822000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 17:27:43.412  7220  7220 W art     : b6822000-b6823000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6823000-b6b44000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 17:27:43.412  7220  7220 W art     : b6b44000-b6b45000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6b45000-b6b60000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 17:27:43.412  7220  7220 W art     : b6b60000-b6b64000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 17:27:43.412  7220  7220 W art     : b6b64000-b6b69000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6b69000-b6b71000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b6b71000-b6b72000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b6b72000-b6b73000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 17:27:43.412  7220  7220 W art     : b6b73000-b6ba1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:27:43.412  7220  7220 W art     : b6ba1000-b6ba2000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6ba2000-b6ba9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:27:43.412  7220  7220 W art     : b6ba9000-b6baa000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 17:27:43.412  7220  7220 W art     : b6baa000-b6bf0000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:27:43.412  7220  7220 W art     : b6bf0000-b6bf1000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6bf1000-b6bf4000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:27:43.412  7220  7220 W art     : b6bf4000-b6bf5000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 17:27:43.412  7220  7220 W art     : b6bf5000-b6c10000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 17:27:43.412  7220  7220 W art     : b6c10000-b6c14000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 17:27:43.412  7220  7220 W art     : b6c14000-b6c15000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 17:27:43.412  7220  7220 W art     : b6c15000-b6c62000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 17:27:43.412  7220  7220 W art     : b6c62000-b6c63000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6c63000-b6c6f000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 17:27:43.412  7220  7220 W art     : b6c6f000-b6c70000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 17:27:43.412  7220  7220 W art     : b6c70000-b6c7d000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 17:27:43.412  7220  7220 W art     : b6c7d000-b6c7e000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6c7e000-b6c7f000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 17:27:43.412  7220  7220 W art     : b6c7f000-b6c80000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 17:27:43.412  7220  7220 W art     : b6c80000-b6c88000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:27:43.412  7220  7220 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6c89000-b6c8a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:27:43.412  7220  7220 W art     : b6c8a000-b6c8b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 17:27:43.412  7220  7220 W art     : b6c8b000-b6c92000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:27:43.412  7220  7220 W art     : b6c92000-b6c93000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:27:43.412  7220  7220 W art     : b6c93000-b6c94000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 17:27:43.412  7220  7220 W art     : b6c94000-b6ca8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 17:27:43.412  7220  7220 W art     : b6ca8000-b6caa000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 17:27:43.412  7220  7220 W art     : b6caa000-b6cab000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 17:27:43.412  7220  7220 W art     : b6cab000-b6cd3000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:27:43.412  7220  7220 W art     : b6cd3000-b6cd5000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:27:43.412  7220  7220 W art     : b6cd5000-b6cd6000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 17:27:43.412  7220  7220 W art     : b6cd6000-b6cd9000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:27:43.412  7220  7220 W art     : b6cd9000-b6cda000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:27:43.412  7220  7220 W art     : b6cda000-b6cdb000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 17:27:43.412  7220  7220 W art     : b6cdb000-b6ce4000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:27:43.412  7220  7220 W art     : b6ce4000-b6ce5000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:27:43.412  7220  7220 W art     : b6ce5000-b6ce6000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 17:27:43.412  7220  7220 W art     : b6ce6000-b6d06000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 17:27:43.412  7220  7220 W art     : b6d06000-b6d07000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 17:27:43.412  7220  7220 W art     : b6d07000-b6d08000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 17:27:43.412  7220  7220 W art     : b6d08000-b6d7b000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 17:27:43.412  7220  7220 W art     : b6d7b000-b6d7f000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 17:27:43.412  7220  7220 W art     : b6d7f000-b6d82000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 17:27:43.412  7220  7220 W art     : b6d82000-b6d8c000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6d8c000-b6e14000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 17:27:43.412  7220  7220 W art     : b6e14000-b6e15000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6e15000-b6e19000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 17:27:43.412  7220  7220 W art     : b6e19000-b6e1a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 17:27:43.412  7220  7220 W art     : b6e1a000-b6e1b000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6e1b000-b6e44000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:27:43.412  7220  7220 W art     : b6e44000-b6e45000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6e45000-b6e48000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:27:43.412  7220  7220 W art     : b6e48000-b6e49000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 17:27:43.412  7220  7220 W art     : b6e49000-b6f23000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:27:43.412  7220  7220 W art     : b6f23000-b6f2a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:27:43.412  7220  7220 W art     : b6f2a000-b6f32000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 17:27:43.412  7220  7220 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:27:43.412  7220  7220 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 17:27:43.412  7220  7220 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6f36000-b6f39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6f39000-b6f5e000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 17:27:43.412  7220  7220 W art     : b6f5e000-b6f5f000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6f5f000-b6f66000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 17:27:43.412  7220  7220 W art     : b6f66000-b6f67000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 17:27:43.412  7220  7220 W art     : b6f67000-b6f6e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 17:27:43.412  7220  7220 W art     : b6f6e000-b6f6f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 17:27:43.412  7220  7220 W art     : b6f6f000-b6f70000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 17:27:43.412  7220  7220 W art     : b6f70000-b6f71000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6f71000-b6f89000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f89000-b6f8a000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6f8a000-b6f8b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f8b000-b6f8c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f8c000-b6f9a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f9a000-b6f9b000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6f9b000-b6f9c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f9c000-b6f9d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 17:27:43.412  7220  7220 W art     : b6f9d000-b6f9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:27:43.412  7220  7220 W art     : b6f9e000-b6fa0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6fa0000-b6fa1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6fa1000-b6fa2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 17:27:43.412  7220  7220 W art     : b6fa2000-b6fa3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 17:27:43.412  7220  7220 W art     : b6fa3000-b6fa4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 17:27:43.412  7220  7220 W art     : b6fa4000-b6fc4000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 17:27:43.412  7220  7220 W art     : b6fc4000-b6fc5000 r--p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6fc5000-b6fc6000 ---p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6fc6000-b6fc8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 17:27:43.412  7220  7220 W art     : b6fc8000-b6fc9000 r-xp 00000000 00:00 0          [sigpage]
08-23 17:27:43.412  7220  7220 W art     : b6fc9000-b6fe4000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 17:27:43.412  7220  7220 W art     : b6fe4000-b6fe5000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 17:27:43.412  7220  7220 W art     : b6fe5000-b6fe7000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 17:27:43.412  7220  7220 W art     : b6fe7000-b6fe9000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : b6fe9000-b6fee000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 17:27:43.412  7220  7220 W art     : b6fee000-b6fef000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 17:27:43.412  7220  7220 W art     : b6fef000-b6ff0000 rw-p 00000000 00:00 0 
08-23 17:27:43.412  7220  7220 W art     : bee67000-bee88000 rw-p 00000000 00:00 0          [stack]
08-23 17:27:43.412  7220  7220 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 17:27:43.462  7220  7220 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 17:27:43.502  7220  7220 I Radio-JNI: register_android_hardware_Radio DONE
08-23 17:27:43.512  7220  7220 E AffinityControl: AffinityControl: registerfunction enter
08-23 17:27:43.532  7220  7220 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 17:27:43.542   751  1663 D PackageManager: START PACKAGE DELETE: observer{236591509}
08-23 17:27:43.542   751  1663 D PackageManager: pkg{<packageName>}
08-23 17:27:43.542   751  1663 D PackageManager: user{0}
08-23 17:27:43.542   751  1663 D PackageManager: caller{2000}
08-23 17:27:43.542   751  1663 D PackageManager: flags{2}
08-23 17:27:43.542   751  1663 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 17:27:43.542   751  1663 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 17:27:43.542   751  1663 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 17:27:43.542   751  1663 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 17:27:43.542   751  1663 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 17:27:43.542   751   920 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 17:27:43.542   751   920 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 17:27:43.542   751   920 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 17:27:43.542   751   920 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 17:27:43.542   751   920 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-23 17:27:43.542   751   920 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 17:27:43.542   751   920 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 17:27:43.542   751   920 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-23 17:27:43.542   751   835 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-23 17:27:43.552   751   920 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 17:27:43.552   751   920 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest

```
